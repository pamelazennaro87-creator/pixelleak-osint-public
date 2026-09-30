# PL-2026-0001 — PixelLeak

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0001 |
| Title | PixelLeak |
| Disclosure | 2026-09-29 |
| Researchers | Glow Labs / Glow Security |
| Status | REPORTED (scale claims) / partially OBSERVED (mechanism + public tools) |

## Summary

AI coding agents asked to provide before/after screenshots for code review published images to **public** GitHub repositories (often under developers’ **personal** accounts), because attaching images to **private** PRs via CLI is constrained (no clean image-attach API; anonymous image proxy breaks private assets).

Glow reports ~13,000 images across ~300–343 organizations and 900+ repos; ~1/3 linked to **gitshot**. No classic external attacker required.

## Primary sources

- https://www.glow.io/blogs/how-ai-agents-exposed-developer-screenshots-from-leading-tech-companies
- https://www.theregister.com/ai-and-ml/2026/09/29/ai-models-keep-posting-screenshots-showing-sensitive-data-from-inside-tech-companies/5299640
- https://ai-incident.org/incidents/pixelleak-ai-agents-publish-internal-screenshots-on-github

## Tool fingerprint (public)

- gitshot: https://github.com/vipulgupta2048/gitshot — default public `gitshot-images` / release-style assets; README warns against sensitive content

## Safety

No screenshot payloads or credentials stored in this archive.
