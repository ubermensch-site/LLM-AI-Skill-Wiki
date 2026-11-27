# translate-book

An Agent Skill for translating complete books from PDF, DOCX, EPUB, or Markdown into another language with parallel sub-agents.

## Why it qualifies

- **2,400+ GitHub stars and 280+ forks** with active maintenance.
- Clear MIT licensing and detailed documentation.
- Uses manifest hashes, resumable chunk-level runs, glossary control, and merge validation instead of treating a long translation as one opaque prompt.
- Documents compatibility with Claude Code, Codex, Cursor, OpenClaw, and other Agent Skills-compatible runtimes.

## Capabilities

- Splits a book into manageable chunks and translates them concurrently.
- Preserves terminology with a generated, editable glossary.
- Supports resumable and selective re-translation when source text or glossary terms change.
- Validates chunk integrity before merging to HTML, DOCX, EPUB, or PDF.
- Includes baseline test assets and explicit safety rules for shell-facing inputs.

## Install

```bash
npx skills add deusyu/translate-book
```

## Source

[deusyu/translate-book](https://github.com/deusyu/translate-book)
