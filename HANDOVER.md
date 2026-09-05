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

The scan-25 finding confirms the issue is not limited to old `றா`; historical `னா` can also produce an apparent-modern-shape misreading.

## Independent source-text corrections found during retrospective audit

- scan 4: `சமூகத்தின்` → `சமுதாயத்தின்`;
- scan 5: `அற்பிய` → `அரும்பிய`;
- scan 5: `சமூகமும்` → `சமுதாயம்`;
- scan 7 / printed 6: `உள்ளங்களை` → `உள்ளங்களே`;
- scan 12 / printed 11: `தாவும்போது பயப்பட்ட பூனை` → `தாவும்போது பயப்படாத பூனை`;
- scan 12 / printed 11: `பயப்பட்டது போல -` → `பயப்பட்டதுபோல -`;
- scan 19 / printed 18: `செக்கச் செவேலென்றோன்றின.` → **`செக்கச் செவேலென்றேதோன்றின.`**.

## Historical-glyph audit checkpoint

Scans **1–27** have completed the retrospective page-by-page historical-glyph audit. Scans **28–37** were transcribed with the complete 13-form rule applied during first pass rather than retrospectively.

Latest source-first batch, scans **33–37 / printed pages 32–36**:

- scan 33: glyph-aware first pass completed; historical identities including `ணா / றா / லை / ளை` were decoded before entry;
- scan 34: glyph-aware first pass completed; `லை / னை` and related historical clusters checked;
- scan 35: historical `ணை` in `ஆணை` and historical `றா` in `நின்றார்` / `தோற்றாய்` were decoded by identity;
- scan 36: `னொ / னை / லை` and related historical clusters checked during first pass;
- scan 37: `னை / னா / ளை` and related clusters checked during first pass; the page visibly closes குமுதாவின் first-person statement with `இப்படிக்கு / இறக்கப் போகும் / குமுதா`.

Physical page-boundary evidence from the latest batch:

- scan 33 `சதா` + scan 34 `என் இருதயப் பீடத்திலே...`;
- scan 35 `அத` + scan 36 `னுடைய` → `அதனுடைய`;
- scan 36 `தூக்கிச்` + scan 37 `சென்றதாக` → `தூக்கிச் சென்றதாக`.

Source spacing/splits were preserved only where truly source-significant; ordinary line/typesetting joins established from the same physical page were normalized into the intended word identity during canonical entry, including `கொள்வதுண்டு`, `கட்டளையிட்டாள்`, and `கண்ணம்மாக்களைக்`.

All scans **1–37** remain `needs-review`. No page is verified.

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **37 / 49 — scans 1–37**;
- `verified`: **0**;
- `needs-review`: **37**;
- `partial`: **0**;
- `not-started`: **12 — scans 38–49**;
- retrospective historical-glyph audit on scans 1–27: **COMPLETE**;
- glyph-aware first-pass transcription: **complete through scan 37**;
- verification freeze: **ACTIVE**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **BLOCKED**;
- English translation: **BLOCKED**;
- source PDF committed: **No**.

Printed-page behavior remains: scans 1–6 unnumbered; scan 7 visibly printed **6**; scan 8 unnumbered; scans 9–49 visibly printed **8–48**.

Structural observations:

- scan 15 / printed 14 — internal heading `உத்தண்டி`;
- scan 19 / printed 18 — internal heading `கண்ணம்மா`;
- scan 32 / printed 31 — internal heading `குமுதா`;
- scan 37 / printed 36 closes குமுதாவின் signed first-person statement;
- scan 38 is expected to contain `வீரன்`, but that must be confirmed directly from source before recording it as an internal heading.

## Exact next activity

**Transcribe scans 38–42 / printed pages 37–41.**

For each scan independently:

1. inspect the complete page at enlarged/high resolution;
2. directly confirm whether scan 38 contains internal heading `வீரன்`;
3. apply the complete 13-form historical reference during first transcription and remain alert for other legacy ambiguity;
4. preserve exact source spelling, punctuation, paragraphing and physical page boundaries;
5. create every page as `needs-review`; do not mark anything `verified`;
6. update page-map, historical-glyph audit, general audit, work/root READMEs and HANDOVER;
7. stop after scan 42.

Do not begin scan 43, assembled Tamil, or English translation in that activity.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
