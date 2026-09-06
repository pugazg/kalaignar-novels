# Next Chat Prompt — வெள்ளிக்கிழமை

Continue the Kalaignar Novels / Story Books archival project directly in:

`pugazg/kalaignar-novels`

Branch: `main`  
Active work: `works/vellikkizhamai/` — **வெள்ளிக்கிழமை**

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve newer durable work. Do not reset or repeat completed pages merely because this copied prompt contains an older checkpoint.

Last confirmed live checkpoint when this prompt was prepared:

`708ffce5ec4304ed19afcb44ccd6908f8ea7a16e` — **`Transcribe வெள்ளிக்கிழமை scans 13-17`**

## CONTROLLING SOURCE MUST BE ATTACHED AGAIN

Before scan-level visual work, attach/resolve:

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf`

Recorded source identity:

- SHA-256: `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`;
- file size: **251,126,214 bytes**;
- recorded actual scans: **179**;
- image-only / no parsed text layer;
- title: **வெள்ளிக்கிழமை**;
- author as printed: **மு. கருணாநிதி**;
- publisher: **திராவிடப்பண்ணை**;
- edition: **இரண்டாம் பதிப்பு: 1968**;
- price: **ரூ. 2-50**;
- printer: **சக்திவேல் பிரஸ், திருச்சிராப்பள்ளி-2.**

Do **not** commit the PDF.

## Mandatory startup

Read completely before any source-dependent change:

1. `NOVEL_PROCESSING_GUIDE.md`
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
3. root `README.md`
4. root `HANDOVER.md`
5. this `NEXT_NOVEL_CHAT_PROMPT.md`
6. `works/vellikkizhamai/README.md`
7. `works/vellikkizhamai/metadata/source.md`
8. `works/vellikkizhamai/indexes/page-map.md`
9. `works/vellikkizhamai/audit.md`
10. existing `works/vellikkizhamai/pages/*.md`

## Current durable state

- page manifest: **179 / 179 scans represented**;
- canonical page records: **17 / 179**;
- scans 1–3 front matter: **verified**;
- scans 4–12 / Chapter 1: **verified / complete**;
- scans 13–17 / Chapter 2 opening: **verified**;
- scan 13 is source-printed Chapter 2 opening;
- scan 23 is directly confirmed Chapter 3 opening;
- printed mapping through scan 17: scan 4 and scan 9 unnumbered; scans 5–8 = printed **4–7**; scans 10–17 = printed **9–16**;
- Tamil full-source audit: **not started**;
- assembled Tamil: **not started**;
- English translation: **blocked until Tamil gate passes**.

## IMPORTANT — previous-chat work on scans 18–22 is NOT durable

The previous chat opened scans **18–22** and confirmed visible printed pages **17–21**. These pages continue and complete Chapter 2 immediately before scan 23 / Chapter 3.

But no canonical page files for scans 18–22 were committed, and no verified durable transcription exists for them.

Therefore:

- do not assume any previous in-chat draft is authoritative;
- re-open the actual source scans;
- re-check every difficult word/glyph from source pixels;
- only then create and mark canonical records complete.

Do **not** claim progress beyond **17/179** until a new commit actually lands on live `main`.

## Already completed source-sensitive decisions

Do not reopen these without genuine contrary source evidence:

- scan 8: **`களைத்துத் தூங்கிவிட்டால்`** — historical `ளை` resolved from source pixels/same-edition comparison;
- scan 9: source-specific **`குழப்பட்டு`** retained;
- scan 12: source-specific **`அந்தப் பருக்கூட்டமே`** retained;
- scans 10–12 Tiruppavai text transcribed from this edition, not substituted from an external canonical version;
- scan 13: source-specific **`எடுபிடி ஆள் அப்புகள்`** retained;
- scan 16: source-specific **`இன்பபுரி வெண்புருக்கள்`** retained;
- scan 17: colloquial **`வேலையில்ல`** and **`நல்லதாப் போச்சு`** retained.

Known continuity:

- scan 14 `அதிலே` → scan 15 `வரும் அர்ச்சுனன்...`;
- scan 16 `எண்ணும்` → scan 17 `போது—`;
- scan 17 ends **`“சுசீலா! நீ?”`**; Suseela's reply begins on scan 18.

## Source authority

Authority order:

**controlling source scan → canonical `pages/` → later assembled Tamil → later English**

OCR, Wikisource, web text, or machine extraction may be used only as a secondary reading aid. Never let them override the supplied source scan. Every canonical reading must be supported by the source pixels.

Do not silently modernize/correct source spelling, wording, grammar, punctuation, vocabulary, names, dialogue, or structure.

Separate printed text from later underlining, ticks, handwriting, stamps, bleed-through, and scan artefacts.

## Historical Tamil glyph rule — mandatory

Every body page must explicitly check at minimum:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Before deciding a difficult reading:

- inspect the complete glyph cluster at high/native resolution;
- consider historical typeforms and faint vowel signs;
- compare same-edition forms when useful;
- require positive pixel evidence;
- never global-replace;
- preserve actual source oddities;
- leave genuine uncertainty `needs-review` instead of guessing.

## Exact next activity

Process **scans 18–22 only**, completing Chapter 2 immediately before scan 23 / Chapter 3.

For each scan:

1. inspect the whole page and enlarged difficult clusters;
2. transcribe printed Tamil source-faithfully;
3. confirm visible printed page number individually — previous direct visual check indicates scans 18–22 = printed **17–21**;
4. run historical-glyph pre-correction checks;
5. preserve source page boundaries and cross-page continuity;
6. exclude later pen/pencil/handwriting from canonical printed text;
7. create canonical page records following the existing filename/front-matter pattern;
8. update `works/vellikkizhamai/indexes/page-map.md`, `audit.md`, work README, root README, `HANDOVER.md`, and this prompt for the next checkpoint;
9. commit narrowly, suggested message: **`Transcribe வெள்ளிக்கிழமை scans 18-22`**;
10. verify live `main` after commit/ref update.

Stop before scan 23 unless explicitly instructed farther.

Do not start English. Do not jump ahead to assembled Tamil. Do not reopen completed prior novels.
