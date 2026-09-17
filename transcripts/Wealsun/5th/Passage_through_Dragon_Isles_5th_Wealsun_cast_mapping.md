# Cast Mapping — Passage through the Dragon Isles (5th Wealsun)

`Passage_through_Dragon_Isles_5th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Folsom, Tyrus, Gouge, Merrick, *Owen Black (DM-voiced).
**In the room (5 voices):** the four players (Folsom, Tyrus, Gouge, Merrick) plus the DM, who narrates and voices Owen Black. This is the hardest file to map — four players share three player-tags and both Merrick and Folsom each land in two different tags.

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_00** | Merrick (watch leader, decision-maker) | Owen Black answers bleeding in (277–279, 322–323, 331–334); OOC dice/map/stat talk from Merrick's player | L502 "Gouge, I think I'm going to take the ship towards Kane Tolley's Island" (addresses Gouge); L372 "who's up there with me? Is it Folsom and Tyrus?"; L641–670 examining the water; L803–813 tasking Folsom |
| **SPEAKER_01** | **DM narration + Owen Black (in-character)** — the primary voice of the file | player-action bleed (L656 "I look at the water") | L1 scene-set narration; L38–39 "It's the black rum, I'm fine"; L53–232 Owen's storytelling; L603 "Well, cousin, you got as far, I can see the dragon isles" |
| **SPEAKER_02** | Gouge | **Merrick** (esp. L257–313, waking + ship discussion); Owen bleed (L107 "These were just rumors", L155–156 Turtle Island correction); L40–41 likely Folsom bleed | Gouge: L354 "What are the odds we can get paid higher…" → L356 Owen "I don't think we could catch him, **Gouge**"; L337 "So I was yelling at **Merrick**…" (3rd person → Gouge); L778–786 "I go down, kick his bunk… Get your ass up" (wakes Folsom) |
| **SPEAKER_03** | Tyrus (early: on deck, spots the Sea Ghost, wakes the crew) | **Folsom** (L594 "I'll sleep with Tyrus"; L793–795 "Call me if you need me"; L816 "I give out audible signs") | Tyrus: L16 "Better than most and half as bad as the rest" (answers Folsom about Owen); L200–256 sights ship, wakes Gouge/Merrick; "I'm Danny" OOC at L6 |
| **SPEAKER_04** | Folsom (the charm offensive — pumping Owen for lore) | — | L14 "I'm gonna walk over to Tyrus"; L17 "Merrick told me to write a song… get some information out of them"; L379–393 debriefing Merrick; L816–889 the flattery/interrogation of Owen |

## Flagged ambiguities (author: please correct)
- **Merrick appears in BOTH SPEAKER_00 and SPEAKER_02.** The waking/ship-sighting block (L257–338) drifts between Merrick (00) and Gouge (02); L295–313 (map discussion — "This is towards Redshore… Nobody goes that way") could be either; I read it as Merrick, but L327–338 is clearly Gouge (he narrates "yelling at Merrick").
- **Folsom appears in BOTH SPEAKER_04 (primary) and SPEAKER_03** (L594, 793–795, 816). L18–31 in SPEAKER_03 is Tyrus telling Folsom about Owen's story, but "It'll go very nicely in **my** song" (L22) is a Folsom line — either a bleed or Tyrus loosely quoting Folsom's purpose. Verify who says L18–31.
- L40–41 (SPEAKER_02, "Not until noon, anyway. I don't blame ya") — responds to Owen about the rum; most likely Folsom, but Merrick was asleep so a stray tag. Confirm.
- L149–151 ("Right here, Cain? / Not right now. / Cool.") reads as table map-pointing (see out-of-band), not in-story.
- L306–307 (SPEAKER_04, "He's heading east… from Dragon Isle") — direction call, could be Folsom or a DM bleed.
- L656 "I look at the water" is tagged SPEAKER_01 (DM/Owen) but is a player action (probably Merrick).

## Out-of-band table chatter
Tagged `[out-of-band]` in the body: **6** ("I'm Danny" — real player), **94** ("I'm still sleeping, right?" — rules clarification), **124–134** (charisma/persuasion check on Owen's story), **149–151** (map-pointing: "Right here, Cain? / Not right now. / Cool."), **213** & **217–219** (perception check on the sighted ship), **396–418** (int-check mechanics: "Do an int check… at disadvantage… Five" + "He's wise, not smart" / "They put you in charge?"), **469–474** (DC talk "higher than my 12" + the healing-potion prop turning white-to-red + "I had to drain the tank"), **476–479** ("What is red? / Cherry juice…" — drink/prop), **758–769** (inventory reconciliation of who holds the yellow-white powder / vial vs packet), **846–851** (persuasion check, nat 20). (All are dice/DC mechanics, real-name/prop/drink talk, or logistics; the surrounding in-character storytelling stays in-story even where the tag is wrong.)

## Speaker discontinuities
- Untagged lines (no `[SPEAKER_##]:` prefix): **L244** ("Okay."), **L385** ("No."), **L453** ("Barrels.") — assign from context (244 ≈ Gouge/DM as Folsom wakes him; 385 ≈ Owen; 453 ≈ DM/Owen reading the book).
- L656 carries a player action under the DM/Owen tag (SPEAKER_01).
- Lines 454–459 (SPEAKER_01) are the DM **reading aloud from Merrick's book** (the Pocra Sententia / sahuagin / yellow-white powder passage) — in-story as read text, not Owen's voice.
