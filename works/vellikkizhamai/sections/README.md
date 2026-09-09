# Assembled Tamil Reading Layer — வெள்ளிக்கிழமை

இந்த `sections/` அடுக்கு வாசிப்பதற்காகத் தொகுக்கப்படும் **source-faithful assembled layer**. இது canonical archival transcription அல்ல.

## Authority

Canonical source-preservation layer:

`../pages/`

அந்த 179 page records source audit முடித்து `verified` செய்யப்பட்டவை. இந்த assembled layer அவற்றிலிருந்து மட்டுமே உருவாக்கப்படுகிறது.

> **முரண்பாடு ஏற்பட்டால் `pages/` record-தான் controlling archival text.**

Source PDF repository-க்குள் commit செய்யப்படாது.

## Assembly structure

Source-printed **23 chapters** தான் section boundaries. ஒவ்வொரு chapter-மும் தனி assembled Markdown file ஆக உருவாக்கப்படுகிறது; வேறு work-ன் section scheme force-fit செய்யப்படாது.

| File | Source scans | Chapter | Status |
|---|---:|---:|---|
| `01-chapter-01.md` | 4–12 | 1 | **VERIFIED** |
| `02-chapter-02.md` | 13–22 | 2 | next |
| `03-chapter-03.md` | 23–32 | 3 | pending |
| `04-chapter-04.md` | 33–44 | 4 | pending |
| `05-chapter-05.md` | 45–51 | 5 | pending |
| `06-chapter-06.md` | 52–58 | 6 | pending |
| `07-chapter-07.md` | 59–67 | 7 | pending |
| `08-chapter-08.md` | 68–74 | 8 | pending |
| `09-chapter-09.md` | 75–84 | 9 | pending |
| `10-chapter-10.md` | 85–91 | 10 | pending |
| `11-chapter-11.md` | 92–98 | 11 | pending |
| `12-chapter-12.md` | 99–106 | 12 | pending |
| `13-chapter-13.md` | 107–114 | 13 | pending |
| `14-chapter-14.md` | 115–119 | 14 | pending |
| `15-chapter-15.md` | 120–126 | 15 | pending |
| `16-chapter-16.md` | 127–133 | 16 | pending |
| `17-chapter-17.md` | 134–141 | 17 | pending |
| `18-chapter-18.md` | 142–148 | 18 | pending |
| `19-chapter-19.md` | 149–153 | 19 | pending |
| `20-chapter-20.md` | 154–159 | 20 | pending |
| `21-chapter-21.md` | 160–165 | 21 | pending |
| `22-chapter-22.md` | 166–171 | 22 | pending |
| `23-chapter-23.md` | 172–179 | 23 | pending |

## Assembly rules

1. Text is derived only from audited canonical `pages/` records.
2. Historical spelling, punctuation, dialogue, colloquial forms, source oddities, paragraph structure and verse layout are preserved.
3. Historical-glyph notes, scan observations, printer/signature marks, illustration descriptions and later handwriting are not inserted into reading prose.
4. HTML comments retain source-scan / printed-page provenance without interrupting normal reading.
5. Cross-page fragments are joined only where the canonical audit already established continuity.
6. Canonical `pages/` files are never changed merely to make assembly read smoothly.
7. One source chapter is assembled and verified per iteration / commit.
8. The whole assembled layer is not `PASSED` until Chapters 1–23 and a final coverage / continuity / canonical-authority audit pass.

## Chapter 1 verification

`01-chapter-01.md` covers scans **4–12** and is **VERIFIED**.

Verified cross-page continuities represented with reversible inline comments:

- scan 4 `ஏதோ` → scan 5 `இன்பக்கனவுகளோ`;
- scan 5 `அவைகளே` → scan 6 `கேலிக்குரியதாக`;
- scan 8 `கிழக்கு வானம் வெளுக்கத்` → scan 9 `துவங்கிவிட்டது.`;
- scan 10 `இருந்தாள்—` → scan 11 quoted continuation.

The source-printed Tiruppavai verse lines in scans 10–11 are retained as verse lines, not flattened into prose. No canonical page text changed during assembly.

## Current status

**Assembly: IN PROGRESS — 1 / 23 chapters VERIFIED.**

Next: Chapter 2, scans **13–22**. English remains blocked until the complete assembled layer passes its final consistency gate.
