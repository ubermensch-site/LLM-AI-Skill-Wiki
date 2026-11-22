# ffmpeg-skill

A local video-editing Agent Skill that gives Claude Code, Cursor, Codex, and MCP clients a verified FFmpeg workflow: probe the media, edit it, inspect the result, and report measurable output instead of guessing.

## What it includes

- 42 local FFmpeg tools for cutting, joining, captions, overlays, motion graphics, HDR-to-SDR, LUTs, audio cleanup, loudness, sync, multicam, rendering, and delivery checks.
- A machine-readable contract describing inputs, outputs, capabilities, verification steps, and mutation boundaries.
- An MCP server whose tool definitions are derived from the same contract as the CLI.
- Review pages that show sources, processing steps, checks, timelines, and the resulting media locally.
- Dry-run, JSON output, timeout, explicit overwrite, plan files, and post-render verification workflows.
- Local-first operation with no cloud account or API key required for the core editor.

## Installation

```bash
npx ffmpeg-skill setup
```

The package installs the skill for compatible agents, checks for FFmpeg, and runs its doctor command. The upstream README documents manual installation, MCP setup, supported FFmpeg versions, and optional local transcription engines.

## Why it is trusted

The repository has substantial community traction, a clear local-only data boundary, CI, an OpenSSF Scorecard badge, compatibility testing, machine-readable contracts, and tests designed to catch tool/schema drift and accidental input mutation.

## Source

[kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill)
