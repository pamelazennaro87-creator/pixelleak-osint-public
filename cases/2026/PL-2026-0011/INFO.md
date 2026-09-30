# PL-2026-0011 — ChatGPT cross-account sandbox channel (Check Point)

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0011 |
| Title | Shared clipboard / cross-account command channel in ChatGPT sandbox |
| Discoverer | Check Point Research |
| Date | 2026 (public write-up) |
| Status | OBSERVED |
| Geography | International |

## Summary

Check Point describes a covert channel between code-execution environments of **different ChatGPT accounts**, enabling an attacker-influenced session to run hidden tasks with the **victim session’s tools and connected apps** (PoC: Gmail data relayed) while the victim still receives a normal visible answer.

## Public locator

- https://research.checkpoint.com/2026/the-shared-clipboard-inside-the-sandbox-cross-account-data-leakage-in-chatgpt/

## Relation

Isolation failure in **hosted agent sandboxes**, not GitHub-centric — expands international scope beyond devtools.

## Safety

No email content or account data stored.
