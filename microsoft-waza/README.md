# Microsoft Waza

Microsoft's open-source CLI and framework for authoring, testing, measuring, and improving AI agent workflows, skills, and custom agents. Waza provides scenario authoring, offline harness checks, graded trials, evidence inspection, CI regression gates, adversarial smoke tests, token-budget tooling, and interoperability helpers for repository-based skill development.

## Why it is trustworthy

- Official Microsoft repository with public documentation, release artifacts, tests, and CI.
- Apache-2.0 licensed Go implementation with explicit boundaries around mock runs, model quality, paid calls, and safety.
- Designed around reproducible evaluation evidence rather than unsupported benchmark claims.

## Key capabilities

- Scaffold projects, skills, evaluations, fixtures, and workflow scenarios.
- Run offline checks and model-backed evaluations with configurable executors and graders.
- Verify evaluation coverage against `SKILL.md` requirements and export CI-friendly results.
- Inspect evidence, compare token budgets, run adversarial harness smoke tests, and optimize skill candidates with held-out qualification.
- Integrate with GitHub Actions, Copilot SDK scenarios, and the Azure Developer CLI extension.

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/microsoft/waza/main/install.sh | bash
```

Then create a workspace and a skill:

```bash
waza init my-project --no-skill
cd my-project
waza new skill my-skill
waza check my-skill
```

## Source

- Repository: https://github.com/microsoft/waza
- Documentation: https://microsoft.github.io/waza/
- License: Apache-2.0
