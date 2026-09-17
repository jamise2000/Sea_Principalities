# Cast Mapping — Paul Goes to Fetch the Formula (4th Wealsun)

`Paul_goes_to_fetch_formula_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Paul, Rodiger (NPC, DM-voiced).
**In the room (2 voices):** the player running Paul, and the DM (narrating and voicing the North Gate guard, later named Rodiger).

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_00** | The DM (all narration) | Rodiger / the North Gate guard's in-character dialogue (lines 148–166, 236–246, 290–333); the DM's OOC clarifications | Nearly the whole file is scene-setting/narration and NPC replies. Guard is named Rodiger at line 242. Occasionally a Paul-voiced line lands here as bleed (e.g. 176–186 discussing what to collect). |
| **SPEAKER_01** | Paul Rivero | — | Terse first-person choices and questions consistent with masked, tight-lipped Paul (lines 88–90 on which mask, 143–146, 174–191, 241–246, 297–334). |

## Flagged ambiguities (author: please correct)
- **Tag orientation:** here narration sits on SPEAKER_00 (the reverse of `Paul_hurries_toward_the_fire`, where narration is on SPEAKER_01). Do not carry a fixed tag→person map between files.
- **Dice-roll bleed:** lines 261–263 ("Roll a intelligence check… Uh, 18") — the roll result "18" is Paul's but sits on the DM tag; normal in-combat bleed.
- **Lines 176–186** ("I want to collect anything I have on that powder…"): the ownership of the powder/keg lines flips between tags; treat the collecting decisions as Paul's and the corrections ("You have three kegs") as the DM's.
- **Modern-term slips (author may reword):** 269 "call the fire department" (in-world term elsewhere is "fire brigade"); 306–309 "napalm" (DM characterizing Jude's fireball for the player).

## Out-of-band table chatter
Tagged `[out-of-band]` in the body: **30–38, 261–263, 269, 306–309**.
- 30–38: an intruding real-world side/phone conversation ("They should. It's supposed to… See you then. Okay… Sorry.") that breaks the map description.
- 261–263: dice ("Roll a intelligence check… 18").
- 269: OOC planning aside using a modern term ("call the fire department").
- 306–309: OOC clarification with a modern reference ("napalm").

## Speaker discontinuities
- The guard is anonymous until line 242, where he gives his name as **Rodiger**; all his earlier lines (148 onward) are the same man.
