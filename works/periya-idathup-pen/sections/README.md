# Assembled Tamil Reading Layer — பெரிய இடத்துப் பெண்

இந்த `sections/` அடுக்கு வாசிப்பதற்காகத் தொகுக்கப்பட்ட **source-faithful assembled Tamil reading layer**. இது canonical transcription அல்ல.

## Authority

Controlling archival text:

`../pages/`

அந்த **49 / 49** canonical page records-மே மேலாதிக்க source-preservation layer. Dedicated whole-work source comparison scans **1–49 / 49**-க்கும் முடிந்துள்ளது. ஆனால் user-mandated verification freeze காரணமாக canonical pages அனைத்தும் இன்னும் `needs-review`; `verified` count **0**.

> **முரண்பாடு ஏற்பட்டால் `pages/` record-தான் controlling archival text.**

இந்த assembled layer-ன் `PASSED` status என்பது derivation / continuity consistency-க்கு மட்டும். அது canonical page status-ஐ `verified` ஆக மாற்றுவதில்லை.

Source PDF repository-க்குள் commit செய்யப்படவில்லை / செய்யக்கூடாது.

## Reading-layer scope

- scans **1–7**: cover, copy annotation, publication details, author/publisher/edition notes — canonical `pages/` layer-ல் பாதுகாக்கப்பட்டுள்ளன; continuous narrative reading layer-ல் duplicate செய்யப்படவில்லை;
- scan **8**: source title `பெரிய இடத்துப் பெண்` + narrative opening;
- scans **8–49**: continuous narrative assembled here;
- scan **49**: narrative ending-க்கு பின் தனியாக அச்சிடப்பட்ட printer colophon `ஸ்ரீமகள் அச்சகம், சென்னை-1` non-narrative source matter ஆக retained.

## Work identity / structure

**`பெரிய இடத்துப் பெண்` ஒரே தொடர்ச்சியான படைப்பு.** Character-name headings தனி works / invented chapters அல்ல; source-printed internal textual structure:

- scan 15 / printed 14 — `உத்தண்டி`;
- scan 19 / printed 18 — `கண்ணம்மா`;
- scan 32 / printed 31 — `குமுதா`;
- scan 38 / printed 37 — `வீரன்`;
- scan 45 / printed 44 — `உலகநாதர்`;
- scan 46 / printed 45 — `கண்ணம்மா`.

## Section map

| File | Source coverage | Source role |
|---|---|---|
| `01-opening.md` | scan 8 → scan 15 before `உத்தண்டி` | title, opening narrative, transition into character accounts |
| `02-uthandi.md` | scan 15 from `உத்தண்டி` → scan 19 before `கண்ணம்மா` | `உத்தண்டி` first-person account |
| `03-kannamma-first.md` | scan 19 from first `கண்ணம்மா` → scan 31 | first `கண்ணம்மா` account |
| `04-kumudha.md` | scans 32–37 | `குமுதா` statement / signed account |
| `05-veeran.md` | scans 38–44 | `வீரன்` account |
| `06-ulaganathar.md` | scan 45 | `உலகநாதர்` account |
| `07-kannamma-conclusion.md` | scans 46–49 | final `கண்ணம்மா` account, narrative ending, separate printer colophon |

Scan 15 and scan 19 are deliberately split at **source-printed internal headings**, not mechanically at page boundaries. No source text is duplicated at those section transitions.

## Assembly rules applied

1. Text is derived only from the final audited canonical `pages/` records.
2. Source spelling, grammar, punctuation, vocabulary, spacing oddities and historical-period forms are preserved; no prose modernization was introduced.
3. Historical Tamil glyph identities use the source-supported modern Unicode readings established by the completed glyph/source audits.
4. Copy-specific marks, scan observations, audit prose and metadata are not inserted into the reader text.
5. HTML comments preserve reversible scan provenance without interrupting reading.
6. Cross-page fragments are joined only where the completed source audit positively established continuity.
7. Canonical `pages/` files and their `needs-review` statuses are not altered by assembly.

## Source-audit-established cross-page joins represented

Lexical / character joins:

- scans 11 → 12: `கிடப்ப` + `தாகக்` → `கிடப்பதாகக்`;
- scans 14 → 15: `நினைக்` + `காதே!` → `நினைக்காதே!`;
- scans 15 → 16: `தெரிந்` + `தது.` → `தெரிந்தது.`;
- scans 18 → 19: `என்` + `றேன்.` → `என்றேன்.`;
- scans 19 → 20: `என்` + `னிலே` → `என்னிலே`;
- scans 21 → 22: `காலக்ஷேபங்` + `கூட` → `காலக்ஷேபங்கூட`;
- scans 22 → 23: `மட்` + `டும்` → `மட்டும்`;
- scans 24 → 25: `‘ஒய்யா` + `ரக்` → `‘ஒய்யாரக்`;
- scans 25 → 26: `கவலை` + `யில்லை.` → `கவலையில்லை.`;
- scans 26 → 27: `நிலையி` + `லேயே` → `நிலையிலேயே`;
- scans 35 → 36: `அத` + `னுடைய` → `அதனுடைய`;
- scans 41 → 42: `கல்யா` + `ணத்தை` → `கல்யாணத்தை`;
- scans 46 → 47: `காரண` + `மாயிருந்தேன்!` → `காரணமாயிருந்தேன்!`;
- scans 47 → 48: `எழுதி` + `யிருந்தாள்.` → `எழுதியிருந்தாள்.`.

Other source-audit-established phrase continuities are preserved with explicit boundary comments, including scans 16→17, 17→18, 20→21, 23→24, 27→28, 28→29, 29→30, 30→31, 33→34, 36→37, 39→40, 40→41, 43→44 and 48→49. Scan 9→10 remains without invented terminal punctuation because the source supplies none at the physical boundary.

## Historical-glyph corrections carried into the reader

The assembled text contains the final canonical readings, including dedicated-audit discoveries:

- scan 33 `கண்ணாடி` (`ணா`);
- scan 43 `இளிச்சவாயனாக` (`னா`);
- scan 46 `நானா ஆள்?` (`னா`);
- scan 47 `விட வேணா?` (`ணா`).

Earlier confirmed corrections such as `ஆவலைக்`, `நின்றார்`, `போகிறாயே`, the `நன்றாக` family, `விழுவேன் என்றானா?`, and `வேலை மட்டுந்தானா?` are likewise carried through from canonical pages.

## Assembly consistency result

Cross-check completed against the final canonical page layer and `FULL_TAMIL_SOURCE_AUDIT.md`:

- narrative source coverage: scan **8 through scan 49** represented;
- all six source-printed internal headings represented in correct order;
- scan-15 and scan-19 mid-page heading transitions represented without duplication;
- all audit-established lexical joins represented;
- final `எழுதியிருந்தாள்.` and `ஒரு பெரிய ஜோதி...` continuities retained;
- narrative ending retained at `...எங்களிடம் வரவேண்டும், தெரியுமா?`;
- final printer colophon retained separately as non-narrative source matter;
- no intentional modernization introduced;
- canonical page files remain untouched and `needs-review` under the freeze.

**Assembled Tamil consistency status: PASSED.**

Detailed check: [`../ASSEMBLED_TAMIL_AUDIT.md`](../ASSEMBLED_TAMIL_AUDIT.md).

## Next stage

Prepare the **English translation plan** from this assembled reading layer, while treating canonical `pages/` as the final textual authority for any disputed wording, punctuation, historical glyph or source-specific form. Do not change the canonical verification freeze merely because translation begins.
