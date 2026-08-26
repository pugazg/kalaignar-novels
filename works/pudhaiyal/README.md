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
- `verified` — **32** (`scans 1–32`)
- `needs-review` — **0**
- remaining known-prefix rows `not-started` — **118**
- Tamil source audit — **not started**
- assembled Tamil reading layer — **blocked by Tamil audit gate**
- English translation — **blocked by Tamil audit gate**

## Verification policy after discovered visual-audit errors

The source scan remains controlling. When the user supplies a transcription, it is the comparison baseline, but not a replacement authority for the scan.

For ambiguous old Tamil print:

1. inspect the native embedded page image rather than a small preview;
2. do not silently replace the user's reading from assistant inference;
3. isolate and recheck the exact source-vs-baseline point;
4. change canonical text only after the native scan establishes the reading;
5. `verified` requires a final direct visual pass after reconciliation.

OCR, grammar expectations, catalogue text and modern spelling are aids only.

## Fidelity history

### Scans 1–12 — front matter + `அறிமுகம்`

Current status: **verified**.

Detailed review: [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md).

### Scans 13–22 — corrected native-resolution re-audit

After hallucinated assistant corrections were identified later, scans 12–22 were reopened using the native **3146 × 4826** images.

That re-audit corrected several assistant errors, including restoring source-supported forms such as `அப்போது தான்`, `கையிலேயும்`, `நம்பிக்கை யுண்டு`, `தன உயிருக்கே`, `அடங்கி விட்டதாகத் தானே`, `ஆராய்ந்து விட்டோம்`, `நாளைத் தவற`, and `அடிபட்டு விட்டதால்`.

It also reconfirmed genuine source readings such as the four opening dialogue lines on scan 18 and the chapter-2 transition on scan 22.

Current status: **verified**.

Corrected report: [`notes/visual-fidelity-scans-013-022.md`](notes/visual-fidelity-scans-013-022.md).

### Scans 23–32 — native-resolution reconciliation complete

The user's Iteration 3 transcription was restored after the earlier assistant pass was invalidated. The range was then re-audited against the native **3146 × 4826** embedded images, candidate readings were individually rechecked, source punctuation was reconciled, and a final page-by-page comparison was completed.

Important final results include:

- scan 23: `மதகின் உள்ளேயிருந்தவர்களுக்கு`; user reading `முரடர்களின் பேச்சு கூட` confirmed;
- scan 24: `சிறு ஆறுதல் அளித்தது`, `சற்று ஆறுதல் அளித்தது`, and source-specific `அவர்களே நோக்கி`;
- scan 25: `ஏதோ`, `போனதாகவும்`, `உணர்ந்ததாகவும்` and source dialogue punctuation;
- scan 26: user readings `உண்மை தான்`, `மிக கூர்மையாக`, `அவனது நடையிலே வேகம் குறைந்தது` confirmed;
- scan 27: `உதவுகிறது.` and `குளிர்காற்று` confirmed; unsupported clean-draft ellipsis removed;
- scan 28: `அவன் முதுகில்`;
- scan 29: **`அவர்களே தான்`** and **`அவளை அவன் காப்பாற்றித் தீர வேண்டும்`** confirmed after a second check; earlier assistant candidates `அவர்களேதான்` and `அவளே அவன்...` are withdrawn; source also has `கடல் பார்த்துக் கொண்டிருந்தாள்`;
- scan 30: `பழைய பிரார்த்தனையில்`; chapter 2 → 3 transition on the same scan;
- scan 31: full stop after `மூர்ச்சை யடைந்தான்.`, plus `அவனைத் தழுவிக்`, `முயன்றும்—விடாமல்`, `கட்டிவிட்டார்`;
- scan 32: `தும்பைப்பூ`; page ends at `காலைத்`.

The supplied clean transcription's systematic doubled terminal punctuation (`..`, `!.`, `?.`) was replaced only where native inspection established the source punctuation.

Current status: **scans 23–32 verified; unresolved readings 0**.

Final report: [`notes/visual-fidelity-scans-023-032.md`](notes/visual-fidelity-scans-023-032.md).

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

Process the user's next transcription iteration for **scans 33–42 / printed pages 31–40** from split part 001. This continues chapter `3` and crosses into chapter `4` at scan 40 / printed page 38.

Use the same native-image verification method and preserve every physical scan boundary. Do not start English translation.