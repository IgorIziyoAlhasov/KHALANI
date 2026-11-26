# Research Pass 005 — Source architecture and audio-methodology controls

**Date:** 2026-11-26  
**State:** Official production commentary verified; target Khalani audio and game-data pairings **not** independently opened.

## 1. Primary publisher evidence about audio production

Blizzard Entertainment's article, *The Sounds of Koprulu*:
https://news.blizzard.com/en-gb/article/20722027/the-sounds-of-koprulu

Blizzard describes original voice recordings as processed through pitch shifts and multi-layered voices. It identifies Allen Adham as an original Dark Templar performer and explains that Remastered sound production sought fidelity to the original recordings rather than reinventing them.

**Implication for our research:** heard spectral details, apparent voice doubling, and some consonant/vowel ambiguities may result from sound processing. This is a **methodological caution**, not evidence of any particular Protoss phoneme. The source discusses original StarCraft / Remastered audio; do **not** extend its specific production details uncritically to every StarCraft II voice line.

## 2. Independent documentation of editor structure

Community SC2 Editor guides:
- https://s2editor-guides.readthedocs.io/New_Tutorials/04_Data_Editor/058_Data_Editor_Introduction/ — lists both `Conversations` and `Conversation States` catalogs.
- https://s2editor-guides.readthedocs.io/New_Tutorials/04_Data_Editor/data-spaces/ — explains that localization strings are stored separately from the underlying data catalog records.

**Implication:** searching only one catalog or file is not a comprehensive negative test. We need to inspect relevant dependencies, conversation object IDs, and associated locale-string keys.

## 3. Audit of prior translation hypothesis

Candidates: `DarkTemplar_Attack00/01` and `DarkTemplar_Yes02/03`.

Current status:
- Secondary indexed pairing: **yes** (previous Pass 004).
- Original `.ogg` assets directly played and independently transcribed: **no**.
- Original SC2 Conversations records directly inspected: **no**.
- Official Khalani→English equivalence demonstrated: **no**.
- Canonical morphology inferred: **none**.

The previous proximity-based pairs remain provisional. No word-for-word assignments such as `de = from` are authorized.

## 4. Reproducible editor capture protocol

For each candidate:
1. Record game/editor build, locale, selected map/mod and exact dependency set.
2. In Data Editor inspect **Campaign Data > Conversations** and, when relevant, **Conversation States**. Enable raw-ID and XML views if appropriate.
3. Search the Khalani candidate and relevant English text across appropriate localization strings as well as object fields.
4. Record conversation ID, field/key, raw source spelling, source file path, locale-string key, translation field and association type.
5. Independently locate the corresponding sound asset in **Art and Sound > Sounds** or archive records, preserving filename, locale, and checksum if available.
6. Capture exact audio transcription, uncertainty marks and alternate segmentations. Do not impose fan orthography before listening.
7. Distinguish **explicit editor translation annotation**, **editor context match**, **adjacent voice responses**, and **mere community assertion** as different evidentiary relationships.
8. If no matches appear, specify exactly which dependencies and localized content were searched; record an incomplete negative search.

## 5. Planned acoustic methodology

- Make a listening record for each recording as released in-game; do not redistribute proprietary audio.
- Prefer side-by-side manual listening with an unmodified reference playback. If any EQ, speed shift or denoising is used, register the process and treat resulting perceptions as secondary observations.
- Keep orthographic convention (spelling), phonetic hearing (IPA estimate), and phonological interpretation (underlying units) separate.
- Have a second listener verify ambiguous boundaries where possible.
- Do not generalize SC1 production conditions directly to SC2.

## 6. Exact research status after Pass 005

- New publisher-supported methodological observation: **1** (processed original Protoss voices).
- New independently verified lexical forms: **0**.
- New verified translations: **0**.
- Original SC2 Conversations entries directly inspected: **0**.
- No new Neo-Khalani terms or grammatical rules adopted.

**Next blocking dependency:** access to original relevant SC2 editor/locale records and actual unit audio, or sufficiently complete primary-source exports with recorded provenance.
