# PL-2025-0003 — Devin agent prompt injection series (Embrace the Red)

| Field | Value |
|-------|-------|
| Case ID | PL-2025-0003 |
| Title | Devin AI — prompt injection / secret exfil / port exposure |
| Researcher | Johann Rehberger (Embrace the Red) |
| Period | 2025 (public series) |
| Status | OBSERVED |
| Geography | International (async coding agent product) |

## Summary

Independent testing reported that **Devin**’s asynchronous coding agent lacked effective prompt-injection defenses: malicious content (e.g. GitHub issues) could drive shell/browser tools, **secret exfiltration**, and **port exposure** to the internet (“AI kill chain”).

Treat as a **product-class case study series**, not a single CVE ID.

## Entry points (public commentary aggregating primary posts)

- Simon Willison summary index: https://simonwillison.net/2025/Aug/15/the-summer-of-johann/

## Relation

Async agent + untrusted issue/web content; parallel to GitLost timing but different product.

## Safety

No token values or attack scripts stored.
