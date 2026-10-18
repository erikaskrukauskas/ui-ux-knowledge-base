---
title: Keep focus from being fully hidden
tags: [practices, accessibility, focus, keyboard]
status: verified
updated: 2026-10-17
---

# Keep focus from being fully hidden

When a control receives keyboard focus, author-created content does not hide it completely.

## When it applies

Use this for sticky headers, banners, and layers. Content the person opened may cover focus if they can reveal the control without moving focus. Confirm that note.

## The decision

- Keep the focused control at least partly visible.
- Test with the sticky regions in their initial positions.
- A visible focus indicator that sits underneath a banner still fails this criterion.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "When a user interface component receives keyboard focus, the component is not entirely hidden due to author-created content." Confirm the current page before you rely on it: [Keep focus from being fully hidden](https://www.w3.org/TR/WCAG22/#focus-not-obscured-minimum).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
