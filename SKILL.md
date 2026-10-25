---
name: wtbi
description: Will They Buy It (WTBI) — a deep conversion review of a website, landing page, store, listing, or product. Walks realistic buyer personas through the page, audits it against proven conversion lenses, maps every buyer objection, compares it with the alternatives buyers would choose instead, and returns a verdict plus prioritized, ready-to-implement changes that would get more people to buy. Use this whenever someone shares a URL, screenshots, or a description of their product, store, or landing page and asks whether it will sell, why it isn't converting, how to get more sales or signups, what's turning customers off, or for a conversion/sales/landing-page review — even if they never say "WTBI" or "personas".
---

# WTBI — Will They Buy It

The goal is to answer one question honestly: **if real target customers landed on this, would they buy — and if not, what exactly would change their mind?** The owner is too close to their own product to see it the way a stranger does. Your job is to be that stranger several times over, then back those reactions up with a systematic audit, so the recommendations rest on more than one point of view.

The review has two halves that check each other:
- **Personas** catch situational and emotional problems: confusion, doubt, "this isn't for me," "I'll just use the free one."
- **Lenses** catch structural problems a single visitor might not articulate: missing risk reversal, weak proof, a call to action that asks for too much, too soon.

Where both halves point at the same problem, you can be confident it matters.

## Depth and persona count

- **Default: the full review** described below.
- **Quick read:** if the user asks for something quick, short, or high-level, skip the scorecard and objection map and deliver only the verdict, persona reactions, and top 3 changes.
- **Persona count:** if the user names a number, use exactly that many. Otherwise use 4. With more than 6, shorten each persona's write-up so the review stays readable.

## 1. Gather the material

Judge the path a buyer actually takes, not just the homepage.

- **A URL:** fetch it with WebFetch, then fetch the pages a buyer would click on the way to buying: pricing, product or features, reviews or case studies, about, FAQ, and the signup or checkout page. Three to six pages is usually right. Look at signup or checkout pages only; never submit forms, create accounts, or start purchases. WebFetch returns text, so read the document order as a proxy for what appears first on screen, and say so when a finding depends on visuals you can't see. If a page won't load or comes back mostly empty (common with JavaScript-heavy sites), say so and ask for screenshots rather than guessing.
- **Screenshots:** read every detail, including small print, buttons, prices, badges, and what the eye lands on first. Visual hierarchy is a real finding here.
- **A written description:** work with what's given, and be clear you're judging the offer and the messaging, not a page you can see.

