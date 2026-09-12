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
- source extent: **198 pages — user/source confirmed**
- current ChatGPT Files parser exposure: **150 pages only / truncated representation**
- pagination relationship: **UNRESOLVED in current parser view**
- SHA-256: **PENDING — hashing runtime unavailable during intake**
- source PDF committed: **No**
- source format: **image-only**

## Durable state

- source intake: **REGISTERED / IN PROGRESS**;
- front matter scans **1–4: VERIFIED / page records created**;
- T1 scans **5–9: COMPLETE / PASS — 5/5 canonical page records created as `needs-review`**;
- visible printed-page mapping for this batch: **scan5 = unnumbered; scan6 = 4; scan7 = 5; scan8 = 6; scan9 = 7**;
- page map: **current parser-visible pages 1–150 only; incomplete relative to 198-page source**;
- prior scan→printed-page terminal mapping: **INVALIDATED**;
- T2 historical-glyph review: **NEXT — scans 5–9 only**;
- T3 final source-fidelity review: **PENDING**;
- terminal boundary: **UNKNOWN / full-source re-audit required later**;
- assembled Tamil / English: **BLOCKED**.

Mandatory historical families:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

## T1 source-boundary observations

- scan 5 visibly carries the heading `அறிமுகம்` and no printed page number;
- scan 6 ends `வாய்ப்பாடு`; scan 7 begins `பாடத்தின் “கோரஸ்”!!`;
- scan 8 ends `யார் வீட்டில் உடல் நலிவு என்றாலும்`; scan 9 continues `பூஞ்சோலை அங்கிருப்பாள்.`;
- scan 9 contains later blue/purple underlining/bracket marks that are not canonical printed prose;
- scan 9 ends with the incomplete source fragment `புல்லாங்`;
- scan 10 was not used during this T1 batch.

## User-supplied project context

The supplied synopsis mentions folk arts such as கரகாட்டம், தீச்சட்டி எடுத்தல் and மயிலாட்டம், superstition, and the characters பூஞ்சோலை, பொன்மணி, கற்பூரம் and மைனா. Keep that synopsis separate from canonical source prose unless the controlling scan itself contains it.

## Exact next activity

Perform **Tamil T2 independent historical-glyph review for scans 5–9 only**.

Requirements:

1. attached source pixels are controlling;
2. re-read all five scans independently rather than trusting T1;
3. explicitly check all 13 known historical families occurrence-by-occurrence;
4. no global replacement, OCR authority, contextual correction, or modernization;
5. record each actual correction in page notes/audit;
6. unresolved clusters remain `needs-review`;
7. do not promote pages to `verified` during T2 — T3 remains separate;
8. update `T1_BATCH_005_009.md`, page map, README, audit and handover;
9. commit and **stop before scan10**;
10. terminal/full-198-page reconciliation remains deferred.

Source PDF must not be committed.
