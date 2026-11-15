---
name: competition
description: How the fund analyzes the competitive landscape and the moats of a startup. It covers mapping the whole landscape, the competitor table, testing seven types of moat for real vs claimed, value added, the competitive response timeline, incumbents' barriers, and the red, yellow or blue ocean verdict, opened by a one-page summary. Load this any time a competitive analysis is being built or refined.
---

# Competitive analysis method

You are analyzing competition to the standard of a rigorous venture analyst. Each claim must lead back to a cited source, the deck or the call notes. Nothing vague. Stay honest: do not overstate any moat that the company has yet to build.

## Core principle: real moats vs claimed moats

A moat is counted only when it already exists and there is evidence for it. A moat the company plans, aspires to or asserts without having built it is CLAIMED, and is labeled as such. Always compare the current reality with the desired future state. If the company says "network effects" or "proprietary data" but nothing shows the flywheel actually turning, that moat is CLAIMED, not REAL.

## Map the full landscape, not just startups

- **Direct competitors**: startups selling the same solution to the same customer.
- **Indirect competitors**: another kind of solution for the same job to be done.
- **Incumbents and the status quo**: banks, large marketplaces and their payment arms, established offline players, manual processes and in-house workarounds.
- **Market dynamics**: the consolidation, funding flows, regulatory changes and platform moves that decide who comes out ahead.

## Competitor table

| Company | HQ | Product | Average ticket | Channel | Tech-enabled | Key differentiator vs [Company] | Funding |

The company itself goes in the first row, judged as strictly as everyone else. Group similar players into one row rather than adding many thin rows, and end with a "Status quo" row when a manual or in-house alternative exists. Unknown cells are `PENDING`. Company claims are marked as claims.

## The seven moat types: REAL (in place, evidenced) or CLAIMED (aspirational)

- **Distribution**: active, signed alliances that open new geographies or deepen the home market. REAL = a live partnership. CLAIMED = "in talks" or a letter of intent.
- **Regulatory**: licenses the company holds, or a believable, documented route to approval. REAL = held, approved or visibly in process. CLAIMED = "we will apply."
- **Founder and sector**: second-time founders, prior exits, decades in the sector, demonstrable contacts and fundraising record. REAL = evidenced history. CLAIMED = ambition or narrative.
- **Investor**: strong investors already on the cap table, actively opening doors. REAL = investors who have in fact put money in. CLAIMED = "we are raising from" or a list of targets.
- **Product and tech**: something genuinely solved and hard to copy because of knowledge the team holds. REAL = running in production, with the advantage shown. CLAIMED = roadmap.
- **Data**: large-scale data that is proprietary or exclusive, which a competitor would struggle to obtain (an exclusive source, years of build-up, or regulatory gating). REAL = the company already has and uses data that others cannot obtain. CLAIMED = "we will accumulate data over time," or a dataset that anyone could put together. Tech is hard to BUILD, data is hard to ACQUIRE: never count one advantage as both.
- **Physical infrastructure**: assets already deployed (logistics networks, hardware fleets, sensors, points of presence) that put up a genuine barrier of capital and time. REAL = built and operating. CLAIMED = a planned rollout or a single pilot site.

Show the assessment in a table, with one row for each moat type relevant to this company:

| Moat type | REAL or CLAIMED | Evidence and rationale |

A split moat gets one line per part. When none of the moats is real yet, state it plainly beneath the table, in these words: "No real moats identified at this stage."

## Value added and differentiation

Where the company is truly better than the rest of the field, and whether that edge is a lasting wedge or just a feature that a funded rival could copy fast.

## Competitive response timeline

How much time would a competitor with plenty of funding need to copy this? If the answer is short, the moat is thin. If it is long, the company is defensible.

## Incumbents' structural barriers

What in the structure of the market prevents incumbents from crushing this company. If nothing does, write "None" and record it as a risk.

## Ocean assessment: competitive density read together with relative moat strength

- **RED**: the competitors are real and credible, and the company lacks any clear moat to hold them off. Crowded and undefended.
- **YELLOW**: in between. Some competitors, moats on both sides, the company holds some real moats but the space is contested. There is room.
- **BLUE**: not many competitors, and the company has strong real moats that they do not have. Space to grow, and well defended.

State the verdict in capitals, with a rationale that ties density and moat strength together.

## Required output, in this order

1. The header (house-style), with the Status line.
2. **One-page summary.** Straight after the header:
   - The landscape at a glance: a short table with the company and its five to eight most relevant competitors (grouped where sensible, status quo included), one line each on who they are and how they compare.
   - The moat verdict: how many moats are REAL today, which ones, and what would turn the claimed ones real.
   - The ocean verdict: RED, YELLOW or BLUE, with its one-line rationale.
   - The top three open competitive questions.
   Every competitor, moat call and verdict here must match the body exactly.
3. **Competitor table** (direct, indirect, incumbents and status quo).
4. **Moat assessment** table.
5. **Value added**: durable wedge or copyable feature.
6. **Competitive response timeline.**
7. **Incumbents' structural barriers**, or the risk noted.
8. **Ocean verdict** with rationale.
9. **Sector insights**: 4 to 5 dated, sourced market dynamics (rounds, launches, acquisitions, regulation), each with what it implies for the company.
10. **Open competitive questions**, each marked OPEN or RESOLVED (a RESOLVED item names the call or document that resolved it), with why it matters and how to resolve it.
11. **Evolution log**: one dated line per version.
12. Sources, then the footer (house-style).

When the analysis is refined (REFINE or DD-REFINEMENT), update the one-page summary together with the body, so the two never disagree.

## Quality bar

Internal working document: the reasoning is rigorous and the format consistent, but it is not a showpiece for the investment committee. Cite sources. Never invent a competitor, a funding round or a moat. Flag missing data instead. Tell claimed from real honestly: that honesty is the whole purpose of this analysis.

## DD-refinement stage

At due diligence the analysis is refined, never rebuilt. Read the competition analysis from Pre-IC, which sits in deals/[Company]/4-dd/1-market-competitive/, the DD competitive material in that same folder and the DD call notes in deals/[Company]/4-dd/6-interviews/. Resolve the open questions the evidence answers, update the competitor entries and moat calls it sharpens (in the summary and the body), mark the Status line as the DD-refined version with its date, and add an Evolution log line. Save it as `YYYY-MM-DD-[company]-competition-dd-refined.md` in the same folder. Never overwrite the Pre-IC file.
