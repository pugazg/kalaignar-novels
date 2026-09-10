# வெள்ளிக்கிழமை

**ஆசிரியர் (source cover):** மு. கருணாநிதி  
**வெளியீடு:** திராவிடப்பண்ணை, 34, சிந்தாமணி, திருச்சி-2  
**பதிப்பு:** இரண்டாம் பதிப்பு — 1968  
**Source PDF:** `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`  
**Source PDF committed:** No

## Source identity

- actual PDF scan count: **179**;
- size: **251,126,214 bytes**;
- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`;
- image-only source;
- source PDF must not be committed.

## Current archival status

- page manifest: **179 / 179**;
- canonical page records: **179 / 179 — COMPLETE / VERIFIED**;
- final narrative: **scan 179 / printed 178**, ending `திரும்பினர்கள்.`;
- unresolved source holds: **0**;
- forward mandatory historical-glyph coverage: **PASS scans 1–179**;
- second historical-glyph re-audit: **COMPLETE — scans 119–179 / 61 of 61 PASS**;
- second re-audit corrections: **5 total / 0 unresolved**;
- full Tamil source audit: **PASSED**;
- Tamil source layer: **PASSED**;
- assembled Tamil: **IN PROGRESS — Chapters 1–3 / 23 VERIFIED**;
- assembled source coverage: **scan 4 through scan 33 before centered `4`**;
- English: **blocked until assembled Tamil passes its own consistency gate**.

## Canonical authority

`pages/` is the canonical archival transcription. If an assembled reading section differs from a canonical page record, the canonical `pages/` record controls unless new direct-source evidence establishes a correction.

Mandatory historical-family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Character identity comes from source pixels first. Grammar is only a locator. Preserve source spelling, grammar, punctuation, spacing, colloquial forms and physical page boundaries. Never global-replace or silently normalize.

## Final second-pass corrections

1. scan 151: `அங்கே வந்து.` → `அங்கே வந்து,`;
2. scan 163: `மேனித்தின்மீது` → `பிணத்தின் மீது`;
3. scan 164: `நயினாவில்` → `நயினாவால்`;
4. scan 164: `“என் சார்?”` → `“ஏன் சார்?”`;
5. scan 165: `அவனது சவம்` → `அவளது சவம்`.

No unresolved source reading remains.

## Durable source exceptions

- scan 66 visibly prints only `5`; do not infer `65`;
- printer/signature marks: scans 82 `6`, 98 `7`, 114 `8`, 130 `9`, 146 `10`, 162 `11—A`;
- scan 171 preserves `அங்கிருந்த வாறு`;
- scan 179 lower illustration and faint later handwriting are non-body material;
- verified cross-page continuities remain recorded in `audit.md` / `indexes/page-map.md` and in reversible provenance comments in assembled sections.

## Assembled Tamil reading layer

Reading files live under `sections/` and are derived only from PASSED canonical page records.

| Chapter | File | Source coverage | Status |
|---:|---|---|---|
| 1 | `sections/01-chapter-01.md` | scans 4–12 | **VERIFIED** |
| 2 | `sections/02-chapter-02.md` | scans 13–22 | **VERIFIED** |
| 3 | `sections/03-chapter-03.md` | scan 23 → scan 33 before centered `4` | **VERIFIED** |
| 4 | `sections/04-chapter-04.md` | scan 33 after centered `4` → scan 45 before centered `5` | **NEXT** |
| 5–23 | see `sections/README.md` | remaining source chapters | pending |

Chapter 3 preserves the already-audited joins `உணர்ந்திருந்ததோடு` → `மட்டுமல்ல;`, `அவர்` + `கள்தானே`, `சேர்ந்` + `தான்.`, `விஷயத்தை வெளி` + `யில் சொல்லாதே`, and `மூன்றாவது` → `ஆள் வேம்பு!`.

Scan 33 is split at the actual source-printed centered `4`: the opening dialogue paragraph belongs to Chapter 3; the rest belongs to Chapter 4.

## Assembly rules

1. Derive only from audited canonical `pages/` records.
2. Preserve source spelling, punctuation, dialogue, historical forms, paragraph structure and intentional oddities.
3. Exclude audit notes, scan observations, printer/signature marks, illustration descriptions and later handwriting from reading prose.
4. Retain reversible source-scan / printed-page provenance.
5. Join only already-verified cross-page continuities.
6. Split mixed chapter-boundary scans at the actual centered source heading.
7. Do not change canonical page records merely to make reading flow smoother.
8. English remains blocked until all 23 assembled chapters and the final assembled-layer consistency audit pass.

## Exact next activity

Assemble and verify **Chapter 4 only** from **scan 33 after centered `4` through scan 45 before centered `5`** into:

`sections/04-chapter-04.md`

Do not begin Chapter 5 or English in the same iteration.

Detailed completed source/glyph history remains recoverable in Git history and in `AUDIT_HISTORY_THROUGH_153.md`; `audit.md` is the current authoritative audit summary.
