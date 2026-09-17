# Cast Mapping — Owen Shows His Face (6th Wealsun)

`Owen_shows_his_face_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Folsom (PC), the DM, Owen Black (NPC), and **Torus** (NPC — Cain Toli's Suel handler; *not* the PC Tyrus).
**In the room (2 voices):** Folsom (his player) and the DM (narration + voicing Owen and Torus). No other player is present — this is Folsom alone, walked into a trap.

## Speaker → character mapping (final, character-locked)
Crew registry: DM `00A`, Folsom `07A`, Owen Black `01B`. Torus is the scene's second NPC → **`02B`**.

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + combat adjudication | 161 |
| **SPEAKER_01B** | Owen Black | NPC — springs the trap, reveals the betrayal | 43 |
| **SPEAKER_02B** | Torus | NPC — Cain Toli's Suel handler in the cabin | 18 |
| **SPEAKER_07A** | Folsom | PC — the whole scene from his POV; blinds Owen and escapes | 147 |

Raw layout: **raw00** = Folsom; **raw01** = DM **and** Owen **and** Torus (separated by content). Owen (`01B`) and Torus (`02B`) both live on raw01 with the DM.

**Author review applied (2nd pass).** Owen credited for "I have a friend watching it" (37), "I've got a bottle" (49), "Here, take a seat" (64), "First a drink" (134) — each **split** off the DM narration (5 splits total, later line numbers shift). **Torus** credited for "I'll light a lantern" (65), "It's there / Drink it" (158–159), and the knife line "We're being friendly here, not kind" (156 split). 116 → "Cain Toli"; 120 and 162 lines extended; 163 → Folsom, 166 → DM; 181 toast fixed ("…Here's rum in your eye!").

## Point of the conversation
Owen walks Folsom down the Redshore docks and lures him aboard a sloop he calls "**Tyrus's new boat**" — into a cabin where **Torus**, a Suel man working for **Cain Toli**, is waiting. Owen drops the friendly act: Folsom is to be **Cain Toli's prisoner** (Owen is "being paid very well"), Merrick and the others "won't be alive much longer," and Owen "feels bad about Tyrus." Torus quizzes Folsom about the artifact — the **Orb**, made by the lich **Acerak**, that Cain learned of from the swamp necromancer — and produces manacles. Folsom stalls for a drink, then **hurls the shot of black rum into Owen's eye to blind him**, draws his rapier, stabs Torus across the table, and bolts. Owen yells "stop him!"; Torus gives chase with a knife; Folsom wounds him again (rapier + Vicious Mockery) and escapes down the docks, running back toward the Chart Room — slowing as he nears, dreading he'll find his friends dead. **This is Owen's on-page betrayal.**

## Hardest calls / flagged ambiguities (author: please correct)
- **Torus (NPC) vs Tyrus (PC) — homophone.** Kept disambiguated: **Torus** = the Suel handler in the cabin (`02B`, lines 43–44, 77–78, 88–92, 97–98, 101, 127–128, 156). **Tyrus** = the paladin PC, referenced but absent (the "new boat," "wait for Tyrus," Owen's "I feel bad about Tyrus," Folsom's cover "Tyrus is a good friend of mine"). Do not let a later pass merge them.
- **19–20 crossed voices:** 19 "Really?" is Folsom (on the DM tag); 20 "Yeah" is Owen (on Folsom's tag).
- **102** "Folsom goes, I mean not Folsom, Owen Black says…" — a DM self-correction; the speaker is **Owen** (`01B`).
- **115–117** ("I'm being paid very well… Cain Toli would find you entertaining") — assigned to Owen; could be Torus. Verify.
- **Combat bleed (186–350):** player action-declarations and DM rulings cross tags; attributed by content.

## Game mechanics (attributed, 146 lines)
The perception/insight check (58–62), table positioning/room-layout (137–149), the drink-glass/flammability planning (163–166, 171–178), and the whole fight's dice — the eye-throw to-hit/blind rolls (186–194, 197–199, 202–215), the rapier attack (223–247), movement/escape logistics (250–298, 308–313), Vicious Mockery rolls (317–348). DM instructions/results → `00A`; Folsom's rolls → `07A`.

## Out-of-band (raw tags kept, 9 lines)
**21** ("Was it pre-established that you bought Tyrus a new boat?" — OOC continuity check), **122–124** ("Manacles are like cuffs" vocabulary aside), **303–307** ("I'm just grabbing my beer and my cake… I'm gonna drink the tank" — real-table chatter).

## Names to normalize in prose
"a soul" (69) / "Asul" (156) / "Toli reaches down" (121) → **Torus** (a Suel man); "Portoli" (50, 74) → **Port Toli**; "Kane/Cain/Keoland totally" (76, 112, 116) → **Cain Toli**; "the stone" (87) → **the Orb**; "the Lich Azorak" (89) → **Acerak**; "Owen Blackwell" (181) → **Owen Black**.

## Speaker discontinuities
- raw01 carries DM, Owen, and Torus with no tag change; 19–20 cross with Folsom.
- Dense DM↔player bleed through the fight (186 onward).
