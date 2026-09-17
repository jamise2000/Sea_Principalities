# Cast Mapping — Departure from Monmurg (4th Wealsun)

`Departure_from_Monmurg_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Merrick, Tyrus, Folsom, Owen Black (NPC, DM-voiced).
**In the room (5+ voices):** four players (Gouge, Merrick, Tyrus, Folsom), the DM (narrating and voicing Owen Black), and an intruding real-world voice (a family/phone call).

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_01** | The DM (all narration) | **Owen Black's** dialogue throughout (40–55, 89–94, 216–367 the drinking/interrogation), and dice/mechanics prompts | Route narration, the sahuagin-body discovery, and Owen's boasting are all here. Owen is DM-voiced. |
| **SPEAKER_00** | Merrick | Bleed: Folsom at 336 ("I grab my fife"); a garbled "I am Owen Black" at 114 | Owen's **cousin** and trusted helmsman — takes the steerage (198), works Owen for information (178–335). Watchful; the perception check is his (98–108). |
| **SPEAKER_02** | Gouge **and** Tyrus (shared tag) | Also a drunk-crew aside at 8–11 | **Gouge** = blunt complaints about the long route, has the flask (78, 178–187, 293 "maybe we can make better pay," answered "…Gouge"). **Tyrus** = 57 ("lottery game," DM confirms "Tyrus says…" at 58) and the billhook/crossbow at 138–151. Both land on SPEAKER_02. |
| **SPEAKER_03** | Folsom | — | The bard — his subversive songs, "fester up a crowd," refusing to give away his knowledge (151, 240, 310–330, 365–368, 377). |
| **SPEAKER_04** | Out-of-band real-world voice | A family/phone call (382–392) plus a stray aside at 319 | Not a character — see below. |

## Flagged ambiguities (author: please correct)
- **SPEAKER_02 is two characters.** Split Gouge (drink, route-griping) from Tyrus (hungover, hooks the sahuagin body, has the crossbow). Line 58 anchors Tyrus; lines 78/293 anchor Gouge.
- **SPEAKER_00 bleed:** line 114 "I am Owen Black" is a garble/mis-tag mid-narration; line 336 "I grab my fife and just start playing" is Folsom, not Merrick.
- **Line 319 (SPEAKER_04) "Are you talking about the whore?"** — unclear whether this is an in-story crew question about Folsom's source or an OOC aside. Flagged; lean in-story but verify.
- **Garbled names (correct in prose):** "Kane Toli / King Toli / Kane Tully" all = **Cain Toli** (270, 288, 333, 356); "Owen Blackwell" vs "Owen Black" is an in-story running gag (367–373); "Evan's ego" (46) = Owen; "Laplar / the plaw / Lord Balin / Lord Baywin" refer to the Plar of Selinmore / **Albashon** figures — reconcile against canon. "Salinmore/Selinmore/Selenmore" = Selinmore.
- "Sloof's deck plant" (21) = the sloop's deck plan; "Folsom Island / Flotsam / Flossum / Jetsam" — reconcile the island names.

## Out-of-band table chatter
Tagged `[out-of-band]` in the body: **100–108, 118–123, 382–392**.
- 100–108: Merrick's perception check (rules explanation + "18").
- 118–123: a real-world contact-lens joke ("I don't have my contact / I'd rather see you die") wrapped around Gouge's perception roll ("1624").
- 382–392: an intruding **family/phone call** ("Mom? / Hey! / Hi! How are you guys?") with DM move-speed mechanics (390) and a modern aside (392 "taking pictures of all my spells") mixed in. Story resumes at 393.

## Speaker discontinuities
- SPEAKER_04 is used both for the outside phone-call voice (382–392) and, once, for an in-room aside (319) — treat them as different people.
- SPEAKER_02 alternates between Gouge and Tyrus with no tag change.
