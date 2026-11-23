---
title: "Which AI each Bot uses"
layout: default
permalink: /which-ai/
lang: en
---

# Which AI each Bot uses

Each of your Bots thinks with an AI. This page lets you choose which AI each Bot uses, and, if you want, which model and how much effort it puts in.

It exists because different jobs suit different AIs. A Bot that drafts long reports and a Bot that sorts your inbox do not need the same one, and they may not cost the same either.

## Before you start

- You need at least one AI connected to your server: a subscription such as Claude or ChatGPT, or an API key. If an AI does not appear in the list, it is not set up yet.
- Changing the AI is free. What the work costs afterwards depends on the AI you pick. See "Costs" below.

![Settings, AI accounts, with the card Which AI each Bot uses: one row per Bot with a dropdown for the AI and a Model and effort fold]({{ '/images/ai-laptop.png' | relative_url }})

*Settings, AI accounts. The screenshots are in English.*

## How to change it

**On a laptop:**

1. Open **Settings**. A list of pages is on the left.
2. Click **AI accounts**.
3. In the card **Which AI each Bot uses**, find the Bot's row.
4. Open the dropdown on the right and choose an AI.

**On a phone:** tap **More** at the bottom, then **Settings**, then **AI accounts**, then follow steps 3 and 4. Use the back arrow to return to the list.

The app confirms with a note such as "Anchor will use Claude subscription. It starts a fresh conversation; what it knows stays."

## Every option explained

**The AI dropdown.** Lists the AIs your server can use. The ones the app knows are: **Claude subscription**, **ChatGPT subscription**, **Anthropic API key**, **DeepSeek API**, **OpenRouter API**, a **Local model** (one running on your own computer or network) and **Pi (its own settings)**. You only see those that apply to your setup.

**Model and effort.** A fold under each Bot. Open it to pick:

- **Model.** The default is **Default model**. The list shows the models that AI offers.
- **Effort.** The default is **Default effort**. Higher effort means the Bot thinks longer before answering; the choices depend on the model. If you switch to a model that does not offer the effort you had, the effort goes back to the default.

Leave both on the default unless you have a reason. Most people never need to touch them.

**The cost line under each Bot's name.** It tells you how that Bot's work is paid:

- **Uses your AI plan**: a flat subscription.
- **Paid per use with your key**: each piece of work costs money.
- **Uses its own settings**: a Local model or Pi. Cost depends on how that is set up.

## What happens when you change it

Moving a Bot to another AI **starts a fresh conversation**. What it knows stays: its memory and notes are kept. Only the running thread of conversation starts over.

Changing only the model or effort shows a short note, such as "Anchor will use the default model." or "Anchor will think at high effort."

If you pick a Local model, the app may show a warning. The app describes a Local model as one with no AI bill that is often weaker than Claude or GPT.

## Examples

A coach keeps her main Bot on her Claude subscription, since she already pays a flat fee. She moves a second Bot, which summarizes long articles, to a cheaper model on an API key. She watches the effect in [Costs]({{ '/costs/' | relative_url }}).

A consultant notices a Bot on a plan is using a lot of his weekly allowance. He moves its heavy jobs to an API key and keeps a monthly limit in place so there are no surprises.

Keep in mind that whatever a Bot reads is sent to the company behind the AI you choose. For client material, pick an AI whose terms you are comfortable with.

## Costs

The app does not set the prices. A **subscription** is a flat fee you already pay. An **API key** is billed per use by that company. The Costs page shows the difference. Setting a [Monthly limit]({{ '/monthly-limit/' | relative_url }}) is wise when Bots run on a key.

## Common problems

- **My AI is not in the list.** It is not connected on your server yet.
- **"Couldn't change that."** The change was not saved. Try again.
- **The Bot forgot what we were saying.** After a change of AI, the conversation starts fresh by design. Its notes and memory are still there.
- **The Bot list says "No Bots yet".** Create a Bot first.

## Related

- [Costs]({{ '/costs/' | relative_url }})
- [Monthly limit]({{ '/monthly-limit/' | relative_url }})
- [Overnight thinking]({{ '/overnight-thinking/' | relative_url }}): uses its own AI, shown on its screen.

[All help articles]({{ '/' | relative_url }})
