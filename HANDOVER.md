# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Before changing the active work, read the root guide/README/handover plus the active work README, `HISTORICAL_GLYPH_AUDIT.md`, metadata, page map, audit, and relevant page records. The attached PDF remains controlling and must not be committed.

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

## Confirmed historical-glyph corrections

- scan 14 / printed 13: `ஆவிலைக்` → **`ஆவலைக்`** (`லை`);
- scan 14 / printed 13: `நின்றூர்` → **`நின்றார்`** (`றா`);
- scan 16 / printed 15: `போகிறயே` → **`போகிறாயே`** (`றா`);
- scan 20 / printed 19: `நன்றுகத்` → **`நன்றாகத்`** (`றா`);
- scan 21 / printed 20: `நன்றுகத்தான்` → **`நன்றாகத்தான்`** (`றா`);
- scan 24 / printed 23: `நன்றுக` → **`நன்றாக`** (`றா`);
- scan 24 / printed 23: `விழுவேன் என்றுனா?` → **`விழுவேன் என்றானா?`** (`றா`);
- scan 25 / printed 24: `வேலை மட்டுந்தானு?` → **`வேலை மட்டுந்தானா?`** (`னா`).

The scan-25 finding confirms the issue is not limited to old `றா`; the historical `னா` shape also caused an apparent-modern-shape misreading.

## Independent source-text corrections found during retrospective audit

- scan 4: `சமூகத்தின்` → `சமுதாயத்தின்`;
- scan 5: `அற்பிய` → `அரும்பிய`;
- scan 5: `சமூகமும்` → `சமுதாயம்`;
- scan 7 / printed 6: `உள்ளங்களை` → `உள்ளங்களே`;
- scan 12 / printed 11: `தாவும்போது பயப்பட்ட பூனை` → `தாவும்போது பயப்படாத பூனை`;
- scan 12 / printed 11: `பயப்பட்டது போல -` → `பயப்பட்டதுபோல -`;
- scan 19 / printed 18: `செக்கச் செவேலென்றோன்றின.` → **`செக்கச் செவேலென்றேதோன்றின.`**.

## Retrospective historical-glyph audit — completed checkpoint

Scans **1–27** have now all been re-audited at enlarged/high resolution against the full 13-form reference. **Retrospective progress: 27 / 27 existing canonical scans — COMPLETE.** Every page remains `needs-review`.

Final four-page batch, scans **24–27 / printed 23–26**:

- scan 24: earlier `நன்றாக` and `விழுவேன் என்றானா?` historical-`றா` corrections directly re-confirmed; no new correction;
- scan 25: historical `னா` corrected `மட்டுந்தானு?` → `மட்டுந்தானா?`;
- scans 26–27: full 13-form sweep; no canonical text correction;
- scan 27 still ends inside a parenthetical sentence and must be continued only from scan 28.

For occurrence-level details use `works/periya-idathup-pen/HISTORICAL_GLYPH_AUDIT.md` and the individual page records.

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **27 / 49 — scans 1–27**;
- `verified`: **0**;
- `needs-review`: **27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- retrospective historical-glyph audit over existing canonical pages: **COMPLETE — 27 / 27**;
- verification freeze: **ACTIVE**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **BLOCKED**;
- English translation: **BLOCKED**;
- source PDF committed: **No**.

Printed-page behavior remains: scans 1–6 unnumbered; scan 7 visibly printed **6**; scan 8 unnumbered; scans 9–49 visibly printed **8–48**.

Structural observations retained provisionally:

- scan 15 / printed 14 contains internal heading `உத்தண்டி`;
- scan 19 / printed 18 contains internal heading `கண்ணம்மா`;
- scan 27 begins an internal parenthetical recollection involving தலையாரி உத்தண்டி;
- scan 32 is expected to contain internal heading `குமுதா`, to be confirmed directly from source.

Boundary evidence through scan 27 remains physical-source evidence only and does not confer verification.

## Exact next activity

**Resume canonical transcription at scans 28–32 / printed pages 27–31.**

For each scan independently:

1. inspect the complete page at enlarged/high resolution;
2. apply the complete 13-form historical reference during first transcription and remain alert for other legacy ambiguity;
3. resolve scan 27's open parenthetical continuation only from the visible opening of scan 28;
4. preserve exact source spelling, punctuation, paragraphing and physical page boundaries;
5. treat scan 32's `குமுதா` as an internal textual heading if visibly confirmed;
6. create every new page as `needs-review`; do not mark anything `verified`;
7. update page-map, audit, work/root READMEs and HANDOVER;
8. stop after scan 32.

Do not begin assembled Tamil or English translation.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
