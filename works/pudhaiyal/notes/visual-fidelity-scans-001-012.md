# Corrected visual-fidelity audit — புதையல் scans 1–12

Date: 2026-08-28

## Why this note changed

A backward integrity audit was opened after repeated assistant misreads of old-print Tamil. Scans 1–12 were therefore rechecked against `TVA_BOK_0064097_புதையல்_part_001_pages_1-49.pdf` instead of trusting the earlier `verified` label.

The scan remains controlling. User-supplied transcription is the comparison baseline. No assistant reading may override an old glyph merely because it appears grammatically or typographically more familiar.

## Result

Scans **1–12 remain verified**, but two material earlier assistant corrections are withdrawn:

### Scan 4 — publication page

Native reinspection establishes:

- `சாதாரணப் பதிப்பு ரூ 5/-`
- `நூல் நிலையப் பதிப்பு ரூ 6/-`
- `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`

The earlier assistant claim that the second price line read `ஸ்பெஷல் பதிப்பு` was wrong. The earlier assistant punctuation `மூன்றாம் பதிப்பு, ...` was also wrong; the scan prints a colon after `பதிப்பு`.

The supplied `முதற் பதிப்பு` remains rejected because the scan clearly prints `மூன்றாம் பதிப்பு`.

### Scan 5 — பதிப்புரை

The earlier recheck remains supported for the author initials and the publisher appeal. No rollback is required here.

### Scan 11 — colloquial anecdote

The scan supports the user's original `இருக்கிறான்னு`.

The earlier assistant correction to `இருக்கிறாள்ன்னு` was a hallucinated glyph interpretation and is withdrawn. `pages/0011-pudhaiyal.md` has been restored accordingly.

## Other retained findings

- scan 3 handwriting remains copy-specific and separate from printed text;
- scans 7–12 retain physical page boundaries;
- scan 8 `அடை` → scan 9 `யாளமாக` remains a cross-page split;
- the quotation begun on scan 10 continues onto scan 11;
- scan 11 `கனவு` → scan 12 `காண்பவர்களின்` remains a cross-page continuation;
- scan 12 ends `அறிமுகம்` and scan 13 begins chapter 1.

## Canonical records corrected in this integrity pass

- `../pages/0004-publication.md`
- `../pages/0011-pudhaiyal.md`

## Gate state

- scans 1–12: **12 verified**
- unresolved readings in scans 1–12: **0**
- project-wide backward integrity audit: **OPEN**
- forward transcription: **FROZEN until the audit gate closes**

See [`backward-integrity-audit-001-118.md`](backward-integrity-audit-001-118.md) for the cross-range correction record.
