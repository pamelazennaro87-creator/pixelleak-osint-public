# Defensive checklist (org-level)

Derived from public cases — not a guarantee of safety.

## Agent permissions
- [ ] Tokens scoped to single repo where possible
- [ ] Agents cannot create public repos from corporate sessions by default
- [ ] Separate identities: personal GitHub vs company org

## Untrusted input
- [ ] Public issues/PRs treated as hostile to agents
- [ ] Human approval before agent posts publicly
- [ ] Disable auto-run on untrusted clones / take-home tests

## Screenshot / review workflows
- [ ] Ban public gitshot-style backends for internal UI
- [ ] Prefer private artifact stores or enterprise image hosts
- [ ] Hunt for `gitshot-images`, `_gitshot`, `pr-assets` under **personal** accounts of staff with private-repo access

## CI agents
- [ ] Pin action versions; review `claude-code-action` (or similar) permissions
- [ ] Secrets not readable via agent file tools (`/proc`, env dumps)
- [ ] Least privilege `GITHUB_TOKEN`

## Detection
- [ ] Alert on new public repos matching agent screenshot patterns
- [ ] Alert on agent comments that paste repository file bodies
