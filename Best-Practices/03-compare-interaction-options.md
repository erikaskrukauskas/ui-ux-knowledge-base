---
title: Compare interaction options
tags: [practices, interaction, workflow]
status: verified
updated: 2026-10-17
---

# Compare interaction options

For a significant interface choice, name the realistic options, the constraint that decides among them, and the option you will implement. Then implement that option.

## When to compare

Compare when more than one interaction could complete the task and the wrong pattern is expensive to unwind. Typical choices are navigation structure, the primary action, how secondary detail is disclosed, how a form reports problems, and a design-system rule other screens will copy.

## What a comparison contains

- Two or three options a person could actually use for this task.
- The constraint that decides: speed of the frequent case, recovery from a mistake, what must stay visible, keyboard reach, or how much the person must remember.
- The option you will implement.
- What you looked at: a practice page, a lesson, a current official guideline, or the existing flow.

A local tweak with one obvious edit can skip the write-up.

## Options are interactions

Describe what the person does and what the interface shows. These are the kinds of choices this page is for:

- Show every section at once, or reveal secondary sections after the person asks.
- Report a field problem as the person leaves the field, or report the problems when they try to finish.
- Keep the person in the current view, or move them to a dedicated step when the task needs full attention.

A design-tool name, a component-library name, or a frontend framework is not an interaction option. Official pages for platform conventions live under [Official documentation](../Official-Documentation/README.md).

## Then implement one

After the choice is made, carry that pattern through the main path and through empty, loading, error, and success. The flow uses the chosen pattern throughout.

Record the comparison in the product when it depends on that product's brand or constraints. Record it here only when the chosen practice still helps after those are removed. See [Separate practice from product](07-separate-practice-from-product.md).

## Check the current rule

When an option depends on a platform convention or an accessibility criterion, confirm the current official page before you treat it as the rule.
