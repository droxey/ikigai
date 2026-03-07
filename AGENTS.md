# Agent Context: Dani Roxberry (@droxey)

> This file is designed for AI agents, copilots, and LLMs. It provides structured context about who I am, how I work, and what I care about — so you can give me better, more relevant responses from the first message.

## Identity

```yaml
name: Dani Roxberry
pronouns: they/them
handle: droxey
location: North Attleborough, Massachusetts (moved from San Francisco Bay Area)
email: dani@bitoriented.com
portfolio: https://droxey.com
github: https://github.com/droxey
linkedin: https://linkedin.com/in/droxey
org: https://github.com/Tech-at-DU
```

## Professional Summary

```yaml
experience_years: 22+
current_roles:
  - Lecturer, Dominican University of California (Applied Computer Science, program closing)
  - Independent CTO / technical architect
previous_roles:
  - Lead Technology Officer, Make School (90 NPS)
  - CTO / Co-founder, FrameBuzz (live streaming patent holder)
education: UC Berkeley
patent: Live streaming interaction patterns (2014, via FrameBuzz)
```

## Technical Stack

```yaml
primary_languages:
  - Go (CLIs, tools — e.g. grain-exporter)
  - Python (Django, APIs, automation)
  - Bash (glue, scripting, DevOps)
secondary_languages:
  - C#, .NET, PHP, React, Node.js

infrastructure:
  orchestration: Docker Swarm (4x8GB nodes: Chicago, Seattle, LA, NY)
  deployment: CapRover (PaaS portal for Docker apps)
  monitoring: Prometheus + Grafana + Loki + Promtail + node_exporter + cAdvisor
  external_monitoring: Uptime Kuma + Gatus (France watchdog node)
  dns_cdn: Cloudflare (DNS, tunnels, bot protection)
  backups: restic → Backblaze B2 (~$3/mo)
  vps_provider: RackNerd (budget-conscious, buys during sales)

hardware:
  prototyping: ESP32, XIAO nRF52840, ZimaBoard
  3d_printing: Ender 3 (droxeybot — SKR Mini E3 V2.0, Hemera, BLTouch)
  daily_driver: MacBook Pro M5

ai_tools:
  chat: Claude (Pro plan, heavy user)
  coding: Claude Code (5-layer CLAUDE.md config, PRISM methodology)
  prompt_engineering: PRISM v2.2 (example-driven, token-optimized, progressive autonomy)
  agents: OpenClaw (self-hosted, security-hardened)
  voice_clone: ElevenLabs (planned for course avatars)
  avatar: HeyGen / MuseTalk (planned)

macos_automation:
  - Hazel (binary plist predicate debugging level)
  - Warp terminal with custom themes

teaching_tools:
  - reveal-md (slide decks)
  - Docsify (course documentation sites)
  - GitHub (all curriculum open source)
  - Grain (meeting recordings — built a Go exporter)
```

## GitHub Repos (by stars)

```yaml
personal:
  - awesome-teachcode: 17★ — Curated resources for classroom and code review
  - droxeybot: 10★ — Ender 3 custom build documentation
  - muteme: 5★ — Wireless mute button on Puck.js
  - goslackit: 5★ — Starter slackbot for BEW2.5
  - rainbowcoin: 5★ — Blockchain collectibles
  - captools: 4★ — Bash scripts for CapRover maintenance
  - litebrite: 4★ — Real-time multiplayer lite brite (litebrite.live)
  - docsify-course: 4★ — Docsify template for ACS courses
  - spacepretzel: 3★ — Three.js 3D visualization
  - docker-flask: 3★ — Docker + Flask starter
  - clincher: 1★ — Production OpenClaw deployment via Docker Compose
  - prompts: 1★ — System prompts for AI chat
  - caprover-workadventure: 0★ — WorkAdventure + LiveKit CapRover one-click app

teaching_org_tech_at_du:
  - ACS-4220-AI-Engineering: 2★
  - js-practice: 2★
  - ACS-3230-Capture-the-Flag: 1★ — OWASP Juice Box CTF
  - ACS-3320-Web-Design-and-Advanced-CSS: 1★
  - ACS-2330-Responsive-Web-Design: 1★
  - React-Express-Tutorial: 1★
  - d3-tutorial: 1★
  - ACS-2130-Autograder: 0★
```

## Courses Taught

