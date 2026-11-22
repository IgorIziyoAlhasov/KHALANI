# Research Pass 004 — Dark Templar voice-line alignment and orthographic variation

**Date:** 2026-11-22  
**Status:** Secondary indexed audio-asset mapping found; original game audio and SC2 Editor Conversations have not been inspected.

## Findings

The StarCraft Wiki *StarCraft II unit quotations/Protoss* index lists:
- `DarkTemplar_Attack00.ogg` — “I strike from the shadows!”
- `DarkTemplar_Attack01.ogg` — “Alakor de zhakan!”
- `DarkTemplar_Yes02.ogg` — “Clever.”
- `DarkTemplar_Yes03.ogg` — “Khatum.”

Reference: https://starcraft.fandom.com/wiki/StarCraft_II_unit_quotations/Protoss

These lines are adjacent within the same response class. This makes the advertised translations plausible, but does **not** prove their semantic equivalence. Adjacency is not a parallel-text annotation.

## Competing written transcriptions for Attack01

| Text | Secondary source |
| --- | --- |
| Alakor de zhakan! | https://starcraft.fandom.com/wiki/StarCraft_II_unit_quotations/Protoss |
| Ahla'kur dei Shakan. | https://liquipedia.net/starcraft2/Dark_Templar_%28Wings_of_Liberty_and_Heart_of_the_Swarm%29 |
| Al'a korr de zhakan | https://www.gamersky.com/handbook/201611/838795_10.shtml |

Differences include possible apostrophe placement, word boundaries and vowel/consonant spelling. No conclusion can yet be drawn about actual phoneme distinctions or dialects.

## Epistemic controls

- **Attested at secondary source level:** each written rendition and its index association.
- **Not established:** Blizzard-approved orthography, English/Khalani identity of meaning, morpheme segmentation or productive grammar.
- **Not completed:** direct listening to the `.ogg` assets, inspection of the SC2 game data, source-specific screenshots, or recorded editor build/dependency search.

## Proposed verification matrix

| Check | Target | State |
| --- | --- | --- |
| V-004-A | Play `Attack00` and `Attack01` from licensed game assets | pending |
| V-004-B | Play `Yes02` and `Yes03` from licensed game assets | pending |
| V-004-C | Inspect corresponding SC2 Editor conversation fields | pending |
| V-004-D | Compare sound sequence to the three published transcriptions | pending |
| V-004-E | Record build, locale, asset path and checksum | pending |
| V-004-F | If English gloss is directly paired in official data, create distinct translation-claim records | pending |

## Next interpretation

First pass evidence supports treating the two pairs as *candidate semantic correspondences*, useful for verification and subsequent analysis. Do **not** conclude that `de` equals “from”, `zhakan` equals “shadows”, or `Khatum` equals “clever” until primary paired evidence is recovered.

## Source status

All three indexed transcriptions are secondary evidence. Liqiuipedia's source page was search-indexed but direct page fetch was blocked by robots restrictions, so its wording should remain independently rechecked.
