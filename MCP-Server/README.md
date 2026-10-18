---
title: MCP server design
tags: [mcp, retrieval, roadmap]
status: candidate
updated: 2026-10-17
---

# MCP server

Phase 2 adds a local MCP server so an agent can search this library from any project. Phase 1 uses [Search-Index/search.py](../Search-Index/search.py). This page is the contract to build against. The server is not implemented.

## Why a server later

Keyword search already works on one machine. An MCP server is worth adding when an agent in another project should call a tool instead of remembering a Python path. PostgreSQL and pgvector are worth adding when keyword search misses useful pages often enough to matter. Those pieces are not part of this phase.

## Proposed tools

| Tool | Purpose |
| --- | --- |
| `search_knowledge` | Keyword search first, hybrid search later. Returns paths, titles, status, and a short snippet. |
| `get_document` | Return one markdown file by its path relative to this repo. |
| `list_lessons` | Filter lessons by status, tag, and environment. |
| `record_lesson` | Create a `candidate` lesson from the template. It must not set `verified`. |

`record_lesson` may write the new file for review. Verification still requires the usability or accessibility check named in the lesson. See [Test the flow and record](../Best-Practices/06-test-the-flow-and-record.md).

Tools read and write only this repository. They do not search the AI knowledge base or other domain repos unless a later, explicit tool is added for that.

## Deployment order

1. A local process on this PC, started by the agent client, with the repo path as configuration.
2. Optional packaging after the tools are stable.
3. Authenticated remote access only after you decide which documents may leave the machine.

ChatGPT does not automatically see a local MCP server. Remote access is a separate phase and needs an approved connector. See [ChatGPT](../Agent-Instructions/chatgpt.md).

## Data rules the server must keep

- Index markdown in this library. Leave `.env` files, PDFs, research recordings, and design-tool files out of the index.
- Return `superseded` documents only when the query asks for them.
- Include `status` on every hit so the caller can prefer `verified`.
- Refuse secret-shaped values in `record_lesson`.
- Refuse a lesson body that is a research recording or a verbatim manual. The lesson states the reusable interface finding.

## Open choices

- Which embedding model to use, and whether pgvector runs locally.
- Whether `record_lesson` commits the new file or only writes it for review. Either way, the status it writes is `candidate`.
- The auth design for any future remote API.

Resolve those when Phase 2 starts, using what Phase 1 search shows about missed pages.
