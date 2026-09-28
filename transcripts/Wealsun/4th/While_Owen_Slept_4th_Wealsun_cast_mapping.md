# Cast Mapping — While Owen Slept (4th Wealsun)

`While_Owen_Slept_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge (PC), Merrick (PC), Folsom (PC), Tyrus (PC, near-silent), the DM. Owen Black (NPC) is asleep the whole scene — no dialogue.
**In the room (4 voices):** three players on deck (Gouge, Merrick, Folsom) plus the DM. Tyrus sleeps first, then takes the last watch; Owen is in his cabin.

## Speaker → character mapping (final, character-locked; crew registry)
This is the **ship-crew thread**, same registry as *Departure from Monmurg*: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`, Folsom `07A` (Owen would be `01B` but has no lines here).

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration / night-sailing adjudication / the gap-run | 40 |
| **SPEAKER_04A** | Gouge | PC — blunt; runs the watch-changing and wake-up rounds | 50 |
| **SPEAKER_05A** | Merrick | PC — at the helm all night; the planner ("pry Owen's mind," get cozy with Cain Toli) | 58 |
| **SPEAKER_06A** | Tyrus | PC — only volunteers to sleep first (9–10); otherwise silent | 2 |
| **SPEAKER_07A** | Folsom | PC — woken to charm Owen; already writing a song | 31 |

Raw diarizer layout: **raw02** = DM, **raw01** = Merrick, **raw03** = Gouge, **raw00** = Folsom (with several crew asides bled onto it).

## Point of the conversation
With Owen asleep, the three crewmen on deck talk strategy through the night. Merrick, at the helm, lays out the plan: learn everything about Owen and how he ties to the Helm Island incident, get close to **Cain Toli** through Owen, and — since Owen likes Folsom — have Folsom charm him with a flattering song and become his best friend to keep him talking. Gouge agrees he's the wrong man to earn trust and judges Owen "a helpful idiot," not deeply involved. Overnight the ship runs the gap between the islands (Merrick hugging the shoreline off-center to avoid Commodore patrols), the last of the dead sahuagin wash out, and at four in the morning the watch rotates: Gouge wakes Folsom, Folsom is sent up to relieve Merrick and then to wake Owen, and Tyrus takes the deck for the final four hours.

## Flagged ambiguities (author: please correct)
- **raw00 bleed (mostly resolved by author).** **9–10** (volunteering to sleep + the "no singing at night" jab) read as **Tyrus**, the one who goes to bed — verify. **24–27** (the "odd deal" suspicion about Owen's escape) → **Gouge**; **31–32** ("I agree… he might know enough") → **Merrick**; **46–49** (mission-focus) confirmed **Folsom**.
- **Lines 130–131 "You've had your aid, right? / Yes"** — tagged `[game mechanics]` (looks like a check on the *Aid* spell buff during the wake-up). If it's just "had your rest," it's in-band — verify.
- **Lines 159–161** ("Well, I was a part of you, but thank you for a reason… If there's a problem, wait, it's all up") are heavily garbled ASR right before the out-of-band block; may be trimmed or are OOC — left in-band on Folsom, flagged.
- **Garbles to fix in prose:** "Bart" (9) and "op-munk" (134) are ASR garbles; "Evan" (46) and "Ellen" (102) = **Owen**; "Kane Tolley" (28) = **Cain Toli**; "sahagin" (95–96) = **sahuagin**; "Bard Charm" (38) = Merrick referring to Folsom's bardic charm.
- Tyrus has no real lines beyond 9–10; he is handed the deck at the very end (135 "send Ty down," 179–184).

## Game mechanics (attributed)
**130–131** — the *Aid*-buff check during the four-a.m. wake-up (Gouge asking `04A`, Folsom answering `07A`). See flag above.

## Out-of-band (raw tag kept)
**162–164** — a real-world/OOC exchange with a modern reference ("YouTube growth done? / I'm out / That's a fucking dick"). Story resumes at 165.

## Speaker discontinuities
- raw00 shifts among players (Folsom primary, with Gouge/Merrick/Tyrus asides) without a tag change.
- raw02 stays the DM throughout; Owen Black never speaks (asleep).
