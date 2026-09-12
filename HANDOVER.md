# Project Handover — Kalaignar Novels Archive

## Repository

- Repository: `pugazg/kalaignar-novels`
- Branch: `main`
- **LIVE MAIN IS AUTHORITATIVE.**
- Active work: **`works/surulimalai/`**

## Active source — சுருளிமலை

Controlling source: `TVA_BOK_0064107_சுருளிமலை_1968 2.pdf`

- title: **சுருளிமலை**
- author: **கலைஞர் மு. கருணாநிதி**
- publisher: **திராவிடப்பண்ணை**
- edition: **இரண்டாம் பதிப்பு — 1968**
- source size: **268,529,598 bytes**
- PDF scan images: **150**
- user-confirmed printed/book extent: **198 pages**
- pagination relationship: **PARTIALLY VERIFIED — scans140–149 = printed189–198; intermediate mapping pending T1**
- SHA-256: **PENDING — hashing runtime unavailable during intake**
- source PDF committed: **No**
- source format: **image-only**

## Durable intake state

- no pre-existing `surulimalai` work directory was present;
- source intake: **REGISTERED / IN PROGRESS**;
- front matter scans **1–4: VERIFIED / page records created**;
- scan **5: body opening confirmed; not yet transcribed**;
- page map: **150 / 150 PDF scan images registered at intake level**;
- printed/book extent: **198 pages (user-confirmed)**;
- scan→printed-page mapping: **terminal region VERIFIED — scans140–149 = printed189–198**;
- body T1: **NOT STARTED**;
- terminal boundary: **PASS / COMPLETE — scan149 = printed198 / ending; scan150 = back cover**;
- historical-glyph review: **NOT STARTED**;
- assembled Tamil / English: **BLOCKED**.

Mandatory historical families:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

## User-supplied project context

The supplied synopsis mentions folk arts such as கரகாட்டம், தீச்சட்டி எடுத்தல் and மயிலாட்டம், superstition, and the characters பூஞ்சோலை, பொன்மணி, கற்பூரம் and மைனா. Keep that synopsis separate from canonical source prose unless the controlling scan itself contains it.

## Exact next activity

Process **Tamil T1 scans 5–9 only**.

Requirements:

1. visually transcribe each scan from the source pixels; no OCR guesswork;
2. record the visible printed page number(s) for each scan, including any two-page spread exactly as seen;
3. preserve punctuation, spelling, paragraphing and historical Tamil glyph forms;
4. explicitly audit the historical families `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
5. do not normalize copy-specific marks into source text;
6. create/update canonical page records and page map;
7. commit immediately after scans 5–9 and stop before scan10;
8. SHA-256 remains an open provenance item if runtime hashing is still unavailable;
9. do not commit the PDF and do not reopen closed prior works.

Terminal audit record: `works/surulimalai/TERMINAL_BOUNDARY_AUDIT.md`.
