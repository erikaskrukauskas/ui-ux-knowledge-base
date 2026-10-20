---
title: Separate a parent link from its submenu control
tags: [practices, accessibility, navigation]
status: verified
updated: 2026-10-19
---

# Separate a parent link from its submenu control

When the parent item itself goes somewhere, a separate control opens and closes the submenu.

## When it applies

Use this when the parent is both a destination and the owner of children.

## The decision

- Let the parent navigate.
- Give the submenu its own button.
- Do not make one control both follow the link and toggle the children.

## Evidence

W3C Web Accessibility Initiative, Fly-out Menus: "For situations when the parent menu item needs to carry out a function, such as linking to a web page, a separate button can be added to the parent item, to open and close the submenu." Confirm the current page before you rely on it: [Separate a parent link from its submenu control](https://www.w3.org/WAI/tutorials/menus/flyout/).

## Related

- [Keep repeated navigation in the same order](72-keep-repeated-navigation-in-the-same-order.md)
