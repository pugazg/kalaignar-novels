# Tamil / split-part audit — புதையல்

Status: **IN PROGRESS — Parts 001–007 part-complete; Part 008 Tamil audit REOPENED / scan 384 disposition pending**

Source: `TVA_BOK_0064097_புதையல்.pdf`

## Authority rule

Through scan 279, completed records retain earlier source-first decisions. From scan 280 onward, supplied Gemini transcription controls lexical wording/forms/spacing and native scans control page identity, headings, punctuation, quotations, paragraphing, physical boundaries, separators and chapter/scene structure.

Part 007 uses `p7.md`; Part 008 uses `p8.md`. A complete native lexical span absent from the baseline must be quarantined rather than silently inserted.

## Split checkpoints

| Part | Source scans | State |
|---|---:|---|
| 001 | 1–49 | part-complete |
| 002 | 50–98 | part-complete |
| 003 | 99–147 | part-complete |
| 004 | 148–196 | part-complete |
| 005 | 197–245 | part-complete with source-damage qualification |
| 006 | 246–294 | part-complete |
| 007 | 295–343 | part-complete |
| 008 | 344–392 | **49/49 canonical; scan 384 needs-review; Tamil audit reopened** |

Seven physically damaged Part-005 records **215–219 and 223–224** remain `needs-review` under the existing qualification.

## Part 008 reopened result

Derivative: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`

- mapped pages: **49 / 49 — scans 344–392 / printed 340–388**
- derivative SHA-256: `717d3ab75eb970313062e1e61517d442cffa188f2fd8cadb8f75263b5e9a8852`
- baseline SHA-256: `aad52bdfeae873459d561a52826f4787fd04f72ac1c27886212a1942d8e89ca2`
- canonical: **49 / 49**
- verified: **48 / 49**
- Part-008 needs-review: **1 — scan 384 / printed 380**
- complete lexical omissions: **1 — native `தகட்டில் இருக்கிறபடி`, absent from `p8.md`**
- Tamil audit: **REOPENED / BLOCKED** — [`notes/part-008-tamil-audit.md`](notes/part-008-tamil-audit.md)

The earlier scan-384 canonical record had silently inserted that native phrase. The insertion has been removed under the standing lexical-authority policy. Explicit user disposition is required before the page can return to `verified`.

Other structural findings remain valid: the `அதிர்ஷ்`→`டம்` split join; chapter transitions at scans 347/348, 355, 362, 369, 376 and 387; four-star transitions at scans 372, 373 and 381; the scan-381 structure-only relocation; and the scan-390 structure-only `அதெல்லாம் எதற்கு வீண் கதை!` ordering. Scan 392 remains open at `நமது`.

## Assembled Tamil progress

Chapters **39–43** are assembled from unaffected canonical material. Chapter 39 includes the audited `அதிர்ஷ்டம்` split join. Chapter 43 closes on scan 376. Chapter 44 includes scan 384 and is therefore not finalized; Chapter 45 and the split-level assembled-Tamil consistency check remain pending.

## Aggregate canonical state

- records created: **392**
- verified/completed: **384**
- needs-review: **8 — Part 005 scans 215–219, 223–224 plus Part 008 scan 384**
- partial: **0**
- assembled Tamil: continuous through **Chapter 43 close on scan 376**
- source-checked/bilingual-reviewed English: through scan **343**
- received source coverage: through scan **392 / printed 388**

## Whole-work gate

**NOT ELIGIBLE.** Source beyond scan 392 remains required, and Part 008 still needs scan-384 disposition, a passing Tamil audit, completion of assembled Tamil, controlled English and bilingual review.

## Exact next activity

Obtain explicit user disposition for scan-384 phrase **`தகட்டில் இருக்கிறபடி`**. If authorized, restore it, rerun the Part-008 Tamil audit, finish assembled Chapters 44–45, and run the assembled-Tamil consistency check.
