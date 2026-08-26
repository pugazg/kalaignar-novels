# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-26

## Why this note exists

The first repository onboarding pass incorrectly treated the page-image range initially exposed by the chat file renderer (**scans 1–150**) as the complete PDF. That conclusion is withdrawn.

The controlling attached source is much larger. The Tamil Digital Library bibliographic record for the same source identity (`TVA_BOK_0064097`, `புதையல்`) gives the physical description **`443 p.`**. The current Tamil Digital Library article page also exposes the item as **PDF — 2 Files**. These public catalogue facts are compatible with the user's correction that the PDF/source contains more than 400 pages and prove that the earlier `150 / 150` full-source claim was not valid.

## Authority distinction

The attached scan remains controlling for textual readings, edition wording, punctuation and page-level transcription.

The Tamil Digital Library catalogue is being used here only to correct **source completeness / extent**, not to override printed text in the scan.

Important catalogue/source distinction:

- attached scan front matter visibly says **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**;
- the Kalaignar special-page catalogue summary labels it **`முதல் பதிப்பு, 1961`**;
- therefore the catalogue summary must **not** replace the edition statement visible in the attached scan.

## Split-source workaround now active

To work around whole-file rendering/materialization limits, the user is supplying non-recompressed page-range splits of the controlling PDF.

First received split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

Verified properties in the chat file system:

- split PDF pages: **49**;
- represented controlling-source scans: **1–49**;
- split file size: **52,760,797 bytes**;
- source PDF / split committed to GitHub: **No**.

This successfully provides usable page images for direct letter-by-letter verification. Scans **1–12** have now been visually fidelity-checked, with all twelve page records at `verified` and no unresolved readings in that range.

See [`visual-fidelity-scans-001-012.md`](visual-fidelity-scans-001-012.md).

## Current technical limitation

The original full attachment is **502,895,096 bytes**. Whole-file byte-level hashing and reliable full-PDF page-object inspection remain unavailable in the current runtime.

The split strategy removes the page-image readability blocker, but the **exact full-source scan count remains pending** until all source ranges are supplied/reconciled. Do not equate Tamil Digital Library's `443 p.` physical description automatically with PDF scan count; covers, blanks, inserts or other scan objects may affect the final scan total.

## Corrected archival interpretation

- `150` = known initial prefix, **not total source page count**.
- Tamil Digital Library bibliographic extent = **443 printed pages**.
- exact PDF scan/page-object count = **pending complete split/native-source reconciliation**.
- page-map rows 1–150 remain a provisional known prefix; the manifest is **not complete**.
- scan 150 / printed page 148 is not a source ending.
- the earlier claim that chapter 16 was the final supplied chapter is withdrawn.
- split part 001 now makes scans 1–49 directly available for detailed verification.

## Public catalogue references

- Kalaignar special page: `https://tamildigitallibrary.in/kalaignar/01.literature/navalkal/005_புதையல்.html`
- Tamil Digital Library item: `https://tamildigitallibrary.in/Articles/நூல்-64097-புதையல்#book1/`
- legacy item page: `https://www.tamildigitallibrary.in/book-detail.php?id=jZY9lup2kZl6TuXGlZQdjZU7luI1`

## Current reconciliation state

- full source identity: **confirmed**
- TDL physical extent: **443 p.**
- exact PDF scan count: **pending**
- part 001 received: **scans 1–49**
- source prefix page map currently present: **scans 1–150**
- full-source page map: **INCOMPLETE**
- scans 1–12 page records: **12 / 12 verified**
- original full-source SHA-256: **pending**

## Required next actions

Two tracks can now proceed without confusing them:

### Textual-fidelity track within received splits

1. continue with **scans 13–16 / printed pages 11–14** from part 001;
2. preserve page boundaries and source punctuation exactly;
3. advance through later scans only when their split/native images are available.

### Full-source extent track

1. receive/reconcile the remaining page-range splits;
2. determine the exact PDF scan/page-object count;
3. inspect scan 151 onward directly;
4. establish the real final printed page and back matter;
5. extend `indexes/page-map.md` to every scan page without inferring printed numbers;
6. revise later chapter boundaries from the full work;
7. calculate the exact original-source SHA-256 when byte-level access becomes available.

No English translation may begin while the Tamil/full-source gates remain open.
