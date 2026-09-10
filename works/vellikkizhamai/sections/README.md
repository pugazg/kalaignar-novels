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
| `05-chapter-05.md` | scan 45 after centered `5` → scan 51 | 5 | next |
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

1. Derive prose only from verified canonical `pages/` records.
2. Preserve source spelling, punctuation, dialogue, historical forms, colloquial forms and intentional oddities.
3. Exclude audit notes, printer/signature marks, illustrations and later handwriting from reading prose.
4. Keep reversible source provenance with HTML comments.
5. Join only already-verified page-boundary continuities.
6. Never change canonical page files merely to smooth assembled prose.
7. Assemble and verify one source chapter per iteration / commit.
8. Do not mark the layer `PASSED` until all 23 chapters and the final coverage / boundary / continuity / authority audit pass.

## Chapter 4 verification

`04-chapter-04.md` is **VERIFIED** from the post-`4` portion of scan 33 through the pre-`5` portion of scan 45.

Verified boundary continuities retained with reversible provenance include:

- scan 33 `பெண்வீடு பார்ப்பதற்குத் தாயார் மட்டுமே` → scan 34 `போவதாக இருக்கிறாள்.`;
- scan 37 `அழகப்பன்,` → scan 38 `நயினா, தாயார்...`;
- scan 38 `காரில்` → scan 39 `போய்க்கொண்டிருந்தார்களாம்.`;
- scan 39 `சாலையின் குறுக்கே` → scan 40 `கிடந்தவனும்...`;
- scan 40 `அடித்து மோதிக்` → scan 41 `கொண்டு அழுதாள்.`;
- scan 41 `தன்னைத்தானே` → scan 42 `அறிமுகப்படுத்திக்கொண்டு...`;
- scan 42 `ஏற்` + scan 43 `பட்டுவிட்டது`;
- scan 44 `நர்சு அவர்` + scan 45 `களச்...` is retained literally from the canonical page records without silent repair.

Scan 45 was split at centered source heading `5`; all post-heading Chapter 5 prose is reserved for `05-chapter-05.md`. The source punctuation oddity on scan 35 (opening quote before narrative `நயினாவின் கேலி...`) is preserved exactly. No canonical page text changed during Chapter 4 assembly.

## Current status

**Assembly: IN PROGRESS — 4 / 23 chapters VERIFIED.**

Next: **Chapter 5 — scan 45 after centered `5` through scan 51**. English remains blocked until the complete assembled Tamil layer passes its final consistency gate.
