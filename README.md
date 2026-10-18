---
title: UI/UX Knowledge Base
tags: [overview, interface, scope]
status: verified
updated: 2026-10-17
---

# UI/UX Knowledge Base

This repository is the shared library for interface and experience knowledge: how people find, understand, and complete a task. Other projects consult it for practices that still help after a product's brand, screens, and constraints are removed.

AI tooling, application implementation, data science, data engineering, and CI/CD keep their own repositories. This repo stores reusable interface practice. It does not store those domains, and it does not store one product's design files.

## What belongs here

- Practices for interaction design, information architecture, visual hierarchy, content design, accessibility, usability research, and design-system rules.
- How to design empty, loading, error, and success states together with the main path.
- Lessons from real interface work, after the named usability or accessibility check.
- Pointers to current accessibility standards, platform human-interface guidelines, and usability methods.
- Citations and original notes for interface references. Full books, ebooks, and PDFs stay out of git.

## How another project uses it

1. Point that project's agent instructions at this checkout. Copy the snippet from [Agent-Instructions/consultation-protocol.md](Agent-Instructions/consultation-protocol.md).
2. Search before a significant interface decision. Pass keywords that must all appear:

```powershell
python Search-Index/search.py "empty error states"
python Search-Index/search.py --tag accessibility
python Search-Index/search.py --list
```

3. Apply what is reusable. Leave brand, screens, copy, research recordings, and local design-tool files in the product repo.
4. After a checked UI/UX lesson, add a file under `Lessons-Learned/` using the template.

Questions about how an agent should brief, search, compare, verify, or record work belong in the [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base). Implementation, data, and release questions belong in those repos.

## Layout

| Path | Role |
| --- | --- |
| `Best-Practices/` | Stable interface and experience practices |
| `Lessons-Learned/` | Findings from real flows, and their validation state |
| `Agent-Instructions/` | Snippets for Cursor, Codex, Claude Code, and ChatGPT |
| `Official-Documentation/` | Links to current standards and platform guidelines |
| `Books/` | Citation and notes policy for references |
| `Search-Index/` | Local keyword search over this repo |
| `MCP-Server/` | Design for a later shared retrieval service |
| `AGENTS.md` | Rules for agents editing this repo |
| `SCOPE.md` | Boundary between this repo and sibling repos |

## Roadmap

| Phase | Outcome | State |
| --- | --- | --- |
| 1. Foundation | Folder layout, practices, lessons template, keyword search | In this repo |
| 2. MCP | Local MCP tools so an agent can search this library from any project | Designed, not built |
| 3. Lessons memory | Validation workflow, superseding, retrieval of verified lessons | Template and rules are in place |
| 4. Remote access | Authenticated access for an agent that cannot read a local checkout | Later, after a local workflow is proven |

## Principles

- Retrieve a relevant slice. Load the page that answers the decision, rather than the whole library.
- Record a lesson after the named usability or accessibility check. Mark a replacement as superseded.
- Keep one copy of each practice. Agent-specific files link to it.
- Keep a product's brand, screens, and research recordings in that product.
