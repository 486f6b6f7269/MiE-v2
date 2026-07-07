# Task load matrix

## Binding rule

Before any production step, read this matrix and list the exact paths required by the task. Do not substitute phrases such as “core files,” “stable canon,” “relevant files,” or “as needed” for an actual path list.

A conditional item may be marked `not applicable` only after the task states why it cannot affect the current episode or chapter.

For drafting, an exact file list is necessary but insufficient. The Chapter Loadout must also reconcile every conflict-prone planned fact through its decision-to-authority check before prose begins.

## Base production load

Read for every planning, drafting, auditing, approval, or continuity task:

- `START_HERE.md`
- `AUTHORITY_MAP.md`
- `PROJECT_STATE.md`
- `canon/ADAPTATION_PREMISE.md`
- `canon/SOURCE_ADAPTATION_RULES.md`
- the relevant section of `workflow/00_WORKFLOWS.md`

## Targeted load rules

| Trigger | Required files |
|---|---|
| Work concerns C2E1, its prologue conditions, Mielle’s first contact with the party, or consequences directly governed by that opening | `continuity/C2E1_STARTING_STATE.md` |
| Mielle appears, decides, speaks, uses equipment, declines to use equipment, or is materially affected | `canon/characters/MIELLE.md`; `continuity/character_state/MIELLE_CURRENT.md`; `canon/POWER_GUIDE.md` plus exact relevant module(s) when a capability, gear item, cognition, protection, recall, storage, possession, non-use or power interaction can affect the result |
| A canon character appears or their decision matters | that person’s dossier in `canon/characters/`; current character-state when it exists; `continuity/KNOWLEDGE_LEDGER.md` and relevant event tiles when knowledge, witness state, belief or suspicion can change speech or action |
| Meaningful Mielle/group social interaction, teasing, care, curiosity, disclosure, question, boundary, or reaction to an established Mielle fact | `continuity/EVENT_INDEX.md`; relevant event tiles; `continuity/KNOWLEDGE_LEDGER.md`; relevant character dossiers and states |
| Relationship, intimacy, trust, injury-care, conflict, obligation, or group position matters | `canon/relationships/RELATIONSHIP_STATE.md`; relevant character states; `continuity/EVENT_INDEX.md`; relevant event tiles |
| A place, institution, custom, law, route, language, money, faction, or NPC affects the scene | exact applicable file(s) from `canon/setting/EXANDRIA_BASELINE.md`, `canon/setting/LOCATIONS.md`, and `canon/setting/FACTIONS_AND_NPCS.md` |
| Mielle makes a bounded inference, reads behavior, reconstructs events, or handles uncertainty | `canon/HOLMES_ENGINE.md` |
| Combat, pursuit, physical threat, hostile magic, meaningful gear use, or consequential power use occurs | `canon/COMBAT_RULES.md`; relevant `canon/mielle_current_power_guide/` module(s); completed pre-check from `templates/COMBAT_TRANSLATION_CARD_TEMPLATE.md`; `canon/HOLMES_ENGINE.md` if tactic depends on reading or inference |
| Drafting or revising prose | `canon/MIELLE_PROSE_STYLE_GUIDE.md`; `canon/CHAPTER_PROSE_AND_CHARACTER_VOICE_PASS.md`; `canon/ANTI_AI_PROSE_EDITING_FILTER.md` |
| Source event, order, knowledge flow, tactical intent, or consequence is being adapted | active transcript/source note; `work/c2eX/TRANSCRIPT_EXTRACTION.md`; `work/c2eX/EPISODE_MAP.md`; `work/c2eX/CANON_DELTA.md`; chapter mini delta where one exists |
| Prior story facts can affect the task | `continuity/CURRENT_STORY_STATE.md`; `continuity/RECENT_STORY_CHAIN.md`; `continuity/OPEN_THREADS.md`; `continuity/EVENT_INDEX.md`; relevant `continuity/events/` tiles; last approved chapter |

## Task-specific load

