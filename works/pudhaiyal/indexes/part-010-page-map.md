# Part 010 page map — புதையல்

Access derivative: `TVA_BOK_0064097_புதையல்_part_010_pages_442-448.pdf`

- split pages: **7**
- represented source scans: **442–448**
- visible printed-page range: **438–443** on scans 442–447
- scan 448: **unnumbered printer colophon**
- derivative file size: **7,206,369 bytes**
- derivative SHA-256: `27660cd6a8abe288ea1924f4ca02c23747713afc5883b010fb2f58a61b6ebbd0`
- lexical baseline: uploaded `p10.md`, **17,559 bytes / 165 logical lines**
- `p10.md` SHA-256: `938407860a3a80e14da3a5d6a273675b8cdcc3e70e8a0e538f40dcceb871dc3a`
- source/split PDF committed: **No**
- baseline file committed: **No**
- canonical records: **7 / 7**
- verified: **6 / 7**
- needs-review: **1 — scan 445 / printed 441**
- not-started: **0**
- split state: **`canonical-complete / tamil-audit-blocked-on-lexical-omission`**

## Authority rule

`p10.md` controls lexical/textual wording. Native scans control page identity, punctuation, quotation marks, paragraphing, physical boundaries, chapter/work ending structure and back matter. Complete source-visible lexical spans absent from `p10.md` require explicit disposition rather than silent insertion.

Part 009 scan 441 ends `அம்ப`; Part 010 scan 442 begins `லமே`, proving **`அம்பலமே`** across the split.

## Lexical omission requiring disposition

Native scan **445 / printed 441** contains:

`தங்கத்திற்குப் பக்கத்திலே புதைத்து விடு!”`

The controlling `p10.md` baseline contains only:

`தங்கத்திற்குப் பக்கத்திலே புதைத்து` + closing quotation mark.

Therefore the complete native word **`விடு`** is currently withheld from canonical scan 445 and that page remains `needs-review` pending explicit user disposition.

| Source scan | Printed page | Section | Status | File / note |
|---:|:---:|---|---|---|
| 442 | 438 | chapter 51 continuation | verified | `../pages/0442-pudhaiyal.md`; Part 009 `அம்ப` → `லமே` |
| 443 | 439 | chapter 51 continuation | verified | `../pages/0443-pudhaiyal.md` |
| 444 | 440 | chapter 51 continuation | verified | `../pages/0444-pudhaiyal.md` |
| 445 | 441 | chapter 51 continuation | **needs-review** | `../pages/0445-pudhaiyal.md`; native `விடு` absent from `p10.md` |
| 446 | 442 | chapter 51 continuation | verified | `../pages/0446-pudhaiyal.md` |
| 447 | 443 | chapter 51 / narrative ending | verified | `../pages/0447-pudhaiyal.md`; native closing rule + ending emblem |
| 448 | — | printer colophon / back matter | verified | `../pages/0448-pudhaiyal.md`; `அன்பு அச்சகம், பொறையார்.` |

## Ending structure

- scan **447 / printed 443**: Chapter 51 and the narrative end;
- scan **448**: separate printer colophon / back matter, `அன்பு அச்சகம், பொறையார்.`

## Exact next activity

Resolve the scan-445 lexical omission. If the user authorizes native **`விடு`**, insert it narrowly, return scan 445 to `verified`, rerun Part-010 Tamil audit and then proceed to assembled Tamil for Parts 009–010.