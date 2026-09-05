# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current target: `works/periya-idathup-pen/`
- Completed reference implementation: `works/balipeedam-nokki/`

Before changing the active work, read the root guide/README/handover plus the active work README, `HISTORICAL_GLYPH_AUDIT.md`, metadata, page map, audit, and relevant page record. The attached PDF remains controlling and must not be committed.

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

Independent source-text corrections found during the retrospective pass:

- scan 4: `சமூகத்தின்` → `சமுதாயத்தின்`;
- scan 5: `அற்பிய` → `அரும்பிய`;
- scan 5: `சமூகமும்` → `சமுதாயம்`.

## Retrospective historical-glyph audit progress

- scan 1: complete; no correction;
- scan 2: complete; later gift label checked, no source-work correction;
- scan 3: complete; `லை / னை / னா` historical forms confirmed and already encoded correctly;
- scan 4: complete; six historical-form occurrences confirmed; one lexical correction;
- scan 5: complete; four historical-form occurrences confirmed; two lexical corrections;
- **scan 6: complete; five historical-form occurrences confirmed; no text correction**.

### Scan 6 finding

Positive historical forms:

- `கருணாநிதி` — `ணா`;
- `நிலையில்` — `லை`;
- `இல்லை` — `லை`;
- `அதனால்` — `னா`;
- `கற்பனைதான்` — `னை`.

All were already encoded correctly. The whole page was re-read at enlarged/high resolution. `வனிதையர்களின்`, `வாலிபக் கிழங்களோடு`, `புரையோடிக்கொண்டிருக்கும்`, and `நம்முன். காட்சியளிக்கத்தான்` remain source-supported. Scan 6 remains `needs-review`.

**Progress: 6 / 27 existing canonical scans re-audited; scans 7–27 pending.**

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **27 / 49 — scans 1–27**;
- `verified`: **0**;
- `needs-review`: **27**;
- `partial`: **0**;
- `not-started`: **22 — scans 28–49**;
- historical-glyph audit: **OPEN — 6 / 27**;
- Tamil source audit: **NOT PASSED**;
- assembled Tamil: **BLOCKED**;
- English translation: **BLOCKED**;
- source PDF committed: **No**.

Printed-page behavior remains: scans 1–6 unnumbered; scan 7 visibly printed **6**; scan 8 unnumbered; scans 9–49 visibly printed **8–48**.

## Exact next activity

**Audit scan 7 only. Do not move beyond one page.**

Inspect the complete scan at enlarged/high resolution, check all 13 known historical forms and any other legacy ambiguity, make only pixel-supported glyph-identity or independent source-text corrections, record the result in the page record and audit trackers, keep scan 7 `needs-review`, and stop.

Do not continue to scan 8, scans 28–32, assembled Tamil, or English translation in that activity.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
