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
   - visibly printed pages **48–96**
   - **COMPLETE / VERIFIED — 49 / 49**
3. `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`
   - source scans **99–147**
   - split page count **49**
   - currently processed **99–108 / printed 97–106**
   - scans **99–107 VERIFIED**
   - scan **108 PARTIAL** because the supplied Iteration 9 baseline stops before the physical page ends

No split is committed to GitHub.

## Fidelity-correction history

Earlier assistant visual passes introduced incorrect readings. The project now requires split-image comparison before changing a user-supplied baseline.

Completed / active stages:

- scans 12–22 — reopened after assistant hallucinations and corrected;
- scans 23–32 — user baseline restored, re-audited and finalized;
- scans 33–49 — part 001 finalized;
- scans 50–62 — Iteration 5 finalized against part 002;
- scans 63–72 — Iteration 6 finalized against part 002;
- scans 73–82 — Iteration 7 finalized against part 002;
- scans 83–98 — Iteration 8 finalized against part 002;
- scans 99–108 — Iteration 9 checked against part 003; **99–107 verified, 108 partial**.

Latest direct findings include:

- scan 99 / printed 97 contains a four-star internal transition and prints `இப்ப யாருடைய பெயரைச் சொன்னேன் தெரியுமா?`;
- scan 100 → 101 splits `தோழர்களைத்` as `தோழர்` / `களைத்`;
- scan 101 prints `அவரைப் பற்றி நான் நன்கு விசாரிக்கவேண்டும் என்ற, ஒரு ஆவல்...` and closes chapter 10;
- scan 102 / printed 100 begins chapter 11;
- scan 104 prints `நெடு நாளா பழக்கமா?` and `உடல் வளர்த்து`;
- scan 105 prints `தொண்ணூறு` and `ஆசையா யிருந்தது`;
- scan 106 prints `நான் வரத்தான் வேண்டுமோ?`;
- scan 107 contains another four-star internal transition and ends at `கடை`;
- scan 108 begins `யாக`, completing `கடையாக`, but the physical page continues below the supplied Iteration 9 endpoint `பேசிக்கொண்டிருந்தான் துக்காராம்.`.

The scan-108 remainder is deliberately **not reconstructed** from context or later material.

## Current textual state

- canonical page records created: **108**
- verified: **107** — scans 1–107
- partial: **1** — scan 108
- needs-review: **0**
- unresolved readings through verified scan 107: **0**
- remaining rows in current 150-scan prefix: **42 not-started**

## Full-source extent track

Still required:

1. complete scan 108 / printed page 106;
2. continue part 003 from scan 109 onward;
3. receive/reconcile later split ranges after scan 147;
4. extend `indexes/page-map.md` beyond the current scan-150 prefix;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Complete the **remaining lower portion of scan 108 / printed page 106** directly from split part 003 and re-audit the whole page. Only after scan 108 is `verified` should work advance to **scan 109 / printed page 107**.

English translation remains blocked until the complete Tamil source/audit gates pass.