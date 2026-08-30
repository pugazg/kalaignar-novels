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

A part Tamil gate normally passes with all pages verified. Where the controlling physical source itself is damaged and stronger witnesses do not exist, the audit may instead record an **explicit source-damage disposition**. Such pages remain `needs-review`; they are never silently promoted to `verified`. Subsequent assembled/English work must preserve that provenance and may not claim whole-work verification from it.

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

This rule follows the retrospective audit in [`notes/old-glyph-retrospective-audit-120-245.md`](notes/old-glyph-retrospective-audit-120-245.md) and the corrected scans-256–259 reinspection in [`notes/visual-fidelity-scans-256-259.md`](notes/visual-fidelity-scans-256-259.md).

## Completed split checkpoints

- Part 001 — scans **1–49** — **`part-complete`**
- Part 002 — scans **50–98** — **`part-complete`**
- Part 003 — scans **99–147** — **`part-complete`**
- Part 004 — scans **148–196** — **`part-complete`**
- Part 005 — scans **197–245** — **`part-complete` with explicit source-damage qualification**

Part 003 scan 120 and the readable Part-005 scans listed in the retrospective old-glyph audit were corrected and downstream Tamil re-synchronized on 2026-08-30. Split-level states remain unchanged after that integrity correction.

## Active split — Part 006

Source derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

- physical pages / mapped source scans: **49 / 49 — scans 246–294**
- visible printed pages: **242–290**
- derivative map: [`indexes/part-006-page-map.md`](indexes/part-006-page-map.md)
- canonical records: **17 / 49 — scans 246–262**
- verified: **17**
- needs-review: **0**
- not-started: **32 — scans 263–294**
- latest native-fidelity record: [`notes/visual-fidelity-scan-262.md`](notes/visual-fidelity-scan-262.md)
- Tamil audit: **not eligible**
- assembled Tamil: **not eligible**
- controlled English: **not eligible**
- bilingual review: **not eligible**
- state: **`in-progress`**

Mandatory opening continuity is closed from native evidence:

- scan 245 ends `இருக்கவே`;
- scan 246 begins `இருக்கிறாள் பரிமளா, ...`;
- joined reading: `இருக்கவே இருக்கிறாள் பரிமளா, ...`.

### Current Part-006 checkpoint

- scans 256–259 were corrected after a second high-resolution reinspection; earlier unsupported assistant differences remain withdrawn;
- scan 260 verifies Iteration-25 opening and ends at `வெள்ளியம்பலம்`;
- scan 261 closes `வெள்ளியம்பலம் கேட்டு விட்டு, ...`, preserves `தவழுகத்`, `ஆள்பாடு ஆயிடும்`, `எங்கேயிருக்கு`, `பேஷாக`, and ends `விடிந்த`;
- scan 262 begins `தும்`, yielding `விடிந்ததும்`; source reads `குறுக்கிட்டது`, `என்று கூறினான்`, `ஆம்;`, `நடந்து, நடந்து`; old-glyph second pass confirms full `தெரியவில்லை`; source-specific `தன்னந் தனியாக` and `கிழவருந்தான்` are retained; chapter **29 closes / chapter 30 begins**; page ends `துக்காராமுக்கோ,`.

Part-006 mapped chapter transitions: chapter 28 begins scan 247; a four-star internal transition occurs on scan 251; chapter 29 begins 254 and closes 262; chapter 30 begins 262; 31 begins 271; 32 begins 278; 33 begins 288.

Do not run the Part-006 Tamil audit or any downstream stage until all scans 246–294 have canonical records and native-fidelity dispositions.

## Part 005 — durable completion record

Source derivative: `TVA_BOK_0064097_புதையல்_part_005_pages_197-245.pdf`

- split pages / canonical records: **49 / 49 — scans 197–245**
- `verified`: **42**
- `needs-review`: **7 — scans 215–219, 223–224**
- not-started: **0**
- Tamil audit: [`notes/part-005-tamil-audit.md`](notes/part-005-tamil-audit.md) — **`part-tamil-audit-source-damage-closed`**
- assembled Tamil: **completed, old-glyph-resynchronized and part-reviewed**
- controlled English translation: **completed and source-checked**
- bilingual review: [`translations/en/PART_005_REVIEW.md`](translations/en/PART_005_REVIEW.md) — **PASSED WITH SOURCE-DAMAGE QUALIFICATION**
- state: **`part-complete`**

Source-condition exceptions remain permanently explicit unless stronger source evidence becomes available:

- scans **215–219** are affected by repair/tape obstruction, including duplicate printed-page witnesses;
- scans **223–224** have substantial physical tear/loss;
- user baseline is retained where source pixels are hidden, but those scans remain `needs-review`;
- no uncertainty is closed from grammar/context or from the old-glyph pattern alone.

## Exact next activity

Reconcile **scan 263 / printed page 259** from user Iteration 25 directly against the native Part-006 source, continuing chapter 30 from `துக்காராமுக்கோ,`. Apply the strengthened two-pass old-typeform rule before accepting any disputed glyph or word spacing.