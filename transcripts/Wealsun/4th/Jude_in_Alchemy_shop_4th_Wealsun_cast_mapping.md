# Cast Mapping — Jude in the Alchemy Shop (4th Wealsun)

`Jude_in_Alchemy_shop_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Jude, Albashon (the alchemist, DM-voiced NPC). (Paul Rivero is absent — off fetching his formula; Leslie not yet present.)
**In the room (2 voices):** Jude's player and the DM (narrating + voicing Albashon).

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_00** | The DM — narration + **Albashon** in-character | DM rulings/meta ("Jude does not know that name," 215–217); table admonishment (72) | Opens naming "Albashon, the Alchemist" (1); all lab business and the long lore exposition (258–487) sit here. |
| **SPEAKER_01** | **Jude** in-character + Jude's player OOC (dice, insight rolls, note-taking, "to the DM") | **Heavy bleed:** frequently carries Albashon's replies too (see flags) | Named Jude (69); his player runs the sahuagin-gill analysis, the Duke of Berghof / Zafar Azane questioning, and all the OOC rules chatter. |

## Flagged ambiguities (author: please correct)
- **Major two-speaker bleed onto SPEAKER_01.** Long stretches tag Albashon's own answers under 01 alongside Jude's questions. Clear cases: **105–114** (Jude asks about magical enhancement, then Albashon's "So what is a blood ritual to you? What is magic to you?" answers bleed in); **135–153** (Jude's Lord-Jameis/Prince-Jeon commission speech is his, but interleaved); **160–170**, **207–208**, **331–333** (Albashon's "That's why you were chosen, Jude" lands under 01). Assign the philosophical/lore replies to Albashon, the questions and desperation to Jude.
- **62–63** ("Hi. / Hola.") — a stray greeting exchange; possibly someone entering the real room. Likely out-of-band; confirm.
- Canonical name normalizations: "Vera/Viren/Varen" → **Albashon**; "Safar/Zafar/Zepharo/Zapara Azane/Zane/Hazane" → **Zafar Azane**; "Ediem/Idiom Nakhond" (272) → the rival Keoland transmuter (later reported dead); "Lord Jameis/James" → **Lord Jamis**; "Prince Gian/Jeon" → **Prince Jeon**; "Toli" → **Cain Toli / Sacnon Toli** line; "Sewell/Seul/Sula" → **Suel**; "Duke of Berghof/Berkhoff" and "Duke of Gratzel/Gretzel" — confirm spellings. Zafar Azane's sister is married to Lord Jamis (284, 447, 471).

## Out-of-band table chatter
Tagged `[out-of-band]` in the body — this file is dialogue-heavy but riddled with OOC asides:
- **72–73** ("Hey **Elise**, please, we're trying to play it here. / I know.") — real person, table admonishment.
- **210**, **213–217** (dice + "I'm just asking the DM if… Jude knows that" + DM ruling "Jude does not know that name").
- **220–224** ("We're talking about **high school** days… This is not high school.") — table banter/anachronism.
- **238–240** ("**To the DM**, it wasn't the Herzog himself…").
- **271** ("Can you give me **as a DM** what those two names are again?").
- **294–311** (extended OOC discussion of what Albashon *means* by asking "who is that young man" — player + DM parsing subtext; note 305–311 esp.).
- **390–407** (insight/intelligence-roll mechanics: proficiency, "plus eight is what your insight would be").
- **416** ("So, do you want to ask a question?" — DM prompt).
- **440–441** ("And how do you spell Sewell? / S-U-E-L.").
- **459–462** (name-spelling clarification, "Ekstor").
- **470** ("imagine watching **Friday the 13th** for the very first time" — movie anachronism).
- **484** ("Did he say Vangna?" — OOC clarification), **488** (player reciting names back to note them).

(Reasons: real names at the table, dice/roll mechanics, explicit "to the DM" OOC, spelling/note-taking, and modern-media anachronisms.)

## Speaker discontinuities
- Persistent 00↔01 bleed through the philosophical exchange (110–130) and the geopolitics lecture (258–488): the DM's Albashon voice repeatedly surfaces under SPEAKER_01. Re-attribute by content, not tag.
