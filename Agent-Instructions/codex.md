---
title: Codex
tags: [agents, codex]
status: verified
updated: 2026-10-17
---

# Codex

Codex should use the same UI/UX library as Cursor and Claude Code. Put the shared steps where Codex will read them for every project, and point that file at this checkout.

## Instructions

Include the [consultation protocol](consultation-protocol.md) in Codex's global agent instructions so a new project inherits the search. Keep that file short and point at this repo for the practices. Add the [project-start checklist](project-start-checklist.md) in a product that should require the search at kickoff.

## What Codex reads

- This repo for interaction, hierarchy, content, accessibility, and usability checks.
- The AI knowledge base for how to brief, search, compare, verify, and record AI-assisted work, including current Codex product behavior.
- The matching domain repo for application implementation, data science, data engineering, or CI/CD.
- The product for brand, screens, copy, and local decisions.

Codex should consult this checkout. A second copy of the practices inside each product will drift.

## Search until MCP exists

```powershell
python "<path-to-ui-ux-knowledge-base>\Search-Index\search.py" --status verified "usability"
```

When the local MCP server in [MCP-Server/README.md](../MCP-Server/README.md) exists, register it in the global Codex configuration. Until then, run the search script.
