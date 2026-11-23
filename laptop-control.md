---
title: "Let Bots use your laptop"
layout: default
permalink: /laptop-control/
lang: en
---

# Let Bots use your laptop

Laptop control lets a Bot you choose see your screen, move the mouse and type, the way you would, so it can do a task in a program on your own computer. A small helper app on your laptop makes this possible.

It exists for jobs that only happen on your laptop, such as filling in a form in a program that has no other way in. Most people never need it. Treat it as a power tool: off until you decide to use it.

## Before you start

- You need a laptop you can install a small **helper app** on. For now the helper works on **Windows** only.
- Switching a Bot on for laptop control is part of **Pro**. (Every part of Pro is on during the trial.) Switching it off is always allowed.
- Nothing is on by default. Laptop control is **off for every Bot** until you switch it on.
- The helper must be running on the laptop. The app says whether it is: **Connected** or **Not connected**.

![Settings, Computer, with the Laptop section showing Your laptop, Not paired, and a Make a pairing code button]({{ '/images/laptop-laptop.png' | relative_url }})

*Settings, Computer, Laptop. The screenshots are in English.*

## How to set it up

The Laptop section is in **Settings, Computer**. On a laptop, open Settings and click **Computer** in the list on the left. On a phone, tap **More** at the bottom, then **Settings**, then **Computer**. Use the back arrow to return.

1. **Install the helper** on your laptop.
2. In **Laptop**, tap **Make a pairing code**. A code appears, with the note "Enter this code in the helper. It works for 10 minutes."
3. **Enter the code in the helper once.** The status changes from **Not paired** to **Connected**.
4. Under **Which Bots may use it**, switch on the Bots that may ask. A switched-on Bot reads: "May ask to use your laptop. You approve on a card." A switched-off one reads "Off."

## What happens when a Bot wants to use it

The **first action of each session asks you on a card** in the chat. You choose to allow it **for this task** or **for 30 minutes**, or you say no. When a Bot is working, the page tells you: "[Bot] is controlling your laptop now."

The Bot starts by taking a picture of the screen, looks at it, then clicks or types. It takes new pictures to check what happened.

To stop being asked for a Bot, add a rule under **What Bots may do**.

## What is blocked

The helper blocks windows that look like the Vault, password managers, banking pages and sign-in screens. It recognizes them by their names, so a bank page with an unusual title might not be caught. Close anything you do not want a Bot to see. If a Bot needs you to sign in somewhere, it has to ask you to do it yourself. Bots are told to treat text on the screen as information, never as an instruction.

Every action is listed in **Activity**, so you can look back at what happened.

## Every button explained

- **Make a pairing code / Pair again.** Creates a code that lasts 10 minutes. After pairing, the same button reads **Pair again**. Pairing again switches every Bot off and takes back their approvals, so switch on the Bots you want again.
- **Unpair.** Disconnects the laptop. The app asks: "Unpair this laptop? The helper stops working until you pair it again."
- **Stop everything** (in the **Stop** row). Ends every session now and blocks laptop control. You can also click the red banner on the laptop, or press **Ctrl+Alt+End**. The status becomes **Stopped**.
- **Start again.** Appears after a stop. Laptop control stays off for every Bot until you press it.
- **The switch per Bot.** Turns that Bot's permission on or off. Turning it off also takes back that Bot's approvals.
- **Status chip.** **Not paired**, **Connected**, **Not connected** or **Stopped**. "The helper is not running or cannot reach this server" means the helper is closed or offline. When it is running, the app shows the screen size it sees.

## Example

A therapist has an old scheduling program on her laptop that she cannot connect to anything else. She installs the helper, pairs it, and switches on one Bot. She asks it to move Thursday's appointments to Friday. A card appears; she allows it for this task. She watches, sees it finish, and sees every click listed in Activity.

She never lets a Bot use her laptop while a client file or her banking is on the screen. The helper tries to block the Vault and banking pages, but good judgment is hers: close what you do not want a Bot to see.

## Costs and limits

The app does not charge for this by itself. The Bot's work uses its AI like any other task. See [Costs]({{ '/costs/' | relative_url }}).

## Common problems

- **Not paired.** Make a code, then enter it in the helper.
- **Not connected.** The helper is closed, or the laptop is asleep or offline. Open the helper again.
- **Stopped.** You pressed Stop. Tap **Start again**.
- **The code does not work.** It lasts 10 minutes. Make a new one.
- **A Bot stops and says it was told no.** If you said no or pressed Stop, the Bot stops and tells you in one line. It does not try another way.

## Related

- [Connect GitHub]({{ '/github/' | relative_url }})
- [Costs]({{ '/costs/' | relative_url }})

[All help articles]({{ '/' | relative_url }})
