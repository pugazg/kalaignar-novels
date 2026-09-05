# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: **none — awaiting the next source/work supplied or named by the user**
- Completed reference implementations:
  - `works/balipeedam-nokki/` — unqualified release-ready reference;
  - `works/periya-idathup-pen/` — completed qualified-release reference with an explicit canonical verification freeze.

Before changing repository state, fetch live `main` first. For a new work, follow `NEXT_NOVEL_CHAT_PROMPT.md` and `NOVEL_PROCESSING_GUIDE.md`. Do not reopen completed works merely because a historical audit/review records an earlier stage. Source PDFs remain controlling evidence and must not be committed.

## பெரிய இடத்துப் பெண் — COMPLETED durable state

Source: `TVA_BOK_0064090_பெரிய_இடத்துப்_பெண்_1953.pdf`  
SHA-256: `50db9c55d670065bd81088ee07e4527f5531a9ab15e3c4533d6b10eda8d09e9628`  
Scans: **49**  
Title: **பெரிய இடத்துப் பெண்**  
Author: **மு. கருணாநிதி**  
Publisher/place: **திராவிடன் பதிப்பகம் / வேலூர் (வ. ஆ.)**  
Edition: **எட்டாம் பதிப்பு: ஜூலை 1953**  
Final printer colophon: **ஸ்ரீமகள் அச்சகம், சென்னை-1**.

### Verification freeze — MUST PRESERVE

**Do not mark any canonical page in this work as `verified` unless the user explicitly changes the instruction.**

Known Periyar-reform-sensitive reference set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Canonical state remains **0 verified / 49 `needs-review`**. The assembled Tamil layer's **PASSED**, English **VERIFIED**, and qualified release-readiness statuses are independent of that freeze.

### Canonical / Tamil state

- page map: **49 / 49**;
- canonical page records: **49 / 49**;
- dedicated full-source audit: **COMPLETE — 49 / 49 directly reviewed**;
- assembled Tamil: **PASSED — seven files covering narrative scans 8–49**;
- source PDF committed: **No**.

Confirmed historical-glyph corrections include scan 14 `ஆவலைக்`, `நின்றார்`; scan 16 `போகிறாயே`; the corrected `நன்றாக` family; scan 25 `வேலை மட்டுந்தானா?`; scan 33 `கண்ணாடி`; scan 43 `இளிச்சவாயனாக`; scan 46 `நானா ஆள்?`; and scan 47 `விட வேணா?`.

The source remains one continuous work with internal headings `உத்தண்டி`, `கண்ணம்மா`, `குமுதா`, `வீரன்`, `உலகநாதர்`, `கண்ணம்மா`.

### English / release state

Working English title: **The Woman of the Great House**.

- English section files: **7 / 7 reviewed**;
- translation batches: **8 / 8 reviewed**;
- final bilingual review: **PASSED**;
- whole-work English: **VERIFIED**;
- release-readiness pass: **PASSED WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION**;
- release report: `works/periya-idathup-pen/translations/en/RELEASE_REPORT.md`;
- repository documentation closeout: `works/periya-idathup-pen/COMPLETION_SYNC_AUDIT.md`.

Accurate package wording:

> **English layer release-ready; archival package RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION — 0 verified / 49 `needs-review`, freeze ACTIVE.**

Section files intentionally retain batch-level `reviewed`; whole-work English `VERIFIED` is established by `translations/en/TRANSLATION_REVIEW.md`.

The final review found one English-only romanisation drift: scan-49 `ரதி` was corrected from **Rathi** to **Rati**. Tamil was unchanged.

Release readiness is an editorial/archival workflow status, not a determination of copyright, licensing, distribution or republication rights.

### No remaining mandatory activity on this title

Do not lift, reinterpret or bypass the canonical Tamil verification freeze automatically. Do not restart source audit, assembly, translation, final bilingual review or release review because an older stage document described them as future work. The repository-wide completion sync marks those older instructions as superseded historical stage notes.

If the user explicitly reopens this title, first preserve the live completed state and the freeze. Otherwise, the next repository activity is to onboard the next source/work supplied or named by the user.

---

## Completed prior work — புதையல்

`புதையல்` remains at its durable release state: **448 / 448** canonical records, **446** completed, two physical-loss scans **223–224** still `needs-review`, assembled Tamil complete, whole-work English VERIFIED, release-ready with those two qualifications.

## Completed prior work — பலிபீடம் நோக்கி

`பலிபீடம் நோக்கி` remains unchanged: Tamil **34 / 34 verified**, assembled Tamil PASSED, English VERIFIED, archival package RELEASE-READY.

## Exact next repository activity

**Await a new source/work.** Once the user supplies or names one, fetch live `main`, follow `NEXT_NOVEL_CHAT_PROMPT.md`, inspect the actual source, and begin source-first intake. There is currently no active work.