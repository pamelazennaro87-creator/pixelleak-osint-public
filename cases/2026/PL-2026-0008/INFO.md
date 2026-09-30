# PL-2026-0008 — Manus shared-project stored prompt injection

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0008 |
| Title | Manus — stored injection via shared project instructions |
| Researchers | CodeAnt AI Security Research Team |
| Fix reported | 2026-09-16 |
| Status | OBSERVED |
| Geography | International (collaborative agent product) |

## Summary

**Stored / indirect prompt injection**: owner-authored instructions in a **shared project** load into other members’ agent context as trusted configuration. Research demonstrated path to code execution in another user’s sandbox and remote-desktop style takeover implications; reported via Meta bug bounty and fixed (per public write-up).

## Public locator

- https://codeant.ai/blogs/manus-prompt-injection-attack-ai-agent-security

## Relation

Trust boundary failure across **multi-user agent workspaces**, not GitHub issue-centric.

## Safety

No credentials or exploit chains stored.
