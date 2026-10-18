---
title: Offer a keyboard way out
tags: [practices, accessibility, keyboard, focus]
status: verified
updated: 2026-10-17
---

# Offer a keyboard way out

If a person can move keyboard focus into a component, they can move it out with the keyboard. If the way out is not the usual keys, the interface tells them how.

## When it applies

Use this for a dialog, a custom widget, or any region that might hold focus. A layer that traps focus without an announced exit fails the task.

## The decision

- Provide a keyboard exit from every region the keyboard can enter.
- Use the standard keys when you can.
- When the exit is a different key, say so where the person will find it before they are stuck.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "If keyboard focus can be moved to a component of the page using a keyboard interface, then focus can be moved away from that component using only a keyboard interface, and, if it requires more than unmodified arrow or tab keys or other standard exit methods, the user is advised of the method for moving focus away." Confirm the current page before you rely on it: [Offer a keyboard way out](https://www.w3.org/TR/WCAG22/#no-keyboard-trap).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
