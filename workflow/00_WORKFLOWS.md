# Production workflows

## Governing rule

A plan does not become canon. A draft does not update memory. An audit does not rewrite story facts. Only approved chapter text may promote facts into continuity.

## Load rule

Before every step, read `TASK_LOAD_MATRIX.md` and create an exact path list from its Base production load, Targeted load rules, and task-specific row.

Do not write “relevant files,” “stable canon,” “core files,” or “as needed” in a work artifact. Name the file. A condition may be marked `not applicable` only with a short reason.

## Template rule

Every work artifact begins from its exact template. Do not create an unstructured substitute because a task feels simple.

| Workflow step | Required template |
|---|---|
| Verify source | `templates/SOURCE_NOTE_TEMPLATE.md` |
| Extract transcript | `templates/TRANSCRIPT_EXTRACTION_TEMPLATE.md` |
| Map episode | `templates/EPISODE_MAP_TEMPLATE.md` |
| Episode Canon Delta | `templates/CANON_DELTA_TEMPLATE.md` |
| Plan chapter | `templates/CHAPTER_PLAN_TEMPLATE.md` |
| Chapter mini delta | `templates/CHAPTER_MINI_DELTA_TEMPLATE.md` |
| Scene cards | `templates/SCENE_CARDS_TEMPLATE.md` |
| Combat pre-check | `templates/COMBAT_TRANSLATION_CARD_TEMPLATE.md` |
| Chapter loadout | `templates/CHAPTER_LOADOUT_TEMPLATE.md` |
| Audit | `templates/AUDIT_TEMPLATE.md` |
| Approve chapter | `templates/APPROVED_CHAPTER_RECORD_TEMPLATE.md` |
| New or materially rebuilt character dossier | `templates/CHARACTER_TEMPLATE.md` |
| New or materially rebuilt character-state file | `templates/CHARACTER_STATE_TEMPLATE.md` |
| New event record | `templates/EVENT_TILE_TEMPLATE.md` |

A template is structure, not canon. Fill only sections that the task has evidence to support. Do not turn an empty heading into invented information.

## 1. Verify source

- Template: `templates/SOURCE_NOTE_TEMPLATE.md`.
- Use when: a canon fact, order, consequence, knowledge state or source action is uncertain.
- Read: Base production load; active transcript or VOD; relevant approved chapter; `continuity/CURRENT_STORY_STATE.md`; `continuity/KNOWLEDGE_LEDGER.md`; relevant event tiles; exact character, setting, power, Holmes or combat files that bear on the question.
- May change: only a source note in active work.
- Output: source note with question, source passage, confidence, unresolved point and exact files consulted.
- Must not: create a Canon Delta, decide prose, or treat absence in the transcript as proof that something never happened.

## 2. Extract transcript

- Template: `templates/TRANSCRIPT_EXTRACTION_TEMPLATE.md`.
- Use when: beginning an episode.
- Read: Base production load; active transcript or VOD; `continuity/CURRENT_STORY_STATE.md`; `continuity/RECENT_STORY_CHAIN.md`; last approved chapter; `continuity/C2E1_STARTING_STATE.md` when starting C2E1; exact setting files needed to distinguish source fact from background context.
- May change: only `work/c2eX/TRANSCRIPT_EXTRACTION.md`.
- Output: source obligations, agency owners, information state, causal sequence, tactical intent, later-dependent consequences and table artifacts to discard.
- Must not: write prose, decide Mielle’s exact insertion, or turn later knowledge into episode knowledge.

## 3. Map episode

- Template: `templates/EPISODE_MAP_TEMPLATE.md`.
- Use when: after transcript extraction.
- Read: Base production load; transcript extraction; `CURRENT_STORY_STATE.md`; `RECENT_STORY_CHAIN.md`; `OPEN_THREADS.md`; relevant character dossiers; relationship state; exact setting files; relevant event tiles and knowledge ledger.
- May change: only `work/c2eX/EPISODE_MAP.md`.
- Output: chapter divisions, pressure, source beats, agency lanes, information movement, setting use and chapter consequences.
- Must not: establish a major canon change, make a later revelation available early, or decide a power answer without the relevant power and mechanics files.

