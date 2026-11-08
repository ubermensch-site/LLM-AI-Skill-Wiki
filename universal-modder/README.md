# Universal Modder

A cross-agent game-development skill collection for modding PC games you own. Universal Modder combines Agent Skills-format workflows, a shared knowledge base, a CLI, and an MCP server so an agent can identify a game's engine, research prior art, build a mod, generate assets, verify it in the running game, and record reproducible field notes.

## Why it qualifies

- 9k+ GitHub stars with a substantial, actively maintained implementation.
- MIT-licensed and documented for Claude Code, Codex, Cursor, Gemini CLI, Copilot, and OpenCode.
- Includes real working examples for Terraria, Age of Empires II, and Minecraft × GTA V.
- Ships safety boundaries: backups before save changes, no anti-cheat/DRM bypass, no online cheating, and no game files or decompiled code in contributions.
- Includes validation and publishing checks, not just prompt files.

## Highlights

- `mod-any-game`, game reconnaissance, reverse engineering, asset, automation, video, and publishing skills.
- Engine playbooks for Unity, Unreal, Godot, Source, Bethesda, Minecraft, and many other ecosystems.
- `um` CLI for scanning installs, asset generation, sprite pipelines, screenshots, recording, backups, knowledge search, and checks.
- Knowledge base of versioned field notes that agents can search and extend through pull requests.

## Install

For skills only:

```bash
npx skills add https://github.com/rehan-remade/universal-modder
```

The repository also documents full plugin installs and the optional `fal` asset-generation integrations.

Source: [rehan-remade/universal-modder](https://github.com/rehan-remade/universal-modder)
