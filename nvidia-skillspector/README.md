# nvidia-skillspector

NVIDIA's open-source security scanner for AI agent skills. It checks `SKILL.md` bundles and related agent artifacts for vulnerabilities, malicious behavior, prompt injection, data exfiltration, supply-chain risk, excessive agency, unsafe MCP configurations, and other security issues before installation.

## Why it’s useful

- Combines deterministic static analysis with optional LLM-based semantic analysis.
- Scans local skill folders, individual `SKILL.md` files, Git repositories, and archives.
- Produces terminal, JSON, Markdown, and SARIF reports for local review and CI/CD gates.
- Supports baselines and false-positive suppression so repeat scans emphasize new findings.
- Includes live OSV vulnerability lookups with an offline fallback and explicit resource limits.

## What’s included (high level)

- CLI, Python package, Docker workflow, and optional MCP server
- Detection for prompt injection, anti-refusal, data exfiltration, privilege escalation, supply-chain attacks, memory poisoning, tool misuse, trigger abuse, YARA matches, and MCP least-privilege issues
- Batch scanning, risk scoring, configurable thresholds, and machine-readable output
- Documentation, tests, security policy, contribution guidance, and Apache-2.0 licensing

## Install

```bash
uv tool install git+https://github.com/NVIDIA/skillspector.git
skillspector scan ./my-skill/
```

For static-only scanning without an LLM:

```bash
skillspector scan ./my-skill/ --no-llm
```

## Trust signals

- Official NVIDIA repository and part of NVIDIA's Verified Skills pipeline
- Apache-2.0 licensed with a documented security-disclosure process
- Large, substantive implementation with extensive tests, active maintenance, and CI-friendly reporting
- Directly addresses the security risks of installing third-party Agent Skills rather than acting as a thin prompt collection

## Source

- https://github.com/NVIDIA/SkillSpector
- https://docs.nvidia.com/skills/scanning-agent-skills
