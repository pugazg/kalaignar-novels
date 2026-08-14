# Transcription & Assembly Audit — பலிபீடம் நோக்கி

## Audit scope

Source: `TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`  
Source pages: **34**  
Source PDF committed to repository: **No**

This file records the completed audit of both the canonical page-level Tamil source-preservation layer and the derived assembled Tamil reading layer.

## Final page-layer coverage gate

| Check | Result |
|---|---|
| Scan pages represented | **34 / 34** |
| Cover / title / publisher front matter represented | yes |
| Body scans 4–33 represented | **30 / 30** |
| Blank/back scan 34 represented | yes |
| Continuous page records | yes — scan 1 through scan 34 |
| Single work identity maintained | yes — `balipeedam-nokki` |
| `ராயசம் வெங்கண்ணு` kept internal, not separate work | yes |
| Source PDF excluded from repository | yes |
| Pages marked `verified` | **34** |
| Pages marked `needs-review` | **0** |
| Pages marked `not-started` | **0** |

## Structural audit

The source is one continuous work:

```text
பலிபீடம் நோக்கி
├── scans 4–7: opening ideological / polemical frame
├── scan 7: explicit transition into a film-like lesson
├── scans 8–29 + opening of scan 30: internal ராயசம் வெங்கண்ணு cinematic-historical sequence
├── scan 30: film end-card, then explicit “படம் முடிந்துவிட்டது...” return to the main frame
└── scans 31–33: concluding direct address
```

Scan 34 is blank/back matter.

No separate work-level metadata, directory, translation identity or release identity has been created for `ராயசம் வெங்கண்ணு`.

## Targeted character-level review — resolved

Seven pages had previously been held at `needs-review`. Each was re-inspected against enlarged source pixels.

- **scan 3:** `பேனுப் பிடிக்கும்`
- **scan 10:** `மித்தானமத்தனுக்குக்` confirmed as printed
- **scan 13:** `முச்சுற்றுப்படுத்திருக்கும்` confirmed
- **scan 21:** `மளமள வென்று`; `என்றுன் பேதை!` confirmed
- **scan 23:** `களேபாரப்படுகிறது` confirmed
- **scan 26:** corrected first-pass readings to `தர்ப்பாகூரர்` and `விபரீதத்தை ஏற்கத்`
- **scan 27:** `ஒரு காரணம்!` confirmed as printed

These are source-based resolutions, not contextual normalization.

## Page metadata / manifest consistency

The 34 page records were checked against the page manifest.

- filenames run continuously from `0001` through `0034`;
- every file's `scan_page` agrees with its filename and manifest row;
- all records use the same source filename;
- all body records use `work: "balipeedam-nokki"`;
- internal section labeling represents source structure without creating a second work;
- all records are `verified`;
- page types correctly distinguish cover, title page, publisher note, body and blank/back matter.

### Printed-page mapping

Printed page numbers are recorded only where visibly printed:

- scans 5–7 → printed pages 4–6;
- scan 8 → no visible printed number;
- scans 9–33 → printed pages 8–32;
- front matter, scan 4 and scan 34 retain `null` / `—` where no printed number is visible.

No missing printed number has been inferred merely from sequence.

## Continuity audit

Cross-page continuity is preserved rather than silently repaired. Important joins include:

- scan 5 → 6: `அணுக்` / `களிலிருந்து`;
- scan 6 → 7: `உதிர` / `ஆறுகளைப் பாருங்கள்`;
- scan 12 → 13: Vijay Raghava's open dying-speech quotation;
- scan 19 → 20: `பாது` / `காத்துக்கொள்`;
- scan 21 → 22: `என்று` / `கூறியபடி`;
- scan 29 → 30: `அப்படித்` / `தத்தளிக்கிறான்...`;
- scan 30 → 31: `கைகூப்புவதை` / `யும்`.

## Printed text vs copy-specific marks

The transcription layer keeps printed text separate from physical-copy artefacts. Page observations identify, where present, library/ownership stamps, handwritten numbers, underlines, marginal/bracket marks, bleed-through, stains, wear and binding artefacts. These marks have not been merged into printed body text.

## Canonical Tamil source result

**Transcription coverage: complete.**  
**Character-level source audit: complete.**  
**Page/metadata consistency audit: complete.**  
**Verified pages: 34 / 34.**  
**Unresolved readings: 0.**  
**Tamil source layer: PASSED.**

The audited `pages/` records remain the canonical preservation layer.

---

# Assembled Tamil Reading Layer Audit

## Files

- `sections/01-opening-frame.md`
- `sections/02-rayasam-vengannu-sequence.md`
- `sections/03-return-and-conclusion.md`
- `sections/README.md`

## Assembly boundaries

The reading layer follows narrative structure rather than mechanically cutting at scan boundaries:

1. **Opening frame:** scans 4–7.
2. **Internal cinematic sequence:** scans 8–29 plus scan 30 through the internal film's `வணக்கம்` end-card.
3. **Return and conclusion:** scan 30 beginning with `படம் முடிந்துவிட்டது...` through scan 33.

This split is necessary because scan 30 contains both the final moments/end-card of the internal film and the explicit return to the main `பலிபீடம்` frame.

## Assembly rules verified

- assembled text derives only from audited `pages/` records;
- no page record was modified to create the reading layer;
- `ராயசம் வெங்கண்ணு` remains an internal section, never a second work;
- historical spelling, punctuation, dialogue, cinematic terms and source oddities are retained;
- scan observations and physical-copy marks are excluded from the reading prose;
- printed source ornaments are retained;
- page provenance is preserved using HTML comments;
- only previously verified page-boundary continuities are joined for readability.

### Readable joins made

- `அணுக்` + `களிலிருந்து` → `அணுக்களிலிருந்து`
- `பாது` + `காத்துக்கொள்` → `பாதுகாத்துக்கொள்`
- `அப்படித்` + `தத்தளிக்கிறான்...`
- `கைகூப்புவதை` + `யும்` → `கைகூப்புவதையும்`

Other sentence/quotation continuities remain source-faithful while page provenance comments identify their boundaries.

## Assembly result

**Assembled Tamil sections: complete.**  
**Source coverage: complete.**  
**Structural identity check: passed.**  
**Page-boundary continuity check: passed.**  
**Canonical page layer unchanged: yes.**  
**Assembly status: PASSED.**

## Translation gate

The Tamil source layer and assembled reading layer have both passed their audits.

**Translation-ready: YES.**

The next stage is to create an English translation plan. Translation may use `sections/` for narrative continuity, but every difficult or unusual wording must be resolved against the canonical audited `pages/` record rather than normalized from memory or general knowledge.
