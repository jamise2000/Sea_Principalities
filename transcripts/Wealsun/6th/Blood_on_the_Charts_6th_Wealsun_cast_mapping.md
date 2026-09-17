# Cast Mapping — Blood on the Charts (6th Wealsun)

`Blood_on_the_Charts_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Merrick, Tyrus, *Mob_leader (Sewell's hired thugs, DM-voiced). **COMBAT — roughly 90% dice/mechanics.**
**In the room (4 voices):** three players (Gouge, Merrick, Tyrus) plus the DM, who narrates and voices the mob (the "guy"/"big guy"/leader). Folsom and Owen are off-scene; Folsom is grappled by a thug at one point (L1010) but does not speak. This is the bar brawl that begins at the end of *Discussions in the Chart Room*.

> **Author note:** This file is a near-continuous combat log — initiative, AC/DC, to-hit rolls, damage dice, spell-slot bookkeeping, and mini placement. **Treat essentially the whole file as `[out-of-band]` mechanics and lift only the sparse in-story beats listed below** into prose. The characters are distinguished by their kit, which is how the tags are assigned.

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_00** | **Gouge** — rogue/fighter (cutlass + dagger + scimitar, sneak attack, cunning action, uncanny dodge, two-weapon fighting, second wind) | occasional roll bleed | L494 DM "Gouge?" → L495 "Yes"; L354–358 lists rogue features; L371 "cutlass and axe," L381 "pull my dagger"; L515 "Gouge moves left with his dagger and hits that guy in the throat" |
| **SPEAKER_01** | **DM** (narration + rules adjudication) **+ the Mob / mob leader ("guy," "big guy")** | player-roll bleed throughout (the DM voice absorbs many player lines in the fast cross-talk) | L38–101 calls the thugs' grapples/attacks; L450–458 grapple rules; L1298–1300 "they scatter… three of you standing in the middle of this bar"; L1433–1434 leader "Yes sir. I was only paid for this" |
| **SPEAKER_02** | **Merrick** — ranger (rapier, Hunter's Mark, Fog Cloud, Longstride) | — | L264 DM "Merrick, you're next" → L265 "I'm grappling on right now"; L267 "can I draw my rapier?"; L312–318 ranger spell list + Hunter's Mark; L1425–1430 grapples the last thug "If you want to live, surrender right now" |
| **SPEAKER_03** | **Tyrus** — paladin (shield AC 16→18, Champion's Challenge, Turn the Tide, Divine/Thunderous Smite, Squad Leader, Lay on Hands, Command) | — | L130–149 Champion's Challenge/Turn the Tide; L664–669 "Divine Smite… you stomped on my nuts"; L887–890 Thunderous Smite; L1373–1388 "I use Command… drop. To the ground. Stop" |

## Flagged ambiguities (author: please correct)
- **Tag bleed is severe in the fast rounds.** SPEAKER_01 (DM) frequently swallows players' roll-callouts, and player tags occasionally carry the DM's prompts (e.g., L1071 "the guy grappling you falls off you as Gouge kills him" is DM narration under SPEAKER_00; L102 "Tyrus, you're next" is the DM under SPEAKER_00). Read by content, not tag.
- **Opening initiative (L1–35) is chaotic cross-talk** — everyone rolling at once; "Battle and bar. Obviously no shields" (L1–2) is the DM's scene opener; L3–5 "roll my nash" is a player under the DM tag.
- **L700–734 is a garbled digression** about coins, a thread on a doorknob, "Carburton's door," and "I was such a good friend to that guy… Jesus Christ." It reads as an out-of-game anecdote/reminiscence tangled with an attack (something thrown at the big guy's eyes, L733–743). Flagging the whole block — decide whether any of it is in-world.
- **L1158–1161** ("Don't play as Merrick. You gonna roll for him? … He's shitting.") indicates Merrick's player stepped away and someone rolled for him for a stretch — so SPEAKER_02 lines in that region may be a proxy roller, not Merrick's player.
- The mob leader here is Sewell's muscle (continuation of the SPEAKER_01/Sewell voice from *Discussions in the Chart Room*).

## Out-of-band table chatter
**Nearly the entire file is dice/mechanics and should be tagged `[out-of-band]`.** In practice: tag every line EXCEPT the in-story beats listed under "keep in-story" below. Beyond the pervasive roll/AC/damage/spell-slot bookkeeping, note these explicit non-combat asides embedded in the log: **159** ("Coors Lights and Medellas" from the fridge — drink talk), **484–493** (the "cursed"/clay/hand-made special dice tangent), **617–622** (choosing a mini for "Guy" — "here's all the ones Aidy can use"), **700–734** (the coins/doorknob/"Carburton" reminiscence — see flags), **1019** ("I almost got the banjo part, Master"), **1054** ("Names are hard to pick up"), **1098–1101** (meta: "we're not even two minutes into what's going on"), **1147** ("Good thing you saved him"), **1158–1161** (rolling for the absent Merrick player), **1192–1196** ("Can you give me that juice? … Are your stones up?" — drink talk), **1232–1234** ("Are you cross-charactering dies?"), **1271** ("Just like my girlfriend" — crude aside), **1409/1413–1414** ("that's the Colt Terrier… out of my kit I got" — dice prop).

**Keep in-story (do NOT tag — lift these into prose):**
- **1–2** — scene opener ("Battle and bar").
- **182–184, 187–189** — Tyrus's Champion's Challenge taunt: "Too much of a pussy to fight me yourself, huh? … I'll take you all on, you pussy."
- **255–257** — "Tyrus punches around, loses his footing, and falls prone… After he goes, I'm gonna take all you bitches on."
- **515–520** — Gouge's dagger/scimitar throat-kills.
- **559–560, 667** — combat trash-talk ("stomped on my nuts").
- **1269–1272** — "Your cutlass goes across his throat, opening it up, and a crimson wave goes all over Merrick… That guy falls." (drop the "just like my girlfriend" aside).
- **1288–1300** — the mob's morale breaks: "they see their guy just gush and they scatter. Three of you are standing here in the middle of this bar…"
- **1337–1341** — Gouge rides a fleeing thug down: "I'll go right down with him… moving your knife into it."
- **1373–1401** — Tyrus's Command climax: "I use Command… drop. To the ground. Stop!" the thug freezes, sword to his neck, "Fuckin' do it."
- **1424–1450** — resolution: Merrick grapples the survivor ("If you want to live, surrender right now"), leader "Yes sir. I was only paid for this," the rest run, ~eight dead bodies, the three coalesce in the middle of the bar.

## Speaker discontinuities
- Untagged lines: **L13** ("Yes."), **L1403** ("Okay.").
- Constant DM↔player and DM↔mob bleed across all four tags (documented above) — the tag numbers are unreliable here; assign by kit/action.
- Merrick played by proxy for a stretch after ~L1158.
