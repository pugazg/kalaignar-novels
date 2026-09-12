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
- visible printed-page mapping: **scan5 = —; scan6 = 4; scan7 = 5; scan8 = 6; scan9 = 7**;
- T2 corrections: **1**;
- T3 corrections: **6**;
- unresolved historical glyphs after T2/T3: **0**;
- source PDF excluded from repository.

Open:

- SHA-256 checksum;
- complete-source / terminal reconciliation against a full **198-page** representation;
- complete per-scan page-type / visible printed-page mapping for the remaining body;
- T1 onward from scan 10;
- later whole-work Tamil audit.

Canonical body transcription is verified through **scan 9**. No OCR output or external transcription has been accepted as source authority.

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

## Exact next activity

Process **T1 scans 10–14 only** from the attached PDF/source pixels. Create five `needs-review` canonical page records, update controls, commit, and stop before scan 15. The full-source/terminal issue remains deferred.
