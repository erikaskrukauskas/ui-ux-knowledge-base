---
title: Wait to flag a format until the field is finished
tags: [practices, usability, forms, errors]
status: verified
updated: 2026-10-19
---

# Wait to flag a format until the field is finished

A format error waits until the person has finished the field. Checking every keystroke shows a false error.

## When it applies

Use this for a date, a code, or any value that is incomplete while they type.

## The decision

- Check when they leave the field or submit.
- Do not mark the field wrong on the first character.
- A check that can succeed while typing, such as a name that is already taken, can update quietly.

## Evidence

W3C Web Accessibility Initiative, User Notification: "In some cases, it does not make sense to check input as it is being typed by the user because it would display error messages most of the time." Confirm the current page before you rely on it: [Wait to flag a format until the field is finished](https://www.w3.org/WAI/tutorials/forms/notifications/).

## Related

- [Write the error where it happened](96-write-the-error-where-it-happened.md)
