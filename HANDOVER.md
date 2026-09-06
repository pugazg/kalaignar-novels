# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- Primary guide: `NOVEL_PROCESSING_GUIDE.md`
- Reusable historical-glyph guide: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- Continuation prompt: `NEXT_NOVEL_CHAT_PROMPT.md`
- Current target: **வெள்ளிக்கிழமை**
- Active path: `works/vellikkizhamai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve any newer durable work. Do not reset or repeat completed work merely because this handover records an older checkpoint.

Last confirmed live checkpoint when this handover was prepared:

`708ffce5ec4304ed19afcb44ccd6908f8ea7a16e` — **`Transcribe வெள்ளிக்கிழமை scans 13-17`**

Before any source-dependent change, read completely:

1. `NOVEL_PROCESSING_GUIDE.md`
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
3. root `README.md`
4. this `HANDOVER.md`
5. `NEXT_NOVEL_CHAT_PROMPT.md`
6. `works/vellikkizhamai/README.md`
7. `works/vellikkizhamai/metadata/source.md`
8. `works/vellikkizhamai/indexes/page-map.md`
9. `works/vellikkizhamai/audit.md`
10. existing `works/vellikkizhamai/pages/*.md`

The controlling PDF must be attached/resolved again in the new chat before scan-level visual work. Do not commit the source PDF.

---

# வெள்ளிக்கிழமை — ACTIVE Tamil transcription

Controlling source: `TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`  
SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`  
File size: **251,126,214 bytes**  
Recorded actual PDF scans: **179**  
Source text layer: **none / image-only**  
Title: **வெள்ளிக்கிழமை**  
Author as printed on source: **மு. கருணாநிதி**  
Publisher: **திராவிடப்பண்ணை**  
Edition: **இரண்டாம் பதிப்பு: 1968**  
Price: **ரூ. 2-50**  
Printer: **சக்திவேல் பிரஸ், திருச்சிராப்பள்ளி-2.**

User-supplied catalogue/context form `கலைஞர் மு. கருணாநிதி` is contextual only; canonical source metadata preserves the cover wording `மு. கருணாநிதி`.

## Current durable state

- page manifest: **179 / 179 scans represented**;
- canonical page records: **17 / 179**;
- scans 1–3 front matter: **verified**;
- scans 4–12 / Chapter 1: **verified / complete**;
- scans 13–17 / Chapter 2 opening: **verified**;
- printed-page mapping established through scan 17: scan 4 and scan 9 unnumbered; scans 5–8 = printed **4–7**; scans 10–17 = printed **9–16**;
- Chapter 1 closes on scan 12;
- scan 13 begins source-printed Chapter 2;
- scan 23 is directly confirmed as Chapter 3 opening;
- later chapter openings directly located at scans 33, 45, 52, 60, 68 for Chapters 4–8;
- full later chapter map: **pending**;
- full Tamil source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**;
- source PDF committed: **No**.

## Important previous-chat status — scans 18–22

The previous chat opened and visually inspected scans **18–22** and confirmed their visible printed pages as **17–21**. They continue Chapter 2 and end immediately before scan 23 / Chapter 3.

However, **no canonical page records for scans 18–22 were committed and no durable verified transcription exists for those scans**. Some provisional reading work happened in-chat, but it must not be treated as repository authority.

Therefore, in a fresh chat:

- reattach/resolve the controlling PDF;
- re-inspect scans 18–22 from source pixels;
- independently source-check every transcription decision;
- only then create/commit canonical pages 0018–0022.

Do not claim 22/179 complete until the commit actually lands on live `main`.

## Completed source-sensitive checkpoints

### Scans 4–8

Historical-glyph gate applied page by page. The scan-8 held cluster is source-supported as:

**`களைத்துத் தூங்கிவிட்டால்`**

with historical `ளை` identity. No contextual guess, spelling modernization, or global replacement was used.

Boundary notes:
- scan 4 final `ஏதோ` → scan 5;
- scan 5 final `அவைகளே` → scan 6 `கேலிக்குரியதாக ஆக்கிய...`;
- scan 8 final `கிழக்கு வானம் வெளுக்கத்` → scan 9 `துவங்கிவிட்டது.`

### Scans 9–12 / Chapter 1 completion

- source-specific scan 9 `குழப்பட்டு` preserved;
- source-specific scan 12 `அந்தப் பருக்கூட்டமே` preserved;
- Tiruppavai quotations are transcribed from this scanned edition, not replaced with an external canonical text;
- scan 12 closes Chapter 1;
- no unresolved glyph/source item remains through scan 12.

### Scans 13–17 / Chapter 2 opening

- scan 13 / printed 12 begins Chapter 2;
- source-sensitive wording preserved, including `எடுபிடி ஆள் அப்புகள்`, `இன்பபுரி வெண்புருக்கள்`, `வேலையில்ல`, `நல்லதாப் போச்சு`;
- scan 14 final `அதிலே` → scan 15 `வரும் அர்ச்சுனன்...`;
- scan 16 final `எண்ணும்` → scan 17 `போது—`;
- scan 17 ends `“சுசீலா! நீ?”`; Suseela's reply begins on scan 18;
- no unresolved glyph/source item remains through scan 17.

## Source authority and transcription rules

Authority order:

**controlling source scan → canonical `pages/` → later assembled Tamil → later English**

OCR, Wikisource, web copies, or machine extraction may be used only as secondary reading aids. They are never controlling authority. Any candidate reading must be confirmed against the supplied source pixels before entering canonical text.

Do not silently modernize or correct spelling, wording, grammar, punctuation, vocabulary, names, dialogue, or structure.

Separate printed text from later underlining, ticks, handwriting, stamps, bleed-through, and scan artefacts.

## Historical Tamil glyph rule — mandatory

For every body page inspect the complete glyph at enlarged/native resolution. Explicitly consider at minimum:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Before deciding a difficult reading:

- inspect the complete glyph cluster at high/native resolution;
- consider historical typeforms and faint vowel signs;
- compare same-edition forms when useful;
- require positive pixel evidence;
- never global-replace;
- preserve source oddities when actually printed;
- leave genuine uncertainty `needs-review` rather than guessing.

## Exact next activity

Process **scans 18–22 only**, completing Chapter 2 immediately before scan 23 / Chapter 3.

For each scan:

1. inspect the whole page and enlarged difficult clusters;
2. transcribe printed Tamil source-faithfully;
3. record the visible printed page number individually — expected from direct prior visual check: scans 18–22 = printed **17–21**, but still confirm from the scan;
4. run historical-glyph pre-correction checks;
5. preserve page boundaries and cross-page continuity;
6. keep later pen/pencil/handwriting outside canonical text;
7. create `works/vellikkizhamai/pages/0018-...md` through `0022-...md` using the repository's existing naming/front-matter pattern;
8. update `works/vellikkizhamai/indexes/page-map.md`, `audit.md`, work README, root README, this handover, and the next-chat prompt if the next checkpoint changes;
9. commit the batch narrowly, suggested message: **`Transcribe வெள்ளிக்கிழமை scans 18-22`**;
10. verify live `main` after the ref update.

Stop before scan 23 unless explicitly instructed farther.

---

## Completed work — பெரிய இடத்துப் பெண்

Completed with 49/49 source-comparison coverage, assembled Tamil PASSED, English VERIFIED, and RELEASE-READY WITH CANONICAL-TAMIL VERIFICATION QUALIFICATION. Canonical freeze remains 0 verified / 49 `needs-review`.

## Completed work — புதையல்

448/448 canonical records; 446 completed; scans 223–224 remain `needs-review` because of physical loss; English VERIFIED; release-ready with qualification.

## Completed work — பலிபீடம் நோக்கி

Tamil 34/34 verified; assembled Tamil PASSED; English VERIFIED; archival package RELEASE-READY.
