# repo-docs-skills

**Repo-Docs** is a portable pair of `SKILL.md` workflows from the AI4GC Lab at Zhejiang University for keeping fast-moving codebases understandable after an agent session ends. It turns real implementation evidence into a walkthrough, code map, concept modules, references, glossary, change log, and synchronization rules.

## What it provides

- `repo-docs`: build, refresh, audit, or clean a repository documentation package.
- `repo-docs-zh`: a Chinese-language overlay for the same workflow.
- Evidence-first guidance that prioritizes current source, tests, configuration, commands, and artifacts over memory.
- A validation script for source locators, anchors, package structure, and lightweight or seed-mode repositories.
- Conservative sync rules that update the smallest documentation page needed when the code or reader model changes.

## Install

```bash
curl -fsSL https://github.com/YurunChen/repo-docs-skills/raw/main/install.sh | bash
```

To install into all supported agent directories from a checkout:

```bash
./install.sh --agent all
```

Then ask the agent to use the `repo-docs` skill to create or refresh documentation for the current repository.

## Why it is included

The repository is a substantive, MIT-licensed skill package with detailed workflow docs, examples, a public validation tool, and clear evidence and quality rules. It is maintained by the AI4GC Lab at Zhejiang University and had 400+ stars with active maintenance when reviewed.

Source: [YurunChen/repo-docs-skills](https://github.com/YurunChen/repo-docs-skills)
