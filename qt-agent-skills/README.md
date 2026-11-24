# qt-agent-skills

Official Qt AI skills for Qt software development and quality assurance. The collection covers Qt/C++ and QML code review, QML best practices, UI design, documentation, profiling, testing, CMake project setup, and Figma-to-QML workflows. Skills use the portable `SKILL.md` format and support Claude Code, Codex CLI, GitHub Copilot, Cursor, Gemini CLI, and other compatible agents.

## Why it qualifies

- Maintained by The Qt Company R&D as an official repository.
- Includes deterministic review rules, testing and profiling workflows, an official Qt documentation MCP server, and a documented cross-platform plugin structure.
- Substantive documentation, examples, CI-oriented conventions, and explicit licensing and AI-service usage terms.

## Highlights

- `qt-cpp-review` and `qt-qml-review` combine deterministic checks with deeper AI analysis.
- QML, Canvas2D, UI design, CMake, documentation, testing, and QML profiling skills cover the full Qt development lifecycle.
- Figma token extraction and component-generation workflows turn design systems into QML assets.
- Plugin and manual installation paths are documented for Claude Code, Codex, Copilot, Cursor, Gemini CLI, and more.

## Install

Claude Code:

```text
/plugin marketplace add TheQtCompanyRnD/agent-skills
/plugin install qt-development-skills
```

Portable installation with the Skills CLI:

```bash
npx skills add TheQtCompanyRnD/agent-skills
```

Consult the source README for individual-skill paths, plugin details, MCP setup, and platform-specific installation instructions.

## Source

[TheQtCompanyRnD/agent-skills](https://github.com/TheQtCompanyRnD/agent-skills)
