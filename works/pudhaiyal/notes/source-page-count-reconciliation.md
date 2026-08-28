# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-28

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- currently mapped scan prefix: **1–150**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction

The source scan controls exact text, edition wording, punctuation and page structure. Catalogue information is used only for bibliographic / completeness reconciliation.

The scan says **`மூன்றாம் பதிப்பு, செப்டம்பர், 1961`**; catalogue wording elsewhere does not override it.

## Split-source workaround

Received access derivatives:

1. `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`
   - source scans **1–49**
   - **COMPLETE / VERIFIED**
2. `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`
   - source scans **50–98**
   - split page count **49**
   - runtime file size **54,231,932 bytes**
   - visibly printed pages **48–96**
   - **COMPLETE / VERIFIED — 49 / 49**

Neither split is committed to GitHub.

## Fidelity-correction history

Earlier assistant visual passes introduced incorrect readings. The project now requires split-image comparison before changing a user-supplied baseline.

Completed stages:

- scans 12–22 — reopened after assistant hallucinations and corrected;
- scans 23–32 — user baseline restored, re-audited and finalized;
- scans 33–49 — part 001 finalized;
- scans 50–62 — Iteration 5 finalized against part 002;
- scans 63–72 — Iteration 6 finalized against part 002;
- scans 73–82 — Iteration 7 finalized against part 002;
- scans 83–98 — Iteration 8 finalized against part 002.

Latest direct findings include:

- scan 83 completes scan 82's `ஆக்ரமிப்ப` with `தற்கும்` and closes chapter 8;
- scan 84 / printed 82 begins chapter 9 and prints `வேகமான நடையிலே`;
- scan 87 prints `அந்த உப்பரிகைத் தளத்தில்` and ends inside `நினைவுச் சுருள்கள்`;
- scan 88 completes that word; closer inspection confirms the baseline sentence `குரலிலே அதிகாரம், முரட்டுத் தனம் இருந்ததே தவிர கனிவு இல்லை.` is source-supported and retained;
- scan 91 prints `முடியாதா` continuously;
- scan 92 closes chapter 9;
- scan 93 / printed 91 begins chapter 10;
- scan 97 supports `சில விநாடிகள்` and `தெவிட்டுவதற்கு`;
- scan 98 is printed page **96**, carries a four-star internal separator, and does **not** establish the source ending.

## Current textual state

- canonical page records created: **98**
- verified: **98** — scans 1–98
- needs-review: **0**
- unresolved readings through scan 98: **0**
- remaining rows in current 150-scan prefix: **52 not-started**

## Full-source extent track

Still required:

1. receive/reconcile the next split beginning at scan 99;
2. continue through the remaining source;
3. extend `indexes/page-map.md` beyond the current scan-150 prefix;
4. identify true final text / back matter / closing leaves;
5. determine exact original PDF scan/page-object count;
6. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Obtain/use the next split beginning with **original scan 99 / printed page 97**. Continue chapter 10 after scan 98's four-star separator. English translation remains blocked until the complete Tamil source/audit gates pass.