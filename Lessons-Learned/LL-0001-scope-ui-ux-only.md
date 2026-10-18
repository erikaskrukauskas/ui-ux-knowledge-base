---
id: LL-0001
title: Keep this repo to UI/UX knowledge
tags: [lessons, scope, governance]
status: verified
updated: 2026-10-17
environment: "Interface knowledge library on Windows; no single product brand"
scope: global
superseded_by:
---

# Keep this repo to UI/UX knowledge

## Problem

A shared library that also holds agent instructions, screen specs, API structure, research recordings, and release steps returns the wrong kind of answer. Someone looking for a reusable empty-state pattern would land on a product's brand decision, or on a note about how an agent should search.

## Approaches that failed

- Approach: Keep one library for interface practice, AI working method, application structure, and each product's screens.
- Why it failed: Those subjects change for different reasons and belong to different readers. Search results mix a reusable accessibility check with a product's copy and with tooling notes that another interface question cannot use.
- Evidence: Scope decision for this repository, 2026-10-17. See [SCOPE.md](../SCOPE.md).

## Working solution

Use this repository for interface and experience knowledge only: interaction design, information architecture, visual hierarchy, content design, accessibility, usability research method, design-system rules, and empty, loading, error, and success states.

Put agent briefing, search, comparison, verification, and lesson-recording practice in the AI knowledge base. Put architecture, APIs, state management, and code structure in the application-development repo. Put data science, data engineering, and CI/CD in their repos. Keep brand, screens, copy, research recordings, and local design-tool files in the product.

When one effort produces more than one kind of lesson, write the UI/UX lesson here and link the others.

## Verification

- Check run: Scope review against the repository decision and the folder layout.
- Result: Root docs and practice pages describe interface and experience practice. Agent tooling, implementation, and product brand appear as neighbors to link, not as practices stored here.

## Scope

`global` for any later product that consults this library.

## References

- [SCOPE.md](../SCOPE.md)
- [Separate practice from product](../Best-Practices/07-separate-practice-from-product.md)
