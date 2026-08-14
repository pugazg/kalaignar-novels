# Assembled Tamil Reading Layer — பலிபீடம் நோக்கி

இந்த `sections/` அடுக்கு வாசிப்பதற்காகத் தொகுக்கப்பட்ட **source-faithful assembled layer**. இது canonical transcription அல்ல.

## Authority

Canonical source-preservation layer:

`../pages/`

அந்த 34 page records அனைத்தும் source scan-ஐ character-level audit செய்து `verified` செய்யப்பட்டவை. இந்த assembled layer அவற்றிலிருந்து மட்டுமே உருவாக்கப்பட்டது.

> **முரண்பாடு ஏற்பட்டால் `pages/` record-தான் controlling archival text.**

Source PDF repository-க்குள் இல்லை; commit செய்யக்கூடாது.

## Work identity

**`பலிபீடம் நோக்கி` ஒரே தொடர்ச்சியான படைப்பு.**

`ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` தனி work அல்ல. அது நூலுக்குள் திரைப்படக் காட்சியாக அமைந்த internal cinematic-historical sequence. அதனால் assembled files அனைத்திலும் ஒரே work identity:

```text
work: balipeedam-nokki
```

## Section map

| File | Source coverage | Role |
|---|---|---|
| `01-opening-frame.md` | scans 4–7 | `பலிபீடம்` உருவகத்தை அமைக்கும் தொடக்க frame; scan 7-ல் internal film அறிமுகம் |
| `02-rayasam-vengannu-sequence.md` | scans 8–29 + scan 30 through the internal film end-card | source-printed `ராயசம் வெங்கண்ணு — தஞ்சை சரித்திரக் கதை` cinematic-historical sequence |
| `03-return-and-conclusion.md` | scan 30 from `படம் முடிந்துவிட்டது...` through scan 33 | internal film-இலிருந்து main `பலிபீடம்` argument-க்கு திரும்புதல் மற்றும் முடிவுரை |

### Why scan 30 is split across sections 2 and 3

Scan 29 ends mid-sentence with `அப்படித்`; scan 30 begins `தத்தளிக்கிறான்...` and finishes the final action of the internal film. The same scan then shows the film's end-card (`வணக்கம்`) and only after that states:

`படம் முடிந்துவிட்டது. பாடம் கற்றுக்கொண்டீர்களா?...`

Therefore the assembled layer uses the **source's narrative transition**, not a mechanically imposed page boundary:

- section 2 carries the internal film through its actual end-card on scan 30;
- section 3 starts with the narrator's explicit `படம் முடிந்துவிட்டது...` return.

No source text is duplicated or omitted at this split.

## Assembly rules applied

1. Text is derived only from audited `pages/` records.
2. Historical spelling, punctuation, dialogue, cinema vocabulary and source oddities are preserved.
3. Scan observations, library stamps, handwriting, bleed-through notes and other copy-specific metadata are **not** inserted into the reading text.
4. Printed textual/ornamental elements that belong to the work, including the scan-7 star and scan-33 closing ornament marker, are retained.
5. HTML source comments preserve page provenance without interrupting normal Markdown reading.
6. Page-boundary joins are made only where the audit had already established exact continuity.

## Verified page-boundary joins in the assembled layer

- scans 5 → 6: `அணுக்` + `களிலிருந்து` → `அணுக்களிலிருந்து`
- scans 6 → 7: `உதிர` + `ஆறுகளைப் பாருங்கள்`
- scans 12 → 13: Vijay Raghava's open quotation continues without invented closure
- scans 19 → 20: `பாது` + `காத்துக்கொள்` → `பாதுகாத்துக்கொள்`
- scans 21 → 22: `என்று` + `கூறியபடி`
- scans 29 → 30: `அப்படித்` + `தத்தளிக்கிறான்...`
- scans 30 → 31: `கைகூப்புவதை` + `யும்` → `கைகூப்புவதையும்`

Each non-trivial join is accompanied by an inline `<!-- source join: ... -->` comment.

## Assembly verification

The assembled files were cross-checked against the final audited page records after the seven character-level review items had been resolved.

Checks completed:

- opening source coverage: scans 4–7 represented;
- internal sequence: scan-8 title card through the scan-30 film end-card represented;
- return/conclusion: `படம் முடிந்துவிட்டது...` through the scan-33 closing ornament represented;
- no `ராயசம் வெங்கண்ணு` work-level split introduced;
- all verified cross-page continuities preserved;
- no source modernization introduced intentionally;
- page provenance retained through comments;
- canonical `pages/` files left unchanged by assembly.

**Assembly status: PASSED.**

## Next stage

Prepare the English translation plan using these assembled sections for reading continuity while treating the audited `pages/` layer as the final textual authority for every disputed wording, punctuation choice or source oddity.
