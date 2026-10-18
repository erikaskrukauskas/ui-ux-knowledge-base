---
title: Consultation protocol
tags: [agents, retrieval, workflow]
status: verified
updated: 2026-10-17
---

# Consultation protocol

Paste this into a project's `AGENTS.md` or `CLAUDE.md`. Replace both path placeholders with the local checkouts.

```markdown
## UI/UX knowledge base

Shared interface and experience practices live in `<path-to-ui-ux-knowledge-base>`.
Questions about how an agent should work are searched in `<path-to-ai-knowledge-base>`.
Application implementation, data science, data engineering, and CI/CD live in those repos. Brand, screens, copy, and research stay in the product.

Before a significant interface decision:

1. UI/UX questions are searched in this repo.
   `python "<path-to-ui-ux-knowledge-base>\Search-Index\search.py" "<keywords>"`
2. Questions about briefing, searching, comparing, verifying, or recording AI-assisted work are searched in the AI knowledge base.
   `python "<path-to-ai-knowledge-base>\Search-Index\search.py" "<keywords>"`
3. Application implementation, data science, data engineering, and CI/CD questions go to those repos.
4. Significant interface choices name the options, then implement one.
5. The named usability or accessibility check is run before the work is called done.
6. A reusable UI/UX lesson is written here. An AI-tooling lesson is written in the AI knowledge base.
```

In the snippet above, "this repo" and "here" mean the UI/UX knowledge base at `<path-to-ui-ux-knowledge-base>`.

Significant means an interaction pattern, an information architecture, a visual hierarchy rule, a content pattern, an accessibility bar, or a design-system rule that other screens will repeat. A narrow local edit with one obvious change can proceed from the screen at hand.

Apply a lesson when its status is `verified` and the interface situation still matches. When a lesson and a current official page disagree about a criterion or a platform rule, the current official page wins.
