# SkillHone

SkillHone is Tencent’s open-source system for continual Agent Skill evolution. When an agent encounters a reproducible failure—such as a missing script, broken reference, or stale instruction—it captures the evidence, repairs the complete skill repository, runs tests, and returns a reviewable local PR with the issue, diff, test result, and persistent decision history kept together.

## Why it qualifies

- Maintained by Tencent and accepted at the EMNLP 2026 Industry Track.
- MIT licensed, versioned, CI-backed, and documented with a reproducible repair walkthrough.
- Addresses skill maintenance as an engineering workflow, not merely prompt generation.
- Supports Codex, Claude Code, Cursor, Pi, and ZCode through a documented DeepSeek Harness integration.

## Key capabilities

- Runtime maintenance for missing files, broken scripts, stale instructions, and API drift.
- Evaluation-driven optimization against frozen datasets and verifiers.
- Isolated repair branches, regression tests, local PRs, approval gates, and decision-history records.
- Bundled Agent Skills, CLI, workbench, examples, and benchmark documentation.

## Install

Follow the upstream installation guide; the project recommends giving the agent this prompt:

```text
Install SkillHone from https://github.com/Tencent/SkillHone, following docs/install/skillhone.md. Verify the installation.
```

## Source

- Original repository: https://github.com/Tencent/SkillHone
- Paper: https://aclanthology.org/2026.emnlp-industry.105/

SkillHone is MIT licensed. Prefer the upstream repository for current installation steps and compatibility details.
