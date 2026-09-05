# /last30days

An AI agent-led search engine scored by upvotes, likes, and real money — not editors. Searches Reddit, X/Twitter, YouTube (full transcripts), TikTok, Hacker News, Polymarket, GitHub, Digg, Threads, Pinterest, Bluesky, Perplexity, and the web in parallel, then synthesizes a brief ranked by what people actually engaged with.

## Why it's different

Google aggregates editors; `/last30days` searches people. It resolves the right subreddits, X handles, and YouTube channels for a topic *before* searching (via a Python pre-research engine), merges cross-source story clusters, and includes a "Best Takes" section scoring for humor/virality alongside relevance.

## Example

```
/last30days OpenClaw vs Hermes vs Paperclip
/last30days Peter Steinberger
```

Can export shareable, dark-mode HTML briefs (`--emit=html`) for Slack/email/Notion, and supports trend monitoring via a SQLite watchlist store.

## Install

```
/plugin marketplace add mvanhorn/last30days-skill
/plugin install last30days
```
or `npx skills add mvanhorn/last30days-skill -g`

## Source

https://github.com/mvanhorn/last30days-skill
