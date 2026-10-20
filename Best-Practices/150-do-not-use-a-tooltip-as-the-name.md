---
title: Do not use a tooltip as the name
tags: [practices, accessibility, forms, labels]
status: verified
updated: 2026-10-19
---

# Do not use a tooltip as the name

A tooltip is not the label. Some people never see it, and some tools never treat it as the name.

## When it applies

Use this when a field has no visible label and someone suggests a title or a hover tip.

## The decision

- Show the label.
- Use a tooltip only for extra, nonessential help.
- If the name must be visually hidden, hide it in a way assistive technology still reads.

## Evidence

W3C Web Accessibility Initiative, Labeling Controls: "This approach is generally less reliable and not recommended because some screen readers and assistive technologies do not interpret the title attribute as a replacement for the label element." Confirm the current page before you rely on it: [Do not use a tooltip as the name](https://www.w3.org/WAI/tutorials/forms/labels/).

## Related

- [Label or instruct before input](77-label-or-instruct-before-input.md)
