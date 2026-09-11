# Release Readiness Report — சாரப்பள்ளம் சாமுண்டி

Status: **PASS / COMPLETE — RELEASE-READY / CLOSED**.

Working English title: **Sarapallam Samundi**.

> This is an archival/editorial release-readiness verdict only. It is **not** a copyright, licensing, commercial-republication or public-domain determination.

## 1. Work identity

- Tamil title: **சாரப்பள்ளம் சாமுண்டி**
- author: **கலைஞர் மு. கருணாநிதி**
- repository work path: `works/sarapallam-samundi/`
- source component: **1978 அரும்பு four-story compilation**
- component physical span: **scans 24–48 / 25 scans**
- source-backed structure: **one continuous work / no source-backed chapter divisions**

Identity check: **PASS**.

## 2. Source edition identity

Controlling source:

- filename: `TVA_BOK_0064361_அரும்பு.pdf`
- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- compilation extent: **92 physical scans**
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- edition: **முதற் பதிப்பு — 1978**
- work span: **scans 24–48**

The source PDF is external controlling evidence and is not part of the repository tree.

Source identity check: **PASS**.

## 3. Tamil page inventory

Canonical Tamil inventory:

- canonical page records: **25 / 25**
- physical coverage: **scans 24–48**
- canonical verification: **25 / 25 VERIFIED**
- T1/T2/T3: **PASS / COMPLETE**
- unresolved historical glyphs: **0**
- unresolved source readings: **0**
- whole-work residual source corrections: **1**

Residual source correction retained:

- scan 29 / printed 26: `வாயாலிருந்துவிட்டான்` → **`வாளாயிருந்துவிட்டான்`**

Printed-page behaviour remains source-faithful:

- scan 24 — unnumbered title opening;
- scans 25–27 — printed 21–23;
- scan 28 — unnumbered landscape illustration spread;
- scans 29–48 — printed 26–45;
- no printed 24/25 is invented.

Tamil page inventory: **PASS**.

## 4. Tamil assembled-section inventory

Reader-facing Tamil section:

- `sections/01-sarapallam-samundi.md`
- source span: **24–48**
- state: **VERIFIED / PASSED**
- section count: **1 / 1**
- provenance markers: **25 / 25**
- verified joins: **PASS**
- scan-28 illustration exclusion: **PASS**
- scan-48 narrative / source-note distinction: **PASS**

Navigation record:

- `sections/README.md`

Tamil assembled-section inventory: **PASS**.

## 5. English section inventory

English reading section:

- `translations/en/sections/01-sarapallam-samundi.md`
- working title: **Sarapallam Samundi**
- source span: **24–48**
- source markers: **25 / 25**
- state: **VERIFIED**
- English section count: **1 / 1**

Controlled batch history:

- Batch 1 — scans 24–28 — **REVIEWED / COMPLETE**
- Batch 2 — scans 29–33 — **REVIEWED / COMPLETE**
- Batch 3 — scans 34–38 — **REVIEWED / COMPLETE**
- Batch 4 — scans 39–43 — **REVIEWED / COMPLETE**
- Batch 5 — scans 44–48 — **REVIEWED / COMPLETE**

English section inventory: **PASS**.

## 6. Tamil audit result

`FULL_TAMIL_SOURCE_AUDIT.md` and `audit.md` establish:

- whole-work Tamil audit: **PASS / COMPLETE**
- physical source order: **PASS**
- canonical record completeness: **PASS**
- page-boundary continuity: **PASS**
- source oddity handling: **PASS**
- unresolved items: **0**

Tamil audit result: **PASS**.

## 7. Bilingual review result

`translations/en/TRANSLATION_REVIEW.md` is:

**PASS / COMPLETE — WHOLE-WORK ENGLISH VERIFIED**.

The final bilingual review confirms:

- complete 25/25 coverage and order;
- no duplicate span;
- material omissions: **0**;
- source-like additions: **0**;
- unresolved translation items: **0**;
- speaker attribution: **PASS**;
- agency / responsibility: **PASS**;
- recurring names / titles / terminology: **PASS**;
- political / religious / social rhetorical force: **PASS**;
- dance / temple terminology: **PASS**;
- cross-page joins: **PASS**;
- scan-28 illustration exclusion: **PASS**;
- scan-48 narrative / source-note separation: **PASS**;
- one-section identity / no invented chapters: **PASS**.

Bilingual review result: **PASS**.

## 8. Reader-facing navigation check

