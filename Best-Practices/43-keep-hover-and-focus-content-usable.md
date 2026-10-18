---
title: Keep hover and focus content usable
tags: [practices, accessibility, hover, focus, tooltip]
status: verified
updated: 2026-10-17
---

# Keep hover and focus content usable

Extra content that appears on hover or focus can be dismissed, pointed at, and kept up until the person leaves it, dismisses it, or it becomes outdated.

## When it applies

Use this for a custom tooltip, a submenu, or any popup the product draws. A browser tooltip the product did not restyle is the user-agent exception.

## The decision

- Let the person dismiss the extra content without moving the pointer or the focus, unless it is an error message or it covers nothing.
- Let the pointer move onto the extra content without it vanishing.
- Leave it visible until the trigger ends, the person dismisses it, or the information is no longer valid.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "Where receiving and then removing pointer hover or keyboard focus triggers additional content to become visible and then hidden, the following are true." Confirm the current page before you rely on it: [Keep hover and focus content usable](https://www.w3.org/TR/WCAG22/#content-on-hover-or-focus).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
