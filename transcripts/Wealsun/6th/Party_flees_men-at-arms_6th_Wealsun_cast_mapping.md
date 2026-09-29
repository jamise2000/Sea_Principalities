# Cast Mapping — Party Flees the Men-at-Arms (6th Wealsun)

`Party_flees_men-at-arms_6th_Wealsun.txt` · Book Two (ship-crew storyline). Follows *Party Reintroduction*. A long combat/flight scene on the Red Shore beach. Maps the diarization speaker tags to who is actually talking. **Character-locked tags:** A-series = PCs/DM; B-series = NPCs.

**Cast (index):** Gouge, Merrick, Tyrus, Folsom (PCs), the DM, and the **knight/men-at-arms** (NPC, DM-voiced). Matches the `.cast.txt` hint (5 voices).
**⚠️ Mostly game mechanics:** this is a full D&D combat encounter (~82% `[game mechanics]` — initiative, attack/damage rolls, positioning "one-two-three-four," AC, saving throws, spell rules). The in-character material is the opening beach debrief, the drunkard ruse, and the shouted combat dialogue / retreat.

## Speaker → character mapping (final, character-locked — DM names them on-page)
Registry: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`, Folsom `07A`. NPC: **knight `01B`**.

| Tag | Character | Basis (this file) | Lines (rp + mech) |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + combat adjudication + inline NPC voices | 134 + 879 = 1013 |
| **SPEAKER_05A** | Merrick | raw01 — **DM: "fog bank that Merrick had put up" (617), "That's Merrick" (1603)**; casts Fog Cloud, Hunter's Mark; **"the coastal terrain is your terrain" (1571–75)**, "expertise in perception" (1972); leads the escape | 64 + 202 = 266 |
| **SPEAKER_04A** | Gouge | raw03 — **DM: "That's Gouge" (697), "Gouge is first" (891), "Gouge has hit him for 30" (1244)**; heavy crossbow, sneak attack, Assassinate, cunning action, scimitar + dagger | 18 + 227 = 245 |
| **SPEAKER_06A** | Tyrus | raw04 — **named "Tyrus" (285/322/770/1318…)**; Thunderous/Searing Smite, Lay on Hands, Shield of Faith, Channel Divinity, sword & shield | 39 + 310 = 349 |
| **SPEAKER_07A** | Folsom | raw00 — the returning drunkard (3–7); Bard: Vicious Mockery, Charm, Cutting Words, Bardic Inspiration, Message, Healing Word | 51 + 146 = 197 |
| **SPEAKER_01B** | The knight | The Earl's mounted knight/commander — the standalone challenge lines ("Who are you? State your name") | 8 |

Raw layout (this file): **raw00 = Folsom**, **raw01 = Merrick**, **raw02 = DM**, **raw03 = Gouge**, **raw04 = Tyrus**. (Note: differs from *Party Reintroduction*, where raw00 = DM and raw02 = Folsom — the diarizer re-numbers per file.)

## Continuity note (RESOLVED by author): Gouge is a Fighter/Rogue
This scene lets the DM name each PC out loud during their initiative turns, so the raw→name mapping is now **certain** (not inferred). It confirms:
- **Merrick = the coastal ranger** (Fog Cloud, Hunter's Mark, and literally "the coastal terrain is your terrain") — this matches your earlier ruling *"Merrick has coastal experience."* ✅
- **Gouge = the rogue/assassin** (heavy-crossbow sneak attacks, Assassinate, cunning action, scimitar + dagger).

**Author-confirmed: Gouge is a Fighter/Rogue multiclass.** That reconciles both scenes — he uses **Second Wind** in *The Party Waits for Owen's Return* (Fighter) and **sneak attack / Assassinate / cunning action** here (Rogue). Gouge = 04A throughout. This also retroactively **confirms the previously-tentative PC mapping in *Party Reintroduction*** (Merrick = raw01, Gouge = raw03, Tyrus = raw04) — no longer tentative.

## Point of the conversation
Still on the cliffs above the wharf (~10 p.m., 6th Wealsun), Merrick debriefs Folsom on his near-capture and Owen's interest in the amulet that controls the turtle dragons. Merrick then spots a **military unit** approaching down the shore — ~10 men-at-arms in archaic **ring mail** carrying halberds, led by a **mounted knight in chainmail** dressed as a mainland Keoish knight: the DM reads them as the **Earl of Regfort's household guard** (heavy, land-bound, dangerous — "not Toli rats"). The unit searches Owen's empty sloop, finds nothing, and the knight spots Folsom. Folsom improvises, staggering out as a **drunkard** and giving his name as **"Owen"** — and the knight, believing he's found **Owen Black**, orders him seized ("the Earl wants to speak with you"). Tyrus joins the drunk act; the ruse collapses ("there's more of them! roust the bushes!") and **combat erupts**. Merrick drops a **Fog Cloud** for cover; Gouge snipes from stealth (a 28-damage assassin crit); Tyrus **Thunderous-Smites the knight off his horse**; Folsom charms/mocks and buffs the party. The men-at-arms prove tough (shield-wall, dodging) and reinforcements keep coming, so the party breaks contact and **flees up the rocky ridgeline toward the south shore**, Merrick leading them through his home coastal terrain where the heavy troops can't follow.

## Canon / continuity notes
- **The pursuers:** the **Earl of Regfort's** men-at-arms + mounted knight — old-fashioned **ring mail / chainmail** heavy troops (Keoland-style), contrasted with the Principalities' scale-mail marines. They "never leave the beach" and don't take ships. Worth a note in the faction/enemies material.
- The knight **mistakes Folsom for Owen Black** — the hunt is (at least ostensibly) **for Owen**, which Folsom later uses to argue the guard "might be on our side" (against Owen). Open question of who the Earl is really after.
- **Merrick's coastal ranger identity** is established firmly here (favored terrain + perception expertise + leading the party cross-country).
- Callback: Owen's interest in the **amulet that controls the turtle dragons** (ties to the Orb of the Dragon Turtle / Cain Toli material).

## Names / garbles to normalize in prose
- **"six of the Wealsun" / "10 p.m. in the morning" (1)** → 6th of Wealsun, 10 p.m.
- **"Red Shore" (21)** → **Redshore**.
- **"Keoland" / "Keog knight" (62, 80)** → Keoland / **Keoish** knight; **"Earl of Regfort" (82)** → author to confirm spelling (ASR).
- **"haliburds/halibirds/holobirds/halibut" (61, 86, 208, 847, 1246, 1822)** → **halberds**.
- **"the men-at-war" (69–70)** → **men-at-arms**; **"Gradsolian fleet" (72)** → author to confirm (the Principalities' fleet).
- **"Thunderous might/Syrinx mic" (716, 1271)** → **Thunderous Smite**; **"Searing Smite"** (1278) OK.
- **"the Anish / roll an edge / roll the niche" (627, 873, 260)** → initiative ("roll for initiative").

## Hardest calls / flagged ambiguities (author: please correct)
- **RP vs. mechanics boundary in a fast combat scene is approximate.** I kept dice/AC/feet/rules as `[game mechanics]` and pulled out in-character dialogue, shouted lines, and pure narration as roleplay — but many turns interleave a spoken line with a movement count on the same breath. Scan the transitions.
- **Inline NPC voices stay on the DM (00A).** The knight's and men-at-arms' lines are almost all embedded inside DM narration frames ("the guy says, …"), so they remain DM narration; only the knight's clearly standalone challenge (158–162, 172–177) is split to **`01B`**. If you'd prefer every NPC quote pulled to a B-tag, say so and I'll re-split (it needs light text surgery on the embedded lines).
- **Out-of-band (77 lines):** real-world/table talk kept on raw diarizer tags — e.g. "Folsom's phone rings" (220), the minis/Monster-Manual/"Brad" setup (486–511), "Mac and cheese?/KK" (1074–78), "Hot pockets!" (1938–39), "Cliffs of insanity" (1977), the Chicago work-meeting aside (2048–61). Confirm none of these were actually in-character.
- **Untagged source lines** (185 "Be drunk", 1253–54, 1506, 1731, 1773, 1857–58) were assigned by context — 1857–58 "Nope. Nope." → Merrick; 185/1506 → out-of-band; the rest → mechanics.

## Speaker discontinuities
- raw02 (DM) carries all narration, adjudication, and inline NPC voices, plus scattered bled PC lines (e.g. 134–136 crossbow talk; 163 "Who, me?" and 174 "My name's Owen" are Folsom's, reassigned to 07A). Separated by content.
