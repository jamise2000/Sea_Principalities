# Cast Mapping — Making Redshore (6th Wealsun)

`Making_Redshore_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Merrick, Tyrus, Folsom (PCs), the DM, and Owen Black (NPC, DM-voiced).
**In the room (5 voices):** the four players plus the DM (who narrates and voices Owen). **Note the tag numbering differs from the 5th-Wealsun files:** here the DM/Owen voice is **raw02**, not raw01.

## Speaker → character mapping (final, character-locked; crew registry)
Same crew registry: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`, Folsom `07A`, Owen Black `01B`.

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration / adjudication / lore recap | 110 |
| **SPEAKER_01B** | Owen Black | NPC — the smuggler host at Redshore | 66 |
| **SPEAKER_04A** | Gouge | PC — the money angle, ties off the boat | 21 |
| **SPEAKER_05A** | Merrick | PC — watchful; the message-spell aside to Folsom | 23 |
| **SPEAKER_06A** | Tyrus | PC — asks about the penned ships | 14 |
| **SPEAKER_07A** | Folsom | PC — both songs; goes off with Owen | 61 |

Raw layout: **raw02** = DM narration **and** Owen; **raw00** = Merrick; **raw01** = Gouge; **raw03** = Tyrus; **raw04** = Folsom.

## Point of the conversation
Evening of the 6th, the sloop makes **Redshore** and finds the bay choked with ~50 merchant ships penned in by three Keoland warships — the **Duke of Gratzel's** blockade, redirecting Monmurg-bound trade here to rot. Owen explains the smuggling economy (buy cheap off desperate traders, mark up twice in Monmurg). The crew debates why the Monmurg fleet won't break the blockade — Gouge assumed the sahuagin, but **Owen says the sahuagin "were never a part of it,"** nudging toward the real cause (the Orb/turtle-dragon situation). Folsom half-recites his biting anti-Monmurg satire ("O Monmurg… your leaders have led you astray"). At the ramshackle beachside **Chart Room**, Folsom performs a flattering song about **Sir Owen Black** (with a dig at Merrick), and Owen — charmed — takes Folsom along to "deal" with merchants, leaving the muscle behind ("we need charm, not that"). On the way out, Owen slips a coin purse to some **Toli** thugs and lies that it was a debt he paid off — a perception check catches the lie.

## Hardest calls / flagged ambiguities (author: please correct)
- **The "O Monmurg" song (100–116)** is **Folsom thinking the lyrics to himself** (not performed aloud) — all of 100–116 are Folsom `07A`, including 111. Render as interior monologue, per author.
- **The waking exchange (11–17)** is muddy: Merrick's player negotiating being woken as the boat comes in, with "Wake up, Merrick!" (17) tagged on Merrick's own raw00 — I read 17 as Owen. Verify.
- **The fleet-blockade discussion (85–94)** is a PC/Owen exchange caught on the DM/Owen tag; I split naval assessment → Owen, "coward"/prompt-to-Folsom → Merrick. Please scan.
- **123–125** ("We can make money… follow the money… Come this way") — I left on Gouge; "Come this way" (125) may be Owen.
- **181** ("refill it with red eyes") — resolved to **Gouge** `04A` per author (red-eye is his drink).
- **261–262** ("He wears leather armor / His arm was a little fucked up") is the DM describing Owen, bleeding onto Merrick's raw00.
- **287 was split** (per author) at the word "roll" into two DM lines: **287** narration ("…and whispers,", `00A`) + **288** `[game mechanics]` ("Roll your perception check."). All later line numbers shift +1.

## Game mechanics (attributed, 16 lines)
**213–214** (Folsom's performance roll), **234–237** (rules Q&A on the *message* spell — Merrick asking, DM answering), **259 & 261** (Owen's stat description — strength 16, leather armor), **282** ("Bring your 20-sided"), **288–291** (perception check as Owen approaches the Toli), **296–298** (second perception roll → "he just lied to you"). DM instructions/results → `00A`; rolls → the roller (Folsom `07A`, Tyrus `06A`, Merrick `05A`).

## Out-of-band (raw tags kept, 7 lines)
**117–119** (players joking about school subjects — "you literature / I've got science and math / Chemistry"), **189–190** (a modern "riffraff from the Mediterranean" analogy), **191–192** (a Star Wars gag — "made the Monmurgian run in less than 12 parsecs").

## Speaker discontinuities
- raw02 carries DM narration and Owen with no tag change; Folsom's song (100–116) also landed there.
- DM stat/description bleed onto Merrick's raw00 (261–262).
- Numbering differs from the 5th-Wealsun files (DM = raw02 here, not raw01).

## Names to normalize in prose
"Dig of Grasel" (64) → **Duke of Gratzel**; "Keogs / Keog marines" (86, 158) → **Keoland / Keoish**; "Burghoff" (113) → **Berghof**; "charter room" (127) → the **Chart Room**; "plars" → **Plars**.
