# AI Marketing Suite — CoWork OS Plugin Marketplace

A complete AI marketing workspace for business owners, installable directly into Claude CoWork.
Six plugins that work as a coordinated system — one setup wizard that configures everything, five specialist tools that activate automatically.

---

## How to install

1. Open Claude CoWork → Customise (sliders icon) → Plugins → + → Add marketplace
2. Enter: `epoch-two/ai-marketing-suite` (replace with your actual GitHub username/repo)
3. Click Sync → confirm the safety notice
4. Go to Browse Plugins → Personal tab → click + on each plugin

**Install order:** Start with AI Marketing Setup. Run it first before using the other five.

---

## The plugins

| Plugin | Slash commands | What it does |
|---|---|---|
| AI Marketing Setup | `/setup`, `/update-setup` | Onboarding wizard — interviews you about your business, generates a Business Context Block for Custom Instructions |
| Email Strategist | `/email-write`, `/email-sequence`, `/email-audit` | Emails, sequences, subject lines, calendars, audits |
| Ad Copy Writer | `/ad-write`, `/ad-hooks` | Facebook, Instagram, Google, YouTube, LinkedIn ads + hook libraries |
| Call Scripts | `/script-dm`, `/script-objection`, `/script-followup` | DM scripts, call scripts, objection handlers, follow-up sequences |
| SOP Builder | `/sop-build`, `/sop-audit`, `/sop-checklist` | Step-by-step SOPs, checklists, onboarding docs, audits |
| Knowledge Base | `/kb-write`, `/kb-audit` | Brand guides, FAQs, positioning docs, content audits |

---

## How it works

**Step 1 — Run `/setup`**
The Setup Wizard interviews you about your business conversationally (10 min). It generates a Business Context Block — a structured summary of your offer, ICP, brand voice, tools, team, and goals.

**Step 2 — Paste the Business Context Block into Custom Instructions**
Settings → Custom Instructions → first field → paste → save.

**Step 3 — All 5 tools are now configured for your business**
Every plugin reads your Custom Instructions automatically. They already know your business name, exact prices, ideal customer, brand voice, confirmed tools, and 90-day goals. No briefing. No re-explaining. Ever.

**When your business changes:** run `/update-setup` to refresh the Business Context Block in under 5 minutes.

---

## Requirements

- Claude desktop app (CoWork tab)
- Claude Pro plan or higher ($20/month)
- CoWork enabled in settings

---

## Self-hosting this marketplace

This repo IS the marketplace. To host your own:
1. Fork this repo to your GitHub account
2. Your marketplace URL is: `epoch-two/ai-marketing-suite`
3. Clients add that URL in CoWork → Customise → Plugins → Add marketplace

To add or update a plugin: edit the files in that plugin's folder and push to GitHub. CoWork syncs automatically.

---

Built by Epoch Two · epoch-two.com
