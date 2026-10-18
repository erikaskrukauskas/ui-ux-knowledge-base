---
title: Offer a non-drag way to do the same thing
tags: [practices, accessibility, drag, pointer]
status: verified
updated: 2026-10-17
---

# Offer a non-drag way to do the same thing

Anything the person does by dragging can also be done with a single pointer without dragging, unless dragging is essential.

## When it applies

Use this for reorder, sliders the product scripts, and drag-and-drop. A native control the product did not restyle can be the user-agent exception.

## The decision

- Offer buttons or a pick-and-place action for the same result.
- Do not make dragging the only path.
- Confirm the essential exception before a canvas truly requires a drag.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "All functionality that uses a dragging movement for operation can be achieved by a single pointer without dragging, unless dragging is essential or the functionality is determined by the user agent and not modified by the author." Confirm the current page before you rely on it: [Offer a non-drag way to do the same thing](https://www.w3.org/TR/WCAG22/#dragging-movements).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
