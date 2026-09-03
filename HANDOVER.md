# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Current work: `works/pudhaiyal/`

## Authority rule

Native scans control page identity, punctuation, quotation marks, paragraph/section structure, physical boundaries, separators, chapter transitions, narrative ending and back matter.

From scan **280 onward**, user-supplied Gemini transcription controls lexical words/forms/spacing:

- Part 007 — `p7.md`
- Part 008 — `p8.md`
- Part 009 — `p9.md`
- Part 010 — `p10.md`

Complete source-visible lexical spans absent from the baseline require explicit user disposition rather than silent insertion. Source/split PDFs and uploaded baseline files are never committed.

## Source identity — புதையல்

- author: கலைஞர் மு. கருணாநிதி, எம். எல். ஏ.
- publisher: அன்புப் பதிப்பகம், பொறையார் :: தஞ்சை மாவட்டம்
- edition: மூன்றாம் பதிப்பு — செப்டம்பர் 1961
- TDL bibliographic extent: **443 p.**
- exact original full-file byte/SHA reconciliation remains separate from the split-derivative workflow

## Durable split state

- Parts **001–010: part-complete**
- Part 009 / scans **393–441 / printed 389–437**: **Tamil audit PASSED + assembled Tamil PASSED + controlled English source check PASSED + bilingual review PASSED / part-complete**
- Part 010 / scans **442–448**: **Tamil audit PASSED + assembled Tamil PASSED + controlled English source check PASSED + bilingual review PASSED / part-complete**
- Part-005 source-damage qualification remains on scans **215–219 and 223–224**.

Part 009 records:

- `works/pudhaiyal/notes/part-009-tamil-audit.md`
- `works/pudhaiyal/notes/part-009-assembled-tamil-check.md`
- `works/pudhaiyal/translations/en/PART_009_ENGLISH_CHECK.md`
- `works/pudhaiyal/translations/en/PART_009_REVIEW.md`
- result: **49 / 49 verified, 0 Part-009 needs-review**
- English source check: **PASSED with one English-only Chapter-46 ritual-oath fidelity correction**
- bilingual review: **PASSED with no additional English changes required**
- no complete `p9.md` lexical omission found
- baseline-only structure marks rejected: `⚬` scan 416; `*` scan 435

Part 010 records:

- `works/pudhaiyal/notes/part-010-tamil-audit.md`
- `works/pudhaiyal/notes/part-010-assembled-tamil-check.md`
- `works/pudhaiyal/translations/en/PART_010_ENGLISH_CHECK.md`
- `works/pudhaiyal/translations/en/PART_010_REVIEW.md`
- `works/pudhaiyal/translations/en/sections/51-chapter-51.md` — bilingual-reviewed through the actual narrative ending on scan 447
- `works/pudhaiyal/translations/en/sections/99-printer-colophon.md` — bilingual-reviewed scan-448 back matter
- result: **7 / 7 verified, 0 Part-010 needs-review**
- controlled English source check: **PASSED with no new correction required during the formal check**
- bilingual review: **PASSED with one English-only scan-445 rhetorical fidelity refinement**
- scan 445 native `விடு`, omitted from `p10.md`, was explicitly authorized by the user on 2026-09-03 and restored narrowly; English represents the complete command as **“bury it beside Thangam!”**
- immediately before the formal source-check gate, scan-446 `ஐயப்பன் கொலை வழக்கு` was refined from “Ayyappan case” to **“Ayyappan murder case”**; the source check confirmed that wording
- bilingual review restored Mayandi's scan-445 self-reproach `இந்தப் பாவி` as **“this sinner”** rather than leaving that rhetorical nuance implicit

Verified source/reading boundaries:

- Part 008→009: `நமது` + `வாழ்க்கையை` → **`நமது வாழ்க்கையை`**;
- Part 009→010: `அம்ப` + `லமே` → **`அம்பலமே`**; English reviewed `Amb` + Part-010 continuation → **`Ambalam`**;
- scan **447 / printed 443**: actual narrative ending;
- scan **448**: separate printer colophon `அன்பு அச்சகம், பொறையார்.`

## Assembled Tamil frontier

- Chapter 45 continues through its close in Part 009.
- Chapters **46–50** are assembled from audited Part-009 pages.
- Chapter **51** is assembled continuously across Parts 009–010 through the actual ending on scan 447.
- scan 448 is separate in `works/pudhaiyal/sections/99-printer-colophon.md` and is not narrative.

## English frontier

- source-checked English narrative: continuous through **scan 447 / printed 443 — actual novel ending**;
- source-checked English back matter: through **scan 448 printer colophon**;
- bilingual-reviewed English narrative: continuous through **scan 447 / printed 443 — actual novel ending**;
- bilingual-reviewed English back matter: through **scan 448 printer colophon**;
- Chapter 45 Part-009 continuation is **bilingual-reviewed through its close on scan 396 portion**, resolving the audited `நமது வாழ்க்கையை` join;
- Chapters 46–50 are **bilingual-reviewed continuously through the Chapter-50 close on scan 438 portion**;
- Chapter 46 source check made one English-only fidelity refinement to the ritual-oath sequence, removing the draft's added interpretive phrase `in oath` while leaving Tamil unchanged;
- Chapter 51 is now **bilingual-reviewed continuously through the actual ending on scan 447**; the Part-009 `Amb` boundary is completed once as **`Ambalam`**, corresponding to Tamil `அம்ப` + `லமே`;
- the Part-010 reviewed English preserves the authorized scan-445 `விடு`, the scan-446 legal wording **“Ayyappan murder case”**, the source's scan-446 `ஆகர` exclamation conservatively as **`Agar!`**, the recovered treasure-secret sequence, and the final source wording that Durai goes to report that **“Velliyambalam had returned”** rather than rationalizing it;
- the bilingual review restored Mayandi's scan-445 self-reproach as **“this sinner”** in his final letter;
- scan 448 is bilingual-reviewed separately as English printer-colophon back matter **“Anbu Press, Poraiyar.”**.

## Aggregate durable state

- canonical records: **448**
- verified/completed: **441**
- needs-review: **7 — only Part 005 scans 215–219 and 223–224**
- partial: **0**
- assembled Tamil narrative: continuous through **scan 447 / printed 443 — actual ending**
- assembled back matter: through **scan 448**
- source-checked English narrative: continuous through **scan 447 / printed 443 — actual ending**
- source-checked English back matter: through **scan 448**
- bilingual-reviewed English narrative: continuous through **scan 447 / printed 443 — actual ending**
- bilingual-reviewed English back matter: through **scan 448**
- Parts **001–010: part-complete**
- whole-work English / release review: **PENDING**
- no whole-work verified or release-ready claim has yet been made

## Exact next activity

Run the **final whole-work English / release review for `புதையல்`** across the complete assembled English package. Verify front matter, introduction, Chapters 1–51, all split-boundary joins, the Part-005 source-damage qualifications, user-authorized restorations, controlled terminology, the narrative ending on scan 447, separate scan-448 colophon, and consistency of all per-part source-check/review records. Only after that whole-work gate passes should `புதையல்` be marked English verified / release-ready.