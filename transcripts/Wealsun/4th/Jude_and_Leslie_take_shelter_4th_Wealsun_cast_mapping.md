# Cast Mapping — Jude and Leslie Take Shelter (4th Wealsun)

`Jude_and_Leslie_take_shelter_4th_Wealsun.txt` · Book Two (Paul/Jude storyline). Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Jude, Leslie (PCs), the DM, and **Ferd** (NPC — the Blood Alley tavern-keeper/fixer, voiced by the DM).
**In the room (3 diarizer voices):** the DM (narration + Ferd), Jude, and Leslie. This is a very bleed-heavy file — the DM/Ferd share one raw tag and Jude's tag carries a lot of DM/Ferd bleed, so most attributions below are content-separations, not tag reads.

## Speaker → character mapping (final, character-locked; Jude/Paul registry)
Registry: DM `00A`, Jude `01A`, Leslie `03A`. NPC: **Ferd `01B`** (first/only named NPC who speaks).

| Tag | Character | Role | Lines (rp + mech) |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + adjudication + OOC continuity | 71 + 36 = 107 |
| **SPEAKER_01A** | Jude | PC — leads Leslie to ground, works Ferd for information | 141 + 29 = 170 |
| **SPEAKER_01B** | Ferd | NPC — Blood Alley tavern-keeper/fixer; trades gossip on the Toli, Gouge's crew, Owen Black, the bard | 69 |
| **SPEAKER_03A** | Leslie | PC — Albashon's apprentice; shaken after the raid, refuses the poisoned whiskey | 18 + 3 = 21 |

Raw layout: **raw02** = DM **and** Ferd (separated by content); **raw01** = Jude (with heavy DM/Ferd bleed); **raw00** = Leslie.

## Author review corrections applied (round 1)
- Re-tagged to **Leslie `03A`**: 66 ("Cold whiskey"), 86 ("They don't want to smoke"), 88 ("Small hands, good fists"), 98 ("Do I start a benefactor…").
- Re-tagged **113** ("You don't want your wine?") → **Ferd `01B`**; **114** ("Yeah, I need a redeye") → **Jude `01A`**; **251** ("Smuggling… that's how I got into Monmurg") → **Jude `01A`**.
- **276** body changed to "I got plenty of brain cells, but I want more, not less." (Leslie `03A`).
- **Ferd garbles corrected in the body** (author ruling that ASR "her/hers/deferred" = Ferd): **43/44** "hers" → "Ferd's"; **68** "walk in deferreds" → "walk in to Ferd's"; **69** "I nod deferred" → "I nod to Ferd"; **79** "walk up to her" → "walk up to Ferd". (Line **124** "her" left as-is — a real female, the masked attacker.)

## Point of the conversation
~9 p.m. on the **4th of Wealsun**: **Jude** and **Leslie** climb out of the sewers into **Blood Alley** in Monmurg's Foreign District, having just escaped the Scarlet Brotherhood raid. Jude covers their exit and walks Leslie to **Ferd's**, the mercenary tavern where Jude keeps a room. Over drinks, Jude quietly briefs Ferd on the sewer fight (masked attackers — the **Scarlet Brotherhood**) and pumps him for intelligence: Ferd confirms masked figures have been moving through the Warrens, that the thieves'-guild master (**Janice**, eight months in the post) is the man Jude's tasked a rogue contact (**Gregory**) to investigate for Toli/Brotherhood ties, and that **Gouge's crew** and **Owen Black** were in the Harbor District the night a Marine bard sang a politically reckless song admonishing the princes and the Toli. Jude nearly starts a rumor about Toli involvement before the DM notes **Cain Toli isn't common knowledge**, so he holds off. He discovers the tavern's cheap whiskey is literally **poison** (a nerve-deadening brew — Leslie, an alchemist, clocks it and refuses). Jude arranges for Ferd to send word if anyone comes asking, then takes Leslie up to his private room, bars the door and window, and settles in to **trance for four hours** to recover his spells.

