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
   - scan **75 needs-review**; remaining scans in this part verified
3. `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`
   - source scans **99–147**
   - split page count **49**
   - page records created through **scan 118 / printed 116**
   - scans **99–108 verified after integrity corrections**
   - scans **109–118 needs-review** because the previous Iteration-10 verification was withdrawn

No split is committed to GitHub.

## Backward integrity audit

Earlier assistant visual passes introduced multiple false source readings. The central correction record is:

[`backward-integrity-audit-001-118.md`](backward-integrity-audit-001-118.md)

Confirmed corrections in the current repair pass include:

- scan 4 `நூல் நிலையப் பதிப்பு` and colon in `மூன்றாம் பதிப்பு: ...`;
- scan 11 `இருக்கிறான்னு`;
- scan 24 `அவர்களை நோக்கி`;
- scan 25 `எதோ`;
- scan 31 no full stop after `மூர்ச்சை யடைந்தான்`, and `அவனைத்தழுவிக்`;
- scan 75 previous `போயிடுச்சா?` claim withdrawn; page reopened;
- scan 99 restored `சொல்வேன் என்று... நான் யாருடைய...`;
- scan 101 removed assistant-inserted `நான்` and comma;
- scan 104 restored `நெடு நாள் பழக்கமா?`, while `உடல் வளர்த்து` remains source-confirmed;
- scan 106 restored `வேண்டுமா?`;
- scans 109–118 downgraded from unreliable `verified` state to `needs-review`.

Forward transcription is frozen until this integrity gate closes.

## Current textual state

- canonical page records created: **118**
- verified: **107**
- needs-review: **11** — scan 75 and scans 109–118
- partial: **0**
- remaining rows in current 150-scan prefix: **32 not-started**
- full-source manifest: **INCOMPLETE**

## Full-source extent track

Still required:

1. close the backward integrity audit for scans 109–118 and scan 75;
2. continue part 003 from scan 119 onward only after that gate;
3. receive/reconcile later split ranges after scan 147;
4. extend `indexes/page-map.md` beyond the current scan-150 prefix;
5. identify true final text / back matter / closing leaves;
6. determine exact original PDF scan/page-object count;
7. calculate the exact original full-source SHA-256 when byte-level access is available.

Do not infer any of those values from the TDL printed-page count.

## Exact next activity

Perform a fresh native-image audit of **scans 109–118 / printed pages 107–116** using the user's Iteration 10 as baseline. Classify every assistant delta as confirmed / withdrawn / ambiguous. Then resolve scan 75's old glyph. Do not begin scan 119 or English translation until all 11 `needs-review` records are closed.
