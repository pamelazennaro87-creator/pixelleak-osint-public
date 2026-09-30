# PL-2026-0007 — DuneSlide (Cursor prompt injection → sandbox RCE)

| Field | Value |
|-------|-------|
| Case ID | PL-2026-0007 |
| Title | DuneSlide |
| Discoverer | Cato AI Labs |
| CVEs | CVE-2026-50548, CVE-2026-50549 (reported) |
| Fix | Cursor 3.0 (reported Apr 2026) |
| Status | OBSERVED |
| Geography | International (widely used AI IDE) |

## Summary

Indirect **prompt injection** (e.g. MCP response or web content) can steer Cursor’s agent to break out of its command sandbox and achieve **arbitrary command execution** on the developer machine without an extra confirmation click, in affected versions before the fix.

Demonstrates: injection is not only “leaky text” — it can become **local RCE** when agent tools + sandbox bugs combine.

## Public coverage

- CSO Online: https://www.csoonline.com/article/4191923/sandbox-bypass-flaws-in-cursor-ide-highlight-prompt-injection-as-an-rce-vector.html
- Hard2bit / Cato narrative: https://hard2bit.com/en/blog/prompt-injection-rce-ai-code-editors-cursor-duneslide/

## Safety

No exploit PoC code stored.
