# PL-2026-0016 — Explosive prompts (trigger-based IPI)

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0016 |
| Title | Explosive prompts — dormant conditional injection |
| Type | Academic research (multi-agent product trials) |
| Date | 2026-09 (arXiv) |
| Status | OBSERVED |
| Tags | research; delayed-trigger; multi-product |
| Geography | International |

## Summary

Paper introduces **explosive prompts**: conditional payloads that stay dormant until an attacker-chosen trigger, evaluated across **nine production agents** (Codex, Gemini CLI, Claude Code CLI, Cursor CLI, Copilot, Devin CLI, Kiro CLI, Qwen Code, Google Assistant). Authors report substantially higher success than bare imperative injections and weaker detection by existing classifiers.

## Public locator

- https://arxiv.org/abs/2609.22510

## Use in archive

Mechanism class for **time-delayed** injection—not a single vendor CVE. Supports correlation across IDE/CLI agents already listed.

## Safety

No payload generator code stored.
