---
name: scoring
description: The fund's scoring method for the six dimensions S1 to S6, applied at two gates: the Pre-IC scorecard (scored conservatively on limited data) and the Final scorecard (after due diligence, with a Pre-IC to Final evolution table). Holds what each dimension measures, its questions, evidence sources and score bands. Load this whenever scoring or re-scoring a company.
---

# Scoring method

This skill says how to score. The numbers that turn scores into a decision (weights, maximum total, thresholds, the impact gate value, the Pre-IC default score) live only in the `fund-thesis` skill. Read them there every time.

## Two modes

**Pre-IC scorecard.** Built from the deck, the first-call notes, the pre-screen, and the market and competition analyses. Scores are indicative. Every dimension names its data gap. The header Status line reads `Pre-IC, limited data`.

**Final scorecard.** Built after due diligence: management DD, financial DD, the DD-refined market and competition analyses, and every DD call note. Every score cites specific evidence. The Status line reads `Final, after due diligence`.

**Call notes sharpen, they never add.** DD call notes move the score of an existing dimension. They never create a new dimension. A CFO who cannot explain churn lowers S4; it does not open a "founder candor" category. When a call contradicts the deck, flag the discrepancy and say which source you weight more and why.

## Scoring principles

**Do not average, triangulate.** Read the pattern across dimensions, not only the total. A strong total resting on a weak S1 is a different company from the same total with balanced scores.

**Gaps cost points at Pre-IC.** A dimension that cannot be assessed takes the Pre-IC default score set in fund-thesis, and the Gap line names the document or call that would change it. Never score optimistically on missing data.

**Impact is a gate, not a bonus.** Apply the S6 gate defined in fund-thesis in both modes, whatever the total. A high S6 never rescues weak commercial dimensions; both must hold.

**Score against the fund's own profile.** Where a band speaks of "healthy" growth, margin or efficiency, measure it against the ideal company profile in fund-thesis.

*Illustration (invented): S4 scores 5, but S1 scores 2 because the founders could not explain their own cohorts. The traction is then less trustworthy than its score, so the recommendation leads with that tension, not the total.*

## The six dimensions

Ratings: 5 Exceptional, 4 Strong, 3 Moderate, 1 to 2 Weak.

### S1 Team

**Measures:** whether these founders, more than any other team with the same idea, can build this company.
**Questions:** Why are they uniquely placed for this customer? Who sells, and who builds? Which critical roles are open, and is there a hire plan? Is the cap table healthy?
**Evidence:** Pre-IC from the deck and first-call notes; Final from the management DD and team and reference calls.

| Score | Meaning |
|---|---|
| 5 | Deep, hard-to-copy insight into the customer; complementary founders who have shipped and sold before; key roles filled or being hired |
| 4 | Clear founder-market fit; one or two gaps with a credible plan |
| 3 | Relevant but generic background; important roles open without a plan |
| 2 | Weak fit to the problem; signs of friction or a lopsided cap table |
| 1 | No fit, critical roles empty, or a serious integrity or alignment concern |

### S2 Market

**Measures:** whether the reachable market can support a venture-scale outcome within the fund's horizon.
**Questions:** Is the sizing built bottom-up, and does a second method agree? How fast is the segment growing in the company's countries? What drives adoption now?
**Evidence:** the market analysis (the `-dd-refined` version at Final), plus expert calls.

| Score | Meaning |
|---|---|
| 5 | Large, fast-growing segment sized two ways that agree; a clear reason adoption happens now |
| 4 | Credible sizing, large enough; tailwinds named |
| 3 | Top-down sizing only; growth asserted rather than sourced |
| 2 | Market likely too small or badly overstated |
| 1 | No credible market for a venture outcome |

### S3 Product and defensibility

**Measures:** whether customers need the product and whether the lead can be kept.
**Questions:** What does it do far better than the status quo? Does retention prove customers rely on it? What compounds with scale (data, network, switching costs, license, distribution)? How long would a funded competitor need to catch up?
**Evidence:** the competition analysis (the `-dd-refined` version at Final), product and technology material, client and expert calls.

