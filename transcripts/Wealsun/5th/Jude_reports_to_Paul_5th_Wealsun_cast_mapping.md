# Cast Mapping — Jude Reports to Paul (5th Wealsun)

`Jude_reports_to_Paul_5th_Wealsun.txt` · Book Two (Paul/Jude storyline). Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Ambiguities flagged below for author correction.

**Cast (index):** Jude, Paul, Leslie (PCs), the DM, and a **servant/guard** (NPC) who announces them.
**In the room (4 diarizer voices):** the DM, Paul, Jude, and Leslie. Early morning, 5th of Wealsun, in Paul's study. **⚠️ Exceptionally bleed-heavy** — rapid comedic cross-talk between Paul and Jude constantly lands on the other's tag; almost everything below is a content-separation, not a tag read. Please scan the whole file.

## Speaker → character mapping (final, character-locked; Jude/Paul registry)
Registry: DM `00A`, Jude `01A`, Paul `02A`, Leslie `03A`. NPC: **servant/guard `01B`** (announces them, line 5).

| Tag | Character | Role | Lines (rp + mech) |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + adjudication; delivers the "Gift of Insamiar" recall | 22 + 3 = 25 |
| **SPEAKER_01A** | Jude | PC — reports the raid, the master's poisoning, presses to interrogate | 121 + 8 = 129 |
| **SPEAKER_02A** | Paul | PC — reading a torture manual; recounts his night; holds the prisoners | 98 |
| **SPEAKER_03A** | Leslie | PC — eccentric, traumatized, babbling ("the man of the myths") | 22 |
| **SPEAKER_01B** | Servant | NPC — "Prince Rivero, here's Jude and a companion of his." | 1 |

**How the two PCs were told apart (they trade tags constantly):**
- **Paul `02A` = raw01** — recounts going to **his** palace for **his** books, coming back to see the alchemist shop explode; holds the captured Scarlet-Brotherhood prisoners; owns the torture manual (*Absalon's/Absalon's Methods of Torture*).
- **Jude `01A` = raw02** — introduces Leslie, recounts the sewer escape and the master's death, wants to interrogate the female captive.
- **Leslie `03A` = raw03**; **DM `00A` = raw00**.

