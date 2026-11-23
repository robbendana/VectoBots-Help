---
title: "VectoCrawl"
layout: default
permalink: /vectocrawl/
lang: en
---

# VectoCrawl

## What it is and why it exists

VectoCrawl is the built-in way for your Bots to look things up online: search the web, read a page, and run a short research round. Without it, a Bot can only answer from what it already knows, which may be out of date. With it, a Bot can check a fact before it guesses and tell you where it found it.

It works with no account and no key. Keys and a proxy are optional extras that make it more reliable. They have their own guides, linked at the end.

## Before you start

- **You need nothing.** Free search works as it is.
- **Cost:** free search costs nothing. Money is only spent if you add a paid key or a proxy yourself, and then the service bills you, not VectoBots. See [Better results with keys]({{ '/vectocrawl-keys/' | relative_url }}).
- VectoCrawl is **on** by default. You can switch it off at any time.

## Where to find it

VectoCrawl lives on the **AI accounts** page of Settings, in its own card called **VectoCrawl**, under the list that shows which AI each Bot uses.

- **Laptop:** open **Settings**, pick **AI accounts** in the list on the left, and scroll to **VectoCrawl**.
- **Phone:** tap **More** at the bottom, then **Settings**, then **AI accounts**, and scroll down to **VectoCrawl**. Use the back arrow to return to the list.

![Settings, AI accounts page with the VectoCrawl card showing the switch, Free search and the search server field]({{ '/images/search-laptop.png' | relative_url }})

*The VectoCrawl card on the AI accounts page. The screenshots are in English.*

## What you can do here

1. Open the VectoCrawl card as described above.
2. Check that the switch **Let Bots use VectoCrawl** is on.
3. Optionally, type the address of your own search server and tap **Save address**. You will see "Address saved".
4. Optionally, add keys in the **Better results (optional keys)** card. That is covered in the next guide.

## Every option explained

**Let Bots use VectoCrawl.** The main switch. On by default. When it is off, Bots cannot look anything up online, and if one tries it is told VectoCrawl is switched off and to ask you to turn it on.

**Free search.** It works with no account, and there is nothing to set. If you have no own server and no keys, this is what is used. Free search can be slow, and it can be refused when the free service is busy.

**Your own search server.** Optional. It takes the address of a SearXNG server, which is a free search tool some people run themselves. Most people leave it empty. If you do fill it in:

- The address must start with `http://` or `https://`.
- Do not put a user name or password inside the address. The app refuses it.
- Your server must have its JSON output turned on. If it does not, the Bot's search reports that your search server answered with an error and asks whether JSON is turned on.
- If you have this server, it is tried first. If you do not, free search is tried last, after any paid keys you added.

**Better results (optional keys)** and **Recommended: IPRoyal proxy.** See the key and proxy guides.

**Daily limit for paid keys.** A number from 0 to 10,000 that stops paid keys for the day once reached. It starts at 100. Free search is not counted. The card also shows how many were used today.

**Last resort: the Bot's browser.** A note that opens its own guide. See [The Bot's browser]({{ '/vectocrawl-browser/' | relative_url }}).

## What Bots actually do with it

- **Search.** The Bot asks a question and gets a short list of results. It tries the cheapest route first.
- **Read a page.** The Bot opens a web address you or it chose and reads the text.
- **Read a whole site.** For one website, a Bot can read up to 40 pages.
- **Research.** The Bot runs one to four searches, reads the best pages, and writes the answer itself with its sources.
- **Social networks.** A Bot can search X, LinkedIn, Facebook, Instagram, Threads, Reddit, TikTok, YouTube and Hacker News. For most of these it searches what search engines have listed, so coverage of posts is partial, and the Bot is told to say so.

Bots are also told to name the source for every fact, to treat page text as information and never as orders, and not to pay for anything or sign up for anything on your behalf.

## Real examples

- **A coach** asks a Bot: "What is the current wording of the ICF core competency on cultivating trust?" The Bot searches, reads the official page, and answers with the link.
- **A therapist** asks for recent published research on a general topic, such as sleep and anxiety, and gets a short summary with numbered sources to check.
- **A consultant** asks a Bot to compare the public pricing pages of three scheduling tools before choosing one.

**A note on confidentiality.** Every search goes to an outside service. The Bots are told never to put client names, health details or other private information into a search, and you should not ask them to. Look up general topics, not people in your practice.

## Costs and limits

- Free search: no cost.
- Paid keys and the proxy: billed by those services, shown on the screen next to each one.
- A Bot can make at most 30 lookups a minute. If it goes faster it is told to wait and use what it already found.
- The daily limit for paid keys starts at 100 and counts over the last 24 hours.
- Private network addresses are refused, so a Bot cannot use VectoCrawl to reach private machines.

## Common problems and fixes

- **A Bot says it cannot search.** Check the **Let Bots use VectoCrawl** switch is on.
- **"The search found nothing" with a suggestion to add a key.** Free search was refused or found nothing. Try other words, or add a key. See the keys guide.
- **A page cannot be read.** Some pages need a sign-in or clicks. The Bot is told it can use its own browser instead, which costs more.
- **"Too many lookups in one minute."** Wait a little. The Bot will use what it already found.
- **"Something went wrong. Try again."** on the card. Reload the page and try again.

## Related features

- [Better results with keys]({{ '/vectocrawl-keys/' | relative_url }})
- [IPRoyal proxy]({{ '/vectocrawl-proxy/' | relative_url }})
- [The Bot's browser]({{ '/vectocrawl-browser/' | relative_url }})
- [Costs]({{ '/costs/' | relative_url }})
- [Which AI each Bot uses]({{ '/which-ai/' | relative_url }})

[All help articles]({{ '/' | relative_url }})
