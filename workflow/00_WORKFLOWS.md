# Production workflows

## Governing rule

A plan does not become canon. A draft does not update memory. An audit does not rewrite story facts. Only approved chapter text may promote facts into continuity.

## Load rule

Before every step, read `TASK_LOAD_MATRIX.md` and create an exact path list from its Base production load, Targeted load rules, and task-specific row.

Do not write “relevant files,” “stable canon,” “core files,” or “as needed” in a work artifact. Name the file. A condition may be marked `not applicable` only with a short reason.

If a scene contains combat, pursuit, physical threat, power use, power non-use, gear use, injury, no-hit result, evasion, resistance or tactical prediction, the exact Power Guide module(s), Combat Rules and Holmes Engine must be read before any prose or revision touches that scene.

If Mielle appears, speaks, decides, reacts, is viewed by someone else or is physically affected, read her dossier and current state before writing her. Apply her current knowledge, gear, personality, voice, drawbacks, constraints/geasa where present and public presentation.

If any canon cast member appears, speaks, reacts, fights, witnesses, withholds or is used as a scene presence, read that character's dossier before writing or revising that line or action. Do not write cast voices from memory or from a prior draft alone.

## Decision-to-authority rule

An exact path list proves only that files were opened. It does not prove that their rules were reconciled.

Before drafting, the Chapter Loadout must contain a completed decision-to-authority check. It covers every planned decision, material fact, visible reaction, item state, power use or deliberate non-use that could be governed by more than one source. Every row must name:

1. the planned fact or decision;
2. the source or planning obligation;
3. the governing permanent rule or mechanic;
4. the continuity and witness limit;
5. what prose may show; and
6. what prose must not imply.

A conflict or missing authority blocks prose. Return it to the owner: source note, Arc Map, Episode Canon Delta, chapter plan, mini delta, permanent canon file or continuity record. Do not solve it by guessing in the draft.

## Anti-AI application rule

An exact Anti-AI path or checked read box proves only that the filter was opened. It does not prove that the draft was inspected or revised under it.

Before prose, the Chapter Loadout and pre-draft guard must identify chapter-specific failure pressure. Each risk must name:

1. the scene trigger;
2. the fact, voice, uncertainty, awkwardness or causal detail that must be protected;
3. the visible pattern the later audit must inspect; and
4. whether an additional targeted Anti-AI cluster is justified.

After prose exists, every complete-draft audit must contain the evidence-based Anti-AI application receipt from `templates/AUDIT_TEMPLATE.md`. The receipt must:

- return to every risk named by the pre-draft guard;
- check the seven universal clusters: explanatory aftertaste, specificity regression, mechanical symmetry and template cadence, flattened dialogue, false certainty and invented consensus, coverage compulsion and planning leakage, and generation residue;
- select only additional targeted clusters justified by the chapter rather than filling all clusters automatically;
- cite local evidence or the exact pattern inspected;
- group repeated symptoms by root cause and use representative examples rather than an exhaustive word inventory;
- record the smallest safe correction or a specific leave-alone reason;
- identify protected material that the correction must not damage;
- compare versions after substantial revision or Silent Edit; and
- reread changed paragraphs for new loss of voice, specificity, causality, uncertainty or character ownership.

`Anti-AI: pass`, `filter read`, `checked`, `complete`, `no issues`, or equivalent unsupported wording is invalid. A universal cluster marked `not present` without local evidence or a named inspected pattern is also invalid.

A missing, generic or incomplete receipt blocks audit closure and chapter approval. A user waiver applies only when the user explicitly names this Anti-AI receipt requirement for that chapter. General approval of the prose does not silently waive it.

## Template rule

Every work artifact begins from its exact template. Do not create an unstructured substitute because a task feels simple.

| Workflow step | Required template |
|---|---|
| Verify source | `templates/SOURCE_NOTE_TEMPLATE.md` |
| Extract transcript | `templates/TRANSCRIPT_EXTRACTION_TEMPLATE.md` |
| Map arc | `templates/ARC_MAP_TEMPLATE.md` |
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
| Relationship-state controller rebuild | `templates/RELATIONSHIP_STATE_TEMPLATE.md` |
| New event record | `templates/EVENT_TILE_TEMPLATE.md` |

