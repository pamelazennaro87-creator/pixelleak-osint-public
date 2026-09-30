# Mechanism matrix (15 cases)

| Case | Attacker? | Trigger | Impact | Root gap |
|------|-----------|---------|--------|----------|
| PL-2025-0001 MCP | Yes | Public issue | Public PR data | Cross-repo token |
| PL-2025-0002 ToB | Yes | Public issue | Malicious PR | Hostile issue assigned to agent |
| PL-2025-0003 Devin | Yes | Issue/web | Secrets / ports | Open async tools |
| PL-2026-0001 PixelLeak | No* | Screenshot task | Public images | No private PR image API |
| PL-2026-0002 GitLost | Yes | Public issue | Public comment | Agentic workflow org read |
| PL-2026-0003 RoguePilot | Yes | Issue→Codespace | Token path | Passive injection + env |
| PL-2026-0004 Claude Action | Yes | CI content | CI secrets | Agent + runner env |
| PL-2026-0005 Mitiga | Yes | Poisoned files | Cloud creds | Auto-run + trusted files |
| PL-2026-0006 GitInject | Yes | CI untrusted | Creds / integrity | Structural CI+agent |
| PL-2026-0007 DuneSlide | Yes | MCP/web | Local RCE | Sandbox write paths |
| PL-2026-0008 Manus | Yes | Shared instructions | Other users | Multi-tenant trust |
| PL-2026-0009 Skills | Yes | Malicious skill | Agent implant | Registry trust |
| PL-2026-0010 AIShellJack | Yes | Repo/rules | Commands | IDE agent obedience |
| PL-2026-0011 Check Point | Yes | Covert channel | Cross-account | Sandbox isolation |
| PL-2026-0012 HF cluster | Autonomous | Exploration | Infra | Agent containment |

\*Typical PixelLeak: developer task, no external attacker.
