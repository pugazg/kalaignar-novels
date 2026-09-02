# Part 006 Tamil audit — புதையல்

Access derivative: `TVA_BOK_0064097_புதையல்_part_006_pages_246-294.pdf`

Source scans: **246–294**  
Printed pages represented: **242–290**  
Canonical records: **49 / 49 created**  
Verified / structurally completed: **49 / 49**  
Needs review in Part 006: **0**  
Partial: **0**

Result: **PART-LEVEL TAMIL AUDIT PASSED**

This is a split-part checkpoint only. It does **not** close the whole-work Tamil audit: Tamil Digital Library describes a 443-page bibliographic extent, later source material beyond scan 294 is still required, the true ending/back matter has not yet been reached, and the exact full-source scan count / SHA-256 remain unresolved.

## Authority model audited

Part 006 contains two approved authority regimes:

- scans **246–279** retain the earlier source-first reconciliation decisions already completed and documented;
- scans **280–294** follow the user's explicit hybrid rule: **Gemini transcription controls lexical/textual words, spellings, suffixes, lexical forms, wording and supplied lexical spacing; the native scan controls only headings, punctuation, quotation marks, long dashes, speaker spacing, paragraph structure, physical line/page breaks, separators and chapter/scene transitions**.

The audit found no unresolved Gemini lexical omission in scans 280–294 and no source-based lexical substitution that needs reversal.

## Physical-page inventory / page-map agreement

`indexes/part-006-page-map.md` enumerates every source scan from **246 through 294** exactly once, with the expected printed-page progression **242 through 290**.

All 49 canonical files are present as `pages/0246-pudhaiyal.md` through `pages/0294-pudhaiyal.md`, and the page map records every one as `verified`.

Part-006 derivative identity remains:

- file size: **57,056,182 bytes**;
- SHA-256: `34a5ea5eb91a71ca8674760257779eb4ed6bdc6640517f8830b9ee70aa34aec7`;
- source/split PDF committed to GitHub: **No**.

## Opening continuity from Part 005

The Part-005 endpoint is not a narrative boundary:

- scan 245 / printed 241 ends `இருக்கவே`;
- scan 246 / printed 242 begins `இருக்கிறாள் பரிமளா, ...`;
- audited continuity: `இருக்கவே இருக்கிறாள் பரிமளா, ...`.

The split boundary therefore remains provenance only.

## Cross-page continuity audited

Important joins checked across Part 006 include:

- 247→248: `இன்` / `னும்`;
- 248→249: `அவ` / `தாரம்`;
- 257→258: `வெள்ளியம்` / `பலம்`;
- 261→262: `விடிந்த` / `தும்` = `விடிந்ததும்`;
- 273→274: `மறு` / `படியும்` = `மறுபடியும்`;
- 275→276: open sentence ending `துரை` continues on scan 276;
- 277→278: `விட` / `லாமென்று` = `விடலாமென்று`;
- 279→280: `அதிபதி` / `யாக` = Gemini lexical `அதிபதியாக`, with the native physical page split preserved;
- 282→283: unpunctuated `நின்றான்` / `சிறிது நேரம்.` — one sentence across the page boundary;
- 284→285: open dialogue `முடியுமா` / `என்று யோசனை செய்கிறேன்`;
- 285→286: `பரி` / `மளாவையும்` — physical split inside Gemini lexical `பரிமளாவையும்`;
- 287→288: `எப்படியா` / `வது` — physical split inside Gemini lexical `எப்படியாவது`;
- 289→290: `பட்டுக்` / `கோட்டை` — place-name continuation;
- 291→292: `காப்` / `பாத்துங்க!` — physical split inside Gemini lexical `காப்பாத்துங்க!`;
- 292→293: `ஓடி` / `விட்டான்.` — sentence continuation;
- 293→294: `படுகுழியொன்` / `றில்` — physical split inside Gemini lexical `படுகுழியொன்றில்`.

No derivative boundary was converted into an invented word, sentence, paragraph or chapter boundary.

## Structural audit

- chapter 27 continues from Part 005 and closes on scan **247 / printed 243**;
- chapter 28 begins scan **247 / printed 243**;
- source-printed four-star internal transition occurs at scan **251 / printed 247**;
- chapter 29 begins scan **254 / printed 250** and closes scan **262 / printed 258**;
- chapter 30 begins scan **262 / printed 258** and closes scan **271 / printed 267**;
- chapter 31 begins scan **271 / printed 267** and closes scan **278 / printed 274**;
- chapter 32 begins scan **278 / printed 274** and closes scan **288 / printed 284**;
- chapter 33 begins scan **288 / printed 284** and continues through the derivative endpoint.

The source-printed horizontal rules / chapter headings at the transitions are represented structurally in the canonical layer.

## Scan-280-onward lexical-preservation audit

The canonical records from scan 280 onward explicitly document the Gemini-lexical / native-structure policy.

Audit findings:

- Gemini lexical words are retained as the controlling text;
- native-source punctuation and quotation structure replace OCR-style punctuation only where structural;
- native physical line/page breaks are recorded without source-correcting Gemini lexical forms;
- the earlier scan-283 `பார்` concern is closed: the refreshed user-supplied Gemini Iteration 27 itself contains `பார்`, so no native lexical supplementation was required;
- no unresolved Gemini lexical omission remains through scan 294.

## Derivative endpoint audit

Scan **294 / printed 290** is **not** an ending.

It ends physically inside the Sub-Inspector's dialogue at open `‘லாக்`, with no closing quotation mark, sentence punctuation, chapter close, work-ending ornament or back-matter transition. The next source scan beyond 294 is required to establish continuation.

The repository must therefore continue to describe scan 294 as **Part-006 access-derivative endpoint only**, not as the ending of chapter 33 or the novel.

## Verdict at Tamil-audit gate

- physical-page inventory: **PASS — 49 / 49**;
- canonical/page-map agreement: **PASS**;
- canonical status coverage: **PASS — 49 verified / 0 needs-review / 0 partial**;
- page-boundary continuity: **PASS**;
- chapter / internal-transition structure: **PASS**;
- scan-280-onward Gemini lexical-preservation rule: **PASS**;
- native structural fidelity: **PASS**;
- derivative endpoint handling: **PASS — explicitly open beyond scan 294**;
- Part-006 Tamil state: **`part-tamil-audit-passed`**;
- whole-work Tamil audit: **not yet eligible**.

## Exact next activity

Build the **Part-006 assembled Tamil reading layer from audited canonical pages only**:

1. extend `sections/27-chapter-27.md` from its current scan-245 endpoint through the chapter-27 close on scan 247, joining the established 245→246 split continuity without losing provenance;
2. create / populate assembled chapter files **28 through 33** from audited scans 247–294;
3. preserve the scan-251 four-star internal transition, real chapter boundaries, reversible source-page comments and all verified cross-page joins;
4. leave chapter 33 explicitly open at scan 294 / `‘லாக்`; do not invent a close or novel ending;
5. update `sections/README.md` and Part-006 status after an assembled-layer consistency check.

Do not begin Part-006 English translation until the assembled Tamil layer has passed its split-level consistency check.