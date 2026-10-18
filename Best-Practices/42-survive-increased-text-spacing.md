---
title: Survive increased text spacing
tags: [practices, accessibility, text, spacing]
status: verified
updated: 2026-10-17
---

# Survive increased text spacing

When the person increases line height, paragraph spacing, letter spacing, and word spacing to the values in the criterion, nothing they need is clipped and no action disappears.

## When it applies

Use this for text in a markup language that allows those style overrides. The page does not have to use those values itself.

## The decision

- Let the person's spacing win over a fixed box.
- The current values are line height 1.5, paragraph spacing 2, letter spacing 0.12, and word spacing 0.16, each times the font size.
- Confirm those values, and the exception for writing systems that do not use a property.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "No loss of content or functionality occurs by setting all of the following and by changing no other style property." Confirm the current page before you rely on it: [Survive increased text spacing](https://www.w3.org/TR/WCAG22/#text-spacing).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
