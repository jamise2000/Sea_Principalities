# Cast Mapping — Leslie's Introduction (4th Wealsun)

`Leslies_introduction_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Leslie (new PC — Oeridian sage-wizard), Albashon (his master, **described only, not present/voiced here**). Jude is listed in the folder cast but **does not appear or speak** in this file.
**In the room (2 effective voices):** the DM (delivering Leslie's character-creation backstory) and Leslie's player (asking a few questions).

> This is a **session-zero backstory briefing**, not a dramatized scene: the DM narrates who Leslie is, his mentor Albashon, the foreign district, and Suel vs. Oeridian lore. It is source material for Leslie's backstory rather than in-scene action.

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_00** | The DM — backstory narration (mentor, foreign district, Suel/Oeridian races, princes) | A couple of Leslie's short answers bleed in (118 "Nope", 121 "Yes") | Second-person exposition throughout ("your mentor," "you feel yourself lucky"); no in-character NPC voicing. |
| **SPEAKER_01** | The DM — **same backstory narration** (a second diarized voice for one narrator) | — | Content is indistinguishable DM exposition, interleaved sentence-by-sentence with SPEAKER_00 (e.g. 11–15, 21–24, 57–70). Treat 00 and 01 as one DM voice. |
| **SPEAKER_02** | **Leslie's player** (out-of-character questions) | — | Asks "Are they still doing exceptionally good?" (41), "is that his name or his race?" (81), and the ready-check answers. |

## Flagged ambiguities (author: please correct)
- **SPEAKER_00 and SPEAKER_01 are the same person (the DM).** The diarizer split one narrator across two tags; do not read them as two characters. This is the defining quirk of this file.
- **82** ("Albinath is his name") is tagged SPEAKER_02 but is the DM answering the player's race-vs-name question; **83** ("Sewell is his race") confirms it under 01. Attribute the answer to the DM.
- Albashon is only *described* here (old, Suel, a transmuter, unbiased toward Oeridian apprentices) — no in-character lines to map. Jude is entirely absent despite the folder cast list.
- Normalizations: "Albinath/Albinath" → **Albashon**; "Sewell/Seul/Sualar" → **Suel**; "Iridian/Aridian/Arrhenius/Iradian" → **Oeridian**; "Ujor Udias" (60), "Vangna" (67) — confirm spellings; "Toli" (112) → the Suel **Toli** line (Cain/Sacnon Toli).

## Out-of-band table chatter
Tagged `[out-of-band]` in the body: the session logistics/check-ins around the exposition — **74** ("Okay."), **80** ("No, not really."), and **117–121** ("Any questions? / Nope. / Okay, Leslie. Are you ready to start? / Yes."). (These are table Q&A / session-start logistics, not backstory content. Note 80–82 also contains a genuine lore question — keep the question's substance, drop the "ready?" framing.) The backstory narration itself is **in-band** worldbuilding, not chatter.

## Speaker discontinuities
- Continuous 00↔01 alternation for a single narrator (see flags) — the biggest thing to correct here.
- Leslie's answers occasionally surface under SPEAKER_00 (118, 121) instead of SPEAKER_02.
