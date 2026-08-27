# புதையல்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.  
**பதிப்பகம்:** அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்  
**Source edition:** மூன்றாம் பதிப்பு — செப்டம்பர் 1961  
**Tamil Digital Library bibliographic extent:** 443 p.  
**Exact full-PDF scan count:** pending complete source reconciliation  
**Source PDF in repository:** No

## Source-extent correction

The earlier project state incorrectly treated the first 150 exposed scans as the complete source. That conclusion is withdrawn. The current page map is a known-prefix manifest only; later splits are required to establish the true source ending and exact scan-object count.

See [`notes/source-page-count-reconciliation.md`](notes/source-page-count-reconciliation.md).

## Split-source workflow

### Part 001

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- state: **COMPLETE / VERIFIED**
- committed to repository: **No**

### Part 002

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- represented source scans: **50–98**
- split PDF pages: **49**
- split size available in chat runtime: **54,231,932 bytes**
- directly processed so far: **scans 50–72 / printed pages 48–70**
- processed range state: **VERIFIED**
- committed to repository: **No**

The split files are access derivatives of the controlling edition, not new editions.

## Current archival status

- source identity — **confirmed**
- scan-printed edition — **மூன்றாம் பதிப்பு, செப்டம்பர் 1961**
- page map — **known prefix scans 1–150; full-source coverage incomplete**
- Tamil page records created — **72**
- `verified` — **72** (`scans 1–72`)
- `needs-review` — **0**
- unresolved readings through scan 72 — **0**
- remaining known-prefix rows `not-started` — **78**
- Tamil whole-work audit — **not started**
- assembled Tamil reading layer — **blocked by Tamil audit gate**
- English translation — **blocked by Tamil audit gate**

## Verification policy after discovered audit errors

The scan remains controlling. User-supplied transcription is the comparison baseline, not a replacement authority.

For every apparent disagreement:

1. inspect the split-source page image;
2. isolate the exact word / spacing / punctuation issue;
3. do not replace ambiguous Tamil from grammar or expectation;
4. apply a change only when the page image establishes it;
5. perform a final page-by-page comparison before `verified`.

OCR, catalogue text, modern spelling and contextual expectation are aids only.

## Fidelity history

- scans 1–12 — verified; front matter + complete `அறிமுகம்`;
- scans 13–22 — corrected native-resolution re-audit after earlier assistant errors;
- scans 23–32 — restored/reconciled after the user's hallucination warning; final 10/10 verified;
- scans 33–49 — split part 001 completion; 17/17 verified;
- scans 50–62 — Iteration 5 directly reconciled against part 002; 13/13 verified;
- scans 63–72 — Iteration 6 directly reconciled against part 002; 10/10 verified.

Detailed reports:

- [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md)
- [`notes/visual-fidelity-scans-013-022.md`](notes/visual-fidelity-scans-013-022.md)
- [`notes/visual-fidelity-scans-023-032.md`](notes/visual-fidelity-scans-023-032.md)
- [`notes/visual-fidelity-scans-033-049.md`](notes/visual-fidelity-scans-033-049.md)
- [`notes/visual-fidelity-scans-050-062.md`](notes/visual-fidelity-scans-050-062.md)
- [`notes/visual-fidelity-scans-063-072.md`](notes/visual-fidelity-scans-063-072.md)

## Important latest reconciliation results

The part-002 pass established several source corrections without relying on grammatical guesswork:

- scan 54: `கேட்கிறீயா`, not clean-baseline `சேட்கிறீயா`;
- scan 56: `இமைகளைத்`, not `இமைகளை த்`;
- scan 60: continuous `மனிதராயிற்றே`, removing the clean transcription's line-break artefact;
- scan 62 → 63: the reply `அதற்குத்தான் ஆறுமாதமாக...` belongs to printed page 61 / scan 63, not scan 62;
- scan 69: chapter numeral `7`, not `1`, and `எவ்வளவுதான்`;
- scan 70: `காரணத்தால்` and `குறும்புக்காரக் கிழவா`;
- scan 71: `பெரிய மனுஷா`.

Source punctuation / dash pauses were restored throughout scans 50–72 instead of the clean extraction's systematic doubled punctuation.

## Physical structure established so far

- scans 1–6 — front matter / blank;
- scans 7–12 — `அறிமுகம்`;
- scan 13 — chapter 1 begins;
- scan 22 / printed 20 — chapter 1 → 2 transition;
- scan 30 / printed 28 — chapter 2 → 3 transition;
- scan 40 / printed 38 — chapter 3 → 4 transition;
- scan 46 / printed 44 — four-star internal transition;
- scan 47 / printed 45 — embedded historical tale begins inside chapter 4;
- scan 52 / printed 50 — chapter 4 → 5 transition;
- scan 60 / printed 58 — chapter 5 → 6 transition;
- scan 68 / printed 66 — chapter 6 ends;
- scan 69 / printed 67 — chapter 7 begins;
- scan 72 / printed 70 — chapter 7 continues and ends mid-sentence at `ஆத்திரத்தோடு,`.

Later chapter boundaries and the true ending remain open until their split-source pages are processed.

## Source registration still open

- Original filename: `TVA_BOK_0064097_புதையல்.pdf`
- Original full-PDF size: **502,895,096 bytes**
- Tamil Digital Library physical description: **443 p.**
- exact original PDF scan/page-object count: **pending**
- original SHA-256: **pending exact byte-level calculation**
- source PDF / splits committed to repository: **No**

Full source record: [`metadata/source.md`](metadata/source.md).  
Current prefix manifest: [`indexes/page-map.md`](indexes/page-map.md).

## Exact next activity

Continue from **scan 73 / printed page 71** using split part 002. First preserve scan 72's unfinished ending `ஆத்திரத்தோடு,`, then process the next controlled transcription batch with the same page-by-page visual-fidelity rule.

Do not start English translation.
