# Cast Mapping — Folsom Tells Merrick What He Has Learned (6th Wealsun)

`Folsom_tells_Merrick_what_he_has_learned_6th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking, for turning the raw session into prose. **Character-locked tags:** the **A-series** is reserved for player characters and DM narration; **NPCs use the B-series**. Best inference from direct mentions, personality cues (`characters/`), and story context; **ambiguities flagged below for author correction.**

**Cast (index):** Gouge, Merrick, Folsom (PCs), the DM, and Owen Black (NPC, DM-voiced, present, a few lines).
**In the room (4 voices):** the three players plus the DM (who narrates and voices Owen). Tyrus is asleep below.

## Speaker → character mapping (final, character-locked; crew registry)
Same crew registry: DM `00A`, Gouge `04A`, Merrick `05A`, Folsom `07A`, Owen Black `01B`.

| Tag | Character | Role | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | Narration / adjudication / the Acerak history answers | 60 |
| **SPEAKER_01B** | Owen Black | NPC — a few lines musing on the missing dragons | 10 |
| **SPEAKER_04A** | Gouge | PC — hears the intel second-hand, urges secrecy | 30 |
| **SPEAKER_05A** | Merrick | PC — receives Folsom's telepathic report, relays to Gouge | 83 |
| **SPEAKER_07A** | Folsom | PC — messages Merrick the artifact intel; does the history checks | 58 |

Raw layout: **raw00** = DM narration **and** Owen; **raw01** = Gouge; **raw02** = Merrick; **raw03** = Folsom.

## Point of the conversation
Past midnight on the 6th, threading the Dragon Isles toward Redshore, **Folsom uses the *message* spell to secretly tell Merrick** what he pried out of Owen: **Cain Toli** holds an artifact made by the lich **Acerak** that **controls the turtle dragons**, keeping them around his island — which is why the isles are silent, and why going near Cain's island means death. Merrick relays it to Gouge; all three agree to steer well clear and to hold the secret close, sharing it carefully even with whoever they report to. Folsom runs a **History check** on Acerak: a lich of **Salinmoor** ~600 years ago, tangled in a war with the **House of Gratzel** (a Gratzel king defeated the side Acerak backed); the **Sons of Olan** take their name from **Lord Olan**, a vampire Acerak is said to have created. They resolve to press on to Redshore, with Folsom staying Owen's "right-hand man." After some watch logistics, Owen takes the helm.

## Canon note
Corroborates the `Name_Normalization_Key.md` entries: **Acerak** (the lich, = the artifact's maker) and the **Sons of Olan** (named for **Lord/Count Olan**). New detail to reconcile: this file says **Lord Olan was a vampire Acerak created** — the Key currently frames the original Acerak as "Count Olan's master"; author to align.

## Hardest calls / flagged ambiguities (author: please correct)
- Owen's lines on the DM's raw00: **68, 74–75, 81–83** (musing on the dragons / Gian's purse / "very strange"), **225–227** ("we'll make it by evening… Tyrus"), and **236** ("Certainly," agreeing to take the helm, bled onto Merrick's tag). Verify.
- **142** ("I just kind of go, Fuck you!") sits on Merrick's tag but reads as **Gouge's** ornery bit leading into 143 ("You don't get any of my red-eye, and I walk away") — assigned to Gouge; confirm.
- **206, 208–209, 211** — a genuine in-story turtle-dragon lore Q&A that's braided into the rest-logistics block; I kept those four in-story and tagged only the hour-counting around them as game mechanics.

## Game mechanics (attributed, 34 lines)
- **9–14, 17, 20–24** — the *message*-spell rules clarification ("would he be the only one to hear it," "you can message back," "this is all in your mind"). I treated the spell-mechanics chatter as game mechanics and kept the actual telepathic content (16, 18, 27–33, etc.) in-story. **If you'd rather this whole beat read in-story, say so and I'll fold it back in.**
- **155–161** (Acerak History check — expertise/proficiency/roll), **186–190** (the second, failed History check), **200–205, 207, 210, 212–213** (rest/watch hour-counting). DM instructions/results → `00A`; rolls → the roller (Folsom `07A`, Gouge `04A`).

## Out-of-band (raw tags kept, 5 lines)
**54** ("Bob White was up there too" — a stray table aside), **171–174** ("I got this on vinyl / my voice sounded funny / a different tone of voice / informative voice" — the player riffing on their own voice; modern reference).

## Names to normalize in prose
"Whale Sun" (2) → **Wealsun**; "Azzagon / Agath / Azrek / Asarak / Aserach" → **Acerak**; "Keintoli / Cane Tolis / Can Toli" → **Cain Toli**; "Gion / Gian" (74–81) → **Jeon** (Prince Jeon); "Salimor" (162) → **Salinmoor**.

## Speaker discontinuities
- raw00 carries DM narration and Owen with no tag change.
- Owen's "Certainly" (236) and a few musings bleed onto the player tags.
