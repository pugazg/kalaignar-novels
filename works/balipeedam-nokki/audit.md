# Transcription Audit — பலிபீடம் நோக்கி

## Audit scope

Source: `TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`  
Source pages: **34**  
Source PDF committed to repository: **No**

This audit records the state of the source-preservation layer after page records were created for the complete scan. It is **not** a declaration that every character is final.

## Coverage gate

| Check | Result |
|---|---|
| Scan pages represented | **34 / 34** |
| Cover / title / publisher front matter represented | yes |
| Body scans 4–33 represented | **30 / 30** |
| Blank/back scan 34 represented | yes |
| Single work identity maintained | yes — `balipeedam-nokki` |
| `ராயசம் வெங்கண்ணு` kept internal, not separate work | yes |
| Source PDF excluded from repository | yes |
| Pages marked `verified` | **27** |
| Pages marked `needs-review` | **7** |
| Pages marked `not-started` | **0** |

## Structural audit

The scan has been read as one continuous work:

```text
பலிபீடம் நோக்கி
├── scans 4–7: opening ideological / polemical frame
├── scan 7: explicit transition into a film-like lesson
├── scans 8–29: internal ராயசம் வெங்கண்ணு cinematic-historical sequence
├── scan 30: explicit “படம் முடிந்துவிட்டது...” return to the main frame
└── scans 31–33: concluding direct address
```

No separate work-level metadata, directory or translation identity has been created for `ராயசம் வெங்கண்ணு`.

## Continuity checks preserved

Page-break continuity has been preserved rather than silently reflowed, including:

- scan 5 → 6: `அணுக்` / `களிலிருந்து`;
- scan 6 → 7: `உதிர` / `ஆறுகளைப் பாருங்கள்`;
- scan 12 → 13: Vijay Raghava's open dying-speech quotation;
- scan 17 → 18: open Venganna quotation;
- scan 19 → 20: `பத்திரமாக பாது` / `காத்துக்கொள்`;
- scan 21 → 22: sentence continuing after `என்று`;
- scan 29 → 30: `அப்படித்` / `தத்தளிக்கிறான்...`;
- scan 30 → 31: `கைகூப்புவதை` / `யும் நோக்குங்கள்`.

## Source features preserved

The page records preserve or separately identify:

- historical / unusual spellings and grammar;
- cinema vocabulary and title-card language;
- dialogue punctuation and bracketed scene/action directions;
- printed question marks and ornaments;
- stamps, handwritten underlines / marginal marks and bleed-through as non-text observations;
- source inconsistencies instead of silently reconciling them.

## Open character-level review queue

### Scan 3 — `pages/0003-publisher-note.md`

One short phrase in the final paragraph remains unresolved. No contextual reconstruction has been inserted.

### Scan 10 — `pages/0010-balipeedam-nokki-07.md`

The unusual printed form currently read as `மித்தானமத்தனுக்குக்` requires one more character-level comparison.

### Scan 13 — `pages/0013-balipeedam-nokki-10.md`

The current reading `முச்சுற்றுப்படுத்திருக்கும்` requires confirmation.

### Scan 21 — `pages/0021-balipeedam-nokki-18.md`

One short scene-transition phrase is explicitly unresolved. The unusual current reading `என்றுன் பேதை!` also requires confirmation.

### Scan 23 — `pages/0023-balipeedam-nokki-20.md`

The current reading `களேபாரப்படுகிறது` requires character-level confirmation.

### Scan 26 — `pages/0026-balipeedam-nokki-23.md`

The current readings `தற்பாகூரர்` and `வீரத்ததை எறக்கத்` require confirmation.

### Scan 27 — `pages/0027-balipeedam-nokki-24.md`

One short scene-transition word / phrase is explicitly unresolved.

## Audit status

**Transcription coverage: complete.**  
**Character-level source audit: not yet complete.**  
**Translation-ready: no.**

The next pass must focus only on the seven `needs-review` pages. If a reading cannot be resolved from the scan, it should remain explicitly unresolved; no historical or linguistic guess should be substituted.

After that targeted pass, perform a final consistency check for front matter, YAML fields, scan/printed-page numbers, page markers, cross-page continuations and status counts before opening the English translation stage.
