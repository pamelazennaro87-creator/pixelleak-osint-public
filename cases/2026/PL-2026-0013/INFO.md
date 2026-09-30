# PL-2026-0013 — Agent Hijacks (conversation history poisoning)

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0013 |
| Title | Agent Hijacks — conversation history poisoning |
| Discoverer | Darktrace research |
| Disclosure | 2026-09-24 (public blog; disclosed to vendors Aug 2026) |
| Status | OBSERVED |
| Tags | history-poison; claude-code; codex; kiro |
| Geography | International |

## Summary

Darktrace shows **agentic harnesses** store conversation history locally **without validating** that stored “assistant” turns were actually produced by the model. Poisoned history can convince a frontier coding agent it is an authorized red-team operator, turning a workstation into an autonomous attacker path after a malicious package/install context.

Confirmed design choice across Claude Code, OpenAI Codex, AWS Kiro-CLI (and open-source Pi) per researchers.

## Public locator

- https://www.darktrace.com/blog/hijacking-agentic-harnesses-to-attack-an-organization

## Relation

Extends IDE/agent trust failures beyond issue text into **local transcript integrity**.

## Safety

No exploit packages stored.
