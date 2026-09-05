# GEO-SEO Claude Code Skill

"GEO-first, SEO-supported." Optimizes websites for AI-powered search engines (ChatGPT, Claude, Perplexity, Gemini, Google AI Overviews) while maintaining traditional SEO foundations.

## Key Commands

| Command | What it does |
|---|---|
| `/geo audit <url>` | Full GEO + SEO audit with 5 parallel subagents |
| `/geo quick <url>` | 60-second GEO visibility snapshot |
| `/geo citability <url>` | Score content for AI citation readiness |
| `/geo crawlers <url>` | Check AI crawler access (robots.txt) against 14+ AI bots |
| `/geo llmstxt <url>` | Analyze or generate an `llms.txt` file |
| `/geo brands <url>` | Scan brand mentions across AI-cited platforms |
| `/geo schema <url>` | Structured data analysis & generation |
| `/geo report <url>` / `/geo report-pdf` | Client-ready GEO report (markdown or PDF with charts) |

## Architecture

13 specialized sub-skills (geo-audit, geo-citability, geo-crawlers, geo-llmstxt, geo-brand-mentions, geo-platform-optimizer, geo-schema, geo-technical, geo-content, geo-report, geo-report-pdf, geo-prospect, geo-proposal, geo-compare) plus 5 subagents. Scoring weights: AI Citability & Visibility 25%, Brand Authority 20%, Content Quality/E-E-A-T 20%, Technical 15%, Structured Data 10%, Platform Optimization 10%.

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/zubair-trabzada/geo-seo-claude/main/install.sh | bash
```

## Source

https://github.com/zubair-trabzada/geo-seo-claude
