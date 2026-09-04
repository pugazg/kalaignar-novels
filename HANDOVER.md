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
- canonical page records: **27 / 49**;
- directly verified: **27 / 49 — scans 1–27**;
- `needs-review`: **0** at this checkpoint;
- `partial`: **0**;
- remaining `not-started`: **22**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil sections: **not started**;
- English translation: **not started; gate closed**;
- source PDF committed: **No**.

## Completed batches

### Scans 1–7

Cover/source identity, copy-specific annotation page, publication details, `திரை விலக`, first `பதிப்புரை`, and eighth-edition `பதிப்புரை` through printed page 6 are directly verified.

### Scans 8–12

Scan 8 is the verified unnumbered narrative opening; scans 9–12 / printed 8–11 are verified narrative continuation. Scan 11 `கிடப்ப` + scan 12 `தாகக்` → `கிடப்பதாகக்`.

### Scans 13–17

Scans 13–17 / printed 12–16 are verified. Scan 15 / printed 14 directly verifies internal heading `உத்தண்டி`. Physical joins include `நினைக்` + `காதே!`, `தெரிந்` + `தது.`, and `நம்` + `வீட்டு`.

### Scans 18–22

Scans 18–22 / printed 17–21 are verified. Scan 19 / printed 18 directly verifies internal heading `கண்ணம்மா`. Physical joins include `கண்டது` + `போலத்தானே!`, scan-18 `என்` + scan-19 `றேன்.`, `என்` + `னிலே`, `நானும்` + `நன்றுகத்தான்`, and `காலக்ஷேபங்` + `கூட`.

### Scans 23–27

- scan 23 / printed 22 — verified narrative continuation;
- scan 24 / printed 23 — verified narrative continuation;
- scan 25 / printed 24 — verified narrative continuation;
- scan 26 / printed 25 — verified narrative continuation;
- scan 27 / printed 26 — verified narrative continuation and opening of an internal parenthetical recollection involving தலையாரி உத்தண்டி.

Direct source review established:

- scan 22 `மட்` + scan 23 `டும்` → `மட்டும்`;
- scan 23 `வீரன் ஏழைதான்` + scan 24 `ஆனால்` — continuation preserved;
- scan 24 `‘ஒய்யா` + scan 25 `ரக்` → `‘ஒய்யாரக்`;
- scan 25 `கவலை` + scan 26 `யில்லை.` → `கவலையில்லை.`;
- scan 26 `நிலையி` + scan 27 `லேயே` → `நிலையிலேயே`.

Source-specific forms retained in this batch include `பெற்ற பேய்கள்`, `வீராப்பில்`, `ஆனந்தங்`, `எண்ணப்பட்டாளம்`, `நன்றுக`, `விழுவேன் என்றுனா?`, `மட்டுந்தானு?`, `வட்டமிடும்`, `யம லோகத்திற்கு`, `மனசுதான்`, `பதிலச்`, `காரணந்`, `பட்சமாயிருந்த`, `ஆயிரங்`, `மெளனமே`, `சச்சிதானந்த`, `ஸ்பரிசத்தால்`, and `வீணன்`.

Scan 27 ends inside the parenthetical sentence after `அவனுக்கு ஒரு`; its continuation must be established only from the visible opening of scan 28. It has not been completed from context.

Canonical records now run continuously through `works/periya-idathup-pen/pages/0027-periya-idathup-pen-20.md`.

## Printed-page behaviour

- scans 1–6: no visible printed page number;
- scan 7: printed page **6**;
- scan 8: no visible printed page number;
- scans 9–49: printed pages **8–48**.

Never infer the missing scan-8 number from sequence.

## Structural note

Representative review supports **one continuous work, `பெரிய இடத்துப் பெண்`**. Character-name headings observed inside the narrative (`உத்தண்டி`, `கண்ணம்மா`, `குமுதா`, `வீரன்`, `உலகநாதர்`) are internal headings at this stage, not separate works. Scans 15 and 19 directly verify `உத்தண்டி` and `கண்ணம்மா` as internal textual structure. The parenthetical recollection beginning on scan 27 is also internal narrative structure, not a new bibliographic unit. Final section boundaries must be source-established during full page/continuity audit.

## Source-fidelity / old-glyph rule

The scan controls exact Tamil. Do not silently modernize or regularize spelling, punctuation, grammar, names, dialogue or odd forms. Before changing a supplied reading because a final sign seems absent, inspect the complete glyph cluster at high resolution, consider historical typeforms/faint marks, compare another same-edition occurrence when useful, and require positive native-pixel evidence. Genuine ambiguity stays `needs-review`. Never globalize one glyph finding.

## Exact next activity

Directly transcribe and visually verify **scans 28–32** (printed pages **27–31**) as the next narrative batch.

1. Resolve scan 27's final parenthetical continuation only from the visible opening of scan 28.
2. Scan 32 / printed page 31 contains internal heading `குமுதா`; retain it as internal textual structure unless page-level continuity proves otherwise.
3. Preserve exact source paragraph/dialogue/punctuation structure and apply the old-glyph pre-correction gate to every doubtful cluster.
4. Update page map/audit/work README/HANDOVER after the batch, then stop.
5. Do not begin assembled Tamil or English translation.

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
