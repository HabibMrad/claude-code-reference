# ⚡ Claude Code — Master Reference

> The most complete, interactive, fact-checked guide to Claude Code — updated for v2.1.112 (April 2026)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-orange?style=for-the-badge&logo=github)](https://habibmrad.github.io/claude-code-reference)
[![Version](https://img.shields.io/badge/Claude%20Code-v2.1.112-7c6ef0?style=for-the-badge)](https://code.claude.com/docs/en/changelog)
[![License](https://img.shields.io/badge/License-MIT-3fb68b?style=for-the-badge)](LICENSE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Habib%20Mrad-0a66c2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/habib-mrad-7108b9148/)

---

## 🚀 Live Demo

👉 **[habibmrad.github.io/claude-code-reference](https://habibmrad.github.io/claude-code-reference)**

Or download `index.html` and open it locally — works fully offline.

---


| Skills & Agents | Memory & Files | Fact-Check |
|----------------|---------------|------------|
| ![Skills](https://raw.githubusercontent.com/HabibMrad/claude-code-reference/main/screenshots/08_skills_agents.png) | ![Memory](https://raw.githubusercontent.com/HabibMrad/claude-code-reference/main/screenshots/09_memory_env.png) | ![Corrections](https://raw.githubusercontent.com/HabibMrad/claude-code-reference/main/screenshots/10_corrections.png) |

---

## 📚 What's Inside

10 interactive sections covering every Claude Code feature:

| Section | Contents |
|---------|----------|
| 🗂️ **Overview** | What Claude Code is, all 8 surfaces, installation (macOS/Linux/Windows/WSL), permission modes, pricing |
| ⚡ **Slash Commands** | 50+ commands — session, config, tools, built-in skills, custom skills with YAML frontmatter |
| ⌨️ **Keyboard Shortcuts** | All shortcuts including new Ctrl+U/Y, transcript viewer, effort levels (low → xhigh → max) |
| 🔌 **MCP** | HTTP/SSE/stdio setup, OAuth, scopes, 400+ integrations, Channels, managed MCP (enterprise) |
| 🧠 **Skills & Agents** | Built-in agents (Explore/Plan/General/Bash), sub-agent teams, Agent SDK, worktrees |
| 📁 **Memory & Files** | CLAUDE.md hierarchy, CLAUDE.local.md, rules/*.md, auto-memory architecture |
| ⚙️ **CLI & Flags** | 25+ CLI flags, piping, scripting, headless mode, cost caps |
| 🔧 **Env Variables** | 30+ environment variables documented with context |
| 🔄 **Workflows** | Plan mode, Checkpoint+Iterate, voice mode, session continuity, scheduling |
| ✅ **Fact-Check** | 15+ corrections vs the viral Jan 2026 cheatsheet — all new v2.1.112 features documented |

---

## 🆕 Features Most Guides Miss

These are **not** in the popular Jan 2026 cheatsheet — all verified from official docs:

- `/ultrareview` — cloud parallel multi-agent PR review
- `/effort` — interactive slider with new `xhigh` level (Opus 4.7)
- `/recap` — summarize session context on return
- `/branch` / `/fork` — conversation branching
- `/tui fullscreen` — flicker-free rendering
- `/cost` — token + cache breakdown
- `/agents` — manage agent configurations
- `/less-permission-prompts` — auto-propose allowlist
- **Auto mode** — no longer requires `--enable-auto-mode` flag
- **PowerShell tool** — native Windows support (`CLAUDE_CODE_USE_POWERSHELL_TOOL`)
- **Plan file naming** — files named after your prompt (e.g. `fix-auth-race-snug-otter.md`)
- **`xhigh` effort level** — between `high` and `max`, Opus 4.7 only
- **`paths:` frontmatter** — path-specific skill/rule activation
- `ENABLE_PROMPT_CACHING_1H` — opt into 1-hour cache TTL
- `CLAUDE.local.md` — personal local notes (gitignored)
- `rules/*.md` — structured rules files separate from CLAUDE.md

---

## 🛠️ Usage

### Online
Visit the live demo: [habibmrad.github.io/claude-code-reference](https://habibmrad.github.io/claude-code-reference)

### Offline
```bash
# Clone the repo
git clone https://github.com/HabibMrad/claude-code-reference.git

# Open in browser
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

No dependencies. No build step. Pure HTML/CSS/JS.

---

## 🔗 Official Sources

This reference cross-checks against:

- [code.claude.com/docs](https://code.claude.com/docs/en/overview) — Official Claude Code docs
- [platform.claude.com/docs](https://platform.claude.com/docs/en/home) — Anthropic Platform docs
- [cc.storyfox.cz](https://cc.storyfox.cz) — Auto-updated daily cheat sheet
- [Claude Code Changelog](https://code.claude.com/docs/en/changelog)

---

## 📅 Version History

| Version | Date | Notes |
|---------|------|-------|
| v1.0 | April 18, 2026 | Initial release — Claude Code v2.1.112 |

---

## 👤 Author

**Habib Mrad** — AI Engineer at Touch Lebanon

Building multi-agent systems, NOC automation, and agentic AI workflows.

[![GitHub](https://img.shields.io/badge/GitHub-HabibMrad-181717?style=flat&logo=github)](https://github.com/HabibMrad)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-habib--mrad-0a66c2?style=flat&logo=linkedin)](https://www.linkedin.com/in/habib-mrad-7108b9148/)

---

## 🤝 Contributing

Found a missing command or a new feature? PRs welcome.

1. Fork the repo
2. Edit `index.html`
3. Open a PR with a brief description of what changed and the source link

---

## ⭐ If this helped you

Give it a star — it helps others find it.

And drop your favorite Claude Code trick in the [LinkedIn post](https://www.linkedin.com/in/habib-mrad-7108b9148/) comments. Let's build a community list.

---

## 📄 License

MIT — free to use, share, and modify with attribution.
