# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Before changing the active work, read the root guides/README/handover plus the active work README, `HISTORICAL_GLYPH_AUDIT.md`, metadata, page map, audit, and relevant page records. The attached PDF remains controlling and must not be committed.

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
- sales rights: **எம். எஸ். ராஜுலு கம்பெனி, 286, சைனா பஜார், சென்னை-1**.

## Verification freeze

**Do not mark any page in this work as `verified`.**

The full known user-supplied Periyar-reform reference set is:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Determine character identity from source pixels and encode that identity in modern Unicode. Do not global-replace or modernize wording, spelling, grammar, punctuation, or vocabulary. Every canonical page remains `needs-review` under the current user instruction. New pages must use the glyph-aware method from first transcription.

The reusable root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is the general procedure for future older-Tamil works. It records the 13-form reference, same-edition comparison method, OCR caution, distinction between glyph decoding and spelling modernization, uncertainty handling, page/audit templates, and lessons from `பெரிய இடத்துப் பெண்` and `புதையல்`.

## Confirmed historical-glyph corrections from retrospective review

- scan 14 / printed 13: `ஆவிலைக்` → **`ஆவலைக்`** (`லை`);
- scan 14 / printed 13: `நின்றூர்` → **`நின்றார்`** (`றா`);
- scan 16 / printed 15: `போகிறயே` → **`போகிறாயே`** (`றா`);
- scan 20 / printed 19: `நன்றுகத்` → **`நன்றாகத்`** (`றா`);
- scan 21 / printed 20: `நன்றுகத்தான்` → **`நன்றாகத்தான்`** (`றா`);
- scan 24 / printed 23: `நன்றுக` → **`நன்றாக`** (`றா`);
- scan 24 / printed 23: `விழுவேன் என்றுனா?` → **`விழுவேன் என்றானா?`** (`றா`);
- scan 25 / printed 24: `வேலை மட்டுந்தானு?` → **`வேலை மட்டுந்தானா?`** (`னா`).

## Historical-glyph audit checkpoint

Scans **1–27** completed the retrospective page-by-page historical-glyph audit. Scans **28–47** were transcribed with the complete 13-form rule applied during first pass.

Latest source-first batch, scans **43–47 / printed pages 42–46**:

- scan 43: continues the `வீரன்` section; glyph-aware first pass completed; source-specific forms including `போக்கியதைப்`, `ஒடித் தெரியத்`, `இளிச்சவாயனுக`, and `தண்டன்` retained; final `கடவுள்` continues to scan 44;
- scan 44: opening `பொறுப்பாரா?` establishes `கடவுள் பொறுப்பாரா?`; page closes the current `வீரன்` passage with `நான் வண்டிக்கார வீரனா?`;
- scan 45: internal heading **`உலகநாதர்`** directly confirmed; historical-form families checked before entry; page ends with a complete question;
- scan 46: internal heading **`கண்ணம்மா`** directly confirmed; source-specific `நானு ஆள்?` retained; final `காரண` remains a physical page split;
- scan 47: opening `மாயிருந்தேன்!` establishes `காரணமாயிருந்தேன்!`; source-specific `வக்குப் பேதி`, `அவமானந்`, `கல்மனங்`, and `விட வேணு?` retained; final **`எழுதி`** continues onto scan 48 and is intentionally unresolved until the source opening of scan 48 is inspected.

No page in scans 43–47 was marked verified. All canonical scans 1–47 remain `needs-review`.

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **47 / 49 — scans 1–47**;
- `verified`: **0**;
- `needs-review`: **47**;
- `partial`: **0**;
- `not-started`: **2 — scans 48–49**;
- retrospective historical-glyph audit on scans 1–27: **COMPLETE**;
- glyph-aware first-pass transcription: **complete through scan 47**;
- verification freeze: **ACTIVE**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **BLOCKED**;
- English translation: **BLOCKED**;
- source PDF committed: **No**.

Printed-page behavior remains: scans 1–6 unnumbered; scan 7 visibly printed **6**; scan 8 unnumbered; scans 9–49 visibly printed **8–48**.

## Structural observations

Directly confirmed internal headings:

- scan 15 / printed 14 — `உத்தண்டி`;
- scan 19 / printed 18 — `கண்ணம்மா`;
- scan 32 / printed 31 — `குமுதா`;
- scan 38 / printed 37 — `வீரன்`;
- scan 45 / printed 44 — `உலகநாதர்`;
- scan 46 / printed 45 — `கண்ணம்மா`.

All remain internal textual structure within the same continuous work; none of these heading findings confer page verification.

## Exact next activity

**Transcribe the final source batch: scans 48–49 / printed pages 47–48.**

For each scan independently:

1. inspect the complete page at enlarged/high resolution;
2. apply the reusable historical-glyph procedure and all 13 known reform-sensitive forms during first transcription;
3. resolve scan 47's trailing `எழுதி` only from the visible opening of scan 48;
4. preserve exact source spelling, punctuation, paragraphing and physical page boundaries;
5. inspect scan 49's narrative ending and printer-colophon text directly rather than relying on the earlier representative review;
6. create both pages as `needs-review`; do not mark anything `verified`;
7. synchronize page-map, historical-glyph audit, general audit, work/root READMEs and HANDOVER to **49/49 canonical**;
8. stop after scan 49. Do not begin assembled Tamil or English translation in that activity.

After full 49/49 canonical coverage, the subsequent activity must be a dedicated Tamil source/audit review under the verification freeze, not automatic verification or translation.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
