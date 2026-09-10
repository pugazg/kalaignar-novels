# Next Chat Prompt — அரும்பு / scan-17 Section 16 corrective re-open

Continue in `pugazg/kalaignar-novels`, branch `main`, active source `collections/arumbu-1978/`, active work `works/arumbu/`. **LIVE MAIN IS AUTHORITATIVE.**

## Controlling source

`TVA_BOK_0064361_அரும்பு.pdf`

- SHA-256 `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`
- **117,270,339 bytes**
- **92 physical scans**
- image-only
- தமிழ்க்கனி பதிப்பகம், சென்னை-28
- முதற் பதிப்பு 1978
- source PDF must **not** be committed.

## Durable compilation structure

- scans 1–5 — collection front matter;
- scans 6–23 — `அரும்பு` — **TAMIL / ASSEMBLED TAMIL PASSED; SECTION 17 NOT READY — corrective English re-open active**;
- scans 24–48 — `சாரப்பள்ளம் சாமுண்டி` — queued;
- scans 49–74 — `பெரிய இடத்துப் பெண்` — additional witness only;
- scans 75–90 — `நடுத்தெரு நாராயணி` — queued;
- scans 91–92 — publisher catalogue/back cover.

## Mandatory startup

Read before changing anything:

1. `NOVEL_PROCESSING_GUIDE.md`, especially Sections 15–17;
2. `HANDOVER.md`;
3. `works/arumbu/README.md`;
4. `works/arumbu/audit.md`;
5. `works/arumbu/indexes/page-map.md`;
6. `works/arumbu/translations/en/README.md`;
7. `works/arumbu/translations/en/PROGRESS.md`;
8. `works/arumbu/translations/en/GLOSSARY.md`;
9. `works/arumbu/translations/en/TRANSLATION_REVIEW.md`;
10. `works/arumbu/translations/en/RELEASE_REPORT.md`;
11. canonical `works/arumbu/pages/0017-arumbu-13.md`;
12. English `works/arumbu/translations/en/sections/01-arumbu.md` around scan 17.

## Durable Tamil state

- canonical Tamil records: **18 / 18 VERIFIED**;
- T1/T2/T3: **PASS / COMPLETE**;
- whole-work Tamil audit: **PASS / COMPLETE**;
- assembled Tamil: **1 / 1 PASSED**;
- canonical Tamil must remain unchanged during this corrective checkpoint.

## Release-preflight blocker

Section 17 found a concrete mismatch missed by the earlier Section 16 review.

Canonical scan 17 / printed page 13:

`“எனக்குப் பொய் அம்மா வேணும்! நிஜ அம்மாதான் வேணும்!”`

Current English:

`“I don't want a fake Amma! I want my real Amma!”`

The source has affirmative **`வேணும்`**; the English inserts an unprinted negative **`don't`**. Direct scan re-inspection supports the canonical affirmative reading. Do not infer or restore `வேணாம்` from context.

## Exact next activity — corrective checkpoint only

1. Correct only the affected scan-17 English sentence so it preserves the source-confirmed affirmative wording. A source-bound rendering should retain the strangeness rather than normalize it; e.g. **`I want a fake Amma! It's my real Amma I want!`**.
2. Add a concise provenance comment beside the sentence documenting that affirmative `வேணும்` is source-confirmed and intentionally not normalized.
3. Update `GLOSSARY.md` with this protected source oddity.
4. Update `TRANSLATION_REVIEW.md` to record the release-preflight correction and recheck; previous Section 16 correction count must no longer remain stale.
5. Recheck the full scan-17 paragraph plus established 16→17 and 17→18 joins against canonical Tamil.
6. If PASS, restore whole-work English **VERIFIED** with **0 unresolved translation items**.
7. Synchronize `PROGRESS.md`, English/work/audit/root controls and `RELEASE_REPORT.md` only as needed to say the corrective checkpoint passed but **Section 17 still requires rerun**.
8. Commit and stop.

Do **not** rerun Section 17 release-readiness in the same corrective checkpoint. Do **not** start `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison.
