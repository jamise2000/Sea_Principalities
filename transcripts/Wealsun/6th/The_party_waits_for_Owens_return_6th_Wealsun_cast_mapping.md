# Cast Mapping — The Party Waits for Owen's Return (6th Wealsun)

`The_party_waits_for_Owens_return_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, class features, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Merrick, Tyrus, Folsom (PCs) and the DM. **No NPC speaks** — Owen, Torus and Cain Toli are only referenced.
**In the room (5 voices):** all four crew PCs plus the DM. Gouge and Folsom rejoin Tyrus and Merrick on the dock and the whole party debates its next move.

## Speaker → character mapping (final, character-locked; crew registry)
Crew registry: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`, Folsom `07A`. No B-tags used.

| Tag | Character | Role | Lines (rp + mech) |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration + adjudication | 50 + 9 = 59 |
| **SPEAKER_04A** | Gouge | PC — **fighter**; runs the debrief (he met Folsom in the alley), argues to stay; uses **Second Wind** | 67 + 9 = 76 |
| **SPEAKER_05A** | Merrick | PC — **rogue**; wants to loot Owen's quarters, invokes coastline **Expertise** for the hideout | 18 + 1 = 19 |
| **SPEAKER_06A** | Tyrus | PC — paladin; presses to find the ship, uses **Lay on Hands** | 48 + 2 = 50 |
| **SPEAKER_07A** | Folsom | PC — recounts the capture, the pouch, the artifact questions | 22 |

Raw layout: **raw02** = DM; **raw00** = Folsom; **raw01** = Tyrus; **raw03** = Gouge; **raw04** = Merrick — with heavy DM/player bleed across all tags in the opening and scattered cross-talk throughout.

**Class-feature lock (how the four PCs were disambiguated):**
- **Gouge `04A` = raw03** — asks "do I get a fighter lay on hand thing," DM gives him **Second Wind** ("that many hit points plus your level back in fighter," 212–215). Fighter.
- **Merrick `05A` = raw04** — "This is still coastline, so I have **expertise** here… I've got expertise" (171–174). Rogue.
- **Tyrus `06A` = raw01** — "I'm going to use my **lay on hands**" (190–191). Paladin.
- **Folsom `07A` = raw00** — the only one who recounts the capture first-hand (42–44, 65, 67–73, 79–86).
- **DM `00A` = raw02**.

