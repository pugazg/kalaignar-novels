# Audit — சுருளிமலை

## Intake gate

Status: **IN PROGRESS**.

Completed:

- live repository checked and current work continued in `works/surulimalai/`;
- root processing guides reviewed;
- attached source inspected directly at the opening;
- title / author / publisher / edition verified from source scans;
- source size / attached-artifact scan count registered;
- user correction/source identity recorded: this copy has **198 pages**; the ChatGPT Files parser currently exposes only **150 pages**;
- front matter scans 1–4: **VERIFIED**;
- T1 scans **5–9: COMPLETE / PASS — 5/5**;
- T2 scans **5–9: COMPLETE / PASS — 5/5**;
- T3 scans **5–9: COMPLETE / PASS — 5/5**;
- scans 5–9 canonical page records: **5/5 VERIFIED**;
- T1 scans **10–14: COMPLETE / PASS — 5/5**;
- scans 10–14 canonical page records: **5/5 VERIFIED**;
- visible printed-page mapping added: **scan10 = 8; scan11 = 9; scan12 = 10; scan13 = 11; scan14 = — / chapter no. 1**;
- visible printed-page mapping: **scan5 = —; scan6 = 4; scan7 = 5; scan8 = 6; scan9 = 7**;
- T2 corrections: **1**;
- T3 corrections: **6**;
- unresolved historical glyphs after T2/T3: **0**;
- source PDF excluded from repository.

Open:

- SHA-256 checksum;
- complete-source / terminal reconciliation against a full **198-page** representation;
- complete per-scan page-type / visible printed-page mapping for the remaining body;
- T3 final source-fidelity review for scans 15–19;
- T1 onward from scan 20;
- later whole-work Tamil audit.

Canonical body transcription is **verified through scan 14**; scans **15–19 have T1/T2 complete and remain `needs-review` pending T3**. No OCR output or external transcription has been accepted as source authority. No OCR output or external transcription has been accepted as source authority.

## Source-ingestion correction

The attached source is the registered source copy whose complete extent is **198 pages**.

In this chat, the Files service reports `num_pages: 150`. That parser/ingestion result is **not authoritative** for source extent or terminal structure.

Consequences:

- the earlier “150 scans vs 198 printed pages” reconciliation remains withdrawn;
- the claim that scans 140–149 equal printed pages 189–198 remains withdrawn;
- the claim that scan149 is the narrative ending and scan150 is the back cover remains **invalidated**;
- early parser-visible pages may still be processed in bounded source-pixel batches;
- terminal reconciliation remains blocked until a complete 198-page source representation is available.

## Terminal-boundary audit status

Previous result: **INVALIDATED / DO NOT USE**.

Current status: **UNKNOWN / RE-AUDIT REQUIRED ON FULL SOURCE**.

## Scans 5–9 gate results

| Scan | Printed page | T1 | T2 | T3 | Final |
|---:|---:|---|---|---|---|
| 5 | — | PASS | PASS | PASS | **verified** |
| 6 | 4 | PASS | PASS | PASS | **verified** |
| 7 | 5 | PASS | PASS | PASS | **verified** |
| 8 | 6 | PASS | PASS | PASS | **verified** |
| 9 | 7 | PASS | PASS | PASS | **verified** |

### T2 correction

- scan9 — `கிட்டவில்ல` → `கிட்டவில்லை` — historical `லை` identity.

### T3 correction ledger

- scan5 — `அவள் ஊரார் அறிவர்.` → `அவளை ஊரார் அறிவர்.`;
- scan6 — `வாசகர்கள் இழுத்துச்` → `வாசகர்களை இழுத்துச்`;
- scan6 — `அறிவிக்கப்பட வேண்டியதில்லை` → source-printed `அறிவிக்கப்பட்ட வேண்டியதில்லை`;
- scan8 — `தோத்திரித்தேன்` → source-printed `தோத்தரித்தேன்`;
- scan8 — `வேதனைகளானாள்` → source-printed `வேதனைக்கலமானாள்`;
- scan9 — `கவலையால்` → source-printed `கவலியால்`.

T3 also confirmed:

- no omitted or duplicated body span remains on scans 5–9;
- paragraph boundaries match the source;
- printed-page mapping is source-visible;
- scan6→7 and scan8→9 continuity is preserved without silent joining;
- scan9 later blue/purple annotations are excluded from printed prose;
- scan9 ending `புல்லாங்` is preserved without consulting scan10;
- T2 historical-glyph decisions remain source-supported;
- unresolved historical glyphs: **0**.

Checkpoint: [`T1_BATCH_005_009.md`](T1_BATCH_005_009.md).

## T1/T2/T3 scans 10–14

T1: **COMPLETE / PASS — 5/5**.  
T2: **COMPLETE / PASS — 5/5; 2 corrections; unresolved historical/source-form readings 0**.  
T3: **COMPLETE / PASS — 5/5 VERIFIED; 3 corrections**.

