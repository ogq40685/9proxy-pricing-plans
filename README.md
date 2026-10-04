# residential proxy service: per-IP or per-GB, and what each 9Proxy plan actually costs

Shopping for a residential proxy service usually starts with a provider list and ends with a bill you didn't expect. The provider matters, but the billing model does more damage. Per-GB pricing punishes you for every JavaScript-heavy page you scrape. Per-IP pricing punishes you for the small, bursty job that needs four addresses for a week.

So the useful question isn't "which service" but "which billing unit matches the way I use proxies." Below is what 9Proxy sells, what it costs, and where the model stops fitting.

## The billing question nobody asks until the invoice arrives

Say your crawler pulls 100,000 pages a month, and each page weighs 2 to 5 MB after rendering. That's roughly 200 to 500 GB of traffic. At common per-GB residential rates, that same workload has been estimated to run anywhere from $1,500 to $3,000 a month, and the number moves every time a target site redesigns its front end. Nothing about your code changed; the invoice did.

Now flip it. If instead you pay per IP with unlimited bandwidth, that traffic costs nothing extra once the IPs are bought. A 200 GB package on 9Proxy is $200 flat, and the 1,000 GB tier is $800. Same work, different meter.

The catch runs the other way too. If your job is 40 accounts on 40 different profiles and maybe 3 GB of traffic a month, buying 100 IPs is overkill in the wrong direction, and a small GB pack is cheaper.

## Two ways 9Proxy sells residential access

9Proxy splits its residential network into two products. They are not the same product with a different price tag, and the differences show up in setup, not just cost.

|  | Residential by IP | Residential by GB |
| --- | --- | --- |
| What you're billed for | A fixed number of IPs | Total traffic, in GB |
| Bandwidth | Unlimited while the IP is active | Capped by purchased GB |
| Expiry | Unused IPs never expire | 180 days (unlimited on Enterprise) |
| How long an IP lives | A few hours, up to about 24 hours | Rotates per request or per sticky session |
| How you access it | 9Proxy App, local port forwarding | Direct from the dashboard |
| Authentication | App, with optional proxy auth | Username/password or IP whitelist |
| Rotation | Auto Rotation Proxy on a schedule you set | Rotating and sticky modes |

The IP-based product is a port-forwarding tool on your own machine: you filter for a country, state, city, ZIP or ISP, forward a chosen IP to a local port, and point your software at `localhost:port`. Roughly speaking, you get a pile of vouchers, and a voucher is only spent when you forward it.

The GB product behaves like the residential proxies most people already know. Credentials in, rotating or sticky sessions out, no local app required.

## The full plan list, with current prices

9Proxy raised prices on IP-based and bundle packages for the first time on June 1, 2026. GB packages were left alone. The table below reflects the post-change prices published in third-party reviews; the entry tier moved from $20 to $24 for 100 IPs, which is why older write-ups still show the lower numbers.

### Residential proxy by IP

