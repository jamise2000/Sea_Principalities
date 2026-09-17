# Cast Mapping — Merrick, Tyrus and Gouge Look for Folsom (6th Wealsun)

`Merrick_Tyrus_and_Gouge_look_for_Folsom_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Merrick, Tyrus, the bar owner (NPC).
**In the room (4 voices):** three players — Merrick, Gouge, Tyrus — plus the DM (narration + voicing the bartender/bar owner and the surviving hired thugs). Folsom is absent this whole scene; he is off with Owen.

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_02** | **The DM** — narration + bar owner/bartender + hired-thug NPCs | Time/logistics rulings; the setting description of Redshore (184–188) | Loot description (10–12), the bartender's "this has been very entertaining… a respectable place" (45–47, 62–63), the thug's "I don't know, he just hired me" (30, 35–43), and all the "you walk five minutes / it's empty" narration. |
| **SPEAKER_00** | **Merrick** (marine; Owen's cousin) | Bleed of the interrogated thug's answers (32, 34 within the "Who hired you?" exchange) | He's the one pushing to find Folsom **and** Owen ("I think we should go find Folsom… and Owen" 130–131); scans the water for Toli ships like a mariner (150–155); asks Gouge what was on the body (102). |
| **SPEAKER_01** | **Gouge** (knife-man / rogue) | — | Loots the dead man and pockets the rapier, dagger and ~50 principality gold (7–27, 107–109); "I sit down and pour an ale" (65); ends by peeling off to "go back by the bar and hide in shadows" (247–260), which sets up the next transcript. |
| **SPEAKER_03** | **Tyrus** (paladin PC — NOT the NPC Torus) | Bleed of a thug's line at 100 ("only worth five silver pieces") | Runs the interrogation and makes the calls ("Make them drop their daggers" 58–59; "Make better choices with your life. Get up and go" 83–84). The DM addresses him directly as Tyrus at 261 ("Tyrus, are you going to stay at the boat?"). |

## Flagged ambiguities (author: please correct)
- **Tyrus (PC) here, never the NPC Torus.** SPEAKER_03 is the paladin PC. The Suel handler Torus does not appear in this transcript.
- **Interrogation bleed at 31–43.** "Who hired you? / That guy. / What guy? / The dead guy." (31–34) is a two-way exchange — Merrick's questions and the thug's answers collapsed under SPEAKER_00. Likewise 35–43 mixes Tyrus's/Merrick's questions with the thugs' replies under 02/03/00. Split by content: the captives say "he just hired me," "same thing," "ten silver coins," "at least we're alive."
- **The tracking banter (161–167) is crossed.** Gouge (01) needles Merrick to "track his footprints… don't you track things?"; the retorts "I wear high heels" (00) and "It's an endogenous cologne, thank you" (167, tagged 01 but clearly the tracker's comeback) are out-of-character table riffing — the perfume/cologne joke is not story dialogue.
- **Line 100** "I can't believe our lives are only worth five silver pieces" reads as one of the released thugs, though tagged to Tyrus (03).
- **Garbled proper nouns:** "principality/Principalities coins" = Sea-Principality gold (18–20, 109–110); "Toli rats" = Torus's Toli hirelings/associates (209–210); "Tim Tufts / three Tufts" appears to be the DM's slang for the hired toughs (70, 126). "Earl of Redshore's castle" (185) is scene-accurate.

## Out-of-band table chatter
Recommended `[out-of-band]` lines/ranges: **104–105, 159–167, 178–179.** (104–105 is the DM's OOC stage cue "Well, role play. Sit down and talk to Gouge"; 159–160 is player meta "he just left a few minutes ago… we have about ten minutes of combat, if that"; 161–167 is the tracking/perfume table banter; 178–179 is travel-time logistics "How long do you want to walk up the dock? Say five minutes." In-character interrogation, the bartender's lines, and the Redshore setting description at 184–188 are left intact.)

## Speaker discontinuities
- 28–43: rapid interrogation cross-talk; questioners and captives share tags 00/02/03.
- 161–167: tracking joke, comeback lands on the wrong tag (167 under 01).
- 100: a thug's line under Tyrus's tag.
