---
name: impact-template
description: The method for producing the impact template, a partner-facing document written FOR the fund's impact committee, whose members are always seeing the company for the first time. At headline level, and without operating specifics, it covers the business model, the opportunity, why this is a good and growing business, and how it matches the fund's impact lens. The KPIs are derived from the outcomes that the impact lens calls for. The evidence log and the open gaps go in the chat, never in the document. Load this any time someone asks for an impact template.
---

# Impact template method

The impact template is a PARTNER-FACING deliverable for the fund's impact committee. When the committee reads it, that is ALWAYS its first encounter with the company. It is addressed to that reader and must be send-ready. It is NOT an investment memo, an audit of the company, or a scorecard.

The impact lens (the five dimensions) and the number of impact KPIs live in `fund-thesis`. Format and file naming live in `house-style`. Do not restate either here or in the document's method.

## 0. What the document must do, and nothing else

Someone new to the company should reach the end with a clear grasp of four points:

1. **The business model:** what the company does and where its money comes from.
2. **The opportunity:** how big the problem is and why the timing is right.
3. **Why it is a good business that is growing:** headline-level traction (see section 1).
4. **Why it fits the fund's impact lens:** who is helped, what changes for them, and the KPIs that will show it.

Every sentence serves one of these four. If it does not, it goes to the IC memo or the due diligence, not to this document.

## 1. The altitude rule (the most important rule)

