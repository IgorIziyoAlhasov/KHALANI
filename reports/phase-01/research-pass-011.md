# Research Pass 011 — First user-extracted audio inventory

**Date:** 2026-11-28  
**Research milestone:** Four user-extracted Ogg Vorbis files became available for direct local inspection.

## Source provenance

The project contributor reports that the four voice lines were extracted from StarCraft II. Exact game build, audio language, extraction workflow, original archive path and extracted asset IDs have not yet been recorded. A matching filename is **not** by itself archive authentication.

## Verified technical properties

| Filename | Length (s) | Channels | Rate (Hz) | Codec | Size (bytes) |
|---|---:|---:|---:|---|---:|
| `HighTemplar_Ready00.ogg` | 2.64 | 1 | 44100 | Ogg Vorbis | 33920 |
| `Zealot_Yes04.ogg` | 2.211 | 1 | 44100 | Ogg Vorbis | 23386 |
| `Mothership_What02.ogg` | 3.137 | 2 | 44100 | Ogg Vorbis | 52452 |
| `Mothership_What03.ogg` | 3.882 | 2 | 44100 | Ogg Vorbis | 64596 |

Cryptographic SHA-256 fingerprints are in `corpus/audio/user-extracted-audio-manifest.json`.

## Immediate scientific implications

- Audio can now be inspected directly without relying solely on community written transcriptions.
- Preserve unmodified source files outside the public repository; do not redistribute copyrighted Blizzard audio.
- All four files are decodable, and the samples can be replayed locally.
- No precise IPA analysis or morpheme boundaries are promoted in this pass.
- The claims `Khassar de templari` / `Ki nala atum` and their English glosses remain source-text hypotheses until a transcriber listens in a blind or controlled comparison and direct translation evidence is found.
- `Mothership_What02` and `What03` are distinct recordings with different durations; any exact parallel translation relationship still needs official data support.

## Follow-up capture fields

1. StarCraft II build and game/editor locale.
2. Exact archive / asset-browser path per file and any localized variant.
3. Extraction software and whether the original bitstream was exported untouched.
4. Two-pass listening transcripts for each sound, including disagreement and uncertainty symbols.
5. Corresponding SC2 Conversations or other localization records with IDs and concrete translation links.

## QA status

- User-supplied source files: **4**
- File format verified by decoder: **4**
- SHA-256 fingerprints recorded: **4**
- Source archive provenance fully documented: **0**
- Literal translation pairs independently confirmed: **0**
- Grammatical analyses accepted from this batch: **0**
