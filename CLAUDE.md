# Investment process workspace

This workspace runs a venture fund's deal flow, from the first pitch deck to the investment committee (IC) memo, with a team of specialist agents.

## Who we are

Example Ventures is a fictional early-stage fund. Its facts (filters, ticket sizes, scoring weights, impact lens) live in the `fund-thesis` skill and nowhere else. The commercial case comes before impact: never frame the fund as impact-first.

## Pipeline routing

Each company has a folder at `deals/[Company]/`, copied from `deals/_TEMPLATE/`. To start a deal, copy the template, rename it to the company, and put the deck in `_inbox/deck/` and the first-call notes in `_inbox/pre-ic-calls/`.

| When the user asks for... | Delegate to | Output folder |
|---|---|---|
| a pre-screen, first-pass triage, weekly screening committee | pre-screen | `0-prescreen/` |
| a market analysis, market sizing | market-analysis | `4-dd/1-market-competitive/` |
| a competition or competitive analysis | competition-analysis | `4-dd/1-market-competitive/` |
| a Pre-IC scorecard, to score a company | scorecard (Pre-IC mode) | `2-preic/` |
| an impact template | impact-template | `1-impact/` |
| an investment template, IC slide template | investment-template | `2-preic/` |
| IC feedback, a DD guide | ic-feedback-dd-guide | `3-ic-feedback/` |
| a data room sorted, files organized into the DD folders | data-room-organizer | sorts files into the `4-dd/` sub-folders and reports the moves |
| the market analysis refined with DD findings | market-analysis (DD mode) | `4-dd/1-market-competitive/` |
| the competition analysis refined with DD findings | competition-analysis (DD mode) | `4-dd/1-market-competitive/` |
| management due diligence | management-dd | `4-dd/2-management/` |
| financial DD, a financial model write-up | financial-model | `4-dd/4-financial/` |
| a Final scorecard | scorecard (Final mode) | `5-final-scorecard/` |
| an IC memo, investment committee memo | ic-memo | `6-ic-memo/` |
| the legal due diligence (only on an explicit "start") | legal-dd | `4-dd/5-legal/` |

Process order: pre-screen, then market + competition + Pre-IC scorecard, then the impact template, then the investment template (the deck the IC sees at Pre-IC), then IC feedback and DD guide, then (organize the data room) management DD + financial DD plus the DD-refined market and competition, then the Final scorecard, then the IC memo.

DD call notes go in `4-dd/6-interviews/`. The cap table and corporate paperwork go in `4-dd/5-legal/`. IC discussion notes go in `3-ic-feedback/`.

Legal DD is the FINAL step. It runs only after the IC memo, and only when a team member explicitly says to start the legal due diligence. It applies only to SAFE or convertible early rounds.

Agents enforce their own prerequisites and stop if upstream work is missing. A completed step is never repeated: market and competition are refined at DD, not rebuilt, and the scorecard runs twice by design (Pre-IC, then Final).

## Rules

1. Never fabricate numbers. If a document is missing or a data point is unavailable, flag it explicitly.
2. Stop after each stage and wait for instruction before proceeding.
3. After producing any deliverable, delete all temporary and intermediate files from the deal folder. Only inputs and final deliverables may remain.
4. Before changing any agent or skill, read `AGENT-EDITING-GUIDE.md`.
