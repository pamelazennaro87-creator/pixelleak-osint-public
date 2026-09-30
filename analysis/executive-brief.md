# Executive brief — AI agent exposure OSINT (2025–2026)

**Dataset:** 15 evidence-first cases · public sources only  
**Repo:** https://github.com/pamelazennaro87-creator/pixelleak-osint-public

## One-sentence finding

When an AI agent can read **untrusted text**, hold **powerful tools or secrets**, and reach a **public or external channel**, exposure becomes a design outcome—not only a model “hallucination.”

## Five recurring patterns

1. **Helpful workaround (PixelLeak)** — Agents publish review screenshots to public repos because private PR image attach is broken/limited via CLI.
2. **Hostile issue as instructions** — Public GitHub issues steer MCP, Agentic Workflows, Copilot Agent, or Codespaces agents (Invariant, Noma, Orca, Trail of Bits).
3. **CI agents + secrets in the runner** — Untrusted PR/issue content reaches agents that can read environment credentials (Claude Action class, GitInject study).
4. **IDE sandbox escape** — Prompt injection becomes local RCE or high-success command execution (DuneSlide, AIShellJack).
5. **Trust in files/skills/shared config** — `CLAUDE.md`, `.cursor/rules`, agent skills, or shared-project instructions act as malware without a binary (Mitiga, ToxicSkills class, Manus).

## What defenders should do first

| Priority | Action |
|----------|--------|
| 1 | Scope agent tokens to one repo; block public repo creation from corp agents |
| 2 | Treat public issues/PRs as hostile input to any agent with write or secret access |
| 3 | Hunt personal `gitshot-images` / public screenshot repos for staff with private-repo access |
| 4 | Pin CI agent actions; keep secrets out of agent-readable env |
| 5 | Disable auto-run on untrusted clones; review installed agent skills |

## What this dataset is not

- Not a list of stolen passwords or victim dumps  
- Not an independent re-count of “13,000 images / 343 orgs” (those stay **REPORTED** from Glow)  
- Not legal advice  

## How to navigate

| Need | Open |
|------|------|
| Full list | `cases/INDEX.md` / `indexes/cases.csv` |
| Compare mechanisms | `analysis/mechanism-matrix.md` |
| Chronology | `timeline/timeline.csv` |
| Technical fingerprints | `indicators/indicators.csv` |
| Links between entities | `relationships/graph.csv` |

---
*Fingerprint OSINT for governance and portfolio demonstration.*
