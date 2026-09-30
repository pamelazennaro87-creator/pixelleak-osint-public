# PixelLeak OSINT

**Evidence-first knowledge base** on AI coding agents that expose internal data through GitHub and related developer surfaces.

> **Principle:** *Preserve the fingerprint, not the stolen payload.*

Public research disclosures, mechanism patterns, and provenance only.  
**No** passwords, tokens, API keys, private keys, malware, or stolen dumps.

## Quick start

1. [`cases/INDEX.md`](cases/INDEX.md) — all 6 cases  
2. [`analysis/mechanism-matrix.md`](analysis/mechanism-matrix.md) — compare mechanisms  
3. [`sources/INDEX.md`](sources/INDEX.md) — 21 public sources  
4. [`indexes/master-index.md`](indexes/master-index.md) — full map  

## Cases

| ID | Title | Mechanism |
|----|-------|-----------|
| [PL-2025-0001](cases/2025/PL-2025-0001/INFO.md) | GitHub MCP (Invariant) | Issue → MCP → private data → public PR |
| [PL-2026-0001](cases/2026/PL-2026-0001/INFO.md) | **PixelLeak** | Screenshot workaround → public host |
| [PL-2026-0002](cases/2026/PL-2026-0002/INFO.md) | GitLost (Noma) | Issue → Agentic Workflow → public comment |
| [PL-2026-0003](cases/2026/PL-2026-0003/INFO.md) | RoguePilot (Orca) | Issue → Copilot Codespaces → token path |
| [PL-2026-0004](cases/2026/PL-2026-0004/INFO.md) | Claude Code Action class | Issue/PR → CI agent → env secrets |
| [PL-2026-0005](cases/2026/PL-2026-0005/INFO.md) | Poisoned coding-test (Mitiga) | Malicious repo files → auto-run agent |

PixelLeak depth: [SUBCASES](cases/2026/PL-2026-0001/SUBCASES.md) · [CLAIMS](cases/2026/PL-2026-0001/CLAIMS-REGISTER.md)

## Shared failure pattern

```text
untrusted or unconstrained agent context
  + powerful tools / tokens
  + public or external egress
→ exposure
```

## Repository layout

```text
cases/           incident cards
sources/         public URL index
timeline/        chronology CSV
indicators/      technical fingerprints
relationships/   suggested links
analysis/        matrix + defensive checklist
methodology/     status rules, schema, correlation design
false-positives/ decision rules
indexes/         master map
SCOPE.md         boundaries
STATUS.md        version
```

## Status labels

| Status | Meaning |
|--------|---------|
| REPORTED | Source claim, not independently verified here |
| OBSERVED | Primary disclosure reviewed and/or public locator checked |
| CONFIRMED | Multi-source or direct non-sensitive technical check |

Details: [`methodology/status-rules.md`](methodology/status-rules.md)

## Defense

[`analysis/defensive-checklist.md`](analysis/defensive-checklist.md)

## Scope

[`SCOPE.md`](SCOPE.md)

---
*Public OSINT portfolio · v1.1*
