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
- second re-audit completed **scans 119–128 / 10 of 61 scans — PASS, 0 corrections, 0 unresolved**;
- second re-audit next batch **129–133**, exactly 5 scans per iteration;
- full Tamil source audit / assembled Tamil / English: **blocked pending second re-audit / not started / blocked**.

## Critical historical-glyph rule

Mandatory set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Identify character identity from source pixels first. Grammar is only a locator, never proof. Preserve source spelling, grammar, punctuation, spacing and colloquial forms. Never global-replace or silently normalize.

## Second re-audit results

### Scans 119–123

**PASS — 0 corrections / 0 unresolved.** Canonical Tamil unchanged.

### Scans 124–128

**PASS — 0 corrections / 0 unresolved.** Canonical Tamil unchanged.

- scan 124: `நீட்டினாள்`, `வயதானவளை`, `ஏற்றிக்கொண்டிருந்தான்`, `அழகப்பனும்` reconfirmed; ends `புகை`;
- scan 125: `அழகப்பனையும்`, `அவளைத்`, `அழகப்பனைத்`, `கணவனாக` reconfirmed; begins `வண்டி`;
- scan 126: `நின்றது`, `ஏறினார்கள்`, `சிந்தாமணியின்`, `எங்ஙனம்` reconfirmed;
- scan 127: centered `16`; `சிக்கிக்கொண்டாள்`, `இறங்கினாள்`, `அவளைத்தான்`, `நீட்டினான்` reconfirmed; ends `வாழ்`;
- scan 128: begins `விலே`; `நின்று`, `அவளைப்`, `அவனைச் சூழ்ந்தது`, `ஏற்றினார்கள்` reconfirmed.

## User-directed second glyph re-audit sequence

`119–123 ✓ → 124–128 ✓ → 129–133 → 134–138 → 139–143 → 144–148 → 149–153 → 154–158 → 159–163 → 164–168 → 169–173 → 174–178 → 179`

For every iteration: source pixels first; all 13 families; only individually supported corrections; no global replacement; record corrections or explicit zero-correction PASS; do not start assembled Tamil until the entire 119–179 re-audit is complete.

## Exact next activity

Re-audit historical Tamil glyphs in **scans 129–133** and commit that five-page audit result atomically. Preserve scan 129 / 130 `அழகப்ப` + `னுடைய` = `அழகப்பனுடைய`, scan 130 bottom `9` printer/signature mark, and scan 131 / 132 `பின்னிக்` + `கொண்டன` = `பின்னிக்கொண்டன`.

## Completed works — preserve

- **பெரிய இடத்துப் பெண்**: source audit complete; assembled Tamil PASSED; English VERIFIED; release-ready with qualification.
- **புதையல்**: 448 canonical / 446 complete / 2 physical-loss `needs-review`; English VERIFIED; release-ready with qualification.
- **பலிபீடம் நோக்கி**: Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; release-ready.
