# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-26

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is withdrawn.

Tamil Digital Library's record for `TVA_BOK_0064097` gives **443 p.** and exposes the item as **PDF — 2 Files**. These facts establish that 150 was only a known prefix, not the full source extent.

## Authority distinction

The scan controls exact wording, punctuation, spacing, edition statements and page-level transcription. Catalogue information is used only for bibliographic/extent corroboration.

Important discrepancy:

- controlling scan: **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**;
- catalogue summary elsewhere: **`முதல் பதிப்பு, 1961`**.

The repository follows the scan.

## Split-source workaround

Received:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

Verified properties:

- split pages: **49**;
- represented source scans: **1–49**;
- split size available in chat runtime: **52,760,797 bytes**;
- source PDF / split committed to GitHub: **No**.

This split provides usable page images for direct letter-by-letter verification.

Completed from part 001:

- scans **1–12** — verified, unresolved **0**;
- scans **13–22** — verified, unresolved **0**;
- scans **23–32** — verified, unresolved **0**;
- total canonical records verified: **32**.

Fidelity reports:

- [`visual-fidelity-scans-001-012.md`](visual-fidelity-scans-001-012.md)
- [`visual-fidelity-scans-013-022.md`](visual-fidelity-scans-013-022.md)
- [`visual-fidelity-scans-023-032.md`](visual-fidelity-scans-023-032.md)

## Structural corrections exposed by split-source verification

- scan 13 begins chapter 1 but has **no visible printed page number**; `printed_page` remains `null`.
- scan 22 / printed 20 closes chapter 1 and begins chapter 2 on the same physical scan.
- scan 30 / printed 28 closes chapter 2 and begins chapter 3 on the same physical scan.
- scan 40 / printed 38 begins chapter 4.

These page-level observations supersede earlier range-only assumptions.

## Current technical limitation

The original full attachment is **502,895,096 bytes**. Exact whole-file page-object count and original SHA-256 remain pending.

Do **not** equate the TDL physical description `443 p.` automatically with PDF scan count; covers, blanks or other scan objects may make those totals differ.

## Current reconciliation state

- full source identity: **confirmed**
- TDL physical extent: **443 p.**
- exact full PDF scan count: **pending**
- part 001 received: **scans 1–49**
- known-prefix page map: **scans 1–150**
- full-source page map: **INCOMPLETE**
- canonical page records: **32**
- verified: **32**
- needs-review: **0**
- original full-source SHA-256: **pending**
- scan 150 / printed 148: **not source end**

## Next actions

### Textual-fidelity track

Review **scans 33–42 / printed pages 31–40** from split part 001. This range continues chapter 3 and crosses into chapter 4 at scan 40 / printed page 38.

### Full-source extent track

1. receive/reconcile remaining split ranges;
2. determine exact PDF scan/page-object count;
3. inspect scan 151 onward directly;
4. establish the true final printed page/back matter;
5. extend `indexes/page-map.md` to every scan without inferred printed numbers;
6. establish later chapter boundaries from the scan;
7. calculate the original full-source SHA-256 when byte-level access is available.

No English translation may begin while these Tamil/full-source gates remain open.
