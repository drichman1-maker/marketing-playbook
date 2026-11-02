# Marketing Playbook

Zero-budget marketing plan for the portfolio. Started 2 November 2026 from a
Claude Code session; keep editing it here rather than starting new notes.

Properties covered:

| Property | What it is | Plan |
|---|---|---|
| CodeMode Apps (codemodeapps.com) | Hub for 16 live affiliate / research aggregator sites | [plans/aggregators.md](plans/aggregators.md) |
| Low Key Mode (lowkeymode.com) | iOS calm-score + Tone Studio app, pre-launch | [plans/lowkeymode.md](plans/lowkeymode.md) |
| Iron Stake (iron-stake.com) | Lease-to-purchase listing marketplace, pre-launch | [plans/ironstake.md](plans/ironstake.md) |
| Web design (Baseline Designs / CodeMode custom builds) | Services business, the cash engine | [plans/webdesign.md](plans/webdesign.md) |
| Real estate | Agent business, feeds and is fed by Iron Stake | [plans/realestate.md](plans/realestate.md) |

The 90-day calendar and the weekly operating rhythm are in
[plans/90-day-calendar.md](plans/90-day-calendar.md). Start there.

## What the audit found (2 Nov 2026)

Read from the repos `agg-monorepo`, `codemode-site`, `lowkeymode-landing-page`,
`iron-stake` and `ironstake-sites`. The live sites could not be fetched from the
session, so this is what the code says, not what the browser shows.

1. **Nothing is measured.** No analytics tag and no email capture appear in the
   homepages of codemodeapps.com, lowkeymode.com or iron-stake.com. The
   aggregator sites were not checked one by one, but the hub has none. Every
   decision below depends on fixing this first.
2. **The existing marketing strategy doc is an empty template.**
   `agg-monorepo/marketing-strategy-2026.md` has headings and no content.
   `SEO-HYPE-TRACKER.md` lists social handles to secure; none are ticked.
3. **The affiliate side is in good shape.** `affiliate-registry.json` is a
   disciplined single source of truth with Amazon Associates active and
   per-site tags. Monetization is not the bottleneck. Traffic is.
4. **Seventeen properties, one person.** Sixteen aggregator sites plus Low Key
   Mode on the hub. Seven of them live on `codemodeapps.com` subdomains, nine
   on their own domains. Effort is spread evenly across all of them, which
   means none of them gets enough to rank.
5. **Low Key Mode's beta flow is a mailto link.** Requesting beta access opens
   the visitor's mail app with a draft. That loses most of the people who
   click. A TestFlight public link or a one-field form fixes it in an hour.
6. **Iron Stake is a two-sided marketplace with no supply yet.** Sellers pay
   $249 a year, buyers are free, and the homepage shows sample homes. The
   August action plan says seller prospecting is "handled separately." It is
   the whole launch problem.
7. **Real estate and Iron Stake are the same audience.** Tired landlords,
   FSBO owners and buyers who cannot get a mortgage yet are leads for both.
   The agent licence and local network are Iron Stake's cheapest seller
   acquisition channel.

## The three rules

1. **Measure before marketing.** Week 1 is analytics and Search Console on
   every property. No channel work until a baseline exists.
2. **Concentrate.** Three aggregator sites get real attention. The other
   thirteen get automation only. Low Key Mode gets a two-week sprint. Iron
   Stake gets supply-side outreach, not awareness.
3. **One channel, daily.** Build in public in one place. Everything else is
   automated or scheduled, not improvised.
