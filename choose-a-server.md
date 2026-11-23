---
title: "Choose a server"
layout: default
permalink: /choose-a-server/
lang: en
---

# Choose a server

VectoBots runs on a small computer in a data center that **you rent**, called a server (also "VPS"). Your Bots, chats and files live there, and it stays on when your laptop is closed. This guide helps you pick one and shows every click for ordering our top pick.

*OVHcloud prices were checked on its order page on **November 23, 2026**. Other prices come from price-comparison sites the same day. Server prices rose in 2026, so check the price on the provider's page before you pay.*

## Which size do you need?

What matters is **how many Bots work at the same time**, not only how many people there are. A Bot that browses the web uses the most memory.

| Who | Suggested size | Why |
|---|---|---|
| Just you | **4 CPUs and 8 GB memory** | Room for a few Bots working at once, plus voice transcription. |
| You and 2 or 3 people | **4 to 6 CPUs and 8 to 12 GB** | More people means more Bots working at the same time. |
| A team of up to 6 | **6 CPUs and 12 GB memory** | Our suggested size for a small team. |

These sizes are our **estimates**, based on what the Bots need. We have not yet tested a full team of 6 working at once, so we will not promise it. If your server feels slow, you can move to a bigger plan from your OVHcloud account, for a higher price.

Also good to know:

- Disk space: **100 GB or more** is comfortable.
- Choose **Ubuntu 24.04** (a version of Linux).
- Pick a place close to you. For Mexico City, the US locations below should work well.
- Each person still uses **their own Claude plan**. The server does not change plan limits.
- Sharing with a team has some limits today. Read [Team members]({{ '/team/' | relative_url }}) first.

## Our picks, and what to do when one is sold out

Good servers sell out. **Check that a plan can be ordered before you plan around it**, and if it is sold out, take the next one on its list. Stock checked on **November 23, 2026**.

**For a team of up to 6 (6 CPUs, 12 GB):**

1. **OVHcloud VPS-3**, about US$14.50 a month with no commitment (US$13.77 on 6 months, US$12.32 on 12 months, before taxes). Best quality of the three. **Sold out on November 23, 2026**: the order page said "currently unavailable". Check again later.
2. **Contabo Cloud VPS 6**: 6 CPUs, 12 GB, 200 GB, about €7.50 a month month to month. It matches the size on paper and is orderable, but it is a shared budget plan with a 300 Mbit/s connection, so we would watch how it performs before trusting it with a whole team.
3. **netcup VPS 2000**: 8 CPUs, 16 GB, 256 GB, about €26 a month month to month (about €22.60 on 12 months). Orderable. Strong, but the most expensive of the three.

**For one person, or you and 2 or 3 people (4 CPUs, 8 GB):**

1. **OVHcloud VPS-2**, about US$10 a month with no commitment (from US$8.50 on 12 months). **Orderable on November 23, 2026**, in the US East (Virginia) location only, with 75 GB of disk.
   - **Need more disk?** OVHcloud sells extra disk space for VPS-2 (the configurator offers 50, 100, 200 GB and more). We saw the add-on listed from US$2.60 a month (before taxes) on November 23, 2026, but could not confirm the exact price for 100 GB, so check the price shown to you before you pay. With about 100 GB extra you would have roughly 175 GB for about US$10 to US$15 a month in total. Add the disk from your OVHcloud control panel after the server is ready, or look for the option in the order page. If it is not offered in your order, ask OVHcloud support.
2. **netcup VPS 1000**: 4 CPUs, 8 GB, 128 GB, about €14 a month month to month. Orderable.

## All the choices side by side

| Server | Size | Price | Terms | Where |
|---|---|---|---|---|
| **OVHcloud VPS-2** | 4 CPUs, 8 GB, 75 GB | from US$8.50 a month (12-month price, before taxes) | About US$10 a month with no commitment | US and worldwide |
| **netcup VPS 1000** | 4 CPUs, 8 GB, 128 GB | about €12 a month (12 months), about €14 month to month | Month to month available | Europe, or a US location for about €1.50 more a month |
| **Contabo Cloud VPS 6** | 6 CPUs, 12 GB, 200 GB | about €7.50 month to month | Month to month available | US and Europe |
| **Contabo Cloud VPS 4** | 4 CPUs, 8 GB, 100 GB | about €5.50 month to month | Month to month available | US and Europe |
| **Hostinger KVM 2** | 2 CPUs, 8 GB | about US$9 a month, only if you pay 24 months up front (about US$216) | Renews at about US$15 a month | Check the provider's page |

Honest notes:

