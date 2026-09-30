# PixelLeak OSINT — International dataset

**Evidence-first OSINT** on AI agents that expose data via GitHub, IDEs, CI, skills, and hosted sandboxes.

> *Preserve the fingerprint, not the stolen payload.*

**15 cases · CLAIMS on all · CSV/graph · consultable web page**

## Web UI

- **Page file:** [`docs/index.html`](docs/index.html) (open in browser)
- **GitHub Pages:** enable Settings → Pages → `/docs`  
  → `https://pamelazennaro87-creator.github.io/pixelleak-osint-public/`

## Start here

| Role | Link |
|------|------|
| **Interactive page** | [`docs/index.html`](docs/index.html) |
| **Executive brief** | [`analysis/executive-brief.md`](analysis/executive-brief.md) |
| **All cases** | [`cases/INDEX.md`](cases/INDEX.md) |
| **Machine table** | [`indexes/cases.csv`](indexes/cases.csv) |
| **Mechanisms** | [`analysis/mechanism-matrix.md`](analysis/mechanism-matrix.md) |
| **Fingerprints** | [`indicators/indicators.csv`](indicators/indicators.csv) |

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

[`SCOPE.md`](SCOPE.md) · [`STATUS.md`](STATUS.md)

---
*v2.2 complete international OSINT portfolio + UI*
