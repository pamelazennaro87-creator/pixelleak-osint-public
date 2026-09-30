# Recheck procedure

## Cadence
Suggested: monthly, or after major media waves.

## Steps
1. Load primary URLs from `indexes/cases.csv` and `sources/INDEX.md`.
2. Record HTTP outcome: AVAILABLE / REDIRECT / REMOVED / UNKNOWN.
3. Update `indicators` availability for repo_path-type rows.
4. Never restore removed content from caches into this repo.
5. Log date + outcome in timeline or a `collection-log/` note.

## Already logged
- `sweeper-demo/pr-assets` → REMOVED (404) 2026-09-30
