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
- embedded page-image size previously established: **3146 × 4826**
- transcription / visual audit state: **49 / 49 complete**
- committed to repository: **No**

User-named next split:

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- intended represented source scans: **50–98**
- current attachment state in this chat: **not attached / not available as a native split source**
- user-supplied Iteration 5 received for **printed pages 48–60 / scans 50–62**
- scans 50–62 were segmented against the controlling full-PDF renderer and loaded as a **baseline only**
- native-resolution letter-by-letter verification: **pending**

The split files are access derivatives of the controlling source, not new editions.

## Current archival status

- source identity from scan — **confirmed**
- scan-printed edition — **மூன்றாம் பதிப்பு, செப்டம்பர் 1961**
- source metadata — **registered; exact full scan count + original SHA-256 pending**
- page map — **known prefix scans 1–150 mapped; full-source coverage incomplete**
- Tamil page records created — **62**
- `verified` — **49** (`scans 1–49`)
- `needs-review` — **13** (`scans 50–62`; user baseline loaded, native part-002 audit pending)
- remaining known-prefix rows `not-started` — **88**
- split part 001 — **COMPLETE / VERIFIED**
- Tamil source audit — **not started**
- assembled Tamil reading layer — **blocked by Tamil audit gate**
- English translation — **blocked by Tamil audit gate**

## Verification policy after discovered visual-audit errors

The source scan remains controlling. When the user supplies a transcription, it is the comparison baseline, but not a replacement authority for the scan.

For ambiguous old Tamil print:

1. inspect the source page image rather than trusting OCR or context;
2. do not silently replace the user's reading from assistant inference;
3. isolate and recheck the exact source-vs-baseline point;
4. change canonical text only after visual evidence establishes the reading;
5. `verified` requires a final direct visual pass after reconciliation.

If only a reduced renderer is available and the native split is missing, preserve the supplied baseline and keep the page `needs-review` rather than inventing source corrections.

OCR, grammar expectations, catalogue text and modern spelling are aids only.

## Fidelity history

### Scans 1–12 — front matter + `அறிமுகம்`

Current status: **verified**.

Detailed review: [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md).

### Scans 13–22 — corrected native-resolution re-audit

After hallucinated assistant corrections were identified later, scans 12–22 were reopened using the source images. That re-audit corrected several assistant errors and reconfirmed the chapter-2 transition on scan 22.

Current status: **verified**.

Corrected report: [`notes/visual-fidelity-scans-013-022.md`](notes/visual-fidelity-scans-013-022.md).

### Scans 23–32 — reconciliation complete

The user's Iteration 3 transcription was restored after the earlier assistant pass was invalidated. The range was then re-audited, candidate readings were individually rechecked, source punctuation was reconciled, and a final page-by-page comparison was completed.

Important final results include source-supported `அவர்களே தான்`, `அவளை அவன் காப்பாற்றித் தீர வேண்டும்`, `பழைய பிரார்த்தனையில்`, `அவனைத் தழுவிக்`, `தும்பைப்பூ`, and the chapter 2 → 3 transition on scan 30.

Current status: **verified; unresolved 0**.

Final report: [`notes/visual-fidelity-scans-023-032.md`](notes/visual-fidelity-scans-023-032.md).

### Scans 33–49 — Iteration 4 / split part 001 completion

The user's continuous Iteration 4 text was mapped back to the physical pages and checked against scans 33–49. The supplied heading “Pages 31–49” corresponds physically to **scans 33–49 / visibly printed pages 31–47**; split part 001 ends at printed page 47.

Source-established corrections include:

- scan 33: printed `“யார்?”` restored where the clean baseline had only `“?”`;
- scan 37: `கிழவர்` rather than clean-baseline `கிழ்வர்`;
- scan 38: `தோணிக்கு` rather than `தொணிக்கு`;
- scan 41: `அவன் திறக்காமலாவது`;
- scan 43: `புற்று நோய்` rather than `புத்து நோய்`;
- source punctuation / dash pauses restored instead of systematic clean-draft `..`, `!.`, `?.` forms.

Important physical boundaries retained include:

