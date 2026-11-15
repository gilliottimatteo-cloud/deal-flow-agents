---
name: fund-thesis
description: The single source of truth for the fund's facts. Holds the fund's identity, ticket sizes, hard filters, ideal company profile, the six scoring dimensions with their weights and thresholds, the return check, and the impact lens. Load this for any triage, screening, scoring, return or impact decision. If any other file disagrees with this one, THIS file wins.
---

# Fund thesis: single source of truth

Example Ventures is a fictional fund, written for this repository. Every number below is invented. To run the system for a real fund, replace the contents of this file and nothing else: every agent and skill points here for fund facts.

If any other document contradicts the facts below, these facts are authoritative.

## Identity

Example Ventures is an early-stage venture fund that invests in Latin American technology companies. It backs companies whose commercial growth widens economic access for small businesses and households that banks serve poorly.

A company must first stand as a venture investment on its own. Impact is assessed after the commercial case, as a condition of fit. It never makes up for a weak business.

## The fund

- Size: USD 40M. Status: investing.
- Stage: Seed to Series A.
- Geography: Latin America.
- Sectors: fintech, commerce enablement, logistics, work and income tools.
- First ticket: USD 300K to 1M. Standard first ticket: USD 500K.
- Follow-on reserve: 40% of the fund.
- Instruments: SAFEs, convertible notes, priced equity.
- Can lead rounds up to USD 2M. Above that, it co-invests.

## Hard filters (reject at triage if any fails)

1. **Stage.** The product is live and has paying customers. The round is not later than Series A.
2. **Geography.** The company's main market is in Latin America.
3. **Founders.** Every founder who holds more than 10% of the company works on it full time.
4. **Round.** A lead investor is named, or at least 50% of the round is committed. If neither holds, the round passes only when the fund itself could lead it.
5. **Access.** The core product is used by small businesses or households that banks serve poorly. A side project or a donation program does not count.

## Ideal company profile (triage signals, not filters)

- Stage: late Seed, with at least 12 months of revenue history.
- Founders: one founder who has sold to this customer before, and one who built the product. Earlier startup experience is a plus.
- Traction: revenue growing at least 8% month over month, or at least 2.5x year over year. Gross margin above 50%, or a clear path to it.
- Efficiency: customer acquisition cost paid back within 12 months. Net burn below 1.5x net new annual revenue.
- Exit: at least three named strategic buyers, and past acquisitions in the sector at known multiples.

## The six scoring dimensions

Each dimension is scored 1 to 5, then multiplied by its weight. The maximum total is 100 points.

| # | Dimension | Weight | Max |
|---|-----------|--------|-----|
| S1 | Team | x5 | 25 |
| S2 | Market | x4 | 20 |
| S3 | Product and defensibility | x3 | 15 |
| S4 | Traction and unit economics | x4 | 20 |
| S5 | Deal and return | x2 | 10 |
| S6 | Impact | x2 | 10 |

Thresholds:
- Pre-IC, advance to due diligence: 60 or more out of 100.
- Final scorecard, recommend to the investment committee: 70 or more out of 100.
- Reject: below 45 out of 100.
- S6 Impact is a gate. A score of 1 disqualifies the company whatever the total.
- At Pre-IC, a dimension that cannot be assessed scores 2 and is flagged as a data gap.

The score bands and the meaning of each score live in the `scoring` skill. The weights and thresholds live only here.

## Return check (always use these assumptions)

The return check answers one question: how much does revenue have to grow for this investment to return ten times the ticket?

- Entry ownership = ticket / post-money valuation (or the valuation cap of a SAFE).
- Dilution from later rounds: 40%.
- Target: the fund's stake is worth 10x the ticket at exit.
- Required exit value = (10 x ticket) / (entry ownership x 0.60).
- Required revenue at exit = required exit value / exit multiple. Take the exit multiple from the financial due diligence. If none has been researched yet, use 4x revenue and mark it as a placeholder.
- Required growth = required revenue at exit / current annualized revenue.

How to read the result:
- Up to 20x: comfortable. The round is priced for a normal outcome.
- 20x to 50x: stretch. It needs conviction on the team and the market.
- Above 50x: long shot. It needs an exceptional team, a very large market, or a lower price.

## Impact lens

The fund describes impact with the five dimensions of the Impact Management Project, a public standard:

- **What** outcome the product produces, and how much it matters to the people who get it.
- **Who** gets the outcome, and how underserved they were before.
- **How much**: how many people, how deep the change, and how long it lasts.
- **Contribution**: what would have happened without the company.
- **Risk**: what could make the impact smaller than expected.

Rules:
- Impact has to come from the core product. If the company could grow its revenue without growing its impact, it fails the Access filter.
- Impact KPIs come from the company's own operating data, are measurable today, and can be reported every quarter.
- Three to five impact KPIs per company. Never more than six.

## Voice

Write like an analyst talking to a colleague: short, specific, and backed by a number wherever one exists. Describe impact with counts from the company's data ("9,400 shops took a card payment for the first time"), not with adjectives. A gap in the information is stated as a gap.
