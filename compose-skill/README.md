# Compose Agent Skill

[Compose Agent Skill](https://github.com/aldefy/compose-skill) gives coding agents practical, source-backed guidance for Jetpack Compose and Compose Multiplatform across Android, Desktop, iOS, and Web. It includes a routing `SKILL.md`, 35 reference guides, and Kotlin source excerpts from AndroidX and JetBrains Compose Multiplatform Core so agents can verify APIs instead of guessing.

## Why it is trusted

- Grounds recommendations in real `androidx/androidx` and `compose-multiplatform-core` source.
- Covers state, recomposition, navigation, animation, accessibility, performance, adaptive layouts, A2UI, TV, Wear, XR, Media3, and multiplatform APIs.
- Provides installation guidance for Claude Code, Codex, Gemini CLI, Cursor, Copilot, Windsurf, and other agents.
- MIT-licensed, with upstream source materials retaining their Apache-2.0 licensing.

## Installation

```text
# Claude Code
/plugin marketplace add aldefy/compose-skill
/plugin install compose-expert
```

For other agents, follow the [installation guide](https://github.com/aldefy/compose-skill/blob/master/docs/INSTALL.md) and consult the `skills/compose-expert/SKILL.md` entry point. See the [source repository](https://github.com/aldefy/compose-skill) for updates and migration notes.