## Point of the conversation
Early on the 5th, a servant leads **Jude** and **Leslie** into Paul's study, where **Paul** sits reading a torture manual (prepping to question his prisoners). Jude reports the raid: the alchemist shop burned, they fled through the sewers, and the master (**Albashon**) died — **not from his wound (a gouged-out eye) but from poison**. The dying alchemist named the poison — **the Gift of Insamiar** (it made him bleed black fluid from his eyes) — and said **"I know what Paul needs,"** which the DM clarifies is the **anti-sahuagin powder** (Jude realizes he lacks the knowledge to recreate it, and the shop's interior — where a magicked firebox might survive — is now cordoned by Palace-District guards). Paul, in turn, recounts reaching the burned shop, mocking the Scarlet Brotherhood for loitering by their own arson, and having **apprehended several — including a dangerous female** — now held in his dungeon (he'd earlier questioned and released six drugged "locals"). Both want to interrogate the woman. After a long comedic tangle over Leslie's bizarre behavior (Paul threatens to have him beheaded; Jude insists he's in charge of Paul's training), they gather a torture book and head **down to the dungeons** to question the prisoners — setting up the interrogation scenes.

## Hardest calls / flagged ambiguities (author: please correct — this file needs a full scan)
- **Severe Paul⇄Jude bleed.** The diarizer routes long stretches of one man's speech onto the other's tag (e.g. 35–46 and 47–74 are split by content). I assigned by who logically speaks; expect misses in the rapid exchanges.
- **Leslie's lines vs bleed (63–66, 196–200, 245–248):** Leslie's grandiose babble ("I got a lot of them," "I own the world," "I'm Paul Rivero") sometimes lands on the DM/Jude/Paul tags and vice versa. Please verify who says what in the Leslie bits.
- **Mixed frame/quote & mixed lines left merged:** 206 ("Why don't you come with us… My mind is too big" — Jude + Leslie on one line); 78 ("I don't remember… Do an int check" — Jude + DM). Split if you prefer.
- **Rodiger confusion (173–178):** Jude means "the guards we worked with before / the thief we captured"; Paul offers "Rodiger" — the thread is tangled (Rodiger is the North-Gate commander, not the thief). Verify.
- **"Absalon's Methods of Torture" (7)** — the torture manual's title (ASR: "Absalon's"/"Absolon's"); author to set the canonical spelling.

## Game mechanics (11 lines) & out-of-band (8 lines)
- `[game mechanics]`: **12–13, 16–17, 20–21** (an insight check on whether Paul is reading the book "for effect" — roll 6+5=11); **78–80** (an int check for Jude to recall the poison's name); **107–108** (whether Jude has enough knowledge to recreate the anti-sahuagin powder — "not at all"). DM `00A` / Jude `01A`.
- `[out-of-band]`: **249–255** (the "isn't that some Canadian guy? / there's no Canada in Monmurg / **Keoland**" real-world riff — the DM corrects the setting reference to Keoland); **281** ("Do you want to get some pizza?"). Raw tags kept.

## Canon / continuity notes (important)
- **The Gift of Insamiar is named on-page (84–88):** it is the **poison** that killed Albashon (black fluid from the eyes), confirmed distinct from his physical wound. This is the field usage matching your ruling (the Gift of Insamiar = a poison, dragon-origin a rumor; cf. `worldbuilding/Insamiar_the_Black.md` and `Name_Normalization_Key.md`).
- **"I know what Paul needs" → the anti-sahuagin powder (98–104):** the dying master's message ties the powder (which Paul needs "for his face") to this thread; Jude cannot recreate it from memory, raising the stakes on recovering anything from the burned shop (`worldbuilding/The_Anti-Sahaugin_Powder.md`).
- **A female Scarlet-Brotherhood captive** is held in Paul's dungeon (likely the masked attacker from the raid) — the interrogation target for the next scenes.

## Names / garbles to normalize in prose
- **"Paul Rivero" / "Paul Rivera" (5, 7, 25, 245)** → **Paul Revero**.
- **"Prince Jean's" (2)** → **Prince Jeon's** (palace).
- **"the fifth of the well sun" (1)** → **the 5th of Wealsun**.
- **"Scarlet of the Brotherhood" / "Skrull Brotherhood" (61, 138, 160)** → **Scarlet Brotherhood**.
- **"anti-sahuagin powder" (103)** → the anti-sahaugin powder (ledger spelling).
- **"Absalon's Methods of Torture" (7)** — torture manual (confirm spelling).

## Author review corrections applied (round 1) — file is now 283 lines
- Re-tagged to **Paul `02A`**: 32 ("Leslie?"), 63 ("Oh yeah"), 64 ("Oh, I got a lot of them"), and old-74 ("I believe I did" → now line 75).
- Re-tagged to **Leslie `03A`**: 69 ("Uh, blame Jude for that").
- **Split at 73:** "Well, I mean… Oh, I did grab the body, yes." → **73** "Well, I mean…" (Jude `01A`) + **74** "Oh, I did grab the body, yes." (Paul `02A`). All later line numbers shift +1.
- Body edits: **52** "my boy" → "my **guardsmen**" (Paul is with his guardsmen when he sees the fireball and knows it's Jude); **56** "It's an alchemy show." → "It's a **fireworks show**."; **234** (old 233) → Leslie `03A`: "No, red is your favorite color, you just don't know it yet."; **248** (old 247) → "Right. Like it matters you are a prince."

## Speaker discontinuities
- raw01 (Paul) and raw02 (Jude) swap constantly; raw00 (DM) and raw03 (Leslie) also catch bleed. Separated by content throughout — the single most bled file in this batch so far.
