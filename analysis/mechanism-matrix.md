# Mechanism matrix

| Case | Attacker needed? | Trigger | Egress | Root gap |
|------|------------------|---------|--------|----------|
| PL-2025-0001 MCP | Yes (issue) | Public issue text | Public PR/comment | Cross-repo token + trusted issue body |
| PL-2026-0001 PixelLeak | No (typical) | Developer screenshot task | Public repo/releases | No private PR image attach via CLI |
| PL-2026-0002 GitLost | Yes (issue) | Public issue text | Public comment | Agentic workflow + org read |
| PL-2026-0003 RoguePilot | Yes (issue) | Issue → Codespace Copilot | Token exfil path | Passive injection + secrets in env |
| PL-2026-0004 Claude Action | Yes (issue/PR) | Untrusted CI content | Issue/log/web | Agent tools + runner secrets |
| PL-2026-0005 Mitiga test | Yes (poisoned repo) | Trusted project files | Cloud APIs | Auto-run + instruction files |

**Defensive takeaway:** remove at least one side of the triangle — untrusted context, broad powers, or public egress.
