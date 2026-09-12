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
- front matter scans **1–4: VERIFIED**;
- T1 scans **5–9: COMPLETE / PASS — 5/5**;
- T2 historical-glyph review scans **5–9: COMPLETE / PASS — 5/5**;
- canonical page status scans 5–9: **5/5 `needs-review` pending T3**;
- T2 corrections: **1** — scan9 `கிட்டவில்ல` → `கிட்டவில்லை` (historical `லை`);
- unresolved historical glyphs after T2: **0**;
- visible printed-page mapping: **scan5 = unnumbered; scan6 = 4; scan7 = 5; scan8 = 6; scan9 = 7**;
- page map: **current parser-visible pages 1–150 only; incomplete relative to 198-page source**;
- prior scan→printed-page terminal mapping: **INVALIDATED**;
- T3 final source-fidelity review: **NEXT — scans 5–9 only**;
- terminal boundary: **UNKNOWN / full-source re-audit required later**;
- assembled Tamil / English: **BLOCKED**.

Mandatory historical families checked in T2:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

## T2 decisions

- scan 7 — `மட்டுந்தானா`: historical `னா` positively confirmed;
- scan 8 — `வீட்டென்றால்`: historical `றா` identity in `என்றால்` confirmed;
- scan 8 — `பதினொறு`: retained exactly as printed; no modernization;
- scan 9 — `கிட்டவில்ல` corrected to `கிட்டவில்லை` from enlarged direct pixels and same-edition `லை` evidence;
- scan 9 — `பொன்னாலன்றே` and `அதுலைதான்` retained exactly as source-supported forms.

## Source-boundary observations

- scan 5 visibly carries `அறிமுகம்` and no printed page number;
- scan 6 ends `வாய்ப்பாடு`; scan 7 begins `பாடத்தின் “கோரஸ்”!!`;
- scan 8 ends `யார் வீட்டில் உடல் நலிவு என்றாலும்`; scan 9 continues `பூஞ்சோலை அங்கிருப்பாள்.`;
- scan 9 later blue/purple marks are non-printed annotations and remain excluded;
- scan 9 ends `புல்லாங்`;
- scan 10 has not been used.

## Exact next activity

Perform **Tamil T3 final source-fidelity review for scans 5–9 only**.

Requirements:

1. attached source pixels are controlling;
2. compare every canonical page against the complete scan again;
3. check omissions, duplication, punctuation, paragraph boundaries, visible page numbering, non-body marks and cross-page continuity;
4. retain T2 historical-glyph decisions unless new positive source evidence overturns them;
5. record every T3 correction explicitly;
6. only pages that fully pass T3 may move from `needs-review` to `verified`;
7. update `T1_BATCH_005_009.md`, page map, README, audit, handover and next-chat prompt;
8. commit and **stop before scan10**;
9. terminal/full-198-page reconciliation remains deferred.

Source PDF must not be committed.
