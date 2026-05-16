# Claude Code — Project Context

## What this repo is

Personal website for Steve Bezner ("Bez") at **https://sbezner.com**.

- Single-file static site (`index.html`) — no build step, no framework
- Hosted on GitHub Pages, custom domain via Cloudflare
- Source: github.com/sbezner/stevebezner.ai

## Profile

Read `PROFILE.md` for complete context on Steve — identity, career, projects, tech stack, and personal details. Always use this as the source of truth.

## Git Rules

- **Only this repo (`sbezner/stevebezner.ai`) is committed to git**
- Do NOT initialize git repos in other local directories (e.g. `~/Projects/scripts`)
- Do NOT commit `.DS_Store` files
- All changes go directly to `main` branch
- Always push to `origin/main` after committing

## Coding Standards

- No build tools — pure HTML/CSS/JS in `index.html`
- All CSS is embedded in `<style>` tags in `index.html`
- All JS is embedded in `<script>` tags at bottom of `index.html`
- No comments in code unless non-obvious
- Mobile-first responsive design
- Dark mode is default; light mode toggled via `[data-theme="light"]` on `<html>`

## Site Sections (in order)

1. Nav (logo, links, theme toggle, LinkedIn)
2. Hero (name, typewriter, location, CTA buttons)
3. About (bio + 4 stat cards)
4. Philosophy (leadership manifesto + 3 pillars)
5. Work (Altus Group + City Council cards)
6. Career Timeline (1990–present, two-column)
7. Projects (12 sites in 4 category groups)
8. AI Stack (Fred / Claude Code / OpenClaw)
9. Running (3 race cards with links)
10. Tech Stack (60+ tags across 7 categories)
11. Footer

## Deployments

Push to `main` → GitHub Pages auto-deploys → live at https://sbezner.com in ~1-2 min.

## Daily AI Briefing

Prompt saved at `~/Projects/scripts/ai_briefing/prompt.md`.
Send via iMessage: `bash ~/Projects/scripts/MessagingApp/send_message.sh "+18324895760" "[message]"`
