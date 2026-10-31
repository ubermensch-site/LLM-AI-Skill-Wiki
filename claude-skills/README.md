# claude-skills

A large, production-oriented collection of Claude Code skills, plugins, agents, and personas spanning engineering, DevOps, marketing, research, compliance, finance, productivity, and business operations. It also provides installation or conversion paths for Codex, Gemini CLI, Cursor, OpenClaw, Hermes Agent, Mistral Vibe, Windsurf, OpenCode, and other coding agents.

## Why it qualifies

- Maintained by Alireza Rezvani, a known AI tooling author, with strong community adoption (29k+ GitHub stars at discovery).
- Substantive repository rather than a prompt-only dump: hundreds of `SKILL.md` packages, Python utilities, references, tests/validation, plugin metadata, and multi-tool installers.
- MIT licensed and documented with explicit security-auditing guidance for installed skills.

## Highlights

- Engineering, DevOps, product, marketing/AEO, research, regulatory/QM, compliance, C-level, finance, and productivity skill families.
- Plugin bundles for Claude Code plus portable Agent Skills layouts for other coding agents.
- Security auditor, conversion/install scripts, reference libraries, personas, and orchestration patterns.
- Research and business-operations collections in addition to the core software-engineering skills.

## Install

Claude Code marketplace:

```text
/plugin marketplace add alirezarezvani/claude-skills
/plugin install engineering-skills@claude-code-skills
```

Portable install for compatible agents:

```bash
npx agent-skills-cli add alirezarezvani/claude-skills --agent codex
```

Consult the source README for the complete bundle list and platform-specific installation instructions.

## Source

[alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)
