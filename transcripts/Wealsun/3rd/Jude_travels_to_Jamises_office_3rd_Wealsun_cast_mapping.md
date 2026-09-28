# Cast Mapping — Jude_travels_to_Jamises_office (3rd Wealsun)

`Jude_travels_to_Jamises_office_3rd_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking. **A tag is a voice, not a fixed character.** Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Jude.
**In the room (2 voices):** the **DM** (narrating + voicing **Lord Jamis**) and **Jude**'s player (in-character Jude + out-of-character asides). Jude's private debrief with Lord Jamis, brought in by a hidden route.

## Speaker → character mapping (two tags)

Two people in the room: **Lord Jamis** (voiced by the DM, who also narrates) and **Jude**. Per the author's convention the sub-tag names the **character**, so every line is one of two tags:

| Tag | Who |
|---|---|
| **SPEAKER_01A** | DM / **Lord Jamis** (narration + Jamis's dialogue) |
| **SPEAKER_00A** | **Jude** |

The diarizer's original bleed has been resolved to the correct character (e.g. 22 "You realize that" → Jamis/DM; 36 and 79 → Jude; Jude's asides at 35, 47, 50, 52, 63, 200, 202, 213, 232 → Jude; Jamis's "They answer to me" at 78 → Jamis). Out-of-band table chatter keeps the `[out-of-band]` prefix.


## Flagged ambiguities (author: please correct)

- **Tag bleed** (attribute by content): e.g. **78 "They answer to me."** is Jamis but tagged SPEAKER_00; some Jamis lines around 108–115 (about Tyrus) sit right, but a few of Jude's replies fall under SPEAKER_01.
- **Line 41 "Walking around the Dallas district or whatever."** — "Dallas" is ASR garble for the district (Harbor/Foreign District); not a real place-name.
- **Line 249–251 "Baron of Redlaw / Red Shore"** — the noble Jude spoke with is tied to **Redshore** (canon spelling); "Redlaw" is a mis-hearing. Whether he is the **Earl of Redshore** (canon title) or a separate "Baron" is unresolved — see `characters/Earl_of_Redshore.md`.

## Out-of-band table chatter
Tagged `[out-of-band]` in the body: **5** (OOC "remind the DM" — but note it conveys a real action: Jude pocketed some powder to study), **105, 106** ("now this is to the DM… is the big guy a paladin? / Did I ever see him smite?"), **134, 135, 136** (the "reading Paul's part" correction — see below), **214** ("What'd you say?" — the DM mishearing the ring quip). The rest is in-story.

## Speaker discontinuities
- **Jude's player was reading Paul's part (lines 128–136).** At 134 the player says: *"sorry, to the DM I think I was accidentally reading Paul's part so I wouldn't know that… That was actually what Paul would have."* So the detail of **what Fairwind admitted aloud in the inner sanctum** (that he'd been siphoning barrels for months, 127–133) is **Paul's** first-hand knowledge, not Jude's — Paul is the one who scouted ahead with the homunculus. When drafting, credit that overheard admission to Paul's POV, not Jude's; Jude knows the barrels were siphoned, but not necessarily from Fairwind's own mouth.
