# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Before changing the active work, read the root guides/README/handover plus the active work README, `FULL_TAMIL_SOURCE_AUDIT.md`, `HISTORICAL_GLYPH_AUDIT.md`, metadata, page map, audit, and relevant page records. The attached PDF remains controlling and must not be committed.

## பெரிய இடத்துப் பெண் — source identity

- source: `TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`;
- SHA-256: `50db9c55d670065bd81088ee07e4527f5531a9ab15e3c4533d6b10eda8d09e9628`;
- size: **70,952,481 bytes**;
- scans: **49**;
- title: **பெரிய இடத்துப் பெண்**;
- author: **மு. கருணாநிதி**;
- publisher/place: **திராவிடன் பதிப்பகம் / வேலூர் (வ. ஆ.)**;
- edition: **எட்டாம் பதிப்பு: ஜூலை 1953**;
- price: **விலை 0—8—0**;
- sales rights: **எம். எஸ். ராஜுலு கம்பெனி, 286, சைனா பஜார், சென்னை-1**;
- final printer colophon: **ஸ்ரீமகள் அச்சகம், சென்னை-1**.

## Verification freeze

**Do not mark any page in this work as `verified`.**

Known user-supplied Periyar-reform reference set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Determine character identity from source pixels and encode that identity in modern Unicode. Do not global-replace or modernize wording, spelling, grammar, punctuation, or vocabulary. Every canonical page remains `needs-review` under the current user instruction.

The root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is the reusable procedure for this and future older-Tamil works.

## Historical-glyph checkpoint

- scans **1–27**: retrospective historical-glyph audit complete;
- scans **28–49**: glyph-aware first-pass transcription complete;
- confirmed retrospective corrections include `ஆவிலைக்` → `ஆவலைக்`, `நின்றூர்` → `நின்றார்`, `போகிறயே` → `போகிறாயே`, the `நன்றாக` family corrections, `விழுவேன் என்றானா?`, and `வேலை மட்டுந்தானா?`;
- no page is verified.

## Full canonical coverage checkpoint

Canonical page records exist for **all 49 / 49 scans**.

Final-source boundary findings remain:

- scan 47 `எழுதி` + scan 48 `யிருந்தாள்.` → **`எழுதியிருந்தாள்.`**;
- scan 48 retains source-specific `வேசின்` and `தத்தம்`;
- scan 48 `ஒரு பெரிய` + scan 49 `ஜோதி நிரந்தரமாக...` → **`ஒரு பெரிய ஜோதி நிரந்தரமாக...`**;
- scan 49 retains source-specific `அழுக்குப்பட்டு`, `உச்ச ஸ்தாயியை`, `போகவேண்டு மென்னிருக்கலே`, and `பாடங்`;
- narrative ends at **`...எங்களிடம் வரவேண்டும், தெரியுமா?`**;
- separate printer colophon reads **`ஸ்ரீமகள் அச்சகம், சென்னை-1`**.

## Dedicated full Tamil source/audit review

The post-coverage whole-work audit has now started.

Completed Batch 1: **scans 1–10 / 49**.

Results:

- no new canonical lexical correction was required in scans 1–10;
- no new historical-glyph correction was required;
- front matter, publication details, eighth-edition note, narrative opening and printed-page mapping through scan 10 were reconfirmed directly;
- scan 9 → 10 was explicitly checked: scan 9 ends `அவளை இவருக்குக் கட்டினர்கள்` without a visible terminal mark; scan 10 begins `அதைப் பற்றி உலகம் பேசாமலில்லை.`; preserve the physical boundary without inserting punctuation or claiming a lexical word join.

Detailed record: `works/periya-idathup-pen/FULL_TAMIL_SOURCE_AUDIT.md`.

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **49 / 49**;
- dedicated full-source audit: **10 / 49 reviewed — IN PROGRESS**;
- `verified`: **0**;
- `needs-review`: **49**;
- `partial`: **0**;
- `not-started`: **0**;
- verification freeze: **ACTIVE**;
- Tamil source audit: **NOT PASSED — in progress**;
- assembled Tamil: **BLOCKED**;
- English translation: **BLOCKED**;
- source PDF committed: **No**.

Printed-page behavior: scans 1–6 unnumbered; scan 7 printed **6**; scan 8 unnumbered; scans 9–49 printed **8–48**.

## Structural observations

Directly confirmed internal headings:

- scan 15 / printed 14 — `உத்தண்டி`;
- scan 19 / printed 18 — `கண்ணம்மா`;
- scan 32 / printed 31 — `குமுதா`;
- scan 38 / printed 37 — `வீரன்`;
- scan 45 / printed 44 — `உலகநாதர்`;
- scan 46 / printed 45 — `கண்ணம்மா`.

These remain internal textual structure within one continuous work.

## Exact next activity

Continue the dedicated **full Tamil source/audit review with scans 11–20 / printed pages 10–19**.

Required focus:

1. compare every canonical page directly against the attached scan;
2. recheck source-sensitive / unusual lexical readings;
3. recheck historical-glyph consistency using the reusable guide;
4. explicitly revisit the documented scan-12 source-text corrections, scan-19 source-text correction and scan-20 `றா` correction;
5. validate physical page-boundary joins and printed-page numbering;
6. document unresolved items explicitly;
7. keep every page `needs-review` under the current user instruction;
8. do **not** mark pages verified, build assembled Tamil sections, or begin English translation.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
