---
title: "Bot templates"
layout: default
permalink: /bot-templates/
lang: en
---

# Bot templates

## What it is and why it exists

A **Bot template** is one small file that describes one Bot: its name, its look and its instructions. You can **export** a Bot as a template to keep a copy or share it, and **import** a template to add a Bot made by someone else, or a Bot you saved earlier.

Think of it as a recipe card, not a finished meal. It tells VectoBots how to set the Bot up. It does not carry what that Bot has learned or any of your private information.

![Settings on a laptop, page You: the Bot templates box with Learn more and the Import a Bot template button]({{ '/images/export-laptop.png' | relative_url }})

*The "Bot templates" box on the You page. It sits under "Your data".*

## Before you start

- It is free and available to you, the owner. Bots cannot export or import templates.
- To **import**, you need a template file. It ends in `.json`, and an exported one is named like `Name.vectobots-bot.json`.
- The new Bot gets this server's **usual AI**, not the one in the file. You can change that later in the new Bot's settings.

## What is in a template

A template holds only descriptive text and a few look settings:

- **Name**, plus its colour, shape and temper setting.
- **Title**, for example "Client care".
- **What it owns**, **what it does** and **what it does not do**.
- **Who it reports to** and its **rules** (the lines it never crosses).
- **Its instructions**, the written description of who the Bot is.

## What is never in a template

- **No memory.** It does not carry anything the Bot remembers.
- **No keys or sign-ins.**
- **No chats.**
- **No code.** It is only text and settings.

That is why a template is safe to keep and share in terms of your own data. It is still **not checked by VectoBots** when it comes from someone else. See "Be careful with files from others" below.

## How to export a Bot as a template

**On a laptop**

1. Open the Bot's chat.
2. Click the Bot's name at the top of the chat. Its details open.
3. Click the **…** button at the top of the details. Its label is "Hide or delete".
4. Choose **Export as a template file**.
5. Your browser saves a file named after the Bot, ending in `.vectobots-bot.json`.

**On a phone**

1. Open the Bot's chat from **Bots**.
2. Tap the Bot's name at the top, then the **…** button.
3. Tap **Export as a template file**.
4. Your phone saves the file in its downloads.

Exporting a Bot with everything else (memory, chats, files) is done with [Export your data]({{ '/export-your-data/' | relative_url }}), which also includes your Bots as templates.

## How to import a template

1. Open **Settings**, then **You** (on a laptop, the gear at the bottom left; on a phone, **More** at the bottom, then **Settings**).
2. Scroll to **Bot templates**.
3. Click or tap **Import a Bot template** and choose the `.json` file.
4. A window opens, **Add this Bot?**, showing everything in the file:
   **Name**, **Title**, **What it owns**, **Who it reports to**, **What it does**, **What it does not do**, **Rules** and **Its instructions**.
5. Read it. If you want to see the raw file, open **Show the file**.
6. Click **Add Bot** to create it, or **Cancel** to stop. Nothing is made until you click **Add Bot**.
7. A message says "{Name} was added." The new Bot opens with a note that it was made from a template file, that VectoBots did not check it, and that it will ask before doing anything that needs your OK.

If a Bot with the same name exists, the new one gets a number, for example "Anchor 2".

## Be careful with files from others

The window says it plainly: **"Not checked by VectoBots. Read it first."** VectoBots does not review a template for you. A template written by a stranger could hold instructions that you do not want your Bot to follow, that work against you or that you would not write yourself.

So always:

1. Read every field in the window, especially **Its instructions** and **Rules**.
2. Add only templates from people you trust.
3. Keep your approval rules on. The new Bot still has to ask before it sends, pays, posts or deletes.

## Examples for a solo practice

- **A back-up of your favourite helper.** Export your "Session prep" Bot after you have tuned its instructions. If you ever need to rebuild, import it.
- **A Bot for a new service.** Make one Bot for intake questions, export it, then import it and rename it to start a second one with similar rules.
- **Sharing with a colleague.** Export a "Weekly planner" Bot and send the file to a trusted colleague. They get your set-up, not your clients, notes or keys.
- **Confidentiality.** A template should never contain client names or details. Before you export or share, read the instructions field and remove anything personal, such as a client's name written there by mistake.

## Costs and limits

- Templates are free.
- A template file can be up to about 100 KB. The instructions can be up to 20,000 characters, and each of the other fields about 600 characters. Longer text is cut.

## Common problems and fixes

- **"That is not a Bot template."** The file is not a VectoBots Bot template. Pick a file that was exported from VectoBots.
- **"That file is too big for a Bot template."** The file is over the size limit.
- **"This template is from a newer version of VectoBots."** Update your VectoBots, then try again.
- **"The template has no name."** Open the file in a text editor and add a name.
- **The new Bot behaves like the default AI.** That is expected. A template never carries its AI. Change it in the Bot's settings.
- **I cannot find Export as a template file.** Open the Bot's menu, not the main Settings page.

## Related features

- [Export your data]({{ '/export-your-data/' | relative_url }}): everything in one file.
- [House rules]({{ '/house-rules/' | relative_url }}): rules for every Bot at once.
- [Which AI]({{ '/which-ai/' | relative_url }}): choose the AI each Bot uses.

[All help articles]({{ '/' | relative_url }})
