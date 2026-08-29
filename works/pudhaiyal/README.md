# புதையல்

**ஆசிரியர்:** கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.  
**பதிப்பகம்:** அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்  
**Source edition:** மூன்றாம் பதிப்பு — செப்டம்பர் 1961  
**Tamil Digital Library bibliographic extent:** 443 p.  
**Exact full-PDF scan count:** pending complete source reconciliation  
**Source PDF in repository:** No

## Source-extent correction

The former `150 pages total` conclusion is withdrawn. Scans 1–150 are only a known prefix. Later source splits are required to establish the true ending and exact full-PDF scan count.

See [`notes/source-page-count-reconciliation.md`](notes/source-page-count-reconciliation.md).

## Publication-page correction

Backward native-image reinspection established:

- `சாதாரணப் பதிப்பு ரூ 5/-`
- `நூல் நிலையப் பதிப்பு ரூ 6/-`
- `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`

The former repository reading `ஸ்பெஷல் பதிப்பு` was an assistant misread and has been withdrawn.

## Split-source / part-completion workflow

The split PDFs are access derivatives of one edition, not separate bibliographic works. Follow [`PART_COMPLETION_WORKFLOW.md`](PART_COMPLETION_WORKFLOW.md): once a split's canonical Tamil is complete, finish its part Tamil audit, assembled Tamil, English translation, bilingual source review and status synchronization before moving to the next split.

### Part 001

`TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf`

- represented source scans: **1–49**
- transcription coverage: complete
- canonical Tamil: **49 / 49 verified**
- part Tamil audit: **PASSED**
- assembled Tamil: **PASSED through scan 49**
- English source check: **PASSED through scan 49**
- bilingual review: **PASSED**
- state: **`part-complete`**
- review: [`translations/en/PART_001_REVIEW.md`](translations/en/PART_001_REVIEW.md)
- committed source PDF: **No**

### Part 002

`TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf`

- represented source scans: **50–98**
- split pages: **49**
- visibly printed range: **48–96**
- canonical Tamil: **49 / 49 verified after backward-integrity audit**
- part Tamil audit: **PASSED**
- assembled Tamil: **PASSED through scan 98**
- English source check: **PASSED through scan 98**
- bilingual review: **PASSED**
- state: **`part-complete`**
- review: [`translations/en/PART_002_REVIEW.md`](translations/en/PART_002_REVIEW.md)
- committed source PDF: **No**

Boundary checks:

- scan **49 → 50** is one continuous sentence inside chapter 4's embedded tale; the split boundary does not create a narrative break;
- scan **98 → 99** is a derivative boundary following a source-printed four-star internal separator; verified scan 99 remains chapter 10, so Part 002 is not the end of the chapter or novel.

### Part 003

`TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf`

- represented source scans: **99–147**
- split pages: **49**
- records created through: **scan 128 / printed page 126**
- scans 99–118: **verified after backward-integrity re-audit**
- scans 119–128: **10 / 10 verified from user Iteration 11 against native source**
- scans 129–147: **structure-only native preflight complete; canonical Tamil still `not-started`**
- Iteration 11 fidelity report: [`notes/visual-fidelity-scans-119-128.md`](notes/visual-fidelity-scans-119-128.md)
- structural preflight: [`notes/part-003-structural-preflight-119-147.md`](notes/part-003-structural-preflight-119-147.md)
- part-level Tamil audit: **not yet eligible**
- assembled / English / bilingual review: pending completion of canonical Tamil for the derivative
- committed source PDF: **No**

## Current archival status

