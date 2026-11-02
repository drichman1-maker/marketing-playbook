# CodeMode Apps and the 16 aggregator sites

## What exists

Sixteen live sites plus Low Key Mode on codemodeapps.com. Nine on their own
domains (theresmac.com, gpudrip.com, healthindex.app, babygearhere.com,
robotsniper.com, coincurator.app, sluggerdata.com, mintcondition.app,
rumbledeals.com) and seven on subdomains (homegear, evdrip, tooldrip,
autofixed, eventplanner, sounddrip, cardroster). Amazon Associates is active
with per-site tags. Scrapers already collect price data on a schedule.

## The honest problem

Google's 2024 to 2026 updates target exactly this pattern: many thin
affiliate catalogs from one operator. Sixteen sites with no backlinks and no
original material will sit near zero no matter how clean the code is. The
way out is not more sites. It is making three of them the kind of site
people cite.

## Pick three

Default picks until Search Console says otherwise:

1. **TheresMac.** Apple deal hunting is a huge, searchable, seasonal market
   and the site already has price history and alerts. November and December
   are its best months.
2. **GPU Drip.** r/buildapcsales and the PC-building forums are the most
   active deal communities on the internet. Price history on GPUs is content
   people genuinely want.
3. **Mint Condition.** Graded Pokemon and comics have obsessive communities
   and the data (PSA population, sold comps) makes shareable charts.

Swap any of these after the two-week baseline if another site shows more
impressions.

## What each focus site gets

- **One citable data asset a month.** A monthly price index built from the
  scraper data. "Mac price index, November 2026." "GPU street price vs MSRP
  tracker." "Graded Charizard index." Publish it as a page with a chart, a
  short methodology, and a one-paragraph takeaway. This is the only content
  that earns links for free, because journalists and Redditors cite numbers.
- **One weekly article answering a search query.** Pick queries from Search
  Console that already show impressions but rank on page two. Rewrite or
  expand those pages before writing anything new.
- **Automated daily deal post.** From the scraper output, post the single
  biggest price drop of the day to X and Bluesky with a plain link, no
  affiliate tag on the social post. One script, cron, done.
- **Deal alert email.** TheresMac already has alerts. Make that the main
  call to action on all three. Email is the only audience you own.
- **Structured data.** Product and Offer JSON-LD on every product page, plus
  BreadcrumbList. It is in `SEO-HYPE-TRACKER.md` already and unticked.

## Community rules (free, and easy to get banned from)

- r/buildapcsales, r/macdeals, r/appledeals, r/PokemonTCG, r/pkmntcgdeals all
  ban or shadow-limit affiliate links. Post deals there with the retailer's
  direct link, not yours. The brand mention in the post title or a comment
  ("spotted on GPU Drip") is what you are after.
- Answer price questions in those communities for a month before ever
  linking the site. Reddit karma on the account matters.
- Discords: PC building servers, Pokemon investing servers. Same rules.

## The other thirteen

Keep them live, indexed and automated. No manual time. Specifically:

- Analytics and Search Console verification, once.
- Automated daily deal post if the scraper already exists for that niche.
- Shared footer cross-links to the three focus sites and to Low Key Mode.
- Review in February. Any site under 50 clicks a month is parked: left
  online, removed from the hub's "LIVE" list, no further deploys.

Do not launch another aggregator until one of the three focus sites clears
1,000 search clicks a month.

## The hub (codemodeapps.com)

The hub does two jobs: prove the portfolio to custom-build clients and send
traffic to the apps. Right now it does the first well. Two changes:

- Add a short "Latest from the network" block that pulls the newest data
  article from each focus site. Gives the hub a reason to be crawled often.
- The "$5,000+ custom projects" block is the real revenue line on this page.
  Put one case study above it with a number in it (traffic, revenue, time
  saved). Sixteen shipped sites is a better pitch than any agency's portfolio;
  say that in one sentence.
