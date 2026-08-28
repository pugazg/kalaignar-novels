# Backward integrity audit — புதையல் scans 1–118

Date opened: 2026-08-28  
Status: **OPEN — forward transcription frozen**

## Why this audit exists

Several earlier assistant visual-fidelity passes changed user-supplied Tamil after misreading old-print glyphs. Some of those changes were later presented as source-confirmed even though they were wrong. A `verified` label could therefore no longer be accepted merely because an assistant had previously performed a visual pass.

This audit works backward from every assistant-introduced disagreement and applies a stricter rule:

1. source scan is controlling;
2. user transcription is the comparison baseline;
3. an assistant change survives only when native scan pixels establish it;
4. ambiguous old glyphs do **not** justify overriding the baseline;
5. ambiguous pages are `needs-review`, not `verified`;
6. forward transcription is frozen while this audit is open.

## Canonical corrections applied in this pass

### Scans 1–12

- scan 4: restored `நூல் நிலையப் பதிப்பு ரூ 6/-`; earlier assistant `ஸ்பெஷல் பதிப்பு` was wrong;
- scan 4: restored `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`; earlier assistant comma after `பதிப்பு` was wrong;
- scan 11: restored `இருக்கிறான்னு`; earlier assistant `இருக்கிறாள்ன்னு` was wrong.

### Scans 23–32

- scan 24: restored `அவர்களை நோக்கி`; earlier assistant `அவர்களே நோக்கி` was wrong;
- scan 25: restored `எதோ மருந்தொன்றை`; earlier assistant normalization `ஏதோ` was wrong;
- scan 31: removed the assistant-inserted full stop after `மூர்ச்சை யடைந்தான்`;
- scan 31: restored continuous `அவனைத்தழுவிக்`; assistant `அவனைத் தழுவிக்` was wrong.

### Scan 75

- earlier assistant `போயிடுச்சா?` is withdrawn;
- user's `போய்ட்டுதா?` is restored as the working baseline;
- exact old-glyph sequence remains unresolved, so scan 75 is now `needs-review`.

### Scans 99–108

- scan 99: restored source `சொல்வேன் என்று நினைக்கிறீர்கள்!... நான் யாருடைய பெயரைச் சொன்னேன் தெரியுமா?`; assistant `சொல்லுவேன் என்றா... இப்ப யாருடைய...` is withdrawn;
- scan 101: restored `அவரைப் பற்றி நன்கு விசாரிக்கவேண்டும் என்ற ஒரு ஆவல்...`; assistant-inserted `நான்` and comma are withdrawn;
- scan 104: restored `நெடு நாள் பழக்கமா?`; assistant `நெடு நாளா பழக்கமா?` is withdrawn;
- scan 104: `உடல் வளர்த்து` is explicitly confirmed; a later assistant suggestion `உடலை வளர்த்து` is itself rejected;
- scan 106: restored `நான் வரத்தான் வேண்டுமா?`; assistant `வேண்டுமோ?` is withdrawn.

## Earlier assistant corrections that survived reinspection

The audit did **not** blindly revert every assistant delta. Source-supported readings retained include, among others:

- scan 5 author initials `எம். எல். ஏ.`;
- scans 13–22 corrected native-resolution readings documented in `visual-fidelity-scans-013-022.md`;
- scan 23 `மதகின் உள்ளேயிருந்தவர்களுக்கு`;
- scan 28 `அவன் முதுகில்`;
- scan 29 `அவர்களே தான்`, `கடல் பார்த்துக் கொண்டிருந்தாள்`, `அவளை அவன் காப்பாற்றித் தீர வேண்டும்`;
- scan 30 `பழைய பிரார்த்தனையில்`;
- scan 32 `தும்பைப்பூ`;
- scan 33 `“யார்?”`;
- scan 37 `கிழவர்`;
- scan 38 `தோணிக்கு`;
- scan 41 `அவன்`;
- scan 43 `புற்று நோய்`;
- scan 69 chapter `7` / `எவ்வளவுதான்`;
- scan 70 `குறும்புக்காரக் கிழவா`;
- scan 71 `பெரிய மனுஷா`;
- scan 84 `வேகமான நடையிலே`;
- scan 97 `சில விநாடிகள்` / `தெவிட்டுவதற்கு`.

These are retained because the native page image supports them, not because an earlier audit said so.

## Iteration 10 safety reset — scans 109–118

The previous Iteration-10 pass was never completed reliably, yet its page files had been labelled `verified`. That status is withdrawn.

All scans **109–118** are now `needs-review` and retain their current text only as a working comparison baseline.

Two user-confirmed readings are protected from assistant substitution:

- scan 109: `என்னா பிரதர்!`
- scan 110: `போய்ட்டு வர்ரேன்`

Every other assistant-introduced difference in scans 109–118 must be rechecked against native part-003 pixels before those pages return to `verified`.

## Current integrity state

- page records created: **118**
- verified: **107**
- needs-review: **11** — scan 75 and scans 109–118
- partial: **0**
- known-prefix not-started: **32** — scans 119–150
- full-source manifest: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- English translation: **blocked**
- source/split PDFs committed: **No**

## Exact next activity

Do **not** begin scan 119.

First perform a fresh native-image, page-by-page integrity audit of **scans 109–118 / printed pages 107–116**, using the user's Iteration 10 as baseline. Do not silently replace old-form glyphs. Resolve each assistant delta as `confirmed`, `withdrawn`, or `ambiguous`. Promote a page to `verified` only after its complete physical page passes.

After scans 109–118 are resolved, separately resolve scan 75's old-glyph reading. Only when all 11 `needs-review` pages are closed may forward transcription resume from scan 119.