A template is structure, not canon. Fill only sections that the task has evidence to support. Do not turn an empty heading into invented information.

## 1. Verify source

- Template: `templates/SOURCE_NOTE_TEMPLATE.md`.
- Use when: a canon fact, order, consequence, knowledge state or source action is uncertain.
- Read: Base production load; active transcript or VOD; relevant approved chapter; `continuity/CURRENT_STORY_STATE.md`; `continuity/KNOWLEDGE_LEDGER.md`; `continuity/EVENT_INDEX.md`; relevant event tiles; `continuity/C2E1_STARTING_STATE.md` when verifying C2E1 or its prologue; exact character, setting, power, Holmes or combat files that bear on the question.
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

## 3. Map arc

- Template: `templates/ARC_MAP_TEMPLATE.md`.
- Use when: before the first Episode Map of a new arc. Reuse the same Arc Map for later episodes in that arc and amend it only when verified source or approved continuity changes the controlling cross-episode picture.
- Read: Base production load; transcript extractions and source notes for the proposed episode range; current continuity; recent chain; open threads; `continuity/EVENT_INDEX.md`; relevant event tiles and knowledge ledger; relevant approved chapters; relevant character dossiers and relationship state; exact setting files; Power Guide, Holmes Engine and Combat Rules when a cross-episode constraint depends on capability, inference, combat or deliberate non-use.
- May change: only `work/arcs/<ARC_ID>/ARC_MAP.md`.
- Output: arc scope, entry and exit state, cross-episode causal chain, delayed revelations, agency ownership, material continuity, Mielle intervention range, episode functions and arc-level change flags that later Episode Canon Deltas must resolve.
- Must not: divide chapters, write scenes or dialogue, decide exact power use, replace an Episode Map, create a canon change, or treat a provisional episode range as confirmed source fact.
- Transition: Episode Maps completed before this step existed remain valid. Create the controlling Arc Map before materially rebuilding one of those Episode Maps or before mapping the next episode in the arc.

## 4. Map episode

- Template: `templates/EPISODE_MAP_TEMPLATE.md`.
- Use when: after transcript extraction and after the controlling Arc Map exists.
- Read: Base production load; controlling Arc Map; transcript extraction; `continuity/CURRENT_STORY_STATE.md`; `continuity/RECENT_STORY_CHAIN.md`; `continuity/OPEN_THREADS.md`; `continuity/EVENT_INDEX.md`; `continuity/C2E1_STARTING_STATE.md` for C2E1; relevant character dossiers; `canon/relationships/RELATIONSHIP_STATE.md`; exact setting files; relevant event tiles and knowledge ledger.
- May change: only `work/c2eX/EPISODE_MAP.md`.
- Output: chapter divisions, pressure, source beats, agency lanes, information movement, setting use and chapter consequences within the function assigned by the Arc Map.
- Must not: establish a major canon change, contradict the Arc Map without returning to it, make a later revelation available early, or decide a power answer without the relevant power and mechanics files.

## 5. Episode Canon Delta

- Template: `templates/CANON_DELTA_TEMPLATE.md`.
- Use when: after Episode Map and before chapter plans.
- Read: Base production load; controlling Arc Map; transcript extraction; episode map; current continuity; `continuity/EVENT_INDEX.md`; `continuity/C2E1_STARTING_STATE.md` for C2E1; Mielle dossier and current state; relevant character dossiers and relationship state; relevant event tiles and knowledge ledger; exact setting files; `canon/POWER_GUIDE.md` and module(s), `canon/HOLMES_ENGINE.md`, and `canon/COMBAT_RULES.md` whenever Mielle’s intervention can touch them.
- May change: only `work/c2eX/CANON_DELTA.md`.
- Output: explicit changes caused by Mielle, preserved source beats, honest outcome review, protected canon agency, knowledge effects, power/mechanics constraints and consequences for later promotion. It must resolve any Arc Map change flag that reaches this episode.
- Must not: replace a canon character’s required agency without explicit permission; use undefined power mechanics as a bridge over an unresolved canon beat; preserve a source outcome by inertia when Mielle’s established position and mechanics would causally change it; or silently alter the controlling Arc Map.

