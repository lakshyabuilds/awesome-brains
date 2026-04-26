<div align="center">

<img src="https://raw.githubusercontent.com/lakshyabuilds/awesome-brains/main/assets/banner.png" alt="awesome-brains banner" width="100%" />

# 🧠 Awesome Brains

**Everyone is building an AI second brain. But which one is actually worth your time & money?**

This list cuts through the noise, with real verdicts, real costs, and real self-hosting data.

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/lakshyabuilds/awesome-brains?style=flat-square&color=gold)](https://github.com/lakshyabuilds/awesome-brains/stargazers)
[![Last Updated](https://img.shields.io/github/last-commit/lakshyabuilds/awesome-brains?style=flat-square&label=last%20updated)](https://github.com/lakshyabuilds/awesome-brains/commits/main)
[![License: CC0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg?style=flat-square)](LICENSE)

[Quick Comparison](#-quick-comparison) · [Self-Hostable](#-self-hostable-first) · [Cloud-Based](#-cloud-based) · [Open Source](#-open-source--free) · [Verdict Guide](#-how-to-pick) · [Contribute](CONTRIBUTING.md)

</div>

---

## Why this list exists

The PKM and AI second-brain space exploded in 2025–2026. There are now 17+ serious contenders, dozens of listicles ranking them by feature count, and zero resources that actually answer the question everyone is asking:

> *"I have $X/month and N hours to set this up — what should I actually use?"*

This list answers that. Every tool is rated on **5 dimensions that actually matter**: AI quality, setup pain, true cost, data ownership, and whether it'll still exist in 2 years.

---

## 📊 Quick Comparison

> Legend: ✅ Yes · ❌ No · ⚠️ Partial · 🔒 Paid only · 🧪 Beta

| Tool | Self-Host | AI Built-in | Free Tier | Cost/mo | AI Quality | Setup Pain | Verdict |
|------|:---------:|:-----------:|:---------:|:-------:|:----------:|:----------:|---------|
| [Obsidian](#obsidian) | ✅ | ⚠️ Plugin | ✅ | $0–$10 | ⭐⭐⭐⭐ | Low | **Best overall** |
| [reor](#reor) | ✅ | ✅ | ✅ | $0 | ⭐⭐⭐⭐ | Low | **Best local AI** |
| [AFFiNE](#affine) | ✅ | ✅ | ✅ | $0–$6 | ⭐⭐⭐ | Medium | **Best Notion alt** |
| [AppFlowy](#appflowy) | ✅ | ✅ | ✅ | $0–$10 | ⭐⭐⭐ | Medium | **Best team self-host** |
| [Logseq](#logseq) | ✅ | ⚠️ Plugin | ✅ | $0–$5 | ⭐⭐⭐ | Low | **Best for Zettelkasten** |
| [SiYuan](#siyuan) | ✅ | ⚠️ | ✅ | $0–$8 | ⭐⭐ | Medium | **Best for Chinese users** |
| [Notion](#notion) | ❌ | ✅ | ✅ | $0–$16 | ⭐⭐⭐⭐ | Low | **Best for non-techies** |
| [Mem.ai](#memai) | ❌ | ✅ | ❌ | $14.99 | ⭐⭐⭐⭐⭐ | None | **Best AI, worst value** |
| [Reflect](#reflect) | ❌ | ✅ | ❌ | $10 | ⭐⭐⭐⭐ | None | **Best minimalist** |
| [Tana](#tana) | ❌ | ✅ | ✅ | $0–$14 | ⭐⭐⭐⭐ | High | **Best for power users** |
| [Capacities](#capacities) | ❌ | ✅ | ✅ | $0–$9 | ⭐⭐⭐ | Low | **Best visual thinker** |
| [RemNote](#remnote) | ❌ | ✅ | ✅ | $0–$8 | ⭐⭐⭐ | Medium | **Best for students** |
| [NotePlan 3](#noteplan-3) | ❌ | ✅ | ❌ | $9.99 | ⭐⭐⭐ | Low | **Best for Apple users** |
| [Heptabase](#heptabase) | ❌ | ✅ | ❌ | $11.99 | ⭐⭐⭐⭐ | Low | **Best visual canvas** |
| [Dendron](#dendron) | ✅ | ❌ | ✅ | $0 | ⭐⭐ | High | **Best for developers** |

---

## 🏠 Self-Hostable First

*You own your data. No vendor lock-in. No subscription roulette.*

---

### Obsidian

> **The Swiss Army knife of PKM.** Local Markdown files + a plugin ecosystem of 1,500+ extensions. The AI story is plugin-based (Smart Connections, Copilot for Obsidian), but it's mature and battle-tested.

**GitHub:** [obsidianmd/obsidian-releases](https://github.com/obsidianmd/obsidian-releases) · ⭐ 10k+

| | |
|---|---|
| **Self-hostable** | ✅ — your files live on your disk |
| **AI quality** | ⭐⭐⭐⭐ — via plugins (Smart Connections, Copilot, Local AI with Ollama) |
| **True cost** | Free for personal. Sync: $4/mo. Publish: $8/mo. |
| **Data format** | Plain Markdown — survives any app death |
| **Setup pain** | Low — download and go |
| **Best for** | Power users, developers, academics, writers |

**Verdict:** If you want to start with zero risk and maximum longevity, start here. The AI plugins have caught up to native AI apps. Cons: no native mobile offline AI, plugin quality varies wildly.

---

### reor

> **Local-first AI PKM for people who take privacy seriously.** Runs LLMs locally via llama.cpp + Ollama. No API keys, no cloud, no telemetry. Your notes, your model, your hardware.

**GitHub:** [reorproject/reor](https://github.com/reorproject/reor) · ⭐ 8.5k

| | |
|---|---|
| **Self-hostable** | ✅ — 100% local, no internet required after install |
| **AI quality** | ⭐⭐⭐⭐ — depends on your hardware; 4-bit quants work on 8GB RAM |
| **True cost** | $0 forever |
| **Data format** | Markdown |
| **Setup pain** | Low — Electron app, one download |
| **Best for** | Privacy-first users, devs without cloud trust |

**Verdict:** The best local AI PKM available right now, period. If your threat model includes "I don't want my notes leaving my machine," this is your answer. Cons: AI quality ceiling is your GPU, not GPT-4o.

---

### AFFiNE

> **Notion + Miro, self-hostable, AI-native.** The edgeless canvas mode is genuinely differentiated. Strongest open-source alternative to Notion in 2026.

**GitHub:** [toeverything/AFFiNE](https://github.com/toeverything/AFFiNE) · ⭐ 50k+

| | |
|---|---|
| **Self-hostable** | ✅ — Docker compose, ~10 min setup |
| **AI quality** | ⭐⭐⭐ — GPT-4o powered; well-integrated, not just a chatbox |
| **True cost** | Free self-hosted. Cloud: $6.75/mo |
| **Data format** | JSON (exportable to Markdown/HTML) |
| **Setup pain** | Medium — Docker required |
| **Best for** | Teams, visual thinkers, Notion refugees |

**Verdict:** The most impressive open-source PKM in 2026. The infinite canvas + structured doc duality is genuinely useful, not a gimmick. Cons: mobile app lags behind desktop, AI costs extra on cloud plan.

---

### AppFlowy

> **Notion clone with actual self-hosting support.** More opinionated than AFFiNE, more stable, better suited for team workflows. AI features are solid and growing.

**GitHub:** [AppFlowy-IO/AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) · ⭐ 60k+

| | |
|---|---|
| **Self-hostable** | ✅ — AppFlowy Cloud (self-managed) or local mode |
| **AI quality** | ⭐⭐⭐ — GPT-4o/Claude backed, pluggable |
| **True cost** | Free self-hosted. Cloud: $10/mo |
| **Data format** | Delta (exportable to Markdown) |
| **Setup pain** | Medium — needs server for multi-device sync |
| **Best for** | Teams needing Notion features without Notion pricing |

**Verdict:** The best self-hosted team PKM. If you're running a small company and want to stop paying $16/user/mo to Notion, AppFlowy is the move. Cons: still catching up on third-party integrations.

---

### Logseq

> **Graph-based, outliner-first, privacy-focused.** The Zettelkasten power tool. Local-first with optional sync. AI via plugins. Built a cult following for good reason.

**GitHub:** [logseq/logseq](https://github.com/logseq/logseq) · ⭐ 35k+

| | |
|---|---|
| **Self-hostable** | ✅ — local-first by design |
| **AI quality** | ⭐⭐⭐ — plugins (LogSeq-GPT, Ollama integration) |
| **True cost** | Free. Sync: $5/mo (in beta) |
| **Data format** | Markdown + EDN (plain text survives) |
| **Setup pain** | Low |
| **Best for** | Zettelkasten practitioners, daily journalers, bidirectional link addicts |

**Verdict:** The gold standard for bidirectional linking and graph-based thinking. If your brain works in connections rather than hierarchies, nothing beats Logseq. Cons: DB version migration caused community friction; AI is plugin-dependent.

---

### SiYuan

> **Feature-complete self-hosted PKM with surprisingly deep AI integration for a lesser-known app.** Block-based, encrypted sync, excellent mobile apps.

**GitHub:** [siyuan-note/siyuan](https://github.com/siyuan-note/siyuan) · ⭐ 25k+

| | |
|---|---|
| **Self-hostable** | ✅ — Docker or local |
| **AI quality** | ⭐⭐ — OpenAI-compatible, needs your API key |
| **True cost** | Free. Cloud sync: $8/mo |
| **Data format** | Protobuf (Markdown export available) |
| **Setup pain** | Medium |
| **Best for** | Users wanting Notion-level features fully self-hosted |

**Verdict:** Underrated. Deep feature set, great mobile, end-to-end encrypted sync. Cons: smaller community, data format is not plain text.

---

### Dendron

> **Developer-first, VSCode-native hierarchical PKM.** Pure Markdown, Git-native, the most developer-aligned tool on this list. No AI built in — you build your own with Copilot or local LLMs.

**GitHub:** [dendronhq/dendron](https://github.com/dendronhq/dendron) · ⭐ 7.4k

| | |
|---|---|
| **Self-hostable** | ✅ — runs in VSCode, files on disk |
| **AI quality** | ⭐⭐ — no native AI; GitHub Copilot fills the gap |
| **True cost** | $0 |
| **Data format** | Plain Markdown + YAML frontmatter |
| **Setup pain** | High — requires VSCode comfort |
| **Best for** | Developers who live in VSCode and want PKM in their editor |

**Verdict:** Niche but excellent for developers. If you already have Copilot, Dendron + Copilot is a surprisingly capable setup. Cons: effectively solo-maintained, no mobile story.

---

## ☁️ Cloud-Based

*Lower friction. Higher trust required. Often genuinely better AI.*

---

### Notion

> **The incumbent.** Everyone has tried it; most teams still use it. AI features matured significantly in 2025–2026. Not a second brain by default, but powerful when set up right.

**Site:** [notion.so](https://notion.so)

| | |
|---|---|
| **Self-hostable** | ❌ |
| **AI quality** | ⭐⭐⭐⭐ — Notion AI is well-integrated, GPT-4o backed |
| **True cost** | Free (limited). Plus: $12/mo. AI add-on: $10/mo extra |
| **Data format** | Proprietary (Markdown export available, lossy) |
| **Setup pain** | Low |
| **Best for** | Non-technical users, teams, people who want everything in one app |

**Verdict:** The safe choice. Not the most innovative, but the most supported, the most integrated, and the one your team already knows. Cons: $22/mo for AI-enabled solo plan is steep; data export is painful.

---

### Mem.ai

> **The most AI-native tool on this list.** Automatically organizes everything. No folders, no tags — just write and let Mem's AI surface what you need. The best AI, the worst value proposition.

**Site:** [mem.ai](https://mem.ai)

| | |
|---|---|
| **Self-hostable** | ❌ |
| **AI quality** | ⭐⭐⭐⭐⭐ — the best in class; retrieval is genuinely impressive |
| **True cost** | $14.99/mo (no free tier) |
| **Data format** | Proprietary (Markdown export) |
| **Setup pain** | None |
| **Best for** | People who hate organizing and want AI to do it all |

**Verdict:** If AI quality is your #1 criterion and you trust the company, Mem is the best. But at $15/mo with no free tier and no self-hosting, the lock-in risk is real. Cons: company viability concerns have circulated in the community.

---

### Reflect

> **The minimalist's second brain.** Networked notes + daily notes + AI, all beautifully designed. No clutter, no feature creep. Exactly what it says on the tin.

**Site:** [reflect.app](https://reflect.app)

| | |
|---|---|
| **Self-hostable** | ❌ |
| **AI quality** | ⭐⭐⭐⭐ — GPT-4o integrated into the writing flow |
| **True cost** | $10/mo (no free tier) |
| **Data format** | Markdown mirror (good export) |
| **Setup pain** | None |
| **Best for** | Writers and thinkers who want speed over structure |

**Verdict:** The best-designed tool on this list. If you value aesthetics and frictionless capture over feature depth, Reflect wins. Cons: no free tier, limited collaboration, no self-hosting.

---

### Tana

> **The most powerful and most complex tool here.** Treats every piece of information as a typed node. Supertags, fields, live views. Closer to a personal database than a note-taking app.

**Site:** [tana.inc](https://tana.inc)

| | |
|---|---|
| **Self-hostable** | ❌ |
| **AI quality** | ⭐⭐⭐⭐ — AI commands are deeply integrated into the node system |
| **True cost** | Free (limited). Tana Starter: $7/mo. Pro: $14/mo |
| **Data format** | Proprietary JSON (export available) |
| **Setup pain** | High — paradigm shift required |
| **Best for** | Structured thinkers, researchers, PKM obsessives |

**Verdict:** The highest ceiling on this list. If you're willing to invest 20+ hours learning the model, Tana unlocks capabilities nothing else can match. Cons: steep learning curve will kill most casual users.

---

### Capacities

> **Object-based thinking made beautiful.** Everything is an object: people, books, ideas, notes. Visual, interconnected, and genuinely fun to use. Growing fast.

**Site:** [capacities.io](https://capacities.io)

| | |
|---|---|
| **Self-hostable** | ❌ |
| **AI quality** | ⭐⭐⭐ — AI assistant is capable, not exceptional |
| **True cost** | Free (limited). Pro: $9/mo |
| **Data format** | Proprietary (Markdown/CSV export) |
| **Setup pain** | Low |
| **Best for** | Visual thinkers, creative professionals, readers |

**Verdict:** The most enjoyable PKM to use daily. The object model clicks immediately for people who think in terms of "things" rather than documents. Cons: limited integrations, no desktop offline mode.

---

### RemNote

> **The only PKM built around spaced repetition from the ground up.** If remembering what you learn is as important as capturing it, nothing else competes here.

**Site:** [remnote.com](https://remnote.com)

| | |
|---|---|
| **Self-hostable** | ❌ |
| **AI quality** | ⭐⭐⭐ — AI flashcard generation is excellent; general AI is average |
| **True cost** | Free (limited). Pro: $8/mo |
| **Data format** | Proprietary (Markdown export) |
| **Setup pain** | Medium |
| **Best for** | Students, medical professionals, language learners, lifelong learners |

**Verdict:** The only tool that makes learning *stick*, not just capturing it. If you're in medicine, law, or any field requiring long-term retention, RemNote is in a category of one. Cons: clunky on mobile, dated UI.

---

### NotePlan 3

> **Calendar + notes + tasks, beautifully integrated for Apple users.** Markdown-native, iCloud sync, excellent AI writing features. The GTD tool for the Apple ecosystem.

**Site:** [noteplan.co](https://noteplan.co)

| | |
|---|---|
| **Self-hostable** | ❌ (files stored locally/iCloud) |
| **AI quality** | ⭐⭐⭐ — AI writing tools are solid, not groundbreaking |
| **True cost** | $9.99/mo or $69.99/yr |
| **Data format** | Plain Markdown (your files, your iCloud) |
| **Setup pain** | Low |
| **Best for** | Apple ecosystem users who want planning + PKM in one place |

**Verdict:** The best PKM for people who live in Apple Calendar and want their notes connected to their schedule. Cons: iOS/macOS only, no collaboration, no Android.

---

### Heptabase

> **Visual-first, card-based, canvas-native.** Think Miro meets Roam Research. The best tool for people who think spatially and want to see connections laid out on a canvas.

**Site:** [heptabase.com](https://heptabase.com)

| | |
|---|---|
| **Self-hostable** | ❌ |
| **AI quality** | ⭐⭐⭐⭐ — AI search and synthesis across the whole canvas is impressive |
| **True cost** | $11.99/mo (after 30-day free trial) |
| **Data format** | JSON + Markdown export |
| **Setup pain** | Low |
| **Best for** | Researchers, visual learners, people who think in whiteboards |

**Verdict:** The best tool for visual knowledge work — bar none. If you're a researcher who needs to synthesize large bodies of work spatially, Heptabase is worth every penny. Cons: no free tier post-trial, no team plan yet.

---

## 🔓 Open Source & Free

*Projects with public source code, regardless of self-hosting status.*

- **[reor](https://github.com/reorproject/reor)** — ⭐ 8.5k — local AI PKM
- **[AFFiNE](https://github.com/toeverything/AFFiNE)** — ⭐ 50k+ — Notion alternative
- **[AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)** — ⭐ 60k+ — team workspace
- **[Logseq](https://github.com/logseq/logseq)** — ⭐ 35k+ — graph-based outliner
- **[SiYuan](https://github.com/siyuan-note/siyuan)** — ⭐ 25k+ — block-based
- **[Dendron](https://github.com/dendronhq/dendron)** — ⭐ 7.4k — VSCode-native
- **[Obsidian](https://github.com/obsidianmd/obsidian-releases)** — closed core, open plugin ecosystem

---

## 🎯 How to Pick

**Answer these 3 questions:**

**1. Does your data leaving your machine make you uncomfortable?**
→ Yes → [reor](#reor) or [Obsidian](#obsidian)
→ No → continue

**2. Are you primarily solo or working with a team?**
→ Team → [AppFlowy](#appflowy) or [Notion](#notion)
→ Solo → continue

**3. What's your superpower — capturing, connecting, or remembering?**
→ Capturing → [Reflect](#reflect) or [Mem.ai](#memai)
→ Connecting → [Logseq](#logseq) or [Tana](#tana)
→ Remembering → [RemNote](#remnote)
→ Visual thinking → [Heptabase](#heptabase) or [Capacities](#capacities)

---

## 🧪 Honorable Mentions

Tools worth watching that didn't make the main list yet:

- **[Notesnook](https://github.com/streetwriters/notesnook)** — end-to-end encrypted, self-hostable, privacy-first note-taking
- **[Trilium Notes](https://github.com/zadam/trilium)** — self-hosted personal knowledge base with scripting
- **[Joplin](https://github.com/laurent22/joplin)** — open-source Evernote alternative with E2E encryption
- **[Standard Notes](https://github.com/standardnotes/app)** — encrypted, extensible, self-hostable
- **[Foam](https://github.com/foambubble/foam)** — VSCode-native Roam Research alternative
- **[Roam Research](https://roamresearch.com)** — the OG bidirectional links app; still relevant, no longer dominant

---

## 📈 The Market at a Glance (2026)

| Metric | Data |
|--------|------|
| AI-related GitHub repos | 4.3 million (+178% YoY) |
| `second-brain` tagged repos | 411 |
| PKM market size | $1.4B (growing) |
| Self-host vs cloud user split | ~35% prefer self-hosted |
| Top user concern in 2026 | Data privacy & AI lock-in |

---

## 🤝 Contributing

Found a tool that deserves to be here? See something wrong? [Contributing guidelines](CONTRIBUTING.md) explain exactly what we're looking for.

Every tool listed here has been evaluated on the same 5 criteria. We don't accept paid placements, sponsored entries, or submissions without self-tested verdicts.

---

## 📜 License

[CC0 1.0 Universal](LICENSE) — do whatever you want with this. Attribution appreciated, not required.

---

<div align="center">

**If this saved you hours of research, consider starring ⭐**

Made with opinions by [@lakshya.build](https://github.com/lakshyabuilds) · Updated weekly

</div>
