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
- T1 scans **5–9 completed directly from attached source pixels**;
- five canonical body records created as `needs-review`;
- visible printed-page mapping recorded only where directly printed: **scan5 = —; scan6 = 4; scan7 = 5; scan8 = 6; scan9 = 7**;
- source PDF excluded from repository.

Open:

- SHA-256 checksum;
- complete-source / terminal reconciliation against a full **198-page** representation;
- complete per-scan page-type / visible printed-page mapping for the remaining body;
- T2 historical-glyph review for scans 5–9;
- T3 final source-fidelity review for scans 5–9;
- later body batches and whole-work Tamil audit.

Canonical body transcription now exists for scans **5–9** only. All five records remain `needs-review`. No OCR output or external transcription has been accepted as source authority.

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

## T1 scans 5–9 — completion

Source scope: attached PDF pixels only.

| Scan | Visible printed page | Record | T1 result |
|---:|---:|---|---|
| 5 | — | `pages/0005-arimugam.md` | **PASS / needs-review** |
| 6 | 4 | `pages/0006-page-4.md` | **PASS / needs-review** |
| 7 | 5 | `pages/0007-page-5.md` | **PASS / needs-review** |
| 8 | 6 | `pages/0008-page-6.md` | **PASS / needs-review** |
| 9 | 7 | `pages/0009-page-7.md` | **PASS / needs-review** |

Source-boundary observations:

- scan 5 is the unnumbered `அறிமுகம்`;
- scan 6 ends `வாய்ப்பாடு`; scan 7 begins `பாடத்தின் “கோரஸ்”!!`;
- scan 8 ends `யார் வீட்டில் உடல் நலிவு என்றாலும்`; scan 9 continues `பூஞ்சோலை அங்கிருப்பாள்.`;
- later blue/purple underlining/bracket marks on scan 9 were excluded from canonical printed prose;
- scan 9 ends `புல்லாங்`; scan 10 was not opened or used to complete that fragment.

Historical-type observations for independent T2 re-read include the T1 representations `மட்டுந்தானா`, `வீட்டென்றால்`, `கிட்டவில்ல`, `பொன்னாலன்றே`, and `அதுலைதான்`. Their final T2 treatment must come from a fresh source-pixel pass, not from contextual expectation.

Checkpoint: [`T1_BATCH_005_009.md`](T1_BATCH_005_009.md).

## Exact next activity

Perform **T2 independent historical-glyph review for scans 5–9 only**, checking all 13 known historical families occurrence-by-occurrence. Keep pages `needs-review`; T3 remains a separate gate. Commit and stop before scan 10.
