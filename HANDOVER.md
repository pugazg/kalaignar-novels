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
- scans **10–14 T1: COMPLETE / PASS — 5/5**;
- scans **10–14 T2: COMPLETE / PASS — 5/5**;
- scans **10–14 canonical records: 5/5 `needs-review` pending T3**;
- scans **10–14 T2 corrections: 2**;
- scans **10–14 unresolved historical/source-form readings: 0**;
- visible printed pages: **scan10=8, scan11=9, scan12=10, scan13=11, scan14=—**;
- scan14 centered **1** is a chapter number, not a printed page number;
- terminal mapping based on the truncated 150-page parser view: **INVALIDATED**;
- terminal boundary: **DEFERRED / UNKNOWN**;
- assembled Tamil / English: **BLOCKED**.

## T2 corrections — scans 10–14

- scan12 — `சிறிதுமில்லாதான்` → **`சிறிதுமில்லைதான்`**; historical `லை` identity confirmed from same-page `இல்லை யெனப்`;
- scan14 — `வேய்ங்குழலில்` → **`வேய்குழலில்`**; enlarged source pixels show no `ங்`.

Confirmed without change:

- scan10 — `வாதீன`;
- scan11 — `அவளத் தேவதையின்`, `நினைப்புடைய இளைஞன்`;
- scan12 — `அடி யெடுத்து`, `கண்ட தில்லை`, `இல்லை யெனப்`, `பூக்கரகம்`;
- scan13 — `ஒரு பைத்தியத்தை மகனைத்`;
- scan14 — `கண்டு பிடித்தான பிறகு`, `செய்கின்றன வென்று`.

No source form above was normalized from context.

## Structural observations

- scan10 begins `குழல்`, physically continuing scan9 terminal `புல்லாங்`;
- scan12 ends `எடுப்பார்`; scan13 begins `கைப்பிள்ளை!`;
- scan13 ends `போவர்` without added punctuation;
- scan14 begins the main chapter layer with large `சுருளிமலை` and chapter number **1**;
- later blue/purple annotations on scans11 and 14 remain excluded;
- scan15 has **not** been opened or processed.

## Exact next activity

Perform **Tamil T3 final source-fidelity review for scans 10–14 only**.

Requirements:

1. attached PDF/source pixels only;
2. compare every canonical record against the complete scan;
3. check omissions, duplication, punctuation, paragraphing, visible page numbers, chapter structure, later annotations and cross-page continuity;
4. retain T2 decisions unless positive source pixels require correction;
5. record every T3 correction explicitly;
6. promote a page to `verified` only after it fully passes T3;
7. update `T1_BATCH_010_014.md`, page map, README, audit, handover and next-chat prompt;
8. commit and **stop before scan15**;
9. full-source/terminal reconciliation remains deferred.

Source PDF must not be committed.
