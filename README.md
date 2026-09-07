# ArenaRank

The first prototype of a **League of Legends Arena** leaderboard — a static page that reads a pre-computed player ranking and renders it.

**This is the early version.** The working system, with live Riot API polling, an Elo-style rating engine and background workers, is [**ArenaRanking**](https://github.com/JoaoVictor-C/ArenaRanking). This repo is kept as the record of where it started.

---

## What is here

| File | Purpose |
|---|---|
| `public/index.html` | The whole client — table rendering and sorting |
| `arena_rank.player.json` | A snapshot of player ranking data |
| `public/riot.txt` | Riot Games domain verification |

Ranking data was generated offline and committed as JSON; the page just reads it. That constraint is what motivated the rewrite — a ladder nobody updates stops being a ladder.

Deployed at [arena-rank.vercel.app](https://arena-rank.vercel.app).

## Status

Superseded by [ArenaRanking](https://github.com/JoaoVictor-C/ArenaRanking). Archived for reference.
