# Backward integrity audit — புதையல் scans 1–118

Date opened: 2026-08-28  
Status: **COMPLETE — integrity gate closed through scan 118**

## Why this audit exists

Earlier assistant visual-fidelity passes changed user-supplied Tamil after misreading old-print glyphs. Some of those changes were later presented as source-confirmed even though they were wrong. A prior `verified` label is therefore not accepted merely because an assistant once performed a visual pass.

Audit rule:

1. source scan is controlling;
2. user transcription is the comparison baseline;
3. an assistant change survives only when native scan pixels establish it;
4. ambiguous old glyphs do **not** justify overriding the baseline;
5. ambiguous pages are `needs-review`, not `verified`;
6. a page returns to `verified` only after the complete physical scan passes native-image reinspection.

## Canonical corrections applied

### Scans 1–12

- scan 4: restored `நூல் நிலையப் பதிப்பு ரூ 6/-`; earlier assistant `ஸ்பெஷல் பதிப்பு` was wrong;
- scan 4: restored `மூன்றாம் பதிப்பு: செப்டம்பர், 1961.`;
- scan 11: restored `இருக்கிறான்னு`; earlier assistant `இருக்கிறாள்ன்னு` was wrong.

### Scans 23–32

- scan 24: restored `அவர்களை நோக்கி`; earlier assistant `அவர்களே நோக்கி` was wrong;
- scan 25: restored `எதோ மருந்தொன்றை`; assistant normalization `ஏதோ` was wrong;
- scan 31: removed the assistant-inserted full stop after `மூர்ச்சை யடைந்தான்`;
- scan 31: restored continuous `அவனைத்தழுவிக்`.

### Scan 75

The disputed அஞ்சலை question was resolved by a dedicated native-resolution inspection.

The physical source line wraps the word as:

- `போயிட்`
- `டுதா?`

Continuous source reading: **`போயிட்டுதா?`**.

Therefore:

- earlier assistant `போயிடுச்சா?` is confirmed wrong;
- temporary restored baseline `போய்ட்டுதா?` is superseded;
- canonical scan 75 records `போயிட்டுதா?` and is `verified`.

### Scans 99–108

- scan 99: restored `சொல்வேன் என்று... நான் யாருடைய...`; assistant `சொல்லுவேன் என்றா... இப்ப யாருடைய...` is withdrawn;
- scan 101: restored `அவரைப் பற்றி நன்கு விசாரிக்கவேண்டும் என்ற ஒரு ஆவல்...`; assistant-inserted `நான்` and comma are withdrawn;
- scan 104: restored `நெடு நாள் பழக்கமா?`; assistant `நெடு நாளா பழக்கமா?` is withdrawn;
- scan 104: `உடல் வளர்த்து` is explicitly confirmed;
- scan 106: restored `நான் வரத்தான் வேண்டுமா?`; assistant `வேண்டுமோ?` is withdrawn.

## Earlier assistant corrections that survived reinspection

The audit did **not** blindly revert every assistant delta. Source-supported readings retained include, among others:

- scan 5 `எம். எல். ஏ.`;
- scans 13–22 native-resolution corrections documented in `visual-fidelity-scans-013-022.md`;
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

## Iteration 10 safety reset — scans 109–118

The prior Iteration-10 verification was withdrawn and all ten pages were reopened. A fresh native-image audit of split part 003 pages 11–20 is complete.

**Result: scans 109–118 are 10 / 10 verified; unresolved readings in this range: 0.**

Key results:

- scan 109: user-confirmed `என்னா பிரதர்!`; source also establishes `துக்கராமாக`, `பாழாய்ப்போன`, `திறமை யில்லேன்னு`;
- scan 110: user-confirmed `போய்ட்டு வர்ரேன்`; chapter 11 → 12 transition confirmed;
- scan 111: `நான் இருக்கிறது மருங்கப்பள்ளம்!`; assistant `மருங்கப்பள்ளம்தான்` withdrawn;
- scan 112: `காஷ்—?` confirmed; following phrase is `என் அனாவசியமா செலவு...`;
- scan 113: `ஆணு, பெண்ணு?`, `இது என் இந்த புதிய கேள்வியைக்...`, and `தம்பீ!` confirmed;
- scan 114: `லக்ஷணம்னு`, `முன்னேயே`, `பாட்டு ஆரம்பித்து விட்டான்`, `"காயாத கானகத்தே!" என்ற பாட்டை`, `பயித்தியமாயிருக்கிறதாக்கும்`, `பாடிக் கொண்டிருக்கும்`;
- scan 115: `போதும் தம்பி போதும்!`; first `மிஞ்சக் கூடியது`, second `மிஞ்சக்கூடியது`;
- scan 116: `செத்துப்போயி கூட`, source-odd `அவர்கள் ஆசிரியர் விடவில்லை`, `நான் தான்`, `நல்ல முடிவு தம்பி!`, `படித்து விட்டு`;
- scan 117: `நம்ப ஊருக்கு`; source correction `பாத்துட்டான்னு சரின்னு சொல்லிடுவான்`;
- scan 118: `மருங்கப்பள்ளத்துச் சிவன் கோயிலுக்கு`, `வேண்டும் என்று அவசர புத்தி`; four-star internal transition retained.

Detailed record: [`visual-fidelity-scans-109-118.md`](visual-fidelity-scans-109-118.md).

## Final integrity state through scan 118

- page records created: **118**
- verified: **118**
- needs-review: **0**
- partial: **0**
- unresolved readings through scan 118: **0**
- known-prefix not-started: **32** — scans 119–150
- full-source manifest: **INCOMPLETE**
- Tamil whole-work audit: **not started**
- English translation: **blocked**
- source/split PDFs committed: **No**

## Audit conclusion

The backward integrity recovery is complete through scan 118. All pages that were reopened because of assistant-introduced uncertainty have either been corrected from native scan evidence or reverified without unresolved readings.

The stricter rule remains permanent for all future work: an old-form glyph may not be changed away from the user's transcription merely because another reading appears grammatically or typographically plausible.

## Exact next activity

Backward integrity is closed. Forward transcription may now resume from **scan 119 / printed page 117**, using split part 003 and the next user-supplied baseline. Do not start English translation.
