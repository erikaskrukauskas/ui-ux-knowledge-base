---
title: Do not remove a name from everyone
tags: [practices, accessibility, forms, labels]
status: verified
updated: 2026-10-19
---

# Do not remove a name from everyone

Hiding an element from view with the methods that also hide it from assistive technology removes the name for everyone.

## When it applies

Use this when you visually hide a label or a hint.

## The decision

- Keep the name available to assistive technology.
- Do not use a hide method that also removes it from the accessibility tree.
- Do not hide an interactive control that way. The control would stay active and unreachable.

## Evidence

W3C Web Accessibility Initiative, Labeling Controls: "Screen readers and other assistive technology, just as web browsers, hide elements from their users when they are styled using display: none; and visibility: hidden;." Confirm the current page before you rely on it: [Do not remove a name from everyone](https://www.w3.org/WAI/tutorials/forms/labels/).

## Related

- [Label or instruct before input](77-label-or-instruct-before-input.md)
