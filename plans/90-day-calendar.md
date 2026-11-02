# 90-day calendar (3 Nov 2026 to 1 Feb 2027)

Budget assumption: under $50 a month total, all of it on tools already paid
for (Vercel, domains, Apple developer account). Time assumption: roughly ten
hours a week on marketing across everything. If that is too much, cut the
long-tail aggregator work first, never the measurement.

## Weeks 1 to 2: measure and unblock (3 to 16 Nov)

- [ ] Add a privacy-friendly analytics tag to every property. Plausible,
      Umami self-hosted, or Cloudflare Web Analytics (free). One shared
      component in `agg-monorepo` so the sixteen sites get it in one deploy.
- [ ] Verify every domain and subdomain in Google Search Console and Bing
      Webmaster Tools. Submit each sitemap.
- [ ] Add an email capture to the three focus aggregator sites and to
      lowkeymode.com. Buttondown free tier or a Formspree form into a sheet.
- [ ] Replace the Low Key Mode mailto beta request with a TestFlight public
      link, or a one-field form if the build is not ready.
- [ ] Record a baseline: impressions, clicks and top queries per site from
      Search Console after 14 days of data. Put it in `metrics/` in this repo.
- [ ] Secure the social handles in `SEO-HYPE-TRACKER.md` for the three focus
      sites, Low Key Mode and Iron Stake only. Skip the rest.

## Weeks 3 to 4: pick the three and launch Low Key Mode (17 to 30 Nov)

- [ ] Rank the sixteen aggregators by Search Console impressions. Pick the top
      three. If data is thin, default to TheresMac, GPU Drip and Mint
      Condition (own domains, large deal-hunting communities, seasonal peak in
      November and December).
- [ ] Low Key Mode launch sprint. Full checklist in `lowkeymode.md`. Target
      launch day: Tuesday 25 November or the first Tuesday after the App
      Store approval lands.
- [ ] Iron Stake: build the seller prospect list (200 names). Details in
      `ironstake.md`.
- [ ] Web design: send the first batch of 20 Loom audits. Details in
      `webdesign.md`.

## Weeks 5 to 8: content and supply (1 to 28 Dec)

- [ ] One data-driven article per focus site per week, built from the price
      data the scrapers already collect. Holiday deal season is the best
      month of the year for TheresMac and GPU Drip.
- [ ] Automate a daily "biggest price drop" post per focus site to X and
      Bluesky from the existing scraper output. Zero marginal effort once
      built.
- [ ] Iron Stake: 50 seller conversations. Goal is ten approved listings in
      one metro before any buyer marketing.
- [ ] Web design: second batch of 20 audits. Follow up the first batch.
- [ ] Low Key Mode: post-launch, reply to every review, ship one update,
      pitch three app roundup newsletters.

## Weeks 9 to 13: double down or cut (29 Dec to 1 Feb)

- [ ] Review the metrics. Any focus site that has not doubled impressions
      gets swapped for the next best one.
- [ ] Park aggregator sites with under 50 clicks a month. Keep them live and
      indexed, stop touching them.
- [ ] Iron Stake: once ten real listings exist, start buyer-side posting in
      local Facebook groups and r/realestateinvesting, and run the first
      email to the real estate list.
- [ ] Write the quarter review in `metrics/2027-q1-review.md`.

## Weekly operating rhythm

| Day | 30 to 90 minutes | Property |
|---|---|---|
| Mon | Check analytics and Search Console. Note one thing to fix. | All |
| Tue | Write or finish the week's data article. | Focus aggregator |
| Wed | Seller outreach calls and messages. | Iron Stake / real estate |
| Thu | Send five Loom audits. Follow up last week's five. | Web design |
| Fri | Community replies: Reddit, Discord, forums. No links unless asked. | Rotating |
| Daily | One build-in-public post in one place. Ten minutes. | You |

## Metrics that matter

Track these monthly in `metrics/`. Nothing else until these move.

| Property | Leading metric | Lagging metric |
|---|---|---|
| Focus aggregators | Search impressions | Affiliate clicks and earnings |
| Long-tail aggregators | Indexed pages, zero effort | Earnings |
| Low Key Mode | Waitlist and TestFlight signups, then App Store page views | Downloads, subscriptions |
| Iron Stake | Seller conversations per week | Paid, approved listings |
| Web design | Audits sent | Proposals, closed projects |
| Real estate | Touches per week to past clients and partners | Referrals, listings |
