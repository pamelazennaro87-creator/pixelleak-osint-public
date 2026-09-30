# International case index — AI agent exposure incidents

Evidence-first OSINT. Fingerprints only. **15 cases** (2025–2026).

## 2025

| ID | Title | Mechanism |
|----|-------|-----------|
| [PL-2025-0001](2025/PL-2025-0001/INFO.md) | GitHub MCP toxic flow (Invariant) | Issue → MCP → private data → public PR |
| [PL-2025-0002](2025/PL-2025-0002/INFO.md) | Trail of Bits Copilot Agent | Issue → Copilot PR backdoor path |
| [PL-2025-0003](2025/PL-2025-0003/INFO.md) | Devin injection series (Rehberger) | Async agent + issue/web injection |

## 2026

| ID | Title | Mechanism |
|----|-------|-----------|
| [PL-2026-0001](2026/PL-2026-0001/INFO.md) | **PixelLeak** (Glow) | Screenshot workaround → public host |
| [PL-2026-0002](2026/PL-2026-0002/INFO.md) | GitLost (Noma) | Issue → Agentic Workflow → comment |
| [PL-2026-0003](2026/PL-2026-0003/INFO.md) | RoguePilot (Orca) | Issue → Codespaces Copilot → token |
| [PL-2026-0004](2026/PL-2026-0004/INFO.md) | Claude Code GitHub Action class | CI agent + untrusted GitHub content |
| [PL-2026-0005](2026/PL-2026-0005/INFO.md) | Poisoned coding-test (Mitiga) | Repo instruction files → auto-run |
| [PL-2026-0006](2026/PL-2026-0006/INFO.md) | **GitInject** (arXiv) | Multi-provider CI/CD injection catalog |
| [PL-2026-0007](2026/PL-2026-0007/INFO.md) | **DuneSlide** (Cursor) | Injection → sandbox RCE |
| [PL-2026-0008](2026/PL-2026-0008/INFO.md) | Manus shared-project injection | Stored multi-user agent instructions |
| [PL-2026-0009](2026/PL-2026-0009/INFO.md) | ToxicSkills class | Malicious agent skill supply-chain |
| [PL-2026-0010](2026/PL-2026-0010/INFO.md) | AIShellJack study | Empirical Copilot/Cursor injection |
| [PL-2026-0011](2026/PL-2026-0011/INFO.md) | ChatGPT cross-account channel | Sandbox isolation failure |
| [PL-2026-0012](2026/PL-2026-0012/INFO.md) | OpenAI agent / HF cluster | Autonomous agent containment |

## Taxonomy

| Tag | Examples |
|-----|----------|
| `github-issue-injection` | MCP, GitLost, RoguePilot, ToB |
| `screenshot-public-host` | PixelLeak |
| `ci-agent` | Claude Action, GitInject |
| `ide-sandbox` | DuneSlide, AIShellJack |
| `skill-supply-chain` | Mitiga, ToxicSkills |
| `hosted-sandbox-isolation` | Manus, Check Point, HF cluster |
