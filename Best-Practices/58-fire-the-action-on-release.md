---
title: Fire the action on release
tags: [practices, accessibility, pointer, errors]
status: verified
updated: 2026-10-17
---

# Fire the action on release

A single-pointer control completes on the up event, and the person can abort or undo it. Completing on the down event is only for a function where that timing is essential, such as a keyboard emulator.

## When it applies

Use this for buttons and other pointer targets.

## The decision

- Do not commit the action on press alone.
- Let the person drag away and release to cancel, or undo after the action.
- Confirm the essential exception before a press-down action commits.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "The down-event of the pointer is not used to execute any part of the function." Confirm the current page before you rely on it: [Fire the action on release](https://www.w3.org/TR/WCAG22/#pointer-cancellation).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
- [Confirm only what is hard to undo](18-confirm-only-what-is-hard-to-undo.md)