## 4. Episode Canon Delta

- Template: `templates/CANON_DELTA_TEMPLATE.md`.
- Use when: after Episode Map and before chapter plans.
- Read: Base production load; transcript extraction; episode map; current continuity; Mielle dossier and current state; relevant character dossiers and relationship state; exact setting files; relevant event tiles and knowledge ledger; `canon/POWER_GUIDE.md` and module(s), `canon/HOLMES_ENGINE.md`, and `canon/COMBAT_RULES.md` whenever Mielle’s intervention can touch them.
- May change: only `work/c2eX/CANON_DELTA.md`.
- Output: explicit changes caused by Mielle, preserved source beats, protected canon agency, knowledge effects, power/mechanics constraints and consequences for later promotion.
- Must not: replace a canon character’s required agency without explicit permission, or use undefined power mechanics as a bridge over an unresolved canon beat.

## 5. Plan chapter

- Template: `templates/CHAPTER_PLAN_TEMPLATE.md`.
- Use when: before a chapter.
- Read: Base production load; episode map; episode Canon Delta; transcript extraction slice for the chapter; current continuity; recent chain; open threads; last approved chapter; relevant character, relationship, setting, event, knowledge, power, Holmes and combat files.
- May change: only the chapter plan.
- Output: chapter contract, source slice, causality, required decisions, information that remains uncertain, agency owners, required files for the next step and end state.
- Must not: write final dialogue, update continuity, force a fixed turn order or silently narrow/expand the episode Canon Delta.

## 6. Chapter mini delta

- Template: `templates/CHAPTER_MINI_DELTA_TEMPLATE.md`.
- Use when: immediately after every chapter plan and before scene cards.
- Read: Base production load; chapter plan; episode Canon Delta; episode map; transcript extraction slice; current continuity; every exact file governing Mielle’s planned intervention, including applicable character, relationship, setting, knowledge, power, Holmes and combat files.
- May change: only `work/c2eX/chapters/XX_CHAPTER_MINI_DELTA.md`.
- Output: the chapter-specific application of the episode Canon Delta: Mielle’s allowed actions, prohibited shortcuts, protected agency, information created or withheld, mechanics/setting constraints, and approval-gated continuity consequences.
- Must not: create a new episode-level change. If it needs one, return to Episode Canon Delta.

## 7. Create scene cards and canon response pass

- Template: `templates/SCENE_CARDS_TEMPLATE.md`.
- Use when: a chapter includes relevant interaction among Mielle and canon characters.
- Read: Base production load; chapter plan; chapter mini delta; relevant character dossiers and current states; relationship state; knowledge ledger; relevant event tiles; exact setting files; Holmes Engine whenever an interpretation or inference matters.
- May change: only scene cards.
- Output: each person’s knowledge, interpretation, want, natural contact point, independent action and conclusion boundary; Mielle’s protected agency.
- Must not: require every present character to speak, make anyone know reader-only facts, or make dialogue perform the job of an author summary.

## 8. Combat pre-check

- Template: `templates/COMBAT_TRANSLATION_CARD_TEMPLATE.md`.
- Use when: combat, pursuit, physical threat, hostile magic, meaningful gear use or consequential power use occurs.
- Read: Base production load; chapter plan; chapter mini delta; scene cards; relevant transcript slice; Mielle dossier and state; relevant combatant dossiers and states; Combat Rules; exact Power Guide modules; Holmes Engine when the tactic depends on reading; setting and terrain files.
- May change: only pre-check or combat translation card.
- Output: board, objectives, source obligations, pressure waves, tactical truth, hostile-effect review, agency lanes, Mielle’s allowed intervention and aftermath.
- Must not: produce a turn list, use Mielle to solve every threat, ignore a defense/mechanic because the source result is desired, or choose a power result before its source mechanics are read.

## 9. Chapter loadout

