# Code Animation Prompts

[Code Animation Prompts](https://github.com/XiaoyeCodes/code-animation-prompts) is a Claude Code and Codex skill for turning visual ideas into editable code-based animations. It combines 341 indexed styles, 196 reference stills, searchable prompt assets, a local style picker, an installation script, and an optional Playwright/Chromium/FFmpeg rendering workflow.

## Why it is trusted

- Substantive repository with a clear skill entry point, deterministic search scripts, rendering tools, examples, and installation tests.
- Documents the provenance and licensing of the bundled prompt and reference assets, including community additions.
- Uses an offline-first workflow: style discovery and prompt lookup need no API key or paid image service.
- Supports both Claude Code and Codex with explicit safeguards around existing installations and dependency setup.

## Installation

```bash
git clone https://github.com/XiaoyeCodes/code-animation-prompts.git
cd code-animation-prompts
python scripts/install_skill.py --target codex
# or: python scripts/install_skill.py --target claude
```

The skill can search styles and plan animations without rendering dependencies. Review the repository's [license and attribution guidance](https://github.com/XiaoyeCodes/code-animation-prompts/blob/main/LICENSE.md) before redistributing bundled third-party assets.
