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
- source extent: **198 pages — user/source confirmed**
- current Files parser exposure: **150 pages only / truncated representation**
- source PDF committed: **No**

## Durable state

- scans **5–14 T1/T2/T3: VERIFIED**;
- scans **15–19 T1: COMPLETE / PASS — 5/5**;
- scans **15–19 T2: COMPLETE / PASS — 5/5**;
- scans **15–19 canonical records: 5/5 `needs-review` pending T3**;
- scans **15–19 T2 corrections: 5**;
- unresolved historical/source-form readings after T2: **0**;
- visible printed pages: **13–17**;
- scan20 has not been opened;
- terminal/full-198-page issue remains **DEFERRED**.

## T2 correction ledger — scans 15–19

- scan15 — `தவறுமல்` → **`தவறாமல்`** — historical `றா`;
- scan16 — `எதுவுமே யில்ல` → **`எதுவுமே யில்லை`** — historical `லை`;
- scan16 — `யாருமில்லதான்` → **`யாருமில்லைதான்`** — historical `லை`;
- scan18 — `வேணுங்கிறன்` → **`வேணுங்கிறான்`** — historical `றா`;
- scan19 — `என்னைத் அம்மமேலே` → **`என்னத்த அம்மமேலே`** — direct source-form correction.

Source-specific unusual forms retained after direct re-read include the scan15 quotation, `ஆந்தைப்பாடினுள்`, `வயப்படுத்தும்`, `வாண்ணே`, `காணேம்`, `அதேயேன்`, `இன்னைக் குத்தான்`, `கனியா குறிச்சி`, `தொடர்ந்தாப் போலே`, `எதிர்த்தாப்போல`, `இல்லேன்னு`, and `‘களுக்’ குன்னு`.

## Exact next activity

Perform **Tamil T3 final source-fidelity review for scans 15–19 only**.

Requirements:

1. attached source pixels only;
2. compare every complete canonical page against its scan;
3. check omissions, duplication, punctuation, paragraphing, printed page numbers and cross-page continuity;
4. retain T2 decisions unless direct source evidence requires correction;
5. record each T3 correction explicitly;
6. promote pages to `verified` only after they fully pass T3;
7. update `T1_BATCH_015_019.md`, page map, README, audit, handover and next-chat prompt;
8. commit and **stop before scan20**;
9. terminal/full-198-page reconciliation remains deferred.
