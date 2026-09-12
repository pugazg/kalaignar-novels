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

- scans **5–19 T1/T2/T3: VERIFIED**;
- scans **20–24 T1: COMPLETE / PASS — 5/5**;
- scans **20–24 T2: COMPLETE / PASS — 5/5**;
- scans **20–24 canonical records: 5/5 `needs-review` pending T3**;
- scans **20–24 T2 corrections: 0**;
- unresolved historical/source-form readings: **0**;
- visible printed pages: **18, 19, 20, 21, 22**;
- scan22 contains a centered chapter **2** after two closing paragraphs from the preceding scene;
- scan25 has not been opened;
- terminal/full-198-page issue remains **DEFERRED**.

## T2 decisions — scans 20–24

No text correction was required.

Confirmed directly from source pixels:

- scan20 — `வேலையவிடப்`, `நாழி`, `பிள்ளை யாண்டான்`, `விட்டகன்று`, `அருமருந்தன்ன`; unusual nested quotation retained;
- scan21 — `சும்மாகிட`, `தோள்மாத்திக்குவாரு`, `பொத்துன்னு`, `வச்சுருக்காரு`, `தொல்லையில்லாம`, `கயிற்றுச் சுருக்கை`; isolated bottom-left `2` remains non-body;
- scan22 — chapter **2** heading plus `அறிமுகமானவளாய்த்தானிருக்க`, `இருக்குமென்பதற்கு`, `தீச்சட்டியேந்திக்`, `கர கரவெனப்`, `வாலைக் குமரியை`;
- scan23 — `கற்றவித்தையைக்`, `எப்படிப்பட்ட தென்று`, `ஊற்று வதற்கு`, `திலகங்களையிட்டு`, `நெற்றியிலே இல்ல`, `தண்ணீர் தந்த தடுமாற்றம்`, `‘அதைக்’`;
- scan24 — `கங்கணம்`, `ஜ்வாலை யெழுப்பி`, `அநாயாசமாக`, `கடைசலிட்டு`, `இருகோவைப் பழங்களாய்ப்`, both short dialogue quotations, and terminal `அதைத்`.

## Exact next activity

Perform **Tamil T3 final source-fidelity review for scans 20–24 only**.

Requirements:

1. attached PDF/source pixels only;
2. compare every complete canonical page against its scan;
3. check omissions, duplication, punctuation, paragraphing, visible page numbers, chapter-transition structure, non-body marks and cross-page continuity;
4. retain T2 decisions unless direct source evidence requires correction;
5. record each T3 correction explicitly;
6. promote pages to `verified` only after they fully pass T3;
7. update `T1_BATCH_020_024.md`, page map, README, audit, handover and next-chat prompt;
8. commit and **stop before scan25**;
9. terminal/full-198-page reconciliation remains deferred.
