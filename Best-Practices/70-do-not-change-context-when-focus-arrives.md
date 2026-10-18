---
title: Leave the context alone when focus arrives
tags: [practices, accessibility, focus, context]
status: verified
updated: 2026-10-17
---

# Leave the context alone when focus arrives

Moving focus to a control does not, by itself, open a new view, submit a form, or otherwise change context.

## When it applies

Use this for every focusable control.

## The decision

- Focus may highlight and may show the extra content allowed by the hover-and-focus rule.
- A change of context waits for an explicit activation.
- Confirm what the current criterion counts as a change of context.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "When any user interface component receives focus, it does not initiate a change of context." Confirm the current page before you rely on it: [Leave the context alone when focus arrives](https://www.w3.org/TR/WCAG22/#on-focus).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
