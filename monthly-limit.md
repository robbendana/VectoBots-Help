---
title: "Monthly limit"
layout: default
permalink: /monthly-limit/
lang: en
---

# Monthly limit

The monthly limit is the amount of money you are comfortable spending on your Bots in one calendar month. You set it once. VectoBots then watches your spending and tells you when you are getting close.

It exists so a busy month never surprises you. It is a smoke alarm, not a lock on the door.

## Before you start

- Nothing to install and nothing to buy. The limit is a number you type.
- It counts the money your Bots spend through **API keys** (work you pay for per use). Work done on a plan, such as a Claude or ChatGPT subscription, has a flat fee and is not counted in dollars. See [Costs]({{ '/costs/' | relative_url }}).
- The default limit is **$180** a month. Change it to whatever fits you.

![The Costs page showing today, this week, this month, and the Limits card with Monthly limit set to 180 and At the limit set to Only warns]({{ '/images/limit-laptop.png' | relative_url }})

*The Costs page. The Limits card is where you set the Monthly limit. The screenshots are in English.*

## How to set it

1. Open **More**, then **Costs**. On a phone, the spending line at the top of the More page also opens Costs.
2. Under **This month**, tap **Change limit**. A **Limits** card opens.
3. In **Monthly limit**, type a number of US dollars, or use the **−** and **+** buttons.
4. Wait a moment. The app saves by itself and shows "Limit saved."

The page works the same on a laptop and on a phone.

## Every option explained

**Monthly limit.** A whole or decimal number of US dollars, from 1 to 100000. If you type something outside that range, the app tells you: "Enter a limit between 1 and 100000." The **+** and **−** buttons move the number in steps that grow with it: 5 up to $49, 10 from $50, 50 from $200 and 100 from $1000. The change saves about half a second after you stop pressing.

**At the limit: Only warns.** This line is information, not a switch. When you reach the limit the app does not cut your Bots off. It tells you.

## What the warnings look like

- At **80%** of your limit you get a spending-check message in chat from your main Bot, plus an alert in the app.
- At **95%** you get a notice message in the same place.
- Each warning arrives **once per month**. They start fresh when the next month begins.
- On the Costs page the bar turns amber from 80% and red from 95%. The message under it reads "Past 80% of the limit.", "Almost at the limit." or "Over the limit." and adds: "Bots keep working. Raise the limit below or slow down."
- Once you are past 80%, a short line also appears in the left column ("$152 of $190 this month") so you can see it without opening Costs.

## What the limit does not do

Your Bots keep working on what you ask them to do. The limit never stops a chat.

One detail from how the app is built: the daily check-ins that a Bot starts by itself are skipped once the limit is reached. Things you ask for are not.

A Bot can also have its own monthly cap, set in **About this Bot**. A Bot that reaches its own cap is paused. That is separate from this limit, and you will see "Paused · cap" next to its name on the spending screens.

## Example

A coach runs three Bots: one that drafts session summaries, one that handles scheduling, one that researches. She sets the limit to $60 because that is what she budgets for tools. By the 20th she gets the 80% message. She opens Costs, sees that the research Bot used most of it, and decides to raise the limit to $75 for this month instead of pausing the work. She never loses a day of work and never gets a surprise.

## Common problems

- **"Couldn't save the limit. Try again."** The change did not reach the server. Check your connection and type it again.
- **"Spending didn't load."** Tap **Try again**.
- **I passed my limit and nothing stopped.** That is how it is built. The limit only warns.
- **My plan work shows no dollars.** Plan work is a flat fee. It is shown as usage, not as money.

## Related

- [Costs]({{ '/costs/' | relative_url }}): see what was spent today, this week and this month.
- [Which AI each Bot uses]({{ '/which-ai/' | relative_url }}): the AI you pick decides whether work is paid per use or on a plan.

[All help articles]({{ '/' | relative_url }})
