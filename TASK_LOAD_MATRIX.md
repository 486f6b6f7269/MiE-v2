# Task load matrix

## Binding rule

Before any production step, read this matrix and list the exact paths required by the task. Do not substitute phrases such as “core files,” “stable canon,” “relevant files,” or “as needed” for an actual path list.

A conditional item may be marked `not applicable` only after the task states why it cannot affect the current arc, episode or chapter.

For drafting, an exact file list is necessary but insufficient. The Chapter Loadout must also reconcile every conflict-prone planned fact through its decision-to-authority check before prose begins.

A read receipt proves only that a file was opened. Drafting, auditing and revision must also use `canon/prose/EXECUTION_APPLICATION_RECEIPTS.md` and `workflow/01_EXECUTION_APPLICATION_WORKFLOW.md` to prove that prose, style, Holmes, combat and character-voice rules reached the page.

## Non-optional read rules

These rules apply even when the task feels small:

- If a fight, threat, pursuit, weapon use, power use, power non-use, injury, evasion, resistance, defense or tactical reading appears, read `canon/POWER_GUIDE.md`, the exact applicable `canon/mielle_current_power_guide/` module(s), `canon/COMBAT_RULES.md`, and `canon/HOLMES_ENGINE.md` before writing or revising the scene.
- If Mielle appears, speaks, decides, reacts, is viewed by someone else, uses gear, refuses to use gear, or is physically affected, read `canon/characters/MIELLE.md` and `continuity/character_state/MIELLE_CURRENT.md`. Apply her current knowledge, gear, personality, voice, drawbacks, constraints/geasa where present, and public presentation.
- If any canon cast member appears, speaks, acts, reacts, witnesses, withholds, jokes, fights, or is used as a POV-adjacent presence, read that character's dossier in `canon/characters/` before writing or revising their line or action. Do not write canon cast voices from memory or from a prior draft alone.
- If a new character or NPC sees Mielle for the first time and has not already seen her fight or use a decisive ability, their default first impression should tend toward underestimation unless their file or the scene gives a concrete contrary reason. The underestimation comes from her petite harmless appearance, closed/blind left eye, round glasses, ordinary wooden sword, soft tired manner and everyday clumsiness. This impression is not proof of incompetence and must change only through observed evidence.
- `canon/HOLMES_ENGINE.md` is not limited to powered inference, mysteries or deduction speeches. It applies whenever Mielle's observation or interpretation changes action, silence, route, preparation, care, suspicion, a question, object handling, danger assessment or a decision to wait, test, disclose, refuse or leave.
- `canon/prose/PROSE_SYSTEM.md` applies to every prose scene. `canon/prose/MIELLE_PROSE_STYLE_GUIDE.md` applies to every substantial Mielle-lens scene. `canon/prose/CHAPTER_PROSE_AND_CHARACTER_VOICE_PASS.md` applies to every decision-relevant speaker or present character whose action, silence, reaction or witness state affects the scene.

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
| Mielle appears, decides, speaks, uses equipment, declines to use equipment, is viewed by someone else, or is materially affected | `canon/characters/MIELLE.md`; `continuity/character_state/MIELLE_CURRENT.md`; `canon/POWER_GUIDE.md` plus exact relevant module(s) when a capability, gear item, cognition, protection, recall, storage, possession, non-use or power interaction can affect the result; applicable Mielle drawbacks, constraints/geasa and public-impression rules in her dossier |
| A canon character appears or their decision matters | that person’s dossier in `canon/characters/`; current character-state when it exists; `continuity/KNOWLEDGE_LEDGER.md` and relevant event tiles when knowledge, witness state, belief or suspicion can change speech or action |
| Meaningful Mielle/group social interaction, teasing, care, curiosity, disclosure, question, boundary, or reaction to an established Mielle fact | `continuity/EVENT_INDEX.md`; relevant event tiles; `continuity/KNOWLEDGE_LEDGER.md`; relevant character dossiers and states; `canon/HOLMES_ENGINE.md` when Mielle's reading affects action, silence, disclosure, withholding or response |
| Relationship, intimacy, trust, injury-care, conflict, obligation, or group position matters | `canon/relationships/RELATIONSHIP_STATE.md`; relevant character states; `continuity/EVENT_INDEX.md`; relevant event tiles |
| A place, institution, custom, law, route, language, money, faction, or NPC affects the scene | exact applicable file(s) from `canon/setting/EXANDRIA_BASELINE.md`, `canon/setting/LOCATIONS.md`, and `canon/setting/FACTIONS_AND_NPCS.md` |
| Mielle observes, weighs, withholds, tests, predicts, reads behavior, reconstructs events, handles uncertainty or lets an observation affect a choice | `canon/HOLMES_ENGINE.md`; exact cognition or Haki module only when the result depends on a power rather than ordinary observation alone |
| Combat, pursuit, physical threat, hostile magic, meaningful gear use, consequential power use, injury, no-hit result, evasion or damage resistance occurs | `canon/COMBAT_RULES.md`; `canon/POWER_GUIDE.md`; relevant `canon/mielle_current_power_guide/` module(s); completed pre-check from `templates/COMBAT_TRANSLATION_CARD_TEMPLATE.md`; `canon/HOLMES_ENGINE.md` |
| Drafting or revising prose | `canon/prose/PROSE_SYSTEM.md`; `canon/prose/MIELLE_PROSE_STYLE_GUIDE.md`; `canon/prose/MIELLE_VOICE_GUIDE.md`; `canon/prose/MIELLE_INVARIANT_APPLICATION_TEST.md`; `canon/prose/CHAPTER_PROSE_AND_CHARACTER_VOICE_PASS.md`; `canon/prose/ANTI_AI_PROSE_EDITING_FILTER.md`; `canon/prose/EXECUTION_APPLICATION_RECEIPTS.md`; `workflow/01_EXECUTION_APPLICATION_WORKFLOW.md` |
| Source event, order, knowledge flow, tactical intent, delayed revelation or consequence is being adapted | active transcript/source note; controlling `work/arcs/.../ARC_MAP.md`; `work/c2eX/TRANSCRIPT_EXTRACTION.md`; `work/c2eX/EPISODE_MAP.md`; `work/c2eX/CANON_DELTA.md`; chapter mini delta where one exists |
| Prior story facts can affect the task | `continuity/CURRENT_STORY_STATE.md`; `continuity/RECENT_STORY_CHAIN.md`; `continuity/OPEN_THREADS.md`; `continuity/EVENT_INDEX.md`; relevant `continuity/events/` tiles; last approved chapter |

