---
title: Write searchable pages
tags: [practices, retrieval, writing]
status: verified
updated: 2026-10-17
---

# Write searchable pages

Write so a later search can find the page, and so a later product can apply it without the original session.

## Frontmatter

Every markdown document starts with:

```yaml
---
title: Short specific title
tags: [practices, accessibility]
status: verified
updated: 2026-10-17
---
```

Lessons also include `id`, `environment`, `scope`, and `superseded_by`, as in the [lesson template](../Lessons-Learned/_template.md).

Tags are lowercase keywords a later search will use: `accessibility`, `keyboard`, `contrast`, `empty`, `error`, `usability`, `hierarchy`, `content`, `states`.

## One topic per page

Give a page one question to answer. A search hit should be a rule someone can apply. A diary of a whole study belongs in the product, split into the reusable findings before any of them are added here.

## Shape

- Open with the rule.
- Name the situation where it applies.
- Give the decision test or the steps.
- Name the evidence: the check, the official page, or the review.
- Link the canonical related page. Leave its text on that page.

## Titles and keywords

Use the words a future search will use. "Design states with the main path" can be found. "Notes" cannot. Put the important words in the title, the tags, and the opening: empty, loading, error, success, keyboard, label, contrast.

Search requires every keyword to appear in the file. A synonym that the file never uses will miss. When a page should have matched and did not, add the missing keywords to that page. See [Search index](../Search-Index/README.md).

## Maintenance

When guidance depends on a standard or a platform, update `updated` and re-check the official page named in the document. When a new page replaces an old one, set the old page to `superseded` and set `superseded_by` to the new path. Keep the old file so existing links still resolve.
