# Next Chat Prompt — வெள்ளிக்கிழமை / assembled Tamil Chapter 4

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. **LIVE MAIN IS AUTHORITATIVE.**

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Durable state

- canonical page records: **179 / 179 — COMPLETE**;
- final narrative: **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- forward mandatory historical-glyph coverage: **PASS scans 1–179**;
- second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS**;
- second-pass corrections: **5 total / 0 unresolved**;
- unresolved source holds: **0**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **IN PROGRESS — Chapters 1–3 / 23 VERIFIED**;
- assembled source coverage: **scan 4 through scan 33 before centered `4`**;
- English: **blocked until assembled Tamil passes its own consistency gate**.

## Full Tamil source audit result

The full canonical-layer audit PASSED: 179/179 continuous records, single `vellikkizhamai` work identity, Chapters 1–23, source-confirmed printed-page mapping including scan 66's visible `5`, historical-glyph gates complete, five second-pass source corrections present, durable page-boundary continuities preserved, and non-body marks kept out of narrative. `metadata/source.md` was synchronized because it still contained an obsolete 111/179 progress snapshot. No canonical Tamil text changed in the full source audit.

Do not reopen the completed 119–179 second glyph re-audit or the PASSED Tamil source layer without new direct-source evidence.

## Completed assembly batches

- `works/vellikkizhamai/sections/01-chapter-01.md` — **VERIFIED**, scans **4–12**.
- `works/vellikkizhamai/sections/02-chapter-02.md` — **VERIFIED**, scans **13–22**.
- `works/vellikkizhamai/sections/03-chapter-03.md` — **VERIFIED**, **scan 23 through the Chapter 3 carryover at the top of scan 33 before centered `4`**.
- All assembled sections derive solely from audited canonical `pages/`; reversible source provenance is retained and canonical page files are unchanged.
- Chapter 1 verified joins include scan 4 `ஏதோ` → scan 5 `இன்பக்கனவுகளோ`, scan 5 `அவைகளே` → scan 6 `கேலிக்குரியதாக`, scan 8 `கிழக்கு வானம் வெளுக்கத்` → scan 9 `துவங்கிவிட்டது.`, and scan 10 `இருந்தாள்—` → scan 11 quoted continuation.
- Chapter 2 verified continuities include scan 14 `அதிலே` → scan 15 `வரும் அர்ச்சுனன்`, scan 16 `எண்ணும்` → scan 17 `போது—`, the scan 17→18 dialogue reply after `“சுசீலா! நீ?”`, and the scan 21→22 dialogue reply after `“லேடி டாக்டர் வந்தாச்சுல்லே?”`.
- Chapter 3 verified joins include scan 23 `உணர்ந்திருந்ததோடு` → scan 24 `மட்டுமல்ல;`, scan 24 `அவர்` + scan 25 `கள்தானே`, scan 25 `சேர்ந்` + scan 26 `தான்.`, scan 28 `விஷயத்தை வெளி` + scan 29 `யில் சொல்லாதே`, and scan 31 `மூன்றாவது` → scan 32 `ஆள் வேம்பு!`.
- Scan 33 is a mixed Chapter 3→4 boundary and was split exactly at the centered source-printed `4`; Chapter 3 contains only the opening pre-heading dialogue paragraph.

## Controlling phase — assembled Tamil reading layer

Follow `NOVEL_PROCESSING_GUIDE.md`. The canonical `pages/` records remain authority.

Assembly rules:

1. derive assembled prose only from audited canonical `pages/`;
2. preserve source spelling, punctuation, dialogue, historical forms and intentional oddities;
3. exclude page observations, printer/signature marks, illustration descriptions and later handwriting from reading prose;
4. retain provenance back to source scans/pages (HTML comments or the repository's established assembly convention);
5. join only already-verified cross-page continuities — never repair grammar or infer missing text;
6. use the source's **23-chapter structure** as the primary organization; do not force-fit another work's section scheme;
7. when one physical scan contains the end of one chapter and a centered heading for the next, split the assembled sections at that source-printed heading; never assign the whole scan mechanically to one chapter;
8. canonical page files must not be changed merely to make assembly read smoothly;
9. after assembly, run a complete source-coverage / chapter-boundary / cross-page-continuity / canonical-authority consistency check;
10. mark assembled Tamil **PASSED** only after that check;
11. do not start English translation until assembled Tamil PASSES.

## Source decisions that assembly must preserve

- scan 66 visibly prints only `5`; do not infer `65`;
- printer/signature marks are non-body: scans 82 `6`, 98 `7`, 114 `8`, 130 `9`, 146 `10`, 162 `11—A`;
- scan 151 source punctuation is `அங்கே வந்து,`;
- scan 163 canonical source phrase is `ஆனந்தியின் பிணத்தின் மீது`;
- scan 164 source forms include `நயினாவால்` and `“ஏன் சார்?”`;
- scan 165 source is `அவளது சவம்`;
- scan 171 preserves `அங்கிருந்த வாறு`;
- scan 179 ends `திரும்பினர்கள்.`; lower illustration and faint later handwriting are non-body.

Verified joins include, among others: `புகை` + `வண்டி`, `வாழ்` + `விலே`, `அழகப்ப` + `னுடைய`, `பின்னிக்` + `கொண்டன`, `புறப்` + `பட்டுவிட்டாயே!`, `தேவ` + `லோகத்தில்`, `சோலை` + `யில்`, `கத்தி` + `னான்.`. Preserve the literal scan 156/157 transition `தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.` without reconstruction.

## Exact next activity

Create and verify **Chapter 4 only**, from **scan 33 after centered `4` through scan 45 before centered `5`**, as:

`works/vellikkizhamai/sections/04-chapter-04.md`

Scan 33 is a mixed Chapter 3→4 boundary scan: begin Chapter 4 only below the source-printed centered `4`. Scan 45 is the Chapter 4→5 boundary: include only the text before centered `5` in Chapter 4 and leave the post-heading text for Chapter 5. Preserve provenance and only verified joins. Then update `sections/README.md`, work README, `audit.md`, `HANDOVER.md`, this prompt, and the page-map assembly state to **4 / 23**. Do not begin Chapter 5 or English in the same iteration.
