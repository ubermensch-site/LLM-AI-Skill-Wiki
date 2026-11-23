# Claude-Red

A curated library of offensive-security `SKILL.md` files for Claude’s Skills system, covering web application testing, identity, cloud, wireless, mobile, exploit development, fuzzing, infrastructure, reconnaissance, AI security, and reporting. The collection currently documents 78 skills across 23 categories.

## Why it qualifies

- Maintained by SnailSploit / Kai Aizen with a clear project identity and MIT license.
- Provides a real skill corpus rather than a prompt-only overview, plus an install script and a generated skill index.
- Includes explicit authorized-use guidance for red-team engagements, bug bounty work, CTF preparation, and security research.
- Recent maintenance added missing YAML frontmatter, corrected technique examples, and kept the collection operationally usable.

## Key features

- Progressive, triggerable `SKILL.md` files for focused attack surfaces.
- Web, API, cloud, AD, wireless, mobile, IoT, container, CI/CD, crypto, privilege escalation, post-exploitation, and AI-security coverage.
- Quick-start installation and sparse checkout support for individual categories.
- Documentation covering workflow selection, sandboxing, evidence, and reporting.

## Install

```bash
git clone https://github.com/SnailSploit/claude-red ~/.claude/skills/claude-red
```

For a category-only checkout, use the sparse-checkout commands in the upstream README.

## Source

- [SnailSploit/Claude-Red](https://github.com/SnailSploit/Claude-Red)
- [Upstream README](https://github.com/SnailSploit/Claude-Red#readme)

Use only for authorized testing and security research, and review the upstream project’s limitations before running any workflow.
