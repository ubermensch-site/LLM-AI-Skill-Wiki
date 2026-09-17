# nvidia-skillevaluator

NVIDIA's open-source framework for evaluating AI agent artifacts, with a strong focus on Agent Skills that follow the `SKILL.md` standard.

## Why it’s useful

- Provides a three-tier pipeline for deterministic validation, semantic overlap/deduplication, and live agent evaluation.
- Includes quality, schema, Unicode, PII, license, script-lint, and security-oriented checks, plus synthetic evaluation-dataset generation.
- Produces reports and CI-friendly gates that help teams assess whether a skill is safe, well-formed, non-redundant, and genuinely useful to an agent.
- Integrates with NVIDIA's Verified Skills pipeline and can run against local or hosted model providers.

## What’s included (high level)

- `validate`, `quality-check`, `security-scan`, `pii-scan`, `lint-scripts`, and rubric-evaluation commands
- Embedding-based similarity checks and context-optimization checks
- Tier 3 live evaluation through sandboxed agent runs, with configurable agents and environments
- CLI, documentation, tests, governance, security reporting, and Apache-2.0 licensing

## Install

```bash
uv tool install --python 3.13 "skillevaluator[all] @ git+https://github.com/NVIDIA/SkillEvaluator.git"
skillevaluator validate ./my-skill --checks schema,pii,license,quality,unicode,lint --no-dedup
```

## Trust signals

- Official NVIDIA repository
- Apache-2.0 licensed with documented governance, security practices, contributing guidance, and CI-oriented workflows
- Substantive implementation and documentation rather than a prompt-only collection
- Directly aligned with the Agent Skills specification and quality/evaluation infrastructure

## Source

- https://github.com/NVIDIA/SkillEvaluator
- https://docs.nvidia.com/skills/skillevaluator/
