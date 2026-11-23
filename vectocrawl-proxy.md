---
title: "IPRoyal proxy"
layout: default
permalink: /vectocrawl-proxy/
lang: en
---

# IPRoyal proxy

## What it is and why it exists

Some websites refuse to talk to the free search and page-reading routes, usually because they treat the traffic as a robot. A **proxy** is a middleman that makes the request on the Bot's behalf, so the site sees an ordinary connection instead. IPRoyal is a company that sells this service. The app recommends it and has a field for its address, in the card **Better results (optional keys)**, on the row **Recommended: IPRoyal proxy**.

The row shows the price: about $6 to $7 per GB, paid to IPRoyal.

## Before you start

- **You need an account with IPRoyal.** You create it yourself. VectoBots does not sell it and does not see your payment.
- **You pay IPRoyal directly,** at about $6 to $7 per GB, as the app shows. That is the only price the app states. Check IPRoyal's own site for their current plans before you buy.
- **After signing up, IPRoyal gives you a connection address.** It looks like `http://user:password@host:port`, with your own details in place of the words. That is the address you paste into the app.
- **The server must be ready to store keys.** If the card says "Keys can't be saved on this server yet", the box is greyed out. This is a setup step on your server: ask your lead Bot, or whoever set up VectoBots for you, for help first.

Most people do not need this. Start with free search, and add a proxy only if your Bots keep reporting that sites refuse them.

## How to add it

- **Laptop:** open **Settings**, pick **AI accounts** on the left, scroll to **Better results (optional keys)**, and find **Recommended: IPRoyal proxy**.
- **Phone:** tap **More** at the bottom, then **Settings**, then **AI accounts**, and scroll to the same row. The back arrow returns you to the list.

1. Click in the box. Its example text is `http://user:password@host:port`.
2. Paste the whole address IPRoyal gave you.
3. Tap **Save**. You will see "Saved", and the row shows **Added**.

The address contains a password, and the app treats it like a key: it is stored safely and **never shown again**. Keep your own copy.

To take it out, tap **Remove**.

![Settings, AI accounts page showing the VectoCrawl card; the proxy row is further down in the keys card]({{ '/images/search-laptop.png' | relative_url }})

*The proxy row is in the keys card below this view. The screenshots are in English.*

## How it is used

- **Only after a site says no.** A Bot always tries the free route first. Only when a page refuses that does the app try once more through your proxy.
- **Each use counts toward the daily limit.** The same **Daily limit for paid keys** that covers Brave, Tavily and the others covers the proxy too. It starts at 100. When the limit is reached, the proxy stops for the day and the Bot is told the daily limit was reached.
- **It is for reading pages.** It does not change how the Bots search.

The proxy does not remove other safeguards. Bots still cannot be pointed at private network addresses.

## Real examples

- **A coach** wants a Bot to read the public programme page of a conference, but the site refuses the free route. After the proxy is added, the page opens.
- **A consultant** keeps getting "could not read that page" on a competitor's pricing page. The proxy gets past it, and the Bot's summary arrives.
- **A therapist** who only looks up general topics from large, open sites does not add a proxy, and loses nothing.

## Costs and limits

- Price: set by IPRoyal. The app states about $6 to $7 per GB, paid to IPRoyal.
- Each proxy request counts toward the daily limit for paid keys.
- A proxy is only used when the free route was refused, so the spend is usually small.
- Nothing is charged by VectoBots.

## Common problems and fixes

- **"That doesn't look like a proxy address. It should look like http://user:password@host:port."** The address was not in that shape. Copy the full connection address from your IPRoyal account again, including the `http://` at the start.
- **The box is greyed out.** Key storage is not set up on your server yet. Ask your lead Bot, or whoever set up VectoBots for you.
- **A page still will not open.** Not every site can be reached. For pages that need a sign-in or clicks, see [The Bot's browser]({{ '/vectocrawl-browser/' | relative_url }}).
- **"The daily limit for paid keys is reached."** Raise the daily limit on the same card, or wait. It counts over the last 24 hours.
- **You pasted the wrong address.** Tap **Remove** and add it again.

## Related features

- [VectoCrawl]({{ '/vectocrawl/' | relative_url }})
- [Better results with keys]({{ '/vectocrawl-keys/' | relative_url }})
- [The Bot's browser]({{ '/vectocrawl-browser/' | relative_url }})
- [Costs]({{ '/costs/' | relative_url }})

[All help articles]({{ '/' | relative_url }})
