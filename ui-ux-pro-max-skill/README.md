# UI UX Pro Max

An AI skill providing design intelligence for building professional UI/UX across multiple platforms and frameworks, centered on an **Intelligent Design System Generator**.

## How it works

1. User request ("Build a landing page for my beauty spa")
2. Multi-domain search across 5 databases in parallel (product type, style, color palette, landing-page pattern, typography)
3. Reasoning engine matches product → UI category, applies style priorities (BM25 ranking), filters industry anti-patterns
4. Outputs a complete design system: pattern + style + colors + typography + effects + anti-patterns to avoid + pre-delivery checklist

## Scale

- **67 UI styles** (Glassmorphism, Neumorphism, Brutalism, Bento Grid, AI-Native UI, etc.)
- **96 color palettes**, **57 font pairings**, **25 chart types**, **13 tech stacks** (React, Next.js, Vue, Svelte, SwiftUI, Flutter, etc.)
- **100 industry-specific reasoning rules** (SaaS, Fintech, Healthcare, E-commerce, Web3, etc.) each with recommended pattern, style priority, color/typography mood, key effects, and anti-patterns

Supports Claude Code, Cursor, Windsurf, Antigravity, Copilot, Kiro, Codex CLI, Gemini CLI, OpenCode, and more via the `uipro-cli`.

## Install

```bash
npm install -g uipro-cli
uipro init --ai claude   # or cursor, windsurf, copilot, codex, gemini, etc.
```

## Source

https://github.com/nextlevelbuilder/ui-ux-pro-max-skill
