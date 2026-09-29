# Cast Mapping — The Party Finds Captain Helm (7th Wealsun)

`Party_finds_captain_Helm_7th_Wealsun.txt` · Book Two (ship-crew storyline). Folsom rejoins the crew on the docks; walking the ships they recognize **Captain Helm's** vessel — a fellow Monmurg spy — and board to arrange escape. Maps the diarization speaker tags to who is talking. **Character-locked tags:** A-series = PCs/DM; B-series = NPCs.

**Cast (index):** the DM, Merrick, Gouge, Tyrus, Folsom (PCs), plus **Georg** (the first mate) and **Captain Helm** (both NPCs, DM-voiced) — matches the `.cast.txt` hint.
**Format:** planning + a long NPC negotiation. Mostly roleplay, a handful of `[game mechanics]` (insight checks) and `[out-of-band]` (pop-culture jokes, a real name).

## Speaker → character mapping (final, character-locked; crew registry)
Registry: DM `00A`, Gouge `04A`, Merrick `05A`, Tyrus `06A`, Folsom `07A`. NPCs: **Georg (first mate) `01B`**, **Captain Helm `02B`** (both DM-voiced).

| Tag | Character | Basis (this file) | Lines |
|-----|-----------|------|-------|
| **SPEAKER_00A** | The DM | raw01 — narration, adjudication, and the interwoven NPC voices | 146 + 12 mech |
| **SPEAKER_05A** | Merrick | raw00 — recognizes Helm; the spy angle ("I was sent here as a spy… bring back to Jameis"); on lookout; writes the coded letter | 92 |
| **SPEAKER_06A** | Tyrus | raw03 — does the talking/waking (DM addresses him "Tyrus," 139/177/242/301); pushes to leave "tonight" | 111 |
| **SPEAKER_04A** | Gouge | raw02 — the flask; Helm calls out "Is Gouge back there!"; strategy (steal/passage/divert) | 30 |
| **SPEAKER_07A** | Folsom | raw04 — recaps the marine intel (Saltmarsh/Seaton); suggests hiding Merrick & Gouge as cargo | 25 |
| **SPEAKER_02B** | Captain Helm | NPC — the ~60-yr-old spy captain; calls Jamis "the spider"; explains the admiral, the pigeons | 43 |
| **SPEAKER_01B** | Georg (first mate) | NPC — the drowsy hammock-sleeper ("Am I in Monmurg?") who points them to Helm | 2 |

Raw layout: **raw00 = Merrick, raw01 = DM (+ NPCs), raw02 = Gouge, raw03 = Tyrus, raw04 = Folsom.**

## Point of the conversation
Folsom rejoins the others and passes on the marine's tips (Saltmarsh / Seaton). Hunting the docks for a "seedy" sloop to slip away on, the crew instead **recognizes a familiar ship** — it belongs to **Captain Helm**, an old, infamous, drink-loving sea captain who is secretly **another of Lord Jamis's agents** ("the spider"), whom Merrick knows. They wake his slow first mate **Georg** and crowd into Helm's cramped cabin. Helm is alarmed at being blown ("you're bringing bad luck," "Is Gouge back there — you're blowing my cover"), but the crew press their case: they have blockade-breaking intel for Jamis and need out **tonight**. The catch — **Admiral Amrachar**, aboard the Keoish man-of-war, controls who may leave, and won't release Helm's ship. Options canvassed: Folsom charms/bribes the admiral to let the ship (or a marine detachment) pass; slip out on a **mail ship** to Saltmarsh/Seaton; or send Helm's **carrier pigeons** to Jamis (three in the hold, ~20-hour flight to Monmurg). They settle on **writing a coded letter for the pigeons** to summon the Monmurg navy — but Merrick insists they must **first confirm the turtle dragons are actually gone** before luring the fleet into a possible death trap, so he heads on deck to scan the waters. Helm agrees to hide "the rats" in his hold and carry the message.

## Canon / continuity notes
- **Captain Helm:** a ~60-year-old, hard-drinking, "infamous" Monmurg sea captain and **spy for Lord Jamis** (whom he nicknames **"the spider"**); loyal to Monmurg, stuck in the Redshore embargo for weeks. His ship + **carrier pigeons** are a comms line to Jamis. New recurring NPC.
- **Georg** — Helm's slow-witted first mate, a former Harbor-District cargo handler who **worked for Tyrus's uncle** and recognizes Tyrus. (The DM voices him as "Keaton" once — treat as Georg per the cast list.)
- **Admiral Amrachar** — commands the Keoish man-of-war and controls all departures from Redshore; the gatekeeper on any escape. New NPC.
- **The escape plan** crystallizes: pigeon-borne coded letter → Monmurg navy, contingent on Merrick verifying the turtle dragons have left. A navy round-trip is estimated at ~day-and-a-half.
- Reinforces: only **mail ships** are being let out; Saltmarsh (new dock) and Seaton are the sanctioned destinations.

## Names / garbles
**Applied to the body** (author-canon / prior rulings): "Red Shore"/"Redshire" → **Redshore**; "Salt Marsh" → **Saltmarsh**; "Seton" → **Seaton**; "Captain Helms" (90) → **Captain Helm**.
**Noted for prose (not changed in body):**
- **"the spider" / "Jameis" / "Janus" / "James" (81, 187, 253, 339, 410)** → **Lord Jamis** ("the spider" = Helm's nickname for him).
- **"Keaton" (135)** → **Georg** (the first mate's name per the cast list).
- **"Admiral Amrachar / Armarchar" (285, 375)** → one spelling (author to confirm); **"Keago man-of-war" (285)** → **Keoish man-of-war**.
- **"King Toli" (394) / "Kane Tolley" (31)** → **Cain Toli**.
- **"summit of the Wealsun" (1)** → **7th of Wealsun**; **"new portal" (12)** → **new port**.

## `[game mechanics]` (12) & `[out-of-band]` (9)
- `[game mechanics]`: the two **insight-check** exchanges — spotting the seedy/familiar ship (64–75) and recognizing the first mate (118–119). On the DM tag `00A`.
- `[out-of-band]`: **39–40** ("Works for **NASCAR**…"), **434** ("**Dick**'s going to write out a letter" — real name), and **436–441** (the *Princess Bride* "**six-fingered man**"/"posterity"/"dot dot dot" banter while writing the letter). Raw tags kept.

## Hardest calls / flagged ambiguities (author: please correct — needs a scan)
- **⚠️ NPC/DM/PC bleed is heavy on the shared DM tag (raw01).** Captain Helm's dialogue is interwoven with DM narration and even a few PC lines on the same tag. I pulled **Helm's clearly-standalone lines to `02B`** and **Georg's to `01B`**, and left **embedded quotes** ("he goes, …") as DM narration `00A` — the same convention used for the knight in *Party Flees*. Please scan Helm's turns (esp. the rapid exchanges around 199–274 and 265–321); some short Helm/PC lines may still sit on `00A` or need swapping.
- **Bleed fixes:** 89 ("I do") → **Merrick 05A**; 172–173 ("I told you to leave me… got my drink on") → **Helm 02B** (they were on Merrick's tag).
- **Line 200 "Sir, I'm also here"** (a PC revealing himself, on the DM tag) was left on `00A` — likely Merrick or Folsom; couldn't pin it confidently.
- If you'd like **every** NPC quote (including embedded ones) pulled onto `01B`/`02B`, I can do a second pass — it needs light editing of the "he goes, …" frame lines.
