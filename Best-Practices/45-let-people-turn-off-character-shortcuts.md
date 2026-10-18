---
title: Let people turn off character shortcuts
tags: [practices, accessibility, keyboard, shortcuts]
status: verified
updated: 2026-10-17
---

# Let people turn off character shortcuts

A shortcut that is only a letter, number, punctuation mark, or symbol can be turned off, remapped to include a modifier, or limited to when its control has focus.

## When it applies

Use this when the product defines single-character shortcuts.

## The decision

- Offer one of the three: off, remap, or active only on focus.
- Do not let a speech-input user fire a shortcut by saying the letter.
- Confirm the current options before you implement only one of them.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "If a keyboard shortcut is implemented in content using only letter (including upper- and lower-case letters), punctuation, number, or symbol characters, then at least one of the following is true." Confirm the current page before you rely on it: [Let people turn off character shortcuts](https://www.w3.org/TR/WCAG22/#character-key-shortcuts).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
