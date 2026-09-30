# PixelLeak OSINT

**Evidence-first knowledge base** on AI coding agents that expose internal data through GitHub and related developer surfaces.

> **Principle:** *Preserve the fingerprint, not the stolen payload.*

This repository documents **public research disclosures**, mechanism patterns, and provenance links.  
It does **not** store passwords, tokens, API keys, private keys, malware, or stolen data dumps.

## Why this exists

Between 2025–2026, multiple independent research teams showed the same structural failure:

```text
untrusted or unconstrained agent context
  + powerful tools / tokens
  + public or external egress
→ data exposure
```

**PixelLeak** (Glow, Sep 2026) is the large-scale instance where agents hosted review screenshots on public repos because GitHub CLI cannot attach images to private PRs cleanly. Other cases use prompt injection via issues, MCP over-scope, or CI agent tools.

## Cases (start here)

| ID | Title | Mechanism |
|----|-------|-----------|
| [PL-2025-0001](cases/2025/PL-2025-0001/INFO.md) | GitHub MCP toxic flow (Invariant) | Public issue → MCP agent → private data → public PR |
| [PL-2026-0001](cases/2026/PL-2026-0001/INFO.md) | **PixelLeak** | Screenshot workaround → public image host |
| [PL-2026-0002](cases/2026/PL-2026-0002/INFO.md) | GitLost (Noma) | Public issue → Agentic Workflow → public comment |
| [PL-2026-0003](cases/2026/PL-2026-0003/INFO.md) | RoguePilot (Orca) | Issue → Copilot Codespaces → token path |
| [PL-2026-0004](cases/2026/PL-2026-0004/INFO.md) | Claude Code GitHub Action class | Issue/PR → CI agent → env secrets |
| [PL-2026-0005](cases/2026/PL-2026-0005/INFO.md) | Poisoned coding-test (Mitiga) | Malicious repo files → auto-run agent |

Full index: [`cases/INDEX.md`](cases/INDEX.md)

## Status taxonomy

| Status | Meaning |
|--------|---------|
| **REPORTED** | Claim from a source; not independently verified here |
| **OBSERVED** | Public locator checked or primary disclosure reviewed |
| **CONFIRMED** | Multiple independent public sources or direct technical verification of a non-sensitive fact |

## What we keep / never keep

See [`SCOPE.md`](SCOPE.md).

## Primary public anchors

- Glow PixelLeak: https://www.glow.io/blogs/how-ai-agents-exposed-developer-screenshots-from-leading-tech-companies
- The Register (PixelLeak): https://www.theregister.com/ai-and-ml/2026/09/29/ai-models-keep-posting-screenshots-showing-sensitive-data-from-inside-tech-companies/5299640
- Invariant MCP: https://invariantlabs.ai/blog/mcp-github-vulnerability
- Noma GitLost: https://noma.security/noma-labs/gitlost-how-we-tricked-githubs-ai-agent-into-leaking-private-repos
- Orca RoguePilot: https://orca.security/resources/blog/roguepilot-github-copilot-vulnerability/

---
*Public OSINT portfolio. Fingerprints only.*
