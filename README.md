# Trendfinder — Cowork Plugin

Turn TikTok/Instagram trend data into content decisions inside Claude Cowork.

The backend only stores and scrapes; **all AI synthesis (trend analysis, scripts, avatar DNA) happens natively in Claude** inside your own Cowork seat.

## Install

```
/plugin marketplace add Tomadm21/trendfinder-cowork
/plugin install trendfinder@trendfinder
```

## Get started

You need two values from your Trendfinder provider: a **backend URL** and an **API key**.
After installing, say *„richte Trendfinder ein"* — the onboarding asks for both and walks
you through niches, your first avatar, scraping, and the Cockpit.

## What it does

- **Trends** — current TikTok/Instagram trends for your niche, with velocity signals
- **Avatar** — your themes, tone and style; scripts get written in your voice
- **Scripts** — hooks + short-video scripts matched to a trend
- **Cockpit** — a Live Artifact dashboard of trends and avatars
- Every action ends with an interactive next-step option block

Connection details are stored locally in `{workspace}/.trendfinder/config.json` and are never committed.
