# Cast Mapping — Jude in the Alchemy Shop (4th Wealsun)

`Jude_in_Alchemy_shop_4th_Wealsun.txt` · Book Two. Maps the diarization speaker tags to who is actually talking. **A tag is a voice, not a fixed character.** **Severe scramble** — only two diarizer voices for three roles (DM, Jude, Albashon), and Albashon's lines were bled across *both* raw tags. Initial best-effort separation applied; **expect a heavier sift than usual.**

**Cast (index):** Jude, **Albashon** (the alchemist). Paul is absent (off fetching Grayson's formula); Leslie not yet present.
**In the room (2 voices):** the **DM** (narration + voicing Albashon) and **Jude**'s player.

## Tag scheme (A = PC/DM, B = NPC)
| Sub-tag | Character | Count |
|---------|-----------|-------|
| **SPEAKER_00A** | **DM** — narration, rulings, meta | 48 |
| **SPEAKER_01A** | **Jude** (PC) | 197 |
| **SPEAKER_01B** | **Albashon** (NPC) | 179 |
| `[out-of-band] [SPEAKER_0N]` | dice/rules, OOC, table asides | 65 |

## The point of the conversation
Jude stays with **Albashon** while Paul fetches his equations. Jude has him analyze the **sahuagin gill** he cut from a corpse: Albashon confirms sahuagin gills are ~100× more susceptible than normal fish — the compound is a **specifically engineered anti-sahuagin poison**, inert to humans, and he can't reproduce it. Jude reveals his commission (Jameis + Jeon want it recreated; the Duke of Berghof stopped supplying ~20 years ago). Albashon then opens up the deep lore: the compound is the legacy of two great Keoland transmuters — **Ediem Nakhond** and **Zafar Azane** — and drops the bombshell that **Zafar Azane's sister is married to Lord Jamis** (i.e., Lady Jamis is an Azane). He frames the real conflict as the **Suel royal houses** (ten bloodline houses; the Scarlet Brotherhood a breakaway "lesser" Suel house derived from knowledge, allied with the Toli), and warns Jude that "slavery" is a pretext — to look into what Keoland (Vangna, the Nihili, the Rhola) has done. A knock at the door ends the scene (Paul returning / Leslie).

## Drafter notes — canon web (big)
- **Zafar Azane** (ASR: Safar/Zepharo/Zapara/Zafara Zane / Hazane) — great Keoland transmuter, visits Monmurg often; **his sister is Lady Jamis** (284, 447, 471). Since **Paul's true family name is Azane/"Azani"** and his paternal grandmother is Lady Jamis, this ties Paul's bloodline to the Azane transmuter line. Dramatic-irony spine.
- **Ediem Nakhond** ("Idiom/Eem," 272) — the rival/friend transmuter, both carry the compound's legacy.
- **Suel houses** (437–458): ten royal bloodline houses; four still named — **Rhola** ("Rola"), **Linth** ("Linn"), a third (ASR "Healy" — likely **Neheli**), and **Ekstor** (extinct ~1000 yrs). Cross-check against the Name Key's four active houses (Neheli/Rhola/Linth/Toli).
- **Duke of Gratzel/Gretzel** (464–474) — named as the one isolating Monmurg; Zafar tries to keep the peace. **Duke of Redshore** (475) waylaid Jude and cited slavery as Gratzel's pretext. **Vangna** (483) — Keoland wrongdoing, flag as a new place-name.
- All name forms above are ASR-variant; normalize per `worldbuilding/Name_Normalization_Key.md`.

## Author rulings applied (review pass 1)
- → **DM (00A):** 8. → **Albashon (01B):** 106, 115, 117, 123, 125, 179, 188. → **Jude (01A):** 116, 155, 169.
- **L117** dialogue corrected (see `manuscript_divergences.md`).

## Sift list (this file bled badly — please verify)
- **Narration inside Albashon blocks**: a few third-person "he points/looks" lines got swept onto 01B and belong on **00A** — notably **290** ("And he points to the gill with his finger"); also check **351, 359, 262** ("he pats the gills").
- **Short interleaved Q&A** where Jude/Albashon alternate line-by-line: **34–51, 105–134, 138–153, 258–293, 342–389, 424–458** — spot-check the one-word turns.
- **Specific ambiguous** (left as-is): **106** ("Magically enhanced?" echo), **269, 332, 388, 438, 456, 482** — could flip PC/NPC.
- Applied tag-00→Jude: 51,131,139,173,208,263,320,365,449,450. Applied tag-01→DM narration: 489 ("There's a knock at the door.").

## Out-of-band table chatter
`[out-of-band]`: **62–63** (Hi/Hola), **72–73** ("Hey Elise…" table admonishment), **210, 213–217** (dice + "Jude does not know that name" ruling), **220–224** ("high school days" anachronism), **238–240, 271, 294–311** (the "who is Paul" OOC deduction), **390–407** (insight-roll mechanics), **416, 440–441, 459–462, 470, 484, 488**.

## Speaker discontinuities
- The core problem is the 2-voice/3-role collapse; Albashon (01B) was reconstructed from both raw tags.
