# Cast Mapping — Blood on the Charts (6th Wealsun)

`Blood_on_the_Charts_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. **This is the bar-brawl COMBAT that opens at the end of *Discussions in the Chart Room* — roughly 90% dice/mechanics.**

**Cast (index):** Gouge, Merrick, Tyrus (PCs), the DM, and the **Mob leader** + his Toli thugs (NPC, DM-voiced). Folsom and Owen are off-scene (Folsom is briefly grappled by a thug at ~1010 but has no lines).
**In the room (4 voices):** three players plus the DM.

## Speaker → character mapping (final, character-locked; crew registry)
Crew registry: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`. The mob leader (the "Mob_leader" of the cast list, Sewell's/the Toli muscle) → **`01B`**.

| Tag | Character | Kit / role | Lines |
|-----|-----------|-----------|-------|
| **SPEAKER_00A** | The DM | Narration + all combat adjudication; voices the mob | 732 |
| **SPEAKER_01B** | The Mob leader | NPC — thug taunt (559–560) and the surrender (1433–1434) | 4 |
| **SPEAKER_04A** | Gouge | rogue/fighter — cutlass + dagger + scimitar, sneak attack | 250 |
| **SPEAKER_05A** | Merrick | ranger — rapier, Hunter's Mark; grapples the last thug | 137 |
| **SPEAKER_06A** | Tyrus | paladin — shield, Champion's Challenge, Smites, Command | 254 |

Raw layout: **raw00** = Gouge, **raw01** = DM (+ the mob), **raw02** = Merrick, **raw03** = Tyrus — but the tags bleed badly in the fast rounds (see below).

## How this file was tagged
This is a near-continuous combat log — initiative, AC/DC, to-hit, damage dice, spell-slot bookkeeping, mini placement. Per the convention, **almost the whole file is `[game mechanics]`, attributed to the character by kit** (raw00→Gouge, raw01→DM, raw02→Merrick, raw03→Tyrus). Only two kinds of line were pulled out: the **in-story beats** (below) → roleplay tags, and the **real-world/table asides** → `[out-of-band]` (raw tag kept). **Because the tags bleed, the character on any given mechanics line is best-effort — the point is that mechanics are marked as mechanics; verify a specific attribution only if you plan to use that line.**

## In-story beats lifted to roleplay (use these in prose)
- **1–2** — scene opener ("Battle and bar").
- **182–184, 187–189** — Tyrus's Champion's Challenge taunt ("Too much of a pussy to fight me yourself… I'll take you all on, you pussy"). *(189 is a diarizer echo on Gouge's tag; it's Tyrus's line.)*
- **255–257** — Tyrus falls prone, "After he goes, I'm gonna take all you bitches on."
- **515–520** — Gouge's dagger/scimitar throat-kills (embedded roll 518 left as mechanics).
- **559–560** — a thug's taunt (mob, `01B`).
- **667** — Tyrus: "You fucking stomped on my nuts."
- **1269–1272** — Gouge's cutlass opens a throat, "a crimson wave goes all over Merrick… that guy falls." *(1271 "just like my girlfriend" kept out-of-band.)*
- **1298–1300** — the mob's morale breaks and they scatter; "three of you standing in the middle of this bar."
- **1337–1341** — Gouge rides a fleeing thug down, knife in.
- **1373–1401** — Tyrus's Command climax ("drop. To the ground. Stop!"), sword to the frozen thug's neck, "Fuckin' do it." *(rolls/"wisdom check" within left as mechanics.)*
- **1422–1450** — resolution: Merrick grapples the survivor ("If you want to live, surrender right now"), the **mob leader** yields — "Yes sir. I was only paid for this" (`01B`) — the rest run, ~eight dead on the floor, the three regroup.

## Out-of-band (raw tags kept, 73 lines) — real-world / table asides
**159** ("Coors Lights and Medellas" from the fridge), **484–493** (the cursed/clay "special dice" tangent), **617–622** (choosing a mini for "Guy" — "the ones Aidy can use"), **700–732** (the coins / thread-on-a-doorknob / "Carburton" reminiscence — an out-of-game anecdote), **1019** ("I almost got the banjo part"), **1054** ("Names are hard to pick up"), **1098–1101** ("we're not even two minutes into what's going on"), **1147** ("Good thing you saved him"), **1158–1161** (rolling for the absent Merrick player — "Don't play as Merrick… He's shitting"), **1192–1196** ("Can you give me that juice… Are your stones up?"), **1232–1234** ("cross-charactering dies"), **1271** ("just like my girlfriend"), **1409, 1413–1414** ("that's the Colt Terrier… out of my kit" — a dice prop).

## Flagged ambiguities (author: please correct)
- **Severe tag bleed.** raw01 (DM) swallows many players' roll callouts, and player tags occasionally carry the DM's prompts. Mechanics attributions by kit are approximate.
- **~1158 onward, Merrick was played by proxy** (his player stepped away), so `05A`/Merrick-region mechanics may be a stand-in roller, not Merrick's own choices.
- **700–732** is a garbled out-of-game reminiscence tangled with a combat action ("I throw it at his eyes," 733) — kept the reminiscence out-of-band and the eye-throw as mechanics; confirm none of it is in-world.
- Untagged lines 13 and 1403 defaulted to DM game-mechanics.

## Speaker discontinuities
- Continuation of the ambush from *Discussions in the Chart Room*; the mob leader is the Toli/Suel muscle from that scene.
- Constant DM↔player and DM↔mob bleed across all four tags — assign by kit/action, not tag number.
