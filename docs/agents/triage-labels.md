# Triage Labels

The skills speak in terms of five canonical triage roles. This file maps those roles to the actual label strings used in this repo's issue tracker (GitHub Issues).

| Role in the skills | Label in this repo | Meaning                                  |
| ------------------ | ------------------ | ---------------------------------------- |
| `needs-triage`     | `needs-triage`     | Maintainer needs to evaluate this issue   |
| `needs-info`       | `needs-info`       | Waiting on reporter for more information  |
| `ready-for-agent`  | `ready-for-agent`  | Fully specified, ready for an AFK agent   |
| `ready-for-human`  | `ready-for-human`  | Requires human implementation             |
| `wontfix`          | `wontfix`          | Will not be actioned                      |

When a skill mentions a role (for example "apply the AFK-ready triage label"), use the corresponding label string from this table.

## Full label set used by the skills

The repo's GitHub labels cover the five triage roles above plus `bug` and the five wayfinder labels used by `/wayfinder`:

- `bug` — something is broken (fix action / BUG filter)
- `wayfinder:map` — the parent map issue of a wayfinder effort (Notes / Decisions-so-far / Fog)
- `wayfinder:research` — research ticket
- `wayfinder:prototype` — prototype ticket
- `wayfinder:grilling` — grilling / discussion ticket
- `wayfinder:task` — implementation task ticket

Issues are labelled strictly according to the skill rules; no labels beyond this vocabulary are forced.
