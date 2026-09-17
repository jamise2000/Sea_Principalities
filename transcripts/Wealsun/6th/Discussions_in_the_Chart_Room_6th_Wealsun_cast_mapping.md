# Cast Mapping — Discussions in the Chart Room (6th Wealsun)

`Discussions_in_the_Chart_Room_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Merrick, Tyrus (PCs), the DM, and — from the ambush at ~177 — the **Mob leader** (NPC, DM-voiced, a Toli-accented Suel man).
**In the room (4 voices):** three players (Merrick, Gouge, Tyrus) plus the DM. Folsom and Owen are off dealing with merchants. The scene runs from the blockade theorizing into the opening of the bar ambush, and hands directly into **Blood_on_the_Charts**.

## Speaker → character mapping (final, character-locked; crew registry)
Crew registry: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`. The ambush leader is the scene's only NPC → **`01B`**.

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration / adjudication / the ambush setup | 81 |
| **SPEAKER_01B** | The Mob leader | NPC — Toli-accented Suel interrogator who springs the ambush | 12 |
| **SPEAKER_04A** | Gouge | PC — pushes the "who benefits" logic; fences with the leader | 45 |
| **SPEAKER_05A** | Merrick | PC — drives the deduction | 71 |
| **SPEAKER_06A** | Tyrus | PC — the song angle; stalls the leader ("deckhand") | 49 |

Raw layout: **raw00** = Merrick; **raw01** = DM **and** the Mob leader (from ~177); **raw02** = Gouge; **raw03** = Tyrus.

## Point of the conversation
With Owen and Folsom off dealing, the three crewmen sit in the **Chart Room** and reason out the blockade: why won't Monmurg break three warships penning ~50 merchantmen? It isn't about money — something **more powerful than the Monmurg navy** must be holding Prince Jeon back. They land on it: the **turtle dragons**, controlled by **Cain Toli's artifact**, are what bottle up the fleet (storms, fogs, ships lost — the same power they glimpsed at Helm). Mid-deduction, **eight Toli thugs** quietly surround them, and a **Toli-accented Suel leader** starts probing — new to Redshore? merchants? what's your business? The crew stalls (Tyrus: "deckhand"; offers to buy the man an ale) until the leader drops it: his associates have them surrounded, clubs in hand, waiting for the word. As the crew maneuvers (Merrick rising to "go past him to piss"), the leader shouts **"get out!"** and the thugs rush in — straight into **Blood_on_the_Charts**.

## Hardest calls / flagged ambiguities (author: please correct)
- **Line 178 "you look over and he is Sewell"** — "Sewell" is an ASR for **Suel**: the DM is saying the leader **is a Suel man**, not naming him. He's the **Mob leader** NPC (the "Mob_leader" of the following combat file). Kept as `01B`; no name assigned.
- **The DM shares raw01 with the Mob leader** from ~177. I split them by voice: the leader's dialogue (177, 179–183, 191, 193, 197, 201, 203–204) → `01B`; scene description (178, 195, 205–221) → DM `00A`. Please scan.
- **Pre-fight positioning (222–228)** drifts as everyone maneuvers: 222 "Tyrus, why don't you stand up?" I read as the DM's prompt; 223 "don't get your panties in a wad" → Merrick; 224–225 → Gouge; 226 → Tyrus; 227–228 → Merrick. Both Gouge (224) and Merrick (228) narrate getting up "to piss" — likely one bit doubled across tags.
- **68** — corrected per author to "**Jeon would never do this to the Sea Principalities**" (DM, `00A`).
- **257 "This guy goes, get out!"** — kept as DM narration (the leader's attack shout reported); render as the leader in prose.

## Game mechanics (attributed, 51 lines)
Dice, checks, and combat setup: **23–25** (wisdom check), **71, 74–75** (Merrick's perception), **95** (a roll), **136–149** (the muddled nature check on turtle dragons — Gouge rolling), **155–159** (Tyrus's perception that spots the thugs), and **229–253** (the full combat setup — placing barrel tokens, choosing minis, character-sheet checks). DM instructions/results → `00A`; rolls → the roller.

## Out-of-band (raw tag kept, 1 line)
**39** ("Sorry, this is going to be loud" — a real-world mic/volume aside).

## Names to normalize in prose
"Prince John / Gian / Gion / Jean" → **Prince Jeon** (and L68 "his sister" → "the Sea Principalities"); "Cain Tolley" (104) → **Cain Toli**; "Hell Island" (152) → **Helm Island**; "Calceres" (165) → **Corsairs**; "Sewell" (178) → **Suel** (descriptor, not a name).

## Speaker discontinuities
- raw01 absorbs the Mob leader from ~177 (watch the DM↔leader switch mid-tag).
- Untagged lines resolved: **24** → game-mechanics roll (Gouge), **185** → DM, **251** → game-mechanics ack.
- Scene ends mid-action and continues in **Blood_on_the_Charts**.
