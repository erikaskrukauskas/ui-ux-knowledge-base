---
title: ChatGPT
tags: [agents, chatgpt]
status: verified
updated: 2026-10-17
---

# ChatGPT

ChatGPT uses the same practices and lessons. It does not read this checkout on its own.

## Now

Work that starts in ChatGPT can still use this library:

- Retrieve the relevant page locally with `Search-Index/search.py`.
- Paste the relevant section into the ChatGPT task, together with the file path.
- Ask ChatGPT to follow that section.

The file in this repo remains the source. A summary pasted into a chat is a copy for that task.

## Later

A local MCP configuration on this machine is not visible to ChatGPT. Remote use needs an authenticated connector and an explicit decision about which documents may leave the machine. That decision is Phase 4 in [MCP-Server/README.md](../MCP-Server/README.md).

## Same rules

ChatGPT output that will be reused still follows [Test the flow and record](../Best-Practices/06-test-the-flow-and-record.md). A suggestion becomes a lesson after the named usability or accessibility check. Questions about how ChatGPT should be briefed or verified are searched in the AI knowledge base.
