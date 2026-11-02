# Iron Stake: the publishing-platform model

Written 2 November 2026. This is the operating model and the reasoning
behind it, not legal advice. The state-by-state opinion in
`iron-stake/docs/legal-launch-decisions.md` remains the gate before the
first real listing is published.

## The decision

Iron Stake is a publisher. Sellers pay a flat annual fee to advertise a
lease-to-purchase home with all material terms stated. Buyers read the
listing and contact the seller directly. The two parties handle everything
after that: negotiation, the agreement, the money, the closing.

This is the same posture as Zillow FSBO, Furnished Finder and Craigslist
housing. It is the standard way to run a real estate listing site without a
brokerage licence, and the current Terms of Use already describe it
correctly (sections 1, 3, 5 and the "not a party" sections).

## The five lines

The model holds as long as every one of these holds. Crossing any one of
them changes what the business is.

1. **Flat fee, paid up front, never contingent on a deal.** The fee is for
   publication, not for a result. The day any fee depends on a signed
   option or a closing, the platform is being paid for a transaction and
   needs a licence in that state.
2. **No negotiation, no showings, no offers relayed.** Delivering a buyer
   enquiry to the seller's dashboard is publishing. Suggesting a counter,
   scheduling a visit, or helping the parties reach terms is brokerage.
3. **Never touch money between the parties.** No option fees, deposits,
   rent or rent credits through the platform. Stripe handles the listing
   fee only. Holding party funds adds escrow licensing and money
   transmission exposure on top of brokerage.
4. **No agreement preparation.** The agreement page says Iron Stake does
   not supply forms. Keep it that way, especially in North Carolina, where
   the State Bar pursued LegalZoom over document assembly and where
   lease-option contracts have their own statute (General Statutes
   Chapter 47G) with content, disclosure and recording requirements the
   parties must meet. Explaining the eight terms is education. Filling in
   a template is practice of law.
5. **Review for completeness, not for quality.** "States all eight terms"
   is a publishing standard, and Section 230 protects that kind of
   good-faith moderation. "Fair terms" or "a good deal" is an opinion about
   the transaction. Product change: replace "approved" with "published
   after review" in the seller dashboard, emails and public copy so the
   word cannot be read as an endorsement.

## The two things that are not pure publishing

### The verification badge

"Seller and title verified" is Iron Stake's own statement. Section 230
does not cover it, and North Carolina's unfair and deceptive trade
practices statute carries treble damages. It is still worth doing, because
it is the entire difference from the lead-generation sites. Requirements:

- A written review standard: who reviews, which sources, what is checked
  (recorded owner, liens, mortgage position, HOA), rejection criteria,
  evidence kept per listing, turnaround target. This is already an open
  item in the launch decisions doc.
- The same checks on every listing, every time. Verification is never a
  paid tier (the pricing methodology already says this).
- Badge copy that says exactly what was checked and the date, and never
  implies the deal, the price or the seller's conduct is safe.
- A re-check trigger when a listing is materially edited or renewed.

### The owner's real estate licence

The founder holds a real estate licence. Regulators look at who owns a
platform. Rules:

- Keep the platform entity, its marketing and its seller outreach entirely
  separate from the licence. Do not mention the licence in Iron Stake
  materials.
- If the founder ever acts as an agent for an Iron Stake user, disclose it
  in writing and run it through the brokerage.
- Do not use licensee-only tools (MLS data) to build Iron Stake prospect
  lists without checking the MLS terms of use; use public sources.

## Smaller items before the first real listing

- **Fair housing.** The Fair Housing Act applies to the platform's own copy
  and to the fields and filters it builds. Budget, structure and term
  filters are fine. Never add a field, prompt or filter that touches a
  protected class, keep the Equal Housing logo, and have a complaint route
  with a named owner. Seller-written text is largely protected by Section
  230 unless the platform induces it.
- **Listing types.** Publish lease options and rent-to-own (lease with
  option) only. Contracts for deed and installment land sales fall under
  NC Chapter 47H and seller-financing rules, and they pull the platform
  toward consumer credit law.
- **Outreach.** Cold text messages to sellers need prior consent under the
  Telephone Consumer Protection Act. Use email (with an opt-out and a
  postal address) and letters.
- **DMCA agent.** Register one with the Copyright Office before accepting
  seller photographs. Already an open item.
- **Referral rewards.** The $40 reward is a subscription bounty, not a
  brokerage referral fee. Issue 1099s at the reporting threshold, and tell
  licensed agents who refer sellers that they may need to disclose the
  payment to their own clients.
- **Marketing claims.** The CFPB and state attorneys general have pursued
  rent-to-own housing operators for misleading buyers. Iron Stake is not
  the seller, but its copy should never imply a likely ownership outcome.
  Keep the forfeiture explanation prominent, as the agreement page
  already does.
- **Billing.** Annual auto-renewal needs clear pre-purchase disclosure, a
  renewal reminder and online cancellation. The Terms cover most of this;
  confirm the Stripe flow does too.

## What counsel must put in writing, per state

1. That flat-fee advertising with no negotiation, no funds and no
   contingent payment is outside the brokerage definition in North
   Carolina and Georgia, and later Colorado.
2. That the verification badge wording and the review standard are
   defensible under each state's consumer protection law.
3. That the listing rules do not publish terms NC Chapter 47G forbids, and
   whether the platform should require sellers to acknowledge 47G
   recording and disclosure duties at submission.
4. Final sign-off on Terms, Privacy, auto-renewal language and the
   fair-housing moderation standard.
