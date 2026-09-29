# Cast Mapping — Folsom Talks with the Marines (7th Wealsun)

`Folsum_talks_w_marines_7th_Wealsun.txt` · Book Two (ship-crew storyline). Folsom, in a merchant persona, pumps a Keoland marine sergeant for information at the Redshore docks. Short scene. Maps the diarization speaker tags to who is talking. **Character-locked tags:** A-series = PCs/DM; B-series = NPCs.

**Cast (index):** the DM, Folsom (PC), and the **marine sergeant** (NPC, DM-voiced) — matches the `.cast.txt` hint.
**Format:** entirely in-character dialogue. **No dice, no out-of-band.** The marine gets a B-tag.

## Speaker → character mapping (final, character-locked)
Registry: DM `00A`, Folsom `07A`. NPC: **marine sergeant `01B`** (DM-voiced).

| Tag | Character | Basis | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM (narration) | The single framing line ("you walk up to a couple of marines") | 1 |
| **SPEAKER_07A** | Folsom | The merchant act: questions, the concerned-citizen reactions, the "lost my company" cover story | 22 |
| **SPEAKER_01B** | Marine sergeant | NPC (DM-voiced): explains the patrol, the trade situation, and lets slip the "foreign spies" line | 18 |

**⚠️ Diarizer was scrambled — reassigned per line by content.** The two raw tags did **not** map cleanly to speakers: raw `SPEAKER_01` carried Folsom's lines **and** the marine's "What do you want?" (4) and "Oh, you're a merchant?" (22) and "You can call me Sergeant" (34); raw `SPEAKER_00` carried the marine's answers **and** Folsom's "Oh my goodness" reactions (10, 14). I split the whole scene into **Folsom `07A`** vs **marine `01B`** (plus the one DM narration line) by who is speaking.

## Point of the conversation
Folsom approaches the newly-arrived dock patrol in the guise of a nervous merchant. He flatters the marines ("officers"), asks why they're patrolling, and the **sergeant** explains: the captain posted a detachment because of the **bloodshed at the Chart Room** a night ago — noting the killers "were a little bit more skilled than many" (i.e., the party). Folsom plays the worried bystander, then pivots to his cover: he's a merchant who "lost his company" and wants to trade back to **Monmurg**. The sergeant says **Monmurg is shut down by order of the Duke of Gradsul** and suggests alternatives — a **new dock opening at Saltmarsh**, or taking wares to **Seton**, where ships still run. Folsom thanks "the Sergeant," and the scene closes on dramatic irony: the sergeant says **"we don't want those foreign spies to cause any more trouble"** — to the very spy he's been chatting with — as Folsom shakes his limp, clammy hand.

## Canon / continuity notes
- **Official account of the Chart Room killings:** the authorities know six were killed and that the killers were unusually skilled; a marine detachment now patrols the docks in response.
- **Monmurg is formally closed** "by order of the Duke of Gradsul" — the embargo stated from the enemy's side.
- **Alternative trade routes:** a **new dock at Saltmarsh** and shipping via **Seton** — places goods can still move (useful geography for the crew's escape/trade plans).
- **The marine is a Sergeant.** His "foreign spies" remark shows the authorities suspect outside agents are behind the trouble.

## Names / garbles
**Applied to the body** (author-canon): "Duke of Gratzel" (26) → **Duke of Gradsul**.
**Noted for prose (not changed in body):**
- **"ne'er-de-wells" (12)** → **ne'er-do-wells**.
- **"Saltmarsh" (29)** and **"Seton" (30)** — place-names; confirm spellings (both plausibly canonical Greyhawk/Sea-Principalities locales).

## Hardest calls / flagged ambiguities (author: please correct)
- **Whole-scene reassignment** (see the ⚠️ note): the diarizer interleaved Folsom and the marine on both raw tags, so I rebuilt the attribution by content. High confidence — it's a clean two-person exchange — but please skim to confirm none of Folsom's reactions were actually the marine's, or vice versa.
- **Line 39 "Thank you"** (on the marine's raw tag) was given to **Folsom** (his closing thanks before shaking the sergeant's hand); could instead be the marine. Minor.
- No `[game mechanics]` or `[out-of-band]`.
