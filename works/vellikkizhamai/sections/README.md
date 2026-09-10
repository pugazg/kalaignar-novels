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
| `15-chapter-15.md` | scan 120 after centered `15` → scan 127 before centered `16` | 15 | **VERIFIED** |
| `16-chapter-16.md` | scan 127 after centered `16` → scan 134 before centered `17` | 16 | **VERIFIED** |
| `17-chapter-17.md` | scan 134 after centered `17` → scan 142 before centered `18` | 17 | **VERIFIED** |
| `18-chapter-18.md` | scan 142 after centered `18` → scan 149 before centered `19` | 18 | **VERIFIED** |
| `19-chapter-19.md` | scan 149 after centered `19` → scan 154 before centered `20` | 19 | **VERIFIED** |
| `20-chapter-20.md` | scan 154 after centered `20` → scan 160 before centered `21` | 20 | **VERIFIED** |
| `21-chapter-21.md` | scan 160 after centered `21` → scan 166 before centered `22` | 21 | next |
| `22-chapter-22.md` | scan 166 after centered `22` → scan 172 before centered `23` | 22 | pending |
| `23-chapter-23.md` | scan 172 after centered `23` → scan 179 | 23 | pending |

## Assembly rules

1. Derive prose only from verified canonical `pages/` records.
2. Preserve source spelling, punctuation, dialogue, historical forms, colloquial forms and intentional oddities.
3. Exclude audit notes, printer/signature marks, illustrations and later handwriting from reading prose.
4. Keep reversible source provenance with HTML comments.
5. Join only already-verified page-boundary continuities; never invent missing text from grammar.
6. Split mixed boundary scans only at the source-printed centered chapter heading.
7. Canonical `pages/` remain controlling authority and are never changed merely to smooth reading flow.
8. Default workflow is one chapter per iteration; a larger contiguous batch is allowed only on explicit user authorization. Chapters 5–9 and 10–19 were explicit user-authorized batches.
9. Do not mark this layer `PASSED` until all 23 chapters and the final coverage / boundary / continuity / canonical-authority audit pass.

## Chapters 10–19 batch verification

At the user's explicit direction, Chapters **10–19** were assembled and independently verified together from the audited canonical records. No canonical `pages/` file changed.

Mixed chapter-boundary scans were split at centered headings on scans **92 (`11`)**, **99 (`12`)**, **107 (`13`)**, **115 (`14`)**, **120 (`15`)**, **134 (`17`)**, **142 (`18`)**, **149 (`19`)**, and **154 (`20`)**. Chapter 16 begins cleanly at centered `16` on scan 127.

Important source-preservation decisions remain reversible in the section files, including the literal scan 117/118 discontinuity (`உட்` followed by `எவ்வளவோ...`) with no invented completion; scan 122/123 literal `...அவளுக்குப் பக்கத்திலே` → `கார்ந்து கொண்டாள்.` with no grammatical repair; and all verified cross-page word fragments such as `வாழ்` + `விலே`, `அழகப்ப` + `னுடைய`, `பின்னிக்` + `கொண்டன`, `தேவ` + `லோகத்தில்`, and `சந்திப்` + `பதற்காக!`.

Printer/signature marks remain excluded from reading prose, including scan 130 bottom `9`, scan 146 bottom `10`, and earlier recorded non-body marks.

## Chapter 20 verification

Chapter **20** was assembled from canonical scans **154 after centered `20` through 160 before centered `21`** and independently checked against those verified records. Mixed boundary scans 154 and 160 were split only at centered `20` and `21`; no canonical `pages/` file changed.

Verified reading-layer joins are preserved reversibly: scan 155 `சோலை` + scan 156 `யில்` → `சோலையில்`; scan 157 `பயங்கரமாக—` continues with scan 158 `ஆனந்தியிருக்கும்`; scan 158 `வராத` + scan 159 `கண்ணீர்,`; and scan 159 `அழகப்பனுக்கும்` + scan 160 `ஒன்றும் புரியவில்லை.` The scan 156→157 physical discontinuity remains literal as `தலையிலும் காயம்` followed by `நயினா எதிர்த்தே அடிக்கவில்லை.` with no supplied punctuation or inferred repair.

## Current status

**Assembly: IN PROGRESS — 20 / 23 chapters VERIFIED.**

Next: **Chapter 21 — scan 160 after centered `21` through scan 166 before centered `22`**. English remains blocked until the complete assembled Tamil layer passes its final consistency gate.
