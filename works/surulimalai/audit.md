# Audit — சுருளிமலை

## Intake gate

Status: **IN PROGRESS**.

Completed:

- live repository checked; no prior `works/surulimalai/` existed;
- root processing guides reviewed;
- attached source inspected directly at the opening;
- title / author / publisher / edition verified from source scans;
- source size / attached-artifact scan count registered;
- user correction recorded: book/printed extent is **198 pages** while the PDF exposes **150 scan images**;
- front matter scans 1–4 recorded and marked verified;
- source PDF excluded from repository.

Open:

- SHA-256 checksum;
- scan→printed-page reconciliation: **150 PDF scan images vs 198 printed/book pages**;
- complete per-scan page-type / visible printed-page mapping for the **intermediate body**, including multi-page scans where source-supported;
- body T1/T2 and whole-work audit.

No canonical body transcription has started. No OCR output has been accepted as source authority.


## Pagination-count correction

The earlier follow-up overcorrected by treating **198 pages** as though it required **198 PDF scans**, creating an unsupported “48 missing pages” claim.

Current durable interpretation:

- the PDF exposes **150 scan images**;
- the user confirms the book/printed extent is **198 pages**;
- these are different count systems and are **not assumed 1:1**;
- no 48-page loss is asserted;
- scan 150 is neither accepted nor rejected as terminal until its visible printed pagination and structural role are checked;
- terminal scans **145–150** are therefore restored as the next direct-visual mapping target.

This correction changes metadata/control interpretation only; no canonical body text exists yet.


## Terminal-boundary / pagination audit

Result: **PASS / COMPLETE**.

Direct visual source inspection established:

- scans 140–149 = visible printed pages **189–198**, one printed page per scan;
- scan 149 = printed page **198** and source-visible narrative ending;
- scan 150 = **back cover / non-narrative outer matter**;
- no narrative continuation exists on scan150;
- 150 PDF scans and 198 printed pages are therefore compatible count systems; no 48-page loss is asserted;
- intermediate scan→printed-page mapping remains to be built only from direct source evidence during T1.

Record: [`TERMINAL_BOUNDARY_AUDIT.md`](TERMINAL_BOUNDARY_AUDIT.md).

Next: **T1 scans 5–9**.
