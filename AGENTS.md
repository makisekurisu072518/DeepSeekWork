# Agent Instructions

This file gives an agent working in this repo the context it needs to operate well.

## Agent skills

### Issue tracker

Issues and specs for this repo live as GitHub issues on `makisekurisu072518/codex`, driven through the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Five canonical triage roles use the default label strings (`needs-triage` / `needs-info` / `ready-for-agent` / `ready-for-human` / `wontfix`). The `/wayfinder` skill additionally uses `wayfinder:map` / `wayfinder:research` / `wayfinder:prototype` / `wayfinder:grilling` / `wayfinder:task`, and `bug` marks broken things. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context layout — one `CONTEXT.md` plus `docs/adr/` at the repo root. See `docs/agents/domain.md`.
