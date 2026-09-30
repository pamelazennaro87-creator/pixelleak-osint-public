# PixelLeak OSINT — International dataset

**Evidence-first OSINT knowledge base** on AI agents that expose data via GitHub, IDEs, CI, skills, and hosted sandboxes.

> *Preserve the fingerprint, not the stolen payload.*

**15 public cases · 2025–2026 · international research disclosures**

No passwords, tokens, malware samples, or stolen dumps.

## Start here

- **[`cases/INDEX.md`](cases/INDEX.md)** — full case list  
- **[`analysis/mechanism-matrix.md`](analysis/mechanism-matrix.md)** — compare mechanisms  
- **[`timeline/timeline.csv`](timeline/timeline.csv)** — chronology  
- **[`sources/INDEX.md`](sources/INDEX.md)** — primary URLs  

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

[`SCOPE.md`](SCOPE.md) · [`methodology/status-rules.md`](methodology/status-rules.md) · [`STATUS.md`](STATUS.md)

---
*Public international OSINT portfolio · v2.0*
