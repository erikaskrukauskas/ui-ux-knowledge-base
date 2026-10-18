---
title: Cursor
tags: [agents, cursor]
status: verified
updated: 2026-10-17
---

# Cursor

Cursor can edit this library and can consult it from other projects.

## This repo

`AGENTS.md` at the root tells an agent how to maintain the library: UI/UX knowledge only, frontmatter, lesson status, and no secrets, research recordings, copyrighted books, or verbatim manuals.

## Other projects

Add the [consultation protocol](consultation-protocol.md) to the project's `AGENTS.md`. That file remains after the chat ends. Keep the protocol short, and link the practice page in this repo when the project needs the full rule.

## Search from a project

From any working directory:

```powershell
python "<path-to-ui-ux-knowledge-base>\Search-Index\search.py" "empty error states"
```

Phase 2 can replace that command with an MCP tool. The practices stay the same when the protocol then says to call the knowledge search tool.

## How the agent should work

Current Cursor product behavior, and the practices for briefing, searching, comparing, verifying, and recording AI-assisted work, live in the AI knowledge base. Search that repo for those questions. This page only says how Cursor reaches the UI/UX library.
