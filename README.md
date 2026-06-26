# CafTea Tracker

An AI-powered daily tracker for caffeine and tea polyphenol intake, built with Claude API.

**Live demo:** https://anzhizhao6-design.github.io/caftea-tracker/

## What it does

- **Coffee mode** — log caffeinated drinks and track daily caffeine intake against the FDA-recommended 400mg limit
- **Tea mode** — log tea drinks and track daily polyphenol (EGCG) intake
- **Photo recognition** — upload a photo of your drink and let Claude identify it automatically
- **AI-powered advice** — get personalized recommendations based on your current intake and time of day
- **Daily log** — all entries are saved locally and reset each day

## How to use

1. Open the [live site](https://anzhizhao6-design.github.io/caftea-tracker/)
2. Enter your Claude API key (get one at [console.anthropic.com](https://console.anthropic.com))
3. Select Coffee or Tea mode
4. Type a drink name or upload a photo — Claude will estimate the content and give advice

## Tech

Built with vanilla HTML + JavaScript. Uses the Anthropic Claude API (claude-sonnet-4-6) for drink recognition and personalized health advice. No backend, no dependencies.

## Note

This tool provides estimates based on general knowledge. Caffeine content in independently-owned cafés may vary significantly from reported values.
