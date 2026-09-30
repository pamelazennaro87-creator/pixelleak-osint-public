# PixelLeak OSINT — International dataset

**Evidence-first OSINT** on AI agents that expose data via GitHub, IDEs, CI, skills, and hosted sandboxes.

> *Preserve the fingerprint, not the stolen payload.*

**15 cases · 2025–2026 · structured CSV/graph · public sources only**

## Start here

| Role | Link |
|------|------|
| **Executive / portfolio** | [`analysis/executive-brief.md`](analysis/executive-brief.md) |
| **All cases** | [`cases/INDEX.md`](cases/INDEX.md) |
| **Machine table** | [`indexes/cases.csv`](indexes/cases.csv) |
| **Mechanisms** | [`analysis/mechanism-matrix.md`](analysis/mechanism-matrix.md) |
| **Fingerprints** | [`indicators/indicators.csv`](indicators/indicators.csv) |
| **Full map** | [`indexes/master-index.md`](indexes/master-index.md) |

## Case families

| Family | Examples |
|--------|----------|
| Screenshot / public host | PixelLeak |
| GitHub issue injection | MCP, GitLost, RoguePilot, Trail of Bits |
| CI agents | Claude Action, GitInject |
| IDE sandbox / RCE | DuneSlide, AIShellJack |
| Skills / repo poison | Mitiga, ToxicSkills |
| Hosted isolation | Manus, Check Point, OpenAI/HF cluster |

## Shared pattern

```text
untrusted or unconstrained agent context
  + powerful tools / tokens
  + public or external egress
→ exposure
```

## Policy

[`SCOPE.md`](SCOPE.md) · [`STATUS.md`](STATUS.md) · [`methodology/`](methodology/)

---
*v2.1 structured international OSINT portfolio*
