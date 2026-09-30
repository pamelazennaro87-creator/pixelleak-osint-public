# Cases index

| Case ID | Title | Date | Status | Mechanism |
|---------|-------|------|--------|-----------|
| PL-2025-0001 | GitHub MCP toxic flow (Invariant) | 2025-05-26 | OBSERVED | Issue → MCP agent → private data → public PR |
| PL-2026-0001 | PixelLeak | 2026-09-29 | REPORTED / partial | Screenshot workaround → public host |
| PL-2026-0002 | GitLost (Noma) | 2026-07-06 | OBSERVED | Issue → Agentic Workflow → public comment |
| PL-2026-0003 | RoguePilot (Orca) | 2026-02-16 | OBSERVED | Issue → Copilot Codespaces → token exfil path |
| PL-2026-0004 | Claude Code GitHub Action class | 2026 | OBSERVED | Issue/PR → CI agent → env secrets |
| PL-2026-0005 | Poisoned coding-test (Mitiga) | 2026-06-19 | OBSERVED | Malicious repo files → auto-run agent |

## Shared pattern

```text
untrusted or unconstrained agent context
  + powerful tools / tokens
  + public or external egress
→ exposure
```

**PixelLeak** is the outlier where the driver is often the **developer’s own helpful task**, not an external attacker issue.
