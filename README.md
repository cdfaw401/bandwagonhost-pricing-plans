# BandwagonHost pricing: Every plan and price explained, so you can pick the right VPS without guessing

Anyone who types "BandwagonHost pricing" into a search bar usually has the same three questions in mind. What does it actually cost? Why do the prices on the order page look so different from each other? And which plan is worth the money for my specific use case?

This article answers all three, using the current plans and prices listed directly on BandwagonHost's own order system. No recycled blog numbers, no invented coupons. Every price below comes from the live order pages that anyone can check before buying.

## The short version of BandwagonHost pricing

BandwagonHost (also known as BWH, operated by IT7 Networks) currently sells KVM VPS plans in three distinct product lines, and the pricing logic differs quite a bit between them:

- **PROMO VPS plans** — the budget line, starting at $49.99 USD per year
- **SPECIAL 40G–1280G KVM PROMO V5 CN2 GIA plans** — premium connectivity to Singapore, Osaka, Hong Kong, and Tokyo, from $49.99 to $10,559.99 USD depending on size and location
- **Ecommerce SLA Los Angeles plans** — business-grade VPS with a 99.99% SLA, from $239.99 USD per year

All prices are in USD. Every plan is strictly self-managed, which is worth understanding before you click buy — more on that later.

If you already know what you need, the fastest way to browse the current lineup is to [👉 view all available VPS plans and pricing](https://bit.ly/BandwagonHost) directly.

## Line 1: PROMO VPS — where the famous "$50 a year" lives

This is the line most people mean when they talk about BandwagonHost pricing. The PROMO VPS plans are the ones that made the brand's reputation: small, cheap, and surprisingly capable for the money.

Here is the full current lineup:

| Plan | SSD | RAM | CPU | Transfer | Cheapest billing option | Most expensive billing option |
| --- | --- | --- | --- | --- | --- | --- |
| 20G KVM - PROMO VPS | 20 GB | 1 GB | 2x Intel Xeon | 1 TB/mo | $49.99 / year | $49.99 / year |
| 40G KVM - PROMO VPS | 40 GB | 2 GB | 3x Intel Xeon | 2 TB/mo | $52.99 / 6 months | $99.99 / year |
| 80G KVM - PROMO VPS | 80 GB | 4 GB | 4x Intel Xeon | 3 TB/mo | $19.99 / month | $199.99 / year |
| 160G KVM - PROMO VPS | 160 GB | 8 GB | 5x Intel Xeon | 4 TB/mo | $39.99 / month | $399.99 / year |
| 320G KVM - PROMO VPS | 320 GB | 16 GB | 6x Intel Xeon | 5 TB/mo | $79.99 / month | $799.99 / year |
| 480G KVM - PROMO VPS | 480 GB | 24 GB | 7x Intel Xeon | 6 TB/mo | $119.99 / month | $1,199.99 / year |

A few observations that are easy to miss if you only glance at the prices:

The **20G plan** is annual-only at $49.99/year. There is no monthly option, so you commit for a year whether you like it or not. At roughly $4.17 per month, it remains one of the cheapest ways to get a KVM VPS with a dedicated IPv4 address, 1 TB of transfer, and full root access.

The **80G plan** is the odd one out — it actually gets *cheaper* per month as you commit longer. Monthly it's $19.99, but annually it works out to about $16.67/month, and you get 80 GB SSD, 4 GB RAM, and 3 TB of transfer. For a lot of self-hosted projects (a few Docker containers, a small database, a personal VPN endpoint), this is the sweet spot in the whole catalog.

The **40G plan** is the only one that does not offer monthly billing at all. You choose between $52.99 semi-annually or $99.99 annually. If you want a month-to-month entry point, the 80G plan is your only option above the 20G tier.

One detail that applies to all PROMO plans: they support **multiple datacenter locations**, and BandwagonHost includes free automatic migration between datacenters, free automatic backups, and free snapshots. That last part matters — many budget VPS providers charge extra for backups.

If you want the classic entry plan, you can [👉 order the 20G KVM PROMO VPS at $49.99/year](https://bit.ly/BandwagonHost), or step up to the [👉 80G KVM PROMO VPS with 4 GB RAM from $19.99/month](https://bit.ly/BandwagonHost).

## Line 2: CN2 GIA V5 plans — premium routes to Asia, premium prices

The second line is where BandwagonHost pricing jumps significantly. These "SPECIAL 40G KVM PROMO V5" and larger plans are built around one thing: **China Telecom CN2 GIA routing** to key Asian hubs — Singapore, Osaka, Hong Kong, and Tokyo.

You pay a lot more than the PROMO line. Whether that premium makes sense depends entirely on what you're connecting to and from.

### Singapore (Equinix SG1)

| Plan | SSD | RAM | CPU | Transfer | Link speed | Monthly | Annually |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SPECIAL 40G | 40 GB | 2 GB | 2x | 500 GB/mo | 1.5 Gbps | $49.99 | $499.99 |
| SPECIAL 80G | 80 GB | 4 GB | 4x | 1 TB/mo | 1.5 Gbps | $86.99 | $869.99 |
| SPECIAL 160G | 160 GB | 8 GB | 6x | 2 TB/mo | 2.5 Gbps | $165.99 | $1,665.99 |
| SPECIAL 320G | 320 GB | 16 GB | 8x | 4 TB/mo | 2.5 Gbps | $329.99 | $3,199.00 |
| SPECIAL 640G | 640 GB | 32 GB | 10x | 6 TB/mo | 5 Gbps | $549.99 | $5,549.99 |
| SPECIAL 1280G | 1.28 TB | 64 GB | 12x | 8 TB/mo | 5 Gbps | $1,059.99 | $10,559.99 |

### Osaka (Equinix)

| Plan | SSD | RAM | CPU | Transfer | Link speed | Monthly | Annually |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SPECIAL 40G | 40 GB | 2 GB | 2x | 500 GB/mo | 1.5 Gbps | $49.99 | $499.99 |
| SPECIAL 80G | 80 GB | 4 GB | 4x | 1 TB/mo | 1.5 Gbps | $86.99 | $869.99 |
| SPECIAL 160G | 160 GB | 8 GB | 6x | 2 TB/mo | 1.5 Gbps | $165.99 | $1,665.99 |
| SPECIAL 320G | 320 GB | 16 GB | 8x | 4 TB/mo | 1.5 Gbps | $329.99 | $3,199.00 |
| SPECIAL 640G | 640 GB | 32 GB | 10x | 6 TB/mo | 1.5 Gbps | $549.99 | $5,549.99 |
| SPECIAL 1280G | 1.28 TB | 64 GB | 12x | 8 TB/mo | 1.5 Gbps | $1,059.99 | $10,559.99 |

The Osaka plans specify the routing explicitly: inbound traffic comes in via China Telecom CN2 GIA/CTG, China Unicom, and China Mobile, while outbound is China Telecom CN2 GIA/CTG.

### Hong Kong (Equinix HK2)

| Plan | SSD | RAM | CPU | Transfer | Link speed | Monthly | Annually |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SPECIAL 40G | 40 GB | 2 GB | 2x | 500 GB/mo | 1 Gbps | $89.99 | $899.99 |
| SPECIAL 80G | 80 GB | 4 GB | 4x | 1 TB/mo | 1 Gbps | $155.99 | $1,559.99 |
| SPECIAL 160G | 160 GB | 8 GB | 6x | 2 TB/mo | 1 Gbps | $299.99 | $2,999.99 |
| SPECIAL 320G | 320 GB | 16 GB | 8x | 4 TB/mo | 1 Gbps | $589.99 | $5,899.99 |
| SPECIAL 640G | 640 GB | 32 GB | 10x | 6 TB/mo | 1 Gbps | $989.99 | $9,989.99 |
| SPECIAL 1280G | 1.28 TB | 64 GB | 12x | 8 TB/mo | 1 Gbps | $1,889.99 | $18,989.99 |

Hong Kong plans route directly via China Telecom (CN2 GIA), China Unicom, and China Mobile.

### Tokyo (Equinix TY8)

| Plan | SSD | RAM | CPU | Transfer | Link speed | Monthly | Annually |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SPECIAL 40G | 40 GB | 2 GB | 2x | 500 GB/mo | 1.2 Gbps | $89.99 | $899.99 |
| SPECIAL 80G | 80 GB | 4 GB | 4x | 1 TB/mo | 1.2 Gbps | $155.99 | $1,559.99 |
| SPECIAL 160G | 160 GB | 8 GB | 6x | 2 TB/mo | 1.2 Gbps | $299.99 | $2,999.99 |
| SPECIAL 320G | 320 GB | 16 GB | 8x | 4 TB/mo | 1.2 Gbps | $589.99 | $5,899.99 |
| SPECIAL 640G | 640 GB | 32 GB | 10x | 6 TB/mo | 1.2 Gbps | $989.99 | $9,989.99 |
| SPECIAL 1280G | 1.28 TB | 64 GB | 12x | 8 TB/mo | 1.2 Gbps | $1,889.99 | $18,989.99 |

Tokyo plans add a detail: CN2 GIA preference is applied on outbound traffic specifically.

To make sense of these numbers: an identical 40G configuration costs $49.99/month in Singapore or Osaka, but $89.99/month in Hong Kong or Tokyo. That's an 80% price difference for the same hardware, purely because of where the machine sits and what routes it gets. Hong Kong and Tokyo capacity genuinely costs more.

The entry point to this entire line is the same whether you pick Singapore or Osaka: [👉 the SPECIAL 40G KVM PROMO V5 CN2 GIA plan at $49.99/month](https://bit.ly/BandwagonHost).

## Line 3: Ecommerce SLA Los Angeles — the business-grade tier

The third line is newer and quite different from everything else in the catalog. These plans trade the CN2 GIA branding for something more concrete: a **99.99% Service Level Agreement**, local NVMe storage, ECC memory, and a long list of infrastructure certifications on the facility.

| Plan | SSD | RAM | CPU | Transfer | Link speed | Quarterly | Annually |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 20G KVM - ECOMMERCE SLA LA | 20 GB NVMe | 1 GB ECC | 2x AMD dedicated | 1 TB/mo | 2.5 Gbps | $65.89 | $239.99 |
| 40G KVM - ECOMMERCE SLA LA | 40 GB NVMe | 2 GB ECC | 3x AMD dedicated | 2 TB/mo | 2.5 Gbps | $116.99 | $399.99 |
| 80G KVM - ECOMMERCE SLA LA | 80 GB NVMe | 4 GB ECC | 4x AMD dedicated | 3 TB/mo | 2.5 Gbps | $199.99 (qtr) | $699.99 |
| 160G KVM - ECOMMERCE SLA LA | 160 GB NVMe | 8 GB ECC | 6x AMD dedicated | 5 TB/mo | 5 Gbps | $299.99 (qtr) | $1,099.99 |

Note the differences from the standard line: the 80G and 160G Ecommerce plans have no monthly billing option, only quarterly and above. And unlike the PROMO line, these use dedicated AMD cores rather than shared Intel Xeon allocations, ECC RAM, and local NVMe instead of network-backed SSD.

The routing claims are specific: China Telecom CN2 GIA/CTGNet (AS4809/AS23764), China Unicom Premium (AS10099), China Mobile CMIN2 (AS58807), plus direct peering with Apple, Google, Facebook, ByteDance, and other networks. The facility carries SOC 1 Type 2, SOC 2 Type 2, ISO 27001, NIST 800-53, PCI DSS, and HIPAA certifications. The 160G plan even includes a free IP change once every 2 weeks, which is handy if you're doing anything that occasionally needs a fresh address.

For an online store that can't afford downtime, the $239.99/year entry price for a 99.99% SLA is a reasonable starting point. You can [👉 check the Ecommerce SLA Los Angeles plans here](https://bit.ly/BandwagonHost).

## How billing cycles actually affect BandwagonHost pricing

Almost every plan offers multiple billing terms, and the difference matters more than you might expect. Let's take the 80G KVM PROMO VPS as the example:

- Monthly: $19.99 ($239.88/year)
- Quarterly: $59.99 ($239.96/year)
- Semi-annually: $107.99 ($215.98/year)
- Annually: $199.99

Going annual instead of monthly saves about 17% on this plan. On the 160G PROMO plan, the gap is similar: $39.99/month ($479.88/year) versus $399.99/year.

The CN2 GIA V5 plans show the same pattern. The Singapore 40G plan costs $599.88/year if paid monthly, but $499.99/year if paid annually — again roughly a 17% discount for committing.

The general rule: **longer commitment = lower effective monthly price**, with annual billing being the cheapest term on every plan that offers it. If you're not sure whether a plan fits your needs, paying monthly for a couple of months first is the low-risk way to find out. If it works out, switch to annual.

One caveat on stock: BandwagonHost's cheaper plans — particularly the low-cost annual ones — do sell out from time to time. The order page will show an out-of-stock notice when a plan isn't currently available, and it's worth checking back or looking at neighboring plans when that happens. Current availability can be [👉 checked on the live plan listing](https://bit.ly/BandwagonHost).

## What every plan includes regardless of price

Whether you spend $49.99/year or $18,989.99/year, the feature baseline is consistent across the catalog:

- **KVM virtualization** via the KiwiVM control panel
- **Full root access**
- **1 dedicated IPv4 address** and a routed /64 IPv6 subnet
- **Free automatic backups** and free snapshots
- **Instant OS reload** and manual ISO install option
- **Choice of OS**: CentOS, Debian, Ubuntu, Rocky Linux, AlmaLinux
- **Instant rDNS (PTR) updates** from the control panel
- **99.95% uptime guarantee** on the standard line (99.99% SLA on the Ecommerce line)
- **Strictly self-managed service**

That last point deserves emphasis. Self-managed means BandwagonHost handles the hardware, network, and virtualization layer — you handle everything inside the VPS. There is no managed support tier, no one to email when your nginx config breaks. If you're comfortable with a Linux command line, this is fine and part of why the prices stay low. If you're not, a managed provider might be a better fit regardless of price.

## Which pricing tier actually fits your situation

Based on the prices and configurations above, the decisions are fairly clear-cut:

**Personal projects, learning, small self-hosted services.** The 20G PROMO plan at $49.99/year is the obvious entry point. The 1 GB RAM limit is real — a single small web app or a lightweight service fits, a WordPress site with heavy plugins will struggle.

**Self-hosting with room to breathe.** The 80G PROMO plan at $199.99/year gives you 4 GB RAM and 3 TB transfer. For most people running a handful of services, this is the best value in the entire catalog.

**Serving users in mainland China with premium connectivity.** This is what the CN2 GIA V5 line exists for. The question is which location. Singapore and Osaka are the cheaper entry points at $49.99/month for the 40G tier. Hong Kong and Tokyo cost $89.99/month for the same hardware but carry direct three-carrier routes. If latency to mainland China is the entire point of the purchase, the premium is usually justified; if not, Los Angeles-based plans are much cheaper.

**Running an actual business that needs guarantees.** The Ecommerce SLA Los Angeles line, starting at $239.99/year with a 99.99% SLA, ECC memory, and certified facility. This is the only line with contractual uptime language backed by specific certifications.

**Anything in between.** The 160G–480G PROMO plans fill the gap nicely — $399.99/year gets you 8 GB RAM and 4 TB transfer, which covers a lot of small production workloads.

## Things to verify before you order

A few practical points worth knowing, all visible on the order pages themselves:

1. **Datacenter location choice.** PROMO plans offer multiple locations at checkout. CN2 GIA V5 plans are locked to their named location.
2. **Stock status.** Cheap plans go in and out of stock. The order page always reflects current reality.
3. **Billing term locks the price.** Once you pick a term, that's your renewal price for that term. Switching terms later is possible but not automatic.
4. **No refunds on some promotions.** Deeply discounted annual plans often come with stricter refund terms than standard plans — worth reading before committing to a year.

## The bottom line on BandwagonHost pricing

The pricing structure is unusual but logical once you see the three lines: cheap general-purpose VPS in Los Angeles, expensive-but-justified premium routes to Asia, and a mid-priced business tier with real SLA language. There's no hidden pricing, no per-feature nickel-and-diming — what you see on the order page is the total cost.

For the vast majority of people searching for BandwagonHost pricing, the answer is one of two numbers: **$49.99/year** to get started on the 20G PROMO plan, or **$199.99/year** for the 80G plan if you want actual headroom. The CN2 GIA and Ecommerce lines serve narrower needs and cost accordingly.

If you've made up your mind, the current full catalog with live stock status is available here: [👉 browse BandwagonHost plans and order](https://bit.ly/BandwagonHost).
