# racknerd 11.11: What the Plans Cost, Which Tier Fits, and Do Renewals Go Up? (Full Plan Table + Four Years of Price History)

RackNerd has not posted a 2026 11.11 lineup on the public store pages checked for this article, so there is no current price to quote. The last complete run is the usable benchmark: four KVM tiers from **$10.76 to $39.99 per year**, with the 2 GB at **$17.66/year** covering most buyers. Below are those verified specs, four years of 11.11 pricing so you can judge whether a new batch is actually a deal, the renewal and IP rules that decide your real cost, and which datacenter to pick.

> **Quick pick (2025 11.11 prices, verified against two independent listings)**
> - Static site, blog, small WordPress: 1 GB at **$10.76/yr**, any location with stock.
> - Asia routing or a light app: 2 GB at **$17.66/yr**. It is the cheapest tier that can use the Los Angeles DC-02 facility.
> - Nextcloud, Gitea, a small Plex: 3 GB at **$26.99/yr**.
> - Several services or anything other people rely on: 4 GB at **$39.99/yr**.
>
> These are last year's promo numbers, not a 2026 quote. 👉 [See what RackNerd has live in the store right now](https://bit.ly/RacKnerd)

## The 2025 11.11 lineup in full

Four plans, all KVM, all annual billing. Prices and specs match across the promo listing and the deal tracker that archived them, which is why they are worth using as a reference point.