- scan 34 `அந்த` → scan 35 `உண்மை...`;
- scan 35 `பேச்சின்` → scan 36 `பாதியிலேயே...`;
- scan 38 `யாரும்` → scan 39 `எதிர்பாராமலே...`;
- scan 40 `காற்றுத் திசைக்கு` → scan 41 `ஏற்றாற்போல...`;
- scan 44 `இந்திரன்` → scan 45 `மகன் சயந்தன்...`;
- scan 45 `ஆழ்ந்து` → scan 46 `பார்க்கப் போனால்...`;
- scan 47 `சந்தோஷ` → scan 48 `மாக...`;
- scan 48 `எப்படிப்` → scan 49 `யாவது...`.

Scan 40 / printed page 38 closes chapter `3` and begins chapter `4` on the same physical scan. Scan 46 carries a four-star transition and scan 47 begins an embedded historical tale about the மருங்கப்பள்ளம் கொல்லர்; it remains an internal chapter-4 sequence, not a separate work.

Scan 49 / printed page 47 ends mid-sentence at `அவள் அப்பனும்,`. It is the end of **split part 001 only**, not the end of the chapter or work.

Current status: **17 / 17 verified; unresolved 0**.

Detailed report: [`notes/visual-fidelity-scans-033-049.md`](notes/visual-fidelity-scans-033-049.md).

### Scans 50–62 — Iteration 5 baseline loaded; native audit pending

The user's Iteration 5 corresponds to **scans 50–62 / visibly printed pages 48–60**. The controlling full-PDF renderer was used only to restore physical page boundaries, printed-page numbers and chapter transitions.

Important structural points established at renderer level:

- scan 50 continues scan 49's embedded historical tale;
- scan 52 / printed page 50 closes chapter `4` and begins chapter `5` on the same physical page;
- scan 60 / printed page 58 closes chapter `5` and begins chapter `6` on the same physical page.

Cross-page boundaries preserved include:

- scan 52 `அந்த` → scan 53 `வீட்டிற்கு...`;
- scan 54 `போயி` → scan 55 `யைப்பாரு...`;
- scan 55 `வெளியேறியிருந்தாலும்-` → scan 56 `அவர்கள்...`;
- scan 56 `பிறகு` → scan 57 `பாடினாள்...`;
- scan 57 `ஆசைப்` → scan 58 `படுகிறோம்...`.

Because `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` itself is not attached, the supplied wording/punctuation was **not silently corrected from the reduced renderer**. These 13 records remain `needs-review` until native split inspection.

Preliminary record: [`notes/visual-fidelity-scans-050-062.md`](notes/visual-fidelity-scans-050-062.md).

## Physical structure established so far

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter 1 begins; no visible printed page number;
- scan 22 / printed 20 — chapter 1 closes and chapter 2 begins on the same scan;
- scan 30 / printed 28 — chapter 2 closes and chapter 3 begins on the same scan;
- scan 40 / printed 38 — chapter 3 closes and chapter 4 begins on the same scan;
- scan 46 / printed 44 — four-star internal transition;
- scan 47 / printed 45 — embedded historical tale begins inside chapter 4;
- scan 49 / printed 47 — split part 001 ends mid-sentence;
- scan 52 / printed 50 — renderer confirms chapter 4 closes and chapter 5 begins; native part-002 verification pending;
- scan 60 / printed 58 — renderer confirms chapter 5 closes and chapter 6 begins; native part-002 verification pending;
- scan 69 / printed 67 — provisional known-prefix checkpoint: chapter 7 begins;
- scan 75 / printed 73 — provisional known-prefix checkpoint: chapter 8 begins;
- scan 84 / printed 82 — provisional known-prefix checkpoint: chapter 9 begins;
- scan 93 / printed 91 — provisional known-prefix checkpoint: chapter 10 begins;
- scan 102 / printed 100 — provisional known-prefix checkpoint: chapter 11 begins;
- scan 110 / printed 108 — provisional known-prefix checkpoint: chapter 12 begins;
- scan 119 / printed 117 — provisional known-prefix checkpoint: chapter 13 begins;
- scan 128 / printed 126 — provisional known-prefix checkpoint: chapter 14 begins;
- scan 138 / printed 136 — provisional known-prefix checkpoint: chapter 15 begins;
- scan 146 / printed 144 — provisional known-prefix checkpoint: chapter 16 begins within the known prefix.

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

Attach / make available `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`. Re-audit the already-loaded scans **50–62 / printed pages 48–60** letter by letter at native split resolution, apply only source-established differences, and perform a final page-by-page comparison before promoting these pages to `verified`.

After that gate passes, continue from scan **63 / printed page 61** onward.

Do not start English translation.