| Package | Price | Effective rate | Get it |
| --- | --- | --- | --- |
| 100 IPs | $24 | $0.24/IP | [open the 100 IP package](https://bit.ly/9-Proxy) |
| 500 IPs | $72 | $0.144/IP | [open the 500 IP package](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | $126 | $0.084/IP | [open the 1,000 + 500 IP package](https://bit.ly/9-Proxy) |
| 2,500 IPs | $210 | $0.084/IP | [open the 2,500 IP package](https://bit.ly/9-Proxy) |
| 5,000 IPs | $360 | $0.072/IP | [open the 5,000 IP package](https://bit.ly/9-Proxy) |
| 15,000 IPs | $720 | $0.048/IP | [open the 15,000 IP package](https://bit.ly/9-Proxy) |
| 25,000 IPs | $863 | $0.035/IP | [open the 25,000 IP package](https://bit.ly/9-Proxy) |
| 50,000 IPs | $1,438 | $0.029/IP | [open the 50,000 IP package](https://bit.ly/9-Proxy) |

The volume curve is steep at the bottom and flat in the middle. Going from 100 to 500 IPs cuts your per-IP cost by 40%. Going from 1,000 to 2,500 does nothing at all, because both sit at $0.084. If you're picking a tier, the 1,000 + 500 bonus package is the sweet spot: it costs 75% more than the 500 IP tier and gives you three times the addresses.

### Business IP packages

| Package | Price | Effective rate | Get it |
| --- | --- | --- | --- |
| 100,000 IPs | $2,300 | $0.023/IP | [open the business IP packages](https://bit.ly/9-Proxy) |
| 200,000 IPs | $4,140 | $0.021/IP | [open the business IP packages](https://bit.ly/9-Proxy) |
| 500,000 IPs | $8,625 | $0.018/IP | [open the business IP packages](https://bit.ly/9-Proxy) |

These exist for resellers and for teams running industrial-scale collection. Unless you're allocating IPs to sub-accounts, the standard tiers are cheaper to experiment with.

### Residential proxy by GB

| Package | Price | Effective rate | Validity | Get it |
| --- | --- | --- | --- | --- |
| 5 GB | $15 | $3.00/GB | 180 days | [start with 5 GB](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $105 | $2.10/GB | 180 days | [open the 50 GB package](https://bit.ly/9-Proxy) |
| 100 GB | $150 | $1.50/GB | 180 days | [open the 100 GB package](https://bit.ly/9-Proxy) |
| 200 GB | $200 | $1.00/GB | 180 days | [open the 200 GB package](https://bit.ly/9-Proxy) |
| 1,000 GB | $800 | $0.80/GB | 180 days | [open the 1,000 GB package](https://bit.ly/9-Proxy) |
| 2,000 GB | $1,500 | $0.75/GB | 180 days | [open the 2,000 GB package](https://bit.ly/9-Proxy) |
| 3,000 GB | $2,160 | $0.72/GB | No expiry | [open the enterprise GB packages](https://bit.ly/9-Proxy) |
| 10,000 GB | From $0.68/GB | Lowest tier | No expiry | [talk to 9Proxy about volume](https://bit.ly/9-Proxy) |

The jump from $3.00 to $1.00 per GB happens between the 5 GB and 200 GB tiers, and that's the gap worth understanding before you buy. Fifteen dollars buys 5 GB at the worst rate on the board. Two hundred dollars buys 200 GB at a third of that rate. If you already know you'll burn 100 GB this quarter, buying the small pack first is how you end up paying three times more for the same data.

One quirk: the 180-day clock applies to GB packages, not IP packages. If your workload is seasonal, that's a real deadline, and the enterprise tiers above 2,000 GB drop it.

### Bundle packages

| Bundle | Contents | Price | Get it |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | [open the Starter bundle](https://bit.ly/9-Proxy) |
| Popular | 1,500 IPs + 50 GB | $180 | [open the 1,500 IP + 50 GB bundle](https://bit.ly/9-Proxy) |
| Pro | 5,000 IPs + 500 GB | $720 | [open the 5,000 IP + 500 GB bundle](https://bit.ly/9-Proxy) |

Bundled traffic is valid for 180 days. Compare the Popular bundle against buying separately: 1,500 IPs at the $0.072 rate would be $108, and 50 GB sits between the $2.10 and $1.50 tiers. The bundle is priced for people who don't want to think about which meter is running.

## What the price buys beyond the IP count

The network itself is what most 9Proxy marketing leads with: over 20 million residential IPs across 90+ countries, HTTP/HTTPS and SOCKS5 support, and targeting down to country, state, city, ZIP code and ISP. That last level is the one that matters operationally. "Los Angeles, California, AT&T" is a very different request from "United States," and plenty of providers quietly can't do it.

Also included:

- Auto Refresh Proxy, which detects an IP that has gone offline and replaces it, so a long job doesn't die because one endpoint dropped
- Auto Rotation Proxy, which swaps IPs on a schedule you set per port
- The Today List, which lets you reuse any proxy from the previous 24 hours at no extra cost. 9Proxy puts the saving at 20–30% on session-heavy work.
- A 60-second credit policy: if a forwarded IP fails to connect within the first minute, you get the IP back
- Clients for Windows, macOS and Linux, plus Proxy2Web for browser-based use with no install, and ProxyHub for mobile device management
- A public API for programmatic session control and usage stats
- SOCKS5 support that drops straight into anti-detect browsers and automation stacks without protocol conversion
- 24/7 support through live chat, email and Telegram

The vendor also advertises 99.95% uptime and a success rate in the 92–99% range depending on which page you read. Treat those as vendor figures, not measured facts. An independent reviewer running a mixed workload across the US, Germany, UK, Brazil and India reported around 99.5% success on their own tests, which is a more useful number because it comes with a described method.

## The limits worth knowing before you pay

**An IP isn't static.** On the IP-based product, an address stays alive for a few hours up to about 24 hours. Users report sessions that die after roughly three hours on average. If you need the same IP for three months, this is the wrong product category entirely.

**IP plans want the desktop app.** You're forwarding ports locally, not pasting credentials into a dashboard. The GB product is the friendlier one for server-side pipelines, since it authenticates with user/pass or an IP whitelist.

**No published free tier.** 9Proxy runs limited trials for new users based on availability, and you generally have to ask for one and specify whether you want the IP-based or GB-based version. The realistic low-risk entry point is the $15 / 5 GB pack or the $24 / 100 IP package, backed by the 60-second credit rule.

**Pool size is mid-market.** Twenty million IPs is respectable and enough for almost everything, but it's smaller than the 55M–102M pools that Bright Data, Decodo and similar providers advertise. If you need a rare ZIP code in a small country, verify availability before committing budget.

**There were outages.** Third-party proxy catalogs documented service interruptions during the summer of 2026, including one user report describing the site and dashboard as unreachable for about a week, and one comparison site counted two separate blackouts. The same catalog now lists 9Proxy as restored and selling again. Two things follow from that: keep a fallback provider for anything revenue-critical, and don't park a year of budget in a wallet balance you can't withdraw.

## Cost math for three common workloads

**Multi-account management, 50–100 profiles.** You need one address per profile and very little traffic. 100 IPs for $24 covers it, and the addresses don't expire if you don't use them all this month. A GB plan would be a waste here.

**Continuous scraping, ~100,000 pages a month.** Estimate 200–500 GB depending on page weight. On GB billing that's the $200 package at $1.00/GB, or $800 for 1,000 GB if you have headroom. On IP billing, 5,000 IPs at $360 gives you unlimited traffic, which is meaningful if page sizes keep growing on you.

**Regional ad verification and SERP checks.** Low volume, high geo precision, lots of rotation. The 50 GB + 5 GB bonus pack at $105 is the sensible starting point; you can top up with a larger tier once you know your actual monthly burn.

## Signing up, paying, and where discounts come from

Sign-up takes a two-field form or a Google account, and there's no multi-day KYC queue before you can generate proxy credentials, which matters if you're used to enterprise providers that hold onboarding for days. You pick a package, pay, and then either download the app or grab credentials for Proxy2Web.

Payment options are broad: credit cards, crypto (USDT, BTC, ETH, LTC, DOGE and others), Alipay, Apple Pay, Google Pay, local region-specific methods, and the built-in wallet. There's a coupon field at checkout, so any code you have goes there.

About codes. 9Proxy runs seasonal promotions that rotate constantly, and the ones I can still see documented have already closed. STACK 99 ran 99 GB for $99 with a one-time 9% coupon and ended August 31. The April GB sale issued a 9% coupon valid to June 30. The LNY2026 code gave 8% off regular IP and GB packages in February. Copying any of those into your cart now will get you an error message.

What does still exist is the referral side: 9Proxy runs a lifetime affiliate program with commissions up to 15% and a 5% discount for users who arrive through a referral. That's the reliable saving, and it applies at sign-up rather than through a code hunt.

👉 [Sign up with the referral link to get the 5% discount applied](https://bit.ly/9-Proxy)

## FAQ

**Is 9Proxy a legitimate provider?**
It's a real service that issues working residential IPs when it's online. The recurring complaint isn't fraud, it's continuity. A comparison site user review from July 2026 reported the service being unreachable for about a week. Judge it on that basis: a workable budget option, not a provider you'd want as your only source on a revenue-critical pipeline.

**Does 9Proxy offer a free trial?**
There are limited trials for new users, subject to availability, and you need to specify IP-based or GB-based when you ask. The dependable alternative is the $15 5 GB pack paired with the 60-second credit policy for dead IPs.

**What's the cheapest way to test the network?**
$15 for 5 GB if your workload is traffic-driven, $24 for 100 IPs if it's session-driven and bandwidth-heavy.

**Do unused IPs expire?**
No. Unused IPs stay in your balance indefinitely on the IP-based product. Only GB traffic carries a 180-day validity window, and that disappears at the enterprise tiers.

**Rotating or sticky sessions?**
Both. GB-based plans rotate per request or hold a sticky session for a configurable period, and the IP-based product adds scheduled rotation through Auto Rotation Proxy.

**Which countries are covered?**
90+ countries, with targeting at country, state, city, ZIP and ISP level. Depth varies by region, and coverage is typically strongest in the US, Southeast Asia and Latin America.

## Who should buy which

If your bottleneck is bandwidth and you keep hitting data caps, get 100 IPs for $24 or 500 for $72 and stop watching a counter. The unlimited-traffic model is the whole reason to use this provider, and buying a small GB pack instead is choosing the worst of both.

If your bottleneck is geo coverage on a lightweight task, a GB plan is cheaper and rotates more naturally. Start at 50 GB + 5 GB for $105, not 5 GB for $15, unless you genuinely have nothing to test with.

If you're managing hundreds of profiles and need one clean IP per profile, the 1,000 + 500 bonus package at $126 is the tier where the per-IP math starts making sense. Anything below 500 IPs costs you $0.144 to $0.24 per address, which is a fine price for a pilot and a poor one for a standing operation.

And if you need the same IP alive for months, or you can't tolerate an outage window, look at static ISP proxies from a provider with a stronger uptime record. No amount of per-IP savings compensates for a pipeline that stops.
