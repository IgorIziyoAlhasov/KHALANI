# Research Pass 012 — Reproducible acoustic inventory

**Date:** 2026-11-28  
**Input:** Four original contributor-extracted SC2 Ogg Vorbis files. English game installation; build **5.0.17.98745**, region **Europe**.

## Scope and limitations

All files were decoded and analyzed directly from the conversation's uploaded bytes. This pass tests *digital-audio metadata and simple signal structure*, **not** the linguistic content or a perceptual transcription. No speech recognition or independent critical listening was performed. The exact internal SC2 asset location remains unverified.

## Measurements

| File | Duration (s) | Channels | Approximate energy-active interval (s) |
|---|---:|---:|---|
| `HighTemplar_Ready00.ogg` | 2.6398 | 1 | 0.21–2.08 |
| `Zealot_Yes04.ogg` | 2.2112 | 1 | 0.17–1.87 |
| `Mothership_What02.ogg` | 3.1368 | 2 | 0.13–2.89 |
| `Mothership_What03.ogg` | 3.8816 | 2 | 0.11–3.58 |

Sample rate is 44,100 Hz for all files. The activity interval uses 10 ms window RMS and a fixed/relative amplitude threshold; **it is not a syllabic, phonetic, or speech-only interval**.

Mothership stereo-channel Pearson correlations are ~0.298 (What02) and ~0.347 (What03), indicating significant differences between channels. Preserve both channels in subsequent listening and avoid treating processing effects as phonemes.

## Integrity correction

Recomputed the SHA-256 fingerprints of all four uploaded files. The former manifest value for `Mothership_What02.ogg` contained a transcription error; corrected SHA-256:

`aef2d737c23fad2da9e3b02a9e6ee7719fc91ef03bd1e3025c145b1fcfea8fae`

Other fingerprints match the previous manifest. No modified source audio was committed.

## Findings not established

- No IPA transcription, underlying sound inventory, morphological analysis or direct translation is substantiated by the acoustic measurements.
- `Khassar de Templari` and `Ki nala atum` remain **candidate** transcriptions from secondary sources; the original audio is now available for human listening, but its content has not been independently transcribed here.
- `Mothership_What02` and `What03` being adjacent sound identifiers does not establish they translate one another.
- Peak decoded amplitude above 1.0 in `Mothership_What03` floating-point audio is not, on its own, evidence of source corruption.

## Next scientific step — blinded transcription

1. Independently listen to each raw file **without seeing the community transcript first**, writing syllable-like impressions and any uncertain phonetic segments.
2. If desired, replay individually at original speed before trying slowed playback; document all transformations.
3. Have a second listener (or contributor) provide another hearing and record disagreements.
4. Compare original unmodified sound with secondary writing variants and any in-game localized strings; avoid promoting phonemes based on processing artifacts.
5. Keep the raw recordings private/off-repository and publish only metadata, source locators and limited quotations as appropriate.

## Status

- Audio files digitally inspected: **4**
- Fingerprints confirmed/corrected: **4**
- Independent critical phonetic transcripts: **0**
- Direct official English translation pairings: **0**
- Newly accepted Khalani grammar rules: **0**

Full numeric measurements: `corpus/audio/acoustic-measurements-pass-012.json`.
