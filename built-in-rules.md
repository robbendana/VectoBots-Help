---
title: "Built-in rules"
layout: default
permalink: /built-in-rules/
lang: en
---

# Built-in rules

## What they are and why they exist

Two sets of rules shape how your Bots behave, and the app shows both on one page, **What Bots may do**:

1. **Built-in rules** set how every Bot **writes to you**: the answer first, short plain words, one question at a time.
2. **Approval rules** set what Bots **may do without asking you**: send, post, pay, delete and more.

Together they make sure your Bots talk like a calm assistant and never take a big step behind your back. This article explains both.

## Before you start

- Both sets are on for everyone and cost nothing.
- Only you, the owner, can see these pages and change the approval rules. Bots follow both sets but cannot change them.
- The built-in rules are for reading. You cannot edit them. To change how Bots write, add your own [house rules]({{ '/house-rules/' | relative_url }}). **Your own rules come first**: if they say something different, yours win.

## Part 1: The built-in writing rules

**To read them**

*Laptop:* click the gear at the bottom left to open **Settings**, click **What Bots may do**, scroll to the bottom and click **See the built-in rules**. Click **Hide the built-in rules** to close them.

*Phone:* tap **More** at the bottom, then **Settings**, then **What Bots may do**, scroll down and tap **See the built-in rules**. Use the back arrow to return to the list.

**What they say, in plain words**

- Start with the result or the answer. Then add only what you need to decide or do next.
- Keep it short: a few sentences or up to five simple bullets. Bold only for the one thing you must not miss.
- Reply in the language you write in, with simple sentences.
- Use plain words. No file paths, folder names, commands, codes or tool names in normal replies.
- Do not list every step. Say what was done in one line. The detail is in Activity.
- When a file is ready, hand it over through the app so you can open it, instead of saying where it is stored.
- Give every web link a name instead of pasting a bare address.
- If something fails, say what went wrong and what is needed from you, with no error codes or logs.
- Ask one question at a time, and say which option is recommended.
- Only when you are working on code, or ask for technical detail, may a Bot use developer words.

## Part 2: Approval rules

An approval rule answers one question: **should this Bot be allowed to do this, here, without asking me?** The app builds each rule as a sentence you can read, such as "Let every Bot post in public on sites matching *.example.com, but always ask first."

The page has these sections, from top to bottom:

- **You taught them.** Rules made when you answered a card with "Yes, stop asking". Each shows how many times it was used. **Undo** removes it and the Bot asks again. If a taught rule is off, **Turn on** brings it back.
- **Always asks you first.** A fixed box of things a rule can never switch off. See below.
- **Your own rules.** Rules you write yourself with **New rule**.
- **Approved for a while.** Temporary approvals you gave on a card ("for this task" or "for 30 min"), with the time left. They end by themselves.

## Making a new rule

1. On the **What Bots may do** page, click or tap **New rule**.
2. Fill in the form:
   - **Who.** **Every Bot**, or one named Bot.
   - **What.** The kind of action, for example send messages, post in public, delete things, pay for things, deploy previews, control your laptop, or "do other things that need a check".
   - **Where (optional).** A pattern for the target. Use \* for any text, for example \*@example.com. Leave it empty to cover everything of this kind.
   - **Decision.** **Allow without asking**, **Always ask first** or **Never allow**.
   - **Note (optional).** Why you made the rule. Up to 200 characters.
3. Read the line **This rule says**. It updates as you change the form. If it is not what you mean, change it.
4. Click **Save rule**. A message says "Rule saved."

On each rule you can use the switch to turn it off and on, **Edit** to change it, or **Delete** (the app asks "Delete this rule?" and you choose **Delete** or **Keep**). A turned-off rule stays in the list but does nothing. Each rule also shows how often it has been used.

When rules overlap, the most specific one wins. You can have up to 200 rules. A target can be up to 120 characters.

## What a rule can never change

The box **Always asks you first** lists these. A rule can only make them ask or be blocked, never allow them:

- Sending emails and messages.
- Posting in public.
- Paying for anything.
- Going live (production deploys and publishing packages).
- Saving or changing a skill.
- Pushing to the main branch is blocked. A rule can turn it into a question.
- Anything you said no to earlier in the same task.
- Anything that touches saved passwords or the Bots' own safety settings, which is always blocked.

If you try to allow one of these, the app says: "A rule can't let a Bot ... without asking." You can still make a rule that asks or blocks. In the form, **Allow without asking** is greyed out as "(not possible here)" for these kinds.

## Examples for a solo practice

- **A coach with a calendar app:** "Let every Bot use connected tools that change things on tools matching the calendar app, but always ask first." You see each change before it happens.
- **Block an action completely:** "Never let every Bot delete things." Good while you are getting used to Bots.
- **A therapist:** make a rule that blocks posting in public for every Bot. It adds a second layer to protect client privacy. It does not replace your own care with confidential information.
- **Fewer interruptions:** when a card keeps asking about something harmless that you are happy to allow, answer **Yes, stop asking**. It appears under **You taught them**, and you can undo it any time.

## Common problems and fixes

- **"The rules didn't load".** Press **Try again**.
- **"Loading rules..." stays on screen.** Check your connection and reopen the page.
- **"Pick what kind of action this rule is about."** Choose an option in **What**.
- **"That's too long. Keep the target under 120 characters and the note under 200."** Shorten them.
- **A Bot still asks even though I allowed it.** Your rule may not match the exact place. Make **Where** broader, or leave it empty. Or the action is on the never-list, which always asks.
- **I want a taught rule gone.** Click **Undo**. "Undone. It will ask again."

## Related features

- [House rules]({{ '/house-rules/' | relative_url }}): your own instructions for every Bot.
- [Laptop control]({{ '/laptop-control/' | relative_url }}): the actions Bots take on your computer.
- [Team members]({{ '/team/' | relative_url }}): approvals always come to you.
- [Monthly limit]({{ '/monthly-limit/' | relative_url }}): a cap on spending.

![The What Bots may do page: rules you taught, the Always asks you first list, your own rules and a link to the built-in rules.]({{ '/images/rules-laptop.png' | relative_url }})
*The What Bots may do page.*

[All help articles]({{ '/' | relative_url }})
