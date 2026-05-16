# Steve Bezner ("Bez")

## About Me

I'm Steve Bezner, though most people call me **Bez**. I'm based in Jersey Village, TX (Houston area) and work at the intersection of enterprise software leadership, civic tech, and entrepreneurship.

**Personal site:** [sbezner.com](https://sbezner.com) — registered via Cloudflare, hosted on GitHub Pages (repo: sbezner/stevebezner.ai).

---

## Professional Life

### Altus Group — 5.5 years total
- **EVP, Customer Enablement & Services** — February 2026–Present
- **Chief Software Development Officer** — December 2020–February 2026

My work spans:
- **Product development** for ARGUS Enterprise, ARGUS Connect, and the ARGUS Intelligence Platform
- **Client relationships** with major commercial real estate firms including Cushman & Wakefield, Newmark, JLL, and UBS
- **Internal AI adoption initiatives**, including a Level 1 support AI bot targeting ~3,000 cases/month in deflection
- **Resource planning** across Support, Training, Operations, and Consulting

### Career History
- **2016–2020:** EVP, R&D / Product — Altus Analytics, an Altus Group Company
- **2014–2020:** City Council — Alderman II, City of Meadows Place, TX (elected; six years in local government that directly shaped all civic tech projects)
- **2010–2016:** Vice President, Development & Service Delivery — Altus Group (led 100-person org)
- **2003–2010:** Co-Founder & Director, Application Development — Financial Softworks (co-founded commercial CRE financial software company)
- **2000–2003:** Director — Realm Business Solutions (formerly ARGUS Financial Software)
- **1995–2000:** Senior Programmer & Software Tester — ARGUS Financial Software (where it all started; original ARGUS developer)
- **1994–1995:** Accountant — The Coastal Corporation
- **1990–1994:** Shift Supervisor — Kinko's

### Education
- **Texas A&M University** — BBA, Accounting, Class of 1994 · Gig 'Em 🤘

### Philosophy
"What got us here today won't get us there tomorrow." I believe in trust over process, small autonomous teams, always being in requirement mode, and investing in people's professional development. Promote from within. Explore new technology.

---

## Side Projects & Civic Tech

### HarrisTaxAppeals
[harristaxappeals.org](https://harristaxappeals.org) — County-scale property tax protest tool for Harris County homeowners.

- **Stack:** Cloudflare Pages, R2, Workers; DuckDB pipelines on Mac Mini M4; PMTiles + MapLibre GL JS; sharded JSON by HCAD neighborhood code
- **Scale:** 1.1M+ residential parcels across Harris County
- **Methodology:** §41.43(b)(3) comparable-home approach — same HCAD neighborhood code, ±15% sq ft, ±10 years age, geographically closest comps
- **Infrastructure:** Enterprise-grade Cloudflare setup with gzip compression, rate limiting, bot fight mode
- **Origin:** Scaled from Jersey Village prototype (JVAppeals2026, ~2,172 parcels)
- **Monetization:** Tip jar via Buy Me a Coffee (civic-tone-preserving)
- **Repo:** github.com/sbezner/HarrisTaxAppeals

### JVAppeals2026
[jvtaxappeal.com](http://jvtaxappeal.com) — The original Jersey Village HCAD protest prototype that proved the concept.

- **Stack:** MapLibre GL JS, flat JSON, GitHub Pages
- **Scale:** ~2,172 Jersey Village parcels
- **Repo:** github.com/sbezner/JVAppeals2026

### JerseyVillage2026
[sbezner.github.io/JerseyVillage2026](https://sbezner.github.io/JerseyVillage2026/) — Voter guide for the May 2026 Jersey Village municipal election.

- **Stack:** Vanilla HTML/JS, flat JSON, GitHub Actions cron, Anthropic API (Claude with web search tools), Cloudflare DNS
- **Automation:** Fully automated — GitHub Actions fetches candidate social media daily, passes to Claude, publishes AI summaries to live site with no manual intervention
- **Repo:** github.com/sbezner/JerseyVillage2026

### run-houston2
[runhouston.app](http://runhouston.app) — Race discovery site for Houston-area runners.

- **Stack:** Vanilla HTML/CSS/JS, flat JSON, GitHub Pages
- **Workflow:** Quarterly research pipeline — Claude pulls live data from RunSignUp API, validates and normalizes it, commits verified race datasets
- **Coverage:** April 2026 through early 2027
- **Repo:** github.com/sbezner/run-houston2

### run-houston
[github.com/sbezner/run-houston](https://github.com/sbezner/run-houston) — Full-stack race platform (v1).

- **Stack:** React 18 + Vite frontend, FastAPI backend, PostgreSQL + PostGIS, Docker, full Jest test suite
- **Features:** Separate marketing and admin dashboards, E2E test coverage

### CREFuture
[sbezner.github.io/CREFuture](https://sbezner.github.io/CREFuture/) — Platform exploring AI and Commercial Real Estate.

- **Stack:** Astro, Tailwind CSS, GitHub Pages

### Sumner Lift Field Manual
[sbezner.github.io/Sumner](https://sbezner.github.io/Sumner/) — Service reference for Sumner lift repair personnel.

- **Stack:** Vanilla HTML, GitHub Pages

### TDC Tribute
[sbezner.github.io/TDC](https://sbezner.github.io/TDC/) — Texas Department of Corrections historical reference.

### The Plant Lab
[theplantlab.cc](https://theplantlab.cc) — Vegan food science resource (repo: VeganFoodScience).

- **Stack:** Jekyll, GitHub Pages, custom domain via Cloudflare

### Fred's Daily Briefing
[sbezner.github.io/Fred](https://sbezner.github.io/Fred/) — Web front-end for Fred's AI briefings.

- **Stack:** Vanilla HTML, GitHub Pages, client-side HN + dev.to API calls, 30-min localStorage cache

---

## E-Commerce

### Energized Engines
[energizedengines.com](https://energizedengines.com) — Shopify-based e-commerce business selling industrial and Sumner lift equipment parts. Customer base seeds ideas for industrial IoT and hardware products.

### Amy's Kitchen
[sbezner.github.io/Amy-s-Kitchen](https://sbezner.github.io/Amy-s-Kitchen/) — Meal planning and rating app for the Energized Engines team.

- **Stack:** React 18 + Vite + TypeScript, Firebase Auth (Google + email magic link), Firestore, Cloud Storage, Tailwind CSS, GitHub Pages

---

## Personal AI Stack

### Fred (Chief of Staff)
Local AI Chief of Staff running on **Mac Mini M4** via **OpenClaw**.

- **Access:** Telegram bot interface
- **Primary model:** Google Gemini 2.5 Flash
- **Secondary model:** Gemini 2.5 Flash-Lite (cost-saving)
- **Email integration:** Dedicated Gmail (fred.onduty@gmail.com) with Python-based IMAP/SMTP
- **Extension:** `/claude` Telegram slash command that shells out to the Claude CLI
- **Workspace:** `~/.openclaw/workspace/`

Claude Max subscription. Claude Code used daily for all implementation work.

---

## Running & Fitness

Active endurance runner logging substantial weekly mileage tracked via Apple Health. Running ties directly into civic tech work through run-houston2.

- **Races:** Cowtown Marathon (Fort Worth), Chevron Houston Marathon
- **Footwear:** Brooks and Xero (high-performance minimalist)

---

## Family

- Married to **Amy Wells Bezner**
- Daughter **Shelby**, who works at Gartner

---

## Interests & Curiosity Areas

- **Civic tech** — voter guides, tax appeals, race discovery for the Houston community
- **AI automation** — building a persistent personal productivity layer (Fred/OpenClaw)
- **Hardware/software product ideas** — SignBox digital signage (Pi 5 + Cloudflare SaaS), YardSense garden sensors (ESP32-C3, solar), Ring-on-Roku WebRTC/HLS bridge, industrial IoT for the Sumner customer base
- **Tesla Cybercab** — evaluating as a potential income-producing asset in Houston
- **Aviation** — recent incidents and general curiosity
- **Distributed compute** — exploring idle laptops via Ollama local inference and batch processing

---

## Full Tech Stack

### Languages
JavaScript, TypeScript, Python, HTML5, CSS3, SQL

### Frameworks & Libraries
React 18, Vite, Astro, Tailwind CSS, FastAPI, Flask, Leaflet.js, MapLibre GL JS, Jekyll, Hugo, Vanilla HTML/CSS/JS

### Data & Maps
DuckDB, PostgreSQL, PostGIS, Firebase Firestore, PMTiles, Flat JSON, Shapefile/HCAD, JSONL

### AI & ML
Claude (Anthropic), Anthropic SDK, Gemini 2.5 Flash, HuggingFace Transformers, PyTorch, Ollama, OpenClaw, MCP, VADER Sentiment, NVIDIA NIMs

### Cloud & Hosting
Cloudflare Pages, Cloudflare Workers, Cloudflare R2, GitHub Pages, GitHub Actions, Firebase, Netlify, Render, Docker

### Hardware & Embedded
Mac Mini M4, Raspberry Pi 5, ESP32-S3, ESP32-C3, STM32G474, ESP-IDF v5, FreeRTOS, CAN-FD Bus

### Commerce & Integrations
Shopify, Telegram Bot API, Gmail IMAP/SMTP, Firebase Auth, RunSignUp API, Reddit API, Apple Health, Buy Me a Coffee

---

## Location

Jersey Village, TX — northwest Houston.

---

## Git / Version Control Rules

- **Only the `sbezner/stevebezner.ai` repo should be committed to git**
- Do NOT initialize git repos in other local directories (e.g. `~/Projects/scripts`)
- Do NOT commit `.DS_Store` files
- All changes go to `main` branch directly
