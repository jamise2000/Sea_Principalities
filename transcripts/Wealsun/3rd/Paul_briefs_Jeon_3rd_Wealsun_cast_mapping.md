# Cast Mapping — Paul_briefs_Jeon (3rd Wealsun)

`Paul_briefs_Jeon_3rd_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — here each tag carries the DM's narration, an NPC's dialogue, *and* a player's out-of-character asides, and the two tags bleed into each other badly. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Paul.
**In the room (2 voices):** the **DM** (narrating + voicing **Prince Jeon**, rendered "Gian"/"John") and **Paul**'s player (in-character Paul + out-of-character asides). This is Paul's private debrief with Prince Jeon; Jamis is explicitly *not* present (lines 38–41).

## Speaker → character mapping (sub-tags applied to the body)

Two people in the room: **Prince Jeon** (voiced by the DM, who also narrates) and **Paul**. The diarizer's two tags bled, so the body has been split into sub-tags:

| Sub-tag | Who |
|---|---|
| **SPEAKER_01A** | DM / **Prince Jeon** (narration + Jeon's dialogue) — dominant of tag 01 |
| **SPEAKER_01B** | **Paul** — his lines the diarizer filed under tag 01 |
| **SPEAKER_00A** | **Paul** — dominant of tag 00 |
| **SPEAKER_00B** | DM / **Prince Jeon** — his lines filed under tag 00 |

So **Jeon = {01A, 00B}** and **Paul = {00A, 01B}**. Assignment follows the author's rules: Helm/mission **questions → Jeon**, mission **answers → Paul**; **history/family questions → Paul**, those **answers → Jeon**.

- **Flipped to Paul (01B):** 4, 14, 23, 27, 40, 42, 47, 49, 97, 153, 154, 157, 177, 180, 188–190, 193, 200, 201, 242, 280, 284, 288, 296, 321, 323, 325, 332, 333, 336, 339, 344, 349, 361, 362, 369, 370, 395–397, 400, 413, 414, 420, 439, 442, 444. *(242, 284, 332, 333, 336, 339 added per author review — Paul's pushback in the Fairwind/family exchange.)*
- **Flipped to Jeon (00B):** 34, 67, 72, 84, 92, 93, 94, 141, 186, 291, 446.
- **Least certain — please check:** 84 ("The Toli?" echo), 97 (Paul recounting the overheard Toli speech), 141 ("Treason."), 186 ("And that was the Toli ship?"), 200–201 ("We saw them sending ships…"), 396–397 ("a wizard spy").

## Flagged ambiguities (author: please correct)

- **The tags bleed heavily; attribute line-by-line by content, not by tag.** Clear examples where the tag is "wrong":
  - Jeon's own questions are tagged **SPEAKER_00** at 34 ("Tell me more of that"), 36 ("How do you know this?"), 72, 92–94, 130, 133, 135–138 — these are Jeon (the DM), not Paul.
  - Conversely, Paul's answers land under **SPEAKER_01** in places through 178–202 and 288–302.
  - The stretch 25–49 alternates almost every line; read it as Jeon-asks / Paul-answers regardless of tag.
- **Line 405 "American Gouge."** is ASR garble (likely "What about Gouge?" or "And Merrick, Gouge"); not a character. 
- **Line 191–194 "Kane Tolley…"** — canonical **Cain Toli** (see Name Normalization Key); here it's Jeon/Paul speculating who captains the *Sea Ghost*.

## Out-of-band table chatter
Tagged `[out-of-band]` in the body: **20, 21, 22** (OOC "who says this to me? / Gian / Gian, okay" — clarifying the speaker), **44** (contains modern slang "sus"), **127** ("Is that what we did?" — checking with the DM), **230, 231** ("Am I forgetting one? / That's about it" — OOC party roll-call). Everything else is in-story (Jeon's charge and Paul's account), even where the tag is wrong.

## Speaker discontinuities
- None of the "reading the wrong part" type here. The only discontinuity is the pervasive tag bleed noted above.

## Notes for the drafter
- This is the scene that gives Jeon's charge to Paul (learn the arcane under Jude; crack the powder; find Fairwind's stash) and the family thread — **Grayson** (Paul's father) and Paul's mother named as brilliant (265–266). Powder figures here (20-year/decades cutoff, "one barrel covers the strait," 150 years) are the transcript's; canon figures live in `worldbuilding/The_Anti-Sahaugin_Powder.md`.
