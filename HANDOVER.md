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

- scans **1–27**: retrospective historical-glyph audit complete;
- scans **28–49**: glyph-aware first-pass transcription complete;
- confirmed historical corrections now include `ஆவலைக்`, `நின்றார்`, `போகிறாயே`, the `நன்றாக` family, `விழுவேன் என்றானா?`, `வேலை மட்டுந்தானா?`, and scan-33 **`கண்ணடி` → `கண்ணாடி` (`ணா`)**;
- the scan-33 correction was newly discovered in the dedicated whole-work audit by direct same-page comparison with `வீணாக்கிக்`;
- no page is verified.

## Full canonical coverage checkpoint

Canonical page records exist for **all 49 / 49 scans**.

Known final-source boundary findings remain to be rechecked in the final dedicated batch:

- scan 47 `எழுதி` + scan 48 `யிருந்தாள்.` → **`எழுதியிருந்தாள்.`**;
- scan 48 `ஒரு பெரிய` + scan 49 `ஜோதி நிரந்தரமாக...` → **`ஒரு பெரிய ஜோதி நிரந்தரமாக...`**;
- narrative ends at **`...எங்களிடம் வரவேண்டும், தெரியுமா?`**;
- separate printer colophon: **`ஸ்ரீமகள் அச்சகம், சென்னை-1`**.

## Dedicated full Tamil source/audit review

Completed:

- **Batch 1 — scans 1–10 / 49**;
- **Batch 2 — scans 11–20 / 49**;
- **Batch 3 — scans 21–30 / 49**;
- **Batch 4 — scans 31–40 / 49**.

Current result through scan 40:

- new independent lexical/source-text corrections in the dedicated pass: **0**;
- new historical-glyph corrections in the dedicated pass: **1 — scan 33 `கண்ணடி` → `கண்ணாடி` (`ணா`)**;
- internal headings `குமுதா` (scan 32) and `வீரன்` (scan 38) were directly reconfirmed in Batch 4;
- scans 31–40 directly confirm printed pages **30–39**;
- all other canonical readings in Batch 4 remain source-supported.

Important Batch-4 boundaries:

- inbound scan 30 `உலகநாதர் குமுதாவிடம் கொண்டிருக்கும்` + scan 31 `ஆசை வரையில் கூறிவிட்டேன்.` → phrase continuity;
- scan 33 `சதா` + scan 34 `என் இருதயப் பீடத்திலே...` → phrase continuity;
- scan 35 `அத` + scan 36 `னுடைய` → **`அதனுடைய`**;
- scan 36 `தூக்கிச்` + scan 37 `சென்றதாக` → **`தூக்கிச் சென்றதாக`**;
- scan 37 closes குமுதாவின் signed statement; scan 38 begins internal heading `வீரன்`;
- scan 39 `ஈரமில்லாத` + scan 40 `தொண்டைக்...` → phrase continuity;
- scan 40 `தேவையான` + scan 41 `பொருளாகிவிட்டேன்.` → **`தேவையான பொருளாகிவிட்டேன்.`**. Scan 41 was checked only as the outbound anchor and is not counted as fully reviewed.

Detailed record: `works/periya-idathup-pen/FULL_TAMIL_SOURCE_AUDIT.md`.

## Current stage

- source registration: complete;
- page map: **49 / 49**;
- canonical records: **49 / 49**;
- dedicated full-source audit: **40 / 49 reviewed — IN PROGRESS**;
- remaining full-source audit coverage: **9 scans — 41–49**;
- `verified`: **0**;
- `needs-review`: **49**;
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

Complete the dedicated **full Tamil source/audit review with scans 41–49 / printed pages 40–48**.

Required focus:

1. compare every remaining canonical page directly against the attached scan;
2. treat scan 41 as a full page, not merely the previous outbound anchor;
3. recheck source-sensitive / unusual lexical readings and all 13 historical-glyph families;
4. confirm internal heading `உலகநாதர்` on scan 45 and `கண்ணம்மா` on scan 46;
5. validate every physical page-boundary join through scan 49;
6. explicitly recheck scan 47 `எழுதி` + scan 48 `யிருந்தாள்.` and scan 48 `ஒரு பெரிய` + scan 49 `ஜோதி நிரந்தரமாக...`;
7. recheck final source-specific forms and printer colophon `ஸ்ரீமகள் அச்சகம், சென்னை-1`;
8. keep every page `needs-review`;
9. do **not** mark pages verified, build assembled Tamil sections, or begin English translation.

---

## Completed prior work — புதையல்

The prior `புதையல்` work remains unchanged at its durable release state: 448/448 canonical records, 446 completed, two physical-loss scans 223–224 still `needs-review`, assembled Tamil complete, whole-work English verified, release-ready with those two qualifications.
