# Elsewhen knowledge base

This repository is the single source of truth for **Elsewhen**: a faceless short-form channel of alternate-history miniseries, styled like strategy-game cutscenes. Every AI agent (Claude Code or any other) and every teammate reads this file first.

If you are a new session: read this file, then [README.md](README.md), then [project/status.md](project/status.md). For any writing work, also read [series/bible.md](series/bible.md). Go deeper through the [map](#where-to-look) only as the task needs.

**Sync both ways.** Other sessions, agents and teammates edit this repository too. At the start of every session, pull the latest version (`git pull`) before reading or writing. At the end of any session that changed something, commit and push. Work that stays in a chat and never reaches this repository is lost.

## Absolute law

Do not break these rules. If anything elsewhere in this repository disagrees with this section, this section wins. If unsure, stop and ask, and do not take the looser reading.

### Who you are working with

Accounts may be shared, so the account name, email or git config does not tell you who is at the keyboard. Before you author anything (a log, a decision, a commit, an "Authored by" line, an approval), ask who you are working with, unless they have already said so in this session. Never guess.

### Confirmation gate

Before changing anything outside this repository (a channel, a handle, a public post, an upload, a scheduled release):

1. Restate the request in your own words: outcome, scope, constraints.
2. Say what you believe is out of scope.
3. Ask clarifying questions about anything vague.
4. Wait for explicit approval.

Read-only work (reading, researching, drafting inside this repo) does not need the gate.

### Two modes

- **Brainstorm mode** (story ideas, research, scripting, storyboards inside this repo): start immediately; ask questions alongside the work.
- **Work mode** (publishing, accounts, anything public or hard to undo): run the confirmation gate with **at least three** clarifying questions and wait for an explicit yes.
- When unsure, it is work mode. Details in [PRINCIPLES.md](PRINCIPLES.md).

### Chesterton's fence

Do not remove, rename, or clean something up until you know why it is there. Find out first ([decisions/](decisions/), [logs/](logs/)), then ask.

### Pareto principle

Start with the small part of the work that carries most of the result. Right now that is getting Episode 1 made.

### The format laws

From [series/bible.md](series/bible.md). Every script and storyboard follows them:

- **One structural change per miniseries.** Everything downstream is consequence, not a new wish.
- **Every invention needs a source:** native tradition or a trade partner. No magic tech jumps.
- **Nothing is free.** The alternate nation keeps real problems.
- **Always end on the real comparison**, in typed text.
- **No narrator, no host, no "CHANGE" tags, no stat cards.** Show, then tell. Watchable with sound off.

See [decision 0005](decisions/0005-no-narrator.md).

### Content guardrails

- **No real living politicians or their families**, as characters or plot devices. Fictional dynasties only ([decision 0003](decisions/0003-no-living-politicians.md)).
- **Japan is an ally and peer.** The WWII villain is a rogue faction with an invented name and flag; atrocity stays off-screen ([decision 0004](decisions/0004-japan-as-ally.md)).
- **The southern sultanates get agency**, never only a buffer or a money source.
- **No copyrighted game assets**, UI, fonts, music or voice lines. "Inspired by" only ([decision 0010](decisions/0010-no-copyrighted-assets.md)).
- **Disclose synthetic content** where platforms require it.

### Credentials

Do not write passwords, API keys, tokens or recovery codes into this repository. Record **which** accounts exist and **where** each login is kept in [map/accounts.md](map/accounts.md). See [decision 0002](decisions/0002-credentials.md).

### Other work

This repository is about Elsewhen only. Never bring in names, accounts or details from Krischan's employer, clients or other repositories.

## Keeping this repository true

- **History carries a source.** Every real-history claim in a script needs a source a commenter could check. Never cite Menzies' *1421*.
- **Stated vs proposed.** Mark what Krischan decided apart from what an agent proposed.
- **Research** goes in [research/](research/), one dated file per piece of work. Use the `research-note` skill.
- **The series** (bible, storyboards, episodes) lives in [series/](series/). One folder per miniseries; one file per episode once it has a shot list.
- **Decisions** someone might later want to undo go in [decisions/](decisions/), including dropped ideas.
- **Logs:** end every session that changed something with a log in [logs/](logs/). Use the `session-log` skill. Never rewrite an old log.
- **Open questions** go in [project/open-questions.md](project/open-questions.md), and come out when answered.
- Keep this file short.

## Where to look

| Looking for | Go to |
| --- | --- |
| Where things stand right now | [project/status.md](project/status.md) |
| How we work | [PRINCIPLES.md](PRINCIPLES.md) |
| Concept, rules, look, brand, all pitches | [series/bible.md](series/bible.md) |
| The Perlangan miniseries, episode by episode | [series/perlangan/storyboard.md](series/perlangan/storyboard.md) |
| Episode 1 shot list | [series/perlangan/ep01-victorias-last.md](series/perlangan/ep01-victorias-last.md) |
| Release order | [project/roadmap.md](project/roadmap.md) |
| Questions waiting on a decision | [project/open-questions.md](project/open-questions.md) |
| Channels, handles, tools | [map/accounts.md](map/accounts.md) |
| Research and sources | [research/](research/) |
| Why things are the way they are | [decisions/](decisions/) |
| What already happened | [logs/](logs/) |
