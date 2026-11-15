---
name: market
description: The fund's method for sizing a startup's market. Geography-realistic TAM, SAM and SOM built two ways (top-down and bottom-up), scenario-based capture, a sector-specific structural gate, market growth and structural tailwinds, opened by a one-page summary. Load this whenever building or refining a market analysis.
---

# Market sizing method

You are sizing a market to the standard of a rigorous venture market analyst. Each figure must lead back to a cited source or to an assumption you state openly. Nothing vague.

## Core principle: geography realism, never global by default

Do not size a market by multiplying a US or global figure by the region's share of GDP. No region is uniform, and few companies can operate in every part of one. Each layer of the sizing follows from where this particular company can realistically expand. Because realistic geographies differ, two companies in one sector can end up with very different market sizes.

## TAM: the realistic ceiling for this company

- Tie the TAM to what is realistically the upper limit for this particular company, not to the whole planet by reflex.
- Default to the fund's home region (see fund-thesis for the geography). A global TAM is allowed only if the company can truly grow past the region, and in that case explain why, tied to the company's characteristics.
- Say where the macro figure comes from and how you chose the subset of it that you use.

## SAM: the countries this company can realistically win

- Cut down to the particular countries this company could plausibly expand into within 5 to 8 years, judged by its real characteristics: product, model, capital, team, regulatory exposure.
- Be explicit about each exclusion and why. A company built for a cluster of small markets should not be credited with the region's largest economies if it cannot realistically win there. Include the largest or hardest market only for a specific reason.
- Split the user persona in two steps, applied in this order:
  1. The startup's actual target: the exact clients or segment the company was designed for (in lending, the kinds of borrowers it serves, not every person who borrows).
  2. The structural reality of that market: narrow further, per country, by the sector-specific factor that decides how many of those targets exist and can be reached (see the structural gate below).
- The startup decides WHO gets counted. The reality of the market decides HOW MANY of them actually exist. Only the people who pass both filters make up the true addressable population.

## SOM: realistic capture as a scenario band

- Show capture as three scenarios, each a share of the SAM: 3% (bear), 5% (base), 8% (bull).
- Set the base case at 5%. Any departure from it must be justified by competitive intensity, market concentration and the state of the art.
- Reality test: compare the base-case path with the required revenue at exit from the return check in fund-thesis. If the market cannot carry that revenue, do not pass silently. Flag it and note that it needs a conviction discussion.

## Bottom-up cross-check (always build it)

- Build the SOM again, independently, bottom-up: ARPU (or average ticket) times the number of target clients per country, summed across the SAM countries.
- The top-down and bottom-up results must triangulate. A wide gap between them is a flag that needs investigating. Do not just take the average of the two.

## Sector-specific structural gate (always identify it)

In each sector, some structural factor limits how many people are really addressable. Find the factor that fits this company's sector and solution, apply it per country, and show the discount. Examples, not exhaustive:

- Fintech, payments, lending: banking access, unbanked share, digital and internet penetration.
- Health: insurance coverage, access to public vs private systems, density of care.
- Education: enrollment in the tier the startup serves (higher education, vocational, K-12).
- Agtech: farm formalization, land access, rural connectivity.
- Work and income tools: share of formal vs informal employment.

The factor has to match what the startup really relies on. If it is genuinely immaterial (some enterprise software), say so in one line and move on. Do not force an irrelevant adjustment.

## Required output, in this order

1. The header (house-style), with the Status line.
2. **One-page summary.** Straight after the header. A short table with the TAM, the SAM and the SOM band (3%, 5%, 8%), each with its figure, unit, year and one line of logic (what is sized, which countries, which filters). Then one line each for the market growth rate, the bottom-up cross-check result, the reality test against the return check, and the two or three open market questions that matter most. Every number and verdict here must match the body exactly.
3. **TAM, SAM and SOM**, each with its number, the method and a cited source. Show the top-down step-down from the macro pool to the company's revenue pool: the macro pool, the startup's actual target, the structural gate, then the revenue pool (served population times price or take rate), with the arithmetic of each step.
4. **SOM band**, 3%, 5% and 8%, with the base case justified.
5. **Bottom-up SOM** next to the top-down one, with a note on whether they triangulate.
6. **Market growth**: the CAGR for the target geography, with its source.
7. **Three structural tailwinds**, each with evidence.
8. **Market conclusion**, 4 to 5 sentences: Is the market large enough? Is the company well placed? Is the timing right? What is the main risk to the market thesis?
9. **Open market questions**, each marked OPEN or RESOLVED (a RESOLVED item names the call or document that resolved it).
10. **Evolution log**: one dated line per version.
11. Sources, then the footer (house-style).

When the analysis is refined (REFINE or DD-REFINEMENT), update the one-page summary together with the body, so the two never disagree.

## Quality bar

Each number leads back to a source or to an assumption you have stated. Cite particular sources: multilateral and development-bank data, central banks and regulators, national statistics offices, sector reports, venture databases. Be specific to the countries in scope: informality, banking penetration, enrollment, coverage and country-by-country regulatory fragmentation must show up wherever they move the numbers. Company figures are claims until another source confirms them.

## DD-refinement stage

At due diligence the analysis is refined, never rebuilt. Read the market analysis from Pre-IC, which sits in deals/[Company]/4-dd/1-market-competitive/, the DD market material in that same folder and the DD call notes in deals/[Company]/4-dd/6-interviews/. Resolve the open questions the evidence answers, update the figures it sharpens (in the summary and the body), mark the Status line as the DD-refined version with its date, and add an Evolution log line. Save it as `YYYY-MM-DD-[company]-market-dd-refined.md` in the same folder. Never overwrite the Pre-IC file.
