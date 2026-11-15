---
name: management-dd
description: The fund's method for management due diligence on a startup, one deeper evaluation of the founders and C-level team, based on DD interviews held for this purpose, reference calls and a review of the cap table. Separate from, and deeper than, the management read in the Pre-IC scorecard. Load this any time someone asks for a management due-diligence assessment.
---

# Management due diligence method

Management DD looks at the PEOPLE: whether this team can execute, whether they are honest, whether the team has no gaps, and whether they are aligned and committed. You write it as a SINGLE document in one pass, handed over after every DD call has taken place. It is not improved step by step.

## Relationship to the Pre-IC scorecard (do not duplicate)

- What the Pre-IC scorecard offers is the EARLY, light read of the team, built only from the deck and the first-call notes (founder background, origin of the idea).
- Management DD is the LATER, DEEPER assessment, built from interviews held one by one with every founder and every C-level executive, reference calls, and a complete review of the cap table.
- Bring over every management concern the Pre-IC scorecard flagged, and test it against the DD evidence.

## Inputs

- Every DD call note in `deals/[Company]/4-dd/6-interviews/`: interviews with the team, references from investors and from clients, expert reviews. Classify each one by reading it, not by its file name.
- The cap table in `4-dd/5-legal/`, plus team and org material in `4-dd/2-management/`.
- The Pre-IC scorecard in `2-preic/`.

## What moves the needle (assess each one explicitly)

The fund's founder preferences and the Founders filter are in `fund-thesis`. Judge the team against them on:

- **Founder type.** First-time or repeat founder, and what the earlier companies became.
- **Founder-market fit.** Years in the industry and depth of domain knowledge. State whether each founder is an insider or an outsider, and why.
- **Full-time commitment.** Whether founders and key leaders work on the company full time.
- **Team completeness.** Whether every key role is filled and actually held. Name the gaps and the key-person risk.
- **Incentives and alignment.** Ownership, vesting, option pool, and whether incentives point at long-term value.
- **Dilution.** Whether the founders still own a meaningful share.
- **Coachability.** Evidence that the founders take input, adapt, and work well with investors.
- **Fundraising record.** Whether credible investors have backed them before.

## Founder and executive background research

Research each founder and key executive independently, to confirm or challenge what they claim in the deck and the calls.

- Use thorough open-web research: earlier companies and senior roles, exits, acquisitions or shutdowns, years in the sector, press, interviews, talks, startup databases, company registries, and reputational signals good or bad.
- When a browser connector is available, also read each person's LinkedIn profile through it and cite it. When none is available, or a profile cannot be opened, say so plainly ("LinkedIn profile could not be retrieved") and continue with open-web research. Never guess or reconstruct a profile.
- Cite every finding to its source. Getting a founder's background wrong does more harm than any other error.
- Separate VERIFIED facts (found and cited), CLAIMED facts (stated by the company, not confirmed) and UNVERIFIED items (could not confirm).
- Flag every CONTRADICTION between a claim and the public record, since these carry strong signal.

Use what you find in the founder-type, founder-market-fit and fundraising judgments, and into the reference synthesis.

## Reference checks (the heart of management DD)

- Synthesize the interview and reference notes for integrity, leadership, resilience, and how the founders handled past failure or conflict.
- Weight references by who has SEEN the founders operate: former colleagues, earlier investors, clients, and anyone who saw them through a hard period. A friendly reference with no working exposure counts least.
- Note where references CORROBORATE or CONTRADICT the founders' claims and the deck.

## Cap-table assessment

- Founder fully diluted ownership, dilution per round, option pool size, investor concentration, inactive founders or large dormant stakes.
- Flag low founder ownership as a red flag.

## Org chart

Include an org chart as a Mermaid diagram (see `house-style`). Show the people in place and the planned hires, styled differently, with reporting lines. Build it only from the materials: never invent a person, a title or an ownership percentage. If a reporting line is unclear, mark it `INFERRED` or leave it out and say so.

## Red flags (separate dealbreakers from watch-items)

- **Dealbreakers:** integrity issues, misrepresentation against the deck or data room, bad references, serious co-founder conflict.
- **Watch-items:** roles not actually held, low founder ownership, key-person dependence, divided commitment.
- Mark each concern carried from the Pre-IC scorecard `OPEN` or `RESOLVED`, naming the call note that resolved it.

## Verdict

- An overall management read: STRONG / ADEQUATE / CONCERN, with the rationale. It goes straight after the document header.
- State how the verdict should inform S1 (Team) of the Final scorecard. The score bands live in the `scoring` skill.

## Output and quality bar

- One Markdown file, `YYYY-MM-DD-[company]-management-dd.md`, in `4-dd/2-management/`, formatted per `house-style`.
- An internal DD working document, rigorous and grounded in evidence. Both the Final scorecard and the IC memo draw on it.
- Every claim cites a specific call note. NEVER fabricate a reference, a quote or an assessment. When a call or data point you need is not there, flag it as `PENDING`.
