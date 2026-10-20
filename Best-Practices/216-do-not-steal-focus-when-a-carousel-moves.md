---
title: Do not steal focus when a carousel moves
tags: [practices, accessibility, navigation, keyboard]
status: verified
updated: 2026-10-19
---

# Do not steal focus when a carousel moves

An automatic slide change leaves focus where the person already is. Previous and next do not move focus either.

## When it applies

Use this for a carousel with automatic motion or with previous and next controls.

## The decision

- Do not pull focus to the new slide when it advances on its own.
- Do not move focus when they use previous or next. They are browsing.
- Move focus to the chosen item only when they pick that item from the item list.

## Evidence

W3C Web Accessibility Initiative, Carousel Functionality: "When the carousel advances automatically, users should not be drawn away from their current place in the page." Confirm the current page before you rely on it: [Do not steal focus when a carousel moves](https://www.w3.org/WAI/tutorials/carousels/functionality/).

## Related

- [Operate every function from the keyboard](109-operate-every-function-from-the-keyboard.md)
