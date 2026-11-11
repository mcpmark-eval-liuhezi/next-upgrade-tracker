# Upgrade Tracking Notes

**Baseline recorded:** `v16.4.6` (latest upstream Next.js release as of 2026-11-09)
**Tracking issue:** #8 — "Track Next.js releases"

## Upstream release baseline

| Field | Value |
| --- | --- |
| Latest upstream release tag | `v16.4.6` |
| Release date | 2026-11-09 |
| Release type | Backport release (bug fixes for `lts-active` channel; does not include all pending canary features) |
| Release URL | https://github.com/vercel/next.js/releases/tag/v16.4.6 |
| Upstream repo | vercel/next.js (starred for easy access) |

## Where to ask questions upstream

vercel/next.js discussions are organized into these categories:

- **App Router** — questions/bugs on the App Router
- **Help** — migration, setup, and debugging help (best starting point for upgrade questions)
- **Feedback** — general feedback
- **Ideas** — new feature proposals
- **RFC** — Request for Comments before proposing changes (use for upgrade proposals we want Vercel to consider)
- **Security** — security reporting
- **Triage** — triage coordination
- **Polls** — voting on proposed directions
- **Show and tell** — sharing what you built
- **Turbopack Error Report** — Turbopack-specific error reports

## Process

1. Evaluate each upstream release (see issue #8 for the permanent record).
2. Record the release tag, date, and verdict in issue #8.
3. Link any follow-up PRs here.
4. Re-baseline this note whenever a new major/minor release ships.

---

_ui Note: this file lives on the `docs/upgrade-notes` branch and is intended to be merged into `main` via PR #9 (`Add upgrade tracking notes`)._
