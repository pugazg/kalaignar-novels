# Next Chat Prompt — அரும்பு / Section 17 release-readiness rerun

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

## Durable state

- `அரும்பு` scans **6–23**;
- canonical Tamil **18/18 VERIFIED**;
- T1/T2/T3 and whole-work Tamil audit **PASS / COMPLETE**;
- assembled Tamil **1/1 PASS**;
- English Batches 1–4 **REVIEWED / COMPLETE**;
- English coverage **18/18 scans**;
- Section 16 whole-work bilingual review **PASS / COMPLETE after scan-17 corrective re-open**;
- whole-work English **VERIFIED**;
- total Section-16 English-only corrections **4**;
- unresolved translation items **0**;
- canonical Tamil changes during corrective re-open **0**;
- previous Section 17 verdict **NOT READY**, but its sole fidelity blocker is now **RESOLVED**;
- formal Section 17 rerun **NEXT**.

## Corrective source decision

Canonical/source scan 17 reads:

`“எனக்குப் பொய் அம்மா வேணும்! நிஜ அம்மாதான் வேணும்!”`

The earlier English inserted `don't`. The corrected verified English is:

**“I want a fake Amma! It's my real Amma I want!”**

This intentionally preserves affirmative `வேணும்` rather than context-normalizing it to an unprinted negative. The full scan-17 paragraph and 16→17 / 17→18 joins were rechecked.

## Mandatory startup

Read:

1. `NOVEL_PROCESSING_GUIDE.md`, especially Section 17;
2. `HANDOVER.md`;
3. `works/arumbu/README.md`;
4. `works/arumbu/audit.md`;
5. `works/arumbu/indexes/page-map.md`;
6. `works/arumbu/sections/README.md`;
7. `works/arumbu/translations/en/README.md`;
8. `works/arumbu/translations/en/PROGRESS.md`;
9. `works/arumbu/translations/en/GLOSSARY.md`;
10. `works/arumbu/translations/en/TRANSLATION_REVIEW.md`;
11. `works/arumbu/translations/en/RELEASE_REPORT.md`;
12. corrected `works/arumbu/translations/en/sections/01-arumbu.md`.

## Exact next activity — Section 17 rerun only

Re-run release-readiness and verify:

- work/source-edition identity;
- Tamil canonical inventory **18/18** and assembled Tamil **1/1**;
- English section inventory and corrected Section 16 VERIFIED state;
- reader-facing navigation and control consistency;
- authority hierarchy and one-work/one-section identity;
- source pagination anomaly and protected oddities;
- canonical Tamil remains unchanged;
- source PDF remains uncommitted;
- any non-blocking editorial limitations.

If all checks pass, update `RELEASE_REPORT.md` to **RELEASE-READY** (archival/editorial), synchronize work/collection/root controls, commit, and stop.

Do **not** start `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison in the same checkpoint.
