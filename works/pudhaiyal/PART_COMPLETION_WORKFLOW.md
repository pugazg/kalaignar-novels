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

The safeguard applies to **every Tamil vowel sign and combining mark**. Demonstrated risks include faint final `லை`, faint `ா`, and `ே` / `ோ` distinctions.

Before changing a user baseline because a character, vowel sign or combining mark appears absent:

1. enlarge the **whole glyph cluster** at high resolution;
2. inspect at more than one useful scale/contrast;
3. explicitly consider old Tamil typeforms;
4. compare the same typeform elsewhere in the edition when useful;
5. require positive native-pixel evidence;
6. if pixels remain ambiguous, retain the baseline and `needs-review`;
7. never perform a global spelling/vowel-sign normalization.

If a proposed difference involves only an old/faint vowel sign, a near-identical same-word glyph, or apparent spacing created by a printed line wrap, perform a **second independent high-resolution inspection** before accepting it. A printed line break alone never proves word-internal spacing. If the user/source challenges one glyph in a batch, reopen every assistant-origin discrepancy in that batch before continuing.

Scan 277 adds the inverse caution: do not preserve or insert a grammatically expected vowel sign merely because it appears in the baseline. Native pixels confirm source `அவன் மணக்க மாட்டேன்`, not baseline `அவனை மணக்க மாட்டேன்`.

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
- canonical records: **32 / 49 — scans 246–277**
- verified: **32**
- needs-review: **0**
- not-started: **17 — scans 278–294**
- latest native-fidelity record: [`notes/visual-fidelity-scan-277.md`](notes/visual-fidelity-scan-277.md)
- Tamil audit: **not eligible**
- assembled Tamil: **not eligible**
- controlled English: **not eligible**
- bilingual review: **not eligible**
- state: **`in-progress`**

### Current Part-006 checkpoint

- scan 277 is source-verified from full-page plus enlarged high-resolution inspection;
- source spacing is `அழைத்துப் போகிறேன்`;
- physical line wraps establish `இருவருக்கும்`, `துன்புறுத்த`, `போகலாம்`, and `உண்மையான`;
- enlarged second pass confirms unusual `அவன் மணக்க மாட்டேன்`, with no final `ை` after `அவன்`;
- source again preserves `காதலர்கள்தானு`;
- source-specific `கஷ்டப் படுத்தணும்`, `கவலைப் படாதே`, `ராத்திரிக்கு`, `பங்களாவிலே`, `தொந்திரவு`, and `இணங்கித்தான் தீரணும்` remain unchanged;
- scan 277 ends `விட`; scan 278 begins `லாமென்று`, establishing `விடலாமென்று` across the boundary.

Part-006 mapped chapter transitions: chapter 28 begins scan 247; a four-star internal transition occurs on scan 251; chapter 29 begins 254 and closes 262; chapter 30 begins 262 and closes 271; chapter 31 begins 271 and closes 278; chapter 32 begins 278; chapter 33 begins 288.

Do not run the Part-006 Tamil audit or any downstream stage until all scans 246–294 have canonical records and native-fidelity dispositions.

## Part 005 — durable completion record

- split pages / canonical records: **49 / 49 — scans 197–245**
- `verified`: **42**
- `needs-review`: **7 — scans 215–219, 223–224**
- state: **`part-complete` with source-damage qualification**

## Exact next activity

Reconcile **scan 278 / printed page 274** directly against the native Part-006 source. First close scan 277 `விட` + scan 278 `லாமென்று` = `விடலாமென்று`, then verify the source-printed chapter **32** transition later on that page. Apply the strengthened two-pass old-typeform rule to all vowel signs and printed-line-wrap questions.