# Cast Mapping — Jude & Leslie Escape the Scarlet Brotherhood (4th Wealsun)

`Jude_Leslie_escape_scarlet_brotherhood_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Jude, Leslie, Albashon (the alchemist, DM-voiced NPC — he dies here), Scarlet Brotherhood agents (the masked raiders / "Brotherhood of Insiniar" snake-worshippers, DM-voiced, incl. one female voice). This is the long set-piece: Leslie flees his master's shop, Jude drags the poisoned Albashon down to the sewers, Albashon dies passing a formula-note to Leslie, and the two escape a running underwater chase, surfacing in Blood Alley.
**In the room (3 voices):** Jude's player (Steve), Leslie's player (Roman), and the DM (narration, Albashon, the agents, and all rulings).

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_00** | The DM — narration + **Albashon** (dying) + **Scarlet Brotherhood agents** + rulings | **Catch-all bleed:** Jude's and Leslie's short replies frequently land here too (e.g. 154–162, 224–234); a few Leslie-player lines during the swim | Opens the scene from Leslie's POV ("your master Albinath," 1–22); voices Albashon's death (143–232), the agents' shouts (78, 310, 420–432, 718–724), and every roll/ruling. |
| **SPEAKER_01** | **Jude** in-character + Jude's player (Steve) OOC (spells, dice, tactics) | Early setup detail (11); a few Albashon replies bleed in | Recaps his wall of fire from the prior fight (37–42); named Jude (154); runs the lightning bolt, magic missiles, shield, and the drag-and-swim. |
| **SPEAKER_02** | **Leslie** in-character + Leslie's player (Roman) OOC (hiding, magic missile, firebolt, climbing) | DM position-calls bleed in (84, 92, 97, 501–517, 809–811) | Hides in the study (27–34), is called by name "Leslie!" (81–90), helps carry the master, casts magic missile/firebolt, and finds the stairwell. |

## Flagged ambiguities (author: please correct)
- **SPEAKER_00 is a catch-all in the death scene.** Albashon's dying speech, Jude's replies, and DM narration are braided under one tag from **143–234**. Key splits: Albashon speaks 143–153, 156–171, 200–205, 213, 220–232; Jude answers 154–155 ("Jude." / "I've got my wand out."), 166–168; the note-hand-off and "Idiom Nakhond is dead… he has a student… Lord Frank knows him" (225–231) are Albashon's last words.
- **Agent voices (DM) to separate from narration:** 78 ("Where's the back door?" — the elf agent, i.e. Jude, overheard); 310 ("They've gone down!"); 420–432 ("the body, there's a body," "it's the alchemist," "The dagger must have gotten him," and the **female** voice "Be aware, I smell something," "There!"); 718–724 ("He's dead! After them! Fools!").
- **DM position-calls bleed onto SPEAKER_02** during mechanics (84, 92, 97, 409–413, 501–517, 590–605, 809–811, 1002–1003) — these "you're here / you can go 15 feet / they can see just as well as you" lines are the DM, not Leslie.
- Normalizations: "Albinath" → **Albashon**; "Insiniar / jaunty / Yon-T / Naga" → **Scarlet Brotherhood Yuan-ti**; "Gouge" (158) — Jude's associate, confirm; "Lord Jameis/Jamis" → **Lord Jamis**; "Idiom/Idie Mahan Nakhond" (226) → the Keoland master alchemist (reported dead); "Lord Frank" (231) — confirm vs. Lord Jamis; "Karmurg/Karmur" (131) — ethnonym aside, not a name; "Ferd's Bar / Blood Alley / Gallage & Carmar" (1508–1518) — foreign-district locale, keep.

## Out-of-band table chatter
This file mixes substantial in-story roleplay/narration with a long, mechanics-dense chase. Tag `[out-of-band]`:

**Discrete table chatter / meta / anachronisms (exact lines):**
- **55–56** ("**Steve**, you roll up. Pick your pile…") — real name, Jude's player.
- **122** ("**Roman**, you did not name yourself Leslie after the character.") — real name, Leslie's player, + meta about the PC's name.
- **1104–1113, 1119–1122** — the DM reading suffocation/breath rules aloud from the book ("Page 183…").
- **1142–1145** ("Why do we always roll a niche so much? Because it determines life or death.") — table meta.
- **1157–1158** ("I just say, I open my mouth. The turd comes in. It's a gross way to die.") — player gallows-humor aside.
- **1221** ("I'll just look it up on my **phone** real quick.") — anachronism.
- **1476** ("We're like in the middle of **Egypt**.") — anachronism/joke (Jude corrects it in-character at 1477).

**Mechanics (dice / initiative / AC / DC / saves / movement-counting / spell rules)** — the pervasive out-of-band layer. In-story beats are the exception; treat as `[out-of-band]` these ranges: **52–77, 83–97, 112–142, 172, 206–218, 236–240, 245–274, 289–309, 311–345, 366–419, 438–473, 497–526, 530–582, 586–605, 609–677, 688–717, 725–905 (excl. lore below), 906–1103, 1114–1156, 1159–1255, 1260–1337, 1357–1424, 1429–1464.** (Movement calls like "you go 45 feet," AC/DC checks, "roll a niche," charge-counting for the wand, etc.)

**In-story beats to KEEP for prose** (everything else is the mechanics layer above): **1–24** (the raid begins — errands, two masked men, blasts); **26–48** (Leslie hides; the stairwell to the sewers; decides to flee); **78–111** (agent "where's the back door"; Albashon carried out bloodied; Jude "take him so I can kill anyone who comes through"); **116–132** (Leslie struggles to lift the frail master); **143–171** (descent; Albashon recognizes Jude as Lord Jamis's agent); **173–234** (Albashon poisoned, hands Leslie the note, names the dead Nakhond and his surviving student, dies); **235, 275–310** (searching the body — robe, pouch, golden alchemy medallion); **420–437** (agents find the corpse; female voice; Jude looses the lightning bolt); **474–496** (lore: the Brotherhood of Insiniar snake-cult; the bolt strikes both men); **527–529, 583–585, 606–608** (darkness; firebolt lights the corridor; Leslie leaps into the water); **678–687, 718–724** (swept down the main seawater pipe; "He's dead! After them!" — two agents splash in); **1256–1259** (Leslie breaks the surface); **1338–1356** (Jude reaches Leslie at the platform, "GO!"); **1425–1428, 1443–1448** (magic missiles down the last agent; Leslie hauls himself out); **1465–1518** (the blinded agent sucked into the pipe; they climb the rungs; surface via the manhole into Blood Alley, behind Ferd's Bar).

(Reasons: real players' names at the table, book/rules read-aloud, dice/AC/DC/save/movement mechanics, and modern-tech/pop anachronisms.)

## Speaker discontinuities
- **223** region and scattered lines are untagged or mis-tagged during fast dice exchanges.
- Sustained 00→player and player→00 bleed throughout the swim-chase (roughly 725–1464): the DM's movement/ruling calls and the players' spell declarations swap tags repeatedly. Re-attribute by content, not tag.
- Albashon's entire death scene (143–234) is compressed under SPEAKER_00 — the single most important re-attribution in the file.