## 6. Plan chapter

- Template: `templates/CHAPTER_PLAN_TEMPLATE.md`.
- Use when: before a chapter.
- Read: Base production load; controlling Arc Map; episode map; episode Canon Delta; transcript extraction slice for the chapter; current continuity; recent chain; open threads; `continuity/EVENT_INDEX.md`; last approved chapter; `continuity/C2E1_STARTING_STATE.md` for C2E1 chapters; relevant character, relationship, setting, event, knowledge, power, Holmes and combat files.
- May change: only the chapter plan.
- Output: chapter contract, POV, source slice, causality, decision points, required decisions, social and knowledge boundaries, information that remains uncertain, agency owners, carry-forward facts, required files for the next step and end state.
- Must not: write final dialogue, update continuity, force a fixed turn order or silently narrow/expand the Arc Map or Episode Canon Delta.

## 7. Chapter mini delta

- Template: `templates/CHAPTER_MINI_DELTA_TEMPLATE.md`.
- Use when: immediately after every chapter plan and before scene cards.
- Read: Base production load; chapter plan; controlling Arc Map; episode Canon Delta; episode map; transcript extraction slice; current continuity; `continuity/C2E1_STARTING_STATE.md` for C2E1 chapters; `continuity/EVENT_INDEX.md` when earlier events can constrain intervention or knowledge; every exact file governing Mielle’s planned intervention, including applicable character, relationship, setting, knowledge, power, Holmes and combat files.
- May change: only `work/c2eX/chapters/XX_CHAPTER_MINI_DELTA.md`.
- Output: the chapter-specific application of the Episode Canon Delta: Mielle’s allowed actions, prohibited shortcuts, protected agency, information created or withheld, mechanics/setting/social constraints, and approval-gated continuity consequences.
- Must not: create a new episode-level or arc-level change. If it needs one, return to the Episode Canon Delta or Arc Map.

## 8. Create scene cards and canon response pass

- Template: `templates/SCENE_CARDS_TEMPLATE.md`.
- Use when: a chapter includes relevant interaction among Mielle and canon characters.
- Read: Base production load; chapter plan; chapter mini delta; controlling Arc Map when cross-episode knowledge, obligation or delayed consequence constrains the scene; `continuity/C2E1_STARTING_STATE.md` for C2E1 scenes; relevant character dossiers and current states; `canon/relationships/RELATIONSHIP_STATE.md`; `continuity/KNOWLEDGE_LEDGER.md`; `continuity/EVENT_INDEX.md`; relevant event tiles; exact setting files; Holmes Engine whenever an interpretation or inference matters.
- May change: only scene cards.
- Output: each person’s knowledge, interpretation, want, natural contact point, independent action and conclusion boundary; Mielle’s protected agency; event-tile and knowledge check.
- Must not: require every present character to speak, make anyone know reader-only facts, press a subject that an event tile or character state leaves unresolved without a meaningful new trigger, or make dialogue perform the job of an author summary.

## 9. Combat pre-check

- Template: `templates/COMBAT_TRANSLATION_CARD_TEMPLATE.md`.
- Use when: combat, pursuit, physical threat, hostile magic, meaningful gear use, consequential power use, injury, evasion, no-hit result or damage result occurs.
- Read: Base production load; chapter plan; chapter mini delta; scene cards; relevant transcript slice; Mielle dossier and state; relevant combatant dossiers and states; Combat Rules; Power Guide and exact module(s) for every power, gear item, defense, prediction, evasion, damage, injury or non-use; Holmes Engine when the tactic depends on reading; setting and terrain files.
- May change: only pre-check or combat translation card.
- Output: board, objectives, source obligations, pressure waves, tactical truth, hostile-effect review, agency lanes, Mielle’s allowed intervention, exact mechanics read receipt and aftermath.
- Must not: produce a turn list, use Mielle to solve every threat, ignore a defense/mechanic because the source result is desired, or choose a power result before its source mechanics are read.

## 10. Chapter loadout

