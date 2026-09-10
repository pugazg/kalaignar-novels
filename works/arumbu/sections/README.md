# Assembled Tamil Reading Layer — அரும்பு

இந்த `sections/` அடுக்கு வாசிப்பு தொடர்ச்சிக்காக உருவாக்கப்பட்ட **source-faithful derived layer**. இது canonical transcription அல்ல.

## Authority

Controlling archival Tamil layer:

`../pages/`

Scans **6–23**-க்கு உரிய **18 / 18** canonical page records அனைத்தும் direct-source T1, independent historical-glyph T2, final source-fidelity T3 மற்றும் whole-work Tamil audit ஆகியவற்றை முடித்து `verified` நிலையில் உள்ளன. இந்த assembled layer அவற்றிலிருந்து மட்டுமே உருவாக்கப்பட்டது.

> **முரண்பாடு ஏற்பட்டால் `pages/` record-தான் controlling archival text.**

Source PDF repository-க்குள் இல்லை; commit செய்யக்கூடாது.

## Work identity and structure

`அரும்பு` இந்த 1978 தொகுப்பின் முதல் component work. Source-backed chapter divisions இந்த 18 scans-க்குள் இல்லை. ஆகவே வாசிப்பு layer ஒரு continuous section ஆக மட்டுமே அமைக்கப்பட்டுள்ளது; artificial chapter split உருவாக்கப்படவில்லை.

## Section map

| File | Source coverage | Role | Status |
|---|---|---|---|
| `01-arumbu.md` | scans **6–23** | முழு `அரும்பு` கதையின் source-faithful continuous Tamil reading layer | **VERIFIED / PASSED** |

Printed-page provenance source-ஐப் போலவே காக்கப்படுகிறது: scan 6 unnumbered; scans 7–13 printed 2–8; scan 14 printed 10; scans 15–23 printed 11–19. Missing printed page 9 **infer செய்யப்படவில்லை**.

## Assembly rules applied

1. Text is derived only from the 18 audited `pages/` records; no independent re-transcription was performed.
2. Source spelling, punctuation, dialogue, paragraph structure, rhetoric, period forms and unusual readings are preserved.
3. Page-level T1/T2/T3 audit notes, scan observations, illustration descriptions and footer/non-body material are not inserted into reading prose.
4. The scan-6 source title is retained as the reading-layer title; the opening illustration itself remains outside narrative text.
5. Reversible HTML comments identify physical page provenance and every cross-page continuation used for assembly.
6. Only already-established page continuations are joined; no wording is supplied from context or memory.
7. No chapter divisions and no synthetic printed page 9 are introduced.
8. Scan 23 remains the ending exactly as supported by the canonical record; no unprinted `முற்றும்` is added.

## Verified cross-page continuations

The following joins were already established during page-level audit and are joined only for readable continuity:

- 7→8: `நடந்` + `தேறின.` → rendered `நடந்தேறின.`;
- 8→9: `அபிநய` + `அசைவுகளை`;
- 9→10: `வைத்தியரை அழைத்து` + `வந்துவிடுகிறேன்”`;
- 11→12: `போய்` + `விட்டனர்.` → rendered `போய்விட்டனர்.`;
- 13→14: `ஊற்றெடுத்துக் கிளம்பிவரும்` + `அருவி!` — across the source-visible printed-number jump 8→10;
- 15→16: `செல்லக்` + `குழந்தையை—...`;
- 16→17: `அவர்களைக்-` + `கவனிக்கிறான்.`;
- 17→18: `குமார்` + `பள்ளிக்கூடத்தில்...`;
- 18→19: `செலவா` + `யிற்று.` → rendered `செலவாயிற்று.`;
- 19→20: `கடிந்துகொண்` + `டிருக்கிறாள்.` → rendered `கடிந்துகொண்டிருக்கிறாள்.`;
- 20→21: `அவனது அம்மா படம்!` + `அதை எடுத்து...`;
- 21→22: `அப்பா பாப்பாவை நினைத்து` + `அழுதுகொண்டே யிருக்கிறாரே!`;
- 22→23: scan 22 closes a complete sentence; scan 23 begins a new paragraph `அவளையறியாமல்,...` and remains a paragraph boundary rather than a fused join.

Each joined boundary is accompanied by an inline `<!-- source join: ... -->` marker. Non-joined source transitions use standalone `<!-- source: scan ... -->` markers where needed.

## Preserved audited oddities

The reading layer deliberately retains source-confirmed forms including:

- scan 22 `பேசினேன்`;
- scan 23 `அம்மனார்`;
- scan 23 final punctuation `இனி:......`.

These were independently source-confirmed before assembly and are not context-normalized here.

## Assembly consistency check

The completed `01-arumbu.md` was reconciled against all 18 verified canonical records after assembly.

Checks completed:

- source coverage: scans **6–23** represented in order;
- canonical records represented: **18 / 18**;
- no canonical page record omitted or duplicated;
- no artificial chapter/section boundary added;
- established page-fragment joins preserved;
- scan 13 / printed 8 → scan 14 / printed 10 provenance preserved without inventing page 9;
- scan 22 `பேசினேன்` and scan 23 `அம்மனார்` retained unchanged;
- scan 23 final text retained without adding `முற்றும்`;
- page-level audit notes/non-body observations excluded from reading prose;
- canonical `pages/` files left unchanged by assembly.

**ASSEMBLED TAMIL READING LAYER — PASSED.**

## English planning status

`../translations/en/TRANSLATION_PLAN.md` is now **PASS / COMPLETE** under Section 14. Working English title: **The Bud**. The planned English layer remains one final section translated in four controlled batches: scans **6–10**, **11–15**, **16–20**, and **21–23**.

The audited `pages/` layer remains final textual authority; this assembled section remains reading-continuity support.

## Next stage

Execute **English Batch 1 pilot — scans 6–10 only**, source-check it against canonical pages, synchronize the English controls, and stop before Batch 2.