## Hardest calls / flagged ambiguities (author: please correct)
- **This whole file is bleed-heavy — please scan the whole thing.** The DM and Ferd share raw02, and Jude's raw01 carries frequent DM/Ferd bleed, so lines were split three ways by content. High-confidence: clear DM narration (00A), Ferd's gossip (01B), Leslie's few lines (03A). Lower-confidence fillers ("Okay," "Yeah," "Gotcha") were assigned to the likeliest speaker in each exchange.
- **Ferd `01B` is my read of the tavern-keeper.** The `.lst` cast lists him (`*Ferd`); I attributed all the in-scene gossip about the Toli, Gouge, Owen Black and the bard (roughly 140–261) to Ferd. Some of those beats could be the DM narrating rather than Ferd speaking — please confirm the DM/Ferd line.
- **Line 82** "I got the oven started, Jay" — attributed to Ferd `01B` (a greeting to "Jay"/Jude); could be table chatter. Verify.
- **Leslie's naive question (93–94)** "Can you define a mercenary? / A mercenary is somebody that is paid to fight." — kept in-story (Leslie `03A` / DM `00A`); it may instead be an out-of-band player clarification. Your call.
- **OOC name-slip (297):** "I can't remember what **Paul's** main mask was" — the player names Paul out-of-character; in-world Jude only knows him as **the masked man**. Tagged `[game mechanics]`; the DM's answer about the mask habits (298–301) is the OOC continuity reply. Don't let "Paul" leak into Jude's in-scene dialogue in prose.
- **Split candidate (336):** "Jude says, I need a trance." is a DM frame + Jude quote on one line — left merged (1:1 with the raw) so the numbering matches your review; split into a `00A` frame + `01A` line if you want.
- **Environmental color on Jude's tag (319–320, 335):** the vomit/bloodstain description and "As Jude lights the lantern" sit on raw01 but read as DM scene-setting → `00A`. Could be Jude's player narrating. Verify.

## Game mechanics (68 lines) & out-of-band (4 lines)
- `[game mechanics]` (OOC table talk, attributed to A-tags): **21–33** (examining the DM's district **map**); **80–81** (perception die); **145–168** (OOC **continuity** recall — the Gregory/Janice tasking, dates); **186–192** (the DM's OOC caution that starting a Toli rumor risks in-game knowledge — "Cain Toli isn't common knowledge"); **264–266** (con check on the poison drink); **297–301** (the OOC mask recall); **340–350, 353–355** (spell/cantrip and trance-timing bookkeeping). Note **145–168** is a real plot thread delivered as OOC recall — flagged so you can pull any of it back into prose.
- `[out-of-band]` (raw tag kept): **316–317** ("Hotel 6" modern-reference joke + "I don't think he gets the reference"); **370–371** (the DM's "housekeeping stuff we should talk about" — OOC session admin at the scene's end).

## Names / garbles to normalize in prose
- **"Blood Alley"** and **"Murder Alley"** — the two alleys by the tavern (Blood Alley being "the better of the two").
- **"Janice" (157)** → the **thieves'-guild master** ("Janice" is the ASR rendering of his name; eight months in the post — author to confirm the canonical spelling).
- **"Gregory" (146)** → Jude's **rogue contact**, tasked on the 2nd, due to report back on the 7th.
- **"Black Owen" (243)** → **Owen Black** (Ferd corrects it in-scene at 244).
- **"her" / "hers" / "deferred" / "deferreds" → Ferd / Ferd's** (author ruling; corrected in the body at 43, 44, 68, 69, 79). The ASR repeatedly renders the tavern-keeper's name as these words. Line **124** "her" is the exception — a real female (the masked attacker) — left unchanged.
- **"the Duke of the Parkhouse" (216)** → likely the **Duke of Berghof / Plar of Hokar** (ASR garble; cf. `Name_Normalization_Key.md`).
- **"Medio Jungle" (71)** → **Amedio (Jungle)**; **"Hul Marshes" (71)** → **Hool Marshes**.
- **The masked man Jude references (296–301)** = **Paul** (his identity is concealed in-world; keep it "the masked man" in Jude's dialogue).

## Speaker discontinuities
- raw02 carries the DM **and** Ferd throughout; separated by content (DM = narration/adjudication/OOC; Ferd = in-scene tavern dialogue).
- raw01 (Jude) repeatedly carries DM answers and Ferd replies (e.g., 41, 55, 73/75, 114, 126, 137, 140, 170, 174, 244, 288, 291, 305).