## Task-specific load

| Task | Required load beyond base production load | Output |
|---|---|---|
| Verify source | active transcript or VOD; relevant approved chapter; `CURRENT_STORY_STATE.md`; `KNOWLEDGE_LEDGER.md`; `EVENT_INDEX.md`; relevant event tiles; `C2E1_STARTING_STATE.md` when verifying C2E1 or its prologue; exact setting/character/power/Holmes/combat files only where source question depends on them | source note in active work |
| Extract transcript | active transcript or VOD; `CURRENT_STORY_STATE.md`; last approved chapter; `C2E1_STARTING_STATE.md` for C2E1; exact setting files needed to distinguish source fact from setting context | `work/c2eX/TRANSCRIPT_EXTRACTION.md` |
| Map arc | transcript extractions and source notes for the proposed episode range; current continuity; recent chain; open threads; `EVENT_INDEX.md`; relevant event tiles and knowledge ledger; relevant approved chapters; relevant character dossiers and relationship state; exact setting files; Power Guide, Holmes Engine and Combat Rules when a cross-episode constraint depends on capability, inference, combat or non-use | `work/arcs/<ARC_ID>/ARC_MAP.md` |
| Map episode | controlling Arc Map; transcript extraction; `CURRENT_STORY_STATE.md`; `RECENT_STORY_CHAIN.md`; `OPEN_THREADS.md`; `EVENT_INDEX.md`; `C2E1_STARTING_STATE.md` for C2E1; relevant character dossiers; `canon/relationships/RELATIONSHIP_STATE.md`; exact setting files; relevant event tiles and knowledge ledger | `work/c2eX/EPISODE_MAP.md` |
| Episode Canon Delta | controlling Arc Map; transcript extraction; episode map; current continuity; `C2E1_STARTING_STATE.md` for C2E1; Mielle dossier and state; relevant character dossiers, relationship state, `EVENT_INDEX.md`, event tiles and knowledge ledger; exact setting files; Power Guide, Holmes Engine and Combat Rules whenever Mielle’s intervention could touch those areas | `work/c2eX/CANON_DELTA.md` |
| Plan chapter | controlling Arc Map; episode map; episode Canon Delta; transcript extraction slice; current continuity; recent chain; open threads; `EVENT_INDEX.md`; last approved chapter; `C2E1_STARTING_STATE.md` for C2E1 chapters; relevant characters, relationship state, setting, event tiles, knowledge ledger and every power module or mechanics source that can affect a planned material fact | chapter plan |
| Chapter mini delta | chapter plan; controlling Arc Map; episode Canon Delta; transcript slice; episode map; `C2E1_STARTING_STATE.md` for C2E1 chapters; `EVENT_INDEX.md` when earlier event constrains intervention or knowledge; every exact document governing Mielle’s planned intervention, including character, relationship, setting, power, Holmes, combat, knowledge and event files | `work/c2eX/chapters/XX_CHAPTER_MINI_DELTA.md` |
| Scene cards | chapter plan; chapter mini delta; controlling Arc Map when cross-episode knowledge, obligation or delayed consequence constrains the scene; `C2E1_STARTING_STATE.md` for C2E1 scenes; relevant character dossiers/states; relationship state; knowledge ledger; `EVENT_INDEX.md`; relevant event tiles; exact setting files; Holmes Engine whenever Mielle's observation, interpretation, withholding or uncertainty can change the scene | scene cards with Holmes applicability and scene maps where required |
| Combat pre-check | chapter plan; chapter mini delta; scene cards; source slice; Mielle dossier/state; relevant combatant dossiers/states; Combat Rules; Power Guide and exact relevant module(s) for every power, gear item, defense, evasion, prediction, damage result or non-use; Holmes Engine; setting/terrain files | pre-check or combat translation card |
| Chapter loadout | controlling Arc Map; chapter plan; chapter mini delta; scene cards; pre-check if any; `C2E1_STARTING_STATE.md` for C2E1 chapters; `EVENT_INDEX.md`; all exact paths required by targeted-load rules; prose package in `canon/prose/`; `workflow/01_EXECUTION_APPLICATION_WORKFLOW.md`; decision-to-authority check; execution-system applicability and audit handoff; Anti-AI pressure map | chapter loadout |
| Draft | completed loadout and every exact path it names; completed decision-to-authority check; Anti-AI pre-draft guard; `canon/prose/EXECUTION_APPLICATION_RECEIPTS.md`; `workflow/01_EXECUTION_APPLICATION_WORKFLOW.md`; sequential passes in the workflow: factual/continuity, character/relationship, mechanics/Holmes/combat when applicable, prose/voice | draft plus paragraph, scene, voice, Holmes and combat audit handoff records |
| Audit | draft; previous version when one exists; loadout; chapter plan; chapter mini delta; scene cards; pre-check if any; source extraction; controlling Arc Map; episode map; episode Canon Delta; `C2E1_STARTING_STATE.md` for C2E1 chapters; `EVENT_INDEX.md`; relevant canon, continuity, setting, character, relationship, event, knowledge, Holmes, power, combat and prose-package files; `canon/prose/EXECUTION_APPLICATION_RECEIPTS.md`; `workflow/01_EXECUTION_APPLICATION_WORKFLOW.md` | audit with Prose System, Prose Guide, Holmes, Combat, Character Voice, Mielle invariant and Anti-AI receipts |
| Revise | draft; previous version; audit; every source named by issue; chapter loadout; `canon/prose/EXECUTION_APPLICATION_RECEIPTS.md`; `workflow/01_EXECUTION_APPLICATION_WORKFLOW.md`; exact character dossier for every speaker or actor being revised; exact power module for every capability, defense, no-hit result, evasion, damage result or non-use being revised | revised draft, updated receipts, version comparison and second-order reread |
| Approve chapter | final draft; closed audit; completed applicable execution receipts; `workflow/01_EXECUTION_APPLICATION_WORKFLOW.md`; chapter plan; chapter mini delta | approved chapter record |
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
8. execution-system applicability and audit handoff;
9. active chapter artifacts.

A heading with no applicable file must say `not applicable` and give one sentence of justification.

The decision-to-authority check must state what each sensitive fact permits and what it cannot imply. A generic statement that no conflict exists is not a receipt.

The execution-system handoff must name which scenes require Prose Guide, Holmes and Combat receipts, which characters require Voice Pass evidence, and which material claims the Prose System audit must verify. Generic `all systems apply` wording is not sufficient.
