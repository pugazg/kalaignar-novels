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
- SHA-256: **PENDING**
- source PDF committed: **No**
- source format: **image-only**

## Durable state

- source intake: **REGISTERED / IN PROGRESS**;
- front matter scans **1–4: VERIFIED**;
- scans **5–9 T1: COMPLETE / PASS — 5/5**;
- scans **5–9 T2: COMPLETE / PASS — 5/5**;
- scans **5–9 T3: COMPLETE / PASS — 5/5**;
- scans **5–9 canonical page records: 5/5 VERIFIED**;
- T2 corrections: **1**;
- T3 corrections: **6**;
- unresolved historical glyphs: **0**;
- visible printed-page mapping: **scan5 = unnumbered; scan6 = 4; scan7 = 5; scan8 = 6; scan9 = 7**;
- page map: **current parser-visible pages 1–150 only; incomplete relative to 198-page source**;
- prior scan→printed-page terminal mapping: **INVALIDATED**;
- terminal boundary: **UNKNOWN / full-source re-audit required later**;
- assembled Tamil / English: **BLOCKED**.

## Durable correction ledger — scans 5–9

T2:

- scan9 — `கிட்டவில்ல` → `கிட்டவில்லை` — historical `லை`.

T3:

- scan5 — `அவள் ஊரார் அறிவர்.` → `அவளை ஊரார் அறிவர்.`;
- scan6 — `வாசகர்கள் இழுத்துச்` → `வாசகர்களை இழுத்துச்`;
- scan6 — `அறிவிக்கப்பட வேண்டியதில்லை` → source-printed `அறிவிக்கப்பட்ட வேண்டியதில்லை`;
- scan8 — `தோத்திரித்தேன்` → source-printed `தோத்தரித்தேன்`;
- scan8 — `வேதனைகளானாள்` → source-printed `வேதனைக்கலமானாள்`;
- scan9 — `கவலையால்` → source-printed `கவலியால்`.

Source-specific unusual forms are preserved without grammar correction or modernization.

## Source-boundary observations

- scan5 carries `அறிமுகம்` and no printed page number;
- scan6 ends `வாய்ப்பாடு`; scan7 begins `பாடத்தின் “கோரஸ்”!!`;
- scan8 ends `யார் வீட்டில் உடல் நலிவு என்றாலும்`; scan9 continues `பூஞ்சோலை அங்கிருப்பாள்.`;
- scan9 later blue/purple annotations remain excluded from canonical prose;
- scan9 ends `புல்லாங்`;
- scan10 has not yet been processed.

## Exact next activity

Process **Tamil T1 scans 10–14 only**.

Requirements:

1. attached PDF/source pixels are controlling;
2. direct visual transcription only;
3. no external transcription and no OCR authority;
4. record only directly visible printed-page numbers;
5. preserve source spelling, punctuation, paragraphing and historical Tamil glyph identity;
6. create five canonical page records with `status: needs-review`;
7. update page map, work README, audit, handover and next-chat prompt;
8. commit and **stop before scan15**;
9. terminal/full-198-page reconciliation remains deferred.

Source PDF must not be committed.
