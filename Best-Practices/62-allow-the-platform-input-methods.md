---
title: Allow the platform input methods
tags: [practices, accessibility, input, keyboard]
status: verified
updated: 2026-10-17
---

# Allow the platform input methods

The view does not turn off an input method the platform provides, unless the restriction is essential, required for security, or required to respect the person's settings.

## When it applies

Use this when a view might block a keyboard, a pointer, or speech.

## The decision

- Leave platform input methods available.
- A restriction that exists only to favor one input style is not essential.
- Confirm the security and user-setting exceptions before you block a method.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "Web content does not restrict use of input modalities available on a platform except where the restriction is essential, required to ensure the security of the content, or required to respect user settings." Confirm the current page before you rely on it: [Allow the platform input methods](https://www.w3.org/TR/WCAG22/#concurrent-input-mechanisms).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
