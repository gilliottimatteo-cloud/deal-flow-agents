---
name: ic-memo
description: The fund's method for producing the IC memo, a strategic slide-by-slide Markdown deck (about 26 to 28 slides, filled from a copy of template.md, including a Value Proposition and Use Cases slide) PLUS a paired annex (filled from a copy of annex-template.md) that deep-dives product, exit, comparables and valuation. The deck shows only the findings that bear on the decision, and the deal's DD guide shapes its emphasis. Load this any time someone asks for an IC memo, an investment committee memo or an IC deck.
---

# IC memo method (paired deck and annex)

The IC memo sits at the top of all deliverables: the investment committee (IC) reads it to make its decision. OUTPUT TIER: IC-facing, highest craft. It consists of TWO files that are paired and linked:
- THE DECK (about 26 to 28 slides): just the material presented and discussed in the meeting, namely the strategic synthesis and the findings that bear on the decision.
- THE ANNEX: a focused deep-dive on product, exit, comparables and valuation, for the committee to read on their own.

Never bury call transcripts or appendix material in the deck. The deck is the tip, the annex and the DD documents are the iceberg.

## Build by FILLING A COPY of the templates

- Copy `template.md` (this folder) to `deals/[Company]/6-ic-memo/YYYY-MM-DD-[company]-ic-memo.md` and `annex-template.md` to `deals/[Company]/6-ic-memo/YYYY-MM-DD-[company]-ic-memo-annex.md`. File naming per `house-style`.
- Fill the copies. Change only the content, never the structure: keep every heading, every slide, the slide order and the table columns. Replace each bracketed guidance slot with this deal's content and delete the guidance text.
- Allowed structural changes, and only these: the debt branch (below); extra slides added for this deal's DD doubts (see "Tailor the emphasis"); removing the conditional product and technology slide when DD did not cover it; deleting the annex's "Debt terms" section (and the "Sources" section when there are no web sources) when it does not apply. An added slide is inserted where the skill says and the slides after it are renumbered.
- Format follows `house-style` (header, bold lead-ins, tables, status labels, sources, footer).

## The deck spine (default order)

The template holds the spine. Keep its logic: problem, then why this company wins, then proof it works, then the team, then the money (forecast, valuation, exit, fund fit), then impact, then risks.

Cover · Disclaimer · Executive summary · Problem and opportunity · Market size · VALUE PROPOSITION AND USE CASES · Solution and product · Business model · Competitive landscape · Moats and key findings · Momentum · Unit economics · Management · Team and cap table · [Product and technology assessment, if DD covered it] · DD DOUBTS RESOLVED · Validation (2 slides) · Revenue forecast · Use of proceeds and milestones · Roadmap and go-to-market · Valuation and entry point · Exit path · Fund fit and return check · Impact · Risks and mitigants · Decision requested.

## Craft rules

1. **One message per slide.** Each slide makes one point. If it needs two, split it or move the detail to the annex.
2. **Action titles.** Every slide title is a full-sentence finding with a number or a verdict in it, never a topic label. Example: "Entry at a USD 8M cap is fair at 4.1x ARR, even on the conservative case." Only the Cover, Disclaimer, Executive summary and Decision requested slides keep plain titles.
3. **Bold lead-ins.** On slides, each bullet opens with a short bold claim, then the evidence. This is a deck-only addition to the lead-in rule in `house-style`. The reader should get the point from the bold text alone.
4. **Numbers with sources.** Every data slide ends with a `Source:` line naming the document, call note or data-room file. Mark company-stated figures as claims and label what DD verified.
5. **Evidence on the page.** Momentum, unit economics, the forecast and the valuation range are shown as a small table or a Mermaid chart, never as prose alone. Use a "Key takeaways" or "Our read" block beside a table to say what it means.
6. **Density without filler.** No generic marketing language, no restating the same fact on two slides. If content is thin, add the table or the takeaway that the evidence supports. Never pad.
7. **No slide left as a skeleton.** A slot with no DD content behind it is marked `PENDING` with what is missing, never filled with invented text.
8. **Honest flags stay visible.** Mark contracts not yet signed, metrics nobody has verified, and earlier work that is missing right on the slide (a status column, `PENDING`, "company-stated"), not hidden.

## Slide recipes

