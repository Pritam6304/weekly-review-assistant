# Weekly Review Assistant

Agent design for FlyRank AI Internship assignment **FL-06 — Design Your Personal Agent**.

The full deliverable is in [`AGENT_SPEC.md`](AGENT_SPEC.md). It specifies a scoped weekly review assistant, a local-first access plan, four narrow tools, draft instructions, six pre-build evaluation cases, guardrails, and a ten-hour scripted-Python build plan.

## Proposed MVP

The assistant reads user-provided Markdown notes plus exported `tasks.csv` and `calendar.csv` files, then drafts a source-linked weekly review and next-week plan. It does not send messages, modify calendars, create external tasks, publish content, or delete data.

## Why this platform

The design chooses a scripted Python agent because it is reproducible, privacy-conscious, testable with fixtures, and runnable without a paid SaaS workspace. A Claude Project with connectors was considered but deferred because it introduces account, plan, and connector-permission dependencies.

## Status

This repository contains the design specification only, as required by FL-06. Implementation is intentionally the next step after the pre-build eval cases are approved.
