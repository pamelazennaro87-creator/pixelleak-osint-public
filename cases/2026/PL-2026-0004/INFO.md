# PL-2026-0004 — Claude Code GitHub Action class

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0004 |
| Status | OBSERVED |

Untrusted **issue/PR/comment** content can steer **Claude Code GitHub Action** / CI agents toward reading runner environment secrets; multiple research threads (Microsoft, GMO Flatt) and vendor mitigations reported.

**Sources:**
- https://www.microsoft.com/en-us/security/blog/2026/06/05/securing-ci-cd-in-agentic-world-claude-code-github-action-case/
- https://flatt.tech/research/posts/poisoning-claude-code-one-github-issue-to-break-the-supply-chain/