## Point of the conversation
Gouge and Folsom walk back up the darkening dock (~10 p.m.) to Tyrus and Merrick, who have been guarding the sloop. **Gouge** gives the short version — **Owen betrayed them**, sent men to kill/capture the party, tried to have Folsom taken prisoner, and got away — and forces the decision: **flee by sea now, or stay.** **Folsom** fills in the details: Owen paid off a stranger (a pouch he claimed was a debt — really silver, to hire the bar thugs), had only one man on the ship, and was pressing Folsom about **the artifact** (which Tyrus, who slept through the earlier reveal, doesn't yet know about). They correct the name **"King Tolley" → Cain Toli** (the DM confirms there is no King Tolley). Reasoning that Owen has no real muscle left — he'd have used his own men, not street-hired thugs — and that fleeing means a slow chase and turtle-**dragons** at sea, they **decide to stay**. They rule out hiding on Owen's own ship (too obvious) and instead **hole up on the hill above the dock**, from which they can watch the moored sloop, keeping to the woods with provisions (and a crate of black rum). They **light the ship's lanterns as bait/signal**, set a two-and-two watch, patch wounds (Tyrus spends Lay on Hands, Gouge takes Second Wind), and settle in overlooking the bay.

## Hardest calls / flagged ambiguities (author: please correct)
- **The recap (22–41) is Gouge's tag `04A`** — this fits: Gouge met Folsom in the alley (*Gouge Waits in the Dark*) and they walk back "talking quietly to one another" (line 2), so Gouge has the story to relay. The finer details (the pouch, the artifact) are Folsom's and he supplies them from 42 on.
- **Line 35** ends with an interjected question — "…we need to stick together because we're all… **Why would Owen double-cross us like that?**" — which is a *listener* cutting in (Tyrus or Folsom), then answered in 36 ("That's not what I'm worried about right now"). **Candidate split** into a Gouge line + a listener line; left merged because I can't cleanly attribute the interjection.
- **Opening guard-bleed (1–20):** heavy DM/player cross-talk about who can see whom and who's on the deck vs. the dock. DM narration (1, 7, 9, 11, 13–14, 16, 20) → `00A`; watcher/positioning questions split to Tyrus (8), Merrick (10, 12) and Gouge (17–18, 19) by best guess. Please scan.
- **138–143 landed on Folsom's tag (raw00)** but concern the **bar interrogation Folsom wasn't present for** ("they weren't hired by Owen… hired by the guy that's dead"). Reassigned to **Gouge `04A`** (who was at the bar). Verify — could be Merrick.
- **Artifact Q&A (63–73):** the questions pressing Folsom ("what were they asking you about," "which was, what artifact?") are split to the PC who *doesn't* know — **Tyrus `06A`** (he slept through the reveal; cf. 73 "you were sleeping," 74 "what the fuck is going on here"). Line 69 ("what do you know about the artifact that Owen didn't know?") → **Gouge `04A`**. Please scan.
- **91** "He said it was for Tyrus as well" sits on Merrick's tag `05A` but is **Folsom's** knowledge (Owen called the trap-sloop "Tyrus's new boat" in *Owen Shows His Face*). Verify speaker.
- **Rum banter (197–198)** — "I'll take a couple bottles, and I ain't sharing… I don't need it" — is in-character PC talk that landed on the **DM's** tag; 197 → Merrick `05A`, 198 left `00A`. Confirm.
- **207** "I do" (needs rest) is a reply from one of the two resting PCs but sits inside Gouge's watch-assignment run `04A`. Minor.

## Game mechanics (21 lines, attributed to A-tags) & out-of-band (1 line)
- `[game mechanics]`: **62** (int check → DM `00A`); **190–191** (Tyrus's Lay on Hands → `06A`); **201–203** (hiding the party / "using the skills" → DM `00A`, party's "yes" → Merrick `05A`); **212–226** (the Second Wind rules exchange → Gouge `04A` / DM `00A`). These carried an `[out-of-band]` prefix in the raw file but are rules/dice talk, so they were reclassified to `[game mechanics]` with the speaking character's A-tag.
- `[out-of-band]`: **15** ("I'm walking, I'm going like this" — a player gesturing at the table). Raw tag kept.

## Names / garbles to normalize in prose
- **"King Tolley" / "Cain Tolley" / "Cain" (47–60)** → **Cain Toli** (the DM explicitly corrects: there is no King Tolley).
- **105** "a crater that black we're on" → "a **crate of that black [rum]**" (cf. 195 "that crate of black rum").
- **115** "**Himx** comes back" → "**He** comes back" (ASR garble).
- **165** "An **N** to stay in" → "an **inn** to stay in."
- **172** "this whole **aisle** went" → "this whole **isle**."
- **204** "**Shadows, me, said**, I'll stay up watching" → likely "[In the] shadows… I said, I'll stay up watching."
- **Owen Black**, **Torus** (Cain Toli's Suel handler) and the **Orb** (the artifact) are referenced but no NPC is present.
- **Insamiar note:** not referenced by name here, but the artifact/Cain-Toli thread continues; a `Name_Normalization_Key.md` cross-reference for the "gift of Insamiar" (from *Owen and Torus Plan*) is still open — note `Insamiar_the_Black.md` already exists in the worldbuilding folder.

## Speaker discontinuities
- Dense DM/player bleed through the opening (1–20).
- The debrief recap (22–41), the artifact Q&A (63–73), and the escaped-thugs discussion (137–143) all cross tags and are separated by content as noted above.
