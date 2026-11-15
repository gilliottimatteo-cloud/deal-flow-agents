---
name: house-style
description: The single source of truth for how every document in this workspace looks and is named. Covers the document header, headings, the bold lead-in rule, tables, status labels, sources, the footer, and file naming. Load this whenever producing any document, so every deliverable looks the same.
---

# House style: single source of truth for format

Every deliverable is a Markdown file (`.md`). It must read well as plain text and as a rendered page. To change how documents look, change this file and nothing else.

## Document header

Every document opens the same way:

```
# [Company]: [Document type]

| | |
|---|---|
| Stage | [Pre-screen / Pre-IC / Due diligence / Final / IC] |
| Date | [YYYY-MM-DD] |
| Prepared by | [agent name] agent, for Example Ventures |
| Status | [one line, see "Living documents"] |
```

A recommendation or verdict, when the document has one, comes straight after the header, before any analysis.

## Headings

- One `#` title per document.
- `##` for sections, `###` for sub-sections. Do not go deeper.
- Headings are short labels in sentence case, with no numbers unless the skill for that document asks for them.

## Paragraphs: the bold lead-in

Every analysis paragraph opens with a bold lead-in of about 3 to 7 words that states the paragraph's main idea. The rest of the paragraph follows in normal weight.

Example: `**Take rate is the crux.** The deck sizes revenue at 3.5% of volume, but the realized rate is 1.6%, which ...`

The lead-in applies to prose only. It does not apply to table cells, list items, headings or status lines.

## Tables

- Use Markdown tables for anything compared across rows: competitors, scores, scenarios, checklists.
- Keep cells short. Put the explanation in the paragraph below the table.
- Every number carries its unit and its period (USD, per month, 2026).

## Status labels

Write these labels in capitals, exactly as below, so a reader can search for them:

- `PENDING`: the data point is not known yet.
- `INFERRED`: a careful inference from the material, not a stated fact.
- `OPEN`, `PARTIALLY RESOLVED` and `RESOLVED`: the state of a question carried from one stage to the next. A `RESOLVED` item names the call or document that resolved it.
- `PLACEHOLDER`: a stand-in number to be replaced, with the reason.

Ratings and verdicts (for example ADVANCE, STRONG, RED FLAG) are also written in capitals.

One exception: the legal checklist and tracker use their own document-status words (Received, Partial, Pending, N/A), defined in the `legal-dd` skill.

## Sources

- Every figure names its source: the deck page, the call note, the data-room file, or a web link.
- Company claims are marked as claims until another source confirms them.
- Web sources go in a "Sources" section at the end, as Markdown links.
- Never fabricate a number, a source, a quote or a document. Flag what is missing.

## Diagrams

Where a picture is clearer than a table (an org chart, an ownership chain), use a Mermaid code block. It renders on GitHub and stays readable as text.

## Footer

Every document ends with this line:

```
---
Example Ventures | Private and confidential | [YYYY-MM-DD]
```

## File naming

- Format: `YYYY-MM-DD-[company]-[document].md`, all lowercase, words joined by hyphens. Example: `2026-03-09-acme-pre-screen.md`.
- The date is the day the document was created.
- Each skill names the `[document]` part for its own output.

## Living documents

The market analysis and the competition analysis are living documents.

- They keep their creation date in the file name when they are refined in place. The Status line in the header carries the freshness: `Pre-IC, initial, 2026-03-09` and later `Updated 2026-03-20, incorporates [calls]`.
- The due-diligence refinement is saved as a new file next to the first one, with the suffix `-dd-refined`: `2026-04-02-acme-market-dd-refined.md`. The Pre-IC file stays untouched.
- When several versions exist, the `-dd-refined` file is the current one. Among files of the same kind, the latest date wins.

## Housekeeping

- Ignore `.gitkeep` and `README.md` files when checking whether a stage folder holds work.
- After producing a deliverable, delete every temporary or intermediate file from the deal folder. Only inputs and final deliverables remain.

## Writing

- Plain words, short sentences, active voice.
- No em dashes. Use a comma, a colon, or two sentences.
- English, one spelling variant (American) throughout.

If a document needs a format rule that is not covered here, follow the closest rule above. Never improvise a different look.
