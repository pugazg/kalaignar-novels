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
- physical scans: **150**
- SHA-256: **PENDING — hashing runtime unavailable during intake**
- source PDF committed: **No**
- source format: **image-only**

## Durable intake state

- no pre-existing `surulimalai` work directory was present;
- source intake: **REGISTERED / IN PROGRESS**;
- front matter scans **1–4: VERIFIED / page records created**;
- scan **5: body opening confirmed; not yet transcribed**;
- page map: **150 / 150 scans registered at intake level**;
- body T1: **NOT STARTED**;
- terminal boundary: **OPEN — scans 145–150 require visual audit**;
- historical-glyph review: **NOT STARTED**;
- assembled Tamil / English: **BLOCKED**.

Mandatory historical families:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

## User-supplied project context

The supplied synopsis mentions folk arts such as கரகாட்டம், தீச்சட்டி எடுத்தல் and மயிலாட்டம், superstition, and the characters பூஞ்சோலை, பொன்மணி, கற்பூரம் and மைனா. Keep that synopsis separate from canonical source prose unless the controlling scan itself contains it.

## Exact next activity

1. visually inspect **scans 145–150** and determine the source-visible terminal narrative/back-matter structure;
2. compute/record SHA-256 when the hashing runtime is available;
3. synchronize `metadata/source.md` and `indexes/page-map.md`;
4. only after the work span is source-confirmed, begin a small T1 body batch from scan 5;
5. do not commit the PDF and do not reopen closed prior works.
