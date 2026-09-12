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
- front matter scans 1–4 recorded and marked verified;
- T1 scans **5–9: COMPLETE / PASS — 5/5**;
- T2 historical-glyph review scans **5–9: COMPLETE / PASS — 5/5**;
- five canonical body records remain `needs-review` pending T3;
- visible printed-page mapping recorded only where directly printed: **scan5 = —; scan6 = 4; scan7 = 5; scan8 = 6; scan9 = 7**;
- T2 corrections: **1**;
- unresolved historical glyphs after T2: **0**;
- source PDF excluded from repository.

Open:

- SHA-256 checksum;
- complete-source / terminal reconciliation against a full **198-page** representation;
- complete per-scan page-type / visible printed-page mapping for the remaining body;
- T3 final source-fidelity review for scans 5–9;
- later body batches and whole-work Tamil audit.

Canonical body transcription exists for scans **5–9** only. All five records remain `needs-review` until T3. No OCR output or external transcription has been accepted as source authority.

## Source-ingestion correction

The attached source is the registered source copy whose complete extent is **198 pages**.

In this chat, the Files service reports `num_pages: 150`. That parser/ingestion result is therefore **not an authoritative statement about the source PDF's actual extent**.

Consequences:

- the earlier “150 scans vs 198 printed pages” reconciliation is withdrawn;
- the later claim that scans 140–149 equal printed pages 189–198 is also withdrawn;
- the claim that scan149 is the narrative ending and scan150 is the back cover is **invalidated**;
- the invalid terminal claims did not create canonical body prose and therefore required no transcription rollback;
- early source-visible pages may still be processed in bounded batches;
- terminal reconciliation remains blocked until the full 198-page source representation is available.

## Terminal-boundary audit status

Previous result: **INVALIDATED / DO NOT USE**.

Reason: performed against a parser representation that stops at page 150 even though the source copy contains 198 pages.

Current status: **UNKNOWN / RE-AUDIT REQUIRED ON FULL SOURCE**.

## T1 scans 5–9

| Scan | Visible printed page | Record | T1 result |
|---:|---:|---|---|
| 5 | — | `pages/0005-arimugam.md` | **PASS / needs-review** |
| 6 | 4 | `pages/0006-page-4.md` | **PASS / needs-review** |
| 7 | 5 | `pages/0007-page-5.md` | **PASS / needs-review** |
| 8 | 6 | `pages/0008-page-6.md` | **PASS / needs-review** |
| 9 | 7 | `pages/0009-page-7.md` | **PASS / needs-review** |

## T2 independent historical-glyph review — scans 5–9

Result: **PASS / COMPLETE — 5/5**.

Method:

- independently re-read each complete scan at enlarged resolution;
- explicitly checked the full known set `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ` occurrence-by-occurrence where present;
- compared same-edition glyph evidence when a form was visually ambiguous;
- no global replacement and no lexical/spelling modernization.

Correction ledger:

| Scan | T1/apparent reading | Source-supported reading | Historical family | Evidence |
|---:|---|---|---|---|
| 9 | `கிட்டவில்ல` | `கிட்டவில்லை` | `லை` | enlarged source pixels; same-edition `பூஞ்சோலை` / `சிலை` comparison |

Confirmed without change:

- scan 7 — `மட்டுந்தானா` = historical `னா`;
- scan 8 — `வீட்டென்றால்` includes historical `றா` identity in `என்றால்`;
- scan 8 — `பதினொறு` retained exactly as printed;
- scan 9 — `பொன்னாலன்றே` and `அதுலைதான்` retained exactly as printed.

Unresolved historical glyphs after T2: **0**.

## Source-boundary observations

- scan 5 is the unnumbered `அறிமுகம்`;
- scan 6 ends `வாய்ப்பாடு`; scan 7 begins `பாடத்தின் “கோரஸ்”!!`;
- scan 8 ends `யார் வீட்டில் உடல் நலிவு என்றாலும்`; scan 9 continues `பூஞ்சோலை அங்கிருப்பாள்.`;
- later blue/purple underlining/bracket marks on scan 9 remain excluded from canonical printed prose;
- scan 9 ends `புல்லாங்`; scan 10 was not opened or used to complete that fragment.

Checkpoint: [`T1_BATCH_005_009.md`](T1_BATCH_005_009.md).

## Exact next activity

Perform **T3 final source-fidelity review for scans 5–9 only**. Check the full text, punctuation, paragraph boundaries, omissions/duplication, visible page numbering, non-body marks and cross-page continuity. Pages remain `needs-review` until T3 passes. Commit and stop before scan 10.
