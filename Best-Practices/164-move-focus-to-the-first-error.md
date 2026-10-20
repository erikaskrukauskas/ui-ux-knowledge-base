---
title: Move focus to the first error
tags: [practices, accessibility, forms, errors]
status: verified
updated: 2026-10-19
---

# Move focus to the first error

After a failed submission, focus moves to the first place that contains an error.

## When it applies

Use this when the person submits and the view stays put.

## The decision

- Move focus to the summary or the first failing group.
- Keep every answer they typed.
- Do not leave focus on the submit control while the errors are elsewhere.

## Evidence

W3C Web Accessibility Initiative, User Notification: "If the submitted data contains errors, it is convenient to set the focus to the first fieldset element that contains an error." Confirm the current page before you rely on it: [Move focus to the first error](https://www.w3.org/WAI/tutorials/forms/notifications/).

## Related

- [Identify an input error in text](76-identify-an-input-error-in-text.md)