- page map — known prefix scans **1–150**, full-source coverage incomplete
- Tamil page records created — **128**
- `verified` — **128**
- `needs-review` — **0**
- `partial` — **0**
- unresolved readings through scan 128 — **0**
- known-prefix not-started — **22**: scans 129–150
- backward integrity audit — **COMPLETE through scan 118**
- forward source-fidelity transcription — **verified through scan 128; next scan 129**
- Part 001 — **part-complete**
- Part 002 — **part-complete**
- Tamil whole-work audit — **not yet eligible**
- assembled Tamil — **part-reviewed continuously through scan 98; whole-work final pass not yet eligible**
- English translation — **part-reviewed continuously through scan 98; whole-work `verified` not yet eligible**
- release-readiness — **blocked until complete source**
- source PDF / split PDFs committed — **No**

## Integrity recovery

Central record:

- [`notes/backward-integrity-audit-001-118.md`](notes/backward-integrity-audit-001-118.md)

The repair withdrew false assistant readings including scan 11 `இருக்கிறாள்ன்னு`, scan 24 `அவர்களே நோக்கி`, scan 25 `ஏதோ`, scan 75 `போயிடுச்சா?`, scan 99 `இப்ப யாருடைய...`, scan 104 `நெடு நாளா...`, and scan 106 `வேண்டுமோ?`.

The audit did **not** blindly revert all assistant changes; source-supported differences survived only after native-image confirmation.

### Scan 75 final resolution

The old-glyph dispute in அஞ்சலை's question is closed. The source word crosses a physical line boundary as:

- `போயிட்`
- `டுதா?`

Continuous source reading: **`போயிட்டுதா?`**.

The earlier assistant `போயிடுச்சா?` and temporary baseline `போய்ட்டுதா?` are both superseded by the native-scan reading.

### Iteration 10 re-audit — scans 109–118

The previously unreliable Iteration-10 verification was reset and repeated against native part-003 images. Result: **10 / 10 verified; unresolved readings in this range: 0**.

Protected / source-established examples include:

- scan 109 `என்னா பிரதர்!`, `துக்கராமாக`, `பாழாய்ப்போன`, `திறமை யில்லேன்னு`;
- scan 110 `போய்ட்டு வர்ரேன்` and chapter 11 → 12 transition;
- scan 112 `காஷ்—?` / `என் அனாவசியமா செலவு`;
- scan 114 `லக்ஷணம்னு`, `முன்னேயே`, `பாட்டு ஆரம்பித்து விட்டான்`, `"காயாத கானகத்தே!" என்ற பாட்டை`, `பயித்தியமாயிருக்கிறதாக்கும்`, `பாடிக் கொண்டிருக்கும்`;
- scan 115 `போதும் தம்பி போதும்!`;
- scan 116 `செத்துப்போயி கூட`, source-odd `அவர்கள் ஆசிரியர் விடவில்லை`, `நான் தான்`, `படித்து விட்டு`;
- scan 117 `பாத்துட்டான்னு சரின்னு சொல்லிடுவான்`;
- scan 118 `மருங்கப்பள்ளத்துச் சிவன் கோயிலுக்கு`, `வேண்டும் என்று அவசர புத்தி`.

Detailed report:

- [`notes/visual-fidelity-scans-109-118.md`](notes/visual-fidelity-scans-109-118.md)

### Iteration 11 — scans 119–128

User Iteration 11 was reconciled page-by-page against native part-003 pages 21–30. Result: **10 / 10 verified; unresolved readings in this range: 0**.

Material source-established examples include:

- scan 120 `இல்ல இல்ல!`;
- scan 121 `எனக்கிட்ட சொன்னு கூட` and physical `விடு` → scan 122 `றேன்` boundary;
- scan 122 four-star internal transition restored from source;
- scan 123 source-odd `புருஷனுய்த்`, `வளர்த்துட்டீங்களே`, `இனிமே என்ன ஆனா என்ன?`;
- scan 124 `தன்னுடைய பரம்பரையிலேயே`, `தங்கம் இருக்கும் இடத்தை`;
- scan 125 source `என்னது?` restored where the baseline had only a placeholder;
- scan 126 first `அழைச்சிகிட்டு`, later `அழைச்சுட்டு`, and source-odd `இதானெ`;
- scan 127 `இதோ ராமனை ஏற்பாடு பண்ணியிருக்கேன்`, `என்று சொல்!`;
- scan 128 `இப்பத் தானே`; the baseline omitted the remainder of the physical page, so the source-confirmed chapter **14** heading and opening prose were restored through the physical endpoint `பல`.

