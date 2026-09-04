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

The user identified a systematic transcription failure in the 1953 typeface. The first confirmed example was a historical/pre-reform Tamil glyph corresponding to modern Unicode `றா` being read as apparent modern `று`. The user then supplied a higher-quality Periyar reform chart proving that the audit must cover a broader set of legacy forms rather than focusing only on `றா`.

The complete known reference set from that chart is:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Examples shown by the chart include `அண்ணா`, `அணை`, `மண்ணொடு`, `கண்ணோடு`, `தலை`, `களை`, `சிறார்`, `மற்றொரு`, `காற்றோடு`, `மன்னா`, `வினை`, `என்னொடு`, and `என்னோடு`.

The historical shapes are visual typeforms. Canonical Markdown must encode the actual Tamil identity in modern Unicode after source-pixel confirmation. This is **not** permission to modernize spelling, grammar, punctuation or vocabulary.

All existing canonical records for scans **1–27** are `needs-review`. Future page records must also remain `needs-review` while the historical-glyph audit is open unless the user explicitly changes this policy.

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

The cover was re-read from an enlarged source render against the complete 13-form reference. No printed occurrence required legacy-form conversion and no other glyph-identity correction was found. Copy-specific handwriting remains outside canonical printed text. Scan 1 remains `needs-review`.

### Scan 2 — completed one-page pass

The page was re-read at enlarged resolution. No original 1953 source-work printed narrative or publication text is present. The clearly printed material is the later copy-specific gift label:

`பேராசிரியர். தி.வ. மெய்கண்டார் அவர்களின்`  
`அன்பளிப்பு`

Those printed label units were checked against all 13 known forms. None requires historical-form conversion. The handwritten Tamil remains copy-specific and was not guessed or promoted into canonical source-work text. Scan 2 remains `needs-review`.

### Scan 3 — completed one-page pass

The publication-details page was re-read at enlarged/high resolution. It contains several positive historical-form occurrences from the 13-form reference:

- `ஜூலை` — historical `லை` form;
- `விலை` — historical `லை` form;
- `விற்பனை` — historical `னை` form;
- `சைனா` — historical `னா` form;
- `சென்னை` — historical `னை` form.

The existing canonical transcription already encoded all five with the correct modern Unicode identities, so no lexical replacement was required. This confirms that the edition uses historical `லை`, `னை`, and `னா` forms in addition to the separately identified `றா` issue. Scan 3 remains `needs-review`.

Progress: **3 / 27 existing canonical scans re-audited; scans 4–27 pending**.

## Current stage

- source registration: **complete**;
- page map: **49 / 49 scans represented**;
- canonical page records: **27 / 49 — scans 1–27**;
- `verified`: **0**;
- `needs-review`: **27 — scans 1–27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- historical-glyph retrospective audit: **OPEN — 3 / 27 reviewed**;
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

For every page:

1. inspect complete glyph clusters at native/high resolution;
2. explicitly check the full known historical set corresponding to `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
3. distinguish historical/pre-reform glyph identity from modern visual resemblance;
4. compare another same-edition occurrence where useful;
5. require positive source-pixel evidence for character identity;
6. encode the actual historical character identity in modern Unicode;
7. do not silently modernize vocabulary, spelling, grammar or punctuation;
8. do not globalize a finding from one occurrence to another;
9. keep the page `needs-review` while this work-wide audit remains open.

The 13-form chart is a minimum known reference set; remain alert for other legacy typographic ambiguity.

## Printed-page behaviour

- scans 1–6: no visible printed page number;
- scan 7: printed page **6**;
- scan 8: no visible printed page number;
- scans 9–49: printed pages **8–48**.

Never infer the missing scan-8 number from sequence.

## Exact next activity

**Audit scan 4 only. Do not move beyond one page in that activity.**

Use the same one-page method:

1. inspect the entire scan at enlarged/high resolution;
2. inspect every printed glyph cluster against the complete 13-form historical reference;
3. make only pixel-supported glyph-identity corrections;
4. record the result in the page record and `HISTORICAL_GLYPH_AUDIT.md`;
5. keep scan 4 `needs-review` regardless of whether corrections are found;
6. stop after scan 4 and report the result.

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