| Score | Meaning |
|---|---|
| 5 | A must-have product with an advantage that widens as it grows; the threat map is complete |
| 4 | Clear differentiation and one real moat showing early proof |
| 3 | Ahead on execution speed only; moats claimed, not shown |
| 2 | Easy to copy; incumbents could take the segment |
| 1 | No clear need and no defensible position |

### S4 Traction and unit economics

**Measures:** whether the numbers tell a true, durable story.
**Questions:** How steady is growth over twelve months? Do cohorts retain and expand? Do payback and margin improve with scale? Is burn efficient? Are projections earned by history?
**Evidence:** Pre-IC from the deck and calls; Final from the financial DD.

| Score | Meaning |
|---|---|
| 5 | Consistent strong growth, retaining cohorts, improving unit economics, efficient burn |
| 4 | Solid growth with some volatility; economics heading the right way |
| 3 | Early or uneven traction; economics partly known or flat |
| 2 | Stalled growth or worsening economics |
| 1 | No meaningful traction, or numbers that do not hold together |

### S5 Deal and return

**Measures:** whether this round, at this price, can return what the fund needs.
**Questions:** Does the round fit the fund's ticket and role? Where does the return check land, and is its exit multiple researched? Who else is in, and how committed is the round?
**Evidence:** the return check (from the financial DD at Final; at Pre-IC, computed per fund-thesis and marked `PLACEHOLDER` where the multiple is not researched) and the round terms.

| Score | Meaning |
|---|---|
| 5 | Fits the fund; return check in the comfortable band; strong, committed co-investors |
| 4 | Fits; return check a stretch but defensible |
| 3 | Price ahead of traction; weak or unknown co-investors |
| 2 | Return check a long shot; round thinly committed |
| 1 | Outside the fund's terms or no plausible path to the return |

### S6 Impact

**Measures:** whether impact grows on the same engine as revenue, read through the impact lens in fund-thesis.
**Questions:** Does each unit of growth produce a unit of impact? Who benefits, and how underserved were they? Which KPIs come from operating data today? What would happen without the company?
**Evidence:** the impact lens in fund-thesis, the impact template, and client calls.

| Score | Meaning |
|---|---|
| 5 | Impact cannot be separated from revenue; KPIs measured from operations today |
| 4 | Strong link; most KPIs in place |
| 3 | Impact follows growth loosely; KPIs partial |
| 2 | Impact is a side effect for a mostly mainstream customer |
| 1 | Impact is positioning, not mechanism |

## Required output structure

Follow `house-style` for format. Save and name the file as the `scorecard` agent says.

### Summary table

| # | Dimension | Score /5 | Weight | Weighted | Rating |
|---|---|---|---|---|---|
| S1 | Team | | | | |
| S2 | Market | | | | |
| S3 | Product and defensibility | | | | |
| S4 | Traction and unit economics | | | | |
| S5 | Deal and return | | | | |
| S6 | Impact | | | | |
| **Total** | | | | **/[max]** | |

Fill the Weight column and the maximum from fund-thesis.

### Per-dimension block (one per dimension)

- **Score:** [X]/5
- **Rating:** EXCEPTIONAL / STRONG / MODERATE / WEAK
- **Key finding:** one or two sentences.
- **Evidence:** the specific source: deck page, call note, DD document.
- **Gap:** at Pre-IC, the document or call that would change the score; at Final, "none" when the evidence is complete.

### Recommendation block

**Pre-IC:** ADVANCE / HOLD / REJECT, read against the thresholds in fund-thesis. Give the top 3 reasons, the top 3 risks, and every dimension scored at the Pre-IC default with what would close the gap.

**Final:** INVEST / CONDITIONAL / DO NOT INVEST, with conditions stated if CONDITIONAL. Give the top 3 reasons, the top 3 risks with mitigations, and the return summary: the return check result and band, and whether the exit multiple is researched or `PLACEHOLDER`.

### Evolution table (Final only)

| # | Dimension | Pre-IC score | Final score | What changed |
|---|---|---|---|---|
| S1 | Team | | | |
| S2 | Market | | | |
| S3 | Product and defensibility | | | |
| S4 | Traction and unit economics | | | |
| S5 | Deal and return | | | |
| S6 | Impact | | | |
