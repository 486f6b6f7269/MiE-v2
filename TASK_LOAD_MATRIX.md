# Task load matrix

## Binding rule

Before any production step, read this matrix and list the exact paths required by the task. Do not substitute phrases such as “core files,” “stable canon,” “relevant files,” or “as needed” for an actual path list.

A conditional item may be marked `not applicable` only after the task states why it cannot affect the current episode or chapter.

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
| Mielle appears, decides, speaks, uses equipment, or is materially affected | `canon/characters/MIELLE.md`; `continuity/character_state/MIELLE_CURRENT.md`; `canon/POWER_GUIDE.md` plus exact relevant module(s) when a named capability, gear item, cognition, protection, or power interaction can affect the result |
| A canon character appears or their decision matters | that person’s dossier in `canon/characters/`; their current character-state file when it exists; `continuity/KNOWLEDGE_LEDGER.md` and relevant event tiles when what they know, witnessed, believe, or suspect can change speech or action |
| Meaningful Mielle/group social interaction, teasing, care, curiosity, disclosure, question, boundary, or reaction to an established Mielle fact | relevant event tiles; `continuity/KNOWLEDGE_LEDGER.md`; relevant character dossiers and states |
| Relationship, intimacy, trust, injury-care, conflict, obligation, or group position matters | `canon/relationships/RELATIONSHIP_STATE.md`; relevant character states; relevant event tiles |
| A place, institution, custom, law, route, language, money, faction, or NPC affects the scene | exact applicable file(s) from `canon/setting/EXANDRIA_BASELINE.md`, `canon/setting/LOCATIONS.md`, and `canon/setting/FACTIONS_AND_NPCS.md` |
| Mielle makes a bounded inference, reads behavior, reconstructs events, or handles uncertainty | `canon/HOLMES_ENGINE.md` |
| Combat, pursuit, physical threat, hostile magic, meaningful gear use, or consequential power use occurs | `canon/COMBAT_RULES.md`; relevant `canon/mielle_current_power_guide/` module(s); completed pre-check from `templates/COMBAT_TRANSLATION_CARD_TEMPLATE.md`; `canon/HOLMES_ENGINE.md` if the tactic depends on reading or inference |
| Drafting or revising prose | `canon/MIELLE_PROSE_STYLE_GUIDE.md`; `canon/ANTI_AI_PROSE_EDITING_FILTER.md` |
| Source event, order, knowledge flow, tactical intent, or consequence is being adapted | active transcript/source note; `work/c2eX/TRANSCRIPT_EXTRACTION.md`; `work/c2eX/EPISODE_MAP.md`; `work/c2eX/CANON_DELTA.md`; chapter mini delta where one exists |
| Prior story facts can affect the task | `continuity/CURRENT_STORY_STATE.md`; `continuity/RECENT_STORY_CHAIN.md`; `continuity/OPEN_THREADS.md`; relevant `continuity/events/` tiles; last approved chapter |

## Task-specific load

| Task | Required load beyond base production load | Output |
|---|---|---|
| Verify source | active transcript or VOD; relevant approved chapter; `CURRENT_STORY_STATE.md`; `KNOWLEDGE_LEDGER.md`; relevant event tiles; `C2E1_STARTING_STATE.md` when verifying C2E1 or its prologue; exact setting/character/power/Holmes/combat files only where the source question depends on them | source note in active work |
| Extract transcript | active transcript or VOD; `CURRENT_STORY_STATE.md`; last approved chapter; `C2E1_STARTING_STATE.md` for C2E1; exact setting files needed to distinguish source fact from setting context | `work/c2eX/TRANSCRIPT_EXTRACTION.md` |
| Map episode | transcript extraction; `CURRENT_STORY_STATE.md`; `RECENT_STORY_CHAIN.md`; `OPEN_THREADS.md`; `C2E1_STARTING_STATE.md` for C2E1; relevant character dossiers; `canon/relationships/RELATIONSHIP_STATE.md`; exact setting files; relevant event tiles and knowledge ledger | `work/c2eX/EPISODE_MAP.md` |
| Episode Canon Delta | transcript extraction; episode map; current continuity; `C2E1_STARTING_STATE.md` for C2E1; Mielle dossier and state; relevant character dossiers, relationship state, event tiles and knowledge ledger; exact setting files; power guide, Holmes Engine and Combat Rules whenever Mielle’s intervention could touch those areas | `work/c2eX/CANON_DELTA.md` |
| Plan chapter | episode map; episode Canon Delta; transcript extraction slice for the chapter; current continuity; recent chain; open threads; last approved chapter; `C2E1_STARTING_STATE.md` for C2E1 chapters; relevant characters, relationship state, setting, event tiles and knowledge ledger | chapter plan |
| Chapter mini delta | chapter plan; episode Canon Delta; transcript extraction slice; episode map; `C2E1_STARTING_STATE.md` for C2E1 chapters; all exact documents that govern Mielle’s planned intervention, including character, relationship, setting, power, Holmes, combat, knowledge and event files where applicable | `work/c2eX/chapters/XX_CHAPTER_MINI_DELTA.md` |
| Scene cards | chapter plan; chapter mini delta; `C2E1_STARTING_STATE.md` for C2E1 scenes; relevant character dossiers and states; relationship state; knowledge ledger; relevant event tiles; exact setting files; Holmes Engine when interpretation or inference matters | scene cards |
| Combat pre-check | chapter plan; chapter mini delta; scene cards; source slice; Mielle dossier and state; relevant combatant dossiers/states; Combat Rules; relevant Power Guide modules; Holmes Engine when applicable; setting/terrain files | pre-check or combat translation card |
| Chapter loadout | chapter plan; chapter mini delta; scene cards; pre-check if any; `C2E1_STARTING_STATE.md` for C2E1 chapters; all exact paths required by the targeted-load rules; prose style guide; Anti-AI filter | chapter loadout |
| Draft | completed loadout and every exact path it names; Anti-AI pre-draft guard | draft |
| Audit | draft; loadout; chapter plan; chapter mini delta; scene cards; pre-check if any; source extraction; episode map; episode Canon Delta; `C2E1_STARTING_STATE.md` for C2E1 chapters; relevant canon, continuity, setting, character, relationship, event, knowledge, Holmes, power, combat, prose, and Anti-AI files | audit |
| Revise | draft; audit; every source named by an issue; chapter loadout; Anti-AI Silent Edit | revised draft and audit resolution |
| Approve chapter | final draft; closed audit; chapter plan; chapter mini delta | approved chapter record |
| Promote memory | approved chapter; final audit; chapter mini delta; episode Canon Delta; current continuity; affected states, relationship state, event tiles and knowledge ledger | continuity updates |

## Loadout receipt

Every chapter loadout must list exact paths under these headings:

1. source and adaptation;
2. continuity;
3. character and relationship;
4. setting and faction;
5. power, Holmes and combat;
6. prose and editing;
7. active chapter artifacts.

A heading with no applicable file must say `not applicable` and give one sentence of justification.
