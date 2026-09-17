# Cast Mapping — Jude Tries to Convince Paul (4th Wealsun)

`Jude_tries_to_convinced_Paul_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **A tag is a voice, not a fixed character** — one tag can carry the DM's narration, an NPC's dialogue, and a player's out-of-character asides, and tags can bleed between speakers. Best inference from direct mentions, personality cues, and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Jude, Paul.
**In the room (3 voices):** Jude's player (Steve), Paul's player, and the DM.

> **Premise:** Jude proposes reversing the day's roles — instead of more arcane lessons, he wants Paul to teach *him* stealth ("throw brass bowls at my shins") and let them "stealth in" on a target. The DM notes this is a pretext: Jude is really probing Paul for his secrets.

## Speaker → character mapping

| Tag | Primary speaker | Also carries | How we know |
|-----|-----------------|--------------|-------------|
| **SPEAKER_00** | The DM | — | Opening narration (1); OOC meta to Paul's player — "you have no interest in going to [Ferds]" (21); "what Jude is doing is actually probing… he's trying to figure your secrets out" (42–47); the session-management wrap "Do you want to continue his training tomorrow?" (172–181). |
| **SPEAKER_01** | Paul | Jude's lines bleed in at 105, 108 | The stealth expert — "rule 101 of stealth… the more people, the harder" (13–14); "Why can't I just send my homunculus?" (26); resists the stealth-in idea and interrogates Jude's motives (85–93, 124, 141–143). |
| **SPEAKER_02** | Jude | Paul's short observations bleed in (collapsed exchanges at 48–51, 75–78) | The elf reveal — "I got pointy ears / I do [hide them], but if you hang out with me enough…" (76–78); stays at Ferd's bar (49, 51); "You stayed under his thumb for 20 years… I've slept in the saddle" (62, 65); keeps pushing to "stealth in" and "switch tracks" (144–155). |

## Flagged ambiguities (author: please correct)
- **48–51** — "Why do you want to go to Ferds? / that's where I'm staying / Why are you staying at Ferds? / Ferd's a good guy" is all tagged SPEAKER_02, but alternates Paul's questions with Jude's answers (Jude is the one who lodges at Ferd's).
- **75–78** — the "So you're an elf / Yeah, I got pointy ears / I thought you hid them / I do…" exchange is entirely SPEAKER_02 but is a two-person dialogue; the pointy-ears admissions are Jude, the observations are Paul.
- **105 & 108** are tagged SPEAKER_01 (Paul) but are **Jude** — "you're trying to figure out if I'm an evil saint, which I'm not" (105) and "the alchemist, the guy who sold me the map" (108); Jude is the one who deals with the alchemist and fears being investigated.
- **21–24** — "you have no interest in going to [Ferds]… I don't… I don't… I don't" collapses DM prompt and player answer.

## Out-of-band table chatter
Tagged `[out-of-band]` in the body: **21–24, 42–47, 160–171, 172–181**. (DM OOC prompting the player about intent — Jude "probing… to figure your secrets out"; the wager logistics — "let's put money on it / 50 gold? 100 gold? / which cards? I'll go first"; and the end-of-session scheduling — "Ending day of [4th Wealsun]… Do you want to continue his training tomorrow?")

**Author's call:** the 100-gold wager (160–171) is an in-world bet on who can creep closest to a guard; if you want the bet in the story, keep the stakes and cut only the turn-order/logistics chatter (169–170).

## Speaker discontinuities
- SPEAKER_02 repeatedly carries both sides of a two-person exchange (48–51, 75–78) — the diarizer failed to split Jude and Paul during rapid back-and-forth.
- SPEAKER_01 carries two of Jude's lines (105, 108) in the alchemist/"evil" exchange.
