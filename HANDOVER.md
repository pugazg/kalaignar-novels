# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Fresh-chat prompt: `NEXT_NOVEL_CHAT_PROMPT.md`

## Mandatory startup

Before changing the current work:

1. read `NOVEL_PROCESSING_GUIDE.md` completely;
2. read root `README.md`;
3. read this `HANDOVER.md` completely;
4. read `works/pudhaiyal/README.md`;
5. read `works/pudhaiyal/PART_COMPLETION_WORKFLOW.md` completely;
6. inspect live `main` and treat it as authoritative;
7. inspect the controlling split scan before changing canonical Tamil;
8. never commit the original source PDF or any split derivative PDF.

## Permanent source rule

The scan is the textual authority. User-supplied transcription is the comparison baseline. Do not replace an old-print Tamil reading because another form appears grammatically or orthographically more plausible. Any assistant-introduced change must be established from native source pixels. Ambiguous readings remain baseline-preserving and `needs-review`.

## Current work — புதையல்

Path: `works/pudhaiyal/`

Source identity:

- original filename: `TVA_BOK_0064097_புதையல்.pdf`
- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு
- edition line: `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`
- original attached size: 502,895,096 bytes
- Tamil Digital Library bibliographic extent: 443 p.
- exact full-PDF scan/page-object count: pending
- original SHA-256: pending exact byte-level access
- source/split PDFs committed: No

The former `150 pages total` conclusion is permanently withdrawn. The source extends beyond that early prefix.

## Available access derivatives

- Part 001: `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` — scans 1–49 — **part-complete**
- Part 002: `TVA_BOK_0064097_புதையல்_part_002_pages_50-98.pdf` — scans 50–98 — **part-complete**
- Part 003: `TVA_BOK_0064097_புதையல்_part_003_pages_99-147.pdf` — scans 99–147 — **part-complete**
- Part 004: `TVA_BOK_0064097_புதையல்_part_004_pages_148-196.pdf` — scans 148–196 — **in progress**

These are access derivatives of one edition, not separate bibliographic works.

## User-approved split-part completion workflow

Finish the complete safe workflow for each supplied split before moving to the next split. Follow `works/pudhaiyal/PART_COMPLETION_WORKFLOW.md`:

1. page map and canonical `pages/` records;
2. native visual/textual fidelity pass;
3. resolution/documentation of uncertainty;
4. part-level Tamil audit;
5. incremental assembled Tamil reading layer;
6. controlled English translation under the shared translation plan;
7. part-level bilingual source check;
8. part status synchronization and `part-complete` checkpoint.

A split boundary is provenance only. It must never create a false word, sentence, paragraph, scene or chapter boundary.

Final whole-work Tamil audit, final assembled-Tamil pass, whole-work English `verified`, and release-readiness remain blocked until the complete source edition and true ending/back matter are known.

## Completed checkpoints

### Part 001 — scans 1–49

**`part-complete`** — Tamil audit, assembled Tamil, English source check and bilingual review all PASSED.

### Part 002 — scans 50–98

**`part-complete`** — Tamil audit, assembled Tamil, English source check and bilingual review all PASSED.

### Part 003 — scans 99–147

**`part-complete`** — 49 / 49 canonical pages verified; Tamil audit, assembled Tamil, English source check and bilingual review all PASSED.

Part 003 ended physically at scan 147 with `அடங்கித்தான் போய்`.

## Part 004 — scans 148–196

Controlling access derivative:

`TVA_BOK_0064097_புதையல்_part_004_pages_148-196.pdf`

Native derivative facts:

- split pages: **49**
- represented scans: **148–196**
- visibly printed range: **146–194**
- derivative source PDF committed: **No**
- derivative-local page map: `works/pudhaiyal/indexes/part-004-page-map.md`
- structural preflight: `works/pudhaiyal/notes/part-004-structural-preflight-148-196.md`

### Iteration 13 — scans 148–158

- **11 / 11 verified**; unresolved **0**.
- fidelity: `works/pudhaiyal/notes/visual-fidelity-scans-148-158.md`
- scan 147 `அடங்கித்தான் போய்` + scan 148 `விட்டார்கள்.` = `அடங்கித்தான் போய் விட்டார்கள்.`
- protected/source-established examples: scan 148 `அவ்வளவு பெரிய வேதனைக் காடா`; scan 149 `ஒருவேளை இந்த முடிவு தவறக் கூட இருக்கலாம்`; scan 150 source-odd `நன்றுக!`; scan 155 chapter heading 17; scan 155 source-odd `கூலிக்காரப் பெண்களைக் தன்`; scan 157 `கேட்பேனும்`; scan 158 `சம்பவந்தான்`.
- scan 158 ends physically at `டாக்`.

### Iteration 14 — scans 159–167