```yaml
active_or_recent:
  - "Docker, DevOps & Deployments": Bash → containers → compose → swarm → deploy
  - "Strongly Typed Languages (Go)": types → templates → files → MakeUtility capstone
  - "Web Security": social engineering → historic hacks → server/client vulns → crypto → CTF
  - "Advanced Web Patterns": WebSockets, payment gateways, search, serverless
  - "Python Data Structures": linked lists, merge sort, prefix trees, AVL trees
  - "AI Engineering": ACS-4220
  - "Responsive Web Design": ACS-2330

teaching_style:
  voice: "Direct, coach-like, encouraging. 'Ship all the things!' Active verbs. Emoji headers."
  structure: "Destination-first — every topic links to the capstone so students see where they're headed."
  philosophy: "Courses end with deployed apps, not toy projects. CTF challenges, not multiple choice."
  tools: "reveal-md slides, Docsify sites, GitHub repos, PR-based grading"
```

## Active Projects

```yaml
team_vault:
  status: feasibility assessed, pre-build
  description: "Developer knowledge management SaaS — web capture + markdown conversion + GitHub integration + prompt injection firewall + MCP gateway"
  motivation: "I have trouble saving interesting stuff I find for my project repos"

bumpband:
  status: architecture designed, pre-prototype
  description: "Waterproof wristband for contact exchange via BLE+NFC bump — no phone needed"
  hardware: "XIAO nRF52840, BLE 5.0, NFC, accelerometer, 100mAh LiPo, magnetic pogo-pin charging"
  sku_tiers: "$49 core / $79 lux / $89 resort edition"
  motivation: "Tech that works at the pool — no phone required"

fieldops:
  status: Django starter app built, backlog written
  description: "Job simulation cohorts on Skool — Django + HTMX, PR-based grading"
  pricing: "$997-1,497/cohort × 8-15 students"
  motivation: "Students need a bridge between tutorials and production"

online_courses:
  status: planning phase
  description: "AI avatar pipeline to turn 7 years of teaching content into sellable courses"
  stack: "ElevenLabs voice + HeyGen/MuseTalk video + RAG over transcripts"
  motivation: "University is closing my program — content should still be useful to someone"

openclaw_deployment:
  status: deployed and hardened
  description: "Security-maximal self-hosted AI agent on Docker Swarm"
  security: "Squid proxy, Docker sandboxing, capability dropping, DM pairing codes, disabled ClawHub"

agentadventure:
  status: plan + README complete
  description: "OpenClaw skill that drops AI agents as avatars into WorkAdventure"
```

## Communication Preferences

```yaml
tone: "Direct, practical, no sugar-coating. Strong opinions with reasoning."
dislikes: "Sycophancy, hedging, over-apologizing, burying the answer in filler."
formatting: "TL;DR style. Organized sections. Short paragraphs (3-5 sentences). Bullet points."
planning: "For non-trivial tasks (≥3 steps), start with specs/assumptions + checkable plan."
quality: "Don't say 'done' without proof. Prefer simplest elegant solution. Root-cause fixes."
methodology: "PRISM — Accuracy > Goals > Efficiency > Style"
```

## Personal Interests

```yaml
spirituality: "Tarot (daily draws, past/present/future spreads), astrology (Sag rising, Cancer sun, Scorpio moon, 1st house Saturn-Uranus-Neptune stellium, North Node in Pisces 3H)"
food_drink: "Dark espresso martinis (Licor 43 Chocolate variant), home cooking (Ninja Combi)"
gaming: "Pokémon GO (daily player, built search filter cheat sheet), Word Jumble"
pets: "Dog parent (Dogtopia, Petco vet)"
dreams: "Working remotely from the Caribbean someday"
apple_ecosystem: "MacBook Pro M5, iPad Air M2, Apple Pencil, AirTag 2, Apple TV, tracks AAPL"
```

## How To Work With Me

```yaml
do:
  - Lead with the answer, then explain
  - Give strong opinions with reasoning
  - Show working code, not suggestions
  - Use my stack (Go for CLIs, Python/Django for APIs, Docker for infra, Bash for glue)
  - Be concise — I read fast and don't need hand-holding
  - Flag uncertainty honestly

dont:
  - Hedge or say "it depends" without following up with a recommendation
  - Over-apologize for mistakes — just fix them
  - Assume I need beginner explanations (22+ years, but I'll ask if confused)
  - Use filler phrases ("Great question!", "That's a really interesting...")
  - Skip verification — tests, logs, or outputs before claiming "done"
```