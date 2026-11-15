# How to modify this workspace (read before changing any agent or skill)

If you are an AI assistant: READ THIS ENTIRE FILE before editing, creating or deleting anything in this workspace. It holds the conventions that keep the system coherent. Follow them even when a local change seems fine in isolation.

## What this workspace is

An investment-process system: a set of AI specialists ("agents") and their playbooks ("skills") that take a deal from the first deck to the investment committee memo and the legal checks. It runs in Claude Code.

## The layers (where things live)

- `CLAUDE.md` (root) is the ROUTER: a thin map of which agent handles which request, plus the non-negotiable rules. Keep it short. It holds no step-by-step method.
- `.claude/agents/*.md` are the AGENTS (the workers). Each has YAML frontmatter (name, description, model) and then plain-English instructions: what it reads, what it produces, where it saves, and its prerequisite checks. Agents are short cover sheets. The detailed method lives in skills.
- `.claude/skills/*/SKILL.md` are the SKILLS (the playbooks): the deep, reusable method an agent loads on demand. Detailed logic and judgment live here. A skill folder may also hold the template its agent fills.
- `deals/[Company]/` is work product, copied from `deals/_TEMPLATE/`.

## Single source of truth (critical)

- The `fund-thesis` skill is the ONLY home for fund facts: ticket sizes, filters, the scoring dimensions with their weights and thresholds, the return check, the impact lens. To change a number or a filter, change it THERE, not in the agents or skills that refer to it.
- The `house-style` skill is the ONLY home for format: the document header, headings, labels, footer, file naming. Change formatting THERE.
- Never duplicate a fact across files. If two files state the same number, they will drift apart. Point everything at the single source.

## The editing rules (how to change things safely)

1. EDIT, do not rebuild. To change a file, edit the specific lines. Do not regenerate a whole file for a small change: you risk losing other content. Rebuild only if a file's structure is fundamentally wrong.
2. VERIFY after multi-file changes. If you change a folder path, a name or a number that appears in several files, SEARCH all of `.claude/agents/` and `.claude/skills/` afterward for stale references and report the matches.
3. NEVER fabricate. Agents and skills must flag missing data and never invent a number, source, document or finding. Preserve this in any edit.
4. RECOMMEND-THEN-CONFIRM for judgment steps. Several agents pause to recommend something (a placeholder multiple, a detected legal structure, the facts to show a partner) and ask the user before applying it. Preserve these human checkpoints. Do not make them automatic.
5. PREREQUISITE GUARDS are deliberate. Agents check that upstream work exists before running and stop if it is missing. Keep these: they protect against running steps out of order. Legal DD additionally requires an explicit "start" command and the IC memo. Never auto-run it.
6. STOP between stages. A completed step is never repeated. Market and competition are refined at DD, not rebuilt. The scorecard runs twice (Pre-IC, then Final) by design.
7. AGENT and SKILL names differ on purpose. The `scorecard` agent uses the `scoring` skill; `market-analysis` uses `market`; `competition-analysis` uses `competition`. They link by reference inside the agent, not by matching names. Do not rename them to "fix" this.

## How to make a change

- To add an agent: create `.claude/agents/[name].md` with frontmatter and body, following an existing agent as the pattern (for example `management-dd.md`). Add a row to the routing table in `CLAUDE.md` and to the step table in `HOW-TO.md`.
- To add a skill: create `.claude/skills/[name]/SKILL.md` following the shape of an existing skill, and point the relevant agent at it.
- After ANY change to an agent or skill file, reload so the change is picked up: start a new Claude Code session, or in VS Code run "Developer: Reload Window".
- Keep `CLAUDE.md` and `HOW-TO.md` in sync with reality whenever you add or change an agent.

## When in doubt

Match the conventions of the existing files: read a similar agent and skill first and mirror their structure, tone, prerequisite checks, and their references to `fund-thesis` and `house-style`. Ask the user before doing anything destructive (deleting, renaming across files, or rebuilding).
