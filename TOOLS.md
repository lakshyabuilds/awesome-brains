# Tools Deep-Dive Reference

This file contains extended data for every tool in the main list. Updated whenever pricing, features, or AI capabilities change materially.

*Last verified: April 2026*

---

## Rating Criteria

### AI Quality (⭐ 1–5)

| Score | What it means |
|-------|---------------|
| ⭐ | AI is an afterthought — basic autocomplete or chat bolted on |
| ⭐⭐ | Functional AI but requires heavy setup or your own API key with no UI polish |
| ⭐⭐⭐ | Solid AI integration — works reliably, covers core use cases |
| ⭐⭐⭐⭐ | AI is a genuine force multiplier — retrieval, synthesis, and generation all work well |
| ⭐⭐⭐⭐⭐ | Best-in-class — AI is the product, not a feature |

### Setup Pain (Low / Medium / High)

| Level | What it means |
|-------|---------------|
| Low | < 15 min from download to first note |
| Medium | 15–60 min; requires some configuration (Docker, plugins, API keys) |
| High | > 60 min or requires developer knowledge to unlock full value |

### Self-Hostable (✅ / ⚠️ / ❌)

| Symbol | What it means |
|--------|---------------|
| ✅ | Fully self-hostable; data never leaves your infrastructure |
| ⚠️ | Partial — local app but sync requires their servers, or self-hosting is experimental |
| ❌ | Cloud only; no self-hosting option |

---

## Extended Tool Data

### Obsidian

| Field | Value |
|-------|-------|
| Founded | 2020 |
| Company | Dynalist Inc. |
| Employees | ~10 (small, profitable) |
| Funding | Bootstrapped |
| Core file format | `.md` (plain Markdown) |
| Plugin ecosystem | 1,500+ community plugins |
| Key AI plugins | Smart Connections, Copilot for Obsidian, Local LLM (Ollama), Text Generator |
| Mobile | iOS + Android (native apps) |
| Offline | ✅ Full offline |
| E2E encryption | ⚠️ Sync uses E2E encryption; local vault is unencrypted |
| API | REST API (community plugin) |
| Pricing tiers | Free · Sync $4/mo · Publish $8/mo · Catalyst (one-time) $25–$100 |
| Data portability | ⭐⭐⭐⭐⭐ — plain `.md` files work in any editor |
| Community size | Large (100k+ Discord, active Reddit) |
| Longevity risk | Low — files outlive the app |
| Notable users | Researchers, developers, writers, academics |

---

### reor

| Field | Value |
|-------|-------|
| Founded | 2024 |
| GitHub stars | 8,500+ |
| License | AGPL-3.0 |
| LLM engine | llama.cpp + Ollama |
| Models supported | Any GGUF model; recommended: Phi-3, Mistral 7B, Llama 3 |
| Min hardware | 8GB RAM for 4-bit quants; 16GB for better models |
| Core file format | `.md` |
| Mobile | ❌ Desktop only (Electron) |
| Offline | ✅ 100% offline |
| E2E encryption | N/A — local only |
| API | ❌ |
| Pricing tiers | Free forever |
| Data portability | ⭐⭐⭐⭐⭐ |
| Community size | Small but active (GitHub Discussions) |
| Longevity risk | Low if you keep the files; medium for the app itself (small team) |

---

### AFFiNE

| Field | Value |
|-------|-------|
| Founded | 2022 |
| GitHub stars | 50,000+ |
| License | MIT |
| AI model | GPT-4o (cloud); bring-your-own API key (self-hosted) |
| Self-host method | Docker Compose |
| Mobile | iOS + Android (beta quality) |
| Offline | ✅ Desktop; ⚠️ Mobile |
| E2E encryption | ✅ On self-hosted |
| Core file format | JSON (Markdown/HTML export) |
| Pricing tiers | Free self-hosted · Cloud $6.75/mo · Pro $13.50/mo |
| Data portability | ⭐⭐⭐ — JSON export isn't universal |
| Community size | Large (30k+ Discord) |
| Longevity risk | Low — well-funded, large OSS community |

---

### AppFlowy

| Field | Value |
|-------|-------|
| Founded | 2021 |
| GitHub stars | 60,000+ |
| License | AGPL-3.0 |
| AI model | OpenAI + Anthropic (pluggable) |
| Self-host method | AppFlowy Cloud (self-managed Docker) or local mode |
| Mobile | iOS + Android |
| Offline | ✅ Local mode; ⚠️ Cloud mode |
| E2E encryption | ✅ Local mode |
| Core file format | Delta (Markdown export) |
| Pricing tiers | Free · Pro $10/mo · Team $10/user/mo |
| Data portability | ⭐⭐⭐ |
| Community size | Large (active Discord + GitHub) |
| Longevity risk | Low |

---

### Logseq

| Field | Value |
|-------|-------|
| Founded | 2020 |
| GitHub stars | 35,000+ |
| License | AGPL-3.0 |
| AI approach | Plugin-based (LogSeq-GPT, Ollama) |
| Mobile | iOS + Android |
| Offline | ✅ |
| Core file format | Markdown + EDN |
| Pricing tiers | Free · Sync $5/mo (beta) |
| Data portability | ⭐⭐⭐⭐ — EDN is parseable, MD is standard |
| Community size | Large |
| Longevity risk | Low (OSS, large community) |
| DB version | New DB version in active beta — migration path exists |

