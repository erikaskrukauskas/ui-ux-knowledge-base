---
title: Warn before input changes context
tags: [practices, accessibility, forms, context]
status: verified
updated: 2026-10-17
---

# Warn before input changes context

Changing a control does not automatically move the person to another context unless they were told before they used it.

## When it applies

Use this for a select, a radio group, or a toggle that might navigate or submit.

## The decision

- Keep the person on the task when they change a setting.
- If a change must navigate, say so in the label before they use the control.
- Prefer an explicit continue action.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "Changing the setting of any user interface component does not automatically cause a change of context unless the user has been advised of the behavior before using the component." Confirm the current page before you rely on it: [Warn before input changes context](https://www.w3.org/TR/WCAG22/#on-input).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
- [Name the outcome on the control](11-name-the-outcome-on-the-control.md)
