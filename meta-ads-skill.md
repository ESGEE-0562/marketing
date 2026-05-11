---
name: eltee-meta-ads
description: Eltee Sydney Meta Ads strategy, account structure, benchmarks, creative management, and tracking system. Use when planning, reviewing, optimising, or briefing Facebook/Instagram ad campaigns for Eltee Sydney across both the Eltee (AU/NZ) and J&J (US/Canada) accounts.
triggers:
  - /meta-ads
  - /ads
  - /facebook-ads
---

# Eltee Sydney — Meta Ads Strategy & Operations

Use this skill when planning, reviewing, optimising, or briefing Meta ad campaigns for Eltee Sydney. Covers both accounts, all funnel stages, creative management, and tracking. Invoke with `/meta-ads`.

---

## Account Overview

Eltee Sydney runs two Meta Ads accounts from a single Ads Manager:

| Account | Markets | Primary Currency |
|---|---|---|
| **Eltee** | Australia, New Zealand, UK | AUD |
| **J&J** | United States, Canada | USD |

**Team roles:**
- **Sarah** (founder): brand, creative direction, copy decisions, strategy
- **JJ**: Meta Ads Manager setup, execution, day-to-day optimisation, reporting
- **Holly**: creative design and asset production

---

## Campaign Structure (Consolidated, April 2026+)

Both accounts use a **single campaign, single broad ad set** structure. This replaces the previous multi-ad-set funnel (TOF / TOM / BOF / ASC T2).

**Why:** Meta's Andromeda system (globally rolled out October 2025) is creative-first, not audience-first. One broad ad set with 20-30+ creatives outperforms fragmented ad sets because it gives the algorithm concentrated conversion data and lets creative do the targeting.

**J&J structure:**
- Campaign: J&J | $900
- Ad set: TOM (J&J) | BROAD (Advantage+ on, broad audience, age 18+, purchasers excluded)
- Budget: $900/day
- Creatives: 30-40 ads spanning cold, warm, and niche audiences

**Eltee structure:**
- Campaign: ELTEE | $820
- Ad set: TOM (AUS/NZ) | BROAD (Advantage+ on, broad audience, purchasers excluded)
- Budget: $780-820/day
- Creatives: 20-30 ads spanning cold, warm, and niche audiences

**Settings (both accounts):**
- Advantage+ ON
- No interest targeting, no lookalikes, no demographic restrictions beyond minimum age
- Purchasers excluded (Klaviyo All Purchasers 180 days + Website Purchase 180 days)
- Placements: Advantage+ (let Meta decide)
- Languages: All

**What NOT to do:**
- Do not create new ad sets within the campaign
- Do not add interest targeting or lookalikes
- Do not split test by duplicating the ad set
- All testing happens within the single ad set via creative variation

---

## Audience Segment Monitoring

With one broad ad set, funnel visibility comes from Meta's audience segment breakdown (available in Ads Manager under Breakdown > Audience Segment). Three segments:

| Segment | What It Is | Healthy Spend Share | ROAS Floor | ROAS Target |
|---|---|---|---|---|
| **New audience** | Cold traffic (never interacted) | 55-70% | 1.2x | 1.5x+ |
| **Engaged audience** | Warm traffic (visited site, engaged with ads/page) | 20-30% | 2.5x | 3.5x+ |
| **Existing customers** | Past purchasers | 5-15% | 3x | 5x+ |

**Flags:**
- Existing customers over 20% of spend: purchaser exclusion lists may need updating, or creative library needs more cold-audience hooks
- Engaged audience frequency over 5: warm creative is fatiguing
- New audience frequency over 2: creative library is too small

---

## Performance Benchmarks

### Overall Blended (Single Ad Set)

| Metric | Floor | Target |
|---|---|---|
| Overall ROAS | 2x | 2.5-3x |
| Overall frequency | Under 3 | Under 2.5 |
| CTR (link click) | 0.8% | 1.5%+ |
| CPC | Under $2.50 | Under $1.50 |
| CPM | Under $25 | Under $15 |
| Hook rate (video) | 15% | 25%+ |

### Frequency Limits by Audience Segment

