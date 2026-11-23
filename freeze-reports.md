---
title: "Freeze reports"
layout: default
permalink: /freeze-reports/
lang: en
---

# Freeze reports

Sometimes a screen in the app stops answering for a moment. You tap and nothing happens, then it wakes up. When that lasts 2 seconds or more, the app quietly writes a short note about what it was doing. This is a **freeze report**. It exists so that if the app is slow or sticky, you or the person helping you can see why, instead of guessing.

You do not need to do anything. Most people never open this page. It is there for the day something feels wrong.

## Before you start

- Nothing to buy and nothing to switch on. It is free and always running.
- The reports stay on **your server**. Nothing is sent anywhere else.
- A report is not an error message and does not mean you did anything wrong.

## Where to find it

**On a laptop:** click the gear at the bottom left to open **Settings**, then **Computer**. Scroll to the section called **App freezes**.

**On a phone:** tap **More** at the bottom, then **Settings**, then **Computer**, and scroll to **App freezes**. Use the back arrow at the top to return to the list.

*The screenshots are in English.*

![The App freezes section of the Computer page, showing "No freezes saved"]({{ '/images/freezes-laptop.png' | relative_url }})

*App freezes, on the Computer page. This one is empty, which is the good news.*

## How to use it, step by step

1. Open **Settings**, then **Computer**, then scroll to **App freezes**.
2. If you see "No freezes saved", the app has not frozen. You are done.
3. If you see rows, each one reads like "Stuck for 6 seconds", with the day and time under it.
4. Press **Details** on a row to open the technical note. Press it again to close.
5. To get help, press **Copy all**. The button changes to "Copied". Paste the text into a message to whoever supports you.
6. When the problem is solved, press **Clear** to remove the reports.

## Every option explained

**A report row.** The title says how long the screen was stuck. Under it you see when it happened and one of two lines:
- "It recovered on its own." The screen woke up again.
- "It had not recovered when this was sent." The screen was still stuck when the report was written.

**Details.** Opens a small text with the technical story: which screen you were on, what was still being done, your last taps (which kind of tap and where, not the words you typed), slow parts the browser measured, and the last steps taken. It is meant for the person fixing the problem, not for you to read.

**Show older (N).** The page shows the 20 newest reports. This button shows 20 more at a time.

**Copy all.** Puts every report on your clipboard as plain text. If your browser blocks copying, the button says "Could not copy".

**Clear.** Asks "Clear all saved freezes?" and explains "This erases the reports. They help find why the app froze." Press **Clear** to confirm or **Cancel** to keep them. It cannot be undone.

## When a report is and is not written

- A report is written when a screen is stuck for 2 seconds or more.
- If a screen stays stuck, the app sends at most about one report a minute.
- Switching to another app, locking the phone or letting the computer sleep is not counted as a freeze.
- The app keeps the latest 200 reports. Older ones are dropped.

## Real examples

- **A coach on a phone** finds that the chat sticks every time they open a long conversation. They press **Copy all** and send it to whoever runs their setup. The person sees which screen was busy.
- **A therapist** checks the page only after the app felt slow. "No freezes saved" tells them the slowness was their internet, not the app.
- **A consultant** clears the list after a fix, so any new report is clearly new.
- Confidentiality: the report records what the app was doing, not what you wrote in your chats. Even so, read it before you forward it, and send it only to someone you trust with your setup.

## Costs and limits

- Free. No AI is used.
- Kept: the latest 200 reports on your server.
- Threshold: 2 seconds.

## Common problems and fixes

- **"Could not load the reports."** The page could not reach your server. Reload and try again.
- **"Could not copy".** Your browser blocked copying. Open **Details** and select the text by hand.
- **I see many reports.** The app is struggling. Copy them all and ask for help, and consider freeing disk space (see [Temp files]({{ '/temp-files/' | relative_url }})).
- **"No freezes saved" but the app feels slow.** The cause may be your connection or your AI provider and not the app screen.

## Related features

- [Temp files]({{ '/temp-files/' | relative_url }}): a full disk can slow things down.
- [Laptop control]({{ '/laptop-control/' | relative_url }})
- [Costs]({{ '/costs/' | relative_url }})

[All help articles]({{ '/' | relative_url }})
