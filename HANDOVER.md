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

## Current completion state

The **entire 34-page scan now has page records**.

- page records created: **34 / 34**
- `verified`: **27**
- `needs-review`: **7**
- `not-started`: **0**
- source PDF in repository: **No**

Page files now cover:

- `0001`–`0003`: front matter;
- `0004-balipeedam-nokki-01.md` through `0033-balipeedam-nokki-30.md`: complete body sequence;
- `0034-blank-back.md`: blank/back scan.

A work-level audit file now exists at:

`works/balipeedam-nokki/audit.md`

It records that transcription coverage is complete but the character-level source audit is not yet complete.

## Important page continuity already preserved

Do not reflow or "repair" these without checking the source:

- scan 5 → 6: `அணுக்` / `களிலிருந்து`;
- scan 6 → 7: `உதிர` / `ஆறுகளைப் பாருங்கள்`;
- scan 12 → 13: open Vijay Raghava dying-speech quotation;
- scan 17 → 18: open quotation;
- scan 19 → 20: `பத்திரமாக பாது` / `காத்துக்கொள்`;
- scan 21 → 22: sentence continues after `என்று`;
- scan 29 → 30: `அப்படித்` / `தத்தளிக்கிறான்...`;
- scan 30 → 31: `கைகூப்புவதை` / `யும் நோக்குங்கள்`.

## Seven open review pages

### Scan 3

`pages/0003-publisher-note.md` — one short phrase in the publisher's note remains explicitly unresolved.

### Scan 10

`pages/0010-balipeedam-nokki-07.md` — unusual current reading `மித்தானமத்தனுக்குக்`.

### Scan 13

`pages/0013-balipeedam-nokki-10.md` — current reading `முச்சுற்றுப்படுத்திருக்கும்` needs confirmation.

### Scan 21

`pages/0021-balipeedam-nokki-18.md` — one scene-transition phrase is explicitly unresolved; `என்றுன் பேதை!` also needs character-level confirmation.

### Scan 23

`pages/0023-balipeedam-nokki-20.md` — current reading `களேபாரப்படுகிறது` needs confirmation.

### Scan 26

`pages/0026-balipeedam-nokki-23.md` — current readings `தற்பாகூரர்` and `வீரத்ததை எறக்கத்` need confirmation.

### Scan 27

`pages/0027-balipeedam-nokki-24.md` — one short scene-transition word/phrase is explicitly unresolved.

Do not use grammar, historical knowledge or narrative context to fill these. Resolve only from the controlling scan; if still unreadable, leave them explicit.

## Copy-specific / non-text marks

Across the scan there are library stamps, handwritten underlines, vertical/bracket marks, age stains, bleed-through and binding artefacts. They are recorded separately in page observations where relevant and must never be merged into printed body text.

Notable later-page examples:

- scan 20: handwritten underline beneath `ஊமை வெயில் போல!`;
- scan 26: large library stamp plus handwritten underline/brace;
- scans 28, 30, 32, 33: handwritten underlining / marginal marks;
- scan 33: printed closing ornament;
- scan 34: blank/back page with physical wear / tape edge.

## Next exact activity

Perform a **targeted character-level source review of scans 3, 10, 13, 21, 23, 26 and 27**.

For each page:

1. inspect enlarged source pixels directly;
2. resolve only characters actually supported by the scan;
3. leave genuinely unreadable material explicitly unresolved;
4. update page status to `verified` only when justified;
5. update `indexes/page-map.md`, `audit.md`, work README and this handover with the final counts.

After that targeted review, perform a full 34-page consistency audit covering YAML fields, scan/printed-page numbering, page markers, cross-page continuations, printed/non-text separation and status counts.

## Translation gate

**English translation remains blocked.**

Do not create translation/review files until the Tamil source layer has completed the targeted review and full consistency audit. If some characters remain genuinely unreadable after that review, carry those uncertainties explicitly into the translation plan rather than silently repairing the source.
