# Correlation engine (design)

## Goal
Suggest links between cases, indicators, and sources — **never auto-promote to CONFIRMED**.

## Inputs
- `indicators/indicators.csv`
- `relationships/graph.csv`
- `timeline/timeline.csv`
- `sources/INDEX.md`

## Suggested rules (human review required)

1. **Same public tool name** across sources → suggest `uses_or_amplified_by`
2. **Same product surface** (MCP, Agentic Workflows, Codespaces) → suggest `targets`
3. **Issue body as instruction** pattern in ≥2 cases → suggest `shares_pattern`
4. **Media-only amplification** of same disclosure day → do **not** create new case IDs
5. **404 on previously cited locator** → set availability REMOVED; keep historical claim

## False-positive risks
- Treating secondary journalism as new incidents
- Counting gitshot presence as proof of unauthorized agent behavior (tool is explicit about public default)
- Merging PixelLeak quantitative claims with GitLost PoC as one event

## Output
Rows in `graph.csv` with `review_state=suggested|accepted|rejected`.
