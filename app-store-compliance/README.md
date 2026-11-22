# App Store Compliance Playbook

A cross-platform compliance skill and pre-submission guard for iOS and Android projects. It helps agents and developers catch Apple App Store and Google Play rejection risks before submission while clearly separating automated findings from checks that still need a person.

## What it includes

- A documented reference for Apple and Google submission requirements.
- A shell guard that scans projects, ranks findings, reports the triggering file and line where available, and blocks critical risks before a submit command.
- Guidance for demo accounts, privacy declarations, SDK behavior, permissions, manifests, and listing/account checks.
- An installer and hook integrations for Claude Code, Codex CLI, Gemini CLI, OpenCode, Cursor, GitHub Copilot, Grok, Qwen Code, Kimi Code, Factory Droid, Augment, and Windsurf.
- A doctor command, dry-run and uninstall flows, explicit unsupported-tool notes, and a clear disclaimer that a clean scan is not approval.

## Installation

```bash
bash ~/repositories/app-store-compliance/scripts/install.sh --tool all
```

For a one-time scan, run the guard against an iOS or Android project. See the upstream README for the exact clone, install, audit, update, and tool-specific hook commands.

## Why it is trusted

The project is actively maintained, CI-backed, multi-agent, and unusually explicit about what automated scans can and cannot prove. Its checklist links claims to live Apple and Google sources, and its guard includes verification and safe uninstall paths.

## Source

[mjmirza/app-store-compliance](https://github.com/mjmirza/app-store-compliance)
