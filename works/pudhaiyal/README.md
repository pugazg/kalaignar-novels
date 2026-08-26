# புதையல்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.  
**பதிப்பகம்:** அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்  
**Source edition:** மூன்றாம் பதிப்பு — செப்டம்பர் 1961  
**Tamil Digital Library bibliographic extent:** 443 p.  
**Exact full-PDF scan count:** pending complete source reconciliation  
**Source PDF in repository:** No

## Source-extent correction

The earlier project state incorrectly treated the first **150 known/rendered scans** as the complete source. That claim is withdrawn. Tamil Digital Library reports **443 p.**; scans 1–150 are therefore only a known prefix until later split-source ranges establish the true scan count.

See [`notes/source-page-count-reconciliation.md`](notes/source-page-count-reconciliation.md).

## Split-source workflow

Received access split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split PDF pages: **49**
- split file size available in the chat runtime: **52,760,797 bytes**
- embedded page-image size: **3146 × 4826**
- committed to repository: **No**

The split is an access derivative of the controlling source, not a new edition.

## Current archival status

- source identity from scan — **confirmed**
- scan-printed edition — **மூன்றாம் பதிப்பு, செப்டம்பர் 1961**
- source metadata — **registered; exact full scan count + original SHA-256 pending**
- page map — **known prefix scans 1–150 mapped; full-source coverage incomplete**
- Tamil page records created — **32**
- `verified` — **22** (`scans 1–22`)
- `needs-review` — **10** (`scans 23–32`)
- remaining known-prefix rows `not-started` — **118**
- Tamil source audit — **not started**
- assembled Tamil reading layer — **blocked by Tamil audit gate**
- English translation — **blocked by Tamil audit gate**

## Verification policy after discovered visual-audit errors

The source scan remains controlling. When the user supplies a transcription, it is the comparison baseline, but not a replacement authority for the scan.

For ambiguous old Tamil print:

1. inspect the native embedded page image rather than a small preview;
2. do not silently replace the user's reading from assistant inference;
3. record the exact source-vs-baseline candidate as `needs-review`;
4. change canonical text only after the reading has been explicitly reconciled;
5. `verified` requires a final direct visual pass after reconciliation.

OCR, grammar expectations, catalogue text and modern spelling are aids only.

## Fidelity history

### Scans 1–12 — front matter + `அறிமுகம்`

Current status: **verified**.

Detailed review: [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md).

### Scans 13–22 — corrected native-resolution re-audit

After hallucinated assistant corrections were identified later, scans 12–22 were reopened using the native **3146 × 4826** images.

The re-audit corrected several assistant errors, including restoring source-supported forms such as:

- `அப்போது தான்`
- `கையிலேயும்`
- `நம்பிக்கை யுண்டு`
- `தன உயிருக்கே`
- `அடங்கி விட்டதாகத் தானே`
- `ஆராய்ந்து விட்டோம்`
- `நாளைத் தவற`
- `அடிபட்டு விட்டதால்`

It also reconfirmed genuine source readings such as the four opening dialogue lines on scan 18 and the chapter-2 transition on scan 22.

Current status: **scans 1–22 verified**.

Corrected report: [`notes/visual-fidelity-scans-013-022.md`](notes/visual-fidelity-scans-013-022.md).

### Scans 23–32 — fresh native-resolution re-audit completed

The user's Iteration 3 transcription was restored after the earlier assistant pass was invalidated. A fresh audit has now been performed directly against the native **3146 × 4826** embedded page images.

**Important:** no source-vs-baseline candidate was silently applied during this pass. Canonical page bodies remain the restored user baseline and all ten scans remain `needs-review` until explicit reconciliation.

High-confidence candidates recorded from the native scan include:

- scan 23: source appears to include `மதகின் உள்ளேயிருந்தவர்களுக்கு`; baseline omits the first `மதகின்`;
- scan 24: source clearly has `சிறு ஆறுதல் அளித்தது` and `சற்று ஆறுதல் அளித்தது`; baseline has `ஆறுதலை` in both places;
- scan 24: native image strongly appears to print `அவர்களே நோக்கி`; baseline has `அவர்களை நோக்கி`; kept unresolved because this was previously disputed;
- scan 28: source `அவன் முதுகில்`; baseline `அவன முதுகில்`;
- scan 29: source-specific `கடல் பார்த்துக் கொண்டிருந்தாள்` and `அவளே அவன் காப்பாற்றித் தீர வேண்டும்`; baseline has `கடலை...` / `அவளை...`;
- scan 30: source `பழைய பிரார்த்தனையில்`; baseline `பழைய பிரார்ந்தனையில்`;
- scan 31: source word-boundary / dash forms include `அவனைத் தழுவிக்`, `முயன்றும்—விடாமல்`, `கட்டிவிட்டார்`;
- scan 32: source `தும்பைப்பூ தாடியிலே`; baseline `தும்பை பூ தாடியிலே`.

The native scan also confirms user readings that the earlier assistant had wrongly replaced, including scan 26 `உண்மை தான்`, `மிக கூர்மையாக`, `அவனது நடையிலே வேகம் குறைந்தது`, and scan 27 `குளிர்காற்று`.

There is additionally a **systematic punctuation mismatch**: the supplied clean transcription repeatedly uses forms such as `..`, `!.`, and `?.`, while the scan generally prints ordinary single stops/questions/exclamations plus source dashes/pauses. This has not yet been silently normalized.

Detailed report: [`notes/visual-fidelity-scans-023-032.md`](notes/visual-fidelity-scans-023-032.md).

## Physical structure established so far

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter 1 begins; no visible printed page number;
- scan 22 / printed 20 — chapter 1 closes and chapter 2 begins on the same scan;
- scan 30 / printed 28 — chapter 2 closes and chapter 3 begins on the same scan;
- scan 40 / printed 38 — chapter 4 begins;
- scan 52 / printed 50 — chapter 5 begins;
- scan 60 / printed 58 — chapter 6 begins;
- scan 69 / printed 67 — chapter 7 begins;
- scan 75 / printed 73 — chapter 8 begins;
- scan 84 / printed 82 — chapter 9 begins;
- scan 93 / printed 91 — chapter 10 begins;
- scan 102 / printed 100 — chapter 11 begins;
- scan 110 / printed 108 — chapter 12 begins;
- scan 119 / printed 117 — chapter 13 begins;
- scan 128 / printed 126 — chapter 14 begins;
- scan 138 / printed 136 — chapter 15 begins;
- scan 146 / printed 144 — chapter 16 begins within the known prefix.

Later chapter boundaries and the true source ending remain open until later splits are supplied.

## Edition/catalogue distinction

The controlling scan visibly says **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**. A Tamil Digital Library summary elsewhere says `முதல் பதிப்பு, 1961`; catalogue wording does not override the scan.

## Source registration

- Original filename: `TVA_BOK_0064097_புதையல்.pdf`
- Original attached-file size: **502,895,096 bytes**
- Tamil Digital Library physical description: **443 p.**
- Exact original PDF scan/page-object count: **pending**
- Original SHA-256: **pending exact byte-level calculation**
- Source PDF / split PDFs committed to repository: **No**

Full source record: [`metadata/source.md`](metadata/source.md).  
Current prefix manifest: [`indexes/page-map.md`](indexes/page-map.md).

## Exact next activity

**Do not advance to scans 33–42 yet.**

First reconcile the explicit source-vs-baseline candidates documented for scans **23–32**, including the systematic punctuation question. Apply only confirmed readings, then perform one final native-image page-by-page comparison of scans 23–32 before changing any of them to `verified`.

Do not start English translation.