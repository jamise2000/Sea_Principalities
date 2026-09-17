# Cast Mapping — Gouge Waits in the Dark (6th Wealsun)

`Gouge_waits_in_the_dark_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Folsom.
**In the room (3 voices):** two players — Gouge and Folsom — plus the DM (narration + mechanics). Folsom, having escaped Owen's boat, rejoins Gouge, who is lying in wait outside the bar; the two then head back toward the party.

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_01** | **The DM** — narration + mechanics | Bleed of Gouge's player (16 "I'm going to whistle at them"; 79 "I say, wait") | Opens the scene ("Gouge, you go back to the bar… roll your stealth" 1–4), narrates Folsom's frantic approach (9–14), and answers questions about Owen's reputation ("You have no idea… he has allies. Contacts." 81–85). |
| **SPEAKER_02** | **Gouge** (knife-man / rogue) | The stealth-roll aside (5–7) | Rolls stealth to lurk in the alley (5–7); "I can't speak back through messaging" (36); the after-action "good fight, got beat down a bit, but came out on top… everyone's alive" (40–43); cautious "I'd rather not stir up any ruckus… get back to the other guys" (88–91). |
| **SPEAKER_00** | **Folsom** (bard) | Bleed of DM lines (28 "You're pretty relieved"; 30 "Actually, what do you do?") | Casts Message to reach Gouge (31–38) and recounts his escape in first person — "Long story short, I blinded him… stabbed his Toli friend and ran off their ship" (56–58), the full retelling at 100–117. |

## Flagged ambiguities (author: please correct)
- **DM/player bleed on both PC tags.** Folsom's tag (00) swallows DM framing lines ("You're pretty relieved" 28; "Actually, what do you do?" 30). Gouge's decision "I'm going to whistle at them" (16) and "I say, wait" (79) sit under the DM tag (01). Attribute by content.
- **The Message-spell exchange (31–64) is mind-to-mind and one-sided in the transcript.** Folsom drives it (all under 00); Gouge's replies mostly appear under 00 as well ("A good fight…," "What now? We takin' the ship…" are actually Gouge/02 at 40–43, 66–67). Watch the 44–64 stretch: it's Folsom narrating both halves of the telepathic conversation, so several "Gouge" beats are Folsom paraphrasing.
- **Line 5 "Okay, cool Terry."** "Terry" reads as a real player name at the table (Gouge's player), i.e. table talk, not a character — do not introduce a character named Terry.
- **Garbled proper nouns:** "King Toli / Caintoli" → **Cain Toli** (63, 105); "a Toli, a Toli friend" → **Torus** (57); "Rumwood" → the black rum from Port Toli (112); "the phone's under protection" (123) is a mis-transcription of "he's/Folsom's under protection."

## Out-of-band table chatter
Recommended `[out-of-band]` lines/ranges: **4, 5–7, 19–23, 36–38.** (4 "roll your stealth"; 5–7 the stealth roll and the "Terry" table aside "You want high. One plus ten is eleven"; 19–23 the perception check "World perception? Seventeen. Plus three. You know"; 36–38 the rules clarification about the Message cantrip "I can't speak back through messaging / Yes, you can / It's just our minds talking." Folsom's in-character retelling of the escape is left intact.)

## Speaker discontinuities
- 28–30: DM framing under Folsom's tag.
- 44–64: Folsom voices both ends of the telepathic exchange; some "Gouge" lines are Folsom relaying.
- 79: Gouge's "I say, wait" under the DM tag.
