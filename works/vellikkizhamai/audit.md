# Transcription / Source Audit — வெள்ளிக்கிழமை

## Current gate

| Check | Status |
|---|---|
| Source identity / checksum / page count | **complete** |
| Initial scan manifest | **179 / 179 represented** |
| Canonical page records | **111 / 179** |
| Body transcription | **through scan 111** |
| Printed-page map | **directly confirmed through scan 111; scan 66 visibly prints only `5`** |
| Chapter map | **direct through Chapter 13 continuation at scan 111** |
| Historical-glyph work-level gate | **REOPENED** |
| Corrective historical-glyph re-audit | **PASS scans 102–111** |
| Retrospective historical-glyph re-audit | **PENDING scans 1–101** |
| Full Tamil source audit | **not started** |
| Assembled Tamil | **not started** |
| English translation | **blocked until Tamil gate passes** |

## Why the gate was reopened

The historical-glyph guide requires character identity to be decoded from the old type before Unicode transcription. The earlier pass failed this rule in multiple places by treating old glyphs as modern look-alikes. Because the same typeface is used across the work, the earlier work-level PASS claim is withdrawn pending retrospective review.

## Corrective re-audit — scans 102–111

**Result: PASS for this ten-scan corrective range.**

| Scan | Earlier/apparent | Source-supported Unicode | Historical family / finding |
|---:|---|---|---|
| 102 | `ஆட்டினள்` | `ஆட்டினாள்` | `னா` before final `ள்` |
| 103 | `நன்றுகக்` | `நன்றாகக்` | `றா` |
| 103 | `கத்தினள்` | `கத்தினாள்` | `னா` before final `ள்` |
| 104 | `கூறினள்` | `கூறினாள்` | `னா` before final `ள்` |
| 106 | `திருப்பினள்` | `திருப்பினாள்` | `னா` before final `ள்` |
| 106 | `என்றுள்` | `என்றாள்` | historical full-cluster misread involving `றா` |
| 106 | `நன்றுகக்` | `நன்றாகக்` | `றா` |
| 106 | `தவறுக` | `தவறாக` | `றா` |
| 107 | `கூறினள்` | `கூறினாள்` | `னா` before final `ள்` |
| 107 | `கொட்டினன்` | `கொட்டினான்` | source-pixel `னா` |
| 107 | `என்றுள்` | `என்றாள்` | historical full-cluster misread |
| 107 | `ஓடினன்` | `ஓடினான்` | source-pixel `னா` |
| 107 | `ஓடினர்கள்` | `ஓடினார்கள்` | source-pixel `னா` |
| 108 | `திமிறினன்` | `திமிறினான்` | source-pixel `னா` |
| 108 | `நடுங்கினள்` | `நடுங்கினாள்` | `னா` before final `ள்` |
| 109 | `சொன்னு` | `சொன்னா` | `னா` |
| 109 | `பொய்தானு?` | `பொய்தானா?` | `னா` |
| 110 | `பெண்ணு?` | `பெண்ணா?` | `ணா` |

Scan 105 and scan 111 were also rechecked and required no confirmed historical-glyph correction. No global replacement was used. Scan 109 `கூறினன்` / `சொன்னன்` and scan 110 `புளுகினன்` were separately inspected and retained.

## Structural result of scans 107–111

- scan 107 / printed 106: Chapter 12 carryover, centered `13`, Chapter 13 opening;
- scans 108–111 / printed 107–110: Chapter 13 continuation;
- scan 106 `அவள் கண்களில்` → scan 107 `நீர் கலங்கிற்று`;
- scan 107 `தப்பித்துவிட` → scan 108 `எவ்வளவோ திமிறினான் டைகர்.`;
- scan 109 `சுருக்கமாகச் சொல்லப்போனால்` → scan 110 `நான் ஒரு புழுதிமேடு!`;
- scan 111 `சிறிதா` → scan 112 source-visible `வது` = `சிறிதாவது`.

## Unresolved project items

- **retrospective historical-glyph re-audit scans 1–101**;
- scans **112–179** forward canonical processing;
- final complete Tamil audit;
- assembled Tamil;
- English after Tamil gate.

## Exact next activity

Do **not** resume forward transcription yet. Process **scans 1–5** as the first retrospective 5-scan historical-glyph audit batch, update any confirmed Unicode corrections from source pixels, and continue chronologically.
