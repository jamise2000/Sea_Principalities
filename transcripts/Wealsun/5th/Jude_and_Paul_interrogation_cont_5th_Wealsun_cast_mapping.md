# Cast Mapping — Jude and Paul Interrogation (cont.) (5th Wealsun)

`Jude_and_Paul_interrogation_cont_5th_Wealsun.txt` · Book Two (Paul/Jude storyline). Direct continuation of *Jude and Paul Interrogate Prisoners*. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Ambiguities flagged below for author correction.

**Cast (index):** Jude, Paul, Leslie (PCs), the DM, and the **male Yuan-ti prisoner** (NPC, voiced by the DM).
**In the room (4 diarizer voices):** the DM (narration + the prisoner), Jude, Paul, Leslie, plus silent guards and the caged female prisoner. **⚠️ Very bleed-heavy AND canon-critical** — please scan; the base mapping is a different diarizer layout from the previous file (see below).

## Speaker → character mapping (final, character-locked; Jude/Paul registry)
Registry: DM `00A`, Jude `01A`, Paul `02A`, Leslie `03A`. NPC: **male prisoner `01B`** (voiced by the DM on the DM's raw tag).

| Tag | Character | Role | Lines (rp + mech) |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + adjudication + delivers the Insamiar lore | 73 + 3 = 76 |
| **SPEAKER_01A** | Jude | PC — does the torture (pulls fangs, an eye) for poison samples | 161 + 16 = 177 |
| **SPEAKER_02A** | Paul | PC — questions the prisoner; goes to make a "contraption" | 79 + 2 = 81 |
| **SPEAKER_03A** | Leslie | PC — eccentric; "workers/profits" schtick, sidelined | 34 |
| **SPEAKER_01B** | Male prisoner | NPC — the Yuan-ti captive; delivers the Insamiar/Gift lore and taunts | 46 |

**⚠️ Note the diarizer layout is different from the previous file:** here **raw00 = Leslie**, **raw01 = DM (+ the prisoner)**, **raw02 = Paul**, **raw03 = Jude**. How the two PCs were told apart: **Jude (raw03)** does the hands-on torture and all the alchemical/pharmacology reasoning (fangs = poison, drug effects, "Samyar" lore); **Paul (raw02)** asks the interrogation questions and leaves to "make a contraption." Heavy short-line bleed across all tags — separated by content.

## Point of the conversation
The torture continues. **Jude** — clumsy but unflinching — pulls the male prisoner's **fangs** (for venom samples), burns and later **removes an eye**, while **Paul** questions him and **Leslie** watches, queasy, riffing about keeping the prisoners as "workers." Under it, the **prisoner talks**, and the scene turns into a lore dump about the enemy:
- The captives are **Yuan-ti** who **voluntarily** took the snake-form (not polymorphed) as part of the **Scarlet Brotherhood's worship** — in that form "we can hear [the dragon] better."
- The snake-cult centers on **Insamiar**, an **ancient black dragon** of legend, tied to the alchemical **nigredo** ("Negrado" — the blackening/dissolution/"cooking" stage): Insamiar is "the god of cooking."
- **The Gift of Insamiar** is "**a liquid from the dragon's self**" — it causes **"insanity — or complete clarity," "the passage into consciousness."** (The prisoner asserts the dragon-origin as cult fact; per the author ruling this remains an in-world claim/rumor.)
- **Why they killed the alchemist (Albashon):** he "knows more than most" and **was working to counteract the effects of the Gift** — a substance to **abrogate its effects / take away the pain** of those afflicted (for the coming war). The Brotherhood couldn't allow it.
- They also **know Paul is trying to recreate the "white/yellow powder that saves Monmurg"** — the **anti-sahuagin powder**, "the powder **Cain Toli** has taken from the Helm" — and mean to stop that too.
- **Foreshadowing:** the prisoner fixes on **Jude** — an elf living among humans, with "colder eyes than any of the others" — and warns he is **"susceptible to the gift," "hears the dragon's call,"** and "**in time will fall and succumb**." Jude shrugs it off ("keep a close eye on me").

They wrap the torture and step into the hall for a private talk (Jude insists on bringing Leslie, and on staying out of the **female** prisoner's earshot) — setting up the next scene.

## Hardest calls / flagged ambiguities (author: please correct — needs a full scan)
- **The whole prisoner/DM split is on one raw tag (raw01).** I separated the **male prisoner `01B`** from **DM narration `00A`** by content; the lore lines (154–167) are kept as DM narration, the taunts/answers as the prisoner. Please verify the boundaries (esp. 225–232, 254–263, 286–291, 349–387).
- **Base PC mapping** (raw02=Paul, raw03=Jude, raw00=Leslie) is my read from the torture action + reasoning; confirm it holds.
- **Bled short lines** reassigned by content (e.g., 31, 36, 40, 43, 98, 130, 155, 161, 227/229/230, 262, 265, 289, 291, 317, 359, 361). Scan.
- **Combined frame+quote (368)** "He basically says, but also, we know what you're trying to do, Paul Ribeiro…" kept on the prisoner `01B`.
- **Real player names:** **69 "Come on, Dave"** marked out-of-band; **216 "…a fork, Tom?"** left in-scene (Jude asking for a fork) but "Tom" should be dropped in prose. **273–280** ("I am the book… the book reads me… Dad's like…") is absurd riffing left on Paul `02A` — may be OOC table banter; your call.
- **The guard's one reply (32 "So are you, sir")** was folded into DM narration `00A` rather than given its own NPC tag. The **female prisoner does not speak** in this file (she spoke in the previous one), so no second B-tag here.
- **"He's got some pain tolerance" (35), "Metal, not wood… hammers, nails, chemicals" (312–316), "Mono would kill his dad" (356)** are garbled/ambiguous — best-guess attributions, flagged.

## Game mechanics (21 lines) & out-of-band (1 line)
- `[game mechanics]`: **142–152** (Jude's history/knowledge check on "Samyar"/Insamiar — "+8… twenty-one"); **157** ("Roll your dice"); **245–253** (an endurance/will check — "Do an end check… eleven… +intelligence… fifteen"). DM `00A` / Jude `01A` / Paul `02A`. The **Insamiar lore** the checks unlock (154–167) is kept as narration, not mechanics.
- `[out-of-band]`: **69** ("Come on, Dave" — real player name).

## Canon / continuity notes (major)
- **Insamiar = ancient black dragon; the Yuan-ti snake-cult worships it** and takes snake-form voluntarily to "hear the dragon." Ties the Scarlet Brotherhood → Insamiar. (Recommend a **Yuan-ti** worldbuilding file and cross-linking `worldbuilding/Insamiar_the_Black.md`.)
- **The Gift of Insamiar = "a liquid from the dragon's self,"** causing insanity / "complete clarity." On-page cult assertion of the dragon-origin (author ruling: treat as in-world claim/rumor). The **fang-venom** Jude milks and the **"Samovar/Insamiar Plague"** ("Black Plague… in the marshlands") are part of this thread.
- **Motive for Albashon's murder:** he was developing a **counter to the Gift** (to abrogate its effects / ease the afflicted before the war). The Brotherhood killed him to stop it — and to stop Paul recreating the **anti-sahuagin powder** ("the powder Cain Toli took from the Helm"; cf. `worldbuilding/The_Anti-Sahaugin_Powder.md`).
- **Jude-corruption foreshadowing:** the prisoner marks Jude as susceptible to the Gift / hearing the dragon's call — a thread to watch.

## Names / garbles to normalize in prose
- **"Samyar" / "Samyar Combs" / "Insigniar" / "Nsemiar" / "Samiar" / "Samovar" / "Gift of Insanity" (131, 135–136, 154, 160, 167, 351, 380–382)** → **Insamiar** / **Gift of Insamiar** / **Insamiar Plague**.
- **"the Negrado" (160)** → the **nigredo** (alchemical blackening/dissolution stage).
- **"Sewell" / "Sewell Brotherhood" / "the ancient Sewell" (125, 158)** → **Scarlet Brotherhood** / **Suel** (context-dependent; cf. `Name_Normalization_Key.md`).
- **"Kane Toli" (377)** → **Cain Toli**; **"Paul Ribeiro" (4, 368)** → **Paul Revero**; **"the Helm" (377)** → **Helm Island**.
- **"white powder" / "yellow powder" (369, 374)** → the **anti-sahaugin powder**.
- **"fifth of Whale's son" (1)** → the **5th of Wealsun**.
- **"Dave" (69), "Tom" (216)** → real player names — drop in prose.

## Author review corrections applied (round 1)
- **69** was NOT out-of-band: it's **Paul `02A`** "Come on, **Jude**" (reasoning with Jude about the torture). "Dave" was a mishearing of "Jude" — the file now has **zero out-of-band lines**.
- **216** "a fork, Tom?" → "a **forked tongue**." — "Tom" was a mishearing of "tongue," not a real name. (So both earlier "real player name" flags were garbles.)
- Re-tagged: **136** → **Paul `02A`** (repeating "Insamiar"); **161** ("What's that?") → **Leslie `03A`** (he knows alchemy); **273–280** ("I am the book…") → **Leslie `03A`** (all Leslie); **298** ("A cheap slave") → **Leslie `03A`**; **243** ("Then he lets on") → **DM `00A`** (narration).
- Body edits (Insamiar): **131** "It's Samyar Combs." → "It is **Insamiar's call**."; **135** "The Samyar?" → "**Insamiar.**"; **136** "It's Samyar." → "**Insamiar.**"; **240** → "…a very cold **crowd**."; **318** "Guard brings you a spin." → "The guard brings you a **spoon**."

## Speaker discontinuities
- raw01 carries the DM **and** the male prisoner throughout (separated by content); the three PC tags (Leslie=raw00, Paul=raw02, Jude=raw03) trade short lines constantly.
