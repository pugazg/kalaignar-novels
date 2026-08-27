# புதையல்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.  
**பதிப்பகம்:** அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்  
**Source edition:** மூன்றாம் பதிப்பு — செப்டம்பர் 1961  
**Tamil Digital Library bibliographic extent:** 443 p.  
**Exact full-PDF scan count:** pending complete source reconciliation  
**Source PDF in repository:** No

## Source-extent correction

The earlier project state incorrectly treated the first **150 known/rendered scans** as the complete source. That claim is withdrawn. Tamil Digital Library reports **443 p.**; scans 1–150 remain only a known prefix until later split-source ranges establish the true scan count.

See [`notes/source-page-count-reconciliation.md`](notes/source-page-count-reconciliation.md).

## Split-source workflow

### Part 001 — complete

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split pages: **49**
- transcription / direct visual audit: **49 / 49 COMPLETE / VERIFIED**
- committed to repository: **No**

### Part 002 — available

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- represented source scans: **50–98**
- split pages: **49**
- Iteration 5 baseline loaded: **scans 50–62 / printed pages 48–60**
- Iteration 6 baseline loaded: **scans 63–72 / printed pages 61–70**
- current textual status: **needs-review pending one controlled fine-grained source-fidelity reconciliation**
- committed to repository: **No**

The split files are access derivatives of the controlling source, not new editions.

## Current archival status

- source identity from scan — **confirmed**
- scan-printed edition — **மூன்றாம் பதிப்பு, செப்டம்பர் 1961**
- source metadata — **registered; exact full scan count + original SHA-256 pending**
- page map — **known prefix scans 1–150 mapped; full-source coverage incomplete**
- Tamil page records created — **72**
- `verified` — **49** (`scans 1–49`)
- `needs-review` — **23** (`scans 50–72`)
- remaining known-prefix rows `not-started` — **78**
- split part 001 — **COMPLETE / VERIFIED**
- split part 002 — **AVAILABLE; baselines loaded through scan 72**
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

OCR, grammar expectations, catalogue text and modern spelling are aids only.

## Fidelity history

### Scans 1–12

Front matter + `அறிமுகம்`: **verified**.  
Report: [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md).

### Scans 13–22

Corrected re-audit after hallucinated assistant changes were identified: **verified**.  
Report: [`notes/visual-fidelity-scans-013-022.md`](notes/visual-fidelity-scans-013-022.md).

### Scans 23–32

User baseline restored, candidate readings rechecked, final reconciliation completed: **verified; unresolved 0**.  
Report: [`notes/visual-fidelity-scans-023-032.md`](notes/visual-fidelity-scans-023-032.md).

### Scans 33–49 — split part 001 completion

Iteration 4 was mapped back to physical scans 33–49 / printed pages 31–47 and directly compared with split part 001. Scan 40 closes chapter 3 and begins chapter 4. Scan 46 carries a four-star internal transition; scan 47 begins the embedded historical tale. Scan 49 ends split part 001 mid-sentence at `அவள் அப்பனும்,`.

Status: **17 / 17 verified; unresolved 0**.  
Report: [`notes/visual-fidelity-scans-033-049.md`](notes/visual-fidelity-scans-033-049.md).

### Scans 50–62 — Iteration 5

The Iteration 5 baseline is loaded into `pages/0050-pudhaiyal.md` through `pages/0062-pudhaiyal.md`. Part 002 is now available, so the earlier source-availability blocker is resolved. These 13 records intentionally remain `needs-review` until the fine-grained wording / spacing / punctuation reconciliation is performed.

Safe structural facts already established:

- scan 50 / printed 48 continues the embedded tale;
- scan 52 / printed 50 closes chapter `4` and begins chapter `5` on the same scan;
- scan 60 / printed 58 closes chapter `5` and begins chapter `6` on the same scan.

Report: [`notes/visual-fidelity-scans-050-062.md`](notes/visual-fidelity-scans-050-062.md).

### Scans 63–72 — Iteration 6 baseline

Iteration 6 has been mapped to physical **scans 63–72 / printed pages 61–70**.

Directly established structure:

- scans 63–68 continue chapter `6`;
- scan 68 / printed 66 closes chapter `6`;
- scan 69 / printed 67 begins chapter **`7`**;
- scans 70–72 continue chapter `7`;
- scan 72 ends mid-sentence at `ஆத்திரத்தோடு,`.

The supplied clean Iteration 6 showed the chapter numeral as `1`; the source page unmistakably prints **`7`**, so that structural correction has been applied. No ambiguous word-level substitutions were silently imposed during baseline loading.

Status: **10 records created; all `needs-review` pending fine-grained visual reconciliation**.  
Report: [`notes/visual-fidelity-scans-063-072.md`](notes/visual-fidelity-scans-063-072.md).

## Physical structure established so far

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter 1 begins; no visible printed page number;
- scan 22 / printed 20 — chapter 1 closes and chapter 2 begins;
- scan 30 / printed 28 — chapter 2 closes and chapter 3 begins;
- scan 40 / printed 38 — chapter 3 closes and chapter 4 begins;
- scan 46 / printed 44 — four-star internal transition;
- scan 47 / printed 45 — embedded historical tale begins inside chapter 4;
- scan 52 / printed 50 — chapter 4 closes and chapter 5 begins;
- scan 60 / printed 58 — chapter 5 closes and chapter 6 begins;
- scan 68 / printed 66 — chapter 6 closes;
- scan 69 / printed 67 — chapter 7 begins.

Later chapter boundaries and the true source ending remain open until later source ranges are directly reconciled.

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

Perform one controlled fine-grained source-fidelity reconciliation of **scans 50–72 / printed pages 48–70** against split part 002. Reconcile Iteration 5 scans 50–62 first, then Iteration 6 scans 63–72. Apply only source-established wording / spacing / punctuation differences, preserve all physical page boundaries, and run a final page-by-page comparison before promoting individual pages to `verified`.

After that gate passes, continue from scan **73 / printed page 71**.

Do not start English translation.