# PL-2026-0010 — AIShellJack (empirical IDE agent injection)

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0010 |
| Title | AIShellJack — prompt injection on agentic coding editors |
| Type | Academic empirical study |
| Status | OBSERVED |
| Geography | International |

## Summary

Paper presents large-scale evaluation of prompt injection against **GitHub Copilot** and **Cursor**, with automated payload framework (hundreds of payloads / ATT&CK-mapped techniques). Reported attack success rates for malicious command execution can be very high under study conditions (authors report up to ~84% in places).

## Public locator

- https://arxiv.org/html/2509.22040

## Use in this archive

Benchmark evidence that IDE agents systematically obey injected repo/rule content — supports correlation with PL-2026-0007 and PL-2025-0002.
