---
name: pre-screen
description: The fund's first-step triage method. A fast, deck-only pre-screen written for the weekly screening committee. Covers the snapshot, the easy flags, the hard-filter check, a first-pass recommendation, and the output file. Load this whenever a pre-screen, a first-pass triage, or a screening-committee write-up is requested.
---

# Pre-screen method

The pipeline begins with the pre-screen; it is the FIRST step. Using nothing but the deck and first-call notes, it hands the weekly screening committee an initial view of a company. It is quick and relies on the deck only.

## Core discipline: DECK-ONLY, no research

- Work ONLY from what the deck and any first-call notes contain. Do NOT search the web, analyze the competitive landscape, or size the market independently. Those tasks belong to the market and competition agents in the following stage, and doing them here would blur the line between stages.
- A data point not in the material is PENDING. A careful inference from the deck is INFERRED. Never fabricate.
- Keep it fast. This is a triage, not a verdict.

## Inputs

- The pitch deck in deals/[Company]/_inbox/deck/.
- Any first-call notes in deals/[Company]/_inbox/pre-ic-calls/.

## 1. Snapshot (from the deck)

A table: founded, stage, sector, headquarters, countries of operation, round size, post-money valuation or cap, annual recurring revenue or run-rate, lead investor, instrument, share of the round committed. Unknowns are PENDING.

## 2. Company summary

Three to six bullets: what the company does, the problem, the business model, the traction headline.

## 3. First-call highlights

Three to five key points from the first-call notes. If there are no notes, mark the section PENDING.

## 4. Easy flags (quick checks)

Show the four flags in one table, then a short paragraph on any flag that is not clean.

- **Valuation multiple.** Post-money valuation (or cap) divided by current annual recurring revenue gives the implied multiple. Label CHEAP / FAIR / STRETCHED / RICH, or PENDING. Flag it if it is more than twice the sector median the deck or general knowledge suggests, and say the comparison is not researched.
- **Cap table health.** Founders' fully diluted ownership, dilution per round (more than 20% per round is a flag), option pool, a crowded cap table (more than 10 investors adds complexity), inactive founders holding large stakes. Label HEALTHY / WATCH / RED FLAG / PENDING.
- **Round commitment.** Share committed, lead confirmed (yes or no), whether the fund could lead (per the ticket and lead rules in fund-thesis), and the distance from the round filter in fund-thesis. Label OK / CONCERN / PENDING. Flag it when the round does not meet that filter.
- **Geography fit.** Compare the markets the company serves today, and any dated expansion plan, with the geography in fund-thesis. Label HIGH / MEDIUM / LOW. Flag it when the main market sits outside that geography with no dated plan to move into it.

## 5. Hard-filter check

Check the company against every hard filter in the fund-thesis skill. Take the filters from there, do not restate them from memory. Mark each one YES / NO / INFERRED / PENDING in a table. A single NO signals reject automatically.

## 6. Competitive context (deck-only, light)

List competitors ONLY if the deck names or clearly implies them. Do not research the landscape. When the deck names no competitor, state that.

## 7. Market context (deck-only, light)

How the deck frames its market, labeled as the company's claim, not verified at this stage.

## 8. Gut feeling

Two to four candid sentences: your instinct on this first pass, what draws you in, what concerns you.

## 9. Recommendation

Choose exactly one:
- ADVANCE: proceed to the market and competition analysis.
- MONITOR: log it and revisit when a specific, named condition is met.
- REJECT: with a clear, real reason.

Give a one-paragraph rationale. Per house-style, the recommendation also appears straight after the document header.

## Output

- ONE Markdown file, formatted per the house-style skill (header, bold lead-ins, tables, status labels, footer).
- Name it `YYYY-MM-DD-[company]-pre-screen.md` and save it to deals/[Company]/0-prescreen/.
