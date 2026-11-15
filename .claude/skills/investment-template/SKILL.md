---
name: investment-template
description: The method for producing the investment template, a slide-by-slide Markdown deck for the investment committee, by filling a COPY of the empty template in this skill folder with this deal's content. A fixed slide sequence with two-panel slides; only the content changes, never the structure. Load this any time someone asks for an investment template, an investment deck, or an IC slide template.
---

# Investment template method

The investment template is an IC-facing deck whose format is STRICT and FIXED. OUTPUT TIER: IC-facing, which sets the highest craft bar of any output here. It must be sendable to the investment committee as-is.

## The cardinal rule: FILL A COPY, do not rebuild

- Copy `template.md` from this skill folder to the output path, then fill it. Do NOT recreate the deck from nothing, reorder slides, rename fixed slide titles, or add free-standing sections.
- Each slide is a `## Slide N: [Title]` section. Two-panel slides have a `### Left panel` and a `### Right panel`. Keep that structure. You change the WORDS and NUMBERS only.
- Format of the header, labels and footer follows `house-style`. Fund facts follow `fund-thesis`.

## Write for a slide

- Each slot holds slide-length text: short bullets, short table cells, a few lines per panel. If content does not fit, cut it and leave the detail in the Pre-IC documents. Never stretch a slot into a memo.
- Every number carries its unit and period, per `house-style`.

## Fixed slide sequence

1. **Problem and solution.** Left: company fact box (founded, sector, stage, round, valuation, annual recurring revenue, impact in one line). Right: the problem (top) and the product and technology solution (bottom).
2. **Management and cap table.** Left: the C-level team with short bios. Right: the team assessment (from the Pre-IC scorecard, S1) and a simplified cap table.
3. **Business model.** Left: how the model works. Right: titled "Revenue streams" or "Unit economics", whichever fits the business model.
4. **Market forecast.** Left: the market forecast. Right: titled "[Geography or sector] nuances", adapted to the company.
5. **Market size.** Full width: a step-down TAM, SAM and SOM table (special handling below).
6. **Momentum, forecast and multiple on exit.** Left: momentum and a quarterly revenue table. Right: projections and the exit-multiple rationale, consistent with the return check in the Pre-IC scorecard.
7. **Competitive landscape.** Full width: a 2x2 map (two axes chosen from the competition analysis), shown as a quadrant table, with the company highlighted.
8. **Competitors (optional).** Full width: a separate competitors slide, used only when the landscape needs one before the advantages slide. Delete it otherwise and renumber.
9. **Competitive advantage and value added.** Full width: three numbered advantages, each with a bold title, an italic subtitle, a short paragraph and a stat callout.
10. **Product roadmap and go-to-market.** Left: a three-phase roadmap. Right: the go-to-market narrative.
11. **Money fit and key due-diligence focus areas.** Left: the due-diligence focus table (market and moats, revenue and unit economics, impact, team, exit path). Right: the money fit box (ask, valuation, instrument, round type), the use of funds, and the round milestones.
12. **About the fund.** The closing slide. Fill it from `fund-thesis` at the time of writing; never copy fund facts into this skill or the template.

## Variable elements (adapt per deal, keep the format)

- The competition section is two slides (most deals) or three (with the optional competitors slide).
- The slide 3 right-panel title and the slide 4 right-panel title adapt to the company.
- The slide 5 step-down columns adapt to the revenue model (take rate, subscription revenue, and so on).

## Market size slide: SPECIAL HANDLING

- Rebuild every number from this deal's market analysis (the `-dd-refined` version if it exists, per `house-style`). Adapt the step-down columns to the revenue model: eligible base, then penetration or share financed, then take rate or revenue per customer, then the resulting revenue. Rows are TAM, SAM and SOM, with scenarios where the market analysis has them.
- The slide's numbers must MATCH the market analysis. If the market analysis lacks a step, mark that cell `PLACEHOLDER` with the reason; do not compute a new figure the analysis does not support.

## Source content from prior work: synthesize, do not invent

- Fill the deck using the documents already written for this deal: take the deck and call notes from `deals/[Company]/_inbox/`; take the Pre-IC scorecard from `deals/[Company]/2-preic/`; read the market analysis and the competition analysis from `deals/[Company]/4-dd/1-market-competitive/`; and use the impact template from `deals/[Company]/1-impact/`.
- NEVER fabricate a number, a name or a quote.
- MISSING DATA: keep the slot and mark the gap inside it with `PLACEHOLDER: [what is missing, and where it will come from]`. For example, if the use-of-funds split is not disclosed, keep the use-of-funds table with one row reading `PLACEHOLDER: split not disclosed, due-diligence item`. Never delete a slot because its data is missing. List every placeholder in the final report.

## Verify before finishing: the deck is NOT done until this passes

1. Every slide in the template is present, in order, with its fixed title (the optional slide 8 either filled or removed with the numbering fixed).
2. No bracketed guidance from the template survives. Every slot is filled or carries a `PLACEHOLDER`.
3. Every number matches its source document: market figures against the market analysis, scores and the return check against the Pre-IC scorecard, impact KPIs against the impact template, competitors against the competition analysis.
4. The header, the company name on every slide, and the footer follow `house-style`.

## Output

- One Markdown file in `deals/[Company]/2-preic/`, named `YYYY-MM-DD-[company]-investment-template.md`.
- Return: the slide count, which slides carry placeholders or flags, and confirmation that the verification pass was done.
