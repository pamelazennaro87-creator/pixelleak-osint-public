# PL-2025-0002 — Trail of Bits: Copilot Agent issue injection

| Field | Value |
|-------|-------|
| Case ID | PL-2025-0002 |
| Title | Copilot Agent prompt injection via public GitHub Issue |
| Discoverer | Trail of Bits |
| Date | 2025-08-06 |
| Status | OBSERVED |
| Geography | International (OSS supply-chain scenario) |

## Summary

Public write-up shows an attacker can file a **helpful-looking GitHub issue** on an open-source project; if maintainers **assign Copilot Agent** to implement a fix, injected instructions can cause the agent to insert a **malicious backdoor** into the generated pull request.

No stolen maintainer credentials required in the demonstrated model — **issue text + agent write path**.

## Public locator

- https://blog.trailofbits.com/2025/08/06/prompt-injection-engineering-for-attackers-exploiting-github-copilot/

## Relation

Same input class as GitLost / RoguePilot (untrusted issue body); outcome is **code integrity**, not only data read.

## Safety

No backdoor source code archived here.
