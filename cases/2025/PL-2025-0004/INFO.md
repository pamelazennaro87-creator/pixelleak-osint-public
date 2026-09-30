# PL-2025-0004 — EchoLeak (Microsoft 365 Copilot)

| Field | Value |
|-------|-------|
| Case ID | PL-2025-0004 |
| Title | EchoLeak |
| Discoverer | Aim Security (reported) |
| CVE | CVE-2025-32711 (reported) |
| Period | 2025 (public discussion; fix server-side) |
| Status | OBSERVED |
| Tags | email-injection; m365-copilot; lethal-trifecta |
| Geography | International |

## Summary

**EchoLeak** is the canonical enterprise example of the **lethal trifecta** outside pure GitHub tooling: a crafted **email** is later retrieved as context by Microsoft 365 Copilot; injected instructions cause the agent to collect user data and exfiltrate via a side channel (e.g. image URL) **without a user click** on the malicious payload. Microsoft registered a critical CVE and applied a server-side fix (per public summaries).

## Why it belongs here

Same structural failure as PixelLeak/GitLost, different surface: **untrusted content (email) + private data + egress**.

## Public anchors

- Concept + case summary in lethal-trifecta explainers (e.g. Data Panda dictionary citing Aim Security / CVE-2025-32711)
- Simon Willison lethal trifecta framing: https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/

## Safety

No email bodies or victim data stored.
