# Hey, I'm Carlo 👋

I build real, working software by teaming up with AI.

I come up with the idea, set the rules, and make the calls. AI (mostly
Claude Code) writes the code with me, tests it, and helps me find what's
broken. **Every project on this page was built that way**, and I'm upfront
about it, because that's the skill: knowing how to direct AI to ship
something that actually works, and knowing when it's wrong.

I'm based in New York. I'm into cybersecurity, especially OSINT and other
ways of gathering information, and I'm working on my **CySA+** and
**Certified Pentester** certs.

---

## How I work with AI

- **I own the problem.** Every project starts from something real I needed:
  trading research, a cluttered inbox, a home lab that has to stay up.
- **I write the rules.** My AI agents work under written project rules
  (like a `CLAUDE.md`): test every change, never touch security settings
  without a way to roll back, protect money first, do only what was asked.
- **I make it prove itself.** Tests, backtests, dry runs, and post-mortems.
  If the data says my idea doesn't work, I publish that too.
- **I ship and document.** Clear write-ups, changelogs, and honest results,
  so anyone can see what was built and why.

---

## What I've built

### [Argus](https://github.com/VagabondCarlo/argus): autonomous AI trading system
A multi-agent system with a market scanner, signal scoring, LLM-assisted
analysis, order execution, and a Telegram control interface. It traded a paper
account live for several weeks. I ran a 22-day trial, analyzed 2,559 signals,
found the bug that blocked trades for 19 days, and rebuilt it as v2 based on
the data. The engineering held up. The strategy never showed a lasting edge,
so I shut it down cleanly and wrote it up instead of chasing it.
106 of its commits are co-authored with Claude.

`Python` `FastAPI` `REST APIs` `SQLite` `Ollama / Llama 3.1` `Alpaca API` `Telegram Bot API` `Playwright` `Integration testing`

### [btc15](https://github.com/VagabondCarlo/btc15): prediction market research
Research tools for 15-minute Bitcoin contracts on Polymarket US. I
rebuilt the exchange's settlement math to the cent, backtested strategies, and
ran out-of-sample tests. The headline result is negative: the model doesn't
beat the market price. I published it anyway, because the method is the
point.

`Python` `Data analysis` `Backtesting` `Statistical testing` `Raspberry Pi` `systemd` `Unit testing`

### [inbox-triage](https://github.com/VagabondCarlo/inbox-triage): daily email bot
I had about 9,000 emails in Gmail and 57,000 unread in Yahoo. I cleaned them
up with an AI agent, then designed a bot so it never builds up again. It
sends a push alert to my phone for bills, debt, and payments, keeps the
senders I care about, and trashes marketing mail. Every rule comes from a
mistake we hit during the cleanup.

`Python` `IMAP` `Automation` `Push notifications` `launchd` `Unit testing`

### Home lab infrastructure
Two Mac Minis networked over Tailscale with SSH key auth. One runs the main
workload, and the other watches it and takes over if it goes down. Automated
health checks, replicated backups, and self-healing recovery, so it fixes
itself without me logging in.

`Tailscale` `SSH` `Bash` `macOS` `Monitoring` `Failover` `Backups`

### In progress
- **Gardening app:** a local-first mobile app (React Native / Expo) for
  garden tracking and a zone- and weather-aware planting guide.
- **Security lab:** rebuilding my virtualization setup (VirtualBox) for
  hands-on security practice.

---

## Skills

**AI:** AI-assisted development · Claude Code · AI agents and agentic
workflows · multi-agent systems · LLM integration · prompt engineering ·
local LLMs (Ollama)

**Building:** Python · FastAPI · REST APIs · SQLite · TypeScript and React
Native · Bash · Git and GitHub

**Shipping:** automated testing · backtesting · data analysis · risk
management · technical writing · post-mortems

**Infrastructure and security:** Linux and macOS · SSH · Tailscale
(WireGuard) · Raspberry Pi · systemd · launchd · OSINT · OpSec

---

I'm open to collaborating on OSINT, security, and AI automation projects.
