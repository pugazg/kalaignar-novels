# Next Chat Prompt — வெள்ளிக்கிழமை / assembled Tamil reading layer

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
- assembled Tamil: **READY / NEXT — not started**;
- English: **blocked until assembled Tamil passes its own consistency gate**.

## Full Tamil source audit result

The full canonical-layer audit PASSED: 179/179 continuous records, single `vellikkizhamai` work identity, Chapters 1–23, source-confirmed printed-page mapping including scan 66's visible `5`, historical-glyph gates complete, five second-pass source corrections present, durable page-boundary continuities preserved, and non-body marks kept out of narrative. `metadata/source.md` was synchronized because it still contained an obsolete 111/179 progress snapshot. No canonical Tamil text changed in the full source audit.

Do not reopen the completed 119–179 second glyph re-audit or the PASSED Tamil source layer without new direct-source evidence.

## Controlling phase — assembled Tamil reading layer

Follow `NOVEL_PROCESSING_GUIDE.md`. The canonical `pages/` records remain authority.

Assembly rules:

1. derive assembled prose only from audited canonical `pages/`;
2. preserve source spelling, punctuation, dialogue, historical forms and intentional oddities;
3. exclude page observations, printer/signature marks, illustration descriptions and later handwriting from reading prose;
4. retain provenance back to source scans/pages (HTML comments or the repository's established assembly convention);
5. join only already-verified cross-page continuities — never repair grammar or infer missing text;
6. use the source's **23-chapter structure** as the primary organization; do not force-fit another work's section scheme;
7. canonical page files must not be changed merely to make assembly read smoothly;
8. after assembly, run a complete source-coverage / chapter-boundary / cross-page-continuity / canonical-authority consistency check;
9. mark assembled Tamil **PASSED** only after that check;
10. do not start English translation until assembled Tamil PASSES.

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

Inspect the completed reference assembly conventions in `works/balipeedam-nokki/` and the existing `works/vellikkizhamai/` directory. Then create the **assembled Tamil reading layer** for `வெள்ளிக்கிழமை` from all 179 canonical records, organized by the source's 23 chapters, with provenance and only verified joins. Run the assembled-layer audit before declaring it PASSED. English remains blocked.
