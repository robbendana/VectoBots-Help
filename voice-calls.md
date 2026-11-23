---
title: "Voice calls"
layout: default
permalink: /voice-calls/
lang: en
---

# Voice calls

## What it is and why it exists

A voice call lets you talk to one Bot out loud, like a phone call, and hear it answer. You can interrupt it. It is handy when your hands are busy, when you are walking, or when you think better by talking than by typing. Everything said on the call is also written into the Bot's chat afterwards, so nothing is lost.

## Before you start

- **A Google AI key.** The only provider that works today is **Gemini Live** from Google. It uses your own Google AI key, so you pay Google directly. The other two listed, **xAI Voice** and **OpenAI Realtime**, are greyed out and cannot be picked yet.
- **The server must be ready to store keys.** If not, the Voice page says "Keys can't be added until the server has its encryption key."
- **A microphone** and a browser that is allowed to use it.
- **Cost:** about **1 cent a minute**, as the Voice page states: "You pay the provider directly, about 1 cent a minute." The call cost also appears in [Costs]({{ '/costs/' | relative_url }}) under the Bot and counts toward your [Monthly limit]({{ '/monthly-limit/' | relative_url }}).

## Set it up

- **Laptop:** open **Settings** and pick **Voice** in the list on the left.
- **Phone:** tap **More** at the bottom, then **Settings**, then **Voice**, and use the back arrow to return.

A small dot beside Voice means it still needs your key.

1. Under **Voice provider**, leave **Gemini Live** selected.
2. In the row **Your key**, paste your Google AI key in the box "Paste your Google AI key".
3. Tap **Save key**. The button says "Checking…" for a moment. If Google accepts it, you see "Key saved." and the row now reads **Key saved**, with "Kept encrypted on the server."
4. Optionally set **Most per day**, **Longest call** and the voice, covered below.

![Settings, Voice page with Gemini Live selected, the limits and the voice list]({{ '/images/voice-laptop.png' | relative_url }})

*The Voice page in Settings. The screenshots are in English.*

To remove a key you saved in the app, tap **Remove** in that row.

## Making a call

1. Open a chat with one Bot.
2. Tap the **phone** button in the chat. Its label is "Call" followed by the Bot's name.
3. Your browser asks to use the microphone the first time. Allow it.
4. The call screen opens with the Bot's face. The first word is **Connecting**, then **Listening…**.
5. Talk normally. Pause when you are done. You can cut in while it speaks.
6. Tap **Hang up** to finish.

During the call the screen shows these states: **Connecting…**, **Listening…**, **Thinking…**, **Working on it…** (the Bot is doing the real work), **Speaking…**, **Microphone off**, **Reconnecting…**, and **Call ended**.

## The buttons on the call screen

- **Mute** turns your microphone off. It becomes **Unmute**. A muted call says "Microphone off".
- **Captions** shows or hides the last lines of the conversation on screen.
- **Hang up** ends the call.
- **Back arrow** (top left): "Back to the chat. The call stays on." A small bar keeps the call within reach.
- **Pop out into a small window** (top right): on a computer with a wide screen, in a browser that supports it, the call moves into a small window that stays on top. It is not offered on phones.
- **Gear:** "Voice and speed", the same picker as in Settings.
- If a Bot needs a tap from you, the screen shows "1 card waits. Open".

## Every setting explained

**Voice provider.** The radio choice. Only Gemini Live works.

**Most per day.** Dollars. It starts at **$2**. The note says "0 means no limit. Spent today: …". The allowed range is $0 to $1000. When today's spend reaches it, calls will not start, and you see: "You reached today's voice limit of $2.00. Raise it in Settings, Voice, or call again tomorrow."

**Longest call.** Minutes. It starts at **10** and can go up to **30**. A call ends on its own with "The call reached its N minute limit."

**Voice and speed.**

- **Voice:** twelve voices, each with a one-word feel: Kore (Firm), Puck (Upbeat), Charon (Informative), Zephyr (Bright), Aoede (Breezy), Sulafat (Warm), Achird (Friendly), Schedar (Even), Gacrux (Mature), Vindemiatrix (Gentle), Umbriel (Easy-going), Sadaltager (Knowledgeable). The default is Kore. Tap the small play arrow beside a name to hear a short sample before you choose.
- **Speed:** a slider from 0.8x to 1.25x, starting at 1x. "Speed changes the pitch a little. A new voice starts on your next call."

## How a call works

The voice you hear is only the voice of the Bot. When you ask for something real, such as a file, a calendar, or your notes, the voice hands the request to the real Bot, says it is on it, and reads the answer back in short words. That is the state **Working on it…**. Calls are kept short and spoken, so expect headlines, not long lists.

**Safety.** A request spoken on a call never approves anything risky by itself. Sending, paying, deleting or installing still needs your tap on a card in the chat, as always. The voice also does not state facts about your schedule, files or money on its own. It asks the Bot first.

## Real examples

- **A coach** walks between sessions and asks: "What do I have this afternoon, and what did we agree with the Thursday client?" The Bot answers briefly, and the full text is in the chat afterwards.
- **A consultant** dictates a rough plan for a workshop out loud, then reads the written version in the chat.
- **A therapist** should be careful. A call goes from your device to Google, so do not speak client names or health details on a call.

## Costs and limits

- About 1 cent a minute, to Google, with your own key.
- A daily limit (**$2** at the start) and a longest call (**10** minutes at the start, **30** at most).
- Real work done by the Bot during the call is charged like any other Bot work.
- When a call ends the screen shows its length and cost, and "The words are in your chat."

## Common problems and fixes

- **"Add your voice key first."** You have no key yet. The app opens Settings, Voice.
- **"The call didn't connect. Check the key in Settings, Voice."** The key may be wrong. Paste it again.
- **"Google refused that key. Check it and try again."** Get a fresh key from your Google account.
- **"Microphone access is blocked. Allow it in your browser settings."** Allow the microphone for this site.
- **"This browser can't use the microphone here. Open the app over its secure address."** Use the app's normal secure address.
- **"Voice isn't available on this server."** The server does not have voice calls.
- **"The call dropped."** Try again. The app tries to reconnect a few times first.
- **"You reached today's voice limit."** Raise **Most per day** or call tomorrow.

## Related features

- [Voice typing]({{ '/voice-typing/' | relative_url }})
- [Costs]({{ '/costs/' | relative_url }})
- [Monthly limit]({{ '/monthly-limit/' | relative_url }})
- [Which AI each Bot uses]({{ '/which-ai/' | relative_url }})

[All help articles]({{ '/' | relative_url }})
