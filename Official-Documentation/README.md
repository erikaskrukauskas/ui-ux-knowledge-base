---
title: Official documentation
tags: [documentation, accessibility, sources]
status: verified
updated: 2026-10-17
---

# Official documentation

Standards and platform guidelines change. Link the current official page, and record the date you checked it. Confirm that page before you rely on a criterion or a platform rule. Do not paste the manual into this repo.

When a practice page and an official page disagree about a criterion or a platform rule, the current official page wins. Update the practice page, or mark it `superseded` and set `superseded_by`.

Checked as entry points on 2026-10-17. Open the live page again before you apply a specific rule.

## Accessibility standards

| Source | Entry | Use for |
| --- | --- | --- |
| W3C Web Content Accessibility Guidelines (WCAG) | https://www.w3.org/WAI/standards-guidelines/wcag/ | The current accessibility standard and its criteria |
| WAI-ARIA | https://www.w3.org/WAI/standards-guidelines/aria/ | Names, roles, and states exposed to assistive technology |

## Platform human-interface guidelines

| Source | Entry | Use for |
| --- | --- | --- |
| Apple Human Interface Guidelines | https://developer.apple.com/design/human-interface-guidelines/ | Apple platform conventions |
| Android design | https://developer.android.com/design | Android platform conventions |
| Material Design | https://m3.material.io/ | Material interaction and layout guidance |
| Windows app design | https://learn.microsoft.com/en-us/windows/apps/design/ | Windows app conventions |

A convention from one platform applies to that platform. Check the other platform's page before you reuse it.

## Usability methods

| Source | Entry | Use for |
| --- | --- | --- |
| Nielsen Norman Group, 10 usability heuristics | https://www.nngroup.com/articles/ten-usability-heuristics/ | A structured heuristic review |
| usability.gov methods | https://www.usability.gov/how-to-and-tools/methods/index.html | Method overviews for planning a usability check |

These rows are starting points. They are not a frozen specification, and they are not a substitute for the check named in the task.

## Keeping the library current

- A topic this repo does not yet cover: `.cursor/skills/add-uncovered-ui-topic/SKILL.md`
- Whether a page already here still matches the sources above: `.cursor/skills/review-covered-ui-topics/SKILL.md`

A covered-topic review writes its report under `Official-Documentation/updates/`.

## How to add a source

Add a row with the official entry URL, the date you checked it, and the decision it supports. Keep AI product docs in the AI knowledge base. Keep implementation, data, and release docs in those repos.

## Local notes

A short note about one official page may sit next to this README:

- Name it for the topic, such as keyboard focus or contrast, rather than for the whole standard.
- State the date you checked the page.
- Quote only the minimum needed to support a decision, with the URL.
- Link the note from the practice or lesson that depends on it.