- **9 / 9 verified**; unresolved **0**.
- fidelity: `works/pudhaiyal/notes/visual-fidelity-scans-159-167.md`
- scan 158 `டாக்` + scan 159 `துரைக்கு` = **`டாக்துரைக்கு`**.
- scan 159 source keeps `நவ நாகரீகத்துக்குக்`.
- scan 163 source-prints the **chapter 17 → 18** transition on the same physical page.
- scan 167 source reads `பழைய டைரிகளை`, not baseline `புழைய டைரிகளை`.
- scan 167 has a source-printed four-star internal separator omitted by the baseline.

### Iteration 15 — scans 168–177

- **10 / 10 verified**; unresolved **0**.
- fidelity: `works/pudhaiyal/notes/visual-fidelity-scans-168-177.md`
- scan 169 source `கிட்டாதாயின் வெட்டென மற`;
- scan 170 source `சூறையாட`, `வெள்ளைக்காரியிடம்`, `ஆண்போல`;
- scan 171 source `போலீசாருக்கு ஆதாரம் போதாதா என்ன?`; chapter 18 closes here;
- scan 172 source-prints chapter **19**;
- scan 173 source-odd `வைப்பானை, என்கிற யோசனை`;
- scan 173 `வள்ளி வெட்டப்` + scan 174 `பட வேண்டும்` = `வள்ளி வெட்டப்பட வேண்டும்`;
- scan 174 source `யாருமற்ற அனாதியாய்`;
- scan 175 source `பலநாள் பட்டினி கிடந்திருப்போம்` and source-odd `உடல் மண்ணோடு மண்ணுக்கிவிட்டு`;
- scan 176 source `பாட்டி! பாட்டி!`;
- scan 177 source `பொக்கை வாய்த் திறந்து` and ends physically at `அந்தகார இருட்டிலே,`.

### Iteration 16 — scans 178–187

- **10 / 10 verified**; unresolved **0**.
- fidelity: `works/pudhaiyal/notes/visual-fidelity-scans-178-187.md`
- scan 177 `அந்தகார இருட்டிலே,` → scan 178 `தளிர்களான நாங்கள்...`;
- scan 178 source `உடைந்த உள்ளத்திற்கு`, `வந்தவன்தான்`, and ends at `எனக்கும், என் தங்கை`;
- scan 179 source-odd `சாமியார் எங்கள் கெட்ட எண்ணத்தோடு`; source `ஒரு நரபலி`; `தெளித்தால்தான்`; chapter 19 closes / chapter 20 begins;
- scan 179 `உப்பரிகையின் மேல்` → scan 180 `தளம் வரையிலே`;
- scan 181 source `நாடியம் கிராமத்திலே` and ends at `அப்`;
- scan 181 `அப்` + scan 182 `படி` = `அப்படி`;
- scan 182 source `கோயில் வாயிலே`;
- scan 183 source `எவையெவைகளையோ`;
- scan 184 source `கண்கள் குளமாயின`, `கதையனைத்தையும்`, and ends at `ஒரு ரத்தம்`;
- scan 184 `ஒரு ரத்தம்` + scan 185 `தோய்ந்த அரிவாள்`;
- scan 187 closes chapter 20 / begins chapter **21**;
- chapter 21 starts `“சாகக் கூடிய வயதல்ல—ஆனாலும் அம்மா...`;
- scan 187 ends physically at `அதுகூட`.

Current Part-004 canonical state:

- scans **148–187**: **40 / 40 verified**
- needs-review: **0**
- unresolved readings: **0**
- scans **188–196**: **9 not-started**

Source-confirmed structure for Part 004:

- scans 148–154 — chapter 16; scan 154 closes it;
- scan 155 — chapter 17 begins;
- scan 163 — chapter 17 closes / chapter 18 begins;
- scan 172 — chapter 19 begins;
- scan 179 — chapter 19 closes / chapter 20 begins;
- scan 187 — chapter 20 closes / chapter 21 begins;
- scan 196 — chapter 21 closes / chapter 22 begins; Part-004 endpoint only, not novel end.

## Canonical Tamil aggregate state

- page records created / verified continuously through: **scan 187**
- verified: **187**
- needs-review in verified range: **0**
- partial in verified range: **0**
- unresolved readings through scan 187: **0**
- full-source page-map coverage: **INCOMPLETE**
- Tamil whole-work audit: not yet eligible
- assembled Tamil whole-work final pass: not yet eligible
- English whole-work verification: not yet eligible
- release-readiness: blocked until complete source

While Part 004 is in progress, use `works/pudhaiyal/indexes/part-004-page-map.md` as the derivative-local authority. Merge it into the work-wide page map at the Part-004 completion checkpoint.

## Exact next activity

Resume **Part 004 at scan 188 / printed page 186 / split page 41** using the next user-supplied baseline and native source page.

Important active boundary: scan 187 ends at **`அதுகூட`**. Do not infer its continuation from grammar or context; scan 188 must establish the next text from native source pixels.

Continue canonical Tamil / fidelity until scans **148–196** are all verified. Then, before accepting another split, complete:

1. Part-004 Tamil audit;
2. assembled Tamil extension;
3. controlled English translation;
4. bilingual source check;
5. Part-004 review;
6. merge Part-004 mapping/status into work-wide documents;
7. mark Part 004 `part-complete` only if every applicable gate passes.
