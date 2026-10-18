---
title: Test the flow and record
tags: [practices, usability, lessons, accessibility]
status: verified
updated: 2026-10-17
---

# Test the flow and record

A flow is done when the check you named has been run and the result matches the task. A lesson is reusable when that check succeeded and the write-up says what the check showed.

## Choose the check

Watch a person attempt the task when you can. Use a structured heuristic review when you cannot. Name the check before the work starts. See [Name the user, the task, and done](02-name-the-user-task-and-done.md).

A session with a person asks them to complete the task. Watch where they hesitate, what they misunderstand, and whether they can recover from empty, loading, error, and success. A recording of that session stays in the product. This repo receives the reusable finding, with identifying detail removed.

A heuristic review names the heuristics in advance and walks the whole flow, including the four states and the expectations in [Meet accessibility expectations](05-meet-accessibility-expectations.md). Looking only at the main screen leaves the rest of the task unchecked.

## Record a lesson when

- The finding would change how a later product designs the same kind of interaction.
- An approach failed for a reason another team would repeat.
- The working approach is still useful after the product's brand, copy, and screens are removed.
- A practice page was incomplete for a current accessibility criterion or platform rule.

Skip the lesson when the adjustment was obvious and local to one screen.

## What the lesson contains

Follow [Lessons-Learned/_template.md](../Lessons-Learned/_template.md).

- The interface situation: audience, platform, and assistive setup when that changes the finding.
- Approaches that failed, and what you observed.
- The working solution, written so another product can apply it.
- The check you ran and what it showed.
- Links to the practice page or the official page you confirmed.
- Scope: reusable interface practice, or a pointer to the product, the AI knowledge base, or another domain repo.

## Lifecycle

| Status | Meaning |
| --- | --- |
| `candidate` | Captured, and the check has not been repeated |
| `tested` | The check was run, or the evidence was reviewed, in this situation |
| `verified` | Reliable enough for another product to apply |
| `superseded` | Replaced by a named newer document |

Move status forward when you have evidence. Keep a superseded lesson, and set `superseded_by` so an old link still explains itself.

When a verified lesson has become a general rule, add that rule to `Best-Practices/` and leave the lesson as the evidence.

A person or an agent drafting a lesson may set `candidate` or `tested`. `verified` waits until the named check has been run. A later `record_lesson` tool follows the same rule. See [MCP server design](../MCP-Server/README.md).
