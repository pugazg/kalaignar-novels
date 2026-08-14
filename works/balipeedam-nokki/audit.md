# Transcription Audit — பலிபீடம் நோக்கி

## Audit scope

Source: `TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`  
Source pages: **34**  
Source PDF committed to repository: **No**

This is the final audit of the page-level Tamil source-preservation layer for this scan.

## Final coverage gate

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
├── scans 8–29: internal ராயசம் வெங்கண்ணு cinematic-historical sequence
├── scan 30: explicit “படம் முடிந்துவிட்டது...” return to the main frame
└── scans 31–33: concluding direct address
```

Scan 34 is blank/back matter.

No separate work-level metadata, directory, translation identity or release identity has been created for `ராயசம் வெங்கண்ணு`.

## Targeted character-level review — resolved

Seven pages had been deliberately held at `needs-review`. Each was re-inspected against enlarged source pixels.

### Scan 3 — publisher note

Previously unresolved text between `உலுத்தர் கும்பல்` and `போது` is visibly:

`பேனுப் பிடிக்கும்`

The page now reads:

`குள்ளநரிச் செயல்களுக்குக் கும்பிடு போடும் உலுத்தர் கும்பல் பேனுப் பிடிக்கும் போது, ...`

### Scan 10

The unusual source form is confirmed as:

`மித்தானமத்தனுக்குக்`

It remains unchanged despite its unusual lexical appearance.

### Scan 13

The source supports:

`முச்சுற்றுப்படுத்திருக்கும்`

No modernization or grammatical repair has been made.

### Scan 21

The previously open scene-transition phrase is resolved as:

`மளமள வென்று`

The unusual source wording:

`என்றுன் பேதை!`

is also visually confirmed and retained.

### Scan 23

The unusual form after `‘ஆண்டவனுக்கு அர்ச்சனை’` is confirmed as:

`களேபாரப்படுகிறது`

### Scan 26

Enlarged review corrected two earlier first-pass readings:

- `தற்பாகூரர்` → **`தர்ப்பாகூரர்`**
- `வீரத்ததை எறக்கத்` → **`விபரீதத்தை ஏற்கத்`**

These corrections are character-level source corrections, not contextual modernization.

### Scan 27

The unusual scene-transition wording is visibly:

`பிறகு காட்சியில் ஒரு காரணம்!`

The phrase `ஒரு காரணம்!` is retained exactly as printed even though it is narratively unusual.

## Metadata / manifest consistency

The 34 page records were checked against the page manifest.

- filenames run continuously from `0001` through `0034`;
- each file's `scan_page` agrees with its filename and manifest row;
- all records use the same source filename;
- all body records use `work: "balipeedam-nokki"`;
- internal section labeling changes only to represent source structure, not a second work;
- all records are now `verified`;
- page types correctly distinguish cover, title page, publisher note, body and blank/back matter.

### Printed-page mapping

Printed page numbers are recorded only where visibly printed:

- scans 5–7 → printed pages 4–6;
- scan 8 → no visible printed number;
- scans 9–33 → printed pages 8–32;
- front matter, scan 4 and scan 34 retain `null` / `—` where no printed number is visible.

No missing printed number has been inferred merely from sequence.

## Continuity audit

Cross-page source continuity is preserved rather than silently reflowed. Important joins include:

- scan 5 → 6: `அணுக்` / `களிலிருந்து`;
- scan 6 → 7: `உதிர` / `ஆறுகளைப் பாருங்கள்`;
- scan 12 → 13: Vijay Raghava's open dying-speech quotation;
- scan 17 → 18: open Venganna quotation;
- scan 19 → 20: `பத்திரமாக பாது` / `காத்துக்கொள்`;
- scan 21 → 22: sentence continuing after `என்று`;
- scan 29 → 30: `அப்படித்` / `தத்தளிக்கிறான்...`;
- scan 30 → 31: `கைகூப்புவதை` / `யும் நோக்குங்கள்`.

## Printed text vs copy-specific marks

The transcription layer keeps printed text separate from physical-copy artefacts. Page observations identify, where present:

- library / ownership stamps;
- handwritten numbers and accession marks;
- handwritten underlines and marginal / bracket marks;
- reverse-side bleed-through;
- stains, wear and binding artefacts.

Notable examples include the large stamp and handwritten underlining/brace on scan 26, later-page underlines/marginal marks, the printed closing ornament on scan 33, and the blank/back physical page on scan 34.

None of these copy-specific marks has been merged into printed body text.

## Source-faithfulness result

The final page layer preserves:

- historical and unusual spellings;
- source punctuation and inconsistent forms;
- cinematic vocabulary, title-card language and bracketed action directions;
- source-supported oddities such as `மித்தானமத்தனுக்குக்`, `முச்சுற்றுப்படுத்திருக்கும்`, `களேபாரப்படுகிறது`, `தர்ப்பாகூரர்`, `என்றுன் பேதை!`, and `ஒரு காரணம்!`;
- the internal-film architecture of the work without promoting it to a separate work.

## Final audit status

**Transcription coverage: complete.**  
**Character-level source audit: complete.**  
**Page/metadata consistency audit: complete.**  
**Verified pages: 34 / 34.**  
**Unresolved readings: 0.**  
**Tamil source layer: PASSED.**  
**Translation-ready: YES.**

The audited page records remain the canonical preservation layer. Any assembled reading text or English translation must derive from them and must not overwrite or silently normalize them.

## Next stage

Create a source-faithful assembled Tamil reading layer in `sections/`, maintaining one work identity while preserving the internal `ராயசம் வெங்கண்ணு` title/sequence. After assembly is checked against the audited page records, prepare the English translation plan.
