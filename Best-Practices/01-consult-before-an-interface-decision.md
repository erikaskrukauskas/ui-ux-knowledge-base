---
title: Consult before an interface decision
tags: [practices, retrieval, workflow]
status: verified
updated: 2026-10-17
---

# Consult before an interface decision

Search this library before a significant interface decision. Search the AI knowledge base when the question is how an agent should work. The two searches answer different questions.

## Choose the library

| Question | Search |
| --- | --- |
| How should this interaction, structure, hierarchy, content, or accessibility bar work? | This repo |
| How should an agent brief, search, compare, verify, or record work? | The AI knowledge base |
| How should the application, the data work, or the release be built? | That domain's knowledge repo |
| What did this product already decide about brand, copy, or screens? | That product |

A new product does not need a private copy of these practices. It needs a pointer to this checkout and a habit of searching it. The paste-ready pointer is the [consultation protocol](../Agent-Instructions/consultation-protocol.md).

On this machine the AI knowledge base is `C:\Users\erika\Cursor Projects\ai-knowledge-base`.

## Sequence

1. Name the user, the task, the constraint, and the decision you are about to make. See [Name the user, the task, and done](02-name-the-user-task-and-done.md).
2. Search this repo for an interface practice that applies.
3. Search the AI knowledge base when the question is how the agent should work.
4. Read the current official page when the decision depends on an accessibility criterion or a platform rule. See [Official documentation](../Official-Documentation/README.md).
5. Compare real interaction options when more than one pattern could finish the task. See [Compare interaction options](03-compare-interaction-options.md).
6. Design the states with the main path, meet the accessibility bar, and run the named check. See [Design states with the main path](04-design-states-with-the-main-path.md), [Meet accessibility expectations](05-meet-accessibility-expectations.md), and [Test the flow and record](06-test-the-flow-and-record.md).
7. Record a lesson when the finding will help a later product.

## What counts as significant

Search and compare when the work chooses an interaction pattern, an information architecture, a visual hierarchy rule, a content pattern, an accessibility bar, or a design-system rule that other screens will repeat.

A narrow visual tweak with one obvious edit can proceed from the screen in front of you. Record a lesson afterward if the finding is still useful once the product's brand is removed.

## Where the search is required

The project-start checklist makes the search part of kickoff. Use [Agent-Instructions/project-start-checklist.md](../Agent-Instructions/project-start-checklist.md) when a product should require it.
