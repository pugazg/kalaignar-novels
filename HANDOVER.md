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
- SHA-256: **PENDING**
- source PDF committed: **No**
- source format: **image-only**

## Durable state

- source intake: **REGISTERED / IN PROGRESS**;
- front matter scans **1–4: VERIFIED**;
- scans **5–9 T1/T2/T3: COMPLETE / PASS — 5/5 VERIFIED**;
- scans **10–14 T1/T2/T3: COMPLETE / PASS — 5/5 VERIFIED**;
- scans **10–14 T2 corrections: 2**;
- scans **10–14 T3 corrections: 3**;
- scans **10–14 unresolved historical/source-form readings: 0**;
- visible printed pages: **scan10=8, scan11=9, scan12=10, scan13=11, scan14=—**;
- scan14 centered **1** is a chapter number, not a printed page number;
- terminal mapping based on the truncated 150-page parser view: **INVALIDATED**;
- terminal boundary: **DEFERRED / UNKNOWN**;
- assembled Tamil / English: **BLOCKED**.

## Corrections — scans 10–14

T2:

- scan12 — `சிறிதுமில்லாதான்` → `சிறிதுமில்லைதான்`;
- scan14 — `வேய்ங்குழலில்` → `வேய்குழலில்`.

T3:

- scan10 — `அவர்களே வீட்டுக்குள் ஓடச் செய்யும்!` → `அவர்களை வீட்டுக்குள் ஓடச் செய்யும்!`;
- scan12 — `எவ்வளவு அமைதியாக யார் யாருக்கும் தெரியாமல்` → `எவ்வளவு அமைதியாக யாருக்கும் தெரியாமல்`;
- scan12 — `கதிரவன் நீராவியாக்குவது,` → `கதிரவன் நீராவியாக்குவதும்,`.

Source-specific forms retained after T2/T3 include `வாதீன`, `அவளத் தேவதையின்`, `அடி யெடுத்து`, `கண்ட தில்லை`, `இல்லை யெனப்`, `ஒரு பைத்தியத்தை மகனைத்`, `கண்டு பிடித்தான பிறகு`, and `செய்கின்றன வென்று`.

## Structural observations

- scan10 begins `குழல்`, physically continuing scan9 terminal `புல்லாங்`;
- scan12 ends `எடுப்பார்`; scan13 begins `கைப்பிள்ளை!`;
- scan13 ends `போவர்` without added punctuation;
- scan14 begins the main chapter layer with large `சுருளிமலை` and chapter number **1**;
- later blue/purple annotations on scans11 and 14 remain excluded;
- scan15 has **not** been opened or processed.

## Exact next activity

Process **Tamil T1 scans 15–19 only**.

Requirements:

1. attached PDF/source pixels are controlling;
2. direct visual transcription only;
3. no external transcription and no OCR authority;
4. record only directly visible printed-page numbers;
5. preserve source spelling, punctuation, paragraphing and historical Tamil glyph identity;
6. create five canonical page records with `status: needs-review`;
7. update page map, work README, audit, handover and next-chat prompt;
8. commit and **stop before scan20**;
9. terminal/full-198-page reconciliation remains deferred.

Source PDF must not be committed.
