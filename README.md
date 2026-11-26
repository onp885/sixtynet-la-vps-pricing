# Los Angeles VPS: SixtyNet's full plan lineup, the monthly math behind each annual price, and who should skip LA

SixtyNet's cheapest Los Angeles plan is LAX-STARTER: 2 cores, 2 GB RAM, 40 GB NVMe, 5 TB of traffic on a 2 Gbps port and DDoS protection listed, at **$200 a year**, which works out to **$16.67 a month**. That is roughly double what a 1–2 GB LA box costs elsewhere, where the entry tier runs $3.48–$8 a month. The gap explains the product: SixtyNet is selling China-optimised routing and residential IPs rather than cheap compute.

Los Angeles itself is the right region for serving the US West Coast and acceptable for Japan and Korea at 110–150 ms. It is the wrong region for European users, and the pricing below is the wrong fit for anyone who just wants the cheapest possible Linux box.

## Quick pick

> Most people searching for an LA VPS want a single box for a site, an API or a proxy, and the LAX line is the one to look at. **LAX-STARTER at $200/year (~$16.67/month)** covers that job with 2 cores, 2 GB RAM and 5 TB of traffic. Move to **LAX-MICRO at $400/year (~$33.33/month)** when you genuinely need 4 GB RAM and 10 TB. Both list DDoS protection in the feature set.
> 👉 [See SixtyNet's current Los Angeles plan prices](https://sixtynet.net/aff.php?aff=39)

## The full SixtyNet lineup, split by what each line is for

The pricing page groups plans by network type, not by size, and that grouping matters more than the core count. The LAX line is the general-purpose one. The Residential and IRVINE-PRO lines are built around a residential IP address, which changes who they are for.

### LAX line (DDoS protection listed)

| Plan | Cores · RAM | Storage | Traffic · Port | Price (USD, annual) | Order |
| --- | --- | --- | --- | --- | --- |
| LAX-STARTER | 2 · 2 GB | 40 GB NVMe, 12,500 IOPS | 5 TB · 2 Gbps | $200/yr · list $240 · save 17% · ≈$16.67/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| LAX-MICRO | 4 · 4 GB | 80 GB NVMe, 12,500 IOPS | 10 TB · 4 Gbps | $400/yr · list $480 · save 17% · ≈$33.33/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| LAX-MEDIUM | 8 · 8 GB | 160 GB NVMe, 25,000 IOPS | 20 TB · 10 Gbps | $800/yr · list $960 · save 17% · ≈$66.67/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| LAX-LARGE | 8 · 16 GB | 320 GB NVMe, 25,000 IOPS | 40 TB · 10 Gbps | $1,600/yr · list $1,920 · save 17% · ≈$133.33/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| LAX-Storage-500G | 4 · 4 GB | 300 GB + 200 GB bonus, RAID 10 | 10 TB · 10 Gbps | $400/yr · list $480 · save 17% · ≈$33.33/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| LAX-Storage, larger tier | 8 · 8 GB | 700 GB + 300 GB bonus, RAID 10 | 15 TB · 10 Gbps | price not displayed on the page | [Order](https://sixtynet.net/aff.php?aff=39) |

### Residential IP and China-optimised line

| Plan | Cores · RAM | Storage | Traffic · Port | Price (USD, annual) | Order |
| --- | --- | --- | --- | --- | --- |
| Residential-STARTER | 2 · 2 GB | 40 GB NVMe, 12,500 IOPS | 5 TB · 2 Gbps | $260/yr · list $300 · save 13% · ≈$21.67/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| Residential-MICRO | 4 · 4 GB | 80 GB NVMe, 12,500 IOPS | 10 TB · 4 Gbps | $460/yr · list $540 · save 15% · ≈$38.33/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| Residential-MEDIUM | 8 · 8 GB | 160 GB NVMe, 25,000 IOPS | 20 TB · 10 Gbps | $860/yr · list $1,020 · save 16% · ≈$71.67/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| Residential-LARGE | 16 · 16 GB | 320 GB NVMe, 25,000 IOPS | 40 TB · 10 Gbps | $1,660/yr · list $1,980 · save 16% · ≈$138.33/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| IRVINE-PRO-STARTER | 2 · 2 GB | 40 GB NVMe, 12,500 IOPS | 5 TB · 2 Gbps · AS9929 | $350/yr · list $420 · save 17% · ≈$29.17/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| IRVINE-PRO-MICRO | 4 · 4 GB | 80 GB NVMe, 12,500 IOPS | 10 TB · 4 Gbps · AS9929 | $550/yr · list $660 · save 17% · ≈$45.83/mo | [Order](https://sixtynet.net/aff.php?aff=39) |
| Los Angeles China Unicom-Premium | not listed | not listed | 100M base, 3× burst, 95th-percentile billing, AS9929, free BGP session | $2,500/yr · list $3,000 · save 17% · ≈$208.33/mo | [Order](https://sixtynet.net/aff.php?aff=39) |

Two gaps on that page are worth naming rather than filling in. The larger storage configuration is priced somewhere the page capture did not reach, and the China Unicom-Premium listing describes bandwidth terms (AS9929 premium transit, burst, 95th-percentile metering, BGP session setup) instead of cores and RAM, so ask for the compute spec before you assume it is a normal VPS.

## What the annual prices actually mean per month

Every price SixtyNet displays is annual, paired with a struck-through standard rate and a "save 13–17%" badge. The only billing-cycle language on the page sits on the China Unicom plan, which mentions quarterly and annual payment discounts. Nothing on the plan grid shows a monthly option, so treat monthly billing as something to confirm rather than something to assume.

The discount converts cleanly: **17% off an annual prepay is the same as paying for 10 months and getting 12**, which is why $240 becomes $200 on LAX-STARTER, or $20 a month dropping to $16.67. The residential line discounts less at the entry tier (13% on Residential-STARTER) and more as the plans grow (15–16%), so the cheap end of that line saves you about six weeks of fees rather than two months.

This is where shopping by headline price goes wrong, because three different pricing structures are in play across the LA market:

- **Struck-through discount pricing.** Cloudzy lists 1 GB at $3.48 against a $6.95 standard rate, a 50% cut with no end date published on the page. You cannot tell from the page whether renewal lands at $3.48 or $6.95.
- **Single-price pricing.** OliveVPS shows $3.99 for Starter and $7.99 for Pro with no discount badge at all, so the number you see is the number you keep paying.
- **Annual-only discounting.** INIZ prices monthly in pounds and takes 10% off for a year (£4.50 becomes £48.60), which is roughly 1.2 months free.

To compare across all three, convert everything to an effective monthly cost on a 12-month term, then ask what the same plan costs in month 13. SixtyNet's answer is visible in the table: $16.67 a month for 2 GB, $33.33 for 4 GB, $66.67 for 8 GB.

Against the rest of the LA market, that is not competitive on specs. A 1 GB LA box from the hosts I checked runs $3.48–$4.50 a month, a 4 GB production box $14–$16. SixtyNet's entry LAX plan costs more than a 4 GB plan at ExtraVM or Cloudzy. You are paying for 5 TB of traffic on a 2 Gbps port at the entry tier, and further up the line, for AS9929 routing or a residential IP.

## Where Los Angeles is fast, and where it is not

Every number below is vendor-reported, and the reporting methods differ: some hosts publish ranges, others publish a single benchmark point. Do not average them.

| Destination | Latency from LA | Source format |
| --- | --- | --- |
| Western US | 5–30 ms | Range published by ExtraVM |
| US East Coast | 60–80 ms | Range published by ExtraVM |
| Tokyo | 108 ms / 110–150 ms | Single benchmark from OliveVPS; range from ExtraVM |
| Sydney | ~150 ms | OliveVPS benchmark |
| Singapore | 160–180 ms | ExtraVM range |
| London | ~138 ms | OliveVPS benchmark |

The pattern is straightforward. LA gives you single-digit or low-double-digit milliseconds to California users and 60–80 ms to the East Coast, which is fine for most web workloads. Toward Asia you are looking at roughly 110–150 ms to Tokyo and 160–180 ms to Singapore, and both ExtraVM and OliveVPS claim LA is the lowest-latency US entry point for trans-Pacific traffic, since it sits at the main submarine cable landing zone. Treat that as a shared marketing claim rather than a measured fact.

For European users, LA is the worst of the major US regions. London at ~138 ms from Los Angeles is worse than what any East Coast location gives you, and no amount of premium routing fixes geography.

## What decides whether a plan actually works

**Ports 80 and 443 are closed on every Residential plan.** The page says so directly, citing IP risk control. If you plan to serve a website from a residential IP product, that is a hard stop, not a configuration detail. SixtyNet states that any refund on the IRVINE-PRO plans is issued as website balance, and those plans additionally reject all external probes and scans with access restricted until you whitelist or port-forward. Budget setup time before you expect a working connection.

**DDoS protection is listed only on the LAX line.** The Residential and IRVINE-PRO feature lists do not mention it. If filtering is part of why you are buying, stay on LAX.

**SixtyNet's plan listings do not name an operating system.** Linux is the safe assumption given the specs, but Windows is not documented anywhere on the page. Elsewhere in this market Windows is a paid upgrade rather than a checkbox: OliveVPS sells its $3.99 Starter as Linux-only and pushes Windows buyers to the $7.99 Pro or $15.99 Premium, which carry a licensing surcharge. The cheapest tier is usually the one that cannot run Windows. Ask SixtyNet support directly before paying for a year.

**Refund terms are thin.** No free trial or money-back window appears on the SixtyNet plan grid. The only refund language is on the IRVINE-PRO plans, and it points to account credit. For comparison, Cloudzy advertises 14 days no-questions-asked and OliveVPS 7 days with no free trial. On a $400–$1,600 annual prepay, that difference is worth a support ticket.

**Overage is priced differently by line.** The China Unicom plan uses 95th-percentile billing with burst, which is a transit-style meter and behaves nothing like a traffic allowance. SixtyNet does not publish an overage rate for the LAX or Residential plans. OliveVPS publishes $0.005/GB on its LA plans, which is the kind of number you want in writing before running anything video-heavy.

**IPv6 is unconfirmed.** A third-party test published in October 2025 reported no IPv6 support on SixtyNet's residential line, and the pricing page does not mention IPv6 either way. If you need a /64, verify first.

👉 [Check whether the plan you want sits on the LAX line or the residential line](https://sixtynet.net/aff.php?aff=39)

## How the alternatives compare (information only)

| Host | Plan | Cores · RAM | Storage · Traffic | Price | Notes |
| --- | --- | --- | --- | --- | --- |
| ExtraVM | 1 GB | 1 · 1 GB | 15 GB NVMe · 3 TB, 1 Gbps | $4.50/mo | DDoS included, Burbank Tier IV facility |
| ExtraVM | 2 GB | 1 · 2 GB | 30 GB NVMe · 5 TB, 1 Gbps | $8.00/mo | Same feature set |
| OliveVPS | Starter | 1 · 1 GB | 25 GB NVMe · 1 TB, 1 Gbps | $3.99/mo | Linux only, 7-day refund |
| OliveVPS | Pro | 1 · 2 GB | 60 GB NVMe · 3 TB, 1 Gbps | $7.99/mo | Windows allowed |
| Cloudzy | 1 GB | 1 · 1 GB | 25 GB NVMe · 1 TB, 40 Gbps | $3.48/mo, listed against $6.95 | 14-day refund, hourly billing |
| Cloudzy | 2 GB | 1 · 2 GB | 60 GB NVMe · 3 TB, 40 Gbps | $7.48/mo, listed against $14.95 | Same terms |
| INIZ | 1 GB | 1 · 1 GB | 20 GB NVMe · 2 TB, 2.5 Gbps | £4.50/mo, £48.60/yr | 100 Gbps L3/4 DDoS, no Windows listed |
| INIZ | 4 GB | 2 · 4 GB | 80 GB NVMe · 8 TB, 2.5 Gbps | £16.00/mo, £172.80/yr | Same terms |

CloudFanatic was listed at $2.99 for 1 GB in May 2025, but that figure is more than 18 months old and may no longer be live.

On specs per dollar, SixtyNet loses this table. Two cores and 2 GB cost $16.67 a month at SixtyNet against $7.48–$8.00 at Cloudzy, OliveVPS and ExtraVM. SixtyNet wins only where the others do not compete: AS9929 China Unicom routing on the IRVINE-PRO and China Unicom plans, a residential IP that streaming and e-commerce platforms read as a home connection, and 10 Gbps ports paired with 20–40 TB of traffic at the top of the LAX line. If none of those three matter, buy the cheaper box.

## Which plan to pick

- One site, API, bot or proxy with US traffic → **LAX-STARTER**, $200/year.
- Need 4 GB of real RAM or more than 5 TB of traffic → **LAX-MICRO**, $400/year.
- Need disk more than CPU → **LAX-Storage-500G** costs the same $400 as LAX-MICRO and swaps 4 cores and 80 GB for 4 cores and 500 GB of RAID 10.
- Need 16 GB of RAM → **LAX-LARGE** at $1,600/year, and note it comes with 8 cores, not 16.
- Need a residential IP for streaming, account management or marketplace work → **Residential-STARTER** at $260/year, with ports 80 and 443 off the table.
- Need both a residential IP and China-optimised routing → **IRVINE-PRO-STARTER** at $350/year, and plan for the default-deny firewall.
- Need dedicated China Unicom transit with 95th-percentile metering → the **AS9929 plan** at $2,500/year, after you get the compute spec in writing.
- Serving European users → pick a European region. LA is the worst choice on the board for that traffic.

Two things to confirm before you enter a card number: whether the plan you chose can be billed monthly rather than annually, and what the refund terms are, since only the IRVINE-PRO plans state one and it comes back as account balance.

👉 [Start from SixtyNet's VPS hosting page and pick your line](https://sixtynet.net/aff.php?aff=39)