- **Test every fact.** Does it help a first-time reader understand the model, the opportunity, the growth or the fit? Remove any detail that leaves that understanding unchanged.
- **Traction is always shown, at headline level.** Scale, growth (current revenue plus what the company aims to reach over the next two years, marked as the company's own targets rather than projections by the fund), one or two genuine proofs that the model works, and overall momentum (how many partners, and in one sentence how many programs sit at each stage). After a single reading, a committee member should be able to repeat it.
- **Not for this document:** the terms and values of contracts, signing dates, how concentrated revenue is, milestone plans and downside plans, round mechanics outside the key-data cells, plans for hiring, technical flows, details of the security architecture and of certifications, roadmap components, program-by-program status, valuation commentary.
- **Name a partner only when the name changes belief.** Use the name if it shifts what the reader thinks about reach or credibility. If the partner network is the company's main strength, the names belong to the story, each one with its true status (live, signed or in negotiation). In every other case, give a total instead.
- **Keep technical and safeguard detail out.** No more than one plain sentence saying who answers to the end user and how their data is kept safe, and nothing on architecture.
- **No dates that can move.** Unless the company has made a public commitment, write "in negotiation" or "planned".

## 2. Say it once

- Every proof lives in ONE place only: the mechanism and the economics go in the business model section; people and outcomes in the impact-lens section; what is live or pending in the status section; scale and plan in the scaling section. No other section repeats it; a brief pointer is the most it gets.
- Self-check: a figure, program or example may appear in two places at most.
- ONE human story, with real data, and it is told only once.
- Show, do not certify. Do not use phrases such as "meets the criteria", "contributes to each outcome" or "measures everything" about the company. Let the evidence make that case.
- One hedge per claim. A status (pending, unsigned, estimated) is given in one spot, not repeated after each claim.

## 3. Reader rule: write for the committee, not for the deal team

- Plain, simple, constructive language that a reader outside the fund understands without context. Consistent names for countries, companies and people.
- NO internal artifacts: no scorecard dimensions or scores, no "Pre-IC", "data room", "DD tracker", "unvalidated", "the fund could not confirm", no internal file names, no internal deliberation, no internal frameworks or jargon.
- Company facts are stated plainly, with no source label; their sources go in the chat evidence log (section 8). This is the one exception to the house-style rule on sourcing, because of the partner-facing tier. EXTERNAL sources (studies, regulators, official statistics, multilateral bodies) get a citation, numbered by the order in which they first appear, and each is listed one time in the Sources section at the end. Cite only what the text uses.
- The company is the SUBJECT, and it is the one acting. Factual and optimistic; the fund's voice is never self-critical.
- No risk appears on its own: each one comes with the way it is managed. There is no separate risk or mission-drift section, and no self-scoring.
- Honest, but not in the language of an audit: never claim more than is true ("interested", not "committed"; "plans", not "will"). A company figure that cannot be verified is left out, unless the argument depends on it and it is marked as the company's own.

## 4. Format: fill the template, do not improvise

- Copy `template.md` from this skill folder to the output path and fill it. Keep its section order and table designs. Change the content, never the structure.
- Replace every bracketed guidance line. None may survive in the finished document.
- As short as it can be while delivering the four things in section 0. No audit-style prose, and no status columns beyond the single status table.

## 5. What each section carries

The template holds the slots. The judgment behind them:

- **Key data table.** Facts, not paragraphs. The traction cell is headline numbers. The round and valuation cells describe the fund's ACTUAL instrument (see section 7).
- **The problem and why it matters.** This section carries the weight of the document. Open with the structural problem, then regional evidence across several countries of the fund's geography (a comparison table, with one country only as an example), the delivery gap, who is hit hardest, and, in brief, the regulation: what falls under regulation, and which activities do or do not require the company to hold a license. Thoroughly researched with fresh web sources, and cited.
- **Relevance of the company to the problem.** What the company is, how it takes the problem away (in plain words), a few lines on the value it offers each side, and one proof of scale. Do not list programs or partners.
- **Business model.** Who the sides of the model are, where the revenue comes from, ONE example that makes the unit economics visible, and the main risks, each paired with its mitigation in two or three sentences.
- **Alignment with the fund's impact lens.** Open with the human outcome in plain words (what people now have that they lacked before). Then walk the five dimensions of the impact lens in `fund-thesis`, one table row each, saying HOW the company drives the change, in active voice. The Risk row names the risk and how it is managed. Where the fit has a gap, say so plainly and give the route through which the company still fits. End with the KPI table.
- **Where the company stands today (optional).** Either a brief overall status, or a single small table showing what is live, implementing and contracting. Partner names only per section 1.
- **Strategy to scale impact after the investment.** From the company's latest strategy material: how it grows and what the round funds; its potential (revenue today, company targets for two years, scale); how it wins customers and why each new one is cheaper to add; where it grows next, each item with its risk and mitigation. No KPI numbers here.
- **Sources.** External only.

## 6. Impact KPIs: derived from the outcomes the impact lens asks for

- Start from the outcome in the What and Who dimensions. For each outcome, ask what the company can measure from its own data. Every KPI must trace to an outcome; drop any that cannot.
- Company efficiency or operating metrics (processing time, cost per unit, service levels) do not belong here, unless they ARE the outcome (for example affordability, when affordability is the change the end user gets).
- Use the number of KPIs set in `fund-thesis`. Each KPI is stated once, in the KPI table, with at most two measures. Baselines still to be established are stated plainly. Never refer to KPI numbers elsewhere in the document, because the references break when the table changes.
- A channel serving people on the supply side earns a KPI only when it is real, can be measured, and is linked to the model.

## 7. Before writing: confirm with the team

Recommend, then confirm. Do not draft until the team answers:

- The instrument the fund is really using, plus the valuation basis, the ticket and the co-investors. These can differ from what the company's documents say (a bridge in place of the round that was announced, for example). Present co-investors as additionality ("already an investor", "interested"), never overclaiming.
- Which partner names and which figures may be shown to the impact committee.
- For each contract figure, whose share it is (the whole contract, or only the company's portion when a prime contractor is involved). If documents disagree, go with what the team says, drop the disputed figure, and note the disagreement in your chat report.

## 8. Evidence log and open gaps: IN THE CHAT, not in the document

An INTERNAL EVIDENCE LOG MUST be part of the final chat report, and it must be kept out of the document:

- A table: claim or figure | value | source (file and page, call note, or link) | status, one of (independently sourced / company-provided / unaudited / conflicting / calculated by us) | where used. Include all company figures and all numbers the fund worked out itself.
- Open gaps: whatever is missing or not confirmed, why the impact committee would care, and who could supply it.
- Places where documents disagree, and the decisions still waiting on the team.
- What was deliberately left out of the document, so the team can judge whether it should be disclosed somewhere else.

The document itself may carry no more than one or two bold `PENDING` markers, and only where a conclusion depends on a single missing datum.

## 9. The committee's recurring concerns: answer them inside the narrative, briefly

1. **Who is served and how vulnerable they are**, and the realistic counterfactual.
2. **Productive, not discretionary:** livelihoods, health or productive activity, not consumption.
3. **Real and mechanical:** revenue growth necessarily extends the impact.
4. **Do no harm:** in a single plain line, who is responsible and who carries the risk.
5. **Additionality:** the capital and specialist co-investors the round crowds in.
6. **Measurement honesty:** a constructive statement of what the KPIs will track.

## 10. Working process

1. Verify the prerequisites (market analysis and Pre-IC scorecard). If either is missing, warn and ask; do not block.
2. Read the company's material and its latest strategy documents. Do the web research for the problem section.
3. Confirm section 7 with the team.
4. Copy the template to `deals/[Company]/1-impact/` and fill it. If the user changed an earlier version, work in THEIR file and keep all of their changes; do not bring back anything they removed.
5. Final checks before reporting:
   - the altitude rule and "say it once" pass (sections 1 and 2);
   - proofreading: spelling, tense, grammar, one English variant, consistent names;
   - every cross-reference still exists, and no KPI number appears outside the KPI table;
   - the header date is today;
   - the file exists at the right path with the right name, no bracketed guidance or internal label remains, and the citation numbers match the Sources list.
6. Report in chat: a summary, the evidence log and open gaps (section 8), and the decisions the team must make.

## 11. Discipline

- The problem section gets deep research with citations; every other section stays at headline level.
- NEVER fabricate a statistic, a source or a metric. Anything you cannot confirm stays out of the document and goes on the list in the chat.
- Talk about impact through data, not storytelling. The commercial case leads; impact follows from the model, and never the other way around.

## Output

- One Markdown file per `house-style`, in English unless the team asks otherwise.
- Name: `YYYY-MM-DD-[company]-impact-template.md` in `deals/[Company]/1-impact/`. Where a version already exists, do what the team says about versions (by default, update the existing file).