- Template: `templates/CHAPTER_LOADOUT_TEMPLATE.md`.
- Use when: immediately before prose.
- Read: Base production load; controlling Arc Map; chapter plan; chapter mini delta; scene cards; combat pre-check if any; `continuity/C2E1_STARTING_STATE.md` for C2E1 chapters; `continuity/EVENT_INDEX.md`; every exact file required under the Matrix headings; `canon/prose/PROSE_SYSTEM.md`; `canon/prose/MIELLE_PROSE_STYLE_GUIDE.md`; `canon/prose/MIELLE_VOICE_GUIDE.md`; `canon/prose/CHAPTER_PROSE_AND_CHARACTER_VOICE_PASS.md`; `canon/prose/ANTI_AI_PROSE_EDITING_FILTER.md`.
- May change: only chapter loadout.
- Output: exact paths and sections required for draft, grouped under source/adaptation, continuity, character/relationship, setting/faction, power/Holmes/combat, prose/editing and active chapter artifacts; a passing decision-to-authority check for every conflict-prone chapter fact; and an Anti-AI pressure map that names chapter-specific risks, protected material, universal clusters and justified targeted clusters for the post-draft audit.
- Must not: summarize canon into new facts, leave a vague conditional reference, replace reading listed files with a summary, let a conflict-prone fact reach prose without a completed authority row, or use generic Anti-AI warnings without a scene trigger and audit target.

## 11. Draft

- Template: no template. Drafts are chapter-specific prose files created only from a completed Chapter Loadout.
- Use when: a complete chapter loadout exists and every decision-to-authority row passes.
- Read: every file named in the loadout; Anti-AI pre-draft guard.
- Draft construction order:
  1. **Factual scene pass.** Read source/adaptation, continuity and chapter artifacts. Build the scene’s causal sequence, agency, material facts, knowledge boundaries and ending. This may be skeletal prose, but it must already obey the decision-to-authority check.
  2. **Character pass.** Read Mielle’s dossier/state, each decision-relevant character dossier/state, relationship state, ledger and event tiles one at a time. Correct action, dialogue, reaction, social distance, first-impression treatment and knowledge before treating sentences as final.
  3. **Mechanics and inference pass.** Read Power Guide, exact modules, Holmes Engine, Combat Rules and pre-check one at a time. Correct power use, deliberate non-use, possession, physical consequences, inference, evasion, resistance, injury/no-hit result and threat boundaries. A conflict returns to planning; it is not smoothed over in prose.
  4. **Prose pass.** Read `canon/prose/PROSE_SYSTEM.md`, `canon/prose/MIELLE_PROSE_STYLE_GUIDE.md`, `canon/prose/MIELLE_VOICE_GUIDE.md`, `canon/prose/CHAPTER_PROSE_AND_CHARACTER_VOICE_PASS.md` and `canon/prose/ANTI_AI_PROSE_EDITING_FILTER.md` one at a time. Rewrite expression, rhythm, scene clarity, evidence support and dialogue texture only. This pass cannot create or solve story facts. Record the paragraphs materially changed for the later Anti-AI receipt.
- May change: draft only.
- Output: `XX_DRAFT.md`, a completed pre-draft-guard receipt in the loadout or guard artifact, completion state for the four verification passes, and a list of materially changed paragraphs for audit handoff when the prose pass alters them.
- Must not: update continuity, alter canon without delta, give characters unsupported knowledge, copy transcript dialogue as prose, use the Anti-AI filter to invent texture, stakes, dialogue or events, begin prose before decision authority is reconciled, or declare the Anti-AI application complete before the post-draft receipt exists.

## 12. Audit

