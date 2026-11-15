# Monedari: run log

How the sample outputs in this folder were produced.

- **When:** all steps ran in one sitting on 14 November 2026, in Claude Code.
- **Dates:** each step was told the date it would have had in a real process, so the documents line up with the invented timeline of the deal.
- **Editing:** none. The files are what the agents wrote.
- **Web research:** real, with linked sources. The agents were told not to search for Monedari or its people, because they do not exist.

## Steps

| # | Request typed | Agent | Model | Date given | Result |
|---|---|---|---|---|---|
| 1 | Run the pre-screen on Monedari | pre-screen | Sonnet | 2026-09-24 | ADVANCE. No hard filter failed |
| 2 | Run the market analysis on Monedari | market-analysis | Opus | 2026-09-29 | Market sized two ways. Flagged that card payments alone cannot carry the return |
| 3 | Run the competition analysis on Monedari | competition-analysis | Opus | 2026-09-29 | Two of seven moats rated REAL. Crowded market |
| 4 | Run the Pre-IC scorecard on Monedari | scorecard | Opus | 2026-10-01 | 65 out of 100, ADVANCE |
| 5 | Build the impact template for Monedari | impact-template | Sonnet | 2026-10-02 | Stopped at its checkpoint, then wrote the document |

Steps 2 and 3 ran side by side. Step 5 is set to Opus in its agent file. It ran on Sonnet here to save usage.

## The human checkpoint in step 5

The impact template is written for readers outside the deal team. Before writing, the agent stopped and asked four questions, each with its own recommendation:

1. **Terms.** Are the instrument, valuation and ticket as the deck states, and may the lead investor be named?
2. **Disclosure.** Which partner names and company figures may the impact committee see?
3. **Contract figures.** Does any figure refer to a total contract and not to the company's share?
4. **Framing.** The deck says every new shop "enters the formal financial system". The agent noticed that signing up requires a bank account, so the shop owner is already banked. It proposed a smaller, accurate claim and a set of four KPIs.

The reply, given as the deal team: go with the recommendations. Keep the lead investor and partners unnamed. Show the company's figures as company-reported. Use the smaller claim.

The agent then did its research and wrote the document. Its evidence log and its list of open gaps came back in the chat, not in the document, as its method requires.
