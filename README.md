# 9proxy residential proxies: pay-per-IP vs per-GB, what each tier costs, and how to pick without burning budget

Most people typing this into a search bar are stuck on the same question: does 9Proxy's "unlimited bandwidth per IP" model actually save money, or is it just a pricing gimmick that punishes you the moment your traffic goes up?

Short answer: it depends entirely on whether your job burns bandwidth or burns IPs. 9Proxy sells both models side by side, so the decision isn't "is this provider good" — it's "which of the three product lines fits the task in front of me." That's what this article sorts out, with current prices and the mechanics that decide which plan is cheaper.

## What 9Proxy actually sells

9Proxy is a residential proxy provider with a pool it advertises at 20M+ real residential IPs across 90+ countries. It supports HTTP/HTTPS and SOCKS5, targets down to country, state, city, ZIP and ISP level, and splits its catalog into three products:

- **Residential Proxy by IPs** — you buy a fixed number of IPs and pay nothing for traffic. Bandwidth is unlimited while an IP is active.
- **Residential Proxy by GB** — you buy a traffic package and generate as many endpoints as you want until the balance runs out.
- **Bundle plans** — IPs and bandwidth in one prepaid package.

The interesting mechanic sits in the IP-based product, and it's the part most reviews gloss over: **an IP is only deducted from your balance when you forward it to a local port.** Buying 1,000 IPs doesn't burn 1,000 IPs. It burns the ones you actually activate, and unused balance doesn't expire.

Two more details that matter before you compare prices.

Activated IPs stay online for a few hours up to roughly 24 hours. That isn't a bug — the IPs belong to real home connections, so they drop off when the person behind them closes their laptop or switches networks. 9Proxy's own support replies on review sites point this out when users complain about IPs dying after an hour. If you need a genuinely fixed IP for weeks, a residential pool is the wrong tool; the same is true of every provider in this category.

And GB packages carry 180-day validity, which is unusually forgiving for pay-as-you-go bandwidth. Project-based work doesn't get its balance confiscated at the end of the month.

## Which model fits your workload

This is the table you actually need before looking at tiers.

| Your workload looks like | Better model | Why |
| --- | --- | --- |
| Long logged-in sessions, heavy page loads, video, large API payloads | Pay-per-IP | Traffic is free per activated IP; a bandwidth meter would bleed you dry |
| Thousands of short requests, price checks, SERP pulls, ad verification | Pay-per-GB | You rotate constantly and consume very little data per request |
| Multi-account setups in anti-detect browsers, one IP per profile | Pay-per-IP | Each profile needs its own IP, and per-profile traffic is unpredictable |
| Spikey, project-based scraping with a hard deadline | Pay-per-GB (or a bundle) | You pay for the spike, not for a shelf full of idle IPs |
| Both at once — some clients on sticky IPs, others on rotating traffic | Bundle | One package covers mixed workloads without two separate top-ups |

The failure mode is predictable on both sides. People who buy IPs for a rotation-heavy scraping job end up with IPs they never forward. People who buy gigabytes for long streaming or heavy-page sessions watch the counter evaporate in an afternoon.

## Every current 9proxy residential proxy plan and price

9Proxy adjusted IP-based and bundle pricing on June 1, 2026 — the first change in its history — and left GB pricing untouched. These are the current published prices.

### Pay-per-IP plans (unlimited bandwidth per activated IP)

