---
title: Expose the current page in the menu
tags: [practices, accessibility, navigation, wayfinding]
status: verified
updated: 2026-10-19
---

# Expose the current page in the menu

When the current item must remain a link, its current state is still exposed.

## When it applies

Use this when the current item stays in the tab order.

## The decision

- Expose the current-page state on that item.
- Keep the visible current marker as well.
- Do not rely on color alone for the current item.

## Evidence

W3C Web Accessibility Initiative, Menu Structure: "Use the aria-current="page" attribute to indicate the current page in the menu." Confirm the current page before you rely on it: [Expose the current page in the menu](https://www.w3.org/WAI/tutorials/menus/structure/).

## Related

- [Show where the person is and how to go back](12-show-where-the-person-is.md)
