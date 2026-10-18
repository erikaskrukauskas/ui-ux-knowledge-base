---
title: Design states with the main path
tags: [practices, states, content, empty, error]
status: verified
updated: 2026-10-17
---

# Design states with the main path

Empty, loading, error, and success belong to the same task as the main path. Design them together, before the flow is called done.

## What each state answers

| State | The person needs to know |
| --- | --- |
| Empty | There is nothing here yet, and the first useful action |
| Loading | Work is in progress, and whether they should wait or can do something else |
| Error | What failed, whether their input is still there, and how to recover |
| Success | What finished, and the next action that follows from that result |

The main path answers a fifth question: how the person completes the task when the data is present and the system is responding.

## Write the state in the interface

- Say what happened in words. Color may support the message. A cue besides color carries the same message. See [Meet accessibility expectations](05-meet-accessibility-expectations.md).
- Offer one clear next action when the person can do something. Omit an action when they cannot take one.
- Keep what they entered when an error is about a field or a submission.
- Make a long wait distinguishable from a frozen screen. Show that progress is happening, and offer a way out when canceling is safe.
- Treat an empty collection as a starting point. Tell the person what will appear here and how to add the first item.

## Walk them as one flow

Review the task in this order: a first visit with nothing to show, a wait, a failed attempt, a completed attempt, and the ordinary case. Specify each state in the same pass as the main path so the words, the next action, and the hierarchy agree.

## What stays in the product

The exact sentences of one product stay in that product. This page keeps the question each state answers. When a product finds a reusable way to answer one of them, record the lesson and, once it holds beyond that product, fold the rule back into this page.
