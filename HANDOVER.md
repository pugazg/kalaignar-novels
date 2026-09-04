# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

## Mandatory startup for continuation

Before changing the current work, read completely:

1. `NOVEL_PROCESSING_GUIDE.md`;
2. root `README.md`;
3. this `HANDOVER.md`;
4. current-work `works/periya-idathup-pen/README.md`;
5. `works/periya-idathup-pen/metadata/source.md`;
6. `works/periya-idathup-pen/indexes/page-map.md`;
7. `works/periya-idathup-pen/audit.md`;
8. relevant existing page records.

The attached source scan remains controlling. Do not commit the PDF.

## பெரிய இடத்துப் பெண் — source identity

- source filename: `TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`;
- SHA-256: `50db9c55d670065bd81088ee07e4527f5531a9ab15e3c4533d6b10eda8d09e9628`;
- file size: **70,952,481 bytes**;
- source scans: **49**;
- title visible on scan 1: **பெரிய இடத்துப் பெண்**;
- author visible on scan 1: **மு. கருணாநிதி**;
- publisher/place visible on scan 1: **திராவிடன் பதிப்பகம் / வேலூர் (வ. ஆ.)**;
- edition visible on scan 3: **எட்டாம் பதிப்பு: ஜூலை 1953**;
- price visible on scan 3: **விலை 0—8—0**;
- sales rights: **எம். எஸ். ராஜுலு கம்பெனி, 286, சைனா பஜார், சென்னை-1**.

## Current stage

- source registration: **complete**;
- page map: **49 / 49 scans represented**;
- canonical page records: **12 / 49**;
- directly verified: **12 / 49 — scans 1–12**;
- `needs-review`: **0** at this checkpoint;
- remaining `not-started`: **37**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil sections: **not started**;
- English translation: **not started; gate closed**;
- source PDF committed: **No**.

## Completed batches

### Scans 1–3

- scan 1 — verified cover title/author/publisher/place; handwriting recorded separately;
- scan 2 — verified copy-specific page classification; illegible handwriting not guessed; later gift-label recorded separately;
- scan 3 — verified edition/date, rights, price and sales-rights details.

### Scans 4–7

- scan 4 — verified `திரை விலக` author note;
- scan 5 — verified first `பதிப்புரை`;
- scan 6 — verified `எட்டாம் பதிப்பு / பதிப்புரை` opening;
- scan 7 / printed 6 — verified continuation and publisher sign-off.

### Scans 8–12

- scan 8 — verified title / narrative opening; visibly unnumbered;
- scan 9 / printed 8 — verified narrative continuation;
- scan 10 / printed 9 — verified narrative continuation;
- scan 11 / printed 10 — verified narrative continuation;
- scan 12 / printed 11 — verified narrative continuation.

Page-boundary continuations were checked directly between scans 9→10 and 11→12. No lexical reading in scans 8–12 remains `needs-review`.

Canonical records now run continuously through `works/periya-idathup-pen/pages/0012-periya-idathup-pen-05.md`.

## Printed-page behaviour

- scans 1–6: no visible printed page number;
- scan 7: printed page **6**;
- scan 8: no visible printed page number;
- scans 9–49: printed pages **8–48**.

Never infer the missing scan-8 number from sequence.

## Structural note

Representative review supports **one continuous work, `பெரிய இடத்துப் பெண்`**. Character-name headings observed inside the narrative (`உத்தண்டி`, `கண்ணம்மா`, `குமுதா`, `வீரன்`, `உலகநாதர்`) are internal headings at this stage, not separate works. Final section boundaries must be source-established during full page/continuity audit.

## Source-fidelity / old-glyph rule

The scan controls exact Tamil. Do not silently modernize or regularize spelling, punctuation, grammar, names, dialogue or odd forms. Before changing a supplied reading because a final sign seems absent, inspect the complete glyph cluster at high resolution, consider historical typeforms/faint marks, compare another same-edition occurrence when useful, and require positive native-pixel evidence. Genuine ambiguity stays `needs-review`. Never globalize one glyph finding.

## Exact next activity

Directly transcribe and visually verify **scans 13–17** (printed pages **12–16**) as the next narrative batch. Scan 15 / printed page 14 contains the internal heading `உத்தண்டி`; retain it as an internal textual heading unless continuity evidence establishes otherwise.

Preserve exact source paragraph/dialogue/punctuation structure, apply the old-glyph pre-correction gate to doubtful clusters, update page map/audit/work README, then stop. Do not begin English translation.

---

# Completed prior work — புதையல்

The previous `புதையல்` project remains unchanged and complete at its durable release state:

- canonical records: **448 / 448**;
- verified / completed: **446**;
- `needs-review`: **2 — scans 223–224 only**, due to substantial physical paper loss;
- Parts **001–010: part-complete**;
- assembled Tamil through scan 448: complete;
- whole-work English: **VERIFIED**;
- repository package: **RELEASE-READY WITH TWO PART-005 PHYSICAL-LOSS QUALIFICATIONS**.

The 2026-09-03 direct user review closed scans 215–219 and synchronized the proven Part-005 corrections through canonical Tamil and English. Stronger source evidence is still required to close scans 223–224.

Final records remain:

- `works/pudhaiyal/indexes/FULL_SOURCE_PAGE_MAP.md`
- `works/pudhaiyal/audit.md`
- `works/pudhaiyal/notes/part-005-tamil-audit.md`
- `works/pudhaiyal/translations/en/TRANSLATION_REVIEW.md`
- `works/pudhaiyal/translations/en/RELEASE_REPORT.md`
