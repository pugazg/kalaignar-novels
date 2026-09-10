# Release Readiness Report — அரும்பு

## Gate

Section 17 release-readiness under `NOVEL_PROCESSING_GUIDE.md`.

**Verdict: NOT READY — one source-fidelity blocker found.**

This is an archival/editorial verdict only. It is not a copyright, licensing, public-domain, republication-rights or commercial-use determination.

## Work and source identity

- work: **அரும்பு**;
- working English title: **The Bud**;
- author: **கலைஞர் மு. கருணாநிதி**;
- source volume: **அரும்பு**;
- publisher: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**;
- source edition: **முதற் பதிப்பு — 1978**;
- controlling file: `TVA_BOK_0064361_அரும்பு.pdf`;
- SHA-256: `04a3013e1f58a1800867acc5d2f159976c47994a64478036e6fe0201edf120bc`;
- source volume: **92 physical scans**;
- work span: **scans 6–23 / 18 scans**.

Identity / boundary check: **PASS**. `அரும்பு` remains the first distinct component of the four-story 1978 compilation.

## Inventory checks

| Inventory | Release-gate result |
|---|---|
| Canonical Tamil page records | **PASS — 18 / 18 VERIFIED** |
| Tamil physical coverage | **PASS — scans 6–23 contiguous** |
| Whole-work Tamil audit | **PASS / COMPLETE** |
| Assembled Tamil | **PASS — 1 / 1 section** |
| English batch coverage | **PASS — 4 / 4 reviewed; scans 6–23 represented** |
| English reading section inventory | **PASS — 1 / 1 continuous section** |
| Section 16 review artifact | **PRESENT** |
| Source PDF exclusion | **PASS — no `.pdf` path found in the live recursive repository tree** |

## Reader-facing structure and provenance

- canonical Tamil authority: `../../pages/`;
- assembled Tamil reading layer: `../../sections/01-arumbu.md`;
- English reading layer: `sections/01-arumbu.md`;
- English remains one continuous section because no source-backed chapter divisions exist;
- scan/page provenance is retained in the assembled Tamil and English layers;
- source-visible pagination remains scan 6 unnumbered, scans 7–13 printed 2–8, scan 14 printed 10, scans 15–23 printed 11–19;
- no printed page 9 is invented;
- scan 23 contains no explicit `முற்றும்`, and English adds no `The End`.

Structural identity / provenance: **PASS**.

## Release-blocking fidelity finding

Section 17 rechecked reader-facing English against canonical Tamil at a source-sensitive passage and found a concrete mismatch that Section 16 did not record.

Canonical scan 17 / printed page 13 reads:

`“எனக்குப் பொய் அம்மா வேணும்! நிஜ அம்மாதான் வேணும்!”`

The current English reads:

`“I don't want a fake Amma! I want my real Amma!”`

The English inserts the negation **`don't`**, but audited canonical Tamil has affirmative **`வேணும்`**. The controlling source pixels were also re-inspected during release preflight and support the canonical affirmative reading. Under this repository's source-fidelity rule, source strangeness must not be silently repaired from context.

Therefore:

- Section 16 requires a **narrow corrective re-open**;
- whole-work English VERIFIED is suspended until this sentence is corrected and rechecked;
- canonical Tamil must remain unchanged;
- English must preserve the source-confirmed affirmative wording rather than infer an unprinted negative.

This remains the sole release blocker.

## Previously documented source oddities

These remain correctly protected and are not blockers:

- scan 22 `பேசினேன்` → English **I spoke**;
- scan 23 `அம்மனார்` → **Ammanar**, distinct from earlier Ammanur;
- final `இனி:......` → **from now on:......**;
- no explicit `முற்றும்` → no **The End**.

## Navigation/control consistency

The release pass found two stale archival controls: `../../indexes/page-map.md` still said English was not started, and `../../sections/README.md` still named Batch 1 as next. Both were **synchronized during this Section 17 checkpoint**. They are no longer blockers.

## Canonical Tamil immutability

Canonical Tamil files were **not changed** during this release-readiness pass.

## Final Section 17 verdict

**NOT READY.**

Release-readiness is blocked only by the scan-17 English negation mismatch.

## Exact next activity

Perform a **narrow Section 16 corrective re-open for scan 17 only**:

1. change the English clause so it preserves source-confirmed affirmative `பொய் அம்மா வேணும்` rather than inserting `don't`;
2. document the source oddity and correction in `GLOSSARY.md` and `TRANSLATION_REVIEW.md`;
3. recheck the affected scan-17 paragraph and its 16→17 / 17→18 joins against canonical `../../pages/0017-arumbu-13.md`;
4. restore whole-work English `VERIFIED` only after that check passes;
5. synchronize affected English/work/root controls;
6. commit and stop.

After that corrective checkpoint, rerun Section 17 release-readiness. Do **not** start `சாரப்பள்ளம் சாமுண்டி` or the 1978 `பெரிய இடத்துப் பெண்` witness comparison before release closure.