| Scan | Printed page | Record | T1 |
|---:|---:|---|---|
| 10 | 8 | `pages/0010-page-8.md` | PASS / needs-review |
| 11 | 9 | `pages/0011-page-9.md` | PASS / needs-review |
| 12 | 10 | `pages/0012-page-10.md` | PASS / needs-review |
| 13 | 11 | `pages/0013-page-11.md` | PASS / needs-review |
| 14 | — | `pages/0014-chapter-1.md` | PASS / needs-review |

T2 correction ledger:

- scan12 — `சிறிதுமில்லாதான்` → `சிறிதுமில்லைதான்` — historical `லை` identity;
- scan14 — `வேய்ங்குழலில்` → `வேய்குழலில்` — direct-pixel source-form correction.

T2 confirmed without change:

- scan10 `வாதீன`;
- scan11 `அவளத் தேவதையின்`, `நினைப்புடைய இளைஞன்`;
- scan12 `அடி யெடுத்து`, `கண்ட தில்லை`, `இல்லை யெனப்`, `பூக்கரகம்`;
- scan13 `ஒரு பைத்தியத்தை மகனைத்`;
- scan14 `கண்டு பிடித்தான பிறகு`, `செய்கின்றன வென்று`.

T3 correction ledger:

- scan10 — `அவர்களே வீட்டுக்குள் ஓடச் செய்யும்!` → `அவர்களை வீட்டுக்குள் ஓடச் செய்யும்!`;
- scan12 — `எவ்வளவு அமைதியாக யார் யாருக்கும் தெரியாமல்` → `எவ்வளவு அமைதியாக யாருக்கும் தெரியாமல்`;
- scan12 — `கதிரவன் நீராவியாக்குவது,` → `கதிரவன் நீராவியாக்குவதும்,`.

T3 also confirmed:

- no omitted or duplicated body span remains on scans 10–14;
- paragraph boundaries and visible page numbers match the source;
- scan9→10 and scan12→13 continuities remain physically separated without silent joins;
- scan13 ending `போவர்` is preserved without invented punctuation;
- scan14 large title + chapter number **1** are structural source content, not a page number;
- later blue/purple annotations on scans11 and 14 remain excluded;
- T2 source-form decisions remain source-supported;
- unresolved historical/source-form readings: **0**.

Structural/source observations:

- scan10 begins `குழல்`, physically continuing scan9's `புல்லாங்`;
- scan12 ends `எடுப்பார்`; scan13 begins `கைப்பிள்ளை!`;
- scan13 ends `போவர்` without invented punctuation;
- scan14 begins the chapter layer with large `சுருளிமலை` and chapter number **1**; no visible printed page number is recorded;
- later blue/purple marks on scans11 and 14 are excluded;
- T2 difficult clusters have now been independently resolved/confirmed; unresolved historical/source-form readings: **0**.

Checkpoint: [`T1_BATCH_010_014.md`](T1_BATCH_010_014.md).

## T1/T2 scans 15–19

T1: **COMPLETE / PASS — 5/5 canonical records**.  
T2: **COMPLETE / PASS — 5/5; 5 corrections; unresolved historical/source-form readings 0**.

| Scan | Printed page | Record | T1 |
|---:|---:|---|---|
| 15 | 13 | `pages/0015-page-13.md` | PASS / needs-review |
| 16 | 14 | `pages/0016-page-14.md` | PASS / needs-review |
| 17 | 15 | `pages/0017-page-15.md` | PASS / needs-review |
| 18 | 16 | `pages/0018-page-16.md` | PASS / needs-review |
| 19 | 17 | `pages/0019-page-17.md` | PASS / needs-review |

Structural/source observations:

- scan15 begins printed page **13** and contains a classical quotation followed by explicit attribution to இளங்கோவடிகள் / சிலப்பதிகாரம்;
- scan17 ends `தீச்சட்டி`; scan18 continues `சிங்காரந்தான்`;
- scan19 ends `காலையில்`; scan20 was not opened;
- T2 resolved the difficult historical/source-form targets from source pixels only.

T2 correction ledger:

- scan15 — `தவறுமல்` → `தவறாமல்` — historical `றா`;
- scan16 — `எதுவுமே யில்ல` → `எதுவுமே யில்லை` — historical `லை`;
- scan16 — `யாருமில்லதான்` → `யாருமில்லைதான்` — historical `லை`;
- scan18 — `வேணுங்கிறன்` → `வேணுங்கிறான்` — historical `றா`;
- scan19 — `என்னைத் அம்மமேலே` → `என்னத்த அம்மமேலே` — direct source-form correction.

Unresolved historical/source-form readings after T2: **0**.

Checkpoint: [`T1_BATCH_015_019.md`](T1_BATCH_015_019.md).

## Exact next activity

Perform **T3 final source-fidelity review for scans 15–19 only** from the attached PDF/source pixels. Check full-page fidelity, promote only pages that pass, update controls, commit, and stop before scan20. The full-source/terminal issue remains deferred.
