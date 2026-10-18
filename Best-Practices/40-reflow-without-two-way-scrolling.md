---
title: Reflow without two-way scrolling
tags: [practices, accessibility, reflow, zoom, layout]
status: verified
updated: 2026-10-17
---

# Reflow without two-way scrolling

At a narrow width equivalent to 320 CSS pixels, content reflows so the person scrolls in one direction. The task and the information stay available. Maps, video, games, data tables, and a canvas that must keep its tools in view may keep two-dimensional scrolling.

## When it applies

Use this when a layout was designed wide and then zoomed or narrowed.

## The decision

- Reflow text and controls into one column of scrolling.
- Do not hide an action because it no longer fits the wide layout.
- Confirm the current pixel equivalents and the two-dimensional exceptions before you rely on the numbers.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "Content can be presented without loss of information or functionality, and without requiring scrolling in two dimensions." Confirm the current page before you rely on it: [Reflow without two-way scrolling](https://www.w3.org/TR/WCAG22/#reflow).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
- [Set visual hierarchy by importance](10-set-visual-hierarchy-by-importance.md)
