---
title: "Better results with keys"
layout: default
permalink: /vectocrawl-keys/
lang: en
---

# Better results with keys

## What it is and why it exists

[VectoCrawl]({{ '/vectocrawl/' | relative_url }}) works for free. A free search can be slow, can be refused when the free service is busy, and cannot read every page. A **key** is a private code from a search service that you sign up for yourself. When you paste it in, your Bots use that service too, and the results get better and more reliable.

Keys are completely optional. If you are not sure you need one, you do not.

## Before you start

- **A key is something you get from the service's own website.** You make an account there, and they give you a long code. You paste that code into VectoBots.
- **The service bills you, not VectoBots.** The prices below come from the app. Check the service's own site before you sign up, because prices are theirs and can change.
- **The server must be ready to store keys.** If it is not, the card says "Keys can't be saved on this server yet." The boxes are greyed out. This is a setup step on your server, not something you can fix on this page: ask your lead Bot, or whoever set up VectoBots for you, for help.
- A key is stored safely and **never shown again** after you save it. Keep your own copy somewhere safe, such as your password manager.

## How to add a key

- **Laptop:** open **Settings**, pick **AI accounts** on the left, and scroll to the card **Better results (optional keys)**.
- **Phone:** tap **More** at the bottom, then **Settings**, then **AI accounts**, and scroll to **Better results (optional keys)**. The back arrow returns you to the list.

1. Find the service you want in the list.
2. Click in its box, which says "Paste the key", and paste your code.
3. Tap **Save**. You will see "Saved", and the row shows **Added**.

![Settings, AI accounts page, the VectoCrawl card and the start of the optional keys list]({{ '/images/search-laptop.png' | relative_url }})

*The optional keys card sits below the main VectoCrawl card. The screenshots are in English.*

To take a key out, tap **Remove** on its row. The row goes back to **Not added**.

## The services, one by one

Each row shows a small label: **Not added**, **Added**, or **Set on the server**. Some rows also show a price. A key set on the server has no Remove button, because it was put there outside the app.

- **Brave Search.** About $5 per 1,000 searches. A good first choice if you only add one.
- **Tavily.** Made for AI, with 1,000 free searches a month.
- **Exa.** Finds pages by meaning, with a small free credit each month. Good when you know what you mean but not the exact words.
- **Firecrawl.** Reads hard pages. Paid plan from about $16 a month. It is tried when a page cannot be read the normal way.
- **Jina Reader key.** Raises the free page-reading limit. Page reading through Jina already works without a key, at a low rate. The key raises that rate.
- **Recommended: IPRoyal proxy.** For sites that block free search. It has its own guide: [IPRoyal proxy]({{ '/vectocrawl-proxy/' | relative_url }}).

## In what order things are tried

You do not need to manage this, but it helps to know:

1. Your own search server, if you added one.
2. Brave, then Tavily, then Exa, for each one you added.
3. Free search, as the last resort.

The first one that returns results wins. For reading a page, the free route is tried first, then Firecrawl if you added it, then Jina Reader.

## Daily limit for paid keys

Below the keys there is a number box called **Daily limit for paid keys**. Paid keys stop for the day at this number. Free search is not counted. Under the name you see how many were used today, as "Today: N used."

- It starts at **100**. You can set any whole number from 0 to 10,000.
- It counts each paid call, over the last 24 hours.
- When the limit is reached, Bots keep working with free search only. The Bot is told that the daily limit was reached.
- With **0**, paid keys are not used at all.

Set it low while you are trying things out. It is your safety net against a surprise bill.

## Real examples

- **A solo coach** adds a Brave key and leaves the limit at 100. Their Bot now finds recent articles reliably when preparing a workshop, and the monthly bill stays small.
- **A consultant** who researches a lot adds Tavily for its free 1,000 searches a month, and sets the daily limit to 30 to stay well inside that.
- **A therapist** adds no keys at all. Occasional general questions work fine on free search, and nothing is spent.

## Confidentiality

Every search goes to an outside service, and a paid service sees your questions too. Never ask a Bot to search for a client's name, health details or anything that identifies someone in your practice.

## Costs and limits

- No VectoBots charge for any key. The service bills you directly.
- The only prices are the ones shown on the screen. Anything else, check with the service.
- Free search is never counted against the daily limit.

## Common problems and fixes

- **The Save button and the boxes are greyed out.** The card says "Keys can't be saved on this server yet." This is a setup step on your server. Ask your lead Bot, or whoever set up VectoBots for you, for help.
- **"Something went wrong. Try again."** Check you pasted the key on its own, with no extra spaces or words, and try again.
- **A key was saved but results did not change.** Check the daily limit. If today's count has reached it, paid keys wait until the count drops.
- **You pasted the wrong key and cannot see it.** Keys are never shown again. Tap **Remove** and add the right one.

## Related features

- [VectoCrawl]({{ '/vectocrawl/' | relative_url }})
- [IPRoyal proxy]({{ '/vectocrawl-proxy/' | relative_url }})
- [The Bot's browser]({{ '/vectocrawl-browser/' | relative_url }})
- [Costs]({{ '/costs/' | relative_url }})
- [Monthly limit]({{ '/monthly-limit/' | relative_url }})

[All help articles]({{ '/' | relative_url }})
