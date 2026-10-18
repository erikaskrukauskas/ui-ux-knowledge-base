---
title: Size targets so the neighbor is safe
tags: [practices, accessibility, target, spacing]
status: verified
updated: 2026-10-17
---

# Size targets so the neighbor is safe

A control is large enough to activate, or it has enough space around it that the person does not activate the control beside it.

## When it applies

Use this for pointer and touch targets the product draws. Confirm the current exceptions before you treat a target in a sentence, a user-agent control, an equivalent control, or an essential dense layout as exempt.

## The decision

- Give each target the minimum size in the current criterion, or space undersized targets so their required clearance does not overlap another target.
- Put the important actions on targets that meet the size, even when spacing would also pass.
- Do not count zoom as the way the target becomes large enough. The size is the size the page lays out.
- Apply the same rule to targets in a layer that opens over the page.

## Evidence

W3C, Understanding Success Criterion 2.5.8 Target Size (Minimum): "Ensure targets meet a minimum size or have sufficient spacing around them." That page currently sets the minimum at 24 by 24 CSS pixels, with a spacing alternative and named exceptions. Confirm the current size and exceptions before you rely on the number: [Target Size (Minimum)](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html).

## Related

- [Meet accessibility expectations](05-meet-accessibility-expectations.md)
- [Set visual hierarchy by importance](10-set-visual-hierarchy-by-importance.md)
