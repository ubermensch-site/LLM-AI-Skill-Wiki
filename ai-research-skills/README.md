# AI Research Skills

A portable catalog of 17 Agent Skills for the full academic-research lifecycle: literature discovery, evidence-aware synthesis, gap analysis, research design, project memory, manuscript writing, Zotero workflows, and bounded delegation across coding agents.

## Why it qualifies

- Maintained by Wenyu Chiou with clear documentation, an MIT license, examples, schemas, and reproducible workflow artifacts.
- Substantive research tooling: the catalog is paired with an executable `research-hub` runtime and optional policy/checkpoint governance rather than being only a prompt collection.
- Strong recent community traction (450+ GitHub stars at discovery) and active maintenance.

## Highlights

- Eight-stage pipeline from discovery and literature triage through design, execution, writing, and release.
- Evidence-aware handoffs with explicit gap verdicts, provenance, anti-leakage rules, and human approval gates.
- Portable `SKILL.md` packages for Claude Code, Codex, Cursor, Gemini CLI, Hermes, OpenClaw, and generic Agent Skills hosts.
- Optional plugins for academic writing, Zotero CRUD, Codex delegation, and Antigravity delegation.

## Install

Claude Code marketplace:

```bash
claude plugin marketplace add WenyuChiou/ai-research-skills
claude plugin install research-workspace@ai-research-skills
```

For the full runtime, see the source repository's `research-hub-pipeline` setup and installation guide.

## Source

[WenyuChiou/ai-research-skills](https://github.com/WenyuChiou/ai-research-skills)
