# Cast Mapping — Paul Organizes the Guards (4th Wealsun)

`Paul_organizes_guards_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Paul, Rodiger (NPC, DM-voiced), the sergeant / Sergeant Holt (NPC, DM-voiced).
**In the room (2 voices):** the player running Paul, and the DM (narrating and voicing Rodiger and Sergeant Holt of the Harbor District marines).

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_00** | The DM (all narration) | Rodiger's dialogue (4–7, 16, 18–27), Sergeant Holt's dialogue (47–54, 121); Paul-voiced orders bleed in too (e.g. 17 "Contain the flames right now") | Scene narration, the runner-for-marines beat, and both NPC officers are on this tag. Holt names himself line 47. |
| **SPEAKER_01** | Paul Rivero | The DM's map-setup and a dice prompt bleed in (101–105, 137–142) | Paul's commands to contain the fire and lead the strike force (8–15, 55–59, 72–75, 124–133); the mask-showing order (132) is unmistakably Paul. |

## Flagged ambiguities (author: please correct)
- **Heavy two-way bleed.** Paul's orders sometimes sit on SPEAKER_00 (17, 60–61) and the DM's prompts sometimes sit on SPEAKER_01 (101–105, 137–142). Assign by content, not tag.
- **Two NPC officers share SPEAKER_00:** Rodiger (North Gate) vs. Sergeant Holt (Harbor District marines, arrives ~46). Keep them distinct — Holt leads the marines in; Rodiger's men contain the fire.
- **Modern-term slip:** 39–41 an OOC joke ("giant bowl of sulfur… ended up for snorting") comparing the alchemist's chemicals to drugs; author should cut or restyle.
- Line 25 "Harbor Gate… squad of Marines" appears on SPEAKER_00 but is Paul/Rodiger relaying the order — a bleed.

## Out-of-band table chatter
Tagged `[out-of-band]` in the body: **40, 101–105, 137–142**.
- 40: OOC drug-joke aside ("ended up for snorting").
- 101–105: dice ("Do an int check… Uh, that's gonna be 16").
- 137–142: battle-map/token setup ("I'll do an X for them… you'll be a triangle… these dashes… walls that are collapsed").

## Speaker discontinuities
- **Sergeant Holt** enters at line 46–47 and is a new NPC on the SPEAKER_00 tag, distinct from Rodiger who has held it up to that point.
