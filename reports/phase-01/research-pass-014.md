# Research Pass 014 — Mothership stereo and spectral comparison

**Date:** 2026-11-28

## Objective

Use the contributor-supplied original audio to test acoustic prerequisites for the perceptual observations recorded in `NK-LISTEN-0001` (Pass 013A), while keeping speaker impression separate from canonical phonological analysis.

## Source and provenance

- English StarCraft II 5.0.17 (98745), Battle.net Europe, contributor extraction.
- `Mothership_What02.ogg`, SHA-256 `aef2d737c23fad2da9e3b02a9e6ee7719fc91ef03bd1e3025c145b1fcfea8fae`.
- `Mothership_What03.ogg`, SHA-256 `e0711a9a0967c49d4a92272db5ca0136e9cde6a8536accb70b2b5f22eed79679`.
- Archive asset locations remain unverified.

## Procedure

Decoded both stereo Vorbis files to floating-point PCM (44,100 Hz). Computed left/right waveform Pearson correlation; mid/side RMS ratio; and whole-recording mid-channel squared STFT magnitude proportion below 250 Hz (2048-sample Hann windows with 1024 samples overlap).

## Results

| Feature | What02 | What03 |
| --- | ---: | ---: |
| Duration (seconds) | 3.136757 | 3.881587 |
| Stereo L/R correlation | 0.297865 | 0.347258 |
| RMS(L−R)/RMS(L+R) | 0.735540 | 0.696837 |
| Mid-channel squared STFT energy below 250 Hz | 76.97% | 86.06% |

Both recordings contain marked stereo-channel differences. The center-channel spectral balance differs materially. **These are whole-file spectral measurements; they must not be read as vowel, consonant, pitch contour, or phoneme measurements.**

## Hypothesis and limitations

In Pass 013A the contributor described:
- A markedly colored /k/-like onset in `Ki`, compared impressionistically with Hebrew ק and Russian palatalization.
- Plain /a/-like vowels in `nala`, but a different quality / pitch impression at the start of `atum`.
- A slightly /ju/-colored ending in `atum`.

This is a useful **individual perceptual report**, not an IPA mapping. The current analyses do not confirm uvularity, palatalization, pharyngealization, glottalization, Mandarin-like lexical tone or diphthongization. Stereo mixing and effects make such inferences especially risky.

## Next verification

1. Obtain an independent human hearing of `Mothership_What02.ogg`, preferably reporting perceived words and voice processing separately.
2. If a new listener is available, blind them to the earlier transcript `Ki nala atum` and the phonetic hypotheses.
3. Annotate time ranges of specific consonants and vowels before undertaking targeted spectrogram or pitch-tracking work.
4. Do **not** use generic whole-recording pitch or spectrum as proof of an individual vowel's articulation.
5. Seek original game-data localization links before making a word-for-word translation claim.

## QA

- Original recordings directly analyzed: 2.
- New signal measurement records: 2.
- New independent critical-listening transcriptions: 0.
- Canonical phonemes or morphology established: 0.

Numeric results: `corpus/audio/mothership-comparison-pass-014.json`.
