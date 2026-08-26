# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-26

## Why this note exists

The first repository onboarding pass incorrectly treated the initially exposed **scans 1–150** as the complete PDF. That conclusion is withdrawn.

Tamil Digital Library describes the same source identity (`TVA_BOK_0064097`, `புதையல்`) as **443 p.** and exposes the item as **PDF — 2 Files**. The exact PDF scan/page-object count must therefore be established from the complete source, not inferred from the original 150-scan viewing window.

## Authority distinction

The source scan remains controlling for exact textual readings, edition wording and page structure. Catalogue information is used only for source-completeness / bibliographic reconciliation.

The scan gives **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**; a TDL summary elsewhere says `முதல் பதிப்பு, 1961`. The repository follows the scan for this edition.

## Split-source workaround

Received:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

Verified file-level properties available in chat:

- split PDF pages: **49**;
- represented source scans: **1–49**;
- split file size: **52,760,797 bytes**;
- committed to repository: **No**.

The split is an access derivative of the controlling source and allows page-level work without committing source PDFs.

## Iteration 3 correction — important

The assistant's visual-correction pass for scans **23–32 / printed pages 21–30** was rejected by the user. The user explicitly confirmed that the transcription they supplied was correct and that the assistant's proposed corrections were hallucinated.

Therefore:

- `pages/0023-pudhaiyal.md` through `pages/0032-pudhaiyal.md` have been restored to the user's supplied transcription;
- the assistant-proposed replacement readings have been withdrawn;
- scans 23–32 are now `needs-review`, not `verified`;
- the previous fidelity report is retained only as an invalidation/audit record: [`visual-fidelity-scans-023-032.md`](visual-fidelity-scans-023-032.md).

Revised operating rule: when user-supplied Tamil and an ambiguous old-print glyph appear to differ, do **not** silently replace the user's text. Flag the exact reading as `needs-review` for confirmation.

## Printed-page reconciliation lesson

One independent metadata rule remains important: never infer a printed number solely from sequence. For example, scan 13 sits between printed pages 10 and 12 but has no visible printed page number, so it remains `printed_page: null`.

## Current reconciliation state

- full source identity: **confirmed**
- TDL physical extent: **443 p.**
- exact full-PDF scan/page-object count: **pending**
- original full-source SHA-256: **pending**
- part 001 received: **scans 1–49**
- known-prefix page map: **scans 1–150**
- full-source page map: **INCOMPLETE**
- canonical page records created: **32**
- `verified`: **22**
- `needs-review`: **10** — scans 23–32
- remaining known-prefix `not-started`: **118**

## Full-source extent track

1. receive/reconcile remaining page-range splits;
2. determine the exact PDF scan/page-object count;
3. inspect later scans directly, including the true ending/back matter;
4. extend `indexes/page-map.md` to every scan without inferring printed numbers;
5. establish the complete chapter structure;
6. calculate the original full-source SHA-256 when byte-level access becomes available.

## Textual-fidelity track

The canonical Iteration 3 text has been restored to the user's supplied transcription. Do not advance to the next range until this correction state is accepted. When visual checking resumes, apparent disagreements must be flagged rather than silently substituted.

No English translation may begin while the Tamil/full-source gates remain open.
