# Cloudflare Security Audit Skill

A coding-agent skill from Cloudflare that orchestrates a structured security audit across reconnaissance, coverage-led hunting, candidate validation, evidence verification, and target-neutral reporting. It produces validated findings and coverage artifacts rather than treating every lead as a confirmed vulnerability.

## Why it is trustworthy

- Published by Cloudflare and described as the starting point for Cloudflare's vulnerability-discovery harness.
- Includes a substantial, documented multi-phase workflow with independent verification and explicit evidence boundaries.
- Ships zero-dependency validators, tests, a report schema, sandbox requirements, and an MIT license.

## Source

- Repository: [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)
- Install with `npx skills add https://github.com/cloudflare/security-audit-skill --skill security-audit`.
