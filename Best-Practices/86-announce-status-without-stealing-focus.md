---
title: Announce status without stealing focus
tags: [practices, accessibility, status, errors]
status: verified
updated: 2026-10-17
---

# Announce status without stealing focus

A status message is exposed so assistive technology can speak it without moving focus onto it.

## When it applies

Use this for a confirmation, a search-result count, or a progress update that appears away from the focused control.

## The decision

- Expose the message as a status.
- Leave focus where the person is working.
- A message that is only a color change is not announced. Pair it with text.

## Evidence

W3C Recommendation, WCAG 2.2, 12 December 2024: "In content implemented using markup languages, status messages can be programmatically determined through role or properties such that they can be presented to the user by assistive technologies without receiving focus." Confirm the current page before you rely on it: [Announce status without stealing focus](https://www.w3.org/TR/WCAG22/#status-messages).

## Related

- [Design states with the main path](04-design-states-with-the-main-path.md)
- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
