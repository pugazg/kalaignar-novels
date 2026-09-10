# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Active work: **வெள்ளிக்கிழமை** — `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work. Do not reopen a completed source/glyph gate without genuinely new direct-source evidence.

## Controlling source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`

- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`
- bytes: **251,126,214**
- scans: **179**
- edition: **second edition, 1968**
- image-only
- **Do not commit the PDF.**

## Current durable state

- manifest: **179 / 179**;
- canonical page records: **179 / 179 — COMPLETE / VERIFIED**;
- final narrative: **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- unresolved source holds: **0**;
- forward historical-glyph coverage: **PASS scans 1–179**;
- user-directed second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS**;
- second-pass corrections: **5 total / 0 unresolved**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**;
- assembled Tamil reading layer: **IN PROGRESS — Chapters 1–3 / 23 VERIFIED**;
- assembled source coverage: **scan 4 through the Chapter 3 carryover at the top of scan 33 before centered `4`**;
- English: **blocked until assembled Tamil passes its final consistency gate**.

## Canonical source decisions to preserve

Mandatory historical-family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Read character identity from source pixels first; grammar is only a locator. Never global-replace, silently normalize, or modernize source spelling/spacing/colloquial forms.

The five second-pass corrections are final unless new direct-source evidence appears:

1. scan 151 `அங்கே வந்து.` → `அங்கே வந்து,`;
2. scan 163 `மேனித்தின்மீது` → `பிணத்தின் மீது`;
3. scan 164 `நயினாவில்` → `நயினாவால்`;
4. scan 164 `“என் சார்?”` → `“ஏன் சார்?”`;
5. scan 165 `அவனது சவம்` → `அவளது சவம்`.

Other durable exceptions include scan 66 visibly printing only `5`; printer/signature marks at scans 82 `6`, 98 `7`, 114 `8`, 130 `9`, 146 `10`, 162 `11—A`; scan 171 `அங்கிருந்த வாறு`; and scan 179's lower illustration / faint later handwriting as non-body material.

## Assembled Tamil reading layer

Canonical authority remains `works/vellikkizhamai/pages/`. The reading layer lives in `works/vellikkizhamai/sections/` and is derived only from the PASSED canonical page layer.

Completed:

- `01-chapter-01.md` — **VERIFIED**, scans 4–12;
- `02-chapter-02.md` — **VERIFIED**, scans 13–22;
- `03-chapter-03.md` — **VERIFIED**, scan 23 through scan 33 **before** centered `4`.

Chapter 3 verified joins:

- scan 23 `உணர்ந்திருந்ததோடு` → scan 24 `மட்டுமல்ல;`;
- scan 24 `அவர்` + scan 25 `கள்தானே` → `அவர்கள்தானே`;
- scan 25 `சேர்ந்` + scan 26 `தான்.` → `சேர்ந்தான்.`;
- scan 28 `விஷயத்தை வெளி` + scan 29 `யில் சொல்லாதே` → `விஷயத்தை வெளியில் சொல்லாதே`;
- scan 31 `மூன்றாவது` → scan 32 `ஆள் வேம்பு!`.

Scan 33 is a mixed Chapter 3→4 boundary. Chapter 3 contains only its opening dialogue paragraph above the centered `4`; everything below `4` belongs to Chapter 4.

Assembly rules remain: preserve source wording/punctuation/paragraph/dialogue structure; use reversible provenance comments; join only already-verified page continuities; exclude audit notes/non-body marks; never modify canonical page records merely for reading flow.

## Exact next activity

Assemble and verify **Chapter 4 only**:

`works/vellikkizhamai/sections/04-chapter-04.md`

Coverage: **scan 33 after centered `4` through scan 45 before centered `5`**. Split both mixed boundary scans at their source-printed centered headings. After verification, update coordinated state to **4 / 23**. Do not start Chapter 5 or English in the same iteration.

## Startup for next chat

Read before changing anything:

1. `NOVEL_PROCESSING_GUIDE.md`
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
3. `HANDOVER.md`
4. `NEXT_NOVEL_CHAT_PROMPT.md`
5. `works/vellikkizhamai/README.md`
6. `works/vellikkizhamai/audit.md`
7. `works/vellikkizhamai/indexes/page-map.md`
8. `works/vellikkizhamai/sections/README.md`
9. completed assembled sections relevant to the active boundary
10. canonical `pages/` records for the exact next chapter