Checked reader-facing paths and control records:

Tamil:

1. work entry — `README.md`;
2. Tamil navigation — `sections/README.md`;
3. Tamil reader — `sections/01-sarapallam-samundi.md`.

English:

1. English control/navigation — `translations/en/README.md`;
2. English progress — `translations/en/PROGRESS.md`;
3. English reader — `translations/en/sections/01-sarapallam-samundi.md`;
4. whole-work review — `translations/en/TRANSLATION_REVIEW.md`;
5. this release report — `translations/en/RELEASE_REPORT.md`.

Root and collection navigation are synchronized in:

- repository `README.md`;
- `collections/arumbu-1978/README.md`;
- `collections/arumbu-1978/indexes/work-map.md`;
- root `HANDOVER.md`.

One stale pre-English line in `sections/README.md` was corrected during this release pass so it no longer claims the English plan is still the next gate.

Reader-facing navigation: **PASS**.

## 9. Authority hierarchy

Release authority remains:

1. controlling source scan;
2. canonical verified Tamil `pages/`;
3. PASSED assembled Tamil `sections/01-sarapallam-samundi.md`;
4. source audits / page map / metadata;
5. VERIFIED English translation;
6. release/reporting controls.

No release document overrides the controlling source or canonical Tamil.

Authority hierarchy: **PASS**.

## 10. Structural identity

Confirmed:

- the work remains one continuous source-backed section;
- batch boundaries were workflow boundaries only;
- no invented chapter divisions exist;
- scan 28 illustration is not converted into prose;
- scan 48 fictional ending and source-printed `குறிப்பு :` remain separate;
- no text from the separate `பெரிய இடத்துப் பெண்` 1978 witness span 49–74 is incorporated.

Structural identity: **PASS**.

## 11. Documented source oddities

The release pass confirms that difficult forms remain explicitly documented in `translations/en/GLOSSARY.md`, including:

- scan 29 `வாளாயிருந்துவிட்டான்`;
- scan 34 `நிழலில் தானம்மா`, `மன்னர் மன்னு`;
- scan 36 `தொடங்கப் பெறுமைக்கு`;
- scan 41 `நீர்த்திவலை`;
- scan 42 `சிற்பங்களை யல்லவா`, `ஏதோ ஓர் ஏக்கத்தை ஏற்பட்டது`;
- scan 43 `தீண்டாக்குவானேன்`;
- scan 46 `எண்பத்தொரு சிலைகளும்`, `மானழியது`, `கைநெருப்பு`;
- scan 47 `ஒரு சிலருன்`, `நிறைவேற்று வதற்கு`.

These are not silently normalized in canonical Tamil.

Documented source-oddity check: **PASS**.

## 12. Canonical Tamil mutation check

No file under `works/sarapallam-samundi/pages/` is changed by this Section 17 release checkpoint.

Canonical Tamil changes during release pass: **0**.

Result: **PASS**.

## 13. Source-PDF repository check

A recursive live-`main` tree check at the start of this release pass found:

- committed `.pdf` files in the repository tree: **0**;
- committed path matching the controlling filename `TVA_BOK_0064361_அரும்பு.pdf`: **0**.

Source PDF exclusion: **PASS**.

## 14. Non-blocking editorial limitations

The following are documented but do not block archival/editorial release readiness:

- the working English title is intentionally transliterative rather than interpretive;
- historical measures, offices, ritual terms and named dance forms retain conservative source-bound handling;
- difficult Tamil source forms are preserved/documented rather than silently modernized;
- scan 28's illustration is excluded from prose by design;
- the source PDF remains external to the repository;
- this release verdict does not determine copyright, licensing, public-domain status, distribution rights or commercial republication rights.

No unresolved textual or structural blocker remains.

## 15. Final verdict

Tamil canonical layer: **25 / 25 VERIFIED**.  
Tamil whole-work audit: **PASS / COMPLETE**.  
Assembled Tamil: **PASS / COMPLETE — 1 / 1 section**.  
English coverage: **25 / 25 scans**.  
Whole-work English: **VERIFIED**.  
Section 16 bilingual review: **PASS / COMPLETE**.  
Section 17 release-readiness: **PASS / COMPLETE**.  
Canonical Tamil changes during release pass: **0**.  
Source PDF committed: **No**.

# VERDICT: RELEASE-READY / CLOSED

This verdict is archival/editorial only. It does not by itself establish legal permission to reproduce, distribute, license or commercially republish the work.
