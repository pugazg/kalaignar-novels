# Assembled Tamil Reading Layer — வெள்ளிக்கிழமை

This `sections/` layer is a source-faithful reading layer derived only from audited canonical `../pages/` records. Canonical `pages/` remain authoritative if any conflict appears.

## Assembly structure

The source has **23 chapters**. Mixed boundary scans are split at the source-printed centered chapter heading; a whole physical scan is never mechanically assigned to one chapter.

| File | Source coverage | Chapter | Status |
|---|---|---:|---|
| `01-chapter-01.md` | scans 4–12 | 1 | **VERIFIED** |
| `02-chapter-02.md` | scans 13–22 | 2 | **VERIFIED** |
| `03-chapter-03.md` | scan 23 → scan 33 before centered `4` | 3 | **VERIFIED** |
| `04-chapter-04.md` | scan 33 after centered `4` → scan 45 before centered `5` | 4 | **VERIFIED** |
| `05-chapter-05.md` | scan 45 after centered `5` → scan 51 | 5 | **VERIFIED** |
| `06-chapter-06.md` | scan 52 → scan 59 before centered `7` | 6 | **VERIFIED** |
| `07-chapter-07.md` | scan 59 after centered `7` → scan 68 before centered `8` | 7 | **VERIFIED** |
| `08-chapter-08.md` | scan 68 after centered `8` → scan 75 before centered `9` | 8 | **VERIFIED** |
| `09-chapter-09.md` | scan 75 after centered `9` → scan 85 before centered `10` | 9 | **VERIFIED** |
| `10-chapter-10.md` | scan 85 after centered `10` → scan 92 before centered `11` | 10 | next |
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

1. Derive prose only from verified canonical `pages/` records.
2. Preserve source spelling, punctuation, dialogue, historical forms, colloquial forms and intentional oddities.
3. Exclude audit notes, printer/signature marks, illustrations and later handwriting from reading prose.
4. Keep reversible source provenance with HTML comments.
5. Join only already-verified page-boundary continuities.
6. Never change canonical page files merely to smooth assembled prose.
7. Default workflow is one source chapter per iteration / commit; a larger contiguous batch may be assembled only when the user explicitly authorizes it. The Chapters 5–9 batch is such an explicit exception.
8. Do not mark the layer `PASSED` until all 23 chapters and the final coverage / boundary / continuity / authority audit pass.

## Chapters 5–9 batch verification

At the user's explicit direction, Chapters **5, 6, 7, 8 and 9** were assembled and verified together from audited canonical records. No canonical `pages/` file changed.

Mixed chapter boundaries were split at centered source headings on scans **59 (`7`)**, **68 (`8`)**, **75 (`9`)** and **85 (`10`)**. Chapter 6 starts cleanly at centered `6` on scan 52. Chapter 5 ends on scan 51.

Representative verified joins retained reversibly include:

- Chapter 5: scan 46→47 `நயினா மெளனமாக` → `நின்றான்.`; scan 47→48 `விரும்ப` + `மாட்டார்கள்`; scan 49→50 `கேலியும்` → `கிண்டலும் செய்தான்`; scan 50→51 `தாயாரின் கையைப்` → `பிடித்து`;
- Chapter 6: scan 52→53 `ஆபத்து வந்திருக்கலாம்` → `என்றும்`; scan 53→54 `அனுப்பப்பட்டிருக்க` + `கிறார்கள்`; scan 54→55 `பிறந்` + `திருக்கிற`; scan 56→57 `கண்டிப்பான` → `முடிவெடுத்தது.`;
- Chapter 7: scan 63→64 `அய்யோ, நம்மால் ஒருத்தியின் வாழ்க்கை` → `கெட்டுவிடுமே`; scan 65→66 `அதை ஆனந்தியின் உதட்டருகே` → `கொண்டுபோனான்`; scan 66→67 `அவளது அற்புத விழிகள்` → `அசைந்துகொண்டிருக்கின்றனவே!`;
- Chapter 8: scan 68→69 `எதிர்` + `பார்த்து`; scan 69→70 `ஏங்கியிருப்` + `பதாகவும்`; scan 73→74 `வரவேண்டுமா` → `என்ன?`; scan 74→75 `அங்கே` → `சிந்தாமணி காணப்படவில்லை.`;
- Chapter 9: scan 75→76 `இழுத்துச் சென்று` → `வீட்டிலேபோட்டுப்`; scan 77→78 `உண்மை` + `களாக`; scan 78→79 `உணர்ந்திருந்` + `தாள்.`; scan 80→81 `வந்த` → `கஷ்டத்தைப்`; scan 84→85 `அதோடு,` → `டைகர் தன் வீட்டு...`.

Scan 66's visible printed page number remains only `5`. Scan 82's bottom standalone `6` is excluded as a printer/signature mark. Source-specific punctuation, spacing, colloquial forms and canonical corrections remain unchanged.

## Current status

**Assembly: IN PROGRESS — 9 / 23 chapters VERIFIED.**

Next: **Chapter 10 — scan 85 after centered `10` through scan 92 before centered `11`**. English remains blocked until the complete assembled Tamil layer passes its final consistency gate.
