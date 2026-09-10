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

Boundary scan ஒன்று இரண்டு chapters-ஐ கொண்டிருந்தால் அந்த scan source-printed centered chapter heading-இல் split செய்யப்படும். முழு scan-ஐ mechanically ஒரு chapter-க்கு assign செய்யக்கூடாது.

| File | Source coverage | Chapter | Status |
|---|---|---:|---|
| `01-chapter-01.md` | scans 4–12 | 1 | **VERIFIED** |
| `02-chapter-02.md` | scans 13–22 | 2 | **VERIFIED** |
| `03-chapter-03.md` | scan 23 → scan 33 before centered `4` | 3 | **VERIFIED** |
| `04-chapter-04.md` | scan 33 after centered `4` → scan 45 before centered `5` | 4 | next |
| `05-chapter-05.md` | scan 45 after centered `5` → scan 51 | 5 | pending |
| `06-chapter-06.md` | scan 52 → scan 59 before centered `7` | 6 | pending |
| `07-chapter-07.md` | scan 59 after centered `7` → scan 68 before centered `8` | 7 | pending |
| `08-chapter-08.md` | scan 68 after centered `8` → scan 75 before centered `9` | 8 | pending |
| `09-chapter-09.md` | scan 75 after centered `9` → scan 85 before centered `10` | 9 | pending |
| `10-chapter-10.md` | scan 85 after centered `10` → scan 92 before centered `11` | 10 | pending |
| `11-chapter-11.md` | scan 92 after centered `11` → scan 99 before centered `12` | 11 | pending |
| `12-chapter-12.md` | scan 99 after centered `12` → scan 107 before centered `13` | 12 | pending |
| `13-chapter-13.md` | scan 107 after centered `13` → scan 115 before centered `14` | 13 | pending |
| `14-chapter-14.md` | scan 115 after centered `14` → scan 120 before centered `15` | 14 | pending |
| `15-chapter-15.md` | scan 120 after centered `15` → scan 127 before centered `16` | 15 | pending |
| `16-chapter-16.md` | scan 127 after centered `16` → scan 134 before centered `17` | 16 | pending |
| `17-chapter-17.md` | scan 134 after centered `17` → scan 142 before centered `18` | 17 | pending |
| `18-chapter-18.md` | scan 142 after centered `18` → scan 149 before centered `19` | 18 | pending |
| `19-chapter-19.md` | scan 149 after centered `19` → scan 154 before centered `20` | 19 | pending |
| `20-chapter-20.md` | scan 154 after centered `20` → scan 160 before centered `21` | 20 | pending |
| `21-chapter-21.md` | scan 160 after centered `21` → scan 166 before centered `22` | 21 | pending |
| `22-chapter-22.md` | scan 166 after centered `22` → scan 172 before centered `23` | 22 | pending |
| `23-chapter-23.md` | scan 172 after centered `23` → scan 179 | 23 | pending |

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

## Chapter 2 verification

`02-chapter-02.md` covers scans **13–22** and is **VERIFIED**.

Verified cross-page continuities represented with reversible provenance:

- scan 14 `அதிலே` → scan 15 `வரும் அர்ச்சுனன்`;
- scan 16 `எண்ணும்` → scan 17 `போது—`;
- scan 17→18 preserves the dialogue reply after `“சுசீலா! நீ?”`;
- scan 21→22 preserves the dialogue reply after `“லேடி டாக்டர் வந்தாச்சுல்லே?”`.

Source `* * *` separators and paragraph/dialogue structure are retained. No canonical page text changed during assembly.

## Chapter 3 verification

`03-chapter-03.md` covers **scan 23 through the Chapter 3 carryover at the top of scan 33 before centered `4`** and is **VERIFIED**.

Verified cross-page continuities represented with reversible provenance:

- scan 23 `உணர்ந்திருந்ததோடு` → scan 24 `மட்டுமல்ல;`;
- scan 24 `அவர்` + scan 25 `கள்தானே` → `அவர்கள்தானே`;
- scan 25 `சேர்ந்` + scan 26 `தான்.` → `சேர்ந்தான்.`;
- scan 28 `விஷயத்தை வெளி` + scan 29 `யில் சொல்லாதே` → `விஷயத்தை வெளியில் சொல்லாதே`;
- scan 31 `மூன்றாவது` → scan 32 `ஆள் வேம்பு!`.

Scan 33 was split at the source-printed centered `4`: only the opening Chapter 3 dialogue paragraph is present in `03-chapter-03.md`; the Chapter 4 heading and all post-heading prose are reserved for `04-chapter-04.md`. No canonical page text changed during assembly.

## Current status

**Assembly: IN PROGRESS — 3 / 23 chapters VERIFIED.**

Next: Chapter 4, from **scan 33 after centered `4` through scan 45 before centered `5`**. Both boundary scans must be split at their source-printed centered headings. English remains blocked until the complete assembled layer passes its final consistency gate.
