---
title: "Costs"
layout: default
permalink: /costs/
lang: en
---

# Costs

Costs is the page that shows what your Bots' work costs. It gives you a quick answer to "how much have I spent today, this week and this month?" and shows where the money went.

It exists because AI work can be paid for in two very different ways, and it is easy to mix them up. This page keeps them apart.

## The two ways work is paid

- **Paid per use, with an API key.** Every piece of work has a price. This is the money the page adds up in dollars.
- **On a plan.** You pay a flat fee to a company, for example a Claude or ChatGPT subscription. Work on a plan is **not billed per message**. A plan has a 5-hour window and a weekly allowance. Each one starts over by itself at the time the page shows.

Money is shown for work paid with an API key. Work on a plan is shown as an estimate, marked with **≈**, and it is never added to your dollars. The page says it plainly: "≈ marks an estimate. Plans are a flat fee."

![The Costs page with the Today, This week and This month figures, the Limits card and the Plans section]({{ '/images/limit-laptop.png' | relative_url }})

*The Costs page on a laptop. The screenshots are in English.*

## How to open it

1. Open **More**, then **Costs**.
2. On a phone, the spending line at the top of the More page also opens Costs.
3. On a laptop, once you pass 80% of your monthly limit, a spending line appears in the left column. Click it to open Costs too.

## What you see, part by part

**Today, This week, This month.** Three big figures. Each is the money paid with API keys. Plan work is never added to these figures.

**The monthly bar.** Under **This month** a bar shows how much of your monthly limit is used, with "of $X limit". The bar is amber from 80% and red from 95%. **Change limit** opens the Limits card. See [Monthly limit]({{ '/monthly-limit/' | relative_url }}). If no limit is set, it reads "No monthly limit set".

**Your plan.** When a Bot runs on a Claude or ChatGPT plan, a tile shows the weekly share used, for example "Claude plan: 40% of this week used, resets Mon 9:00 AM". A second line can show the 5-hour window. When a plan is used up, the tile says **Used up** instead of a percent. The meters are as fresh as the last time the plan reported; if the reading is old the tile says how long ago it was read. If a plan has not reported anything, you see "no meter reported". The app never guesses a figure.

**Solid and striped bars.** A solid bar is money you pay (API keys). A striped bar is work on a plan.

**Plans.** A short list with one line for each plan sign-in: how many tasks and how many tokens (a token is a small piece of text the AI reads or writes) it used this month, and which Bots use it. The label on the right says "usage, not dollars".

**By Bot.** Which Bot cost what today. A Bot that has its own monthly cap shows a "cap" tag, or "Paused · cap" if it hit it. **Check daily spend per Bot** opens the same view.

**Last 30 days.** A small chart of paid spending per day, with the peak day. Work on plans appears as a dim dashed line above it.

**Voice calls.** If you made phone-style voice calls, they appear with the minutes and the cost.

## Examples

A therapist runs her Bots on a Claude subscription. Her Costs page shows $0.00 for today, this week and this month, and a plan tile at 35% of the week. That is normal: no money was paid per use. She only needs to watch the percent so she does not run out mid-week.

A consultant has one Bot on an API key for long reports. Costs shows $4.20 this month of a $50 limit. The By Bot list shows that Bot as the only one with spending.

## Common problems

- **"Spending didn't load"** Tap **Try again**.
- **Everything shows $0.00.** Either nothing ran yet, or your Bots run on a plan. Plan work is shown as usage and ≈ estimates, not dollars.
- **"Plan limit not reported" or "no meter reported".** The plan has not told the app its numbers yet. They appear after a Bot runs.
- **A plan figure looks old.** It is only as fresh as the last run. Run a Bot and look again.

## Related

- [Monthly limit]({{ '/monthly-limit/' | relative_url }})
- [Which AI each Bot uses]({{ '/which-ai/' | relative_url }})
- [Overnight thinking]({{ '/overnight-thinking/' | relative_url }}): has its own small daily spending limit.

[All help articles]({{ '/' | relative_url }})
