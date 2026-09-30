# PL-2026-0014 — Unauthenticated MCP servers in the wild (Pluto)

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0014 |
| Title | Wide Open MCP — unauthenticated servers exposed |
| Discoverer | Pluto Security |
| Date | 2026-09-24 |
| Status | OBSERVED |
| Tags | mcp; exposure; misconfiguration |
| Geography | International (internet-wide scan) |

## Summary

Pluto reports **147 unauthenticated MCP servers** reachable on the internet with no login/token, including severe cases (production tools, sensitive data classes). Exposure is **misconfiguration / open tool surface**, not classic prompt injection—but it feeds the same agent risk model: any connected agent inherits a wide-open tool backend.

## Public locator

- https://pluto.security/blog/wide-open-hundreds-of-mcps-exposing-root-shells-production-data-and-citizen-records-one-call-away/

## Safety

No server IPs, credentials, or citizen records archived. Counts and mechanism only.
