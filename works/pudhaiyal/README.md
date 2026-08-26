# புதையல்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.  
**பதிப்பகம்:** அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்  
**Source edition:** மூன்றாம் பதிப்பு — செப்டம்பர் 1961  
**Tamil Digital Library bibliographic extent:** 443 p.  
**Exact full-PDF scan count:** pending complete source reconciliation  
**Source PDF in repository:** No

## Critical source-extent correction

The earlier project state incorrectly treated the first **150 known/rendered scans** as the entire supplied PDF. That claim is withdrawn.

Tamil Digital Library's catalogue for the same item reports **443 p.**, and its current item page lists the source under **PDF — 2 Files**. The current archive therefore treats scans 1–150 only as a provisional known prefix until the remaining source ranges are supplied and reconciled.

See [`notes/source-page-count-reconciliation.md`](notes/source-page-count-reconciliation.md).

## Split-source verification now active

The user has supplied the first non-recompressed range split:

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- split PDF pages: **49**
- split file size available in the chat runtime: **52,760,797 bytes**
- committed to repository: **No**

This split provides usable page images for letter-by-letter source comparison. It is an access derivative of the same controlling source, not a new edition.

## Current archival status

- source identity from scan — **confirmed**
- repository duplicate check — **no existing duplicate work**
- scan-printed edition statement — **மூன்றாம் பதிப்பு, செப்டம்பர் 1961**
- source metadata — **registered; exact full scan count + original SHA-256 pending**
- page map — **known prefix scans 1–150 mapped; full-source coverage incomplete**
- Tamil page records actually created — **12**
- `verified` — **12**
- `needs-review` — **0**
- remaining known-prefix rows `not-started` — **138**
- source scans beyond 150 — **not yet fully mapped from split/native parts**
- Tamil source audit — **not started**
- assembled Tamil reading layer — **blocked by Tamil audit gate**
- English translation — **blocked by Tamil audit gate**

## Letter-by-letter fidelity pass — scans 1–12

Scans **1–12** have now been directly re-inspected from split part 001. The complete `அறிமுகம்` on scans **7–12** is transcribed and `verified`.

Detailed review: [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md).

Important corrections made from the scan rather than accepting the supplied draft verbatim include:

- scan 4: `ஸ்பெஷல் பதிப்பு ரூ 6/-`, not `நூல் நிலையப் பதிப்பு`;
- scan 4: `மூன்றாம் பதிப்பு, செப்டம்பர், 1961.`, not `முதற் பதிப்பு`;
- scan 4: no source-supported full stop after either `ரூ`;
- scan 5: `எம். எல். ஏ.`, not `எம்.எ.ஏ.`;
- scan 5: `தமிழர்கள் ஆதரிக்க வேண்டுகின்றோம்.`;
- scans 7–12: source punctuation replaces the supplied draft's repeated `..` punctuation;
- scan 10: source word retained as `பெறுமானமுள்ள`;
- scan 11: colloquial source reading retained as `இருக்கிறாள்ன்னு`.

Copy-specific handwriting on scan 3 remains separated from printed edition text.

## Introduction page-boundary continuity

Physical scan boundaries are retained in the canonical page layer:

- scan 7 ends `காய்ந்த மீனின் வாசம்`; scan 8 continues `‘கம கம’ வென்று வந்துகொண்டிருக்கும்.`;
- scan 8 `அடை` + scan 9 `யாளமாக` forms continuous `அடையாளமாக`;
- the quotation begun on scan 10 continues on scan 11;
- scan 11 `கனவு` + scan 12 `காண்பவர்களின்` is preserved across the boundary;
- scan 12 closes the `அறிமுகம்`; scan 13 begins chapter 1.

No cross-page text has been silently moved into a neighboring page record.

## Source structure — currently known prefix only

The first 150 known scans establish this prefix structure:

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scans 13–21 — chapter 1;
- scans 22–30 — chapter 2;
- scans 31–39 — chapter 3;
- scans 40–51 — chapter 4;
- scans 52–59 — chapter 5;
- scans 60–68 — chapter 6;
- scans 69–74 — chapter 7;
- scans 75–83 — chapter 8;
- scans 84–92 — chapter 9;
- scans 93–101 — chapter 10;
- scans 102–109 — chapter 11;
- scans 110–118 — chapter 12;
- scans 119–127 — chapter 13;
- scans 128–137 — chapter 14;
- scans 138–145 — chapter 15;
- scan 146 — chapter 16 begins within the known prefix.

No claim is currently made about later chapter boundaries or the final chapter number.

## Important edition/catalogue distinction

The scan visibly says **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**. A Tamil Digital Library Kalaignar special-page summary labels the work **`முதல் பதிப்பு, 1961`**.

The scan is the controlling authority for this repository edition, so the repository retains **third edition, September 1961**. The catalogue discrepancy is documented rather than silently reconciled.

## Source registration

- Original filename: `TVA_BOK_0064097_புதையல்.pdf`
- Original attached-file size: **502,895,096 bytes**
- Tamil Digital Library physical description: **443 p.**
- Exact original PDF scan/page-object count: **pending**
- Original SHA-256: **pending exact byte-level calculation**
- Source PDF committed to repository: **No**

Full source record: [`metadata/source.md`](metadata/source.md).  
Current prefix manifest: [`indexes/page-map.md`](indexes/page-map.md).

## Authority

The source scan controls exact Tamil wording, punctuation, spelling, dialogue and page-level transcription. User-supplied draft text, OCR, catalogue/web material and external editions may assist comparison/navigation but may not override visible source text.

## Exact next activity

**Continue within split part 001 with scans 13–16 / printed pages 11–14, the opening Chapter 1 batch.**

For that batch:

1. perform direct letter-by-letter visual comparison;
2. create `pages/0013-pudhaiyal.md` through `pages/0016-pudhaiyal.md`;
3. preserve physical page boundaries and cross-page word/sentence continuity;
4. mark any genuinely uncertain glyph `needs-review` instead of guessing;
5. update the page map, this README and root `HANDOVER.md`;
6. continue full-source extent reconciliation as later split parts are supplied;
7. do not start English translation.
