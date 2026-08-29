# Source page-count reconciliation — புதையல்

Date opened: 2026-08-25  
Last updated: 2026-08-29

## Why this note exists

The first onboarding pass incorrectly treated scans **1–150** as the complete PDF. That conclusion is permanently withdrawn.

Tamil Digital Library describes source identity `TVA_BOK_0064097` as **443 p.** and exposes the item as **PDF — 2 Files**. The repository therefore distinguishes:

- bibliographic printed extent: **443 p.**;
- currently mapped scan prefix: **1–150**;
- exact original PDF scan/page-object count: **still pending**.

## Authority distinction

The source scan controls exact text, edition wording, punctuation and page structure. Catalogue information is used only for bibliographic / completeness reconciliation.

Native reinspection establishes the scan-printed publication line as **`மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`** Catalogue wording elsewhere does not override it.

## Split-source workaround

Received access derivatives:

1. `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`
   - source scans **1–49**
   - transcription coverage complete
   - **49 / 49 verified**
   - split workflow state: **part-complete**
2. `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`
   - source scans **50–98**
   - split page count **49**
   - visibly printed pages **48–96**
   - transcription coverage complete
   - **49 / 49 verified after backward-integrity audit**
   - split workflow state: **part-complete**
3. `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`
   - source scans **99–147**
   - split page count **49**
   - visibly printed pages **97–145**
   - transcription coverage complete for this derivative
   - **49 / 49 verified; unresolved 0**
   - Part-003 Tamil audit **PASSED**
   - assembled Tamil and bilingual English review **PASSED**
   - split workflow state: **part-complete**
   - scan 147 ends mid-sentence at `அடங்கித்தான் போய்`

No split is committed to GitHub.

## Backward integrity audit

Earlier assistant visual passes introduced multiple false source readings. The central correction record is:

[`backward-integrity-audit-001-118.md`](backward-integrity-audit-001-118.md)

Confirmed repair items include scan 4 `நூல் நிலையப் பதிப்பு`, scan 11 `இருக்கிறான்னு`, scan 24 `அவர்களை நோக்கி`, scan 25 `எதோ`, scan 31 no inserted full stop after `மூர்ச்சை யடைந்தான்`, scan 75 final `போயிட்டுதா?`, scan 99 restored `சொல்வேன் என்று... நான் யாருடைய...`, scan 104 `நெடு நாள் பழக்கமா?`, scan 106 `வேண்டுமா?`, plus the native re-audits through scan 118.

The backward integrity audit is **COMPLETE through scan 118**.

## Part 003 completion

Part 003 was subsequently completed under the user-approved per-split workflow.

Fidelity coverage:

- scans 99–108 — `visual-fidelity-scans-099-108.md`;
- scans 109–118 — `visual-fidelity-scans-109-118.md`;
- scans 119–128 — `visual-fidelity-scans-119-128.md`;
- scans 129–137 — `visual-fidelity-scans-129-137.md`;
- scans 138–147 — `visual-fidelity-scans-138-147.md`.

Part Tamil audit: [`part-003-tamil-audit.md`](part-003-tamil-audit.md) — **PASSED**.  
Part bilingual review: [`../translations/en/PART_003_REVIEW.md`](../translations/en/PART_003_REVIEW.md) — **PASSED / part-complete**.

Important final source-established points include:

- scan 131 `நிச்சயமாகத் தெரிகிறது—நீங்கள் பைத்தியக்காரர் இல்லை!`;
- scan 137 `பிறந்தத் தரணி—`, source-odd `புழுதி மண்ணுகப்`;
- scan 137 `வாழ்` → scan 138 `விலே` = `வாழ்விலே`;
- scans 141–142 source-odd `பழுமாகப்`;
- scan 144 source-odd `தடுப்பானேன்`, `அவர்களே ஊமையாகியது`;
- scan 145 `சிறுவனுயிற்றே நீ`;
- scan 146 `இளம் தளிராக!` and chapter 15 → 16 transition;
- scan 147 `சூடு ஆறிவிடாமல் அருந்துகிற தேநீர்`;
- scan 147 physical endpoint `அடங்கித்தான் போய்`, with no continuation inferred.

## Current textual state

- canonical page records created: **147**
- verified: **147**
- needs-review: **0**
- partial: **0**
- unresolved readings through scan 147: **0**
- remaining rows in current 150-scan prefix: **3 not-started** — scans 148–150
- Parts 001–003: **part-complete**
- full-source manifest: **INCOMPLETE**

## Full-source extent track

Still required:

1. receive/reconcile a later split beginning at scan 148;
2. verify the continuation of scan 147's incomplete sentence before later text;
3. complete the full safe workflow for that new derivative before moving onward;
4. extend `indexes/page-map.md` beyond the current scan-150 prefix as later scans become available;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Attach / obtain the next source split beginning at **scan 148 / printed page 146**.

The first source check must continue scan 147's physical endpoint **`அடங்கித்தான் போய்`** from native evidence. Do not guess the continuation from grammar, context or outside editions.