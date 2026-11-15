---
name: legal-dd
description: The fund's method for early-stage (SAFE or convertible) legal due diligence on a startup. Detect the corporate structure and subsidiary jurisdictions, assemble a document matrix from jurisdiction memory, map the data room to Received / Partial / Pending / N/A, and write a twin investor-facing checklist and shared tracker. Load any time someone asks for a legal DD, a corporate verification or a document checklist.
---

# Legal due diligence method (early-stage SAFE)

## Scope and gate

Applies ONLY to early-stage rounds on a SAFE or convertible note. A priced round or a secondary is OUT OF SCOPE: stop and explain that it needs a full share-purchase due diligence. Do no work until the instrument is confirmed.

## What the package must prove

1. There is a holding company, and it was validly constituted.
2. The founders own the holding company.
3. The holding company owns the operating subsidiaries: the chain of ownership has no gaps from top to bottom.
4. No encumbrances, debts, liens or litigation exist in the group without being disclosed, and the cap table is clean.

Pitch the depth at what a careful seed investor would request for a convertible ticket: good practice, kept proportionate. Retain the must-haves and leave out whatever is only nice to have.

## Step 1: detect the structure, then CONFIRM with the user

Using the cap table, the instrument and the corporate documents, classify the holding entity and list every subsidiary jurisdiction. Common patterns:

- A Delaware corporation or LLC directly over the local operating companies.
- A Cayman exempted company over the operating companies, sometimes with a Delaware entity in between.
- Other or unknown: treat as a research jurisdiction (Step 3).

RECOMMEND the structure you detected, with every jurisdiction listed, and ASK the user to confirm or correct it BEFORE you build the matrix. A stale memory file or an outdated footprint must not silently drive the package.

## Step 2: assemble the document matrix

One section per entity in the chain, top down: holding company, any intermediate entity, each operating subsidiary, then a group-level section. Build each section from:

- **Entity sets.** For each entity, load `jurisdiction-memory/[jurisdiction].md` from this skill's folder.
- **Group-level set.** Org chart and confirmation that it lists every entity; schedule of all SAFEs and convertibles plus the fully diluted cap table; list of debt and financing plus a no-undisclosed-liabilities confirmation; option pool status.

The standard spine for each subsidiary: existence, legal representative and good standing; tax ID; bylaws as amended and key minutes; share register showing the parent as owner; latest tax return; encumbrance search and no-seizure confirmation; litigation search; IP (assignment and trademark); data-protection registration if it processes personal or credit data; written confirmation of regulatory status if the activity is regulated.

Tag every line essential or optional, so the checklist stays tight.

## Step 3: jurisdiction memory and research

For each jurisdiction with NO memory file:

1. Research the local equivalents across corporate, tax, encumbrance, IP and data, and regulatory and litigation. Cite official sources (company registry, tax authority, IP or data regulator).
2. Put forward the list and apply it on this run.
3. Save it as `jurisdiction-memory/[jurisdiction].md`, following the shape of the existing files and opening with the same "confirm with local counsel" line, so that the following deal can begin from memory.

Never fabricate a local requirement. When research does not settle an item, mark it "to confirm".

## Step 4: map the data room to status

Go through every document in `4-dd/5-legal/` and any legal or corporate files elsewhere in `4-dd/`. Match by file name AND content (a cap-table file can satisfy both the fully diluted cap table and the SAFE schedule). Mark each line:

- **Received**: name the document as the source.
- **Partial**: there is some evidence, but it still needs confirming.
- **Pending**: the company has not provided it.
- **N/A**: give the reason.

Never fabricate a status. If you are not sure, mark it Partial and add a note.

## Step 5: write the twin documents

The checklist and the tracker are TWINS: same sections, same items, same status words.

**Checklist** (for the fund's investors): document header per `house-style`, with IC date, ticket and post-money valuation where known; the confirmed group structure in one line, plus a Mermaid ownership chain; one table per entity (No. / Document / Status / Notes); a Key findings section after the last table (ownership chain confirmed or not, encumbrance position, completeness, gaps by entity, flags); and this caveat: "Working DD tool, not legal advice. To be confirmed by the fund's counsel before close."

**Tracker** (shared working file with the founders): a short header, the group structure in one line, how to use the file, a status count line (Received / Partial / Pending / N/A / Total), then ONE table (No. / Document / Status / Data-room reference / Notes) with a bold entity row opening each section. Notes are neutral descriptions only. No investor commentary, no findings.

## Output and rules

- Save both files in `4-dd/5-legal/` as `-legal-dd-checklist.md` and `-legal-dd-tracker.md`, named and formatted per `house-style`.
- Never fabricate a number, a document, a status or a finding. Flag it instead.
- Delete temporary files, leaving only the two deliverables.
