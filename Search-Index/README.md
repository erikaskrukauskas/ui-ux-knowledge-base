---
title: Search index
tags: [retrieval, search]
status: verified
updated: 2026-10-17
---

# Search index

Phase 1 retrieval is keyword search over the markdown in this repo. It uses the Python standard library. It does not need PostgreSQL, an embedding model, or a running server.

Semantic search and hybrid ranking belong with the MCP service in Phase 2. See [MCP-Server/README.md](../MCP-Server/README.md).

## Commands

From the repo root:

```powershell
python Search-Index/search.py --list
python Search-Index/search.py "keywords"
python Search-Index/search.py --tag accessibility
python Search-Index/search.py --status verified "usability"
```

`--list` prints every document's path, status, title, and tags. A query requires every keyword to appear in the file. `--tag` and `--status` filter YAML frontmatter. You can combine a status or a tag with keywords.

The script skips `.git`, `.venv`, `__pycache__`, and this `Search-Index` folder, so this page itself is not a search hit.

## How to think about a miss

A miss means no indexed page used those words. Try the words from the decision (`accessibility`, `empty`, `keyboard`, `usability`, `scope`) or list the catalog and open the closest title. Add the missing keywords to the page that should have matched, or write the page if the topic is new. See [Write searchable pages](../Best-Practices/08-write-searchable-pages.md).

## What this search will not do

- It does not search the AI knowledge base or other domain repos.
- It does not search the web or the official pages linked from this library.
- It does not rank by meaning. A synonym that never appears in the file will miss.
