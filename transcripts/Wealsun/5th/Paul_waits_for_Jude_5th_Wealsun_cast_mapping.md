# Cast Mapping — Paul Waits for Jude (5th Wealsun)

`Paul_waits_for_Jude_5th_Wealsun.txt` · Book Two (Paul/Jude storyline). Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Ambiguities flagged below for author correction.

**Cast (index):** Paul (PC), the DM, a **palace guard** (NPC) and the **servant** who announces Jude (NPC).
**In the room (2 diarizer voices):** the DM (narration + the guard + the servant) and Paul. Just past midnight into the small hours of the 5th of Wealsun.

## Speaker → character mapping (final, character-locked; Jude/Paul registry)
Registry: DM `00A`, Paul `02A`. NPCs by appearance: **palace guard `01B`** (speaks first, line 82), **servant `02B`** (announces Jude, 114+).

| Tag | Character | Role | Lines (rp + mech) |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + adjudication + voices the guard/servant frames | 56 + 5 = 61 |
| **SPEAKER_02A** | Paul | PC — jails the prisoners, sets the watch, interrogates, hunts a torture manual | 53 + 1 = 54 |
| **SPEAKER_01B** | Palace guard | NPC — "Where should we put them, sir? / Back in the Warren?" | 2 |
| **SPEAKER_02B** | Servant | NPC — announces Jude's arrival | 4 |

Raw layout: **raw00** = DM (+ guard + servant); **raw01** = Paul. Moderate bleed both ways on short lines (Paul's answers landing on the DM tag and vice versa) — separated by content.

## Point of the conversation
Back at the palace after the raid, **Paul** has the captured suspects locked up — each isolated, the two dangerous ones (the violent, hooded Scarlet-Brotherhood pair) in the most secure cells, watched by **five armed guards** with crossbows. He decides to **stay put and wait for Jude**, sending a runner to the north gate to bring Jude to him if he appears. Meanwhile he goes down to interrogate the **six captives found non-responsive on the floor** — malnourished, incoherent, "as if dreaming"; nothing coherent comes out except one who looks up and mutters **"the dragon, the dragon"** before slipping under again. Judging them a waste, Paul has them **released** ("catch and release") — dumped back in the Warren or at the north gate — and keeps the dangerous two for later ("I gotta cook something up for them"). He heads to his study/library and digs up a **book on torture** to prepare. As he's reading, the **servant** knocks: **Jude has arrived** at the front gates and wants to talk — setting up the next scene.

## Hardest calls / flagged ambiguities (author: please correct)
- **NPC numbering by appearance:** the **guard** (82, 84) speaks before the **servant** (114–119), so guard = `01B`, servant = `02B` — even though the `.lst` names only `*servant`. Renumber if you'd rather the named servant be `01B`.
- **Line 84** "Back in the Warren?" — read as the guard confirming the drop-off (`01B`); could be Paul. Verify.
- **Embedded NPC mutter (74):** "…one of the guys looks at you and goes, **the dragon, the dragon**, and falls asleep again" is kept inside the DM's narration (`00A`); split the mutter onto a prisoner B-tag if you want it as spoken dialogue.
- **Split candidates left merged** (1:1 with the raw for review): **26** ("Are they the Marines, or is it… No, the Marines basically transfer them up" — Paul's question + DM's answer on one line); **44** ("If they look at you funny, just go ahead and… Alright, so it's pretty late" — Paul's order + DM transition).
- **67** "Do you want to burn them?" — attributed to the DM (`00A`) prompting Paul on how far to go; could be Paul musing. Verify.

## Game mechanics (6 lines) & out-of-band (4 lines)
- `[game mechanics]`: **120–125** — OOC staging clarification about which room Paul is in ("Am I in the library or are you there? / The study / which is kind of a library / it has a library"). Attributed to Paul `02A` / DM `00A`.
- `[out-of-band]`: **110–113** — modern-reference joking about the torture book ("A Noob's Guide," "Torture for dummies"). The book itself is a real in-story item (established at 98–102, 106–109); only the joke names are OOC. Raw tags kept.

## Canon / continuity notes
- **The "dreaming" captives + "the dragon" (16–22, 61–63, 74):** the six non-responsive prisoners are drug-addled and dreaming — this strongly reads as the **Insamiar drug-rite** (the addictive black-dragon "Blessing"/"gift of Insamiar"; cf. `worldbuilding/Insamiar_the_Black.md`). One muttering **"the dragon"** ties the Scarlet-Brotherhood raiders to that cult/drug. Flagged for the author as a likely Insamiar thread.
- **"methed out" (60)** and similar — Paul's modern phrasing for the drugged state; normalize to "**drugged / drugged senseless**" in prose.

## Speaker discontinuities
- raw00 carries the DM plus both NPCs (guard, servant); raw01 is Paul, with the usual short-answer bleed onto the DM tag (e.g., 3, 6, 55, 66, 80, 83).
