# Contributing to Awesome Brains

First — thank you. This list is useful because people like you spotted gaps, found new tools, or corrected outdated information.

**The goal of this list is to be the most honest PKM comparison on the internet.** That means we have higher standards than most awesome lists. Please read this before opening a PR.

---

## What we accept

### ✅ New tools

A tool qualifies for the main list if:

- It's actively maintained (last commit or release within 6 months)
- It has a meaningful AI component — either built-in or a first-class plugin story
- It's used by real people (not a demo or prototype)
- You've personally used it for at least 2 weeks
- It meaningfully differs from existing entries

A tool qualifies for **Honorable Mentions** if it meets all the above except the AI requirement, or if it's too new to fully evaluate but shows genuine promise.

### ✅ Corrections and updates

- Pricing changed
- A feature shipped or was removed
- A star count is badly outdated
- A link is broken
- A verdict is factually wrong

### ✅ Improving verdicts

If you think a verdict is unfair or incomplete — open an issue first, explain your perspective, and we'll discuss before changing the text.

---

## What we don't accept

- Tools without an AI component (use another awesome list)
- Abandonware (no meaningful activity in 12+ months)
- Paid sponsorships or promotional placements
- Submissions from founders about their own tools without disclosure
- Vague verdicts like "great tool, check it out"
- Duplicate entries to game rankings

---

## How to submit a new tool

### Step 1: Open an issue first

Before writing a PR, [open an issue using the "Add a Tool" template](.github/ISSUE_TEMPLATE/add-tool.md). This lets us discuss whether the tool belongs here before you spend time writing it up.

### Step 2: Use this format exactly

Copy this template for the tool entry:

```markdown
### Tool Name

> **One sentence hook.** What makes it different in 7 words or fewer.

**GitHub/Site:** [link/to/repo](url) · ⭐ star count (if OSS)

| | |
|---|---|
| **Self-hostable** | ✅ / ❌ / ⚠️ Partial |
| **AI quality** | ⭐ to ⭐⭐⭐⭐⭐ |
| **True cost** | Actual numbers, not marketing language |
| **Data format** | Be specific (Markdown, JSON, proprietary, etc.) |
| **Setup pain** | Low / Medium / High |
| **Best for** | Specific user type, not "everyone" |

**Verdict:** 2–3 sentences. What does it do better than everything else? What's the main downside? No hype.
```

### Step 3: Update the Quick Comparison table

Add a row to the table at the top of README.md in alphabetical order within its section (self-hostable or cloud).

### Step 4: Submit your PR

Title format: `Add: [Tool Name]`

In the PR description, confirm:
- [ ] I've personally used this tool for 2+ weeks
- [ ] The pricing is accurate as of today's date
- [ ] I have no financial relationship with this tool
- [ ] I've added a row to the Quick Comparison table
- [ ] I've checked for existing entries that overlap

---

## Updating existing entries

Title format: `Update: [Tool Name] — [what changed]`

Always include a source or screenshot for pricing/feature changes. Don't change verdicts without explaining why in the PR description.

---

## Style rules

- **Sentence case** everywhere — not Title Case
- **No superlatives** without evidence — "best" is fine when you explain why; "amazing," "revolutionary," "game-changing" are not
- **Be specific about costs** — "$10/mo" not "affordable"
- **Be specific about AI** — say which model powers it if known
- **Verdicts need a con** — every entry must have at least one honest downside
- Keep verdicts under 60 words

---

## Code of Conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md). Be direct, be honest, be kind.

---

## Questions?

Open an issue or reach out to [@lakshyabuilds](https://github.com/lakshyabuilds).
