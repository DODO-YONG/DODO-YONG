# Hi, I'm MJ 👋

**Aspiring Network & Security Engineer** · building AI-assisted tools with Claude Code

I'm building a career in network and security engineering, with the goal of working in KY or IN.
I learn by building: in the past weeks I designed, shipped, and operated several small AI agents and web apps on my own, with security and zero running cost as ground rules.

[🌐 Workshop site](https://dodo-yong.github.io/Obsidian/) · [📓 Work journal (daily & weekly)](https://dodo-yong.github.io/Obsidian/journal/?lang=en) · [🧠 TRACER (live)](https://tracer-eosin.vercel.app/ccna/) · [📁 Main repository](https://github.com/DODO-YONG/Obsidian)

---

## 🎓 Education & Training
| Program | Status |
|---|---|
| AWS training program | In progress (2026) |

## 📜 Certifications
| Certification | Status |
|---|---|
| Google Cybersecurity Professional Certificate | ✅ Completed |
| Cisco CCNA 200-301 | 📚 In progress |

## 🛠️ Projects

| Project | What it does | Built with |
|---|---|---|
| 🧠 **[TRACER](https://tracer-eosin.vercel.app/ccna/)** — CCNA practice site | Public CCNA 200-301 practice site with Google sign-in. Serves questions from a 1,808-question bank with full explanations (including why each wrong choice is wrong), saves progress per account, and adds XP, titles, and quests. Includes an admin console (user roles, daily AI limits, activity log, flagged questions) and a natural-language admin command bar. | JavaScript · Vercel serverless · Supabase (Postgres, Auth) · Gemini (free tier) · Playwright tests on GitHub Actions |
| 📱 **Tracer Route** — Android app | Offline version of TRACER for Android with the question bank built in, English/Korean UI, anonymous error reports, and a privacy policy. Release build ready; Google Play closed testing next. | Capacitor · Android · Supabase |
| 🛡️ **[SENTINEL](https://github.com/DODO-YONG/security-agent)** — web security checker | Non-intrusive website security agent: checks authorization first, then reads only responses (headers, cookies, TLS, page content) and writes a report with risk levels and fixes. No attacks. | Python · Claude Agent SDK |
| 🎤 **MIRROR** — interview coach | Practice coach for AWS Leadership Principles interviews. Asks about the weakest principles first, digs in with follow-up questions, and scores answers on STAR structure, numbers, and principle fit. | Python · Claude Agent SDK |
| 💗 **[Heartline](https://dodo-yong.github.io/Obsidian/heartline/)** — conversational web app | Web app where users design a chat persona (personality, tone, relationship) and talk in a messenger-style UI, with an English-practice mode and built-in safety rules. Planned, built, tested, and presented in one day. | JavaScript · Python · Gemini |
| 🎧 **[SHADOW](https://dodo-yong.github.io/Obsidian/shadow/)** — English shadowing coach | Downloads audio from a video link, splits it into sentences, and records you while you hold Space. Compares your intonation curve and the words recognized against the original. Runs fully on the local machine. | Python · Whisper (local) · yt-dlp |
| 🧹 **SWEEPER** — laptop cleanup helper | Scans Downloads/Desktop without AI, then proposes cleanup; nothing moves until approved in the terminal, and deletions go to the Trash only. | Python · Claude Agent SDK |
| 🐛 **[worm-arena](https://github.com/DODO-YONG/worm-arena)** | Browser worm game with single-player and same-network multiplayer. | Python · HTML/JavaScript |

**Study logs:** [CCNA study log](https://github.com/DODO-YONG/ccna-study-log) (Packet Tracer labs) · [TryHackMe write-ups](https://github.com/DODO-YONG/tryhackme-writeups) (no flags or answers)

## 🧰 Skills
- **Networking:** routing, switching, subnetting · Cisco Packet Tracer · Wireshark
- **Security:** non-intrusive web checks (headers, cookies, TLS) · secret scanning with pre-commit hooks · least-privilege database rules · privacy policies
- **Development:** Python · JavaScript · HTML/CSS · SQL (PostgreSQL) · Linux shell
- **Cloud & DevOps:** Vercel · Supabase · GitHub Pages · GitHub Actions (CI, scheduled jobs) · Playwright end-to-end tests
- **AI tooling:** Claude Code · Claude Agent SDK · Gemini · multi-agent workflows (two AI assistants splitting tasks in parallel)

## 🧭 How I work
- **Security first:** the main repository is public, so keys live only in local env files and a pre-commit hook blocks anything that looks like a secret.
- **Zero extra cost:** everything runs on free tiers and existing subscriptions; daily limits protect free quotas.
- **Write it down:** every change is committed with a clear message, and a nightly job turns those commits into the work journal below.

## 📓 Recent work
<!-- journal:start -->
**Week of Nov 23 – Nov 29: Admin Tool Modernization and New Service Foundations** · [weekly review](https://dodo-yong.github.io/Obsidian/journal/?lang=en#w-2026-11-23)
> Expanded TRACER safely into production by adding an open-access mock admin portal and natural-language AI query tools.  
> Defined the brand name, visual design, and core mechanics for the dating service 'say when', successfully deploying its initial web beta.  
> Formulated cooperative multi-agent protocols and built automated systems for dispatching work progress reports.  

| Date | Highlights | Commits |
|---|---|---|
| [Nov 25](https://dodo-yong.github.io/Obsidian/journal/?lang=en#d-2026-11-25) | Built automated reporting emails to summarize and send work updates every night and weekend.<br><sub>Workshop & Wiki</sub> | 2 |
| [Nov 24](https://dodo-yong.github.io/Obsidian/journal/?lang=en#d-2026-11-24) | Named the dating app 'say when', completed web deployment, and tested user signups.<br><sub>say when (dating app), Workshop & Wiki</sub> | 55 |
| [Nov 23](https://dodo-yong.github.io/Obsidian/journal/?lang=en#d-2026-11-23) | Expanded learning platform admin features and established an equal dual-AI collaboration system<br><sub>TRACER, Workshop & Wiki, say when (dating app)</sub> | 31 |
| [Nov 22](https://dodo-yong.github.io/Obsidian/journal/?lang=en#d-2026-11-22) | Completed launch preparations for the network learning app and significantly expanded the question bank.<br><sub>Tracer Route, TRACER, SHADOW</sub> | 16 |
| [Nov 20](https://dodo-yong.github.io/Obsidian/journal/?lang=en#d-2026-11-20) | Deployed TRACER to production, built a question bank, and introduced a new English coach<br><sub>TRACER, SHADOW, Workshop & Wiki</sub> | 26 |

<sub>Updated automatically every night from my commit history · [full journal →](https://dodo-yong.github.io/Obsidian/journal/?lang=en)</sub>
<!-- journal:end -->
