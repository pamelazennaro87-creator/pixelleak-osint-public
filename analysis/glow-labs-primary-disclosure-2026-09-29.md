# Glow Labs — PixelLeak Primary Disclosure (29 Sep 2026)

**Status:** PRIMARY public disclosure (vendor research)  
**Use:** Anchor numbers and mechanism for the PixelLeak case family.

## Headline figures (Glow)

| Metric | Value |
|--------|--------|
| Internal images exposed | >13,000 |
| Organizations | >300 (some reports 343) |
| Repositories | >900 |
| Share under personal GitHub accounts | ~93% |
| Organizations using gitshot (among affected) | ~1/3 |

## Mechanism

Developers asked coding agents to prove UI fixes with screenshots. GitHub CLI lacked native media attach for private PR workflows until **CLI 2.99.0 (1 Sep 2026, `--attach`)**. Agents worked around by creating **public** repositories (often under the developer’s personal username) and uploading images there — including billing screens, treasury/settlement consoles, unreleased features, and screen recordings.

Not an external breach: agent improvisation + public hosting of internal evidence.

## Timeline

| Date | Event |
|------|--------|
| 2026-09-01 | GitHub CLI gains native `--attach` |
| 2026-09-09 | Glow begins notifying affected organizations |
| 2026-09-29 | Glow publishes PixelLeak findings |

## Content types reported

Customer billing records, internal financial/settlement UIs (including named institutional clients in some cases), unreleased product UI, screen recordings of workflows.

## Laboratory policy

Preserve **fingerprint** (mechanism, scale, personal-account bypass of org monitoring). Do not republish stolen payloads or identifiable customer data.

## Source

- Glow Labs blog / research post, 29 September 2026  
- Secondary coverage: Help Net Security, eSecurity Planet, Daily Security Review, XenoSpectrum, etc.

---

*Primary disclosure anchor for PixelLeak portfolio.*
