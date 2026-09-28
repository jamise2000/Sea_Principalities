# Cast Mapping — Passage through the Dragon Isles (5th Wealsun)

`Passage_through_Dragon_Isles_5th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Folsom, Tyrus, Gouge, Merrick (PCs), the DM, and Owen Black (NPC, DM-voiced).
**In the room (5 voices):** the four players plus the DM (who narrates and voices Owen). **This is the hardest file in the set** — the diarizer smeared the long Owen↔Folsom interview and the Owen↔Merrick water/route discussion across single tags, and Merrick lands in two raw tags (00 and 02), Folsom in two (04 and 03).

## Speaker → character mapping (final, character-locked; crew registry)
Same crew registry as the other 5th/6th-Wealsun files: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`, Folsom `07A`, Owen Black `01B` (NPC).

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration / adjudication / reading Merrick's book aloud (454–459) | 200 |
| **SPEAKER_01B** | Owen Black | NPC — storytelling, the interview, the dragon reveal | 185 |
| **SPEAKER_04A** | Gouge | PC — the ship-chase money angle; wakes Folsom | 100 |
| **SPEAKER_05A** | Merrick | PC — helm all night, decides to pass the Dragon Isles, examines the water | 197 |
| **SPEAKER_06A** | Tyrus | PC — spots the Sea Ghost, wakes the crew | 58 |
| **SPEAKER_07A** | Folsom | PC — the charm offensive, pumping Owen for lore | 144 |

Raw diarizer layout: **raw01** = DM narration **and** Owen Black (the primary voice); **raw00** = Merrick (heavy Owen bleed in the water talk); **raw02** = Gouge (heavy Merrick bleed 257–313); **raw03** = Tyrus (Folsom bleed at 594, 793–795, 816); **raw04** = Folsom.

## Point of the conversation
On the 5th, sailing toward Redshore, **Folsom works Owen for lore** while the others sleep: Owen recounts escaping Apple Yard Keep with bugbear mercenaries of the **Sons of Olan** cult, and that the necromancer **Ixid** ("Exit") traded **Cain Toli** the location of an ancient artifact. At dawn **Tyrus spots the Sea Ghost** — Cain's impossibly fast cutter — sailing east, off the shipping lanes; Merrick, now awake, notes its heading but decides not to tail it. Recalling the book Merrick took (read aloud, the **Pocra Sententia** / yellow-white anti-sahuagin-powder passage), the crew connects Cain to a huge powder store on his fortress-island. Merrick then insists on **sailing right between the Dragon Isles** — unheard of in 150 years — because they're eerily silent (no turtle-dragon roaring, in mating season). The water shows no sign of the powder, so that's not why the dragons are gone. In the **payoff**, a nat-20 charm from Folsom gets Owen to reveal the secret: the artifact is a device that **controls the turtle dragons**, made by a lich called **Acerak** ("Aserach" — i.e. Ujor Udias; canon: the **Orb of the Dragon Turtle**), and **Cain Toli is using it to pull the dragons off the isles for his own purposes** — possibly to pin down the Monmurg fleet.

## Canon confirmed (per `Name_Normalization_Key.md`)
The artifact = the **Orb of the Dragon Turtle** (made by **Acerak** = Ujor Udias); **Ixid**, necromancer of the **Sons of Olan**, told Cain where it lay; **Pocra Sententia** = Cain's fortress-island and the powder staging ground. This transcript is the on-page reveal that the Orb **controls turtle dragons** and answers *why the Dragon Isles fell silent*.

## Hardest calls / flagged ambiguities (author: please correct)
- **The Owen↔Folsom interview (≈34–188, 800–894) is dense bleed on raw01.** Owen's substantive lines → `01B`; Folsom's questions/reactions ("Really?", "Interesting", "Held in Apple Yard Keep?") → `07A`; DM narration → `00A`. Many one-word reactions are best-guess — please scan.
- **The Sea-Ghost / route / water discussion (≈257–370, 464–570, 656–704) mixes Merrick (00A) and Gouge (04A), with Owen (01B) answering and the DM (00A) on the map.** Merrick vs Gouge on the shared raw02 tag is the shakiest call — verify 291, 312–313, 460–465, 548–558.
- **Owen bleed onto Merrick's raw00 tag:** 153, 279–280, 282, 293, 323, 331–334, 340–341, 344, 350, 625, 643–644, 709, 719–720, 722 read as Owen despite the tag.
- **Line 94 "I'm still sleeping, right?"** — resolved to **Merrick** (in-band, `05A`) per author; was mis-tagged out-of-band.
- **Untagged lines resolved by context:** 244 → Gouge (grunt as Tyrus wakes him), 385 → Merrick, 453 → DM (into the book reading).
- **656 "I look at the water"** — a Merrick action that sat on the DM/Owen tag; moved to `05A`.
- **Names to normalize in prose:** "Whalesun" → **Wealsun**; the many "Kane Tolley / Caintoli / Cain Tole / Kane totally / King Toli / Keitoly" → **Cain Toli**; "Aserach" → **Acerak**; "Exit" → **Ixid**; "Sacknon Toli" → **Sacnon Toli**; "Selenmore" → **Selinmore**; "sahagin" → **sahuagin**; "Azur Sea" → **Azure Sea**; "Seaghost/seagulls" → the **Sea Ghost**; "Hula Martian" → **Hull Marshes**; "Berghoff/Berkhoff" → **Berghof**.

## Game mechanics (attributed)
`[game mechanics]` (60 lines): **124–134** (Folsom's charisma/persuasion check on Owen's story), **149–151** (map-pointing "Right here, Cain?"), **213 & 217–219** (Tyrus's perception check on the sighted ship), **396–418** (Merrick's int-check block, with table ribbing), **469** (a DC "higher than my 12"), **758–769** (inventory reconciliation of who holds the powder — vial vs packet), **846–851** (Folsom's nat-20 persuasion that unlocks the dragon reveal). DM instructions/results → `00A`; each roll → the roller (Folsom `07A`, Tyrus `06A`, Merrick `05A`, Gouge `04A`).

## Out-of-band (raw tags kept, 10 lines)
**6** ("I'm Danny" — real name), **470–474** (the healing-potion **prop** turning white-to-red + "I had to drain the tank"), **476–479** ("What is red? / Cherry juice…" — the drink/prop). All real-world/prop/table asides.

## Speaker discontinuities
- raw01 carries **DM narration and Owen** with no tag change (densest in the interview and the dragon reveal).
- **Merrick spans raw00 and raw02**; **Folsom spans raw04 and raw03**; **Gouge's raw02 absorbs Merrick** through the ship-sighting block.
