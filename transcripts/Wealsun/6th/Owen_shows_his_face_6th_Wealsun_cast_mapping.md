# Cast Mapping — Owen Shows His Face (6th Wealsun)

`Owen_shows_his_face_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Folsom, Owen Black (NPC), Torus (NPC).
**In the room (2 voices):** Folsom (his player, in-character + OOC asides) and the DM (narration + voicing Owen Black and the NPC Torus). No other player is present — this is Folsom alone with Owen, walked into a trap.

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_01** | **The DM** — narration, plus Owen Black (IC) and Torus (IC) | Combat/dice mechanics; occasional bleed of Folsom's player (e.g. 225 "I pull out my rapier", 234 "I want to attack him") | Carries all the docks/cabin narration (1–74), Owen's dialogue ("This is Tyrus' new boat" 17–18; "first a drink" 134), Torus's dialogue (77, 88), and every DM prompt/roll call. |
| **SPEAKER_00** | **Folsom** (his player) — in-character dialogue + out-of-character table talk | Bleed of DM lines during combat (e.g. 293 "Do you want to try and get away?", 342–343 action-economy rulings) | The nervous replies to Torus about the artifact (79–86, 93–96), "I appreciate that, Owen. Tyrus is a good friend of mine" (109–110), and the whole escape sequence in first person. Also all the "roll/dex bonus/is it an action" asides. |

## Flagged ambiguities (author: please correct)
- **Torus (NPC) vs Tyrus (PC) — homophone trap.** This transcript's body has been hand-disambiguated per `worldbuilding/Name_Normalization_Key.md`. **Torus** is the Suel man in the cabin (Owen's Toli handler): lines **41, 54, 75, 77, 88, 101**. **Tyrus** is the paladin PC, referenced but not present: the new boat Owen procured (**17, 18, 21**), the crew/party they should "wait for" (**28**), Owen's regretful "I do feel bad about Tyrus… he was a good friend" (**106**), and Folsom's cover line "Tyrus is a good friend of mine" (**110**). Do not let a later pass re-merge these two names.
- **Tag swap at 19–21.** 19 "Really?" (tag 01) is Folsom reacting; 20 "Yeah." (tag 00) is Owen answering — the two voices are crossed here. 21 "Was it pre-established that you bought Tyrus a new boat?" is the player asking the DM (pure OOC), captured under Folsom's tag.
- **Combat bleed both directions.** Through the fight (186–350) player action-declarations land under the DM tag (225, 234) and DM rulings/prompts land under Folsom's tag (293, 342–343). Attribute by content, not tag.
- **Garbled proper nouns to normalize in prose:** "Kane/Cain/Keoland totally" → **Cain Toli** (76, 112, 116); "Portoli" → **Port Toli** (50, 74); "the stone" → **the Orb** (87–88); "the Lich Azorak" → **Acerak** (89); "this dude is a soul" / "Asul" / "the Toli" → **Torus, a Suel man** (69, 121, 156). Line 102 also stumbles ("Folsom goes, I mean not Folsom, Owen Black says…") — the speaker is Owen.

## Out-of-band table chatter
Recommended `[out-of-band]` lines/ranges: **21, 58–62, 122–124, 137–149, 163–166, 171–178, 186–194, 197–199, 202–215, 223–224, 230–232, 236–247, 250–263, 265–281, 289–298, 303–311, 313, 317–318, 321–333, 335–337, 340–348.** (Perception/insight and initiative calls and their dice results; d20/attack/damage rolls and dex/charisma-bonus math; saving-throw and blind-duration rolls; action-economy rulings — "it's an action," "you've already done a cantrip," Vicious Mockery action vs bonus action; grid movement counting and table-position/reach logistics; the "manacles are like cuffs" clarification; and pure real-table chatter at 303–307 — "I'm just grabbing my beer and my cake … Actually I'm gonna drink the tank." Owen's IC dialogue, Torus's IC dialogue, and DM narration are left intact even where the tag is wrong.)

## Speaker discontinuities
- 19–21: voices crossed (Folsom under 01, Owen under 00) before settling.
- 186 onward: dense interleave of dice/tactics with IC action; player and DM lines repeatedly cross tags for the rest of the fight.
