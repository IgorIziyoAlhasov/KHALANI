# Research Pass 013 — Blind-listening protocol and phonetic transcription queue

**Date:** 2026-11-28  
**Status:** Listening protocol ready, source audio accessible to the current research session; perceptual transcription not yet independently completed.

## Purpose

Move from source-file integrity measurements to reproducible *perceptual* phonetic descriptions. The first pass should be blind to community strings and alleged glosses to minimize expectation bias.

## Source material

The user extracted four Ogg Vorbis recordings from English-language StarCraft II **5.0.17 (98745)**, Battle.net region Europe:

| Recording | Duration | Channels | Notes |
| --- | ---: | ---: | --- |
| `HighTemplar_Ready00.ogg` | 2.640s | mono | First-pass listening target |
| `Zealot_Yes04.ogg` | 2.211s | mono | Test perceived similarity without spelling cues |
| `Mothership_What02.ogg` | 3.137s | stereo | Preserve both channels |
| `Mothership_What03.ogg` | 3.882s | stereo | Compare after independent transcription of What02 |

Hashes and signal metadata: `corpus/audio/user-extracted-audio-manifest.json` and `corpus/audio/acoustic-measurements-pass-012.json`.

## Independent listening instructions

1. Work in filename order, with existing fan transcripts and reported meanings **hidden**.
2. Play the original file twice at normal speed and note the number of possible syllables and word groups without attempting etymology.
3. Play again, then write your best hearing in Latin letters. Use `(?)` for uncertain sounds; use spaces only for perceived breaks.
4. Record alternative hearings and confidence per segment, not a single overall certainty score.
5. If slowing the file, note playback speed, algorithm/player and whether pitch changes; do not substitute transformed playback for the original evidence.
6. Have a second listener independently transcribe before showing either transcription to the other.
7. Compare listening results; only then unmask source-index spellings and investigate word/translation claims.

## Suggested annotation fields

Each line needs `filename`, `listener_id`, `listening_date`, `listening_order`, `hearing`, `syllable_count_estimate`, `word_breaks_confidence`, `uncertain_spans`, `alternative_hearing`, `playback_transformations`, and `notes`. Confidence is about *perception*; it is not a canon status.

## Secondary transcriptions: only reveal after blind pass

- High Templar / Zealot: reported `Khassar de Templari`, with differing punctuation/case.
- Mothership What02: reported English response `As all are one`.
- Mothership What03: reported `Ki nala atum`.

These are **secondary** identifications, not automatically audio-verified transcripts or official translation pairs.

## Important scientific caveat

The game voice processing may alter perceived segment boundaries and timbre. Frequencies, waveforms and spectrograms alone do not identify phonemic categories or validate semantic glosses. Even two matching human hearings are evidence of perception, not proof of official orthography.

## Milestone and QA

- Original file access: confirmed.
- Technical baseline from Pass 012: available.
- Blind-listening observation records: **0**.
- Perceptually verified IPA entries: **0**.
- Direct official translation pairings: **0**.
- New grammar rules admitted: **0**.

**Next action:** obtain the independent first-hearing for `Mothership_What03.ogg` (or all four where available), then record it verbatim without correcting to fan spellings.