- Template: `templates/AUDIT_TEMPLATE.md`.
- Use when: after a complete draft.
- Read: Base production load; draft; previous draft when one exists; loadout; pre-draft guard; chapter plan; chapter mini delta; scene cards; combat pre-check if any; transcript extraction; controlling Arc Map; episode map; Episode Canon Delta; `continuity/C2E1_STARTING_STATE.md` for C2E1 chapters; `continuity/EVENT_INDEX.md`; relevant canon, continuity, setting, character, relationship, event, knowledge, power, Holmes, combat and prose-package files.
- May change: audit only.
- Output: issue list with severity, evidence, governing source and required correction; show-don't-tell evidence table; and a complete Anti-AI application receipt that returns to pre-draft risks, checks universal and targeted clusters, compares substantial revisions, records protected material and confirms a second-order reread.
- Must not: invent facts, promote memory, silently revise story decisions, call a problem style-only when its correction changes canon, agency, POV, relationship framing, knowledge control or mechanics, close on unsupported `pass` language, omit a pre-draft risk, or approve a generic Anti-AI receipt.
- Blocker: the audit remains open while the Anti-AI application receipt is absent, generic or invalid. Only an explicit chapter-specific user waiver naming this receipt requirement may override the blocker.

## 13. Revise

- Template: no separate template. Revise the existing draft and audit record, then run the Anti-AI Silent Edit.
- Use when: audit identifies a correction.
- Read: Base production load; current draft; previous draft; audit; every source named by an issue; chapter loadout; character dossier for every revised speaker or actor; exact Power Guide module for every revised power, defense, injury/no-hit result, evasion, damage, gear state or non-use; `canon/prose/PROSE_SYSTEM.md`; `canon/prose/CHAPTER_PROSE_AND_CHARACTER_VOICE_PASS.md`; `canon/prose/ANTI_AI_PROSE_EDITING_FILTER.md`.
- May change: revised draft and audit resolution status.
- Output: new draft version, resolved audit, completed Anti-AI Silent Edit receipt, material before/after comparison and second-order reread of every changed paragraph.
- Must not: introduce a canon change without returning to the needed planning document, preserve a smoother sentence that loses material specificity, skip comparison because the approximate meaning survived, or continue polishing once the filter’s stop condition is met.

## 14. Approve chapter

- Template: `templates/APPROVED_CHAPTER_RECORD_TEMPLATE.md`.
- Use when: the user approves the final draft.
- Read: final draft; closed audit; completed Anti-AI application receipt; chapter plan; chapter mini delta.
- May change: `chapters/approved/` and project state.
- Output: approved chapter record.
- Must not: promote continuity before approval or approve while the Anti-AI application receipt is absent, generic or invalid. A waiver is valid only when the user explicitly names this receipt requirement for the chapter.

## 15. Promote memory

- Templates: `templates/CHARACTER_STATE_TEMPLATE.md` for a new or rebuilt character state; `templates/RELATIONSHIP_STATE_TEMPLATE.md` for a material rebuild of the relationship-state controller; `templates/EVENT_TILE_TEMPLATE.md` for each new event tile. Update the existing `canon/relationships/RELATIONSHIP_STATE.md`, `continuity/KNOWLEDGE_LEDGER.md`, `continuity/EVENT_INDEX.md`, relevant event tiles and open threads; do not create a parallel party-memory controller.
- Use when: only after approval.
- Read: approved chapter; final audit; chapter mini delta; Episode Canon Delta; current continuity; `continuity/EVENT_INDEX.md`; affected character states; relationship state; event tiles; knowledge ledger; open threads.
- May change: current story state, recent chain, event index, event tiles, knowledge ledger, affected character states, `canon/relationships/RELATIONSHIP_STATE.md`, open threads and project state.
- Output: continuity ready for the next chapter.
- Must not: record an unused plan, omitted scene idea or author intention as a fact.

## 16. Update permanent rule or decision

- Template: use `templates/CHARACTER_TEMPLATE.md` only when a new or materially rebuilt character dossier is required; use `templates/CHARACTER_STATE_TEMPLATE.md`, `templates/RELATIONSHIP_STATE_TEMPLATE.md` and `templates/EVENT_TILE_TEMPLATE.md` under the same rule for a new state, relationship-controller rebuild or event record. Otherwise, update the owning file directly.
- Use when: the user makes a new permanent decision about character, setting, adaptation, combat, power or production.
- Read: Base production load; authority map; likely owning file; all files that point to that owner where a reference may become stale.
- May change: single owner file and necessary references.
- Output: updated owner and a note of current-work impact when relevant.
- Must not: duplicate a rule in several files or retroactively alter approved chapters without explicit revision.
