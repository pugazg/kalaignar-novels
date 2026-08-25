# Source page-count reconciliation — புதையல்

Date: 2026-08-25

## Why this note exists

The first repository onboarding pass incorrectly treated the page-image range exposed by the chat file renderer (**scans 1–150**) as the complete PDF. That conclusion is withdrawn.

The controlling attached source is much larger. The Tamil Digital Library bibliographic record for the same source identity (`TVA_BOK_0064097`, `புதையல்`) gives the physical description **`443 p.`**. The current Tamil Digital Library article page also exposes the item as **PDF — 2 Files**. These public catalogue facts are compatible with the user's correction that the PDF/source contains more than 400 pages and prove that the earlier `150 / 150` full-source claim was not valid.

## Authority distinction

The attached scan remains controlling for textual readings, edition wording, punctuation and page-level transcription.

The Tamil Digital Library catalogue is being used here only to correct **source completeness / extent**, not to override printed text in the scan.

Important catalogue/source distinction:

- attached scan front matter visibly says **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**;
- the Kalaignar special-page catalogue summary labels it **`முதல் பதிப்பு, 1961`**;
- therefore the catalogue summary must **not** replace the edition statement visible in the attached scan.

## Current technical limitation

The chat Files renderer currently exposes page images only through scan 150 for this attachment. A request beginning at page 151 returns no rendered page images. This renderer limitation is not evidence that the underlying PDF ends at page 150.

The 502,895,096-byte attachment also cannot currently be raw-materialized through the available 100 MiB materialization route, so the exact PDF page-object count and SHA-256 have not yet been calculated locally.

## Corrected archival interpretation

- `150` = currently rendered/inspectable scan window in this chat, **not total source page count**.
- Tamil Digital Library bibliographic extent = **443 printed pages**.
- exact PDF scan/page-object count = **pending direct full-file/native inspection**.
- page map rows 1–150 remain useful as a verified/provisional prefix, but the manifest is **not complete**.
- scan 150 / printed page 148 is not a source ending; it is only the end of the currently exposed renderer window.
- the earlier claim that chapter 16 was the final supplied chapter is withdrawn.

## Public catalogue references

- Kalaignar special page: `https://tamildigitallibrary.in/kalaignar/01.literature/navalkal/005_புதையல்.html`
- Tamil Digital Library item: `https://tamildigitallibrary.in/Articles/நூல்-64097-புதையல்#book1/`
- legacy item page: `https://www.tamildigitallibrary.in/book-detail.php?id=jZY9lup2kZl6TuXGlZQdjZU7luI1`

## Required next action

Before advancing transcription beyond the already-created prefix, regain access to the full source extent and:

1. determine the exact PDF scan/page-object count;
2. inspect scan 151 onward directly;
3. establish the real final printed page and back matter;
4. extend `indexes/page-map.md` to every scan page without inferring printed numbers;
5. revise chapter boundaries from the full work rather than the first 150 scans;
6. calculate the exact SHA-256 from the real PDF bytes when byte-level access is available.

No English translation may begin while this source-extent reconciliation is open.
