---
title: Separate practice from product
tags: [practices, scope, lessons]
status: verified
updated: 2026-10-17
---

# Separate practice from product

Write each fact in the place where it stays true.

## Reusable interface practice

Lives in this repo when another product can still use it:

- How to structure a task, set visual hierarchy, write interface content, and choose an interaction.
- How to design empty, loading, error, and success with the main path.
- Accessibility expectations for an interaction: keyboard use, labels, contrast, and a cue besides color.
- How to run a usability check or a structured heuristic review, and how to record the lesson.
- Design-system rules stated without a vendor's component names.

## Product knowledge

Lives in the product:

- Brand, visual identity, and voice.
- Screens, flows, and the copy written for them.
- Research recordings of real users.
- Local design-tool files.
- Decisions that hold only under that product's constraints.

## Neighboring knowledge

| Topic | Where it lives |
| --- | --- |
| How an agent should brief, search, compare, verify, or record | AI knowledge base |
| Application architecture, APIs, state management, and code structure | Application-development repo |
| Data science | Its own knowledge repo |
| Data engineering | Its own knowledge repo |
| CI/CD and release automation | Its own knowledge repo |

The AI knowledge base on this machine is `C:\Users\erika\Cursor Projects\ai-knowledge-base` (https://github.com/erikaskrukauskas/ai-knowledge-base).

## Promotion rule

Move a product decision into this repo only after the brand, the copy, the screens, and the local constraints are removed and the remaining statement still helps another product. When nothing reusable remains, keep the decision in the product.

## One effort, more than one lesson

When the work teaches an interface lesson and an AI-tooling lesson, write the interface lesson here and link the AI knowledge base for the tooling lesson. When it also teaches an implementation lesson, link the application-development repo for that part. Each repo keeps its own lesson.
