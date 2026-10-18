---
title: Make the focus indicator meet the appearance minimum
tags: [practices, accessibility, focus, contrast]
status: verified
updated: 2026-10-17
---

# Make the focus indicator meet the appearance minimum

When you draw the focus indicator, it is large enough and contrasts with the unfocused control. The current minimum is a 2 CSS pixel perimeter and 3:1 contrast between the focused and unfocused pixels, with the exceptions in the criterion.

## When it applies

Use this when the product changes the focus style. An untouched user-agent indicator is the exception.

## The decision

- Size the indicator at least as large as a 2 CSS pixel perimeter of the control.
- Contrast the focused and unfocused pixels at 3:1 or more.
- Confirm both numbers and the exceptions before you ship a custom ring.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "When the keyboard focus indicator is visible, an area of the focus indicator meets all the following." Confirm the current page before you rely on it: [Make the focus indicator meet the appearance minimum](https://www.w3.org/TR/WCAG22/#focus-appearance).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