- **EXECUTIVE SUMMARY:** first line, in bold, is the recommendation (ticket, instrument, round, valuation or cap, conditions). Then 4 to 5 sub-headed blocks of 1 to 3 bullets each, in this order: what the company is and its traction · Why now · The wedge (what sets it apart structurally) · Momentum with discipline · Entry, valuation and exit. Conditional deals add: the Final scorecard line, Conditions to close, Return honesty (the return check result and its reading, per `fund-thesis`), Key risks.
- **PROBLEM:** 3 to 4 quantified claims, each with a numbered source, plus one synthesis block on the structural gap. Sources listed as numbered footnotes.
- **MARKET:** a TAM / SAM / SOM table (the figures and the scenario band exactly as in the latest market analysis), the growth rate, the assumption ratios, and 3 to 4 bullets on where the sector is heading.
- **SOLUTION AND PRODUCT:** a table with one column per product layer or module: What it does · Status (live / built / pilot) · Proof. Under the table, one paragraph on architecture, integrations and controls, ending with one sentence on what is proven today.
- **BUSINESS MODEL:** numbered revenue streams, each with Description · Pricing · Revenue driver · Contract status, plus a revenue-by-stream table (revenue, change, share of total, margin).
- **COMPETITIVE LANDSCAPE:** a 2x2 positioning map as a Mermaid quadrant chart with labeled axes, then a comparison table (company, differentiators, main channel, target user, footprint, funding) with the company's row in bold, then the market inflection points.
- **MOATS:** four blocks, each labeled REAL or CLAIMED as in the competition analysis, with the evidence under each.
- **MOMENTUM:** revenue, users or funnel over time as a table or Mermaid chart, a one-line explanation for every anomaly (a dip, a spike), and our read.
- **UNIT ECONOMICS:** a table of the core ratios over time (acquisition cost, payback, ticket, margin) and a Key takeaways block with 3 sub-heads of 2 to 3 bullets.
- **MANAGEMENT:** one block per principal: who they are and why it matters · relevant experience · current role and scope · our assessment (strengths, risks). Draw from the management DD and its verdict.
- **TEAM AND CAP TABLE:** the cap table, insights bullets, and the current versus planned team (a Mermaid org chart if it helps).
- **REVENUE FORECAST:** the quarterly P&L table (revenue by line, cost of sales, gross margin, operating costs, EBITDA, margin) with a "Reading the forecast" block, then the management case against the fund case from the financial DD, as a table or Mermaid chart, with insights.
- **USE OF PROCEEDS:** round terms, use-of-funds split, the milestones the round must reach before the next round, and the KPIs to track.
- **FUND FIT AND RETURN CHECK:** the return check from `fund-thesis` applied to this deal (ticket, entry ownership, required exit value, required growth and its reading). One-sentence read underneath.
- **IMPACT:** the commercial mechanism first (impact never leads the memo, per `fund-thesis`), then a table of the impact dimensions from `fund-thesis` with the KPIs and proof points from the impact template.
- **RISKS:** 4 to 6 numbered risks, each with its mitigant or the condition to close.

## VALUE PROPOSITION AND USE CASES (mandatory slide)

Title: "[Company] creates value by [mechanism], turning it into [outcome for the customer]."

Left block, "Value proposition": four sub-blocks, each with a bold title and 3 to 4 short bullets. They are the four things the CUSTOMER receives, told from the customer's point of view with the outcome first (how things change for them), never as a list of features. Derive them from the product material, the deck, reference letters and client calls.

Right block, "Use cases for [target segment]": three numbered use cases. Each one states the user and their circumstances · how they use the product · the outcome that can be measured (income, cost, time, conversion) · a single concrete example or client, by name. In a B2B company the use cases are scenarios for clients, ideally one that is live, one being implemented and one that is a target.

Rules: evidence only. Every use case must lead back to a real client, pilot, reference letter, case study or interview. If a use case is a target, label it "target, not yet live". Do not invent outcomes or figures. When the data room holds no case studies, show the blocks that have evidence behind them and mark the others `PENDING`. This slide does NOT take the place of Solution and product: the value proposition is what the customer receives, and the solution is the way it operates.

## Three sections need specific handling

- **DD DOUBTS RESOLVED (the keystone):** go through the IC feedback and DD guide in `deals/[Company]/3-ic-feedback/`. Show, point by point, each doubt the IC raised at pre-approval and how due diligence answered it, in a table: Doubt raised (source) · DD finding (source) · Status. Status is RESOLVED, PARTIALLY RESOLVED or OPEN, per `house-style`. Usually 7 to 10 rows. No slide matters more to the decision.
- **VALIDATION (2 slides):** pull the DD call notes together, grouped by interview type: expert reviews, investor references, client references, team interviews. Two types per slide, each block with who and when, Findings and Watch items. Findings only, never transcripts.
- **VALUATION AND ENTRY POINT, then EXIT PATH (2 slides):** give valuation real space. Slide one: the entry multiple, the comparable multiples (trading and transaction medians), the venture-method result and a valuation range by method (a football-field table or Mermaid chart with the entry price marked). Slide two: the exit routes, named acquirers and their appetite, and the M&A context. The full walk-through lives in the annex.

