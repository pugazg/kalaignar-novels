# Next Chat Prompt — வெள்ளிக்கிழமை

Continue directly in `pugazg/kalaignar-novels`, branch `main`, active work `works/vellikkizhamai/`. Live `main` is authoritative.

## Source

`TVA_BOK_0064233_வெள்ளிக்கிழமை.pdf` — SHA-256 `ac241cbfbe3d47d76f22140f43c662176ba29a91521b826a1a8f5c75cf3081d3`, **179 scans**, image-only, second edition 1968. Do not commit it.

## Current durable state

- canonical records: **143 / 179**;
- Chapter 16 / 17 boundary: **scan 134 / printed 133**, centered `17`;
- Chapter 18 opens: **scan 142 / printed 141**, centered `18`;
- Chapter 18 transcribed through **scan 143 / printed 142**;
- historical-glyph coverage: **PASS scans 1–143**;
- next iteration: **scans 144–148**;
- batch size: **5 scans**;
- assembled Tamil / English: **not started / blocked**.

## Mandatory glyph rule

Check `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ` from source pixels. Grammar is only a locator. Never global-replace or normalize source wording.

## Production workflow

1. Fetch live `main` once.
2. Transcribe all five full pages straight through.
3. Run one batch-level 13-family historical-glyph sweep.
4. For a genuinely unclear token, allow **one targeted enlargement only**.
5. If still unresolved, record a source hold / `needs-review` and continue.
6. Create five page records, update audit/page-map/README/HANDOVER/prompt together, then make one atomic commit.
7. Do not reopen previously PASS scans unless new direct source evidence contradicts them.

## Recent source boundaries to preserve

- scan 137 / 138: `“இதோ,` → `கொண்டுவருகிறேன்”`;
- scan 138 / 139: `‘மளமள’` → `வென்று...`;
- scan 139 / 140: `புயலால் தாக்குண்டவன்போல` → `ஆனேன் அன்று!`;
- scan 140 / 141: `நயினா` → `எதுவும் பேசவில்லை.`;
- scan 142: Chapter 18 opening, centered `18`;
- scan 142 / 143: `வாசகங்கள்` → `இருந்தன.`;
- scan 143 ends a complete sentence; establish scan 144 only from direct source.

## Source-specific recent forms

Preserve confirmed source forms such as `வழங்கினை`, `சூறாவளி`, `காணத் வேண்டிப்போலவே`, `கைகாரியானாள்`, `நினைக்காதீர்கள்`, `நனைந்துபோன`, `அனைவருங்கூடி`, `விளக்கமுறைக்கவேண்டுமென்று`, `ஆனந்திமீது`, and `எங்ஙனம்`.

## Exact next activity

Process **scans 144–148** in one bounded 5-page iteration. Do not start assembled Tamil or English.
