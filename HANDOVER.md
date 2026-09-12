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
- pagination relationship: **OPEN — counts are not assumed 1:1; no 48-page loss is asserted**
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
- scan→printed-page mapping: **OPEN**;
- body T1: **NOT STARTED**;
- terminal boundary: **OPEN — scans 145–150 require direct visible-pagination / structural audit**;
- historical-glyph review: **NOT STARTED**;
- assembled Tamil / English: **BLOCKED**.

Mandatory historical families:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

## User-supplied project context

The supplied synopsis mentions folk arts such as கரகாட்டம், தீச்சட்டி எடுத்தல் and மயிலாட்டம், superstition, and the characters பூஞ்சோலை, பொன்மணி, கற்பூரம் and மைனா. Keep that synopsis separate from canonical source prose unless the controlling scan itself contains it.

## Exact next activity

1. audit **PDF scans 145–150** directly and record the visible printed page number(s) on each scan;
2. determine whether any of those scans are two-page spreads and whether scan 150 contains the source-visible ending / printed page 198 / publisher back matter;
3. treat **150 scans** and **198 printed pages** as distinct measures — do not invent 48 missing PDF scans;
4. extend the scan→printed-page mapping backward/forward only from direct source evidence;
5. compute/record SHA-256 when the hashing runtime is available;
6. once source structure is stable, begin bounded T1 from scan 5;
7. do not commit the PDF and do not reopen closed prior works.
