# Research Pass 003 — SC2 Conversations: Evidence and Access Audit

**Date:** 2026-11-22  
**Status:** Official attestation located; SC2 Editor translation pairs not independently inspected.

## Core result

An article by Blizzard Entertainment staff member Amelia Savery on Xbox Wire (26 September 2024) ends in **Khas il'adare!** This directly verifies the written form and its official *use*, but not its meaning or grammar:

https://news.xbox.com/es-latam/2024/09/26/conoce-starcraft-y-starcraft-ii-cuando-lleguen-a-game-pass/

- Source ID: NK-SRC-0005
- Attestation: NK-ATT-0004
- Source location: final paragraph before related stories
- Official spelling for that occurrence: `Khas il'adare!`
- Translation supplied by article: **none**
- Interpretation: unresolved.

## Conversations data research

The StarCraft Wiki's Khalani compilation reports that some SC2 phrases receive translations in the Data Editor's Conversations category: https://starcraft.fandom.com/wiki/Khalani . This is **S3 secondary reporting**; no original game editor data asset, in-editor screenshot identifying the exact entries, or source-specific conversation metadata was recovered in this pass.

A Blizzard Cutscene Editor guide discusses conversation data, lines and source dependencies: https://us.media.blizzard.com/starcraft2/downloads/tutorial/SCII-CutsceneEditorInstructions.pdf . The document's searchable text was accessible, but web PDF screenshot retrieval failed; visual verification remains pending.

Independent community editor documentation lists Conversations among Data Editor categories: https://s2editor-guides.readthedocs.io/New_Tutorials/04_Data_Editor/058_Data_Editor_Introduction/

Therefore: **Do not yet promote the wiki's Khalani/English pairs to primary-verified translations.**

## Candidate utterance-pair queue (S3 only)

| Candidate form | Secondary gloss | Lead |
| --- | --- | --- |
| `Alakor de zhakan` | I strike from the shadows! | StarCraft Wiki Khalani; Protoss unit quotations, Dark Templar Attack01 |
| `Khatum` | Clever. | Protoss unit quotations, Dark Templar Yes03 |
| `Anan pokahl` | Time for battle. | StarCraft Wiki Khalani |
| `Khas il'adare` | May your spirit soar. | StarCraft Wiki Khalani |

The first two have useful adjacent voice-line indexes (DarkTemplar_Attack00/01 and DarkTemplar_Yes02/03). However, *neighboring response lines* do not prove literal word-by-word equivalence: they may be contextually alternative speech rather than parallel translations.

## Next reproducible verification procedure

1. With legally installed StarCraft II and the StarCraft II Editor, open Data Editor and select Conversations.
2. Load the campaign/mission dependencies necessary to expose the relevant conversations.
3. Search candidate Khalani forms in conversation text and localized strings.
4. For any find, record game build, dependency list, conversation ID, field name, original form, directly paired English text, asset path and UI screenshot.
5. Cross-check the originating audio, unit, and line index in the audio assets.
6. If none is found, log that build/dependency search as a negative result; **do not claim global absence**.
7. Store the resulting translation claims as separately attributed records and update attestation status only where warranted.

## Methodological observations

- An official *usage attestation* and an official *translation attestation* are different evidentiary objects.
- A secondary pair can be a research lead without being canon-verified.
- The syllable sequence `Khas` occurs as a canonical title elsewhere; it must not be assumed to have that meaning or be the same morpheme in `Khas il'adare`.
- There is still no primary-supported productive Khalani grammar in the corpus.

## Counts from this pass

- New official orthographic attestation: **1**
- SC2 original conversation entries directly opened: **0**
- Official English translations newly verified: **0**
- Audio recordings directly analyzed: **0**
