---
title: "Choose a server"
layout: default
permalink: /choose-a-server/
lang: en
---

# Choose a server

VectoBots runs on a small computer in a data center that **you rent**, called a server (also "VPS"). Your Bots, chats and files live there, and it stays on when your laptop is closed. This guide helps you pick one and shows every click for ordering our top pick.

*Prices checked on **November 23, 2026**. Server prices are rising this year, so check the price on the provider's page before you pay. This list is updated every month.*

## Which size do you need?

What matters is **how many Bots work at the same time**, not only how many people there are. A Bot that browses the web uses the most memory.

| Who | Suggested size | Why |
|---|---|---|
| Just you | **4 CPUs and 8 GB memory** | Room for a few Bots working at once, plus the extras. |
| You and 2 or 3 people | **4 to 6 CPUs and 8 to 12 GB** | More people means more Bots working at the same time. |
| A team of up to 6 | **6 CPUs and 12 GB memory** | Our pick for a small team. |

These sizes are our **estimates**, based on what the Bots need. We have not yet tested a full team of 6 working at once, so we will not promise it. If your server ever feels slow, you can move up one size with a click at most providers.

Also good to know:

- Disk space: **100 GB or more** is comfortable.
- Choose **Linux**, **Ubuntu 24.04** or newer.
- Pick a place close to you. For Mexico City, the US locations below work well.
- Each person still uses **their own Claude plan**. The server does not change plan limits.

## Our top pick: OVHcloud VPS-3 (about $14.50 a month, before taxes)

- 6 CPUs, 12 GB memory, 100 GB fast disk.
- **Month to month**: cancel any time.
- US locations: Virginia (east) and Oregon (west).
- Cheaper if you commit: about **$13.77** a month for 6 months, or about **$12.32** for 12 months.
- Best match for a team of up to 6.

## The other good choices

| Server | Size | Price | Terms | Where |
|---|---|---|---|---|
| **OVHcloud VPS-2** | 4 CPUs, 8 GB, 75 GB | from $8.50 (12-month price, before taxes) | Month to month costs about 18% more | US and worldwide |
| **netcup VPS 1000** | 4 CPUs, 8 GB, 128 GB | about €12 a month (12 months), about €14 month to month | Month to month available | Europe, and Virginia (US) with a small extra fee |
| **Contabo Cloud VPS 4** | 4 CPUs, 8 GB, 100 GB | about €5.50 month to month | Month to month available | US and Europe |
| **Hostinger KVM 2** | 2 CPUs, 8 GB, 100 GB | about $9 a month | Needs a **24-month** payment up front, then the price goes up | Several, including the US |

Honest notes:

- **Contabo** is the cheapest, but it shares more of the machine between customers and has a slower connection (200 Mbit/s). Fine for one person, risky for a team.
- **Hostinger** is cheap only if you pay for 2 years at once. We do not suggest it unless you are sure.
- **Hetzner**, a favorite of the past, **raised prices twice in 2026** and has limited stock for new customers. We do not suggest it right now.
- **DigitalOcean, Vultr and Akamai (Linode)** are excellent and reliable, but an 8 GB server costs about **$40 to $48** a month. Choose them only if you want a very well-known name.
- **Mexico:** we did not find a Mexico-based option we can confirm and recommend yet. A US server works well from Mexico City.

## Will prices change in 2027?

Nobody can promise, but here is what we see today:

- Memory chips are much more expensive this year, which is pushing server prices up. Hetzner and netcup both raised prices in 2026.
- OVHcloud says it is limiting its increases on newer servers, and it lets existing customers keep their current price for the commitment they choose when they renew.
- No provider has announced a 2027 increase yet that we can find, but we are watching.
- **Black Friday and year-end sales are on now.** OVHcloud's current offer is free backup options for up to 3 months (until December 1). netcup usually runs deals during Black Friday week and in December.
- If you are sure you will keep your server for a year, paying for **12 months** is usually cheaper and protects you from a price rise.

## Order the OVHcloud VPS-3, step by step

You need: an email address, a payment card, and about 15 minutes. **Nothing is charged until you confirm at the very end.** We looked at the order page on November 23, 2026 to write these steps. If your screen looks different, stop and ask.

1. **Open the plans page.** Go to **us.ovhcloud.com/vps**. You see four cards: VPS-1, VPS-2, VPS-3 and VPS-4.
2. **Choose VPS-3.** Its card says **6 vCores, 12 GB RAM, 100 GB SSD NVMe**. Tap **Configure**.
3. **Commitment period.** You see three boxes: **No commitment**, **6 months (save 5%)** and **12 months (save 15%)**. **12 months is already selected for you.** If you want to cancel any time, tap **No commitment**. The "starting at" price on the card is the 12-month price. A commitment renews by itself unless you turn that off in your account.
4. **Number of VPS.** Leave it at **1**.
5. **Location.** Open the **North America** tab and pick **Virginia** (closer to Mexico City) or **Oregon**.
6. **Image.** Open **Distribution only**, then tap **Ubuntu** and choose version **24.04** (newer is fine). It is free.
7. **Options.** You can leave the extras off. Daily backups are already included at no cost.
8. **Check the summary on the right.** It lists the plan, the commitment and the image. Prices there are **before taxes**. Make sure the total is what you expect.
9. **Continue and create your account.** Enter your name, email and a strong password, then confirm the email OVHcloud sends you.
10. **Add your address and card, and pay.** Tap the final button only when the total is right.
11. **Wait for the email.** Within minutes OVHcloud sends your server's **address** and a temporary **password**. Keep both private and never paste them in a chat.
12. **Connect it to VectoBots.** Open the VectoBots setup page. It asks for the server address and walks you through the rest.

## Good habits

- Turn on **two-step sign-in** on your provider account.
- Keep the **daily backup** that OVHcloud includes switched on.
- Write down the date your server renews, and put a reminder one week before.
- If you ever stop, cancel in the provider's control panel, because deleting VectoBots does not cancel the server.

## Questions

**Can I change size later?** Yes. At OVHcloud you can move up with one click. Moving down means ordering a new server.

**Is the server included in VectoBots?** No. You rent it from the provider and pay them directly.

**Do you earn money if I order?** No. These are plain links, not paid ones.

[All help articles]({{ '/' | relative_url }})
