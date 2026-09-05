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

Determine character identity from source pixels and encode that identity in modern Unicode. Do not global-replace or modernize wording, spelling, grammar, punctuation or vocabulary.

## Historical-glyph checkpoint

Confirmed historical corrections now include:

- scan 14 `ஆவலைக்`, `நின்றார்`;
- scan 16 `போகிறாயே`;
- scans 20–24 the corrected `நன்றாக` family and `விழுவேன் என்றானா?`;
- scan 25 `வேலை மட்டுந்தானா?`;
- scan 33 `கண்ணடி` → **`கண்ணாடி`** (`ணா`);
- scan 43 `இளிச்சவாயனுக` → **`இளிச்சவாயனாக`** (`னா`);
- scan 46 `நானு ஆள்?` → **`நானா ஆள்?`** (`னா`);
- scan 47 `விட வேணு?` → **`விட வேணா?`** (`ணா`).

The last four were discovered during the dedicated whole-work source audit by direct enlarged-pixel and same-edition comparison. No page is verified.

## Full canonical coverage checkpoint

Canonical page records exist for **all 49 / 49 scans**.

The dedicated full Tamil source/audit review is now **COMPLETE — all 49 scans directly reviewed**.

Final-source findings directly reconfirmed:

- scan 41 `கல்யா` + scan 42 `ணத்தை` → **`கல்யாணத்தை`**;
- scan 43 `கடவுள்` + scan 44 `பொறுப்பாரா?` → **`கடவுள் பொறுப்பாரா?`**;
- scan 46 `காரண` + scan 47 `மாயிருந்தேன்!` → **`காரணமாயிருந்தேன்!`**;
- scan 47 `எழுதி` + scan 48 `யிருந்தாள்.` → **`எழுதியிருந்தாள்.`**;
- scan 48 `ஒரு பெரிய` + scan 49 `ஜோதி நிரந்தரமாக...` → **`ஒரு பெரிய ஜோதி நிரந்தரமாக...`**;
- narrative ends at **`...எங்களிடம் வரவேண்டும், தெரியுமா?`**;
- separate printer colophon: **`ஸ்ரீமகள் அச்சகம், சென்னை-1`**.

## Dedicated full Tamil source/audit review

Completed:

- **Batch 1 — scans 1–10 / 49**;
- **Batch 2 — scans 11–20 / 49**;
- **Batch 3 — scans 21–30 / 49**;
- **Batch 4 — scans 31–40 / 49**;
- **Batch 5 — scans 41–49 / 49**.

Dedicated-pass result:

- new independent lexical/source-text corrections: **0**;
- new historical-glyph corrections: **4 — scans 33, 43, 46, 47**;
- printed-page mapping directly confirmed through printed page **48**;
- all six internal headings directly reconfirmed as internal structure within one continuous work.

Detailed record: `works/periya-idathup-pen/FULL_TAMIL_SOURCE_AUDIT.md`.

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **49 / 49**;
- dedicated full-source audit: **COMPLETE — 49 / 49 directly reviewed**;
- remaining full-source audit coverage: **0**;
- `verified`: **0**;
- `needs-review`: **49**;
- verification freeze: **ACTIVE**;
- Tamil source-comparison audit: **COMPLETE**;
- assembled Tamil: **READY AS NEXT PHASE / not started**;
- English translation: **BLOCKED pending assembled Tamil**;
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

Build the **assembled Tamil reading layer** from the canonical 49-page layer.

Required rules:

1. preserve canonical page records as the higher authority;
2. keep all 49 canonical pages `needs-review` under the active verification freeze;
3. assemble by the source's internal textual structure, not invented chapters;
4. join only positively established physical page-boundary fragments;
5. retain reversible source provenance/comments for every join;
6. include the separate final printer colophon as non-narrative source matter;
7. run an assembled-Tamil consistency audit before marking the assembled layer complete;
8. do not begin English translation until that assembled-Tamil audit is complete.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
