# Cast Mapping — Jude and Paul Interrogate Prisoners (5th Wealsun)

`Jude_and_Paul_interrogate_prisoners_5th_Wealsun.txt` · Book Two (Paul/Jude storyline). Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Ambiguities flagged below for author correction.

**Cast (index):** Jude, Paul, Leslie (PCs), the DM, the **jailer/guards** (NPC), and the **female Scarlet-Brotherhood prisoner** (NPC). A **male prisoner** is present but (see flags) may not speak.
**In the room (4 diarizer voices):** the DM (narration + jailer + prisoner), Jude, Paul, Leslie. 2 a.m., 5th of Wealsun, the dungeons under Monmurg Palace. Bleed-heavy on the Jude/Paul/Leslie tags — separated by content.

## Speaker → character mapping (final, character-locked; Jude/Paul registry)
Registry: DM `00A`, Jude `01A`, Paul `02A`, Leslie `03A`. NPCs by appearance: **jailer/guard `01B`** (56), **female prisoner `02B`** (65).

| Tag | Character | Role | Lines (rp + mech) |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + adjudication + voices the jailer and prisoners | 61 + 4 = 65 |
| **SPEAKER_01A** | Jude | PC — leads the interrogation; milks the fang-venom for the poison | 93 |
| **SPEAKER_02A** | Paul | PC — recounts the capture; helps direct; owns the torture book | 21 |
| **SPEAKER_03A** | Leslie | PC — eccentric; argues about "slaves/workers/test subjects" | 11 |
| **SPEAKER_01B** | Jailer / guard | NPC — reports the prisoners' strange language; fetches the man-catcher | 3 |
| **SPEAKER_02B** | Female prisoner | NPC — "You've failed, you foolish elf" (in Ancient Suel) | 1 |

Raw layout: **raw00** = DM (+ jailer + prisoner); **raw01** = Jude; **raw02** = Paul; **raw03** = Leslie. Short-line bleed across the PC tags throughout.

## Point of the conversation
At 2 a.m., Jude, Paul and Leslie descend to the palace dungeon, where five wary guards hold two captured "Scarlet Brotherhood" agents behind bars — but in the torchlight Jude sees they've been **transformed**: fangs, slit snake-eyes, the beginnings of scales. The DM (via Jude's knowledge check) identifies them as **the Yuan-ti** ("the transformed") — people turned into snake-minded slaves by **transmuters from the east**, creatures Jude's late master **Albashon** had described. The female prisoner spits a curse in **Ancient Suel** ("You've failed, you foolish elf"). Paul recounts how he tailed and apprehended them; Jude, reasoning their fangs hold the poison, has the jailer wrangle the **male** first with a **man-catcher** pole, chains him, and — in a bare room with a drain — pries his jaws open and **milks a pale-green venom into sample vials**. (Leslie, sidelined, riffs about keeping them as "workers/test subjects" and watches from the corner.) This gives Jude a working sample of the toxin tied to the alchemist's murder.

## Hardest calls / flagged ambiguities (author: please correct)
- **Does the male prisoner speak? (70)** "The alchemist is dead." — I attributed it to **Jude `01A`** (taunting the male, then asking "is he tracking?"), but it may be the **male prisoner** taunting (parallel to the female's line 65). If so, give the male his own NPC tag (`03B`). Your call.
- **Bleed on the PC tags:** the slaves/workers/test-subjects argument (105–121) and several short answers swap between Jude, Paul and Leslie. Assigned by content — please scan.
- **Combined frame+quote lines** kept on the NPC tag (split candidates): **56** ("The guard … goes, They speak some language…"), **65** ("She says, You've failed…"), **129** ("…the jailer says, I know just this thing…").
- **Garbled table cross-talk (174–179):** "…so not as many as he shackled a manapal… Wait, I'm shackled? No, not here. He's all, wait, wait. … I was planning." — messy; kept on Jude `01A` except **178** "Dude, wake up" (out-of-band). Verify.
- **Male-first vs female-first (132–141)** is all on Paul's tag with a self-correction ("Let's do the female first. No, let's do the male."); some beats may be Jude.

## Game mechanics (4 lines) & out-of-band (4 lines)
- `[game mechanics]`: **13–16** — Jude's knowledge/int check to identify the transformed ("roll… plus your intelligence modifier, +4"). DM `00A`. The lore that follows (17–22, the Yuan-ti) is kept as narration.
- `[out-of-band]`: **91, 93** ("It's like a Pokémon catcher" — modern comparison for the man-catcher pole; the pole itself is a real in-scene item), **122** ("I'll tell you about Dr. Mangala" — a real-world reference, ≈ Dr. Mengele), **178** ("Dude, wake up" — table aside). Raw tags kept.

## Canon / continuity notes
- **The Yuan-ti / "the transformed" (7–22):** the Scarlet-Brotherhood captives are people transmuted into snake-people (fangs, slit eyes, scales) — made by **eastern transmuters** to serve as slaves; **Albashon** had spoken of them. This is a significant reveal about what the Brotherhood's agents are (cf. `worldbuilding/` — no dedicated Yuan-ti file yet; recommend one).
- **The fang-venom (94, 189–197):** a **pale-green** toxin milked from the prisoners' fangs — Jude's working sample of the poison, tied to the alchemist's murder (the **Gift of Insamiar** thread). Author to confirm whether this snake-venom *is* the Gift of Insamiar or a related toxin.
- The female prisoner curses in **Ancient Suel** — consistent with the Suel/Scarlet-Brotherhood connection.

## Names / garbles to normalize in prose
- **"Paul Ribeiro" (1)** → **Paul Revero**.
- **"the Yontai" (20)** → **the Yuan-ti** (cf. `Name_Normalization_Key.md`: "jaunty"/"yawn-tee" → Yuan-ti).
- **"Ancient Soul" (65)** → **Ancient Suel**.
- **"Absalon" (19)** → **Albashon** (the master alchemist).
- **"Walesun" (1)** → **Wealsun**.
- **"a nit check" (13)** → an **int/knowledge check**.
- **"Dr. Mangala" (122)** → real-world reference (≈ Dr. Mengele) — recast or cut for prose.

## Author review corrections applied (round 1)
- **110** "Who can lift a 50-ton block?" re-tagged **Leslie `03A` → Jude `01A`** (the exchange is Leslie 109 / Jude 110 / Leslie 111).
- Body edits: **44** "tries to sit in her face" → "tries to **study** her face"; **69** "I look at the **mail**" → "I look at the **male**".
- Confirmed (no change): **77** is Jude asking Paul; **121** "Workers." is Leslie.

## Speaker discontinuities
- raw00 carries the DM plus the jailer and the female prisoner; the three PC tags trade short lines throughout. Separated by content.
