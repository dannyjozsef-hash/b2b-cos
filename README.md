# B2B CoS Automation

This repo documents the automated reports running in the **#b2b-cos** Slack channel for the Nubank B2B Sales team.

---

## What's automated

Every day, a set of reports are posted to #b2b-cos automatically — no one needs to write or send them manually.

| Report | When | Who sends it |
|---|---|---|
| 🏪 **Merchant Monitor** | Weekdays at 09:30 | NuPay Update Bot |
| 📋 **Daily Digest** | Weekdays at 19:00 | Claude (via Danny's account) |
| 🎯 **Top of Mind** | Every Monday at 09:32 | Claude (via Danny's account) |
| 📊 **M-Team Update** | 4th Monday of each month | Claude (via Danny's account) |

There is also a **Feedback Review** that runs every Friday at 17:00 — it reads thread replies on the reports above, identifies structural improvement suggestions, and DMs Danny privately with proposals.

---

## What each report does

**Merchant Monitor** — Daily NuPay metrics (TPV, transactions, Share of Credit, NuPay Mix, WoW/MoM trends) for Uber, iFood, 99, and Amazon. Data comes from Databricks and is posted by the NuPay Update Bot.

**Daily Digest** — End-of-day roundup of the most important things that happened across B2B Slack channels in the past 24 hours. Only posts when there are at least 3 notable items.

**Top of Mind** — Weekly strategic priorities for the B2B leadership team. Surfaces action items with a suggested owner and things to keep an eye on, sourced from 13 B2B channels.

**M-Team Update** — Monthly leadership update with live OKR data (pulled directly from the B2B OKR spreadsheet), narrative highlights, concerns, what's next, and an AI progress section.

**Feedback Review** — Reads thread replies on all four reports, filters for structural suggestions, and proposes changes to the standing instructions. Danny approves in Cowork and the changes apply automatically to all future runs.

---

## How to make changes

**To update what the Claude reports say or how they behave:**
Reach out to Danny. Changes are made in Cowork and apply automatically — no code changes needed.

**To report a bug or suggest an improvement:**
Reply in thread to any report in #b2b-cos. The Feedback Review will pick it up on Friday and propose it to Danny.

**For full technical details:**
See [b2b-cos-automation-playbook.md](./b2b-cos-automation-playbook.md) — it has every channel ID, metric formula, formatting rule, and architecture diagram needed to fully reproduce the system.