| Task | Required load beyond base production load | Output |
|---|---|---|
| Verify source | active transcript or VOD; relevant approved chapter; `CURRENT_STORY_STATE.md`; `KNOWLEDGE_LEDGER.md`; `EVENT_INDEX.md`; relevant event tiles; `C2E1_STARTING_STATE.md` when verifying C2E1 or its prologue; exact setting/character/power/Holmes/combat files only where source question depends on them | source note in active work |
| Extract transcript | active transcript or VOD; `CURRENT_STORY_STATE.md`; last approved chapter; `C2E1_STARTING_STATE.md` for C2E1; exact setting files needed to distinguish source fact from setting context | `work/c2eX/TRANSCRIPT_EXTRACTION.md` |
| Map episode | transcript extraction; `CURRENT_STORY_STATE.md`; `RECENT_STORY_CHAIN.md`; `OPEN_THREADS.md`; `EVENT_INDEX.md`; `C2E1_STARTING_STATE.md` for C2E1; relevant character dossiers; `canon/relationships/RELATIONSHIP_STATE.md`; exact setting files; relevant event tiles and knowledge ledger | `work/c2eX/EPISODE_MAP.md` |
| Episode Canon Delta | transcript extraction; episode map; current continuity; `C2E1_STARTING_STATE.md` for C2E1; Mielle dossier and state; relevant character dossiers, relationship state, `EVENT_INDEX.md`, event tiles and knowledge ledger; exact setting files; Power Guide, Holmes Engine and Combat Rules whenever Mielle’s intervention could touch those areas | `work/c2eX/CANON_DELTA.md` |
| Plan chapter | episode map; episode Canon Delta; transcript extraction slice; current continuity; recent chain; open threads; `EVENT_INDEX.md`; last approved chapter; `C2E1_STARTING_STATE.md` for C2E1 chapters; relevant characters, relationship state, setting, event tiles, knowledge ledger and every power module or mechanics source that can affect a planned material fact | chapter plan |
| Chapter mini delta | chapter plan; episode Canon Delta; transcript slice; episode map; `C2E1_STARTING_STATE.md` for C2E1 chapters; `EVENT_INDEX.md` when earlier event constrains intervention or knowledge; every exact document governing Mielle’s planned intervention, including character, relationship, setting, power, Holmes, combat, knowledge and event files | `work/c2eX/chapters/XX_CHAPTER_MINI_DELTA.md` |
| Scene cards | chapter plan; chapter mini delta; `C2E1_STARTING_STATE.md` for C2E1 scenes; relevant character dossiers/states; relationship state; knowledge ledger; `EVENT_INDEX.md`; relevant event tiles; exact setting files; Holmes Engine when interpretation or inference matters | scene cards |
| Combat pre-check | chapter plan; chapter mini delta; scene cards; source slice; Mielle dossier/state; relevant combatant dossiers/states; Combat Rules; relevant Power Guide modules; Holmes Engine when applicable; setting/terrain files | pre-check or combat translation card |
| Chapter loadout | chapter plan; chapter mini delta; scene cards; pre-check if any; `C2E1_STARTING_STATE.md` for C2E1 chapters; `EVENT_INDEX.md`; all exact paths required by targeted-load rules; prose style guide; chapter prose and character voice pass; Anti-AI filter; decision-to-authority check for every conflict-prone decision, fact, possession state, power use or non-use | chapter loadout |
| Draft | completed loadout and every exact path it names; completed decision-to-authority check; Anti-AI pre-draft guard; `canon/CHAPTER_PROSE_AND_CHARACTER_VOICE_PASS.md`; sequential passes in the workflow: factual/continuity, character/relationship, mechanics/Holmes/combat when applicable, prose/voice | draft plus completed verification-pass receipt |
| Audit | draft; loadout; chapter plan; chapter mini delta; scene cards; pre-check if any; source extraction; episode map; episode Canon Delta; `C2E1_STARTING_STATE.md` for C2E1 chapters; `EVENT_INDEX.md`; relevant canon, continuity, setting, character, relationship, event, knowledge, Holmes, power, combat, prose, chapter prose and character voice pass, and Anti-AI files | audit |
| Revise | draft; audit; every source named by issue; chapter loadout; `canon/CHAPTER_PROSE_AND_CHARACTER_VOICE_PASS.md`; Anti-AI Silent Edit | revised draft and audit resolution |
| Approve chapter | final draft; closed audit; chapter plan; chapter mini delta | approved chapter record |
| Promote memory | approved chapter; final audit; chapter mini delta; episode Canon Delta; current continuity; `EVENT_INDEX.md`; affected states, relationship state, event tiles and knowledge ledger | continuity updates |

## Loadout receipt

Every chapter loadout must list exact paths under these headings:

1. source and adaptation;
2. continuity;
3. character and relationship;
4. setting and faction;
5. power, Holmes and combat;
6. decision-to-authority check;
7. prose and editing;
8. active chapter artifacts.

A heading with no applicable file must say `not applicable` and give one sentence of justification.

The decision-to-authority check must state what each sensitive fact permits and what it cannot imply. A generic statement that no conflict exists is not a receipt.
