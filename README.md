# sbezner.com

Personal website for Steve Bezner ("Bez") — EVP at Altus Group, civic tech builder, AI enthusiast, and endurance runner based in Jersey Village, TX.

**Live site:** https://sbezner.com

## Stack

- Single-file static site (`index.html`) — no build step, no framework
- Hosted on GitHub Pages with custom domain via Cloudflare
- Dark/light mode toggle with localStorage persistence
- Scroll-triggered fade-in animations via IntersectionObserver
- Typewriter hero with cycling roles

## Sections

- Hero
- About (stats: 1995 Original ARGUS Developer, 6 Yrs City Council, 26.2 Marathon, 30+ Yrs CRE Tech)
- Philosophy (leadership manifesto)
- Work (Altus Group + City of Meadows Place City Council)
- Career Timeline (1990–present)
- Projects (12 public sites across civic tech, running, industry, food, AI, commerce)
- AI Stack (Fred / Claude Code / OpenClaw + MCP)
- Running (Cowtown Marathon, Chevron Houston Marathon, run-houston2)
- Tech Stack (60+ tags across 7 categories)

## Profile Files

- `personal.md` — detailed profile for AI context (source of truth)
- `gemini.md` — condensed profile summary
- `LinkedInProfile.pdf` — LinkedIn export (May 2026)

## Deploy

Push to `main` → GitHub Pages auto-deploys → live at https://sbezner.com

## Git Rules

- **Only this repo (`sbezner/stevebezner.ai`) should be committed to git**
- Do NOT initialize git repos in other local directories (e.g. `~/Projects/scripts`)
- Do NOT commit `.DS_Store` files
- All changes go to `main` branch — no feature branches needed for this site
