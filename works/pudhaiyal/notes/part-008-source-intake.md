# Part 008 source intake — புதையல்

Date: 2026-09-02

## Received access derivative

- derivative: `TVA_BOK_0064097_புதையல்_part_008_pages_344-392.pdf`
- physical pages: **49**
- represented source scans: **344–392**
- visible printed pages: **340–388**
- file size: **54,567,816 bytes**
- SHA-256: `717d3ab75eb970313062e1e61517d442cffa188f2fd8cadb8f75263b5e9a8852`
- source/split PDF committed: **No**

## User-supplied lexical baseline

- file: `p8.md`
- size: **159,525 bytes**
- SHA-256: `aad52bdfeae873459d561a52826f4787fd04f72ac1c27886212a1942d8e89ca2`
- lines: **319**
- declared transcription coverage: printed pages **340–388**
- committed: **No**

Under the standing scan-280-onward rule, `p8.md` controls lexical/textual words, spelling, suffixes, lexical forms, wording and supplied lexical spacing. The native Part-008 PDF controls page identity, punctuation, quotation marks, paragraphing, physical boundaries, separators and chapter/scene structure.

A complete source-visible lexical word/span absent from `p8.md` must be flagged `needs-review`; it must not be silently inserted without explicit user authorization.

## Cross-part boundary verification

Part 007 scan **343 / printed 339** ends at open `அதிர்ஷ்`.

The native first page of Part 008, scan **344 / printed 340**, begins:

`டம் அடிக்குது!`

The supplied `p8.md` begins with the same lexical continuation.

Therefore the cross-split join is directly verified as:

**`அதிர்ஷ்` + `டம்` → `அதிர்ஷ்டம்`**

The continuous utterance is **`அதிர்ஷ்டம் அடிக்குது!`**. No chapter or scene boundary occurs at the derivative split.

## Mapping / visible structure

The filename range is confirmed by the actual pages:

- PDF page 1 = source scan **344** / printed **340**
- PDF page 49 = source scan **392** / printed **388**

Native chapter landmarks observed at intake:

- scan **347 / printed 343** — Chapter 39 closes at the foot rule;
- scan **348 / printed 344** — Chapter 40 begins;
- scan **355 / printed 351** — Chapter 40 closes and Chapter 41 begins;
- scan **362 / printed 358** — Chapter 41 closes and Chapter 42 begins;
- scan **369 / printed 365** — Chapter 42 closes and Chapter 43 begins;
- scan **376 / printed 372** — Chapter 43 closes and Chapter 44 begins;
- scan **387 / printed 383** — Chapter 44 closes and Chapter 45 begins;
- scan **392 / printed 388** — derivative ends inside Chapter 45 at open `நமது`.

The endpoint is provenance only and is not a chapter or novel ending.

## Intake state

- derivative identity: **resolved**
- physical/printed mapping: **resolved**
- lexical baseline identity: **resolved**
- Part-007→008 opening continuity: **verified**
- canonical Part-008 records: **0 / 49**
- Part-008 verified records: **0 / 49**
- Part-008 needs-review: **0**
- Part-008 not-started: **49**
- state: **`intake-complete / canonical-reconciliation-next`**

Page map: [`../indexes/part-008-page-map.md`](../indexes/part-008-page-map.md).

## Exact next activity

Reconcile **all Part-008 scans 344–392** into canonical page records, using `p8.md` for lexical text and the native PDF for structure. Preserve the verified `அதிர்ஷ்` + `டம்` cross-split join, inspect every physical page boundary and chapter/separator transition, and quarantine any complete `p8.md` lexical omission instead of silently repairing it.
