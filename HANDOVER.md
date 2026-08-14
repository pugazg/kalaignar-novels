# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- When resuming, verify current `main` before making changes.

## Permanent startup rule

Before any new work:

1. Read `NOVEL_PROCESSING_GUIDE.md` completely.
2. Read root `README.md`.
3. Read `works/balipeedam-nokki/README.md`, `metadata/source.md`, `indexes/page-map.md`, and `audit.md`.
4. Inspect current repository state and continue existing work rather than creating duplicates.
5. Treat the supplied scan as controlling authority.
6. Do **not** upload/commit the source PDF to this repository.

## Current source

Work: **பலிபீடம் நோக்கி**  
Author: **மு. கருணாநிதி**

Source filename, external to repository:

`TVA_BOK_0065570_பலிபீடம்_நோக்கி.pdf`

- SHA-256: `c4700c9043da8eadbf25144e7127a66a9270326512c095d99e1113a4feb464fe`
- File size: 69,724,254 bytes
- Scan pages: 34
- Edition visible in scan: முதல் பதிப்பு, ஏப்ரல் 1947
- Publisher visible in scan: எரிமலைப் பதிப்பகம், துறையூர்
- PDF committed to repository: **No**

## Critical structural rule

**`பலிபீடம் நோக்கி` is one continuous work across scans 4–33.**

Do not treat `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` as a separate work. It is the embedded cinematic-historical sequence within the same work.

Source-supported structure:

1. **Scans 4–7:** opening ideological / polemical frame.
2. **Scan 7:** narrator explicitly introduces a film-like lesson.
3. **Scan 8:** internal title card — `ராயசம் வெங்கண்ணு`, `தஞ்சை சரித்திரக் கதை`, `எரிமலை ‘ரிலீஸ்’`, credit vocabulary and `விநியோக உரிமை`.
4. **Scans 9–29:** embedded historical episode in cinematic / screenplay-like form.
5. **Scan 30:** `படம் முடிந்துவிட்டது. பாடம் கற்றுக்கொண்டீர்களா? பலிபீடம் நோக்க...` — explicit return to the main frame.
6. **Scans 31–33:** concluding direct address and close of the same work.
7. **Scan 34:** blank/back matter.

Archival rule for every body page scan 4–33:

```text
work: balipeedam-nokki
```

`ராயசம் வெங்கண்ணு` may appear only as an internal `section` label preserving the printed heading.

## Tamil source-preservation state — COMPLETE

The entire 34-page scan has been transcribed, character-reviewed and consistency-audited.

- page records created: **34 / 34**
- `verified`: **34 / 34**
- `needs-review`: **0**
- `not-started`: **0**
- unresolved readings: **0**
- Tamil source audit: **PASSED**
- source PDF in repository: **No**

Page files cover:

- `0001`–`0003`: front matter;
- `0004-balipeedam-nokki-01.md` through `0033-balipeedam-nokki-30.md`: complete body sequence;
- `0034-blank-back.md`: blank/back scan.

Final audit file:

`works/balipeedam-nokki/audit.md`

## Targeted review resolved

The seven previously open pages were reviewed against enlarged source pixels.

- **scan 3:** `பேனுப் பிடிக்கும்`
- **scan 10:** `மித்தானமத்தனுக்குக்` confirmed as printed
- **scan 13:** `முச்சுற்றுப்படுத்திருக்கும்` confirmed
- **scan 21:** `மளமள வென்று`; `என்றுன் பேதை!` confirmed
- **scan 23:** `களேபாரப்படுகிறது` confirmed
- **scan 26:** corrected first-pass readings to `தர்ப்பாகூரர்` and `விபரீதத்தை ஏற்கத்`
- **scan 27:** `ஒரு காரணம்!` confirmed as the unusual printed transition wording

These resolutions came from the scan itself. Do not re-normalize them later from grammar, history or narrative expectation.

## Important page continuity preserved

Do not reflow or "repair" these joins in the canonical page layer:

- scan 5 → 6: `அணுக்` / `களிலிருந்து`;
- scan 6 → 7: `உதிர` / `ஆறுகளைப் பாருங்கள்`;
- scan 12 → 13: open Vijay Raghava dying-speech quotation;
- scan 17 → 18: open quotation;
- scan 19 → 20: `பத்திரமாக பாது` / `காத்துக்கொள்`;
- scan 21 → 22: sentence continues after `என்று`;
- scan 29 → 30: `அப்படித்` / `தத்தளிக்கிறான்...`;
- scan 30 → 31: `கைகூப்புவதை` / `யும் நோக்குங்கள்`.

## Copy-specific / non-text marks

Across the scan there are library stamps, handwritten underlines, vertical/bracket marks, age stains, bleed-through and binding artefacts. They are recorded separately in page observations and must never be merged into printed body text.

Notable examples:

- scan 20: handwritten underline beneath a printed phrase;
- scan 26: large library stamp plus handwritten underline/brace;
- scans 28, 30, 32, 33: handwritten underlining / marginal marks;
- scan 33: printed closing ornament;
- scan 34: blank/back page with physical wear / tape edge.

## Final consistency audit result

The repository was checked for:

- continuous page sequence 1–34;
- scan-page / printed-page mapping;
- one work identity throughout the body;
- correct internal section transitions;
- source filename consistency;
- all page statuses `verified`;
- page-level source markers;
- preserved cross-page continuations;
- separation of printed text from copy-specific marks;
- cover/front matter, closing ornament and blank/back coverage.

Result: **Tamil source-preservation layer PASSED.**

## Translation gate

The previous block on translation is now lifted because the Tamil source layer has passed audit.

However, **do not translate directly from memory or from an independently retyped text**. The audited `pages/` records remain the canonical source layer.

## Next exact activity

Create a **source-faithful assembled Tamil reading layer under `works/balipeedam-nokki/sections/`** without altering the audited page files.

Recommended assembly:

1. `sections/01-opening-frame.md` — scans 4–7;
2. `sections/02-rayasam-vengannu-sequence.md` — scans 8–29, explicitly labeled as an internal sequence of `பலிபீடம் நோக்கி`, not a separate work;
3. `sections/03-return-and-conclusion.md` — scans 30–33;
4. `sections/README.md` — explain derivation, page ranges and preservation rules.

Assembly rules:

- derive text only from the audited page files;
- do not modernize spelling or punctuation;
- page-boundary joins may be made readable in the assembled layer only when the exact two-page continuity is already verified, while retaining source-page markers/comments so provenance is reversible;
- preserve the internal scan-8 title card and cinematic vocabulary;
- do not create separate work-level metadata for `ராயசம் வெங்கண்ணு`;
- cross-check each assembled section against its source page records before marking assembly complete.

After the assembled Tamil layer passes that check, create an English translation plan and begin translation in controlled batches.
