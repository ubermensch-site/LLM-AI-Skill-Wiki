# Claude SEO — SEO Audit Skill

Comprehensive SEO analysis skill for Claude Code. Covers technical SEO, on-page analysis, content quality (E-E-A-T), schema markup, image optimization, sitemap architecture, AI search optimization (GEO), local SEO, maps intelligence, Google SEO APIs (Search Console, PageSpeed, CrUX, GA4), PDF report generation, and strategic planning.

## Key Commands

| Command | Description |
|---|---|
| `/seo audit <url>` | Full site audit with parallel subagent delegation |
| `/seo page <url>` | Deep single-page analysis |
| `/seo schema <url>` | Detect, validate, and generate Schema.org markup |
| `/seo geo <url>` | AI Overviews / Generative Engine Optimization |
| `/seo technical <url>` | Technical SEO audit (9 categories) |
| `/seo content <url>` | E-E-A-T and content quality analysis |
| `/seo local <url>` / `/seo maps` | Local SEO & Google Business Profile / maps intelligence |
| `/seo google [command]` | Google SEO APIs (GSC, PageSpeed, CrUX, Indexing, GA4) with PDF/HTML report generation |
| `/seo programmatic <url>` | Programmatic SEO analysis & planning with quality gates |
| `/seo competitor-pages <url>` | Competitor comparison page generator |
| `/seo hreflang <url>` | Multi-language hreflang audit & generation |

## Architecture

15+ sub-skills plus 10+ subagents under `~/.claude/skills/seo-*` and `~/.claude/agents/seo-*.md`. Optional extensions integrate DataForSEO (live SERP/keyword/backlink data) and AI image generation for SEO assets.

## Install

```bash
/plugin marketplace add AgriciDaniel/claude-seo
/plugin install claude-seo@AgriciDaniel-claude-seo
```

## Source

https://github.com/AgriciDaniel/claude-seo
