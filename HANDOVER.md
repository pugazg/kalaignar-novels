# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Current target: **வெள்ளிக்கிழமை**
- Active path: `works/vellikkizhamai/`

Before changing repository state, fetch live `main` first. Read `NOVEL_PROCESSING_GUIDE.md`, `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`, this handover, and the active-work README/audit/page map. Source PDFs remain controlling evidence and must not be committed.

## வெள்ளிக்கிழமை — ACTIVE source intake

Source: `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`  
SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`  
File size: **251,126,214 bytes**  
Actual PDF scans: **179**  
Source text layer: **none / image-only**  
Title: **வெள்ளிக்கிழமை**  
Author as printed: **மு. கருணாநிதி**  
Publisher: **திராவிடப்பண்ணை**  
Edition: **இரண்டாம் பதிப்பு: 1968**  
Price: **ரூ. 2-50**  
Printer: **சக்திவேல் பிரஸ், திருச்சிராப்பள்ளி-2.**

### Current state

- initial page manifest: **179 / 179 scans represented**;
- canonical page records: **3 / 179**;
- scans 1–3: **verified front matter**;
- body transcription: **not started**;
- printed-page mapping: **sampled only / full audit pending**;
- chapter mapping: **partial**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**;
- source PDF committed: **No**.

### Directly confirmed structure / numbering

- scan 4 — Chapter 1 opening; no visible printed page number;
- scan 5 — printed page 4;
- scan 13 — Chapter 2;
- scan 23 — Chapter 3;
- scan 33 — Chapter 4;
- scan 45 — Chapter 5;
- scan 52 — Chapter 6;
- scan 60 — Chapter 7;
- scan 68 — Chapter 8;
- scan 176 — printed page 175;
- scan 179 — printed page 178, final narrative paragraph plus illustration.

Do not infer later chapter boundaries or unreviewed printed-page values from sequence alone.

### Historical-glyph rule — mandatory from scan 4 onward

Use the source-pixel workflow for the known minimum set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

For every doubtful cluster, inspect the complete glyph at enlarged/native resolution, compare same-edition forms if useful, and encode only proven character identity. Do not modernize spelling/grammar/punctuation. Never global-replace. Several sampled body pages also contain later marks; do not merge those into printed text.

### User-supplied context

The user supplied a synopsis describing the work as rejecting inherent specialness in Friday while narrating a family trapped in a dangerous social situation and the destruction of a vulnerable woman's life. Treat this as contextual orientation only, not canonical source transcription.

### Exact next activity

Process **scans 4–8** as the first narrative batch:

1. inspect each scan directly at high resolution;
2. transcribe printed Tamil only;
3. populate each visible printed-page value individually;
4. run historical-glyph pre-correction checks;
5. separate underlining/handwriting/marks from printed text;
6. create canonical page records;
7. update `indexes/page-map.md`, `audit.md`, and the work README;
8. commit the batch with a narrow descriptive commit.

Stop before scan 9 unless explicitly instructed to continue farther.

---

## Completed work — பெரிய இடத்துப் பெண்

`works/periya-idathup-pen/` remains complete with **49 / 49** source-comparison coverage, assembled Tamil PASSED, English VERIFIED, and **RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION**. Its canonical freeze remains **0 verified / 49 `needs-review`** and must not be lifted automatically.

## Completed work — புதையல்

`புதையல்` remains at its durable release state: **448 / 448** canonical records, **446** completed, two physical-loss scans **223–224** still `needs-review`, assembled Tamil complete, whole-work English VERIFIED, release-ready with those two qualifications.

## Completed work — பலிபீடம் நோக்கி

`பலிபீடம் நோக்கி` remains unchanged: Tamil **34 / 34 verified**, assembled Tamil PASSED, English VERIFIED, archival package RELEASE-READY.