---

### Notion

| Field | Value |
|-------|-------|
| Founded | 2016 |
| AI model | GPT-4o |
| Mobile | iOS + Android (excellent) |
| Offline | ❌ (poor offline support) |
| E2E encryption | ❌ |
| Core file format | Proprietary (Markdown export lossy) |
| Pricing tiers | Free · Plus $12/mo · Business $18/mo · AI add-on $10/mo |
| Data portability | ⭐⭐ — export is lossy, especially for databases |
| Community size | Massive |
| Longevity risk | Very Low — well-funded, large user base |
| API | ✅ Public API |

---

### Mem.ai

| Field | Value |
|-------|-------|
| Founded | 2020 |
| AI model | Proprietary (GPT-4o based) |
| Mobile | iOS + Android |
| Offline | ❌ |
| E2E encryption | ❌ |
| Core file format | Proprietary (Markdown export) |
| Pricing tiers | $14.99/mo only (no free tier) |
| Data portability | ⭐⭐ |
| Community size | Medium |
| Longevity risk | Medium — limited pricing tier, community concerns about viability |
| Key feature | Automatic organization — no manual tagging required |

---

### Reflect

| Field | Value |
|-------|-------|
| Founded | 2021 |
| AI model | GPT-4o |
| Mobile | iOS + Android |
| Offline | ⚠️ Limited |
| E2E encryption | ✅ |
| Core file format | Markdown mirror (local + cloud) |
| Pricing tiers | $10/mo (no free tier after trial) |
| Data portability | ⭐⭐⭐⭐ — Markdown export |
| Community size | Small-medium |
| Longevity risk | Medium (small team, single price tier) |
| Key feature | Best-designed interface on this list |

---

### Tana

| Field | Value |
|-------|-------|
| Founded | 2022 |
| AI model | GPT-4o + custom |
| Mobile | iOS (Android pending) |
| Offline | ⚠️ Limited |
| E2E encryption | ❌ |
| Core file format | Proprietary JSON |
| Pricing tiers | Free · Starter $7/mo · Pro $14/mo |
| Data portability | ⭐⭐ |
| Community size | Engaged (Slack community) |
| Longevity risk | Medium |
| Key feature | Supertags + fields = most powerful data model |

---

### Capacities

| Field | Value |
|-------|-------|
| Founded | 2022 |
| AI model | GPT-4o |
| Mobile | iOS (Android limited) |
| Offline | ❌ |
| Core file format | Proprietary (Markdown/CSV export) |
| Pricing tiers | Free · Pro $9/mo |
| Data portability | ⭐⭐⭐ |
| Community size | Growing |
| Longevity risk | Medium |
| Key feature | Object-based model — every note type has a type |

---

### RemNote

| Field | Value |
|-------|-------|
| Founded | 2020 (MIT spinout) |
| AI model | GPT-4o |
| Mobile | iOS + Android |
| Offline | ⚠️ |
| Core file format | Proprietary (Markdown export) |
| Pricing tiers | Free (limited) · Pro $8/mo |
| Data portability | ⭐⭐ |
| Community size | Medium (strong student community) |
| Longevity risk | Low-medium |
| Key feature | Built-in spaced repetition — the only tool where this is native |

---

### Heptabase

| Field | Value |
|-------|-------|
| Founded | 2021 |
| AI model | GPT-4o |
| Mobile | iOS (limited) |
| Offline | ✅ Desktop |
| Core file format | JSON + Markdown export |
| Pricing tiers | $11.99/mo (30-day free trial) |
| Data portability | ⭐⭐⭐ |
| Community size | Growing |
| Longevity risk | Low-medium |
| Key feature | Canvas-native research — best for visual synthesis |

---

## Frequently Compared Pairs

### Obsidian vs Logseq
Both local-first Markdown tools. Obsidian wins on polish, plugin ecosystem, and mobile. Logseq wins on daily journaling flow and native graph database model. Most serious PKM users try both.

### AFFiNE vs Notion
AFFiNE wins on self-hosting, open source, and canvas. Notion wins on ecosystem, integrations, and mobile quality. If you need self-hosting, AFFiNE is the move. If you need integrations (Slack, GitHub, Figma), Notion.

### Mem.ai vs Reflect
Both are premium cloud-only tools. Mem.ai wins on AI intelligence; Reflect wins on design and E2E encryption. At similar price points, Reflect is the better long-term bet for privacy-conscious users.

### reor vs Obsidian + Local LLM
reor is simpler and more integrated; Obsidian + Local LLM plugin is more powerful but requires more setup. If you want local AI without configuration overhead, start with reor.

### Tana vs Notion
Different paradigms entirely. Notion is a document database. Tana is a typed knowledge graph. If you've tried Notion and found it too flat, Tana might be what you're looking for — but expect a significant learning investment.

---

*See [CONTRIBUTING.md](CONTRIBUTING.md) to update or add tool data.*