| Package | Price | Effective cost | Notes | Buy |
| --- | --- | --- | --- | --- |
| 100 IPs | $24 | $0.24/IP | Best for proof-of-concept runs | [Start with 100 IPs](https://bit.ly/9-Proxy) |
| 500 IPs | $72 | $0.14/IP | Solo operators, light multi-accounting | [Grab the 500 IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $126 | ~$0.08/IP | Small teams running steady workloads | [Get the 1,000 + 500 bonus deal](https://bit.ly/9-Proxy) |
| 2,500 IPs | $210 | ~$0.08/IP | Several verticals at once | [Buy 2,500 IPs](https://bit.ly/9-Proxy) |
| 5,000 IPs | $360 | ~$0.07/IP | Agencies, mid-scale scraping and SEO stacks | [Buy 5,000 IPs](https://bit.ly/9-Proxy) |
| 15,000 IPs | $720 | ~$0.05/IP | Regional teams, heavier automation | [Buy 15,000 IPs](https://bit.ly/9-Proxy) |
| 25,000 IPs | $863 | ~$0.035/IP | Resellers, automation labs | [Buy 25,000 IPs](https://bit.ly/9-Proxy) |
| 50,000 IPs | $1,438 | ~$0.029/IP | Platform-level operations | [Buy 50,000 IPs](https://bit.ly/9-Proxy) |
| 100,000 IPs | $2,300 | ~$0.023/IP | Commercial volume | [Request the 100,000 IP tier](https://bit.ly/9-Proxy) |
| 500,000 IPs | $8,625 | ~$0.017/IP | Largest published tier | [Request the 500,000 IP tier](https://bit.ly/9-Proxy) |

Billing is one-off and prepaid. There is no monthly subscription, and unused IP balance does not expire.

### Pay-per-GB plans (180-day validity)

| Package | Price | Per GB | Buy |
| --- | --- | --- | --- |
| 5 GB | $15 | $3.00 | [Buy a 5 GB test package](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $105 | $2.10 | [Buy the 50 GB + 5 GB package](https://bit.ly/9-Proxy) |
| 100 GB | $150 | $1.50 | [Buy 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | $200 | $1.00 | [Buy 200 GB](https://bit.ly/9-Proxy) |
| 1,000 GB | $800 | $0.80 | [Buy 1,000 GB](https://bit.ly/9-Proxy) |
| 2,000 GB | $1,500 | $0.75 | [Buy 2,000 GB](https://bit.ly/9-Proxy) |

Volume pricing continues past that table and bottoms out around $0.68 per GB at the 10,000 GB tier — roughly a quarter of the entry rate. If you're shopping at that level, get the number in writing.

### Bundle plans (IPs + bandwidth, 180-day traffic validity)

| Package | Contents | Price | Buy |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | [Buy the Starter bundle](https://bit.ly/9-Proxy) |
| Popular | 1,500 IPs + 50 GB | $180 | [Buy the Popular bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | [Buy the Pro bundle](https://bit.ly/9-Proxy) |

### Enterprise

Enterprise isn't published as a fixed price — you go through sales. What it adds is worth knowing: unlimited data validity instead of 180 days, team mode with one owner and up to five members, no-expiration bandwidth sharing inside the team, per-member traffic controls, full activity logs, and dedicated support. For agencies billing several clients, the shared pool is the part that matters more than the per-GB rate.

## What a month actually costs — three quick calculations

Prices are meaningless without a workload attached, so here's the arithmetic at published rates.

**Scenario 1: 100 browser profiles, 40 GB of traffic this month.** On per-IP at the 100-IP tier you'd pay $24, and the 40 GB costs nothing extra because bandwidth isn't metered. On per-GB, 40 GB at the 100 GB tier rate of $1.50/GB runs about $60. The IP plan wins by a wide margin — and it isn't close.

**Scenario 2: 8 GB of traffic spread across 20,000 rotating IPs.** Per-IP here is absurd — you'd be paying for IPs you never forward. A 5 GB pack at $15 plus a second one gets you there for around $30, versus $24 for 100 IPs if you could somehow squeeze the rotation into 100 addresses. Rotation is the whole point here, so the GB model wins.

**Scenario 3: a client project — 200 IPs for account work plus 30 GB for a scraper.** Buying separately is 500 IPs ($72) plus a 50 GB pack ($105) = $177, and you're leaving 300 IPs sitting in the balance. The $180 Popular bundle gives you 1,500 IPs and 50 GB with matching 180-day validity. If you already know you'll reuse the IPs, the IP plan is still cheaper; if the project might end in six weeks, the bundle's flexibility is worth the extra three dollars.

The reusable takeaway: per-GB wins when your traffic per IP is small, per-IP wins when your traffic per IP is large.

## How you actually connect

The two products have genuinely different setups, and this trips people up.

**IP-based proxies** run through the 9Proxy desktop app on Windows, macOS or Linux. You filter the pool by country, state, city, ZIP or ISP, forward an IP to a local port, and use it at `localhost:port`. Optional proxy authentication keeps other local applications off the port. There's also Proxy2Web, a browser-based option for the IP product that avoids installing anything — useful if you're on a machine you don't control.

**GB-based proxies** skip the app entirely. Everything happens in the dashboard's Proxy Generator: pick your authentication method, pick your location filters, choose sticky or rotating, export endpoints as `.txt` or `.csv`, and grab ready-made code samples. Authentication is either a sub-user with username/password or IP whitelisting, where your machine's IP is approved and then connects with no credentials at all.

## Targeting, sticky sessions, and the username you'll be typing

On the bandwidth product, all targeting lives inside the username string. The general shape:


<subuser>-country-<code>-st-<state>-city-<city>-isp-<isp_code>-sst-<minutes>-ssid-<id>


Only the parameters you need are required. `country-us` gives you a rotating US IP. Add `sst-15` and you hold that IP for 15 minutes. Add `ssid-device1` and you can run several sticky IPs from the same configuration, each with its own session ID. A working call looks like:

bash
curl -x yourproxyhost:yourport \
  -U "subuser-country-us-sst-15-ssid-bot01:yourpassword" \
  https://ipinfo.io


One practical warning from 9Proxy's own documentation: over-filtering shrinks your available pool. Stacking state + city + ISP on a target market you don't actually need precision for will slow down responses and increase failures. Target by country when the country is enough.

## Performance: the benchmarks disagree, so test on your own targets

Here's where you should be sceptical of every review, including the flattering ones.

One detailed third-party test published late in 2025 reported roughly 99.5% average success rates across US, DE, UK, BR and IN, around 0.6 seconds average response time, and near-99.4% uptime on key routes over a week. A proxy comparison directory, meanwhile, lists 9Proxy at 97% success with 1,300 ms average response — twice the latency and a noticeably worse hit rate. Another independent cost analysis slots 9Proxy into the "budget tier" at roughly $0.70–$2 per GB and notes success rates of 90–95% on moderately protected targets.

Those numbers come from different targets, different sample sizes and different time windows. None of them describe *your* workload. The honest version of this: 9Proxy lands where you'd expect a budget-tier residential pool to land. Fine on unprotected and lightly protected targets, less reliable against hard anti-bot stacks, and heavily dependent on which sites and regions you're hitting.

Which means the only sensible pre-purchase test is a small one. A 5 GB pack at $15 is $15 of information you can turn into a keep-or-leave decision after a day of real traffic. 👉 [Run your own test on a 5 GB pack](https://bit.ly/9-Proxy)

## Reviews, downtime reports, and the risk you should price in

Third-party directory scores sit in the 3.9/5 range, and user-submitted ratings on some tools directories cluster around 4.3/5. The Trustpilot profile is a different story — it sits in the lowest rating band, and the negative reviews repeat two themes: IPs dropping after roughly an hour, and interruptions to service in mid-2026. 9Proxy has answered those complaints directly, explaining that residential IP lifetimes can't be guaranteed because the underlying devices belong to real people who go offline.

There's a competitive angle worth flagging: at least one site talking up 9Proxy's mid-2026 outages sells alternatives on a shared balance, so treat that framing as marketing rather than reporting. But the underlying facts — that residential IPs churn, and that a provider can have bad weeks — are true of the entire category, not just this one.

What follows from that is a purchasing habit, not a warning label. Don't park six months of budget in a wallet you can't use if something breaks. Buy the IP volume you're going to consume this quarter, keep the rest of the money on your side of the table, and judge the service on a real test rather than on a review written by someone with an affiliate link — this one included.

## Where 9Proxy fits, and where it doesn't

**Good fit:** scraping and price monitoring on unprotected to moderately protected targets; multi-account work in anti-detect browsers where you need clean IPs per profile; geo-verification and ad checking; teams that need both sticky IPs and bulk rotation without buying from two vendors. The pay-per-IP model is genuinely unusual, and if your jobs are heavy on traffic and light on IP count, it's the cheapest structure in this price bracket.

**Poor fit:** you need a fixed IP that stays put for weeks — that's a static ISP product, and 9Proxy's answer is a rotating residential pool. Also a poor fit if your targets are Tier 3 hardened sites where a 70–85% success rate would wreck the pipeline; that's Bright Data or Oxylabs territory, at three to five times the per-GB price. And if you're a first-time proxy user who wants a support engineer to configure your scraping stack, the pay-per-IP workflow with port forwarding and localhost ports assumes you already know your way around SOCKS5.

## FAQ

**Is there a free trial?** 9Proxy has said in its own forum posts that it offers a limited trial for new users depending on availability, and the signup itself costs nothing. Treat the trial as unreliable and the 5 GB pack as your real test.

**Do unused IPs expire?** No. They stay in your balance until you forward them. That's the single biggest advantage of the IP-based model for stop-start projects.

**Which is cheaper, pay-per-IP or pay-per-GB?** Divide your total monthly traffic by the number of IPs you need. Above roughly 1–2 GB per IP, the IP model usually wins. Below it, bandwidth pricing wins.

**Are there discount codes?** 9Proxy runs rotate — there was an 8% Lunar New Year code covering regular IP and GB packages that ran through late February 2026, and the site has offered additional discounts or product bonuses tied to specific payment methods. None of those are permanently applicable, so don't build a budget around a code you read about six months ago. Registering through the invite link is the dependable route. 👉 [Create your account and see current rates](https://bit.ly/9-Proxy)

**Can I share a package with a team?** On standard plans, bandwidth sharing outside your account follows the 180-day limit. Enterprise removes the expiry and adds five team seats with per-member traffic controls.

## Bottom line

9Proxy's residential proxy catalog isn't a tier ladder so much as two different products wearing the same logo. If your jobs push real data through a small number of sessions, the pay-per-IP line at $24 for 100 IPs with unlimited bandwidth is one of the cheaper structures you'll find, and the non-expiring balance makes it forgiving of uneven project flow. If your jobs rotate through thousands of addresses with tiny payloads, buy gigabytes and stop thinking about IP counts entirely.

Pick the model first, then the tier size. Buy small, test against your own targets for a day, and scale the balance once the success rate proves itself on your traffic rather than on somebody else's benchmark table. 👉 [Start with a small package and test it against your own targets](https://bit.ly/9-Proxy)