| Plan | vCPU | RAM | SSD | Annual price | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 | 1 GB | 20 GB | **$10.76/yr** | [Order](https://bit.ly/RacKnerd) |
| 2 GB KVM VPS | 2 | 2 GB | 35 GB | **$17.66/yr** | [Order](https://bit.ly/RacKnerd) |
| 3 GB KVM VPS | 3 | 3 GB | 55 GB | **$26.99/yr** | [Order](https://bit.ly/RacKnerd) |
| 4 GB KVM VPS | 4 | 4 GB | 80 GB | **$39.99/yr** | [Order](https://bit.ly/RacKnerd) |

Bandwidth and the DC-02 restriction sit outside the main table because they change the buying decision more than the CPU count does:

| Plan | Monthly transfer | Los Angeles DC-02 |
| --- | --- | --- |
| 1 GB | 3,000 GB | Not offered |
| 2 GB | 5,000 GB | Available, stock permitting |
| 3 GB | 6,000 GB | Available, stock permitting |
| 4 GB | 8,000 GB | Available, stock permitting |

Every plan in that run included KVM virtualization rather than OpenVZ containers, pure SSD storage in RAID-10, a 1Gbps port, one dedicated IPv4 address, full root access, a SolusVM panel for reboots, OS reinstalls and rDNS, and instant setup after payment. The 2025 batch ran across nine locations, including Los Angeles DC-02, San Jose, Seattle, Dallas, Chicago, New York, Atlanta, and selected European sites depending on the plan.

## Four years of 11.11 pricing, side by side

The entry tier has barely moved in four years, and the top tier went up in 2025.

| Year | 1 GB | 2 GB | 3 GB | 4 GB |
| --- | --- | --- | --- | --- |
| 2022 | $11.11 | $17.11 | $29.11 | $48.11 |
| 2023 | $11.00 | $17.55 | $28.31 | $38.77 |
| 2024 | $11.11 | $17.98 | $25.98 | $36.88 |
| 2025 | $10.76 | $17.66 | $26.99 | $39.99 |

Two things fall out of that table. The 1 GB plan has drifted between roughly $10.76 and $11.11 for years (a 2021 listing advertised entry KVM plans from $12/year, so the floor is old), while the hardware behind it improved: the 2024 1 GB shipped with 14 GB of disk and 2,000 GB of transfer, and the 2025 version came with 20 GB and 3,000 GB for less money.

The 4 GB plan is the exception. It cost $36.88 in 2024 and $39.99 in 2025, but it also went from 3 vCPU and 50 GB of disk to 4 vCPU and 80 GB. Anyone who tells you these sales get cheaper every single year is guessing. Some years you get more hardware for more money, and the 4 GB tier in 2025 was one of those.

There is also an unlabeled older batch in the tracker's archive with five plans from $9.98/yr, including a Windows 3 GB VPS at $78.88/yr against a $331.08/yr regular Windows plan. Those listings are marked as sold out or removed from the store, so treat them as history rather than something to hunt for.

## How much the 11.11 price actually cuts

Against RackNerd's closest regular plans, the discounts are large at the bottom and moderate in the middle.

| 11.11 plan | Promo price | Closest regular plan | Regular price | Difference |
| --- | --- | --- | --- | --- |
| 1 GB | $10.76/yr | 1 GB KVM VPS Special | $21.99/yr | 51% cheaper |
| 2 GB | $17.66/yr | 2 GB KVM VPS Special | $35.99/yr | 51% cheaper |
| 3 GB | $26.99/yr | 2 GB KVM VPS Special | $35.99/yr | 25% cheaper, different specs |
| 4 GB | $39.99/yr | 4 GB KVM VPS Special (3 vCPU, 60 GB) | $59.99/yr | 33% cheaper |

The 3 GB row deserves a caveat: RackNerd has no regular 3 GB plan, so the comparison lands on a 2 GB with fewer cores and less disk. The 25% is real money, but it is not a like-for-like figure the way the 1 GB and 2 GB rows are.

## Three clauses that matter more than the sticker price

**The promo price is the renewal price.** RackNerd states that 11.11 plans renew at the same promotional rate, with no increase after year one. On a $10.76 plan that turns a first-year loss leader into a $32 three-year cost, which is the number to compare against any monthly-billed alternative. Buyers from earlier 11.11 batches are still running at their original rates. Check the order form at checkout anyway: the price you see on the invoice is the one that holds.

**You get 72 hours to swap a bad IP.** Addresses come from shared pools, so a new box can arrive with an IP that streaming services block or that sits on a spam list. RackNerd allows one free IP change within 72 hours of deployment; after that it is $3 per change. If you are buying for anything that depends on clean outbound IP reputation, test the address in the first day rather than the first week. The Los Angeles DC-02 allocation reportedly hands out 74.x.x.x addresses, which tend to unlock international services better, but you only find out what you got after provisioning.

**Bandwidth can be doubled for free through LowEndTalk.** Post your order number in the provider's 11.11 thread on the LowEndTalk forum and the bandwidth allowance is doubled at no cost. The order number is in the "RackNerd - Order" email. This has been running since at least the 2022 sale, so it is a standing arrangement rather than a one-year gimmick. It costs nothing to try and doubles a 3,000 GB allowance to 6,000 GB if it is honoured.

👉 [Check current 11.11 stock, prices and plan details](https://bit.ly/RacKnerd)

## Which datacenter to pick

Los Angeles DC-02 is the only location with the Asia-optimized network blend, which includes CN2 routing into China. It is also restricted to 2 GB plans and above, so a 1 GB order cannot select it at any price. San Jose is the other reasonable pick for China Telecom users; the remaining US locations are fine for backups, crawlers, batch jobs and anything else that does not care about 150ms versus 200ms.

Test before you buy rather than after. RackNerd runs a looking glass per facility (the labels follow lg-lax02, lg-sj, lg-sea, lg-dal, lg-chi, lg-ny and lg-atl), and pinging the test file from your own connection tells you more than any benchmark chart. If your latency tolerance is loose, order whichever location still has stock and skip the queue for DC-02 entirely.

## Which tier for which job

**1 GB, $10.76.** A tuned LEMP stack runs a normal blog or a static site on 1 GB without complaint, and 20 GB of SSD is enough for the site, a database and a year of logs. It is not enough for Plex, a Windows licence, a Docker host running five containers, or anything with a JVM in it.

**2 GB, $17.66.** Development environments and small Node or Python apps fit here, and 1 GB is workable but tight once you add a database and a build step. This is also the cheapest route to DC-02.

**3 GB, $26.99.** Self-hosted Nextcloud, Gitea, Vaultwarden or a small Plex library with direct play. Two gigabytes is the floor for that workload; three is comfortable.

**4 GB, $39.99.** Several services on one box, a small VPN with real users, or a production site you would rather not debug at 2am with no headroom. The 4 vCPU and 80 GB matter as much as the RAM.

## Before you click order

Stock is the constraint, not the price. RackNerd's event pricing sells out and does not come back, and the 1 GB plan and DC-02 slots go first. Flash sales in general appear without warning and the best plans can clear in minutes, so if a plan and location combination is showing available, the decision is whether you want it, not whether a better version arrives next week.

Two more things to know. These are unmanaged servers: support answers tickets, but if you break the configuration you own the problem, and a few hours for a standard ticket is the realistic expectation rather than instant chat. Payment runs through PayPal, credit cards, Alipay, UnionPay and 30-plus cryptocurrencies via Coinify, and deployment is instant after payment clears.

On timing: 11.11 lands about two weeks before Black Friday, lasts a day or two, and the date is known in advance, which is the opposite of a flash sale. Nothing in the pricing history says 11.11 is cheaper than Black Friday; it says 11.11 is the earlier, more predictable of the two.

If you want the cheapest thing that works, take the **1 GB at $10.76** and stop reading. If you need DC-02 or you are running something other people connect to, the **2 GB at $17.66** is the tier where the price-to-spec ratio stops being a compromise. Confirm the location still has stock and read the IP policy once before checkout.

👉 [Open RackNerd's store and pick a plan](https://bit.ly/RacKnerd)
