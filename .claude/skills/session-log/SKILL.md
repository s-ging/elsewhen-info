---
name: session-log
description: Write the end-of-session log and update project status in the Elsewhen knowledge base. Use at the end of any session that changed something, or when asked to log what happened.
---

# Session log

0. If you do not yet know who you are working with in this session, ask. Never take the name from the account, email or git config.
1. Copy `templates/log.md` to `logs/YYYY-MM-DD-short-topic.md` (today's date in Asia/Manila). Fill in every section; write "nothing" under Changed if read-only.
2. Add a row at the top of the table in `logs/README.md`.
3. Update `project/status.md` and its "Last updated" date. Newest items at the top; when an item is finished, move it to the top of "Done" as `- [x] YYYY-MM-DD ...` with a link. Never delete checklist items.
4. If the series changed, update `series/bible.md` or the miniseries files. Mark what Krischan decided apart from what an agent proposed.
5. If a choice someone might later undo was made, or an idea dropped, add a decision in `decisions/` and list it in `decisions/README.md`.
6. Move answered questions out of `project/open-questions.md` into the file where the answer belongs.
7. Commit and push.

Never write plain-text passwords or keys. Never rewrite an old log.
