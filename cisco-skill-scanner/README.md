# Cisco Skill Scanner

Cisco AI Defense's open-source security scanner for AI Agent Skills. It helps review `SKILL.md` bundles and related agent artifacts for prompt injection, data exfiltration, malicious code, unsafe dependencies, and other supply-chain risks before installation or deployment.

## What it does

- Combines pattern-based detection, YAML/YARA-X rules, AST and dataflow analysis, optional LLM analysis, and a bounded CEL decision layer.
- Scans individual skills, directories, GitHub repositories, and archives, with support for standard Agent Skills formats and lenient scanning of common non-standard layouts.
- Produces terminal, JSON, Markdown, HTML, and SARIF results for local review and CI/CD gates.
- Includes reusable GitHub Actions and pre-commit integrations, configurable policies, severity thresholds, and custom rules.
- Documents measured results, threat taxonomy mappings, false-positive trade-offs, and explicit limitations; a clean scan is not a security guarantee.

## Why it qualifies

- Maintained by Cisco AI Defense in an official Cisco organization, with a public security-focused roadmap and contribution process.
- Strong community adoption: approximately 2,602 stars and 331 forks when reviewed on 2026-10-15; counts are supporting evidence, not a quality guarantee.
- Apache-2.0 licensed, packaged for Python and standalone use, with CI, extensive tests, documentation, and published releases.
- Recent maintenance added credential-exfiltration detection, frontmatter coverage, taxonomy mappings, symlink/load-failure reporting, and other scanner hardening improvements.

## Install

From the upstream README:

```bash
uv tool install cisco-ai-skill-scanner
skill-scanner scan-repo owner/repo
```

For a local skill, use `skill-scanner scan ./my-skill --use-llm --policy balanced --fail-on-severity high`. Review findings manually before trusting a skill; the project explicitly describes its detection as best effort.

## Source

- Repository: https://github.com/cisco-ai-defense/skill-scanner
- Documentation: https://cisco-ai-defense.github.io/docs/skill-scanner
- Agent Skills specification: https://agentskills.io/

Always consult the upstream repository for current versions, supported providers, and security limitations.
