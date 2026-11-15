# How to use this workspace

This workspace runs a fund's deal pipeline through a set of AI specialists. You drive them with short, plain requests in Claude Code. You do not need any special commands: ask for what you want and name the company.

## Starting a new deal

1. Copy the folder `deals/_TEMPLATE/` and rename the copy to the company name (for example `deals/Acme/`).
2. Put the pitch deck in `_inbox/deck/` and the notes from the first call in `_inbox/pre-ic-calls/`. That is all `_inbox/` holds.
3. Later, put the investment committee (IC) discussion notes in `3-ic-feedback/`, and the due-diligence (DD) call notes (team interviews, investor references, client references, expert reviews) in `4-dd/6-interviews/`.

If you receive a full data room, drop it into the company's `4-dd/` folder and say "organize the data room for [Company]". Every file is sorted into the six DD sub-folders and every move is reported.

## What you can ask for, in the order the process runs

| Say this... | You get... | It lands in... |
|---|---|---|
| run the pre-screen on [Company] | A triage for the weekly screening committee | `0-prescreen/` |
| run the market analysis on [Company] | Market sizing (TAM, SAM, SOM) and market context | `4-dd/1-market-competitive/` |
| run the competition analysis on [Company] | Competitive landscape and moats | `4-dd/1-market-competitive/` |
| run the Pre-IC scorecard on [Company] | A scored recommendation on six dimensions | `2-preic/` |
| build the impact template for [Company] | The impact document for the fund's impact committee | `1-impact/` |
| build the investment template for [Company] | The investment deck the IC sees at Pre-IC | `2-preic/` |
| build the IC feedback and DD guide for [Company] | The IC's feedback and the guide for due diligence, in one document | `3-ic-feedback/` |
| organize the data room for [Company] | A sorted data room | (moves files, reports in chat) |
| refine the market analysis for [Company] with DD findings | The DD-refined market analysis | `4-dd/1-market-competitive/` |
| refine the competition analysis for [Company] with DD findings | The DD-refined competition analysis | `4-dd/1-market-competitive/` |
| run management DD on [Company] | Founder and team assessment | `4-dd/2-management/` |
| run the financial DD on [Company] | Financial model write-up | `4-dd/4-financial/` |
| run the Final scorecard on [Company] | The scored recommendation after DD, with what changed since Pre-IC | `5-final-scorecard/` |
| build the IC memo for [Company] | The IC deck and its annex | `6-ic-memo/` |
| start the legal due diligence on [Company] | A legal checklist and a tracker to share with the founders. Final step, SAFE or convertible rounds only | `4-dd/5-legal/` |

## Good to know

- **Order matters.** Each specialist checks that the steps before it are done. If you skip ahead, it tells you what is missing and asks before continuing, so you cannot build on nothing by accident.
- **It will not make things up.** If a number or a document is missing, the specialist flags it instead of inventing it.
- **A completed step is never repeated**, with two deliberate exceptions. The scorecard runs twice (Pre-IC, then Final after DD). The market and competition analyses are refined once at DD, not rebuilt.
- **The specialists pause at judgment calls.** Several of them recommend something (the company's legal structure, an IC decision read from the notes, a placeholder multiple) and ask you to confirm before they apply it.
- **Every document looks the same.** The format lives in one place, the `house-style` skill.
- **The fund's facts live in one place.** Filters, ticket sizes, scoring weights and thresholds are in the `fund-thesis` skill. Change them there and every specialist follows.
- **Legal DD is the last step** and runs only when you explicitly say "start the legal due diligence", never automatically. It detects the company's corporate structure, confirms it with you, and builds the checklist only for the jurisdictions that company has.

## The financial model

Put the company's financial model in `4-dd/4-financial/` (the data-room organizer does this for you). If the fund's team has built its own, more conservative case, save it in the same folder with "fund case" in the file name. The financial DD then shows the company's projections and the fund's case side by side. The specialist reads and explains models. It never builds or changes one.

## If something looks off

Re-run the step, or ask the specialist to revise ("redo the market SOM for Acme with a 3% base case"). For a change in format or method that should apply to ALL deals, edit the playbooks in `.claude/skills/`, not an individual output. Read `AGENT-EDITING-GUIDE.md` first.
