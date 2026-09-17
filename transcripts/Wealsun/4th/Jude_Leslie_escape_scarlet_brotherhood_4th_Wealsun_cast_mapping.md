# Cast Mapping — Jude & Leslie Escape the Scarlet Brotherhood (4th Wealsun)

`Jude_Leslie_escape_scarlet_brotherhood_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking. **A tag is a voice, not a fixed character.** **Largest file in the set** (1518 lines; 1183 out-of-band combat/chase mechanics). Initial pass applied — the NPCs are separated onto B-tags; **a heavy file, so expect more sift.**

**Cast (index):** Jude, **Leslie**, **Albashon** (the alchemist — **dies here**), **Scarlet Brotherhood agents** (the "Brotherhood of Insiniar" Yuan-ti snake-cult raiders, incl. a female voice).
**In the room (3 voices):** the **DM**, **Jude**'s player (Steve), **Leslie**'s player (Roman).

## Five-tag scheme (A = PC/DM, B = NPC)
| Sub-tag | Character | Count |
|---------|-----------|-------|
| **SPEAKER_00A** | **DM** — narration, rulings | 177 |
| **SPEAKER_01A** | **Jude** (PC) | 93 |
| **SPEAKER_03A** | **Leslie** (PC) | 20 |
| **SPEAKER_01B** | **Albashon** (NPC, dying) | 35 |
| **SPEAKER_02B** | **Scarlet Brotherhood agents** (NPC) | 10 |
| `[out-of-band] [SPEAKER_0N]` | combat/chase mechanics, dice, positioning | 1183 |

*(Narration lead-ins like "He goes…", "…and comes down and goes…", "This one looks over at you and goes…" remain on the NPC line; strip them in prose.)*

## The point of the conversation
The long escape set-piece. From **Leslie's** POV: he's hiding in the study when the raid hits; Jude (the elf) has dragged the poisoned **Albashon** toward the sewer stairwell. The three descend; Albashon, dying of **insidious poison** from the dagger wound, presses a **formula-note into Leslie's hand** — "Paul Rivero is looking for this… this is why they attacked me" — names Leslie his heir ("you can help Paul"), and with his last words tells them the master alchemist **Idiom Nakhond is dead** but **has a student that Lord Frank knows**. Albashon dies; Jude strips the body (a golden medallion). The **Brotherhood of Insiniar** (Yuan-ti snake-cult) pursue — a female agent smells them out — and Jude blasts them (lightning bolt, magic missiles). Jude and Leslie plunge into the flushing seawater sewer, are swept down a running underwater chase, and finally surface in **Blood Alley**, behind **Ferd's Bar**.

## Canon / names
- **Albashon dies here** (poison from the raid) — update his status.
- **The note**: a formula/recipe Albashon gives Leslie *for Paul Rivero* — a key plot object.
- **Idiom Nakhond** (226) = **Edium Nicond** (the other great Keoland transmuter; per Name Key) — reported **dead**, but **has a student** that **Lord Frank** (Franck) knows. Plot thread: that student becomes the new path to reproducing the powder.
- **Brotherhood of Insiniar** (477) = the **Scarlet Brotherhood** Yuan-ti snake-cult; rumored coven near **Westkeep**, mate with kobolds. Normalize to Scarlet Brotherhood / Yuan-ti.
- **Blood Alley** (1508), behind **Ferd's Bar**; "Gallage and Carmar" (1510) — locale color.

## Flags (author: this is a big file — please sift)
- **Narration-vs-Jude "I" bleeds** in the chase: several DM-tag lines are Jude acting ("I turn around…" 1465) and several Jude-tag lines are DM narration ("You see the guy get sucked under" 1466). Spot-check 1465–1468, 1355 ("I say, GO!" = Jude).
- **78 "You hear an elf say, Where's the back door?"** — the "elf" is **Jude** (overheard from Leslie's POV), not an agent; left on 00A.
- **Author rulings applied:** 159, 161 → **out-of-band**; **188 "It's insidious poison."** and **219 "Help, Paul Rivero."** → **Albashon (01B)**. Still open: **143** (Albashon's "do you have your book?" buried in DM narration), **165** (short interjection).
- **Position-calls** ("you can go 15 feet," "they can see just as well as you") that landed on Leslie's tag during mechanics are the DM — mostly captured as OOB, but check any that remain.

## Out-of-band table chatter
`[out-of-band]`: the bulk — initiative/movement/spell mechanics, dice, positioning, and the extended swim/chase rolls (much of 240–1500). ASR: "Albinath" = **Albashon**; "Insiniar/jaunty/Yon-T/Naga" = **Scarlet Brotherhood Yuan-ti**; "Idiom/Edie Mahan Nakhond" = **Edium Nicond**; "Lord Frank" = Franck.

## Speaker discontinuities
- The catch-all death scene (143–232) and the agent shouts were reconstructed from the DM tag; the chase narration still has scattered PC/DM "I/you" bleeds (flagged).
