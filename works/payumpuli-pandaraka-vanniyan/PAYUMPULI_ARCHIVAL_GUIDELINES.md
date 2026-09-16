# பாயும்புலி பண்டாரக வன்னியன் — Part-by-Part Archival Guidelines

This is the work-specific operating guide for `works/payumpuli-pandaraka-vanniyan/`.

It adopts the **Kuraloviyam per-Part closure methodology** while retaining the novel repository's assembled-Tamil and release-readiness layers.

## 1. Controlling-source rule

The user-attached split PDFs are the controlling source. They are the Tamil Digital Library copy supplied by the user.

Do not use Tamil Digital Library, Wikisource or another mirror as a second witness unless the user explicitly requests comparison.

Source wording, punctuation, paragraphing, historical glyph identity, visible printed-page numbering and page structure control.

## 2. Multipart numbering

Complete source: **477 physical scans / 16 supplied Parts**.

- Parts001–015: 30 scans each
- Part016: 27 scans
- canonical `scan_page`: global 1–477, never resets
- `part_page`: local position inside the split PDF
- every page record carries exact `part`, `part_page` and `source_filename`

Split files are provenance/access boundaries only, not textual boundaries.

## 3. Mandatory Part lock

> **Finish the entire maintained workflow for the active Part before beginning transcription of the next Part.**

A later Part may be:
- supplied and registered;
- used as the adjacent boundary witness needed to resolve the active Part's outgoing boundary.

But a later Part must **not** receive canonical transcription records, Pass work, assembled Tamil or English work until the active Part reaches final closure.

For this work:

**Part001 must reach Tamil archival-ready + assembled Tamil closure + English completion + release/readiness report + final Part closure before Part002 transcription begins.**

## 4. Tamil Part workflow

For each Part, in order:

1. **Source intake**
2. **Pass 1 — complete physical capture/transcription**
   - one canonical record for every physical scan;
   - complete printed Tamil text entered;
   - page provenance, printed-page mapping, visual/non-body notes retained;
   - records remain non-final.
3. **Pass 2A — direct textual verification**
   - compare every word, punctuation mark, paragraph boundary and page continuation against the attached scan.
4. **Pass 2B — independent lexical/historical-glyph reread**
   - performed only after Pass 2A covers the entire Part;
   - apply `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
   - no normalization.
5. **Pass 3 — meaningful visual/structural verification**
   - headings, block structure, page furniture, illustrations, non-body marks and continuations.
6. **Part audit**
7. **Final metadata/status synchronization**
8. **Documentation synchronization**
9. **Tamil archival-ready checkpoint**

Final `verified` status is assigned only after the whole-Part verification/audit chain closes. A page must not be called formally verified merely because an earlier local batch received a review.

## 5. Novel-specific assembled Tamil layer

After Tamil archival-ready:

1. assemble readable Part-level Tamil sections only from audited canonical page records;
2. preserve source-page provenance and verified cross-page joins;
3. audit the assembled layer against the canonical pages;
4. close the assembled Tamil Part checkpoint.

The assembled layer never supersedes canonical `pages/`.

## 6. English workflow

English is a **project-created translation** and begins only after the Part's Tamil archival and assembled-Tamil gates are closed.

Permanent gate order:

**translation plan → draft → source-check → glossary reconciliation → editorial review → Part-level bilingual review → release/readiness report → release-ready synchronization → final Part closure**

Required controls include:

- `translations/en/TRANSLATION_PLAN.md`
- `translations/en/GLOSSARY.md`
- `translations/en/PROGRESS.md`
- `translations/en/TRANSLATION_REVIEW.md`
- `translations/en/RELEASE_REPORT.md`

The release/readiness report must confirm Tamil/English coverage, bilingual alignment, unresolved items, navigation/provenance and source-PDF exclusion.

## 7. Final Part closure

Create a durable Part closure record, e.g.:

`PART_001_FINAL_CLOSURE.md`

It must confirm:

- Tamil Part archival-ready;
- assembled Tamil closed;
- English translation complete;
- whole-Part bilingual review passed;
- release/readiness report passed;
- unresolved blockers recorded;
- source/boundary state durable;
- no unauthorized drift after release.

**Only after this checkpoint passes may Part002 transcription begin.**

## 8. Boundary rule

The next Part's first page may be inspected as an outgoing-boundary witness before the next Part is active.

For Part001:
- scan30 / Part001 local30 and scan31 / Part002 local1 were directly compared;
- **30→31 = GENUINE CONTINUATION**;
- this boundary finding is retained;
- Part002 transcription remains blocked until Part001 final closure.

## 9. Batch cadence

User-directed normal source batch size: **10 physical scans**, with a shorter final remainder.

A batch is only complete when the requested Pass work for those scans is complete. Page/provenance-only scaffolding is not Pass-1 completion.

For Part001 Pass 1:
- scans1–5: printed-text capture exists, but formal final verification is deferred to the whole-Part chain;
- scans6–15: **COMPLETE / text-complete / needs-review**;
- scans16–25: **COMPLETE / text-complete / needs-review**;
- scans26–30: **COMPLETE / text-complete / needs-review**.

Part001 Pass 1 is **30/30 COMPLETE**; formal Pass 2A is **30/30 COMPLETE**; formal Pass 2B is **30/30 COMPLETE**. The next gate is **formal Pass 3 from scan1**.

## 10. Current Part lock

- **Active Part: Part001 / overall scans1–30**
- **Part002: SOURCE REGISTERED / TRANSCRIPTION BLOCKED**
- Part002 may not become active until `PART_001_FINAL_CLOSURE.md` passes.
