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

Determine character identity from source pixels and encode that identity in modern Unicode. Do not global-replace or modernize wording, spelling, grammar, punctuation, or vocabulary. Every canonical page remains `needs-review` while the retrospective audit is open.

## Confirmed historical-glyph corrections

- scan 14 / printed 13: `ஆவிலைக்` → **`ஆவலைக்`** (`லை`);
- scan 14 / printed 13: `நின்றூர்` → **`நின்றார்`** (`றா`);
- scan 16 / printed 15: `போகிறயே` → **`போகிறாயே`** (`றா`);
- scan 20 / printed 19: `நன்றுகத்` → **`நன்றாகத்`** (`றா`);
- scan 21 / printed 20: `நன்றுகத்தான்` → **`நன்றாகத்தான்`** (`றா`);
- scan 24 / printed 23: `நன்றுக` → **`நன்றாக`** (`றா`);
- scan 24 / printed 23: `விழுவேன் என்றுனா?` → **`விழுவேன் என்றானா?`** (`றா`).

The scan-24 corrections were established earlier but scan 24 still awaits its formal retrospective page-audit pass.

## Independent source-text corrections found during retrospective audit

- scan 4: `சமூகத்தின்` → `சமுதாயத்தின்`;
- scan 5: `அற்பிய` → `அரும்பிய`;
- scan 5: `சமூகமும்` → `சமுதாயம்`;
- scan 7 / printed 6: `உள்ளங்களை` → `உள்ளங்களே`;
- scan 12 / printed 11: `தாவும்போது பயப்பட்ட பூனை` → `தாவும்போது பயப்படாத பூனை`;
- scan 12 / printed 11: `பயப்பட்டது போல -` → `பயப்பட்டதுபோல -`;
- scan 19 / printed 18: `செக்கச் செவேலென்றோன்றின.` → **`செக்கச் செவேலென்றேதோன்றின.`**.

## Retrospective historical-glyph audit progress

Scans **1–23** have now been re-audited page by page at enlarged/high resolution. Every audited page remains `needs-review`.

Latest ten-page batch, scans **14–23 / printed 13–22**:

- scan 14: two historical-form corrections — `ஆவலைக்`, `நின்றார்`;
- scan 15: no text correction; `உத்தண்டி` remains an internal heading;
- scan 16: historical `றா` correction — `போகிறாயே`;
- scans 17–18: no canonical text correction;
- scan 19: direct source-text correction — `செக்கச் செவேலென்றேதோன்றின.`; `கண்ணம்மா` remains an internal heading;
- scans 20–21: earlier `நன்றாகத்` / `நன்றாகத்தான்` historical-`றா` corrections re-confirmed; no new correction;
- scans 22–23: no canonical text correction.

For occurrence-level details use `works/periya-idathup-pen/HISTORICAL_GLYPH_AUDIT.md` and the individual page records.

**Progress: 23 / 27 existing canonical scans re-audited; scans 24–27 pending.**

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **27 / 49 — scans 1–27**;
- `verified`: **0**;
- `needs-review`: **27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- historical-glyph audit: **OPEN — 23 / 27**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **BLOCKED**;
- English translation: **BLOCKED**;
- source PDF committed: **No**.

Printed-page behavior remains: scans 1–6 unnumbered; scan 7 visibly printed **6**; scan 8 unnumbered; scans 9–49 visibly printed **8–48**.

Structural observations retained provisionally:

- scan 15 / printed 14 contains internal heading `உத்தண்டி`;
- scan 19 / printed 18 contains internal heading `கண்ணம்மா`;
- scan 27 begins an internal parenthetical recollection involving தலையாரி உத்தண்டி.

Boundary evidence through scan 23 remains physical-source evidence only and does not confer verification.

## Exact next activity

**Audit scans 24–27 / printed pages 23–26 as the remaining four-page retrospective batch.**

For each scan independently:

1. inspect the complete page at enlarged/high resolution;
2. check every printed glyph cluster against the complete 13-form historical reference and remain alert for other legacy ambiguity;
3. re-confirm the already known scan-24 `றா` corrections from the source;
4. make only pixel-supported glyph-identity or independent source-text corrections;
5. record findings in the page record and audit trackers;
6. keep every page `needs-review`;
7. stop after scan 27.

Do not continue to scans 28–49, assembled Tamil, or English translation in that activity.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
