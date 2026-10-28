# PixelLeak OSINT

**Evidence-first research into AI-agent data exposure.**

> Preserve the fingerprint, not the stolen payload.

This repository documents public evidence of how AI agents expose data through GitHub, IDEs, CI systems, skills, and hosted sandboxes.  
The focus is mechanism analysis and fingerprint preservation, not reproduction of sensitive content.

---

## Start Here

| Resource | Link |
|----------|------|
| **Interactive page** | [`docs/index.html`](docs/index.html) |
| **Executive brief** | [`analysis/executive-brief.md`](analysis/executive-brief.md) |
| **All cases** | [`cases/INDEX.md`](cases/INDEX.md) |
| **Machine-readable table** | [`indexes/cases.csv`](indexes/cases.csv) |
| **Mechanism matrix** | [`analysis/mechanism-matrix.md`](analysis/mechanism-matrix.md) |
| **Indicators / fingerprints** | [`indicators/indicators.csv`](indicators/indicators.csv) |

**GitHub Pages:** enable Settings → Pages → `/docs`  
→ `https://pamelazennaro87-creator.github.io/pixelleak-osint-public/`

---

## Case Families

| Family | Examples |
|--------|----------|
| Screenshot / public host | PixelLeak |
| GitHub issue injection | MCP, GitLost, RoguePilot, Trail of Bits |
| CI agents | Claude Action, GitInject |
| IDE sandbox / RCE | DuneSlide, AIShellJack |
| Skills / repo poison | Mitiga, ToxicSkills |
| Hosted isolation | Manus, Check Point, OpenAI/HF cluster |

---

## Shared Pattern

```text
untrusted or unconstrained agent context
  + powerful tools / tokens
  + public or external egress
→ exposure
```

---

## Research Stance

This work follows the same evidence discipline used across the portfolio:

- Claims are tested, not collected
- Independence of sources is examined
- Sensitive payloads are not reproduced
- Fingerprints and mechanisms are preserved for analysis and defence

Part of the evidence-first system:

- [OSINT Signal Lab](https://github.com/pamelazennaro87-creator/osint-signal-lab-) — investigations & methodology
- [OSINT Command Center](https://github.com/pamelazennaro87-creator/osint-command-center) — investigation workspace
- **PixelLeak OSINT** — AI-agent exposure mechanisms

---

## Policy

[`SCOPE.md`](SCOPE.md) · [`STATUS.md`](STATUS.md)

---

*v2.2 — International OSINT portfolio + UI*
