# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-27

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- the bibliographic printed extent (**443 p.**);
- the currently mapped scan prefix (**1–150**);
- the exact original PDF scan/page-object count (**still pending**).

## Authority distinction

The source scan controls exact text, edition wording, punctuation and page structure. Catalogue information is used only for bibliographic / completeness reconciliation.

The scan says **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**; a catalogue summary elsewhere says `முதல் பதிப்பு, 1961`. The scan governs this repository edition.

## Split-source workaround

Received access derivatives:

1. `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`
   - source scans **1–49**
   - state **COMPLETE / VERIFIED**
2. `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`
   - source scans **50–98**
   - split page count **49**
   - runtime file size **54,231,932 bytes**
   - directly verified so far **scans 50–72 / printed pages 48–70**

Neither split is committed to GitHub.

## Fidelity-correction history

Earlier assistant visual passes introduced incorrect readings. The project now requires split-image comparison before changing a user-supplied baseline.

Key repaired stages:

- scans 12–22 — reopened after assistant hallucinations and corrected;
- scans 23–32 — user baseline restored, then re-audited and finalized;
- scans 33–49 — checked against part 001 and finalized;
- scans 50–72 — checked against part 002 and finalized.

The latest pass also found a **cross-iteration physical-boundary error**: Iteration 5 included the reply `அதற்குத்தான் ஆறுமாதமாக...` after printed page 60, but the split shows that reply at the top of **printed page 61 / scan 63**. The canonical page records now reflect the actual boundary.

## Current textual state

- canonical page records created: **72**
- verified: **72** — scans 1–72
- needs-review: **0**
- unresolved readings through scan 72: **0**
- remaining rows in the current 150-scan prefix: **78 not-started**

Part-002 source corrections established in the latest audit include `கேட்கிறீயா`, `இமைகளைத்`, `மனிதராயிற்றே`, chapter numeral `7`, `எவ்வளவுதான்`, `காரணத்தால்`, `குறும்புக்காரக் கிழவா`, and `பெரிய மனுஷா`. Source punctuation / dash pauses were restored rather than preserving the clean extraction's systematic doubled punctuation.

## Full-source extent track

Still required:

1. process the rest of part 002 through scan 98;
2. receive/reconcile later split ranges;
3. extend `indexes/page-map.md` beyond the current scan-150 prefix;
4. identify the true final text / back matter / closing leaves;
5. determine the exact original PDF scan/page-object count;
6. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Continue from **scan 73 / printed page 71** in part 002. Preserve scan 72's unfinished ending `ஆத்திரத்தோடு,` and continue chapter `7` from the next physical page.

English translation remains blocked until the complete Tamil source/audit gates pass.