- **Contabo** is the cheapest here. Its listed connection is 200 Mbit/s, lower than we would like for a busy team. Fine for one person; for a team we prefer OVHcloud.
- **Hostinger** is cheap only if you pay for 2 years at once. It also has only 2 CPUs, below our suggested size. We do not suggest it unless you are sure.
- **Hetzner**, long a popular choice, **raised prices twice in 2026** and since June 2026 has limited cloud server orders for many new customers. We do not suggest it right now.
- **DigitalOcean, Vultr and Akamai (Linode)** are excellent and reliable, but an 8 GB server costs about **US$40 to US$48** a month. Choose them only if you want a very well-known name.
- **Mexico:** we did not find a Mexico-based option we can confirm and recommend yet. A US server works well from Mexico City.

## Will prices change in 2027?

Nobody can promise, but here is what we see today:

- Memory chips cost much more in 2026, pushing server prices up. Hetzner and netcup raised prices in 2026, and OVHcloud's newer VPS plans (June 2026) cost more than its older ones for the same size.
- OVHcloud says it is limiting increases on its newer services, and has let existing customers keep their price for a set term if they renew before a deadline. Check OVHcloud's site for current terms.
- As of November 23, 2026, we found no provider that has announced a 2027 increase, but we are watching.
- **Until December 1, 2026**, OVHcloud offers up to 3 months of its upgraded (Premium) backup free. It is not a discount on the server, and it may cost money after the free period, so check before adding it. netcup may have December offers; we have not confirmed any.
- If you are sure you will keep your server for a year, a **12-month** commitment is usually cheaper and keeps your price fixed for those 12 months.

## Order an OVHcloud server, step by step (shown with VPS-3)

If VPS-3 says "currently unavailable", the same steps work for VPS-2, or use another pick above. You need: an email address, a credit or debit card, and about 15 minutes. You should not be charged until you confirm the order at the end. We followed OVHcloud's order page up to the summary (step 8) on November 23, 2026; the sign-up and payment screens may differ. If anything looks different, stop and ask your Bot. OVHcloud may also send you to a different OVHcloud site for your country, so check that the VPS-3 price there matches this guide.

1. **Open the plans page.** Go to **us.ovhcloud.com/vps**. You see a row of plan cards, including VPS-3.
2. **Choose your plan.** VPS-3's card says **6 vCores, 12 GB RAM, 100 GB SSD NVMe**. Click (or tap) **Configure**. If the page says the plan is unavailable, or the location list says **No location available**, it is sold out: go back and take the next pick.
3. **Commitment period.** You see three boxes: **No commitment**, **6 months (save 5%)** and **12 months (save 15%)**. **12 months is already selected for you.** If you want to be able to cancel any time, click **No commitment**. The "starting at" price on the card is the 12-month price. With 6 or 12 months, you agree to pay for the whole period even if you stop early. All plans renew and bill again until you cancel.
4. **Number of VPS.** Leave it at **1**.
5. **Location.** Open the **North America** tab and pick **Virginia** (closer to Mexico City) or **Oregon**.
6. **Image.** Open **Distribution only**, then click **Ubuntu** and choose version **24.04**. It is free.
7. **Options.** You can leave the extras off. The summary shows a standard automatic backup at US$0.00.
8. **Check the summary on the right.** It lists the plan, the commitment and the image. Prices there are **before taxes**. Make sure the total is what you expect.
9. **Continue and create your account.** Enter your name, email and a strong password, then confirm the email OVHcloud sends you.
10. **Add your address and card, and pay.** Click the final button only when the total is right.
11. **Wait for the email.** Usually within minutes. OVHcloud may first ask you to confirm your identity, which can take longer. It sends your server's **address** and a temporary **password**. Keep both private. Type the password only where the VectoBots setup page asks for it; never send it by email, chat or message, not even to us.
12. **Connect it to VectoBots.** Open the VectoBots setup page. It asks for the server address and walks you through the rest.

## Good habits

- Turn on **two-step sign-in** on your provider account.
- If your provider includes backups, keep them on.
- Write down the date your server renews, and put a reminder one week before.
- If you ever stop, cancel in the provider's control panel, because deleting VectoBots does not cancel the server.

## Questions

**Can I change size later?** Yes. At OVHcloud you can move to a bigger plan from your account; your price goes up. Moving to a smaller plan means ordering a new server.

**Is the server included in VectoBots?** No. You rent it from the provider and pay them directly.

**Do you earn money if I order?** No. No provider on this page pays us, and we use no referral links. If that changes, we will say so here.

[All help articles]({{ '/' | relative_url }})
