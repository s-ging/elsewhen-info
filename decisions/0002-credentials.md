# 0002 — Where logins and secrets are kept

**Date:** 2026-11-12
**Decided by:** pending (Krischan)
**Status:** proposed (standing default from the team's template)

## Context

The channel will have logins: YouTube, TikTok, Facebook/Instagram, maybe an editing or asset service. Plain-text passwords in Git stay in history forever and are read by every AI session that opens the repo.

## Options

1. **Password manager vault.** The repo records which logins exist and where they're kept. Recommended.
2. **Encrypted file in the repo** (SOPS with age, or git-crypt).
3. **Plain text in the repo.** Not recommended.

## Decision

Pending. Until decided, no plain-text secrets in the repo.
