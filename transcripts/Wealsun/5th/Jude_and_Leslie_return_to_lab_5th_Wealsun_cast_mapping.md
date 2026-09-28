# Cast Mapping — Jude and Leslie Return to the Lab (5th Wealsun)

`Jude_and_Leslie_return_to_lab_5th_Wealsun.txt` · Book Two (Paul/Jude storyline). Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Ambiguities flagged below for author correction.

**Cast (index):** Jude, Leslie (PCs), the DM, a **shop-cordon guard/sergeant** (NPC) and a **north-gate guard** (NPC).
**In the room (3 diarizer voices):** the DM (narration + both guards), Jude, and Leslie. ~1 a.m. on the 5th of Wealsun. Moderately bleed-heavy — separated by content.

## Speaker → character mapping (final, character-locked; Jude/Paul registry)
Registry: DM `00A`, Jude `01A`, Leslie `03A`. NPCs by appearance: **shop-cordon sergeant `01B`** (line 113), **north-gate guard `02B`** (188+).

| Tag | Character | Role | Lines (rp + mech) |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + adjudication + voices the guards | 68 + 2 = 70 |
| **SPEAKER_01A** | Jude | PC — wizard; wakes Leslie, leads them to the burned shop, plans to fetch Paul | 100 + 3 = 103 |
| **SPEAKER_03A** | Leslie | PC — alchemist's apprentice; grieving/rattled, worried about the fire and pursuers | 15 |
| **SPEAKER_01B** | Shop-cordon sergeant | NPC — turns them away ("no one is allowed past this area"; "Order of Paul Revero") | 5 |
| **SPEAKER_02B** | North-gate guard | NPC — recognizes Jude ("You're the wizard") | 3 |

Raw layout: **raw01** = DM (+ guards); **raw00** = Jude; **raw02** = Leslie. Heavy short-line bleed both ways (Jude's answers on the DM tag, Leslie's/Jude's lines swapping) — separated by content.

## Point of the conversation
Just past 1 a.m. on the 5th, **Jude** finishes his four-hour trance (recovering his spell slots), wakes **Leslie**, and decides they must **go check on the alchemist shop** — which Jude fears burned down in the raid (Leslie needles him: Jude was "a little overzealous with his fire spells," while Leslie recalls his master **bleeding black ooze from his eyes** from the assassin's poison). Jude cloaks Leslie in a hooded cloak so he won't be recognized as the alchemist's assistant, and they slip out past Ferd's late-night drinkers (Ferd has somehow come by a fresh supply of black rum and cider) and take the well-lit main road through the **Row of the Gods** (rented foreign temples and a red-light strip). They find the burned shop **cordoned off by five Upper-City guardsmen**; a sergeant refuses to let them past and won't help them reach **Paul Rivero** ("a prince of the city"). After weighing a dangerous route through the **Warrens**, Jude decides instead to **go back up to the palace to fetch Paul** in person. At the **north gate** (~1:30 a.m.), a guard recognizes Jude as "the wizard" — setting up Jude's reunion with Paul.

## Hardest calls / flagged ambiguities (author: please correct)
- **Bleed-heavy — please scan.** Three voices on three tags with constant short-line bleed; clear DM narration (00A), Jude's lines (01A), and Leslie's lines (03A) are high-confidence, but many one-word fillers ("Yeah," "Okay," "Right") were assigned to the likeliest speaker.
- **NPC numbering by appearance:** shop sergeant = `01B` (113), north-gate guard = `02B` (188+) — distinct NPCs at distinct locations.
- **Guard frames combined with quotes (113, 124):** "one of the guards comes up and goes, sorry citizen…" (113) and "He goes, Paul Rivero is a prince of the city" (124) carry a DM frame + the guard's quote on one line — assigned to the guard `01B`; split off the "…goes," frame if you prefer.
- **189 "Let him see me"** — attributed to the north-gate guard `02B` (leading into "You're the wizard"); the line is garbled and could be staging. Verify.
- **82–83** "Oh, I see you're well-satiated, brother. Come here." — kept as Jude `01A` (mocking the red-light hawkers); could be a solicitor NPC. Verify.
- **110** "Jude, we're just walking past." — the vocative "Jude" makes this **Leslie** `03A` addressing Jude (it landed on Jude's tag); confirm.

## Game mechanics (5 lines) & out-of-band (0)
- `[game mechanics]`: **138–142** — a check to know a Warren back-route ("Doing [a] check. Eight. … plus five. Thirteen."). DM `00A` / Jude `01A`.
- `[out-of-band]`: none. (The "statue of the pharaoh" / "Vestal Virgins" lines at 77–79 are real-world *analogies* the DM/Jude use to paint the Row-of-the-Gods red-light strip — kept in-scene; reinterpret in prose rather than using the literal Earth references.)

## Names / garbles to normalize in prose
- **"Paul Ribeiro" / "Paul Rivero" / "Paul Rivera" (115–124, 149, 185)** → **Paul Revero** (canonical; cf. `Name_Normalization_Key.md`).
- **"1 p.m. in the morning" (8)** → **1 a.m.** (also 50, 62, 107).
- **"the Palix District" / "Upper City" (89, 94)** → the palace/Upper-City guard (not Foreign-District) — author to confirm district name ("Palix" is an ASR guess).
- **"red-eye black rum" (49)** → red-eye / **black rum** (Ferd's stock; cf. the black-rum thread).
- **Row of the Gods** — the strip of rented foreign temples + hawkers + red-light district in the Foreign District (worldbuilding detail worth keeping).

## Author review corrections applied (round 1)
- **115** re-tagged **Jude `01A` → the guard `01B`**, and body corrected: "Order Paul Ribeiro." → "**Order of Paul Revero.**" (the sergeant citing whose authority closed the area).
- Body edits: **8** "1 p.m." → "1 am"; **89** "Palix District" → "**Palace District**"; **91** "You walked over some kind of an anthill." → "**Kicked** over some kind of an anthill."
- Note: the other Paul-name garbles left as raw record (116 "Ribeiro", 124 "Rivero", 149/185 "Rivera") — normalize to **Paul Revero** in prose (or on request).

## Speaker discontinuities
- raw01 carries the DM plus both guards; raw00 (Jude) and raw02 (Leslie) each carry bleed from the other and from the DM. Separated by content throughout.
