---
name: financial-model
description: How the fund does financial due diligence: it reads the financial model of a company (a spreadsheet or CSV files, sometimes with the fund team's own conservative case beside it) and writes the financial DD that explains drivers, assumptions, unit economics, the return check, and red flags, adjusted by stage and business model. The agent only reads and interprets the model; building or changing it is not its job. Load this whenever a financial DD or a financial model write-up is requested.
---

# Financial due-diligence method

Your job is to READ the company's financial model and WRITE the document that explains it. You are the interpreter and writer, not the modeler.

## Interpret, do not re-model

- Treat the model files in `4-dd/4-financial/` as the source of truth. Explain their structure, drivers, assumptions and scenarios.
- Do not build a new model, do not change the files, and do not quietly re-derive or "correct" figures.
- If a figure, driver or assumption is unclear, missing or inconsistent, FLAG it. Never guess a number.
- Keep the company's projections and the fund's case apart. If a file whose name says "fund case" exists, present the two side by side and explain where and why they differ. If there is no fund case, say so and do not create one.

## First, identify stage and business model

Both change what the write-up must contain. Every company that passes the stage filter in fund-thesis has live revenue to examine.

### Depth by stage

- **Seed:** mostly projections over a short history. Test whether the ramp is credible against the months that exist, and scrutinize the growth logic and the assumptions behind it.
- **Series A:** the most thorough. Hold the projections against a real track record, analyze history and projections together, and run the lending checklist (under "Scope by business model") if the company lends or carries debt.

### Scope by business model

- **Software or marketplace:** the metrics spine below is enough.
- **Lending, or any company that funds itself with debt:** its health lives in the book and the facility, not only the P&L. Also cover: facility behavior (utilization, advance rate, cost of funds); cash flow specific to the loan book; covenants and the headroom against each; book quality (delinquency, defaults, provisioning, loss curves by cohort); and asset-liability matching (do funding terms match loan terms).
- **Other capital-intensive models:** apply equivalent scrutiny to whatever actually drives that business's economics.

## Inputs

- The company's model (spreadsheet or CSV files), any fund case file, and any comparables file, all in `4-dd/4-financial/`.
- The deck and the financial call notes in `4-dd/6-interviews/`.
- The return check assumptions and bands from `fund-thesis`.

## Metrics spine

- Burn multiple and runway in months at current burn.
- Cash flow: how cash actually moves across the projection.
- Gross margin: level, quality, and trend.
- Cohorts: retention and revenue by cohort.
- Unit economics: acquisition cost, lifetime value, their ratio, payback.
- Revenue quality: recurring versus one-off, and durability.
- Customer concentration.
- Growth by period and compound monthly growth rate.
- Revenue build: the drivers and the logic linking them.

## Return check

Compute the return check exactly as fund-thesis defines it, with its assumptions, and read the result against its bands. Take the exit multiple from the comparables file in `4-dd/4-financial/`. If there is none, use the fund-thesis placeholder multiple only after the user agrees, and mark every figure derived from it `PLACEHOLDER`. State the band and what it implies for the round. If a fund case exists, show the check on both cases.

## Red flags (lead with these)

- Cash needs well beyond the raise, so runway is dangerously short.
- Projections not earned by history: a sharp acceleration, or a sudden jump in margin, lifetime value or unit economics, with no operating reason.
- Margins that do not support the model at scale.
- Unit economics inverting: acquisition cost rising faster than lifetime value, or payback lengthening.
- Heavy dependence on one or a few customers.
- Burn multiple worsening across the projection.
- Anything else that strains credibility against the history and the deck.

## Output and quality bar

- One Markdown file following `house-style`, named and saved as the `financial-model` agent says. Never produce or change a model file.
- Open with the red flags and the return check result, then the analysis.
- Cite the sheet or file and the figure behind every claim from the model.
- Keep the company's projections and the fund's case clearly apart, and state when there is no fund case.
- Flag every missing or unclear input.
- Match depth to stage: projections-focused for Seed, full history plus projections (and debt, where present) for Series A. Never manufacture rigor the data does not support.
