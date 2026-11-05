# Paper Search Pro

[Paper Search Pro](https://github.com/O0000-code/paper-search-pro) is an Apache-2.0 literature-discovery skill for Claude Code, Codex, and other agents that load `SKILL.md`. It searches OpenAlex, Semantic Scholar, CrossRef, PubMed, arXiv, and topic-specific sources, uses evidence-bounded relevance screening, and produces self-contained HTML plus Markdown, CSV, BibTeX, RIS, and PRISMA-S-style audit outputs.

## Why it is trusted

- Apache-2.0 licensed with a documented, versioned workflow and reproducible output files.
- Uses public scholarly sources and clearly distinguishes accessible searches from paste-ready strategies for closed databases such as Web of Science and Scopus.
- Provides multiple search tiers, citation chasing, journal partitions, bilingual support, and an audit trail rather than presenting unsupported paper lists.
- Includes deterministic Python helpers, CI-validated dependency files, and a headless JSON mode for agent workflows.

## Installation

```bash
git clone https://github.com/O0000-code/paper-search-pro.git \
  ~/.claude/skills/paper-search-pro
export PSP_HOME="$HOME/.claude/skills/paper-search-pro"
python3 -m pip install -r "$PSP_HOME/scripts/requirements.txt"
```

Use the corresponding skills directory for Codex or another agent, and see the [source README](https://github.com/O0000-code/paper-search-pro) for setup, API-key guidance, and current instructions.
