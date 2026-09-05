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

Canonical page records now exist for **all 49 / 49 scans**.

Latest final batch, scans **48–49 / printed pages 47–48**:

- scan 47 `எழுதி` + scan 48 `யிருந்தாள்.` → **`எழுதியிருந்தாள்.`**;
- scan 48 retains source-specific `வேசின்` and `தத்தம்` after direct enlarged source review;
- scan 48 `ஒரு பெரிய` + scan 49 `ஜோதி நிரந்தரமாக...` → **`ஒரு பெரிய ஜோதி நிரந்தரமாக...`**;
- scan 49 retains source-specific `அழுக்குப்பட்டு`, `உச்ச ஸ்தாயியை`, `போகவேண்டு மென்னிருக்கலே`, and `பாடங்`;
- narrative visibly ends at **`...எங்களிடம் வரவேண்டும், தெரியுமா?`**;
- separate printer colophon directly reads **`ஸ்ரீமகள் அச்சகம், சென்னை-1`**.

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **49 / 49**;
- `verified`: **0**;
- `needs-review`: **49**;
- `partial`: **0**;
- `not-started`: **0**;
- verification freeze: **ACTIVE**;
- Tamil source audit: **NOT PASSED**;
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

Perform a dedicated **full Tamil source/audit review** over the completed 49-page canonical layer.

Required focus:

1. recheck source-sensitive / unusual lexical readings against the scan;
2. recheck historical-glyph consistency using the reusable guide;
3. validate all physical page-boundary joins;
4. confirm page numbering, metadata and internal structural continuity;
5. document unresolved items explicitly;
6. keep every page `needs-review` under the current user instruction;
7. do **not** mark pages verified, build assembled Tamil sections, or begin English translation in that activity.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
