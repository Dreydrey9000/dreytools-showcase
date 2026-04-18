# dreytools-showcase

Three-card tools showcase for drey tools.

**Live:** https://showcase.dreytools.com
**CF project:** `dreytools-showcase` → deploys to `dreytools-profile-card.pages.dev`

## What it is

Single-file HTML. Three overlapping cards that fan out on hover, each linking to a flagship Drey tool:

- DR. DREY (drdrey.com) — AI musician, 7 albums
- Life Dashboard (dashboard.dreytools.com) — personal OS (flagship, center, "YOU" badge)
- Dottie (dottie.dreytools.com) — phone AI

## Stack

Pure HTML + CSS + vanilla JS. Zero dependencies, zero build step.

## Deploy

```bash
wrangler pages deploy . --project-name dreytools-profile-card --branch main
```