- Template: `templates/CHAPTER_LOADOUT_TEMPLATE.md`.
- Use when: immediately before prose.
- Read: Base production load; chapter plan; chapter mini delta; scene cards; combat pre-check if any; every exact file required under the Matrix headings; `canon/MIELLE_PROSE_STYLE_GUIDE.md`; `canon/ANTI_AI_PROSE_EDITING_FILTER.md`.
- May change: only chapter loadout.
- Output: exact files and sections required for the draft, grouped under source/adaptation, continuity, character/relationship, setting/faction, power/Holmes/combat, prose/editing and active chapter artifacts.
- Must not: summarize canon into new facts, leave a vague conditional reference, or replace reading listed files with a summary.

## 10. Draft

- Template: no template. Drafts are chapter-specific prose files created only from a completed Chapter Loadout.
- Use when: a complete chapter loadout exists.
- Read: every file named in the loadout; Anti-AI pre-draft guard.
- May change: draft only.
- Output: `XX_DRAFT.md` and a completed pre-draft-guard receipt in the loadout or audit record.
- Must not: update continuity, alter canon without delta, give characters unsupported knowledge, copy transcript dialogue as prose, or use the Anti-AI filter to invent texture, stakes, dialogue or scene events.

## 11. Audit

- Template: `templates/AUDIT_TEMPLATE.md`.
- Use when: after a complete draft.
- Read: Base production load; draft; loadout; chapter plan; chapter mini delta; scene cards; combat pre-check if any; transcript extraction; episode map; episode Canon Delta; relevant canon, continuity, setting, character, relationship, knowledge, power, Holmes, combat, prose and Anti-AI files.
- May change: audit only.
- Output: issue list with severity, evidence, governing source and required correction.
- Must not: invent facts, promote memory, silently revise story decisions, or call a problem style-only when its correction changes canon, agency, POV, relationship framing, knowledge control or mechanics.

## 12. Revise

- Template: no separate template. Revise the existing draft and audit record, then run the Anti-AI Silent Edit.
- Use when: audit identifies a correction.
- Read: Base production load; draft; audit; every source named by an issue; chapter loadout; Anti-AI filter.
- May change: revised draft and audit resolution status.
- Output: new draft version, resolved audit and completed Anti-AI Silent Edit receipt.
- Must not: introduce a canon change without returning to the needed planning document, or continue polishing once the filter’s stop condition is met.

## 13. Approve chapter

- Template: `templates/APPROVED_CHAPTER_RECORD_TEMPLATE.md`.
- Use when: the user approves the final draft.
- Read: final draft; closed audit; chapter plan; chapter mini delta.
- May change: `chapters/approved/` and project state.
- Output: approved chapter record.
- Must not: promote continuity before approval.

## 14. Promote memory

- Templates: `templates/CHARACTER_STATE_TEMPLATE.md` for a new or rebuilt character state; `templates/EVENT_TILE_TEMPLATE.md` for each new event tile; preserve the existing structure of `continuity/relationships/RELATIONSHIP_STATE.md` rather than creating a parallel relationship template.
- Use when: only after approval.
- Read: approved chapter; final audit; chapter mini delta; episode Canon Delta; current continuity; affected character states; relationship state; event tiles; knowledge ledger; open threads.
- May change: current story state, recent chain, event index, event tiles, knowledge ledger, affected character states, relationship state, open threads and project state.
- Output: continuity ready for the next chapter.
- Must not: record an unused plan, omitted scene idea or author intention as a fact.

## 15. Update permanent rule or decision

- Template: use `templates/CHARACTER_TEMPLATE.md` only when a new or materially rebuilt character dossier is required; use `templates/CHARACTER_STATE_TEMPLATE.md` and `templates/EVENT_TILE_TEMPLATE.md` under the same rule for a new state or event record. Otherwise, update the owning file directly.
- Use when: the user makes a new permanent decision about character, setting, adaptation, combat, power or production.
- Read: Base production load; authority map; the likely owning file; all files that point to that owner where a reference may become stale.
- May change: the single owner file and necessary references.
- Output: updated owner and a note of current-work impact when relevant.
- Must not: duplicate a rule in several files or retroactively alter approved chapters without explicit revision.
