# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-29

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- verified source-scan coverage currently available: **1–196**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction

The source scan controls exact text, edition wording, punctuation and page structure. Catalogue information is used only for bibliographic / completeness reconciliation.

Native reinspection establishes the scan-printed publication line as **`மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`** Catalogue wording elsewhere does not override it.

## Split-source workaround

Received access derivatives:

1. `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`
   - source scans **1–49**
   - **49 / 49 verified**
   - **part-complete**
2. `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`
   - source scans **50–98**
   - printed pages **48–96**
   - **49 / 49 verified**
   - **part-complete**
3. `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`
   - source scans **99–147**
   - printed pages **97–145**
   - **49 / 49 verified; unresolved 0**
   - Tamil audit / assembled Tamil / bilingual review **PASSED**
   - **part-complete**
4. `TVA_BOK_0064097_புதையல்_part_004_pages_148-196.pdf`
   - source scans **148–196**
   - printed pages **146–194**
   - **49 / 49 verified; unresolved 0**
   - Tamil audit / assembled Tamil / bilingual review **PASSED**
   - **part-complete**
   - scan 196 closes chapter 21 and begins chapter 22; chapter 22 continues beyond the split

No split is committed to GitHub.

## Backward integrity audit

Earlier assistant visual passes introduced multiple false source readings. The central correction record is [`backward-integrity-audit-001-118.md`](backward-integrity-audit-001-118.md). The backward integrity audit is **COMPLETE through scan 118**.

## Part 004 completion

Fidelity coverage:

- scans 148–158 — `visual-fidelity-scans-148-158.md`
- scans 159–167 — `visual-fidelity-scans-159-167.md`
- scans 168–177 — `visual-fidelity-scans-168-177.md`
- scans 178–187 — `visual-fidelity-scans-178-187.md`
- scans 188–196 — `visual-fidelity-scans-188-196.md`

Part Tamil audit: [`part-004-tamil-audit.md`](part-004-tamil-audit.md) — **PASSED**.  
Part bilingual review: [`../translations/en/PART_004_REVIEW.md`](../translations/en/PART_004_REVIEW.md) — **PASSED / part-complete**.

Important Part-004 continuity includes:

- scan 147 `அடங்கித்தான் போய்` → scan 148 `விட்டார்கள்.`
- scan 158 `டாக்` → scan 159 `துரைக்கு` = `டாக்துரைக்கு`
- scan 173 `வள்ளி வெட்டப்` → scan 174 `பட வேண்டும்`
- scan 187 `அதுகூட` → scan 188 `இல்லை எனக்கு.`
- scan 193 `ஆகா` → scan 194 `ரமும்` = `ஆகாரமும்`
- scan 194 `வேண்டா` → scan 195 `மென்று` = `வேண்டாமென்று`
- scan 195 `ஒரு பெருமாள் கோவில்` → scan 196 `வாசல்—`

## Current textual state

- canonical page records created: **196**
- verified: **196**
- needs-review: **0**
- partial: **0**
- unresolved readings through scan 196: **0**
- Parts 001–004: **part-complete**
- full-source manifest: **INCOMPLETE beyond scan 196**

## Full-source extent track

Still required:

1. receive/reconcile the next split beginning at scan 197;
2. continue chapter 22 from native evidence;
3. complete the full safe workflow for that derivative before moving onward;
4. extend `indexes/page-map.md` beyond scan 196 as later scans become available;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Attach / obtain the next source split beginning at **scan 197 / printed page 195** and establish the next chapter-22 text directly from native source evidence.
