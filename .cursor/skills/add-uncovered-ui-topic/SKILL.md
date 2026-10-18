---
name: add-uncovered-ui-topic
description: >-
  Add a missing interface or experience topic to this knowledge base after
  confirming no page covers it. Use when the user asks to document, add, or
  update the UI/UX knowledge base on a topic it does not yet cover, including
  interaction design, information architecture, visual hierarchy, content
  design, accessibility, usability research, design-system rules, or empty,
  loading, error, and success states.
---

# Add an uncovered interface topic

Add one topic this library does not yet answer. If a page already answers it, edit that page.

## Decide where it goes

Read [SCOPE.md](../../../SCOPE.md). Add the topic here when another product could reuse the interface practice after the brand, screens, and copy are removed.

Leave briefing, searching, comparing, verifying, and recording AI-assisted work to the AI knowledge base. Leave application implementation, data science, data engineering, and CI/CD to those repos. Leave brand, screens, copy, research recordings, and design-tool files in the product. If the request is out of scope, name the repo that should own it and stop.

## Confirm it is uncovered

```powershell
python Search-Index/search.py --list
python Search-Index/search.py "topic words"
```

Search `Best-Practices/`, `Lessons-Learned/`, `Official-Documentation/`, and `Agent-Instructions/`. A page that answers the question is covered. Edit that page. When the task is to refresh a covered page from current sources, use [review-covered-ui-topics](../review-covered-ui-topics/SKILL.md).

A near match is still covered when the gap is a paragraph. Add the paragraph on that page.

## Read the current source

Open the matching entry in [Official documentation](../../../Official-Documentation/README.md), then open the specific page for the criterion, platform rule, or method. Confirm that live page before writing the rule. Quote only the sentence needed, with the URL. Do not paste a standard, a guideline, or a book.

## Write one page

Follow [Write searchable pages](../../../Best-Practices/08-write-searchable-pages.md).

| Kind of knowledge | Where to put it |
| --- | --- |
| Stable rule for later products | Next numbered file in `Best-Practices/`, and a row in its README |
| How one agent reaches this library | The matching file in `Agent-Instructions/` |
| Finding from a checked flow | Next `LL-####` file, using `Lessons-Learned/_template.md` |

Set `status` to `verified` when a current official page supports the rule. Set `candidate` when the only support is a secondary article you have not confirmed. Do not mark a lesson `verified` unless the usability or accessibility check named in the lesson was run.

One topic per page. Link the related practice. Set `updated` to the day you write it.

## Report

```markdown
# Topic added
- Page:
- Why it was uncovered:
- Official page: [title](url)
- Status:
```

If you refused the topic, say where it belongs.
