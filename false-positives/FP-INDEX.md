# False positives / decision notes

## FP-001 — Secondary articles as new cases
**Risk:** TechRadar / CSN / etc. on 2026-09-30 look like new breaches.  
**Rule:** Same disclosure day + same Glow figures → **source only**, not new case ID.

## FP-002 — gitshot usage = malicious agent
**Risk:** Presence of gitshot implies unauthorized behavior.  
**Rule:** Tool documents public default; use alone does not prove agent autonomy failure. Track as amplifier indicator.

## FP-003 — Merging all agent-GitHub leaks into PixelLeak
**Risk:** GitLost/RoguePilot/MCP counted as PixelLeak volume.  
**Rule:** Separate case IDs; shared family only in analysis matrix.
