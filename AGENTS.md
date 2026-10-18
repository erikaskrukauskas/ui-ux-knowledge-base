---
title: Agent rules for this repository
tags: [agents, governance]
status: verified
updated: 2026-10-17
---

# Agent rules

You are in the UI/UX knowledge base. Other projects consult this repo for interface and experience practices. AI tooling, application implementation, data science, data engineering, and CI/CD have their own repos.

## While editing this repo

- Add or update UI/UX knowledge only. Read [SCOPE.md](SCOPE.md) before creating a document.
- Put stable guidance in `Best-Practices/`. Put findings from real flows in `Lessons-Learned/`.
- Give every document YAML frontmatter with `title`, `tags`, `status`, and `updated`.
- Lessons also have `id`, `environment`, `scope`, and `superseded_by`.
- Keep one canonical copy of a practice. Link to it from agent-specific files.
- Questions about briefing, searching, comparing, verifying, or recording AI-assisted work belong in the AI knowledge base at `C:\Users\erika\Cursor Projects\ai-knowledge-base`. Link that repo. Do not restate its practices here.
- Do not commit secrets, research recordings of real users, copyrighted books, or verbatim manuals.
- Do not commit or push unless the task explicitly asks for that.
- Do not present an unchecked finding as `verified`. Use the lifecycle in [Lessons-Learned/README.md](Lessons-Learned/README.md).
- When a newer document replaces an older one, set the old document to `superseded` and point `superseded_by` at the replacement. Keep the old file.

## Status values

`candidate` → `tested` → `verified`

Use `superseded` when a newer document replaces this one. Past references still resolve.

## Before you finish a documentation change

Search for an existing page on the same topic:

```powershell
python Search-Index/search.py --list
python Search-Index/search.py "your topic"
```

Update the existing page when the topic already exists. Tags are lowercase search words. One topic per page.
