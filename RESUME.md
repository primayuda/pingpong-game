# Resume Guide

Project folder: clone or open this repo locally (e.g. `~/Development/pingpong-game`).

## Quick start

```bash
cd pingpong-game   # from your clone directory
open pingpong.html          # play locally
npm run dev                 # local Cloudflare preview
npm run deploy              # deploy to Cloudflare manually
```

## Main file to edit

- **`pingpong.html`** — game source (edit this)
- Run `npm run build` to copy it to `public/pingpong-game/index.html` before deploy

## Links

| Resource | URL |
|----------|-----|
| Live game | https://primayuda.dev/pingpong-game/ |
| GitHub | https://github.com/primayuda/pingpong-game |
| Developer site | https://primayuda.dev |

## Cloudflare

- **Worker name:** `pingpong-game`
- **Routes:** `primayuda.dev/pingpong-game*`, `www.primayuda.dev/pingpong-game*`
- **Auto-deploy:** push to `main` on GitHub
- **Recommended build command:** `npm run build`
- **Deploy command:** `npx wrangler deploy`

## What we built

- Single-file table tennis game (player left, AI right)
- Difficulty: Easy / Normal / Hard
- Points to win: 3, 5, or 7
- Spin physics and sound effects
- Deployed via Cloudflare Workers static assets
- Inspired by DeepLearning.AI coursework (Andrew Ng)

## Git status

Check before continuing:

```bash
git status
git pull
```
