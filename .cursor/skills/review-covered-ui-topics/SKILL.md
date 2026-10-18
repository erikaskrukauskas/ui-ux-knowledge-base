---
name: review-covered-ui-topics
description: >-
  Review accessibility standards, platform human-interface guidelines, and
  usability methods for changes to interface topics this knowledge base
  already documents, then update those pages. Use when the user asks to
  review covered topics, refresh existing UI/UX practices against current
  sources, or check whether documented guidance is outdated.
---

# Review covered interface topics

Start from the pages already in this repo. Check whether the current official pages still agree with them. A topic this repo does not yet cover uses [add-uncovered-ui-topic](../add-uncovered-ui-topic/SKILL.md).

## List the covered topics

```powershell
python Search-Index/search.py --list
```

Review `Best-Practices/` and verified files in `Lessons-Learned/`. Skip `Lessons-Learned/_template.md`, files with `status: superseded`, and files in `Official-Documentation/updates/`.

For each page, note the claim a source could change: an accessibility criterion, a platform convention, a usability method, or a rule written as current.

## Check the sources for those claims

Use the entry points in [Official documentation](../../../Official-Documentation/README.md):

- Accessibility: WCAG and WAI-ARIA
- Platform guidelines: Apple, Android, Material, and Windows
- Usability methods: Nielsen Norman Group heuristics and usability.gov

Open the live page and read the section that matches the claim. Confirm that page before you change a criterion or a platform rule.

A blog post or a book does not change a practice page. Confirm the claim on the official page first.

An official change that does not touch a covered claim is outside this review.

## Update the page

Edit the existing page when the current official page contradicts or extends that claim. Set `updated` to today. Keep `status` unless the page is wrong enough to mark `superseded`, with `superseded_by` pointing at the replacement.

Do not add a new topic during this review. Do not paste a standard or a guideline into the repo. Quote only the sentence needed, with the URL.

A guideline change is not a lesson. Add a lesson only when a flow was checked against the change.

## Report

Write the report to `Official-Documentation/updates/YYYY-MM-DD-covered-topics.md` with frontmatter `title`, `tags: [documentation, updates]`, `status: verified`, and `updated`. Put the same report in the chat:

```markdown
# Covered topic review
Checked: YYYY-MM-DD

## Updated
- **Page** — what the source changed — [url](url)

## Still current
- Page — source checked

## Unconfirmed
- Page — claim that could not be checked, and which source failed
```
