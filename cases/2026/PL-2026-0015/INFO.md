# PL-2026-0015 — MCP Python SDK OAuth credential theft

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0015 |
| Title | MCP Python SDK OAuth flow hijack |
| Discoverer | Cycode (+ advisory credits) |
| Fix | SDK 1.30.0 / 2.2.0 (reported) |
| Advisory wave | 2026-09 |
| Status | OBSERVED |
| Tags | mcp; oauth; sdk |
| Geography | International |

## Summary

A **malicious MCP server** could trick apps built on the official **MCP Python SDK** into sending OAuth client secret, authorization code, and PKCE material to an attacker-controlled token endpoint—enabling account takeover of the linked login provider in vulnerable client configurations.

## Public locators

- Cycode: https://cycode.com/blog/mcp-python-sdk-oauth-account-takeover/
- The Hacker News summary: https://thehackernews.com/2026/09/official-mcp-python-sdk-flaw-can-let.html

## Relation

Complements Invariant MCP *behavior* issues with an **SDK protocol/auth** failure class.

## Safety

No secrets or PoC credentials stored.