## Tailor the emphasis to THIS deal's DD guide

The spine of the deck stays fixed, but its emphasis is VARIABLE. Start by reading the DD guide: the committee will argue about the doubts the IC raised before approval. EXPAND the sections that respond to those doubts (add a focused slide when a doubt is significant, for example a second market slide if size was contested, or a second momentum slide if growth was questioned) and keep settled areas to a single slide. Insert an added slide right after the template slide it expands. Do not stamp out an identical deck every time.

## Debt branch (conditional)

If the company carries debt or debt facilities (a credit line, venture debt, a lending book funded by third parties):
- **Deck:** add a "Debt facility" slide right after "Use of proceeds and milestones". It shows each facility (lender, size, drawn amount, cost, maturity, security, covenants), the debt-to-equity mix, headroom against covenants, and what happens to the equity if a covenant breaks. Action title, sources, flags as for every slide.
- **Annex:** fill the fifth section, "Debt terms", which the annex template places after Step-by-step valuation: the full terms of each facility, covenant tests with current values, repayment schedule, and the debt's ranking against the fund's instrument.

Take every figure from the financial DD and the legal documents in `4-dd/5-legal/`. Companies without debt add no debt slide and delete the "Debt terms" section from the annex copy.

## The annex: a focused deep-dive

The annex does NOT copy the deck. It holds ONLY the four sections below, in the order shown (plus "Debt terms" under the debt branch), and nothing else:
1. **Product and roadmap evolution:** the current state of the product and the roadmap ahead, phase by phase. From the deck, product material in `4-dd/3-product-tech/` and the call notes.
2. **Exit pathways:** the exit routes that are realistic, the strategic acquirers, and the M&A context. From the financial DD and the competition analysis.
3. **Comparable benchmarks:** the trading and transaction comparables with their medians. From the financial DD and any comparables file in `4-dd/4-financial/`.
4. **Step-by-step valuation:** the venture-method valuation walked through line by line, then the range of exit scenarios.

No executive summary, problem, management, validation, impact or risks: those live only in the deck.

**Comparables and exit multiple.** Take them from the financial DD and any comparables file in `4-dd/4-financial/`. If they were not researched, use the placeholder exit multiple defined in `fund-thesis`, mark every figure built on it `PLACEHOLDER`, and flag it in the Comparable benchmarks section and on the valuation slide. Never invent a comparable company or a multiple.

**Valuation walk-through.** Use the return check from `fund-thesis`. Point to it, do not restate its assumptions; show only this deal's inputs and results at each step.

## Source content from completed work (synthesize, never re-analyze)

Draw on the documents already finished for this deal; do not work anything out again:
- the Final scorecard in `5-final-scorecard/` (the recommendation, scores, conditions);
- the management DD in `4-dd/2-management/` and the financial DD in `4-dd/4-financial/`;
- the market and competition analyses in `4-dd/1-market-competitive/`: the `-dd-refined` version of each wins, per `house-style`;
- the impact template in `1-impact/`;
- the IC feedback and DD guide in `3-ic-feedback/`;
- the DD call notes in `4-dd/6-interviews/`.

Never fabricate a number, a quote or a source. Flag missing inputs on the page.

## Verify before finishing

Run this pass on both files and fix what fails:
1. Every template slide is present and in its template order (plus the debt slide if the branch applies, plus any slide added for a DD doubt; minus the product and technology slide only if DD did not cover it).
2. No unfilled slot: no bracketed guidance text left, no empty table cell without `PENDING`.
3. Every slide title is an action title (except the four plain ones).
4. Every number matches its source document, and every data slide has a `Source:` line.
5. Deck and annex agree: the same valuation, multiples, comparables, exit routes and roadmap in both.
6. The Value proposition and use cases slide and the DD doubts resolved slide are filled with evidence.
7. Any `PLACEHOLDER` multiple is flagged in both files.

## Output

- Deck: `YYYY-MM-DD-[company]-ic-memo.md` in `deals/[Company]/6-ic-memo/`.
- Annex: `YYYY-MM-DD-[company]-ic-memo-annex.md` in `deals/[Company]/6-ic-memo/`.
- Return to the main thread: the recommendation, the slide count, which sections were expanded for this deal's DD doubts, whether the debt branch was used, and confirmation that the verification pass was done.

This is token-intensive, and that is acceptable. Precision over speed.
