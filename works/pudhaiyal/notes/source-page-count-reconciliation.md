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
   - verified after backward-integrity corrections
2. `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`
   - source scans **50–98**
   - split page count **49**
   - visibly printed pages **48–96**
   - transcription coverage complete
   - **49 / 49 verified after backward-integrity audit**
3. `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`
   - source scans **99–147**
   - split page count **49**
   - page records created through **scan 128 / printed 126**
   - scans **99–128 verified**; scans 109–118 were re-audited during integrity recovery and scans 119–128 were reconciled against the Iteration-11 baseline under the permanent old-glyph rule

No split is committed to GitHub.

## Backward integrity audit

Earlier assistant visual passes introduced multiple false source readings. The central correction record is:

[`backward-integrity-audit-001-118.md`](backward-integrity-audit-001-118.md)

Confirmed repair items include:

- scan 4 `நூல் நிலையப் பதிப்பு` and colon in `மூன்றாம் பதிப்பு: ...`;
- scan 11 `இருக்கிறான்னு`;
- scan 24 `அவர்களை நோக்கி`;
- scan 25 `எதோ`;
- scan 31 no full stop after `மூர்ச்சை யடைந்தான்`, plus `அவனைத்தழுவிக்`;
- scan 75 earlier `போயிடுச்சா?` claim withdrawn and final source reading resolved as `போயிட்டுதா?` from physical line wrap `போயிட்` / `டுதா?`;
- scan 99 restored `சொல்வேன் என்று... நான் யாருடைய...`;
- scan 101 removed assistant-inserted `நான்` and comma;
- scan 104 restored `நெடு நாள் பழக்கமா?`, while `உடல் வளர்த்து` remains source-confirmed;
- scan 106 restored `வேண்டுமா?`;
- scans 109–118 were reset and then re-audited against native part-003 images.

The scans 109–118 audit is **10 / 10 verified; unresolved 0**. Detailed record: [`visual-fidelity-scans-109-118.md`](visual-fidelity-scans-109-118.md).

The backward integrity audit is **COMPLETE through scan 118**.

## Iteration 11 — scans 119–128

The user-supplied Pages 117–126 baseline was reconciled against native part-003 split pages 21–30.

Result: **10 / 10 verified; unresolved 0**.

Important source-established points include:

- scan 120 `இல்ல இல்ல!`;
- scan 121 `எனக்கிட்ட சொன்னு கூட` and physical continuation `விடு` → scan 122 `றேன்`;
- scan 122 source four-star separator retained;
- scan 123 `புருஷனுய்த்`, `வளர்த்துட்டீங்களே`, `இனிமே என்ன ஆனா என்ன?`;
- scan 124 `தன்னுடைய பரம்பரையிலேயே` and `தங்கம் இருக்கும் இடத்தை`;
- scan 125 `என்னது?`;
- scan 126 distinct `அழைச்சிகிட்டு` / `அழைச்சுட்டு`;
- scan 127 `இதோ ராமனை ஏற்பாடு பண்ணியிருக்கேன்` and `என்று சொல்!`;
- scan 128 `இப்பத் தானே`; the physical page continues beyond the supplied baseline into the printed chapter **14** heading, so the complete source page was retained.

Detailed record: [`visual-fidelity-scans-119-128.md`](visual-fidelity-scans-119-128.md).

## Current textual state

- canonical page records created: **128**
- verified: **128**
- needs-review: **0**
- partial: **0**
- unresolved readings through scan 128: **0**
- remaining rows in current 150-scan prefix: **22 not-started** — scans 129–150
- full-source manifest: **INCOMPLETE**

## Full-source extent track

Still required:

1. continue part 003 from scan 129 onward;
2. receive/reconcile later split ranges after scan 147;
3. extend `indexes/page-map.md` beyond the current scan-150 prefix;
4. identify true final text / back matter / closing leaves;
5. determine exact original PDF scan/page-object count;
6. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Resume forward transcription from **scan 129 / printed page 127** using split part 003 page **31** and the next user-supplied baseline.

Do not begin English translation.
