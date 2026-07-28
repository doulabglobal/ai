# CLAUDE.md — doulab-site

> **The authoritative instruction file for this project is [`AGENTS.md`](./AGENTS.md).**
> Read and follow it before making any change. This file exists only so that
> Claude Code's `CLAUDE.md` convention points at the real rules.

## Must-read on entry
- **`AGENTS.md`** — workflow, guardrails, phased execution (Phase B1–B6 → Phase C/D),
  build discipline, commit/governance rules, and the `docs/ops/` manifest.
- **`docs/ops/doulab-net-backlog.md`** — canonical backlog (statuses + commit hashes).
- **`../CLAUDE.md`** — Doulab workspace map (one level up); defers to this project's files.

## Hard rules (summary — `AGENTS.md` is authoritative)
- Any structural/content/styling change MUST run `npm run build:cf` and `npm run verify:build`.
- STOP and report on: unexpected files, broken links, encoding drift, or scope creep.
- No silent changes — always report what changed, files touched, and build/verify status.
- Never weaken, skip, or bypass verifiers.
- Do not modify the frozen `clients.doulab.net` surface from this repo.
- Follow phase sequencing; don't jump phases without explicit approval.