Use whatever context the user gives (who the customer is, where traffic comes from, current conversion rate, price, what they've already tried). Don't hold up the review to ask for it; state your assumptions in one line each so they can correct them.

Only judge what's actually there. Don't invent features, prices, reviews, or numbers. Anything a buyer needs that's missing (price, shipping, return policy, what's included, who's behind it) is itself a finding.

## 2. Classify the offer

The same page element can be fine for one kind of business and fatal for another, so classify before judging:

- **Business type:** SaaS or app, e-commerce product, marketplace listing, service or local business, B2B or high-ticket, course or info product, or something else. Read the matching section of `references/business-types.md` for what buyers in that category decide on and what usually kills sales.
- **Conversion goal:** what action the page asks for (buy, start a trial, sign up free, book a call, request a quote, download). Judge the page against that action. A free signup and a $2,000 purchase need very different amounts of convincing.
- **Price and decision weight:** impulse (under about $50), considered (needs comparison and some proof), or high-ticket (needs strong proof, risk reversal, and often a human).
- **User vs. payer:** if they differ (teen and parent, employee and manager, gift recipient and giver), both need convincing, and the payer is often the one the page forgets.

## 3. Map the alternatives

Every purchase is a choice against something: a direct competitor, a free tool, a cheaper substitute, doing it yourself, or doing nothing. A clear, polished page can still lose because it never answers "why this instead of that?"

- Start from your own knowledge. For niche, local, or fast-changing categories, or when you're unsure who the main players are, run one or two quick web searches (e.g., "[category] alternatives", "best [category] [year]").
- Identify the 2–4 alternatives a buyer is most likely to weigh. For each: what it costs, its main pull (free, official, cheaper, better known, already in use), and whether the page gives a reason to choose this product over it.
- If one alternative is clearly the main threat and has a public page, fetch it and compare the essentials: headline promise, price, proof, and offer. Seeing what the buyer sees in the other tab often reveals the real gap.
- Don't forget **doing nothing**. For many products the strongest competitor is "I'll deal with it later," which only urgency and a sharp sense of the problem can beat.

## 4. Build the personas

Create personas who could realistically land on this page, each specific enough to have real reasons. Give each one:

- **Name and situation:** one line, concrete ("Maya, junior, scored 1280, wants 1400 for her reach schools, test in 6 weeks").
- **How they arrived:** search, ad, social post, referral, marketplace browse. This sets what they expect to see first.
- **Awareness level:** how much they already know, which decides what the page must do for them:
  - *Problem-aware:* knows the pain, not the solutions. Needs the problem named and a clear promise.
  - *Solution-aware:* knows solutions exist and is comparing. Needs differentiation.
  - *Product-aware:* knows this product and is deciding. Needs proof, price clarity, and reassurance.
  - *Unaware:* arrived cold from an ad. Needs the hook and the problem made vivid in seconds.
- **The job:** what they're really trying to get done, in their words.
- **Budget and who pays.**
- **Alternatives they're weighing**, drawn from step 3. At least one persona should be seriously considering one.
- **Decision criteria:** the two or three things they must see before acting.

Choose the mix that fits the product. Usually include the ideal buyer (if even they don't buy, that's the biggest problem), a skeptic or comparison shopper, a price-sensitive buyer, and a cold visitor. Add the payer as their own persona when user and payer differ.

## 5. Walk each persona through it

Take each persona through the page in the order they'd experience it:

1. **First 5 seconds:** do they understand what this is, who it's for, and why they should care?
2. **The scroll:** what they look for next (proof, price, details, comparisons) and whether they find it.
3. **The sticking point:** the exact element where they hesitate. Quote it or name what's missing.
4. **The call to action:** are they ready to take the action asked of them, at that point on the page?
5. **Decision:** **Buys**, **Maybe** (one specific thing would tip them), or **Doesn't buy**, plus the deal-breaker and roughly where they'd leave the page.

Write one or two short lines of inner monologue per persona, in their voice ("Okay, but Khan Academy is free... what does this do that it doesn't?"). It makes problems vivid for the owner in a way analysis alone doesn't.

Be honest. The value of this skill is an unflattering outside view, and a review where everyone buys is useless unless the page truly earns it. Equally, don't manufacture problems; when something works, say so, so the owner doesn't break it.

## 6. Run the conversion lenses

Now audit the page systematically. Read `references/lenses.md` and rate each lens **Strong**, **Okay**, **Weak**, or **Missing**, with one line of evidence pointing at the actual page. The lenses are: clarity, relevance and message match, value and differentiation, proof, trust and credibility, risk reversal, pricing and value framing, offer and call to action, friction and flow, objection handling, urgency and motivation, and visual hierarchy and readability.

Evidence matters more than the rating. "Weak: the only proof is 'Example' screenshots; no reviews, numbers, or named customers" helps; "Weak: needs more proof" doesn't. If you can't judge a lens from what you have (e.g., visual hierarchy from text alone), mark it "Can't tell" rather than guessing.

## 7. Build the objection map

Gather every objection raised by the personas and the lenses. For each, record:

- **The objection**, in the buyer's words.
- **Who has it.**
- **How much it blocks:** Deal-breaker, Slows them down, or Minor.
- **Does the page answer it:** Yes, Partly, or No.
- **Where the answer belongs:** the spot on the page where the buyer has that doubt (near the price, by the button, in the hero, in the FAQ).

Unanswered deal-breakers are almost always the top changes. Answers placed far from where the doubt arises (a refund policy buried in the footer, say) count as "Partly."

## 8. Prioritize the changes

Turn the findings into changes and rank them by:

- **Impact:** how many personas it moves, and how many deal-breakers it resolves.
- **Confidence:** whether both personas and lenses point to it, or only one.
- **Effort:** Quick fix (under an hour), Moderate (about a day), or Bigger project.

Rank by impact first. Present **3–5 top changes**, up to 7 only if that many truly matter; fewer, sharper changes get implemented. Put small, worthwhile fixes that didn't make the top list under "Quick wins."

Each top change should be detailed enough to hand to a designer or copywriter without another conversation. "Improve trust" is not a change; "Add 3 customer reviews with photos directly under the Add to Cart button" is. For each, cover:

- **The problem now:** what's on the page today (quote it, or name what's missing) and why it stops buyers.
- **Who it wins over:** which personas it moves, and how (Doesn't buy → Maybe, Maybe → Buys), and which objections it answers.
- **How to do it:** the specific steps, including where on the page each piece goes.
- **Example:** ready-to-use copy, a rewritten section, or a short description of the new element. Write real wording wherever wording is the fix. When the example needs facts you don't have (stats, reviews, guarantees), use clearly marked placeholders like [real number] and say they must be replaced with true figures; never present invented proof as real.
- **How to measure it:** the number to watch (signup rate, trial-to-paid, add-to-cart, pricing-page exits) or a simple A/B test, so the owner knows whether it worked.
- **Effort.**

## 9. Rewrite the first screen

The first screen does most of the selling, so always include a rewrite of it: headline, subheadline, call-to-action button, and one supporting line (proof or risk reversal). Offer two headline options with different angles (for example, outcome-led and pain-led), and say briefly which persona each speaks to. If the current first screen is already strong, say so and suggest only targeted tweaks.

## Output format

Deliver the review in the chat, with this structure. Use tables where shown; they keep a deep review scannable.

```
## Verdict
[Two or three sentences: would most target customers take the action as it stands, and what's the single biggest reason they don't?]

**Confidence:** [High / Medium / Low] — [one line on what this rests on, e.g. "based on 5 pages; couldn't see the mobile layout or checkout"]
*Assumptions: [target customer] · [conversion goal] · [business type and price level]*

## Scorecard
| Lens | Rating | Evidence |
|---|---|---|
| Clarity | Strong | ... |
| ... | | |

## What buyers would use instead
| Alternative | Cost | Its pull | Does the page beat it? |
|---|---|---|---|

## How each buyer reacted
**[Name], [one-line situation]** · arrived from [source] · [awareness level]
> "[inner monologue line]"
**Decision:** [Buys / Maybe / Doesn't buy] — [deal-breaker, and where they'd leave]

[repeat for each persona]

## Objection map
| Objection | Who | Blocks | Answered? | Where the answer belongs |
|---|---|---|---|---|

## Top changes to make
### 1. [The change, as an action]
**The problem now:** ...
**Who it wins over:** ...
**How to do it:**
- ...
**Example:** ...
**How to measure it:** ...
**Effort:** ...

### 2. ...

## Quick wins
- [small fix, where, one line each; 3–5 items]

## Rewritten first screen
**Option A ([angle], for [persona]):**
Headline: ...
Subheadline: ...
Button: ...
Supporting line: ...

**Option B ([angle], for [persona]):** ...

## What's already working
- [1–3 things to keep, so they don't get removed by accident]

*Not evaluated: [pages or aspects you couldn't see, if they matter]*
```

A full review is long by nature, so make every line earn its place: evidence over adjectives, one idea per bullet, no repeating the same point across sections (the objection map can point to a change number instead of re-explaining it). The verdict and persona reactions should still be readable in under two minutes, and each top change should stand on its own so the owner can work through them in order, starting with #1.

If the review is very long and the user may want to share it with a team or keep it, offer in one line at the end to turn it into a document.
