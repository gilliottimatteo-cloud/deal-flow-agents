---
name: data-room-organizer
description: How to take a data room that was dumped in one place and sort it into the due-diligence sub-folders. Read each file, classify it by domain (market, management, product and tech, financial, legal, interviews, impact), and MOVE it to the right folder, never deleting. Finishes with a report listing each move. Load this any time a data room has to be organized or files have to be sorted into the DD structure.
---

# Data room organizer

Organizing files is your ONLY job: take a data room that was dumped in one place and put each file into the right due-diligence sub-folder. You do NOT analyze or summarize files, and you do NOT alter what is inside them. The task is sorting and nothing more.

## SAFETY RULES: absolute, non-negotiable

- You may MOVE and RENAME, nothing else. NEVER delete a file. Remove a folder ONLY once its contents have been moved out and you have verified it is empty.
- What is inside a file must never be changed.
- Leave every `.gitkeep` and `README.md` file where it is. They are part of the folder template, not the data room.
- When in real doubt, leaving a file where it is beats moving it to the wrong place.
- Report every move (from, to) and every file left in place, so the user can check and correct.

## Where files go

The target folders sit under deals/[Company]/4-dd/:
- **1-market-competitive/**: studies of the market, research on competitors, reports on the industry and sector, market-size data.
- **2-management/**: org charts, team bios and CVs, employment and founder agreements, board materials.
- **3-product-tech/**: product specs, technical architecture, roadmap, demos, go-to-market and sales material, product-related IP.
- **4-financial/**: the financial model, P&L, balance sheet, cash flow, projections, audits, revenue data, unit economics.
- **5-legal/**: every corporate or legal paper: incorporation and corporate structure, the cap table and any equity ledger, SAFEs, convertible notes and term sheets, agreements with shareholders and investors, instructions for wiring and payment, compliance, licenses from regulators, IP filings and trademarks, contracts, litigation.
- **6-interviews/**: call notes and transcripts, expert and third-party reviews, reference-call notes.

Send impact and ESG material UP to deals/[Company]/1-impact/, because impact is a stage with a folder of its own. Never make an impact folder within 4-dd/.

## How to classify

- Start with the file NAME. When the name leaves it unclear, look briefly at the content.
- Classify each FILE by what it is, not by the folder it arrived in. A folder named "Legal" may hold a P&L.
- A data room often comes as nested folders. Put each individual file in its right folder; flattening is fine. If a sub-folder is a coherent set (for example, a year of audited financials), you may move it whole into the right folder.
- BEST GUESS on ambiguous files: place the file in your single best-guess folder and flag it in the report as a guess, with your reasoning. Do not create an unsorted folder. Make the call and report it.
- A file that fits two folders: choose its dominant purpose and note the alternative in the report.
- Cap tables, investment instruments (SAFEs, notes, term sheets), and wiring or payment instructions belong in 5-legal/ ALWAYS, never in 2-management/, although the management analysis reads the cap table later. The physical home is legal; another agent reading it from there is fine.

## Output: a report in the chat, not a file

After sorting, give a concise report directly in the chat:
1. For each of the six folders, and for 1-impact/, the files now in it.
2. A separate "Best guesses and flags" list: every file whose placement was uncertain, with your reasoning.
3. Every file you left where it was, with the reason.

Make it easy to scan, and include nothing beyond these three parts.
