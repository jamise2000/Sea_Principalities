# Cast Mapping — Paul and Marines Capture the Suspects (4th Wealsun)

`Paul_and_marines_capture_suspects_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.** **This is a COMBAT transcript — the bulk of it is dice and grid mechanics.**

**Cast (index):** Paul, Sergeant Holt (NPC, DM-voiced), the Scarlet Brotherhood agents (NPCs, DM-voiced — two masked men and the woman).
**In the room (2 voices):** the player running Paul, and the DM (narrating, running all the marines/enemies, and voicing Sergeant Holt).

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_01** | The DM (all narration + combat calls) | Sergeant Holt's dialogue (19–22, 551, 590–616), the enemies' shouts ("It's the young prince!" 40), the mask/snake-eye reveal narration (561–574) | The overwhelming majority of the file is the DM calling attacks, damage, and movement, and narrating the fight. |
| **SPEAKER_00** | Paul Rivero | Paul's own dice results; his orders ("Take him alive," "I want her alive"); OOC excitement | First-person orders and rolls (18, 103, 123–124, 193, 265, 335, 449–451). Note dice bleed both directions throughout. |

## Flagged ambiguities (author: please correct)
- **Do not mine this file for character voice** — it is ~90% mechanics. The story content is thin and lives in the beats listed under out-of-band.
- **The captured woman and the two men are all DM-voiced on SPEAKER_01** and barely speak; author supplies their characterization from the reveal (563–574: fang-like teeth, vertical slit "snake eyes" — explicitly likened to **Jude**, line 572).
- **"Romero" (line 530)** — the sergeant calls Paul "Romero"; almost certainly a misspeak/garble for **Rivero**. Flag for correction.
- **Modern drug slang in narration/asides (author reword):** 320 "You guys are coked up," 634–635 "meth heads," and 28 "a bunch of methods" (garble). These describe the addicted occupants; keep the imagery, drop the modern words.
- Line 78 "I gotta start recording this stuff" is a real-world meta remark by the DM.

## Out-of-band table chatter
The fight's **dice and grid mechanics run from ~46 to ~546 and are tagged `[out-of-band]` throughout**, EXCEPT the in-story beats, which are left untagged:
- **In-story beats (NOT tagged):** 79–85 (bolt hits the arm, black blood), 103 (take him alive), 119–124 (the woman with the dagger; kill/keep-alive orders), 156 (she draws the scimitar), 170 (scimitar across Paul's shoulder), 193–197 (take her alive), 223–225 (a marine's throat cut), 316–329 (the tough, hard-to-kill man), 353 (shoved back with a shield), 374–377 (Paul stumbles and falls), 393 (Paul knocks her blade away), 441–442 & 444–445 (marines dogpile the man), 471 (short-sword to the chest, "give up"), 475–480 (her strikes turned by scale mail), 529–530 (Holt: "Knock her out").
- **Closing scene 547–636 is NOT tagged** (mask/snake-eye reveal, securing prisoners, thanks to the marines, Helm's Island exchange, leading out).
- **Also explicitly tagged out-of-band inside the above:** 78 (meta "start recording"), 443 (TV reference, "Like they do in *The Harbinger*").

## Speaker discontinuities
- Sergeant Holt (from `Paul_organizes_guards`) continues on SPEAKER_01 alongside DM narration; the enemy that is unmasked at 561–574 is one of the two Scarlet Brotherhood men.
