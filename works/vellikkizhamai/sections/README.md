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
| `10-chapter-10.md` | scan 85 after centered `10` → scan 92 before centered `11` | 10 | **VERIFIED** |
| `11-chapter-11.md` | scan 92 after centered `11` → scan 99 before centered `12` | 11 | **VERIFIED** |
| `12-chapter-12.md` | scan 99 after centered `12` → scan 107 before centered `13` | 12 | **VERIFIED** |
| `13-chapter-13.md` | scan 107 after centered `13` → scan 115 before centered `14` | 13 | **VERIFIED** |
| `14-chapter-14.md` | scan 115 after centered `14` → scan 120 before centered `15` | 14 | **VERIFIED** |
| `15-chapter-15.md` | scan 120 after centered `15` → scan 126 | 15 | **VERIFIED** |
| `16-chapter-16.md` | scan 127 after centered `16` → scan 134 before centered `17` | 16 | **VERIFIED** |
| `17-chapter-17.md` | scan 134 after centered `17` → scan 142 before centered `18` | 17 | **VERIFIED** |
| `18-chapter-18.md` | scan 142 after centered `18` → scan 149 before centered `19` | 18 | **VERIFIED** |
| `19-chapter-19.md` | scan 149 after centered `19` → scan 154 before centered `20` | 19 | **VERIFIED** |
| `20-chapter-20.md` | scan 154 after centered `20` → scan 160 before centered `21` | 20 | **VERIFIED** |
| `21-chapter-21.md` | scan 160 after centered `21` → scan 166 before centered `22` | 21 | **VERIFIED** |
| `22-chapter-22.md` | scan 166 after centered `22` → scan 172 before centered `23` | 22 | **VERIFIED** |
| `23-chapter-23.md` | scan 172 after centered `23` → scan 179 | 23 | **VERIFIED** |

## Assembly rules

1. Derive prose only from verified canonical `pages/` records.
2. Preserve source spelling, punctuation, dialogue, historical forms, colloquial forms and intentional oddities.
3. Exclude audit notes, printer/signature marks, illustrations and later handwriting from reading prose.
4. Keep reversible source provenance with HTML comments.
5. Join only already-verified page-boundary continuities; never invent missing text from grammar.
6. Split mixed boundary scans only at the source-printed centered chapter heading.
7. Canonical `pages/` remain controlling authority and are never changed merely to smooth reading flow.

## Assembly history

- Chapters **1–4** — completed in chapter-sized iterations.
- Chapters **5–9** — verified in a user-authorized five-chapter batch.
- Chapters **10–19** — verified in a user-authorized ten-chapter batch.
- Chapter **20** — verified in the default one-chapter workflow.
- Chapters **21–23** — verified together after explicit user authorization to assemble all remaining chapters.

Across all assembly work, mixed physical scans were split only at centered source headings, canonical source oddities were preserved, printer/signature marks were excluded, and no canonical `pages/` record was changed.

## Final assembled Tamil consistency gate

**PASS — 2026-09-10.**

The final gate confirmed:

- exactly **23 / 23** chapter section files, with `section_order` **1–23**, `status: verified`, and derivation from audited canonical page records;
- contiguous narrative coverage from Chapter 1 opening on **scan 4** through the final narrative on **scan 179 / printed 178**;
- correct chapter-boundary treatment, including centered mixed-scan splits at scans **33, 45, 59, 68, 75, 85, 92, 99, 107, 115, 120, 134, 142, 149, 154, 160, 166 and 172**, plus clean chapter openings where the source starts a chapter on a fresh scan;
- Chapter 15 correctly ends on **scan 126**, with Chapter 16 opening cleanly on **scan 127**;
- every assembled cross-page join remains source-verified and reversible through provenance comments;
- literal source discontinuities remain unrepaired, including scan **117→118** (`உட்` → `எவ்வளவோ முயன்றும் நடக்கவில்லை.`), scan **122→123** (`...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.`), and scan **156→157** (`தலையிலும் காயம்` → `நயினா எதிர்த்தே அடிக்கவில்லை.`);
- non-body printer/signature marks are absent from assembled prose, and scan 179 contributes only its final narrative paragraph while its lower illustration and later handwriting remain excluded;
- comparison from the passed Tamil-source checkpoint `591fe29f7ce6bb7f814f165b757098e89fe25aa5` through the completed assembly head `52d7dcd9d6c5d561ca14f69fd850d37a55963310` shows **no canonical `works/vellikkizhamai/pages/` changes**.

Final gate result: **PASS — 23 / 23 chapters; 0 unresolved; 0 canonical changes.**

## Current status

**ASSEMBLED TAMIL: PASSED — 23 / 23 chapters VERIFIED.**

English prose has **not** started. The translation-planning gate is now open.

Next: create `../translations/en/TRANSLATION_PLAN.md` as required by `NOVEL_PROCESSING_GUIDE.md`. Do not begin English prose until that plan exists.