| Segment | Healthy | Refresh Trigger | Action Needed |
|---|---|---|---|
| New audience | Under 1.5 | 2 | Over 2.5 |
| Engaged audience | Under 4 | 5 | Over 6 |
| Existing customers | Under 3 | 4 | Over 5 |

---

## Creative Management

### Creative Library

All new and used creative assets are stored in the shared Google Drive folder:
**[Creative Library](https://drive.google.com/drive/folders/1ylYvtuf7byMF8eSkj-XSIdQRerFOzqIh?usp=sharing)**

Check here before briefing new creative. Existing assets may be reusable or adaptable. When new creative is produced, add it to this folder.

### Creative-as-Targeting Principle

In a broad Advantage+ structure, creative IS the targeting. Meta's algorithm matches specific creative to specific users based on behavioural signals. Include a range of creative types:

- **Cold-audience hooks:** stat-led ("67% of girls skip swimming because of their period"), problem-led ("She missed 3 swim sessions last term"), product-first ("Period underwear that goes under her swimsuit. Yes, in the water.")
- **Warm-audience content:** product demos, comparison carousels, feature walkthroughs, educational checklists
- **Hot-audience content:** testimonials, social proof, urgency, "customers also bought" angles
- **Niche creative:** specific sports (sailing, disabled athletes, netball), specific audiences (dads). These find their audience through the algorithm rather than manual targeting.

### Creative Volume Rules

- Minimum 15 active ads in the ad set at all times. Target 20-30.
- Minimum 5 untested or under-tested ads available at all times.
- Load new creative in batches, not one at a time. Dripping in individual ads can nudge the ad set back into learning.
- Rotate fresh creative every 2-3 weeks, or sooner if frequency triggers are hit.

### Creative Qualification (90-Day / 4x Filter)

When evaluating whether a creative earns its place in the ad set:

- **4x ROAS over 90 days with 5,000+ impressions** = earned its place. Keep it.
- **Under 14 days old with under 5,000 impressions** = give it more time regardless of ROAS. It hasn't had a fair shot.
- **Below 4x ROAS with 5,000+ impressions over 90 days** = retire it or move to the Retest Queue.
- **Below 1x ROAS with $200+ spend over 14 days** = pause. It's had enough data.

### Creative Briefing Template

When briefing new creative, use this format:

| Field | Detail |
|---|---|
| Format | Video / Static / Carousel / UGC |
| Product focus | Which product or range? |
| Audience | Mums / Girls / Mixed |
| Hook | What is the opening line or visual hook? |
| Key message | One thing this ad should communicate |
| CTA | Shop now / Learn more / specific landing page |
| Due date | When does this need to be live? |
| Reference | Link to inspiration or past ads that worked |

### Meta Ads Headline Specs

- Headline: 25-40 characters. Front-load the most important words in the first 27 characters (truncation point on most placements).
- Primary text: 125 characters display without "See more." Can write longer but most won't expand.
- Link description: 27-30 characters max.

---

## Budget Rules

- Never increase a working ad set by more than 20% at a time
- Wait 3-4 days between increases
- If reducing, reduce by no more than 20% at a time
- If ROAS drops below 2x for 3+ consecutive days after learning phase, hold budget and flag
- Scaling ladder example: $600 > $720 > $860 > $900 (20% steps, 3-4 days each)

---

## Refresh and Kill Triggers

**Decision tree when ROAS drops below floor:**

1. Has it been below floor for 3+ consecutive days? (5+ days if ad set spends under $100/day)
2. Check frequency: is it climbing alongside the ROAS drop?
3. **YES (frequency rising + ROAS dropping) = creative fatigue.** Action: pause tired ads, load fresh creative.
4. **NO (frequency stable but ROAS dropping) = audience or external issue.** Action: check for seasonal dip, site issues, or Meta algorithm shift. Do not panic-swap creative.
5. If ROAS stays below floor for 7+ days regardless of creative refresh, escalate to Sarah.

---

## Tools and Integrations

- **Meta Ads Manager:** primary platform for both Eltee and J&J accounts
- **Motion Creative Analytics:** connected via Claude MCP integration. Use Motion to pull creative performance insights, demographic breakdowns, creative summaries, and competitor analysis directly within Claude. Call `get_auth_context` first, then use tools like `get_creative_insights`, `get_creative_summary`, `get_demographic_breakdown`, and `get_inspo_creatives` for competitor research.
- **Klaviyo:** email marketing platform. Purchaser exclusion lists are synced from Klaviyo to Meta (Klaviyo All Purchasers 180 days).
- **Shopify:** ecommerce platform. Connected via Claude MCP for product, order, and analytics queries.
- **Creative Library (Google Drive):** [Creative Library](https://drive.google.com/drive/folders/1ylYvtuf7byMF8eSkj-XSIdQRerFOzqIh?usp=sharing)

---

## Tracking System

The ad tracker spreadsheet has these tabs:

| Tab | Purpose | When to Update |
|---|---|---|
| **Benchmarks** | Reference card for all performance thresholds | Read-only. Check before making decisions. |
| **Weekly Performance** | Numbers snapshot from Ads Manager | Every Monday. One row per campaign + audience segment breakdown. |
| **Ad Creative Log** | Master list of every creative that exists | When launching, pausing, or retiring any ad. |
| **Creative Lifecycle** | Full history of every creative's journey | Every time a creative moves, gets paused, rested, retested, or modified. One row per event. |
| **Retest Queue** | Second chances for unlucky creative | When pausing something that failed for reasons other than poor performance. |
| **Creative Pipeline** | What's in production | When briefing or tracking new creative production. |
| **Monthly Summary** | Rolled-up monthly view | End of each month. |

### Creative ID Convention

- Eltee creative: EL-001, EL-002, EL-003, etc.
- J&J creative: JJ-001, JJ-002, JJ-003, etc.
- The ID follows the creative forever, across all tabs, regardless of which ad set it runs in.

### Creative Lifecycle Event Types

Launched, Promoted (up funnel), Demoted (down funnel), Paused (fatigue), Paused (underperform), Paused (outcompeted), Rested, Retested, Modified, Killed, Moved (same stage)

### Performance at Move

When logging a lifecycle event, record the 7-day ROAS, purchases, frequency, and spend at the time of the move. For ad sets spending under $50/day, note both 7-day and 30-day in the Notes column for context.

### Retest Queue Criteria

**Add to Retest Queue if:**
- Outcompeted by a stronger ad in the same ad set
- Launched during a budget cut or ad set pause (insufficient delivery)
- Ran during a seasonal dip or unusual period
- Had fewer than 1,000 impressions before being paused
- Worked in one market, worth testing in the other

**Do NOT add if:**
- Had plenty of impressions and genuinely didn't convert
- Killed for brand or policy reasons
- Outdated (old product shots, discontinued offers, irrelevant seasonal content)

### Modification Log (Within Lifecycle Tab)

When modifying an ad, use the test columns in the Creative Lifecycle tab:
- **Test Variable:** Headline, Hook, Body copy, CTA, Image/thumbnail, Video edit, Aspect ratio, Landing page
- **Test Detail:** What changed from/to, hypothesis, result after 7 days
- **Test Verdict:** Winner, Loser, No difference, Inconclusive
- Rule: test ONE variable at a time. Changing headline AND image simultaneously teaches nothing.

---

## Weekly Workflow

### Monday: Review and Report

1. Pull previous week's numbers into the Weekly Performance tab
2. Log one row per campaign + three rows for audience segment breakdown (New, Engaged, Existing)
3. Check overall ROAS against the 2x floor
4. Check segment spend split (New audience should be 55-70%)
5. Check frequency by segment against limits
6. Send summary to Sarah: overall ROAS, segment split, top 3 performing creatives, bottom 3, anything that needs a decision

### Wednesday: Optimise

1. Review individual ad performance. Pause any ad with $200+ spend over 14 days and ROAS below 1x
2. Do NOT pause ads under 14 days old or under 5,000 impressions
3. Log any modifications in the Creative Lifecycle tab before making them
4. Check if a budget step-up is due

### Friday: Creative Pipeline

1. Check: are there at least 5 untested/under-tested ads in the ad set?
2. Check the Retest Queue before briefing new creative (retesting is faster and cheaper)
3. Brief new creative if needed using the template above
4. Flag to Sarah if the pipeline is empty

### Monthly: Full Review

1. Fill in the Monthly Summary tab
2. Review 90-day ROAS of every ad. Retire anything below 2x with 5,000+ impressions over 90 days
3. Clean out the Retest Queue (mark anything no longer relevant)
4. Review budget for the month ahead

---

## Escalation Rules

Flag to Sarah if:
- Overall ROAS below 2x for 5+ consecutive days after learning exits
- Ad set stuck in Learning Limited after 7 days
- Existing customers segment taking more than 20% of spend
- Creative pipeline empty (fewer than 5 fresh/untested ads available)
- Any ad receives negative comments touching on brand sensitivity
- Meta flags or rejects an ad
- Total spend pacing significantly over or under monthly budget

---

## UnderAustin Campaign Notes

UnderAustin is a standalone product launch running within the existing consolidated ad set, not as a separate campaign. Key guardrails:

- **Co-design accuracy:** Kiera Austin co-designed UnderAustin but does not "own" or solely represent it. She cannot wear club or national uniform in promotional material.
- **Cold audience copy:** Headlines must not assume familiarity with Kiera Austin or netball. "Not a sponsor" framing is incorrect. Correct framing: "co-designed."
- **Quote accuracy:** Never infer or add specificity to real quotes. If a detail isn't stated, it doesn't exist in the copy.
- **Product terminology:** "Free-moving protection panel" not "boyleg cut." Terminology must match Eltee's own framing exactly.
- **Preferred headline for product-first (Kiera-agnostic) creative:** "Built with her. For them."
- **Netball season timing:** SSN runs March through early July. Community/grassroots winter netball typically April through September.

---

## Key Learnings from Account Audit (March 2026)

These insights inform ongoing strategy:

- **J&J outperforms Eltee on cost per purchase** ($37 vs $80). The US/Canada market responds better to current creative.
- **V COMPARISON format is a consistent winner** across both accounts and funnel stages (3.04x in Eltee BOF, 4.68x in J&J TOM). Replicate this format for new products.
- **Checklist/educational format works for mum-facing TOM** (AUS CHECKLIST at 2.07x, PACKAGING UNDERDANCE at 1.55x).
- **UGC and real-life content outperforms polished studio content** for this audience.
- **Frequency is the lead indicator of fatigue.** ROAS drops follow frequency spikes by 3-5 days. Watch frequency first.
- **The same creative can perform very differently by market.** V INDALI UNDERDANCE: 1.85x in J&J, 0.66x in Eltee. Always test per-market.
- **Niche creative (dad ad, sailing ad, disabled athletes) should be loaded into the broad ad set**, not given their own targeting. Meta's algorithm finds the right audience for niche creative more efficiently than manual interest targeting.
- **BOF as a separate ad set is not viable at small budgets.** At $40-57/day, BOF ad sets cannot generate enough conversions to exit learning phase. The consolidated structure handles retargeting through the Engaged audience segment.

---

## Historical Benchmark Reference (Pre-Consolidation)

These were the funnel-stage benchmarks used when running separate TOF/TOM/BOF ad sets. Retained for reference when reviewing historical data:

| Stage | ROAS Floor | ROAS Target | Frequency Healthy | Frequency Limit |
|---|---|---|---|---|
| TOF | 1.5x | 1.8x | 1-2 | 2.5 |
| TOM | 2.5x | 3.5x | 2-3 | 3.5 |
| BOF | 3x | 5x+ | 2-3.5 | 4 |

---

## Self-Check Before Making Changes

- Is the ad set in the learning phase? If yes, do not make changes.
- Has the underperformance lasted 3+ days (5+ for low-spend), or is it a single bad day?
- Is this a frequency problem (creative fatigue) or a non-frequency problem (external factor)?
- Am I changing one variable at a time, or multiple things at once?
- Have I logged this change in the tracker before making it?
- Does the creative pipeline have at least 5 fresh assets ready?
