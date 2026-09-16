# Hey, I'm Jose 👋

CS & Engineering @ UCLA

Most of my projects are ones I deploy and operate by myself
🌐 [joseelizalde.dev](https://joseelizalde.dev) · 💼 [LinkedIn](https://linkedin.com/in/JoseElizalde) · 📫 joseelizalde02@g.ucla.edu

---

## 🔭 What I'm building

### [DailyCodeForce](https://github.com/ElizaldeJoseCS)
A self-hosted competitive programming platform. Seven Docker Compose services on a single DigitalOcean droplet: Next.js app, PostgreSQL, a sandboxed C++17 judge, a Go Discord bot, presence tracker, cron scheduler, and Nginx out front.

The judge runs untrusted submissions in under a second behind four enforced rlimits, inside a hardened container with pids caps, a `noexec` `/tmp`, and `no-new-privileges`. The scheduler holds a 90-day dedup window over a 113-problem pool and has shipped **81 consecutive daily problems with zero repeats**.

`Next.js` `TypeScript` `PostgreSQL` `Prisma` `Go` `Docker` `Nginx`

### Robinhood Discord Portfolio Bot
A C++ Discord bot (D++) talking to a Python FastAPI backend, serving live portfolio analytics at **486ms median / 783ms p99** on a single-vCPU 512MB VPS. Pickled session persistence and proactive token refresh mean it survives restarts without re-login and is fully up 2s after cold start.

Also screens all 503 S&P 500 tickers on momentum in 39 seconds, in a background thread, inside a 107MB peak footprint.

`C++` `Python` `FastAPI` `pandas` `NumPy` `systemd`

### [Jump The Gun](https://github.com/ElizaldeJoseCS) — Game Director @ UCLA ACM Studio
A first-person action shooter built with an 8-person team of programmers, artists and designers. I wrote a custom physics-based movement controller in C# to replace Unity's default character controller, and I run the team's Git branching and PR workflow.

`Unity` `C#` `Git`

## 🛠️ Stack

**Languages**
`C++` `C` `C#` `Python` `Go` `TypeScript` `SQL` `Bash`

**Backend & Infra**
`Linux` `Docker Compose` `FastAPI` `PostgreSQL` `Prisma` `Nginx` `systemd` `DigitalOcean`

**Web & Data**
`Next.js` `React` `Tailwind` `pandas` `yfinance`

**Tools**
`Git` `CMake` `Unity` `Neovim` `LaTeX`

---

<sub>Manjaro + Neovim. Codeforces on the side. Currently learning Vulkan, because eventually I want to write the engine instead of using one.</sub>
