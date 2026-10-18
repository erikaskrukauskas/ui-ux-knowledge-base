---
title: Lessons learned
tags: [lessons, index]
status: verified
updated: 2026-10-17
---

# Lessons learned

Lessons are evidence from a real flow. Best-practice pages are the stable rules. A lesson becomes a practice page only after the finding holds beyond the original product.

## Lifecycle

`candidate` → `tested` → `verified`

| Status | Set it when |
| --- | --- |
| `candidate` | The finding is written down and has not been re-checked |
| `tested` | The usability or accessibility check was run, or the evidence was reviewed, in this situation |
| `verified` | Another product can apply it without repeating the dead ends |
| `superseded` | A newer lesson or practice page replaces it |

Superseded files stay in the folder. Set `superseded_by` to the replacement path.

## File names

`LL-0001-short-slug.md`

Increment the number. Keep each id unique.

## What to record

Use [_template.md](_template.md). A useful lesson names the interface situation, the approaches that failed, the working approach, and the check that showed it worked.

Record a UI/UX lesson here. When the same effort also produced an AI-tooling lesson, write that lesson in the AI knowledge base and link it. When it produced an implementation lesson, link the application-development repo. Leave research recordings of real users in the product.

## Current lessons

| ID | Title | Status |
| --- | --- | --- |
| [LL-0001](LL-0001-scope-ui-ux-only.md) | Keep this repo to UI/UX knowledge | verified |
