---
title: "The Bot's browser"
layout: default
permalink: /vectocrawl-browser/
lang: en
---

# The Bot's browser

## What it is and why it exists

Search and page reading cover most things a Bot needs to look up. A few jobs they cannot do: pages that need you to sign in, and pages that only show their content after someone clicks, scrolls or fills in a form. For those, a Bot can use its own web browser, clicking and typing the way a person would.

That is why the card in Settings calls it **Last resort: the Bot's browser**. It is for sign-ins and pages that need clicks, and it costs much more.

## Before you start

- **There is nothing to switch on here.** The card is a note, with a **Learn more** link to this page. It has no switch and no field.
- **It costs much more.** Working through a page click by click takes many more steps than reading text, and each step is AI work you pay for through your usual plan or key. That is why it is the last resort.
- **It is the Bot's own browser, not yours.** Each Bot has its own screen with a browser. It is not the browser on your laptop. Letting a Bot use your own laptop is a separate feature: see [Let Bots use your laptop]({{ '/laptop-control/' | relative_url }}).
- **You can watch.** Open the Bot's details (tap its name at the top of the chat) and tap **Computer** to see its screen. Watching and taking over a Bot's screen are part of Pro.

## Where you see it

- **Laptop:** open **Settings**, pick **AI accounts** on the left, and scroll to the bottom of the VectoCrawl area. The last card is **Last resort: the Bot's browser**.
- **Phone:** tap **More** at the bottom, then **Settings**, then **AI accounts**, and scroll down to the same card. Use the back arrow to return to the list.

## How a Bot decides

You do not choose the order. Bots are told to go from cheapest to most expensive:

1. **Search.** Ask the web a question.
2. **Read the page.** Open a web address and read its text. If the free route is refused, an optional proxy may be tried. See [IPRoyal proxy]({{ '/vectocrawl-proxy/' | relative_url }}).
3. **The browser.** Only when the first two cannot show the page.

When a page cannot be read, a Bot sees this message: "Could not read that page", followed by the reason, and a hint to use its browser if the page needs a sign-in or clicks, which costs more. A page with almost no text, for example one drawn entirely by scripts, gets the same hint.

## What it is good for

- A page behind a login, such as a members area you already belong to.
- A page that only loads its content after a click.
- Work that needs several steps on one site.

## What Bots will not do

- Bots are told not to pay for anything or sign up for anything on your behalf.
- If a site needs a sign-in, the Bot asks you for the login on a card in the chat. You type the user name and password into that card and tap **Save login**. The card then says "Saved in the vault. The Bot can sign in but never sees the password." Never type a password into a chat message.
- Anything risky, like sending, paying or deleting, still waits for your tap on a card.

## Real examples

- **A coach** asks a Bot to check, in a booking system they already use, which sessions are open next week. The page needs a login, so the Bot asks for it on a login card, then signs in with its browser.
- **A consultant** needs figures from an industry directory that only shows its table after a click on "Show all". Search and page reading come back empty, so the Bot opens the browser.
- **A therapist** should not use this for anything that shows client information. Keep client records out of any page a Bot opens for you, and use the browser only for public or administrative pages.

## Costs and limits

- No fixed price is shown in the app. The honest answer is "much more than a search or a page read".
- The cost is the AI work the Bot spends clicking, which shows up in [Costs]({{ '/costs/' | relative_url }}) like other Bot work.
- If you have set a [Monthly limit]({{ '/monthly-limit/' | relative_url }}), it applies.
- If the information is public text, ask the Bot to search or read the page instead. It is far cheaper.

## Common problems and fixes

- **A Bot says it cannot read a page and mentions the browser.** That is the last-resort hint. Decide if the page is worth the extra cost, then ask the Bot to go ahead.
- **A Bot keeps using the browser for easy things.** Tell it in the chat: "Search first, and read the page, and only use the browser if those fail."
- **The browser needs a login.** The Bot asks for it on a login card in the chat. Fill it in on the card, not in a message, so the Bot can sign in without ever seeing the password.
- **Nothing happens.** Open **Settings**, **Computer**, and look at **The Bots' screens**. You can restart a Bot's screen there with **Restart screen**.

## Related features

- [VectoCrawl]({{ '/vectocrawl/' | relative_url }})
- [Better results with keys]({{ '/vectocrawl-keys/' | relative_url }})
- [IPRoyal proxy]({{ '/vectocrawl-proxy/' | relative_url }})
- [Let Bots use your laptop]({{ '/laptop-control/' | relative_url }})
- [Costs]({{ '/costs/' | relative_url }})

[All help articles]({{ '/' | relative_url }})