Detailed report:

- [`notes/visual-fidelity-scans-119-128.md`](notes/visual-fidelity-scans-119-128.md)

## Source-confirmed structure ahead of transcription

A structure-only native pass over part 003 pages 21–49 established:

- scan **119 / printed 117** — chapter **13** begins — now verified;
- scan **128 / printed 126** — chapter **13 closes / chapter 14 begins** on the same physical page — now verified;
- scan **138 / printed 136** — chapter **14 closes / chapter 15 begins** on the same physical page;
- scan **146 / printed 144** — chapter **15 closes / chapter 16 begins** on the same physical page;
- scan **147 / printed 145** — chapter 16 continues and is only the end of split part 003, not the end of the novel.

Scans **129–147** remain `not-started` for canonical Tamil until user-supplied baselines are reconciled under the permanent old-glyph rule.

## Fidelity / audit / review records

- [`notes/visual-fidelity-scans-001-012.md`](notes/visual-fidelity-scans-001-012.md)
- [`notes/visual-fidelity-scans-013-022.md`](notes/visual-fidelity-scans-013-022.md)
- [`notes/visual-fidelity-scans-023-032.md`](notes/visual-fidelity-scans-023-032.md)
- [`notes/visual-fidelity-scans-033-049.md`](notes/visual-fidelity-scans-033-049.md)
- [`notes/visual-fidelity-scans-050-062.md`](notes/visual-fidelity-scans-050-062.md)
- [`notes/visual-fidelity-scans-063-072.md`](notes/visual-fidelity-scans-063-072.md)
- [`notes/visual-fidelity-scans-073-082.md`](notes/visual-fidelity-scans-073-082.md)
- [`notes/visual-fidelity-scans-083-098.md`](notes/visual-fidelity-scans-083-098.md)
- [`notes/visual-fidelity-scans-099-108.md`](notes/visual-fidelity-scans-099-108.md)
- [`notes/visual-fidelity-scans-109-118.md`](notes/visual-fidelity-scans-109-118.md)
- [`notes/visual-fidelity-scans-119-128.md`](notes/visual-fidelity-scans-119-128.md)
- [`notes/backward-integrity-audit-001-118.md`](notes/backward-integrity-audit-001-118.md)
- [`notes/part-001-tamil-audit.md`](notes/part-001-tamil-audit.md)
- [`notes/part-002-tamil-audit.md`](notes/part-002-tamil-audit.md)
- [`translations/en/PART_001_REVIEW.md`](translations/en/PART_001_REVIEW.md)
- [`translations/en/PART_002_REVIEW.md`](translations/en/PART_002_REVIEW.md)
- [`notes/part-003-structural-preflight-119-147.md`](notes/part-003-structural-preflight-119-147.md)

## Source registration still open

- Original filename: `TVA_BOK_0064097_புதையல்.pdf`
- Original full-PDF size: **502,895,096 bytes**
- Tamil Digital Library physical description: **443 p.**
- exact original PDF scan/page-object count: **pending**
- original SHA-256: **pending exact byte-level calculation**

Full source record: [`metadata/source.md`](metadata/source.md).  
Current prefix manifest: [`indexes/page-map.md`](indexes/page-map.md).

## Exact next activity

Continue **Part 003** canonical Tamil from **scan 129 / printed page 127 / split part-003 page 31** using the next user-supplied baseline and the permanent old-glyph rule.

Do not begin Part-003 English translation before scans **99–147** have all passed canonical Tamil verification and the Part-003 Tamil audit.

Once Part 003 Tamil is complete, finish that split's assembled Tamil, English translation, bilingual source review and `part-complete` checkpoint **before moving to the next PDF split**.
