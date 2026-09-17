# Cast Mapping — Owen and Torus Plan (6th Wealsun)

`Owen_and_Torus_plan_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** the DM, Owen Black (NPC), Torus (NPC). No player is present — this is a DM interlude bridging Folsom's escape and the party's next scene.
**In the room (1 raw voice):** the DM alone, narrating and voicing both NPCs. The single diarizer tag has been separated by content into DM narration + Owen's and Torus's quoted dialogue.

## Speaker → character mapping (final, character-locked)
DM `00A`, Owen Black `01B`, Torus `02B` (same NPC numbering as *Owen Shows His Face*).

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + Torus's closing interior monologue | 26 |
| **SPEAKER_01B** | Owen Black | NPC — his confession and the "let the Earl handle it" plan | 29 |
| **SPEAKER_02B** | Torus | NPC — his questions and reproaches | 10 |

The whole file was one diarizer tag (raw00 = DM). Quoted dialogue was split off onto the NPC tags; the DM's "X said," frames were split into their own `00A` lines (per the author's stated preference), and **Torus's closing interior monologue (52–65) stays DM narration `00A`** — it is narrated thought, not spoken dialogue.

## Point of the conversation
As Folsom flees, **Owen** — who caught his own "special draught" (the **gift of Insamiar**) in the eye, having meant only to knock Folsom out for the trip to Cain Toli's island — confesses to **Torus** and, feeling the poison take hold, refuses to give chase. His plan: don't deal with it themselves — tip their contact with the **Earl of Redshore** (with coin) that there are Monmurg smugglers in town, hand over the sloop's location, and let the Earl's men (and maybe the Navy) run them down; "it's out of our hands." Owen lies down, out for ~8 hours. **Torus's interior monologue** closes the scene: Owen is near the end of his usefulness — the gift of Insamiar will consume him (he'll crave it, become useless as a servant) — but keep him alive for now; his Redshore idea is sound. Let **Redshore and Jamis** believe each other enemies, both being manipulated — neither realizing how far. **Torus is the manipulator playing both sides.**

## Flagged ambiguities (author: please correct)
- **Split "X said," frames.** The DM's narration frames (6, 8, 10, 17, 22, 43 in the original) were split from the quotes they introduce; the quotes go to Owen/Torus. Line 8's frame ("Owen said, well, and Torus continued,") keeps Owen's aborted "well" inside the DM frame — if you want that as an Owen line, say so.
- **Interior monologue = DM.** 52–65 (Torus's thoughts) are tagged `00A` as narrated interior monologue, matching how *Owen's Suspicions* was handled; flip to `02B` only if you want interior thought voiced as NPC dialogue.

## Worldbuilding / canon note
The **"gift of Insamiar"** (the "special draught"/"poison" Owen used) reads here as an **addictive drug** — it consumes those exposed, who come to crave it. This ties to the **Followers of Insamiar** referenced earlier in the series. **Not yet in `Name_Normalization_Key.md`** — recommend adding an entry (the gift/Blessing of Insamiar + the Followers of Insamiar).

## Out-of-band / game mechanics
**None.** Pure DM narration and quoted NPC dialogue — no dice, mechanics, or real-table talk.

## Names to normalize in prose
"Kane-Toli's island" (11/15) → **Cain Toli**; "Jameis" (58) → **Jamis**; "Red Shore" (58) → **Redshore**; "Redshore's minute arms" (55) → **armsmen / minute-men**.

## Speaker discontinuities
- Originally one diarizer tag; separated by content. Numbering differs from companion files (DM = raw00 here).
