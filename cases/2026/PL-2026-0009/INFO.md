# PL-2026-0009 — ToxicSkills / agent skill supply-chain (Snyk class)

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0009 |
| Title | Malicious / unsafe AI agent skills in public registries |
| Example research | Snyk analysis of ClawHub-style skill registries (reported Feb 2026) |
| Status | REPORTED / OBSERVED (class) |
| Geography | International |

## Summary

Public research on **AI agent skill marketplaces** reports high rates of security flaws, malicious payloads, and remote instruction loading (e.g. curl|bash patterns) that turn “install skill” into **supply-chain compromise** of the agent.

Adjacent to Mitiga instruction-file findings (PL-2026-0005).

## Notes

Exact percentages and registry names should be re-cited from primary Snyk publication when archiving claims as CONFIRMED. This card records the **incident class** for correlation.

## Relation

Skill files as trusted agent context — same trust mistake as poisoned `CLAUDE.md` / `.cursor/rules`.
