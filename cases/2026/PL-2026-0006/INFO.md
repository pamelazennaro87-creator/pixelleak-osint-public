# PL-2026-0006 — GitInject (CI/CD agent prompt injection)

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0006 |
| Title | GitInject |
| Type | Academic / open research framework + attack catalog |
| Date | 2026-06 (arXiv) |
| Status | OBSERVED |
| Geography | International (multi-provider GitHub Actions study) |

## Summary

**GitInject** evaluates prompt injection against **real live GitHub workflows** used by AI coding agents in CI/CD. Researchers document **eleven named attack classes** (config-file injection, credential exfiltration, judgment manipulation, availability, etc.) across **four AI providers**. All tested providers susceptible to at least one class in default configs; critical issues often **structural** (credentials + config handling), not model-specific.

## Public locators

- Paper: https://arxiv.org/abs/2606.09935
- Framework (reported): https://github.com/ceferisbarov/GitInject

## Relation

Extends PL-2026-0004 (Claude Code Action) into a **multi-vendor CI agent** evidence base.

## Safety

No exploit payloads or stolen secrets stored.
