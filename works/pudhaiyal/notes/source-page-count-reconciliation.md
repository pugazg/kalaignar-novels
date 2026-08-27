# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-27

## Why this note exists

The first repository onboarding pass incorrectly treated the initially exposed **scans 1–150** as the complete PDF. That conclusion is withdrawn.

Tamil Digital Library describes the same source identity (`TVA_BOK_0064097`, `புதையல்`) as **443 p.** and exposes the item as **PDF — 2 Files**. The exact PDF scan/page-object count must therefore be established from the complete source, not inferred from the original 150-scan viewing window.

## Authority distinction

The source scan remains controlling for exact textual readings, edition wording and page structure. Catalogue information is used only for source-completeness / bibliographic reconciliation.

The scan gives **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**; a TDL summary elsewhere says `முதல் பதிப்பு, 1961`. The repository follows the scan for this edition.

## Split-source workaround

Received access derivatives:

1. `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`
   - represented source scans: **1–49**
   - split pages: **49**
   - transcription / direct visual audit: **49 / 49 COMPLETE / VERIFIED**
   - committed to repository: **No**

2. `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`
   - represented source scans: **50–98**
   - split pages: **49**
   - materialized size in chat runtime: **54,231,932 bytes**
   - Iteration 5 baseline loaded: **scans 50–62 / printed 48–60**
   - Iteration 6 baseline loaded: **scans 63–72 / printed 61–70**
   - fine-grained textual reconciliation: **pending for scans 50–72**
   - committed to repository: **No**

The split files are access derivatives of the controlling source and allow page-level work without committing source PDFs.

## Fidelity correction lesson

Earlier assistant visual-correction passes produced hallucinated Tamil substitutions. Those errors were later withdrawn and corrected. The standing rule is therefore:

- user-supplied transcription is the comparison baseline;
- the scan remains the higher textual authority;
- ambiguous old-print Tamil must not be silently replaced from assistant expectation;
- exact source-vs-baseline disagreements must be isolated and rechecked;
- `verified` is used only after a final direct page-by-page comparison.

## Printed-page reconciliation lesson

Never infer a printed number solely from sequence. For example, scan 13 sits between printed pages 10 and 12 but has no visible printed page number, so it remains `printed_page: null`.

## Current reconciliation state

- full source identity: **confirmed**
- TDL physical extent: **443 p.**
- exact full-PDF scan/page-object count: **pending**
- original full-source SHA-256: **pending**
- part 001 received: **scans 1–49 — COMPLETE / VERIFIED**
- part 002 received: **scans 50–98**
- known-prefix page map: **scans 1–150**
- full-source page map: **INCOMPLETE**
- canonical page records created: **72**
- `verified`: **49** — scans 1–49
- `needs-review`: **23** — scans 50–72
- remaining known-prefix `not-started`: **78**

## Structure established through current baselines

- chapter 4 closes / chapter 5 begins on scan 52 / printed 50;
- chapter 5 closes / chapter 6 begins on scan 60 / printed 58;
- chapter 6 closes on scan 68 / printed 66;
- chapter 7 begins on scan 69 / printed 67;
- the source chapter numeral on scan 69 is **`7`**, correcting the clean Iteration 6 transcription's `1`;
- scan 72 / printed 70 ends mid-sentence at `ஆத்திரத்தோடு,`.

## Full-source extent track

1. reconcile the rest of part 002 through scan 98;
2. receive/reconcile later page-range splits;
3. determine the exact PDF scan/page-object count;
4. inspect the true ending/back matter directly;
5. extend `indexes/page-map.md` to every scan without inferring printed numbers;
6. establish the complete chapter structure;
7. calculate the original full-source SHA-256 when byte-level access becomes available.

## Textual-fidelity track

Immediate gate: perform one controlled fine-grained source-fidelity reconciliation of **scans 50–72 / printed pages 48–70** against part 002. Reconcile Iteration 5 scans 50–62 first and Iteration 6 scans 63–72 second. Apply only source-established differences and perform a final page-by-page comparison before any promotion to `verified`.

After that gate, continue from scan **73 / printed page 71**.

No English translation may begin while the Tamil/full-source gates remain open.