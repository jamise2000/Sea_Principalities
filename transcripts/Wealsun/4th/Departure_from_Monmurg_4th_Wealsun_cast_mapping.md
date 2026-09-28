# Cast Mapping — Departure from Monmurg (4th Wealsun)

`Departure_from_Monmurg_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge (PC), Merrick (PC), Tyrus (PC), Folsom (PC), Owen Black (NPC, DM-voiced).
**In the room (5+ voices):** four players (Gouge, Merrick, Tyrus, Folsom), the DM (narrating and voicing Owen Black), and an intruding real-world voice (a family/phone call).

## Crew character-lock (this thread's A-registry)
This is the **ship-crew storyline**, a separate cast from the Jude/Paul files. It extends the global PC registry (DM `00A`, Jude `01A`, Paul `02A`, Leslie `03A`) with the crew, so these numbers stay stable across the crew's transcripts (this file + the 6th-Wealsun set):

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration / adjudication | 104 |
| **SPEAKER_04A** | Gouge | PC — Monmurg knife-man, has the crossbow & flask | 26 |
| **SPEAKER_05A** | Merrick | PC — scout/navigator, Owen's cousin; works Owen for info | 86 |
| **SPEAKER_06A** | Tyrus | PC — giant Marine; hooks the sahuagin body, works the sails | 16 |
| **SPEAKER_07A** | Folsom | PC — bard; his subversive song comes up | 25 |
| **SPEAKER_01B** | Owen Black | NPC (DM-voiced) — the smuggler captain | 127 |

Raw diarizer layout for this file: **raw00** = Merrick (+ heavy Owen bleed in the interrogation), **raw01** = DM **and** Owen Black (separated by content), **raw02** = **Gouge and Tyrus sharing a tag** (split by content), **raw03** = Folsom, **raw04** = the out-of-band phone voice.

**Author review applied (2nd pass).** DM reclaimed 204–205, 208. Owen reclaimed 259, 270 ("Kane Toli himself" = Owen bragging), 322, 368. Folsom reclaimed 227–228 and 233–235 (he fetches the rum and hands it to Owen), plus 369, 371, 376. Two **line splits** (each shifts later numbers +1): "Yeah, go down to the cabin" → **Folsom "Yeah."** + **Owen "Go down to the cabin."**; and Merrick's "…conversed last…" → **Merrick** + **Owen "Have a nice piss off the back of the deck?"** (yelling at Tyrus). Names: "Laplar" → **the Plar**.

## Point of the conversation
The crew (Gouge, Merrick, Tyrus, Folsom) leaves Monmurg on Owen Black's sloop the morning of the 4th, bound for Redshore by the long, safer easterly route — through the Gap between Flotsam and Jetsam and past the (currently dragon-free) Dragon Isles — to avoid Keoland patrols in the Strait. Along the way they pass **dead sahuagin floating in the water**, killed by the anti-sahuagin "stuff" the party dumped at the Helm; the shark-men had been massing. Then Merrick plies **Owen** with drink to loosen his tongue, and Owen talks: he works for **Cain Toli** (moving men and weapons through the Saltmarsh), Cain has a small fleet parked on an island in the bay, the **"Toli rats"** have a presence in Redshore, the **Plar of Salinmoor** ("Laplar" / "Lord Balin" = Lord Gloin Baywin) has taken over Selinmore chasing a cult of necromancers and once beat Owen and broke his arm, and Cain Toli recovered Owen's stolen ship from an old sailor now imprisoned on Cain's island. Folsom's subversive song from the night before comes up. Owen never learns the crew's real business (the Helm operation).

## Hardest calls / flagged ambiguities (author: please correct)
- **The Owen interrogation (≈178–378) is heavily bled.** The diarizer smeared both sides of the Merrick↔Owen dialogue across raw00 (Merrick) and raw01 (DM/Owen). I separated them by content — Owen → `01B`, Merrick → `05A`, DM narration → `00A` — but several short interjections are best-guess. Please scan this stretch closely. Specific bleed calls: **82–83, 85** (Owen answering, on Merrick's raw00) → Owen; **114 "I am Owen Black"** (garbled fragment on Merrick's tag) → tentatively Owen; **233–234** ("I hand it to Owen… here you are, sir," the fetcher on raw01) → Merrick; **254, 287, 298, 353, 360, 362** (crew one-liners bled onto raw01) → Merrick; **263, 270, 322, 366, 371** (short lines that flip speaker mid-tag).
- **raw02 = Gouge + Tyrus.** Split by content: **Gouge** (crossbow, flask, blunt route-griping) = 33–35, 78, 86–88, 141, 143, 159, 176, 186–189, 293, 295, 303, 339, 355, 363; **Tyrus** (hungover, hooks the body, works the sails) = 8–11, 56–57, 79, 138, 144, 149–150, 161–162, 174–175, 227–228, 244. Line 58 ("Tyrus says as he walks onto the deck") anchors Tyrus; 78/293 anchor Gouge.
- **Line 319 "Are you talking about the whore?"** — RESOLVED per author: this is **Gouge** (in-band, `04A`), trying to pin Folsom's knowledge on his talking with a prostitute. (Was mis-tagged out-of-band.)
- **Names to normalize in prose:** "Kane Toli / King Toli / Kane Tully" (270, 288, 333, 356) = **Cain Toli**; "Owen Blackwell" (367, and Owen's own "the Blackwell family" at 373) — Folsom misspeaks; canonical is **Owen Black**, and the character file says there is *no* "Blackwell" family, so flag Owen's 373 line; "Sac Nontoli" (311) = **Sacnon Toli**; "Laplar / the plaw / Lord Balin" (297–301, 354) = the **Plar of Salinmoor, Lord Gloin Baywin**; "Selinmore / Selenmore" (281, 301) = **Selinmore**.

## Game mechanics (attributed to a character)
Tagged `[game mechanics]`: **100–108** (Merrick's perception check — roll/skill/DC talk, DM ↔ Merrick), **120 & 123** (the perception roll that spots the body; 123 "1624" = Gouge's roll), **190–191** ("Can I hear them?" / "he wanted to do this as an aside" — who overhears the aside), **206–207 & 210** (scene-privacy logistics for Merrick's private chat with Owen), **390** ("you move ten feet per round faster…" — DM move-speed, mixed into the phone-call block).

## Out-of-band (raw tags kept)
**118–119, 121–122** (a real-world contact-lens joke wrapped around Gouge's perception roll — "I don't have my contact / I'd rather see you die"), **319** (the "whore" aside — see flag), **382–389, 391–392** (an intruding **family/phone call**: "Mom? / Hey! / How are you guys?" plus a modern aside about "taking pictures of all my spells"). Story resumes at 393.

## Speaker discontinuities
- raw01 carries **two** speakers throughout — DM narration and Owen Black — with no tag change; the interrogation is the densest mixing.
- raw02 alternates between **Gouge and Tyrus** with no tag change.
- raw04 is used both for the outside phone voice (382–392) and, once, for the mid-scene aside at 319.
