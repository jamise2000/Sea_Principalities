# Cast Mapping — Merrick, Tyrus and Gouge Look for Folsom (6th Wealsun)

`Merrick_Tyrus_and_Gouge_look_for_Folsom_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Merrick, Tyrus (PCs), the DM, the **bar owner** (NPC), and the surviving **hired thugs** (NPC). Folsom is absent (off with Owen).
**In the room (4 voices):** three players plus the DM (who voices the bartender and the thugs).

## Speaker → character mapping (final, character-locked; crew registry)
Crew registry: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`. NPCs: **bar owner `01B`**, **hired thug(s) `02B`**.

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + adjudication | 83 |
| **SPEAKER_01B** | Bar owner | NPC — wants his "respectable place" back; the Earl will send men | 8 |
| **SPEAKER_02B** | Hired thug(s) | NPC — the interrogated captives ("he just hired me") | 14 |
| **SPEAKER_04A** | Gouge | PC — loots the dead, later peels off to the bar | 50 |
| **SPEAKER_05A** | Merrick | PC — pushes to find Folsom *and* Owen; scans for Toli ships | 51 |
| **SPEAKER_06A** | Tyrus | PC — runs the interrogation (the paladin PC, **not** the NPC Torus) | 63 |

Raw layout: **raw02** = DM + bar owner + thugs; **raw00** = Merrick; **raw01** = Gouge; **raw03** = Tyrus.

## Point of the conversation
After the brawl, the party loots the dead leader (a fine rapier, a dagger, ~50 Sea-Principality gold), interrogates the two surviving thugs — who know only that "the dead guy hired them" for coin (they're **Toli rats**) — tips the bartender ten gold, and lets the captives go. Realizing they were **specifically targeted** (someone paid Toli muscle to beat them in the bar), they set out to find **Folsom and Owen**: searching the night market and docks, Merrick scanning the water for Toli ships, finding no trace. They return to the moored cutter, light lanterns on deck as a signal in case Folsom finds his way back, and split up — **Gouge heads back to the bar to hide in the shadows**, while Merrick and Tyrus stay to guard the boat and the dock. (Sets up *Gouge Waits in the Dark*.)

## Hardest calls / flagged ambiguities (author: please correct)
- **Tyrus (PC), never the NPC Torus** — `SPEAKER_06A` is the paladin; the Suel handler Torus is not in this scene.
- **Split "X says," frames:** the bartender's lines (45, 62) and a thug's line (91) were split off the DM narration frames.
- **Interrogation cross-talk (31–43):** "Who hired you? / That guy. / What guy? / The dead guy." — split into Merrick's questions (`05A`) and the thug's answers (`02B`).
- **Bleed onto the wrong tag:** thug lines that landed on player tags — **70** ("ten silver coins"), **100** ("our lives are only worth five silver pieces") → thug `02B`; and several DM answers that landed on player tags (146, 209 "they're Toli rats", 223, 227) → DM.
- **The split-watch debate (247–256)** is tangled on Gouge's tag: Gouge insisting on going alone vs the others wanting to stay together. I split it Gouge `04A` / Merrick `05A` by content — please scan.
- **204–207** ("Get to the same old fuck… I'm getting laid") reads as garbled OOC banter but wasn't clearly separable — left on Gouge; confirm.

## Game mechanics (attributed, 4 lines) & out-of-band (4 lines)
- `[game mechanics]`: **104–105** (the DM's "well, roleplay it — sit down and talk to Gouge" stage direction) and **178–179** (walk-time logistics — "how long do you want to walk… say five minutes").
- `[out-of-band]`: **160** (meta — "we have about ten minutes of combat, if that") and the **perfume/high-heels tracking jokes** (164, 165, 167). The genuine tracking attempt around them (159, 161–163, 166) is kept in-story.

## Names to normalize in prose
"principality / Principalities coins" → **Sea-Principality gold**; "gold points" (48) → **gold coins**; "Tim Tufts / three Tufts" (70, 126) → the DM's slang for the **hired toughs**; "Toli rats" → **Torus's Toli hirelings**; "sacked outside" (203) → **stacked outside**.

## Speaker discontinuities
- raw02 carries DM + bar owner + thugs; separated by content, with the "X says," frames split.
- Interrogation (28–43) and the split-watch debate (247–256) cross tags.
