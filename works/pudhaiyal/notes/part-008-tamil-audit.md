# Part 008 Tamil audit — புதையல்

Date: 2026-09-02

Derivative: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`  
Source scans: **344–392**  
Printed pages: **340–388**  
Lexical baseline: uploaded `p8.md`

## Verdict

**PART-008 TAMIL AUDIT: REOPENED / BLOCKED — lexical omission disposition required at scan 384**

The earlier PASS verdict is withdrawn. During assembled-Tamil construction, a missed complete source-visible lexical omission was detected on scan **384 / printed 380**.

## Reopened lexical issue

Native scan 384 contains the phrase:

`தகட்டில் இருக்கிறபடி`

between `எங்கும் ஓடிவிடாமல்!` and `அவளுக்கு ஒரு மாப்பிள்ளை...`.

The controlling `p8.md` baseline omits that complete phrase. The earlier canonical scan-384 record had incorrectly source-filled it. That unauthorized insertion has now been removed; scan 384 is `needs-review` pending explicit user disposition.

## Current gate checks

- physical page mapping: **PASS — 49 / 49**
- canonical page records: **PASS — 49 / 49**
- verified statuses: **48 / 49**
- Part-008 `needs-review`: **1 — scan 384 only**
- known complete baseline omissions: **1 — `தகட்டில் இருக்கிறபடி` on scan 384**
- Part-007→008 `அதிர்ஷ்` + `டம்` continuity: **PASS**
- chapter landmarks 39→45: **PASS**
- internal native separators/transitions: **PASS**
- physical page joins: **PASS**
- scan-381 structure-only relocation: **PASS**
- scan-390 structure-only ordering correction: **PASS**
- open scan-392 endpoint at `நமது`: **PASS**

## Assembled-Tamil consequence

Assembled Chapters **39–43** have been built from unaffected audited canonical material. Chapter **44** includes scan 384 and therefore must not be finalized until the omission receives explicit disposition. Chapter 45 remains pending behind that gate.

## Next gate

Obtain explicit user disposition for scan 384 `தகட்டில் இருக்கிறபடி`. If authorized, restore that source-visible phrase, return scan 384 to `verified`, rerun this Tamil audit, then finish assembled Chapters 44–45 and the Part-008 assembled-Tamil consistency check. Do not begin controlled English until the assembled-Tamil check passes.
