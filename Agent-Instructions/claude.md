---
title: Claude Code
tags: [agents, claude]
status: verified
updated: 2026-10-17
---

# Claude Code

Claude Code should follow the same consultation steps as Codex. The global file is `CLAUDE.md`.

## Instructions

Add the [consultation protocol](consultation-protocol.md) to the global `CLAUDE.md`. Use the project's `CLAUDE.md` for constraints that are true only in that product.

Link a practice page instead of pasting the guide into `CLAUDE.md`. The canonical page stays in this repo.

## Search until MCP exists

```powershell
python "<path-to-ui-ux-knowledge-base>\Search-Index\search.py" --status verified "<keywords>"
```

Claude Code can use the same local MCP server as Codex once Phase 2 is built. Register that server in Claude's MCP configuration. It reads this library. It is not a second knowledge store.

Current Claude Code product behavior lives in the AI knowledge base. Search that repo for how the agent should brief, search, compare, verify, or record work.

## Lessons

When Claude finds a reusable interface result, it writes the lesson here with status `candidate` or `tested`, using the template. It sets `verified` only after the usability or accessibility check named in the lesson has been run. An AI-tooling lesson is written in the AI knowledge base.
