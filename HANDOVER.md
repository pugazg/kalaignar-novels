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

The reusable root `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` is now the general procedure for future older-Tamil works. It records the 13-form reference, same-edition comparison method, OCR caution, distinction between glyph decoding and spelling modernization, uncertainty handling, page/audit templates, and lessons from `பெரிய இடத்துப் பெண்` and `புதையல்`.

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

Scans **1–27** completed the retrospective page-by-page historical-glyph audit. Scans **28–42** were transcribed with the complete 13-form rule applied during first pass.

Latest source-first batch, scans **38–42 / printed pages 37–41**:

- scan 38: internal heading **`வீரன்`** directly confirmed; `வளைவுகள்` (`ளை`), `பண்ணைத்` (`ணை`), `கல்யாணம்` (`ணா`) and related clusters checked;
- scan 39: `இன்னொருநாள்` (`னொ`) and `மற்றொருநாள்` (`றொ`) checked by historical identity; final `ஈரமில்லாத` continues to scan 40;
- scan 40: opening `தொண்டைக்` continues scan 39; `பண்ணையைப்` checked as historical `ணை`; final `தேவையான` continues to scan 41;
- scan 41: opening `பொருளாகிவிட்டேன்.` establishes `தேவையான பொருளாகிவிட்டேன்.`; `புரியவில்லையே` was checked as a complete old/faint `லை`-family cluster; final `கல்யா` remains a physical page split;
- scan 42: opening `ணத்தை` establishes `கல்யாணத்தை`; historical `லை / ளை / னை / ணா` families checked; page ends cleanly.

No post-entry glyph correction was required in scans 38–42 because character identities were decoded before canonical entry. All scans 1–42 remain `needs-review`.

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **42 / 49 — scans 1–42**;
- `verified`: **0**;
- `needs-review`: **42**;
- `partial`: **0**;
- `not-started`: **7 — scans 43–49**;
- retrospective historical-glyph audit on scans 1–27: **COMPLETE**;
- glyph-aware first-pass transcription: **complete through scan 42**;
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
- scan 38 / printed 37 — `வீரன்`.

Scan 45 is expected to contain `உலகநாதர்` and scan 46 is expected to contain `கண்ணம்மா`, but both must be directly confirmed from source before being recorded as structure.

## Exact next activity

**Transcribe scans 43–47 / printed pages 42–46.**

For each scan independently:

1. inspect the complete page at enlarged/high resolution;
2. apply the complete reusable historical-glyph procedure and all 13 known reform-sensitive forms during first transcription;
3. directly confirm the expected internal heading `உலகநாதர்` on scan 45 and `கண்ணம்மா` on scan 46 before recording either;
4. preserve exact source spelling, punctuation, paragraphing and physical page boundaries;
5. create every page as `needs-review`; do not mark anything `verified`;
6. update page-map, historical-glyph audit, general audit, work/root READMEs and HANDOVER;
7. stop after scan 47.

Do not begin scan 48, assembled Tamil, or English translation in that activity.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
