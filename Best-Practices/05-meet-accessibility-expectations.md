---
title: Meet accessibility expectations
tags: [practices, accessibility, keyboard, contrast]
status: verified
updated: 2026-10-17
---

# Meet accessibility expectations

A significant interaction meets the accessibility expectations for that interaction before the work is called done. This library always names four: keyboard use, labels, contrast, and a cue that is not color alone.

## Keyboard use

A person who uses a keyboard can reach, operate, and leave every control the task requires. Focus order follows the task order. Focus is visible. When a layer holds focus, it also provides a way out.

## Labels

Every control has a name a person and assistive technology can use. The name says what the control does, and it remains available when a hint inside the control disappears. An icon-only control has a text name. Grouped fields name the group and the individual control.

## Contrast

Text, essential icons, and the focus indicator stay readable against their backgrounds for the conditions the task expects, including text on a button and a message on a tinted surface. Confirm the current contrast criterion on the official page before you treat a ratio as the rule. See [Official documentation](../Official-Documentation/README.md).

## A cue besides color

Error, success, selection, and other states are also carried by text, shape, position, or a symbol. Color may add emphasis. A color change by itself does not explain what changed.

## How to use a standard

Read the current accessibility standard for the criterion you are about to rely on. This page says what to check in this library. It is a local rule, and the standard remains the source for the criterion. If this page and the current standard disagree, the current standard wins. Update this page, or mark it superseded and point `superseded_by` at the replacement.

A platform human-interface guideline can add a convention for that platform. Confirm the current platform page the same way. A convention from one platform stays a hypothesis on another until you check that platform's page.

## The check

Name the check in the task: a pass through the flow by keyboard, a review of names and contrast, and a check that each state is understandable without color. Run that check before calling the work done. See [Test the flow and record](06-test-the-flow-and-record.md).
