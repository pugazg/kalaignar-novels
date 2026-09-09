# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`; branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **251,126,214 bytes**, **179 scans**, image-only, second edition 1968. Do not commit PDF.

## Current durable state

- manifest **179 / 179**;
- canonical records **179 / 179 — COMPLETE**;
- final narrative **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- forward mandatory historical-glyph coverage **PASS scans 1–179**;
- unresolved source holds **0**;
- user-directed second historical-glyph re-audit **IN PROGRESS**;
- second re-audit completed **scans 119–123 / 5 of 61 scans — PASS, 0 corrections, 0 unresolved**;
- second re-audit next batch **124–128**, exactly 5 scans per iteration;
- full Tamil source audit / assembled Tamil / English: **blocked pending second re-audit / not started / blocked**.

## Critical historical-glyph rule

Mandatory set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace or silently normalize.

## Second re-audit result — scans 119–123

**PASS — 0 corrections / 0 unresolved.** The five canonical page texts remain unchanged.

- scan 119: `ஓடினாள்` and reform-sensitive `பாலையூர்` clusters reconfirmed; ends `கவனித்து`;
- scan 120: `தொண்ணூறு`, `எண்ணினான்`, `ஏங்கினான்`, `நின்றாள்` reconfirmed; centered `15` preserved; begins `விட்டான்.`;
- scan 121: `குமுறினாள்`, `அலறினாள்`, both `ஓடினான்` occurrences reconfirmed; ends `வண்டியில்`;
- scan 122: `வருகிறானா`, `போகிறாள்`, `கிளம்பியிருக்கிறாள்` reconfirmed; ends `சிந்தாமணி, அவளுக்குப் பக்கத்திலே`;
- scan 123: `நோக்கினாள்`, `நன்றாகக்`, `தோன்றினாள்` reconfirmed; literal source opening `கார்ந்து கொண்டாள்.` retained.

## User-directed second glyph re-audit sequence

`119–123 ✓ → 124–128 → 129–133 → 134–138 → 139–143 → 144–148 → 149–153 → 154–158 → 159–163 → 164–168 → 169–173 → 174–178 → 179`

For every iteration: source pixels first; all 13 families; only individually supported corrections; no global replacement; record corrections or explicit zero-correction PASS; do not start assembled Tamil until the entire 119–179 re-audit is complete.

## Exact next activity

Re-audit historical Tamil glyphs in **scans 124–128** and commit that five-page audit result atomically. Preserve scan 124 / 125 `புகை` + `வண்டி`, scan 127 centered `16`, and scan 127 / 128 `வாழ்` + `விலே`.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
