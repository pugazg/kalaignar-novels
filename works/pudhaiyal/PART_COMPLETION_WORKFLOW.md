# Split-PDF part-completion workflow — புதையல்

The split PDFs are **access derivatives of one source edition**, not separate bibliographic works. A split may reach `part-complete`, but whole-work Tamil/English/release gates remain blocked until the complete edition is processed.

## Per-split sequence

1. map represented source scans;
2. create/reconcile canonical `pages/` records;
3. perform native visual/textual fidelity review;
4. resolve or explicitly retain every `needs-review` item;
5. run a part-level Tamil audit;
6. update assembled Tamil from audited canonical pages only;
7. translate the audited material;
8. source-check English against canonical Tamil;
9. run part-level bilingual review;
10. synchronize status before moving to the next split.

A derivative boundary is provenance only. Do not invent word, sentence, paragraph, scene or chapter boundaries from it.

## Mandatory old-Tamil-typeform check before a correction

This edition contains old/faint Tamil typeforms whose vowel marks can be easy to miss at ordinary zoom. A demonstrated risk is final `லை`, especially in `இல்லை` / `வில்லை`-type forms, where the faint `ை` component can make the cluster look like bare `ல்`.

Before changing a user baseline because a final letter, vowel sign or combining mark appears absent:

1. enlarge the **whole glyph cluster** at high resolution;
2. inspect the character at more than one useful scale/contrast when the mark is faint;
3. explicitly consider old Tamil typeforms before declaring a discrepancy;
4. compare the same typeform elsewhere in this source edition when useful;
5. require **positive native-pixel evidence** for the replacement;
6. if pixels remain ambiguous, retain the baseline and `needs-review` rather than guessing;
7. never run a global `வில்ல` → `வில்லை`, `இல்ல` → `இல்லை`, or reverse replacement — individual source pixels govern every occurrence.

**Strengthened after the scans-256–259 correction:** if a proposed difference from the baseline involves only an old/faint vowel sign, a near-identical same-word glyph, or apparent word spacing created by a printed line wrap, perform a **second independent high-resolution inspection** before accepting the change. Compare another clear occurrence from the same edition when possible. A printed line break by itself never proves word-internal spacing. If the user/source challenges one glyph in a batch, reopen every assistant-origin discrepancy in that batch before continuing forward.

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**
- Part 005 — scans **197–245** — **`part-complete` with explicit source-damage qualification**

## Active split — Part 006

Source derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages / mapped source scans: **49 / 49 — scans 246–294**
- visible printed pages: **242–290**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- canonical records: **19 / 49 — scans 246–264**
- verified: **19**
- needs-review: **0**
- not-started: **30 — scans 265–294**
- latest native-fidelity record: [`notes/visual-fidelity-scan-264.md`](notes/visual-fidelity-scan-264.md)
- Tamil audit: **not eligible**
- assembled Tamil: **not eligible**
- controlled English: **not eligible**
- bilingual review: **not eligible**
- state: **`in-progress`**

### Current Part-006 checkpoint

- scans 256–259 remain corrected after second high-resolution reinspection;
- scan 260 verifies the Iteration-25 opening and ends `வெள்ளியம்பலம்`;
- scan 261 closes `வெள்ளியம்பலம் கேட்டு விட்டு, ...` and ends `விடிந்த`;
- scan 262 begins `தும்`, yielding `விடிந்ததும்`, closes chapter 29 and begins chapter 30, and ends `துக்காராமுக்கோ,`;
- scan 263 closes `துக்காராமுக்கோ, ஆனந்தம் தாங்கவில்லை.` and establishes `நடந்தவைகள்`, `புதையலைக் கண்டுபிடிப்பதற்காகவே`, and full `மறந்து விடவில்லை`;
- scan 264 establishes source `என்ன — தெரியாது மாதிரி விழிக்கிறே?`, source punctuation `தெரியவில்லை — விழித்தாள்!`, `சரி — சரி —`, `வந்தேனே......`, and full `புரியவில்லை`; endpoint `பேசக்கூட விடமாட்டேங்கிறீர்களே!”`.

Part-006 mapped chapter transitions: chapter 28 begins scan 247; a four-star internal transition occurs on scan 251; chapter 29 begins 254 and closes 262; chapter 30 begins 262; 31 begins 271; 32 begins 278; 33 begins 288.

Do not run the Part-006 Tamil audit or any downstream stage until all scans 246–294 have canonical records and native-fidelity dispositions.

## Part 005 — durable completion record

- split pages / canonical records: **49 / 49 — scans 197–245**
- `verified`: **42**
- `needs-review`: **7 — scans 215–219, 223–224**
- state: **`part-complete` with source-damage qualification**

## Exact next activity

Reconcile **scan 265 / printed page 261** from user Iteration 25 directly against the native Part-006 source, continuing chapter 30. Apply the strengthened two-pass old-typeform rule before accepting any disputed glyph or word spacing.