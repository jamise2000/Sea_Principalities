# Cast Mapping — Paul_briefs_Jeon (3rd Wealsun)

`Paul_briefs_Jeon_3rd_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — here each tag carries the DM's narration, an NPC's dialogue, *and* a player's out-of-character asides, and the two tags bleed into each other badly. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Paul.
**In the room (2 voices):** the **DM** (narrating + voicing **Prince Jeon**, rendered "Gian"/"John") and **Paul**'s player (in-character Paul + out-of-character asides). This is Paul's private debrief with Prince Jeon; Jamis is explicitly *not* present (lines 38–41).

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_01** | **DM** — scene narration + **Prince Jeon** ("Gian") | Many of Paul's replies (tag bleed), and Paul's OOC clarifications | Opens with narration ("Paul Rivero returns to Monmurg… led to John's office," 1–19); delivers Jeon's long charge — Grayson, the powder, the tutoring, "I charge you…" (258–443). "Gian" named as the speaker at 21. |
| **SPEAKER_00** | **Paul** (the PC — his first-person account) | Some of Jeon's questions/interjections (tag bleed) | Delivers Paul's first-person Helm account ("We sailed to the island… Me, Jude, and 20 other Marines," 50–64, 106–134) and his assessments of the party (217–257). |

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
