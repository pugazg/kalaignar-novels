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

The user identified historical/pre-reform Tamil glyph misreadings. The full known Periyar-reform reference set is:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Determine character identity from source pixels and encode that identity in modern Unicode. Do not global-replace or modernize wording, spelling, grammar, or punctuation. Every page remains `needs-review` while the retrospective audit is open.

## Confirmed glyph corrections already made

- scan 20 / printed 19: `நன்றுகத்` → `நன்றாகத்`;
- scan 21 / printed 20: `நன்றுகத்தான்` → `நன்றாகத்தான்`;
- scan 24 / printed 23: `நன்றுக` → `நன்றாக`;
- scan 24 / printed 23: `விழுவேன் என்றுனா?` → `விழுவேன் என்றானா?`.

## Independent source-text corrections found during the retrospective pass

- scan 4: `சமூகத்தின்` → `சமுதாயத்தின்`;
- scan 5: `அற்பிய` → `அரும்பிய`;
- scan 5: `சமூகமும்` → `சமுதாயம்`;
- scan 7 / printed 6: `உள்ளங்களை` → `உள்ளங்களே`;
- scan 12 / printed 11: `தாவும்போது பயப்பட்ட பூனை` → `தாவும்போது பயப்படாத பூனை`;
- scan 12 / printed 11: `பயப்பட்டது போல -` → `பயப்பட்டதுபோல -`.

## Retrospective historical-glyph audit progress

Scans **1–13** have now been re-audited page by page at enlarged/high resolution. Every audited page remains `needs-review`.

Recent five-page batch findings:

- **scan 9 / printed 8:** historical `லை / ளை / னா / னை / ணை` occurrences checked; no text correction;
- **scan 10 / printed 9:** old-form `றா` in `என்றான்` checked explicitly against the user-supplied chart, together with other `ணை / னை / னா / லை` forms; no text correction;
- **scan 11 / printed 10:** historical `னா / னை / லை / ளை` forms checked; no text correction; final `கிடப்ப` continues into scan 12;
- **scan 12 / printed 11:** historical forms were already encoded correctly, but direct source comparison corrected `பயப்பட்ட பூனை` → `பயப்படாத பூனை` and `பயப்பட்டது போல -` → `பயப்பட்டதுபோல -`;
- **scan 13 / printed 12:** historical `ணை / னை / னா / லை` forms checked; no text correction.

For occurrence-level details use `works/periya-idathup-pen/HISTORICAL_GLYPH_AUDIT.md` and the individual page records.

**Progress: 13 / 27 existing canonical scans re-audited; scans 14–27 pending.**

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **27 / 49 — scans 1–27**;
- `verified`: **0**;
- `needs-review`: **27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- historical-glyph audit: **OPEN — 13 / 27**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **BLOCKED**;
- English translation: **BLOCKED**;
- source PDF committed: **No**.

Printed-page behavior remains: scans 1–6 unnumbered; scan 7 visibly printed **6**; scan 8 unnumbered; scans 9–49 visibly printed **8–48**.

Structural observations retained provisionally:

- scan 15 / printed 14 contains internal heading `உத்தண்டி`;
- scan 19 / printed 18 contains internal heading `கண்ணம்மா`;
- scan 27 begins an internal parenthetical recollection involving தலையாரி உத்தண்டி.

## Exact next activity

**Audit scans 14–18 / printed pages 13–17 as the next five-page batch.**

For each scan independently:

1. inspect the complete page at enlarged/high resolution;
2. check every printed glyph cluster against the complete 13-form historical reference and remain alert for other legacy ambiguity;
3. make only pixel-supported glyph-identity or independent source-text corrections;
4. record findings in the page record and audit trackers;
5. keep the page `needs-review`;
6. stop after scan 18.

Do not continue to scan 19, scans 28–32, assembled Tamil, or English translation in that activity.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
