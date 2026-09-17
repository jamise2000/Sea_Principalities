# Cast Mapping — Jude in Combat (4th Wealsun)

`Jude_combat_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking. **A tag is a voice, not a fixed character.** **Combat transcript** — the bulk (192 of 235 lines) is dice/rules/positioning and is `[out-of-band]`; only the sparse in-story beats are in-band.

**Cast (index):** Jude, **Albashon** (the alchemist), Scarlet Brotherhood raiders (**non-speaking** — their strikes are DM narration).
**In the room (2 voices):** the **DM** (narration + Albashon + attackers + rulings) and **Jude**'s player.

## Tag scheme (A = PC/DM, B = NPC)
| Sub-tag | Character | Count |
|---------|-----------|-------|
| **SPEAKER_00A** | **DM** — narration + the attack (dagger/bolt/fire) | 32 |
| **SPEAKER_01A** | **Jude** (PC) | 10 |
| **SPEAKER_01B** | **Albashon** (NPC) — one line only (38 "Can I help you?") | 1 |
| `[out-of-band] [SPEAKER_0N]` | combat mechanics, dice, positioning, table chatter | 192 |

## The point of the conversation
The **opening of the night raid** on Albashon's shop — the ambush Jude feared. Jude goes invisible (his ring) and positions to intercept. An assassin drives a **dagger through the door into Albashon's eye/face**, a crossbow bolt follows, and Albashon goes down. Jude retaliates: he steps to the door-slit and hurls a **fireball out through the portal**, incinerating the attackers out front (screams, shouting outside). More bolts/darts come through the door as the raiders surround the building. Nearly all of it is fought in mechanics; the in-story beats are few.

## In-story beats (the "keep" lines)
- **6 "You are important to me."** — Jude to Albashon, just before going invisible (a genuine beat — Jude has said he fears this man being targeted).
- **38 "Can I help you?"** — Albashon (01B) answering the door, immediately before the dagger strikes.
- **39–41, 61–62, 90, 94, 99, 136–137, 180–186, 213–220** — DM narration of the attack and Jude's fireball.
- **42 "…I put my palm up through the door," 138 "Jude walks out there and area effect…"** — Jude acting.

## Applied bleed fixes
- **7 "And I use my ring and I go invisible."** → **Jude (01A)** (was DM tag).
- **38** → **Albashon (01B)**.
- **60 "You do not go first," 63 "In the head," 216/218/219** (dart narration) → **DM (00A)** (were on Jude's tag).

## Flags (author: please confirm)
- **4 "There's a knock on the door."** (01A) — Jude noting it, or DM narration? (duplicates the DM's line 1.)
- **214 "So there's a magic user?"** (00A) — reads as Jude asking; left on DM tag.
- **217 "Seven."** (01A) — a to-hit roll; could be `[out-of-band]`.

## Out-of-band table chatter
`[out-of-band]`: essentially all the mechanics — invisibility/positioning (8–35), initiative/reaction/shield rules (43–89, 100–135), fireball damage dice (139–179), AC/save rolls (187–212, 221), the "Elise/Sam/Adrian" real-family chatter (28–34, 222–235). ASR: "board" (36) = the **door**; "niche" = **initiative**.

## Speaker discontinuities
- None of the reading-the-wrong-part type; this is a combat log — mechanics dominate, in-story beats are sparse.
