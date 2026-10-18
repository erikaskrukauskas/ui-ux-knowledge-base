---
title: Scope of this repository
tags: [scope, governance]
status: verified
updated: 2026-10-17
---

# Scope

This repository is the UI/UX knowledge base. Other projects read it for practices and verified lessons about interface and experience design.

## In this repo

- Interaction design: how a person moves through a task and recovers when it goes wrong.
- Information architecture: how tasks, objects, and navigation are grouped.
- Visual hierarchy: what is seen first, and what waits.
- Content design: labels, empty and error language, and the words on a control.
- Accessibility expectations for an interaction, including keyboard use, labels, contrast, and cues besides color.
- Usability research method: testing a flow with a person, or running a structured heuristic review, then recording the reusable finding.
- Design-system rules stated so another product can apply them.
- Empty, loading, error, and success states, designed with the main path.

## In other repos

| Topic | Where it lives |
| --- | --- |
| AI tooling, agent instructions, prompting, retrieval, and MCP | [AI knowledge base](https://github.com/erikaskrukauskas/ai-knowledge-base) |
| Application implementation: architecture, APIs, state management, and code structure | Its own knowledge repo |
| Data science | Its own knowledge repo |
| Data engineering | Its own knowledge repo |
| CI/CD and release automation | Its own knowledge repo |
| A product's brand, screens, copy, research recordings, and local design-tool files | That product |

On this machine the AI knowledge base checkout is `C:\Users\erika\Cursor Projects\ai-knowledge-base`.

A lesson about a screen layout, a component implementation, a model, a pipeline, or a deployment is recorded in the matching product or domain repo. If that work also produced a reusable interface lesson, write the interface lesson here and link the other write-up.

## Where a new note goes

Ask what a future product could reuse after this product's brand and constraints are removed.

- If the answer is a way of structuring a task, a state, a hierarchy, a content pattern, or an accessibility check, add it here.
- If the answer is how an agent should brief, search, compare, verify, or record work, add it to the AI knowledge base.
- If the answer depends on application structure, data science, data engineering, or release automation, add it to that repo.
- If the answer is this product's brand, copy, screens, or recordings, keep it in the product.
- If more than one of these is true, split the note. This repo keeps the interface practice. Each other repo keeps its own part.

## Promotion rule

A decision made inside one product becomes a page here only after the brand, the screens, the copy, and the local constraints are removed and the remaining statement is still useful. If nothing remains, leave it in the product.
