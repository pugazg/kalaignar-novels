# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-28

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
   - directly verified so far **scans 50–82 / printed pages 48–80**

Neither split is committed to GitHub.

## Fidelity-correction history

Earlier assistant visual passes introduced incorrect readings. The project now requires split-image comparison before changing a user-supplied baseline.

Key repaired / completed stages:

- scans 12–22 — reopened after assistant hallucinations and corrected;
- scans 23–32 — user baseline restored, then re-audited and finalized;
- scans 33–49 — checked against part 001 and finalized;
- scans 50–62 — Iteration 5 checked against part 002 and finalized;
- scans 63–72 — Iteration 6 checked against part 002 and finalized;
- scans 73–82 — Iteration 7 checked against part 002 and finalized.

Important physical corrections now established include:

- scan 62 / printed 60 ends `எத்தனை மணியிருக்கும்?`; `அதற்குத்தான் ஆறுமாதமாக...` begins scan 63 / printed 61;
- scan 75 / printed 73 closes chapter `7` and begins chapter `8`;
- scan 82 / printed 80 ends mid-word at `ஆக்ரமிப்ப`; continuation belongs to scan 83.

## Current textual state

- canonical page records created: **82**
- verified: **82** — scans 1–82
- needs-review: **0**
- unresolved readings through scan 82: **0**
- remaining rows in the current 150-scan prefix: **68 not-started**

Latest direct source corrections include `போயிடுச்சா?`, `தொட்டுத் தொட்டுப்`, `வீசி யெறியப்பட்டன`, and `சப்தமிட்டுக் கொண்டே`, in addition to the earlier part-002 corrections already documented. Source punctuation / dash pauses are retained rather than the clean extraction's systematic doubled punctuation.

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

Continue from **scan 83 / printed page 81** in part 002. First verify the continuation of scan 82's unfinished `ஆக்ரமிப்ப`, then continue chapter `8` from the next physical page.

English translation remains blocked until the complete Tamil source/audit gates pass.