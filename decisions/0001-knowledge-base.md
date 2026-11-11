# 0001 — A Git knowledge base as the single source of truth

**Date:** 2026-11-12
**Decided by:** Krischan
**Status:** accepted

## Context

The series lived in chats and a working document (the series bible, rev. 1 and rev. 2). Chat history does not carry over between sessions, tools or models.

## Decision

Keep everything in `s-ging/elsewhen-info` as Markdown, set up the same way as `s-ging/oshi-theater-info`. Adapted for a channel:

- `product/` became `series/`: the bible at the top, one folder per miniseries (`series/perlangan/`), one file per episode once it has a shot list.
- `project/scope.md` was dropped; the release order lives in `project/roadmap.md`.
- No performance or no-AI-art law carried over from the oshi theater; those are that product's rules, not this channel's.

## Why

A new chat or agent reads the repo and is up to speed. Git history shows what changed, when and why.

## Alternatives considered

- Project memory in one AI tool: does not carry over between tools, models or teammates.
