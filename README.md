- 👋 Hi, I’m Carlo
- 👀 I’m interested in Cybersecurity, especially OSINT and other information-gathering methods
- 🌱 I’m currently earning my certs in CYSA+ and Certified Pentester.
- 💞️ I’m looking to collaborate on OSINT and OppSec practices.

## What I've Been Building

**Home lab infrastructure** — Two Mac Minis networked over Tailscale with SSH key-based auth: one runs the primary workload, the other watches it and can take over if it goes down. Built out automated health checks, replicated backups, and self-healing recovery so the system repairs itself without needing me to SSH in.

**[Argus](https://github.com/VagabondCarlo/argus) — autonomous trading system** — A multi-service system (market scanner, LLM-assisted signal scoring, order execution, Telegram interface) that traded a paper account live for several weeks. Built a full research loop around it: backtesting, a "shadow book" for testing thresholds without risking capital, and rigorous after-the-fact analysis. Honest result: the engineering held up under real trading conditions, but the strategy itself never showed a durable edge — closed it out cleanly with a full write-up instead of chasing it further.

**Telegram bot interfaces** — Built the notification and control layer for Argus: live trade/signal broadcasts, an owner command interface, and a guarded guest chat mode with input/output safety screening.

**Gardening & planting app** — Currently building a local-first mobile app (React Native/Expo) for garden tracking, planning, and a zone/weather-aware planting almanac.

**Lab environment rebuild** — Currently troubleshooting and rebuilding local virtualization infrastructure (Oracle VirtualBox) as the base for an upcoming hands-on project.
