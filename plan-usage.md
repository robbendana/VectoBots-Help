---
title: "Plan usage"
layout: default
permalink: /plan-usage/
lang: en
---

# Plan usage

Your Claude plan and your ChatGPT plan both limit how much you can use in a given period. The app shows how much of each limit is used, so you are not surprised by a limit in the middle of a task. You see it on the **More** page and on **Costs**, and every Bot is told too, so a Bot can save its heaviest work for when there is room.

## The two kinds of limit

- **The 5-hour window.** A short allowance that starts over by itself a few hours after you start working. On Claude plans it begins with your first message and starts over five hours later.
- **The weekly window.** A larger allowance that starts over once a week, at a fixed time for your account.

Which limits you have depends on your plan, and the companies change them. This is what they say today:

- **Claude (Pro, Max).** Both a 5-hour window and a weekly limit. Some accounts have no 5-hour window. Claude's help center explains it, and your own page at claude.ai under Settings, then Usage, shows the exact figures.
- **ChatGPT (Plus, Business).** A 5-hour allowance, with a weekly limit that may also apply.
- **ChatGPT Pro.** OpenAI says Pro plans currently have no 5-hour limit, and weekly limits may apply. If your plan sends no 5-hour window, the app says "no 5-hour limit reported on this plan" and shows only the week. It never invents a figure.

Check the company's own page if you are unsure about your plan. The app shows what your plan reports. It does not assume it.

## How fresh the numbers are

The app looks again about every 5 minutes.

- **ChatGPT.** It reads the usage that ChatGPT's own tool records on your computer each time it works. This costs nothing.
- **Claude.** Every Bot run updates it. If no run has updated it for 5 minutes, the app sends one very short message on Claude's smallest model, only to receive the usage report. It uses a tiny part of your plan, it never runs while a Claude Bot is working, it slows to about once an hour when nothing has run since the last check, and it skips while your plan is in extra usage. It stops at once, for many hours, if Claude Code is signed in with a key instead of your plan. It ignores your own Claude Code settings and hooks. You can turn it off in Settings, under Usage.

Between readings the app tells you how old the reading is. A window that has already started over is marked as an **estimate** until the next reading, because the app has not heard the new figure yet.

## Measured and estimated

- **Measured:** the percent used and the reset time, exactly as the plan reported them, with the time of the reading.
- **Estimate:** anything shown after a reset, and any gap between readings. If you also use Claude or ChatGPT on another device, that use appears at the next reading, not instantly.

## What to do with it

- Above 85%, the tile turns amber. Do the most important work first.
- If a Bot hits a limit, its job waits calmly until the reset time and one card on Today tells you.
- On a $20 plan, check the 5-hour window before you start a long task. A long task can use most of a window by itself.

## Heads-ups from your Bot

The app also watches how fast a window has been filling. If, at that pace, a window would run out before it resets, your lead Bot tells you in plain words, for example: "At this pace your Claude 5-hour limit runs out around 3:40 PM, before it resets at 5:10 PM. I'll do the most important work first." It also tells you once when a window passes 85% used.

- It is an estimate. Use comes in bursts, so the time can move. It needs the window to be at least 20% used and some history before it says anything: 10 minutes for the 5-hour window, 6 hours for the week.
- You get at most one heads-up per window for each of the two reasons, never a repeat. They do not use up your Bot's own daily check-ins.
- It follows your Bot's **On its own** setting. Below **Check in**, the Bot does not start the message. It still knows, and says it when you ask or when it replies to you. Quiet hours and the daily limit also apply.

## Common problems

- **"Limit not reported yet".** The plan has not sent numbers yet. They appear within a few minutes of the first Bot run or check.
- **The ChatGPT plan shows only the week.** Your plan has no 5-hour window right now. That is what the plan reports.
- **A figure looks old.** The line says how long ago it was read. If it stays old, the sign-in may have expired. Sign in again in Settings.

## Related

- [Costs]({{ '/costs/' | relative_url }})
- [Monthly limit]({{ '/monthly-limit/' | relative_url }})
- [Which AI each Bot uses]({{ '/which-ai/' | relative_url }})

[All help articles]({{ '/' | relative_url }})
