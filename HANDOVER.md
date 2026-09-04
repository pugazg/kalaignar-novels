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
4. `works/periya-idathup-pen/README.md`;
5. `works/periya-idathup-pen/HISTORICAL_GLYPH_AUDIT.md`;
6. `works/periya-idathup-pen/metadata/source.md`;
7. `works/periya-idathup-pen/indexes/page-map.md`;
8. `works/periya-idathup-pen/audit.md`;
9. relevant existing page records.

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

## CURRENT VERIFICATION FREEZE

**Do not mark any page in `பெரிய இடத்துப் பெண்` as `verified`.**

The user identified a systematic transcription failure in the 1953 typeface: a historical/pre-reform Tamil glyph corresponding to modern Unicode **`றா`** can resemble modern **`று`**. Earlier page work copied that apparent modern shape and therefore generated false “odd source forms.” This invalidates the previous 27/27 verification claim.

All existing canonical records for scans **1–27** are `needs-review`. Future page records must also remain `needs-review` while the historical-glyph audit is open unless the user explicitly changes this policy.

This is a glyph-identity problem, not permission to modernize spelling. Determine the historical character identity and encode that identity in modern Unicode; otherwise preserve source wording, spelling, punctuation, grammar and page structure exactly.

## Confirmed historical-glyph corrections

| Scan | Printed page | Earlier transcription | Correct Unicode reading |
|---:|:---:|---|---|
| 20 | 19 | `நன்றுகத்` | `நன்றாகத்` |
| 21 | 20 | `நன்றுகத்தான்` | `நன்றாகத்தான்` |
| 24 | 23 | `நன்றுக` | `நன்றாக` |
| 24 | 23 | `விழுவேன் என்றுனா?` | `விழுவேன் என்றானா?` |

Do not global-search-and-replace from these examples. Every occurrence must be checked against its own source pixels. Full tracking is in `works/periya-idathup-pen/HISTORICAL_GLYPH_AUDIT.md`.

## Retrospective historical-glyph audit progress

### Scan 1 — completed one-page pass

The cover was re-read from an enlarged source render. Printed text checked individually:

- `பெரிய இடத்துப் பெண்`
- `மு. கருணாநிதி`
- `திராவிடன் பதிப்பகம்`
- `வேலூர் (வ. ஆ.)`

No printed `றா` cluster occurs on scan 1, so the specific old-`றா` / apparent-modern-`று` ambiguity is absent on this page. No other printed glyph-identity correction was required in this pass. Copy-specific handwriting remains outside canonical printed text.

**Important:** scan 1 remains `needs-review`. A completed historical-glyph pass is not a `verified` page state.

Progress: **1 / 27 existing canonical scans re-audited; scans 2–27 pending**.

## Current stage

- source registration: **complete**;
- page map: **49 / 49 scans represented**;
- canonical page records: **27 / 49 — scans 1–27**;
- `verified`: **0**;
- `needs-review`: **27 — scans 1–27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- historical-glyph retrospective audit: **OPEN — 1 / 27 reviewed**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil sections: **BLOCKED / not started**;
- English translation: **BLOCKED / not started**;
- source PDF committed: **No**.

## Existing transcription coverage

Canonical records exist continuously through `works/periya-idathup-pen/pages/0027-periya-idathup-pen-20.md`, but none carries verified status.

Structural observations retained provisionally:

- scan 15 / printed 14 contains internal heading `உத்தண்டி`;
- scan 19 / printed 18 contains internal heading `கண்ணம்மா`;
- scan 27 begins an internal parenthetical recollection involving தலையாரி உத்தண்டி.

These are source-structure observations only and do not establish page verification.

## Existing boundary evidence

The following joins remain useful source evidence but are provisional until the retrospective page audit is complete:

- scan 11 `கிடப்ப` + scan 12 `தாகக்` → `கிடப்பதாகக்`;
- scan 14 `நினைக்` + scan 15 `காதே!` → `நினைக்காதே!`;
- scan 15 `தெரிந்` + scan 16 `தது.` → `தெரிந்தது.`;
- scan 16 `நம்` + scan 17 `வீட்டு` → `நம் வீட்டு`;
- scan 17 `கண்டது` + scan 18 `போலத்தானே!`;
- scan 19 `என்` + scan 20 `னிலே` → `என்னிலே`;
- scan 20 `நானும்` + scan 21 `நன்றாகத்தான்`;
- scan 22 `மட்` + scan 23 `டும்` → `மட்டும்`;
- scan 24 `‘ஒய்யா` + scan 25 `ரக்` → `‘ஒய்யாரக்`;
- scan 25 `கவலை` + scan 26 `யில்லை.` → `கவலையில்லை.`;
- scan 26 `நிலையி` + scan 27 `லேயே` → `நிலையிலேயே`;
- scan 27 ends inside a parenthetical sentence after `அவனுக்கு ஒரு`; continuation awaits scan 28.

## Historical-glyph audit rule

For every suspect form:

1. inspect the complete glyph cluster at native/high resolution;
2. explicitly consider historical/pre-reform Tamil typeforms before deciding Unicode identity;
3. compare another same-edition occurrence where useful;
4. require positive source-pixel evidence for character identity;
5. encode the actual historical character identity in modern Unicode;
6. do not silently modernize vocabulary, spelling, grammar or punctuation;
7. do not globalize a finding from one occurrence to another;
8. keep the page `needs-review` while this work-wide audit remains open.

The user-confirmed `றா` issue is the starting pattern, not the only glyph form to inspect.

## Printed-page behaviour

- scans 1–6: no visible printed page number;
- scan 7: printed page **6**;
- scan 8: no visible printed page number;
- scans 9–49: printed pages **8–48**.

Never infer the missing scan-8 number from sequence.

## Exact next activity

**Audit scan 2 only. Do not move beyond one page in that activity.**

Use the same one-page method:

1. inspect the entire scan at enlarged/high resolution;
2. distinguish later gift-label / handwriting from source printed text;
3. inspect every printed glyph cluster for historical typeforms, including but not limited to old `றா`;
4. make only pixel-supported glyph-identity corrections;
5. record the result in the page record and `HISTORICAL_GLYPH_AUDIT.md`;
6. keep scan 2 `needs-review` regardless of whether corrections are found;
7. stop after scan 2 and report the result.

Do not continue to scans 28–32, assembled Tamil, or English translation.

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

Final records remain:

- `works/pudhaiyal/indexes/FULL_SOURCE_PAGE_MAP.md`
- `works/pudhaiyal/audit.md`
- `works/pudhaiyal/notes/part-005-tamil-audit.md`
- `works/pudhaiyal/translations/en/TRANSLATION_REVIEW.md`
- `works/pudhaiyal/translations/en/RELEASE_REPORT.md`
