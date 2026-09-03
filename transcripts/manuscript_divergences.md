# Manuscript ↔ Transcript Divergences

A record of the places where the manuscript of *Journey of the Stone* **deliberately departs** from the cleaned session transcripts it is drawn from.

The cleaned transcripts (`transcripts/cleaned/`) are the narrative source of truth, and the raw session transcripts are the verbatim record. But the author has, in places, changed a fact or a beat on purpose — and where that happens, the manuscript, the `characters/` files, and the `worldbuilding/` ledgers are the authority, not the transcript.

This file exists so those intentional changes are not "corrected" back toward the transcript by a later continuity pass, and so a transcript-vs-chapter check can tell an intentional divergence apart from a genuine mistake.

**How to use.** Before syncing a transcript line into the manuscript, or before flagging a manuscript fact as contradicting a transcript, check here first:

- If the discrepancy is listed below, it is **intentional** — leave the manuscript as it stands, and leave the transcript as the verbatim record.
- If it is **not** listed, treat it as a real continuity question and raise it.

**Maintaining it.** When a new deliberate departure from the transcripts is made, add an entry below using the same shape: what the transcript says, what the manuscript establishes instead, where each lives, and why the change was made.

---

## Merrick's father — killed by the sahaugin, not hobgoblins

- **Transcript says:** Merrick's father was "supposedly killed by hobgoblins." — `transcripts/cleaned/Marines_shelter_in_guard_tower_2nd_Wealsun_CLEANED.txt` (≈ line 181)
- **Manuscript establishes instead:** Merrick's father, **Captain Nado**, was taken by the **shark-men (sahaugin)** in deep water beyond the warded coast. — Ch. 16 *Tracks on the Beach* (the print his father named for him); Ch. 20 *Nothing to Be Done* ("The shark-men took my father — out in the deep, years back"); `characters/Merrick.md`.
- **Why it's intentional:** The sahaugin killing his father is the thematic engine of Merrick's whole arc — the vigilance his father planted ("were they truly gone, or only waiting?"), his lifelong watch of the water, and the personal horror of watching the shark-folk take the Helm. A hobgoblin death would cut that thread. The change is canonical; the character file and chapters govern.

---

## Helm Island's neighbor — Jetsom, not Flotsom

- **Transcript says:** Helm Island lies "between the Monmurg Peninsula and Flotsam Island." — `transcripts/cleaned/Jude_Paul_travel_to_Helm_Island_2nd_Wealsun_CLEANED.txt` (≈ line 7)
- **Manuscript establishes instead:** The large island the Helm sits beside, to the **east**, is **Jetsom**. **Flotsom** lies to the **south** of Monmurg and the Helm (and is the eastern lighthouse's relay target). — Ch. 17 *The Corsair* ("between the peninsula and the looming bulk of Jetsom Island"); `worldbuilding/Helm_Island.md`.
- **Why:** The transcript misnames the neighboring isle — the author's geography is the authority here. Jetsom is the eastern island beside the Helm; Flotsom is the southern one. The manuscript is correct; the transcript line is the error. (Note also the spelling: the manuscript uses "Flotsom"/"Jetsom," the raw transcript "Flotsam.")

---

## Paul's landing squad — ten Marines and ten crossbowmen

- **Transcript says (correctly):** "about ten men in scale mail and ten crossbowmen" (20). — `transcripts/cleaned/Jude_Paul_travel_to_Helm_Island_2nd_Wealsun_CLEANED.txt` (≈ line 275)
- **Manuscript now matches this:** Ch. 17 originally read "twenty men in scale mail, ten more with crossbows" (30) — a manuscript error, since Ch. 19 ("our twenty guys"), Ch. 21 ("our twenty men"), Ch. 23 ("the twenty who had come ashore with Paul"), and the "hundred and twenty-two" total all require 20. Corrected to "ten men in scale mail, ten more with crossbows slung."
- **Note:** Logged for the record; the manuscript has been changed to agree with the transcript, so this is no longer a live divergence.

## Jude is not "the knife" — that is Gouge's role

- **Transcript says:** In Jamis's private word, he tells Jude, "You'll be the knife." — `transcripts/cleaned/Jamis_has_quick_word_w_Jude_2nd_Wealsun_CLEANED.txt` (≈ line 13)
- **Manuscript establishes instead:** "You are not the knife, Jude. Your task is to see that Paul comes home alive." — Ch. 14 *Orders for the Helm*; matches `characters/Jude.md` ("He is not Jamis's knife — that is Gouge's part").
- **Why:** Gouge is Jamis's knife-man; Jude's charge is to keep Paul alive. The transcript line is a slip; the manuscript follows the character files.

## Fairwind's garrison — better than four hundred, not "a hundred"

- **Transcript says:** "Fairwind has more than a hundred men on the island. You'll be outnumbered roughly two-to-one." — `transcripts/cleaned/Jamis_has_quick_word_w_Jude_2nd_Wealsun_CLEANED.txt` (≈ line 25)
- **Manuscript establishes instead:** "Better than four hundred men on that island. You'll be outnumbered near two to one." — Ch. 14.
- **Why:** "A hundred" contradicts "two to one" against 250 Marines, and the island's own garrison runs near four hundred (keep ~150, midway garrison 100, beacon detachments) per Ch. 25. Four hundred is the internally consistent figure.

## Jeon and Fairwind are old friends, not enemies

- **Transcript says:** "There's been bad blood between him [Fairwind] and Jeon for years now." — `transcripts/cleaned/Merrick_Gouge_meet_Jamis_office_2nd_Wealsun_CLEANED.txt` (≈ line 35)
- **Manuscript establishes instead:** Jeon "counts the man a friend — has for years, and will hear no word against him." — Ch. 13 *Summoned to the Harbor Office*; matches `characters/Fairwind.md` ("a childhood friend of Prince Jeon turned self-serving schemer").
- **Why:** Jeon's refusal to believe the treason rests on that old friendship. The friendship is canonical; the transcript's "bad blood" is the outlier.

## Ferd's signal word — "the still," not "the stale"

- **Transcript says:** Jude tells Gregory to "ask for 'the stale.'" — `transcripts/cleaned/Jude_Paul_interrogate_prisoner_2nd_Wealsun_CLEANED.txt` (≈ line 581; also the alchemist transcript)
- **Manuscript establishes instead:** "ask the barkeep for 'the still.'" — Ch. 12 *Masks and Measures*.
- **Why:** Jude bought a *still* (a distillery) from the alchemist as his cover, and the code word refers to it. "The stale" is a mis-hearing of "the still" in the recording.

## The sergeant delivers the sea-creatures warning; Jude follows Paul against his judgment

- **Transcript says:** Paul warns about "sea creatures swarming a hull," and Jude simply agrees ("I'm with you"). — `transcripts/cleaned/Jude_Paul_ambushed_one_Pier_2nd_Wealsun_CLEANED.txt`
- **Manuscript establishes instead:** The *sergeant* gives the sea-creatures warning, and Jude follows Paul back toward the ship reluctantly — judging it folly, but bound by his charge to keep Paul alive. — Ch. 18 *The Empty Harbor*.
- **Why:** A deliberate reshaping to set up Jude's divided loyalty and Paul's recklessness.

## Paul, not Jude, calls off the rescue

- **Transcript says:** Jude does the arithmetic and decides to fall back ("Not worth it"), with Paul following. — `transcripts/cleaned/Jude_Paul_attacks_by_Sahaugin_2nd_Wealsun_CLEANED.txt`
- **Manuscript establishes instead:** *Paul* is the one who realizes the rescue is hopeless and calls the retreat, Jude having followed him into it. — Ch. 19 *Out of the Deep*.
- **Why:** Deliberate, to complete the Ch. 18 setup — Jude follows Paul's reckless charge until Paul himself sees it cannot be done.

## Gouge rallies the southern squad; the fog beat relocated

- **Transcript says:** After the corsair is overrun, Merrick names an "unnatural fog" that came "a few days ago," and the squad's reaction is largely dismay. — `transcripts/cleaned/Marines_shelter_in_guard_tower_2nd_Wealsun_CLEANED.txt`
- **Manuscript establishes instead:** Gouge turns the loss into resolve and drives the squad to act; Merrick's beat leans on the failed *wards* rather than the fog, and the unnatural fog is grounded later — the day before the attack, seen from Monmurg — in Ch. 21. — Ch. 20 *Nothing to Be Done*; Ch. 21 *The Garrison*.
- **Why:** Deliberate, to give Gouge a driving role and to place the fog where it is properly established (the garrison experienced it up close; the Monmurg fleet saw it from the seawall).

## Gouge's closing line at the tower (wording)

- **Transcript says:** "That's fantastic — and also terrible, since we're supposed to be protecting that guy." — `transcripts/cleaned/Marines_shelter_in_guard_tower_2nd_Wealsun_CLEANED.txt` (≈ line 109)
- **Manuscript establishes instead:** "Well, that tears it… there's the man we're meant to keep alive, walking straight into the worst of it." — Ch. 16 *Tracks on the Beach*.
- **Why:** A deliberate rewording to a less contemporary, more in-register line; the sense is unchanged.

---

## Canonical name spellings vs. the verbatim recordings

The session recordings were auto-transcribed, and several names come through inconsistently or mis-heard. The manuscript, `characters/` files, and `worldbuilding/` ledgers use the author's settled spellings; the verbatim transcripts in `transcripts.lst` are left as the recorded record. These are settled authorial choices, not errors to "correct" back toward the transcript:

- **Paul Revero** — canon everywhere. The recordings give "Rivera," "Rivero," "Riviero," "Royero" (e.g. `Paul_Revero_Prolog/Paul_reads_Graysons_letters_Prolog`, `.../Paul_creates_Homunculus_Prolog`). The cleaned duplicate transcripts have been updated to "Revero"; the verbatim files retain their recorded spellings.
- **Lady Alaria** (Paul's mother) — canon everywhere. The verbatim recording says **"Lady Elaria"** (`Paul_Revero_Prolog/Paul_Revero_prolog`, ≈ line 54; also "Elyria" in `Paul_reads_Graysons_letters_Prolog`). Ch. 5 and 7 originally matched the recording ("Elaria"); the author standardized on **Alaria** (per Ch. 15 and `Jeon.md`). This is a deliberate choice — the recording's "Elaria" is not the canon.
- **Horace Baldpate** — canon. The recording gives "Boltpate"/"Boldpate" (`Jude_Prolog/Jude_intro_mid_Flocktime`). "Baldpate" is the intended, meaning-bearing spelling (the man is bald), per `characters/Horace_Baldpate.md`.
- **Archibald Fryhone** — canon. The recording is pure transcription noise: "Fryhoun," "Fryhorn," "Fryholm" (`Paul_Revero_Prolog`). "Fryhone" is the settled spelling.

## The homunculus tome — "The Homunculi," credited to Grayson

- **Transcript says:** the book Paul finds is titled **"Creating a Homunculus," *translated by* Grayson Jamis** (`Paul_Revero_Prolog/Paul_discovers_secret_lab_prolog`, ≈ line 1263); the method and stones belong to the lithomancer Zafar Azane (`.../Paul_studies_Homunculi_manual_Prolog`).
- **Manuscript establishes instead:** the tome is titled **"The Homunculi," the work of Grayson Jamis**, with the craft and the paired stones credited to his uncle, the lithomancer Zafar Azane. — Ch. 6 *The Room Behind the Wall*; Ch. 10 *Clay and Blood*.
- **Why:** an authorial rename, now consistent across Ch. 6 and Ch. 10. Grayson is treated as the book's author (his hand throughout, notes in the margins) rather than merely its translator; Zafar remains the originator of the method, preserving the recording's substance.

## Archibald — Zafar's ward, parentage left a mystery

- **Transcript says:** Lady Jamis calls Archibald **"my nephew,"** a bastard raised in her house, his mother a high noble of Port Toli (`Paul_Revero_Prolog/Paul_confronts_Lady_Jamis_Prolog`, ≈ line 186).
- **Manuscript establishes instead:** Archibald is **Zafar's ward** — a bastard brought into the house to raise — and his true parentage is pointedly withheld (the grandmother deflects: "A foundling has no father worth the naming"). — Ch. 8 *Grandmother*.
- **Why:** a deliberate mystery-seed. Making him a ward of uncertain blood, rather than a plain nephew, keeps open the question the story circles — whether Archibald was more closely tied to the family (and to Paul) than anyone admits.

## The all-in force — a hundred twenty, not the transcript's "one hundred seventy"

- **Transcript says:** the combined garrison-plus-landing-party strength is "170 guys" — "are we going to go all out and get the captain and the garrison and 170 guys?" — `transcripts.lst`: `Wealsun/2nd/Jude_Paul_plan_2nd_Wealsun` (≈ line 65).
- **Manuscript establishes instead:** roughly **a hundred twenty** — Ch. 24 *All In* ("a hundred twenty men, near enough"). This follows the garrison strength already fixed across Ch. 21–23: the midway garrison's hundred (Ch. 21, "the garrison's full hundred men"; Ch. 23, "the garrison's own hundred") plus the twenty who came ashore with Paul — the same arithmetic behind Ch. 22's "hundred and twenty-two" (garrison 100 + squad 20 + Paul + Jude).
- **Why:** The transcript's 170 implies a garrison of ~150, which contradicts the 100-man garrison and the 122 total established in Ch. 21–23. 120 is the internally consistent figure.
- **Still to reconcile:** Ch. 25's captain's-ledger math still runs on the old 170 (seventy to hold the garrison + a hundred free to assault). Bring that into line with the 120 figure when Ch. 25 is revised.

## The garrison's leader — the "commander," a Marine officer, not "the captain"

- **Transcript says:** the garrison's leading officer is called "the captain" — "we're going to find out from the captain," "the captain and the garrison and 170 guys." — `transcripts.lst`: `Wealsun/2nd/Jude_Paul_plan_2nd_Wealsun` (≈ lines 65, 80). (The companion transcript `Jude_Paul_consult_commander` calls the same man "the commander.")
- **Manuscript establishes instead:** he is the garrison **commander**, a Marine officer — Ch. 21 ("the garrison commander … a greying, square-built man"), Ch. 24 (uniformly "the commander"). "Captain" is reserved for the ship's captain, **Richard**, who went down with the corsair; using it for the garrison's Marine leader would confuse the two.
- **He is unnamed — leave him "the commander."** A draft briefly named him **Sten** (Ch. 21, 27, 28); the author has since decided against naming him, and that name has been removed everywhere. Do not reintroduce "Sten" (or the transcript's jokey "Steve," which is table crosstalk); refer to him only by the descriptor "the commander."
- **"Captain" now reserved for ship's captains only (later pass).** Per an explicit authorial rule, the word "captain" is used *only* for someone who captains a ship; every land/staff use was changed. Garrison-leader references became "commander" in the Ch. 28 close (the four in the merged rousing scene, formerly Ch. 29, plus "the household captain" → "the commander"), Ch. 30 (two), Ch. 44, and Book 2 Ch. 3. Other non-ship uses also changed: the Redshore gate's "guard captain" → "guard commander" (Ch. 1); "captained mercenary companies" → "led mercenary companies" (Ch. 5); the personal superiors Folsom, Merrick, and Tyrus each call "my captain" → "my commander" (Ch. 34, 48; Book 2 Ch. 1); and Jeon's figurative "good captains and good fighters" → "good commanders and good fighters" (Book 2 Ch. 2).
- **Left as genuine ship's captains (do not change):** Captain Richard and every "the captain" for him aboard the corsair (Ch. 15, 17); the merchant-ship captain (Ch. 1); the corsair's captain during the return voyage (Ch. 43); Captain Nado, Merrick's father, a fleet navigator (Ch. 13); the privateer "captains like Cross" (Ch. 13); the naval "captains stationed" at Redshore (Ch. 46); and the pirate epithet "Captain Crimson" (Ch. 2, 11).
- **Not yet synced:** the earlier compiled drafts (now archived in `manuscript/old/` as `The_Brewing_Storm_second_draft.md`, formerly `The_Brewing_Storm_Revised.md`, and `The_Brewing_Storm_third_draft.md`, formerly `The_Brewing_Storm.md`) still hold their old "captain"/"Steve"/commander wording. They are superseded by the per-chapter files and kept only as historical drafts; no need to re-run the pass over them unless one is revived.
- **Resolved (Ch. 25 revised):** the chapter is retitled *The Commander's Ledger* (file renamed to `Chapter_25_The_Commanders_Ledger.md`), every "captain" reference for the garrison's leader is now "commander," and his description is brought into line with Ch. 21 ("greying, square-built"). Ch. 26's garrison-leader references were updated to "commander" as well. (Note: the "aboard the corsair" line I'd first flagged was *not* an error — it refers to **Gouge**, who crossed disguised among the corsair's crossbowmen (Ch. 17); Ch. 26 now makes that explicit, as the hook for Paul's curiosity about Jamis's hidden agents.)

## Structural — Ch. 29 merged into Ch. 28; later chapters renumbered

- **What changed:** the former **Ch. 29, *No Time to Finish*** (Jude roused from his trance, the wall plan confirmed, and Gouge and Merrick revealing to Paul Jamis's suspicion that Fairwind may have let the warding fall) was folded into the close of **Ch. 28, *The Prince in the Mask***. Its one unique thread — *why* the sahaugin came at all, a possible broken bargain with sea-folk — was carried into that merged scene.
- **Renumbering:** with the old Ch. 29 gone, every later chapter shifted down by one. The old **Ch. 30–58** are now **Ch. 29–57**. The `The_Brewing_Storm_book1_chapters/README.md`, the chapter H1 headings, and the `Ch. NN` cross-references in `worldbuilding/` and this file were updated to match.
- **Reading old references:** a citation to an old Ch. 30-or-later means the chapter now numbered one lower; anything that pointed at the old Ch. 29 now lives in Ch. 28.

## Structural — Ch. 38 and Ch. 39 merged into Ch. 38, *The Poison Sea*; later chapters renumbered

- **What changed:** the former **Ch. 38, *What the Water Gave Back*** (reaching the grotto, sighting the ballista and barrels, and splitting the party — Jude and Merrick to the high ground on the ballista and bow, the other four down to the beach) was folded into the opening of the former **Ch. 39, *The Poison Sea*** (the beach fight, cracking a barrel of powder into the water, and the poisoned-sea aftermath). The merged chapter keeps the title ***The Poison Sea*** and is now **Ch. 38**.
- **Renumbering:** with the two chapters now one, every later chapter shifted down by one. The old **Ch. 40–57** are now **Ch. 39–56**; the book runs **56 chapters**. The `The_Brewing_Storm_book1_chapters/README.md`, the chapter H1 headings, and the `Ch. NN` cross-references in `worldbuilding/` were updated to match.
- **Reading old references:** chapter numbers in entries *above* were written before this change and use the older numbering. To convert: a former **Ch. 40-or-later** is now one lower; a citation to the old **Ch. 39** (*The Poison Sea*) or the old **Ch. 38** (*What the Water Gave Back*) now lives in **Ch. 38**. (This is cumulative with the earlier Ch. 29 merge, so a citation predating both may sit two lower than its original number.)

## Ch. 27 — Gouge's crossing party is six, not the transcript's seven

- **Transcript says:** the party going ahead is Gouge and Merrick "and I think three swords and two bowmen" — seven all told. — `transcripts.lst`: `Wealsun/2nd/Gouge_Merrick_etal_travel_to_Barracks_2nd_Wealsun` (≈ lines 16, 74, 93).
- **Manuscript establishes instead:** **six** — Gouge, Merrick, Tyrus, Folsom, and two crossbowmen (the party fixed in Ch. 22). Under cover of Merrick's fog, the **two crossbowmen fall back** to the tower; the **four** (Gouge, Merrick, Tyrus, Folsom) cross the bridge and reach the garrison.
- **Why:** consistency with the six-man party established in Ch. 22 (*The Karmirg Signal*).
- **Related:** the barracks strength reads **120**, not the transcript's 150 (see the all-in-force / garrison-number entries above). And the telepathic hail at the palisade is given to **Folsom** (a bard's Message), not Merrick.

---

## Corrections — places where the manuscript was brought back into line with the verbatim record

*(Not intentional divergences. Recorded so a later pass doesn't "re-diverge" them.)*

### Signal method — a shuttered lantern (a night light-signal), not a sun-mirror heliograph

- **Transcript says:** the garrison and the southern tower signal one another by a *light* signal after dark — "It's like a light signal," and "you guys have signaling devices that work at night." — `transcripts.lst`: `Wealsun/2nd/Marines_get_signal_from_barracks_2nd_Wealsun` (≈ lines 136, 152); the scene runs at dusk into full dark ("it's going to be pretty dark").
- **Manuscript (now in agreement):** the signaling is done with a **shuttered lantern**, worked after sunset — Ch. 21 ("they had tried the lamps"), Ch. 22 ("a light blinking out"), Ch. 23 ("a squat brass lantern, working its shutter"). An earlier draft of Ch. 23 wrongly rendered it as a sun-mirror heliograph ("a hinged mirror against the dying sun," "reflected fire," "borrowed sunlight") — impossible at dusk/after dark, and at odds with the transcript and with Ch. 21–22. Corrected to a shuttered lantern.
- **Keep it consistent:** any future signal scene on the Helm uses shuttered lamplight at night, not sunlight.

### Ch. 26 — the Gouge briefing is Jude's, not Paul's

- **Transcript says:** in `transcripts.lst`: `Wealsun/2nd/Jude_Paul_discuss_abilities_2nd_Wealsun`, it is **Jude** (SPEAKER_00 — the caster: "I levitate shit," line 91) who knows Gouge and briefs Paul on him: "you're… gonna need to be able to take orders from… Gouge" (44), "How do you know this guy? / I've fought a war with him… the South Province" (52–57), "He's a killer" (67), "arguing's not in his wheelhouse" (80), "Anytime that I've ever argued with Gouge, I've been half prepared to have to kill him" (81). Paul (SPEAKER_01) is the one being briefed.
- **Manuscript (now in agreement):** Ch. 26 gives all of this to **Jude** — he ran with Gouge (the two of them "and a third," Karmirg left unnamed), tells Paul to let Gouge lead, calls him "a knife… built to kill," and owns the near-arguments. An **earlier draft had these lines backwards**, with Paul claiming the personal history — a departure from the transcript (Paul knows Gouge only through Jamis's stories) and from canon (Jude, Gouge, and Karmirg were companions — Ch. 21; `characters/Jude.md`, `Gouge.md`). Corrected so the flip matches the transcript.
- **Manuscript elaborations (added, canon-consistent, not contradictions):** Paul's curiosity is opened via Gouge having "crossed with us on the corsair" as a disguised crossbowman (true per Ch. 17, where Jude spots him in the ranks) and via Paul's broader interest in "Jamis's business and his agents." These develop character and are not in the source verbatim, but contradict nothing in it.
- **Do not re-flip:** the Gouge-history dialogue stays Jude's. Paul's knowledge of Gouge is secondhand only.

## Book 2 Ch. 8 — the powder is *not* harmless to air-breathers (raw powder lethal to inhale)

- **Transcript says:** the alchemist calls the compound inert to humans — "no human being would be affected by this… the same dose that's nothing to us would be lethal to them." — `transcripts.lst`: `Wealsun/4th/Jude_and_Paul_visit_Alchemist_4th_Wealsun` (≈ lines 55, 64).
- **Manuscript establishes instead:** the compound is *far* more dangerous to water-breathers, **but not harmless to air-breathers.** Diluted through the sea it is safe for a man to swim (the basis of the warding) and lethal to gilled creatures at a trace through the gills; but the **raw powder is deadly to inhale — breathing even a minute amount will kill a man.** This preserves and pays off Paul's mother's warning (Ch. 6, Ch. 31; Paul warns Tyrus of it in Ch. 38). The alchemist's fish demonstration is kept intact, but his "no harm at all" is reframed as diluted-in-water safety, and **Paul supplies the inhalation caveat**, silently recognizing his mother's warning confirmed. Ledgers updated to match: `The_Anti-Sahaugin_Powder.md` and `magic_system.md`.

## Structural — Ch. 39 and Ch. 40 reordered (deliberation before Jude's search)

- **Transcript order:** `Battle_w_Sahaugin` → `Jude_searches_for_Fairwind` → `Party_takes_short_rest` — i.e., Jude's solo search of the keep comes *before* the party's short-rest deliberation (the raw session is muddled: Jude scouts, the party rests and debates, then he goes invisible again and reports at the top of `Party_escapes_Helm_island`).
- **Manuscript establishes instead:** the deliberation comes first. **Ch. 39, *What Fire and Iron Decide*** (the short-rest council — hold the vantage, turn the locked garrison, take the signal tower — ending with Jude slipping off invisibly to search) now precedes **Ch. 40, *The Empty Racks*** (that search). Part Six opens on Ch. 39.
- **Why:** as originally adapted, the search chapter came first and *then* the council sent Jude off to perform the search we'd already read — and the council ignored his findings (the cove footprints, the vanished Sea Ghost). Reordering puts cause before effect: the party decides and Jude departs, then we follow the search, and Ch. 41 (*What the Shark Gave Up*, "while Jude searched") runs concurrent with it. Jude's motivation for going alone now lives at the end of Ch. 39, so Ch. 40's opening was trimmed to avoid repeating it.

## Ch. 44 — Gouge threw Fairwind; Jude killed the Toli (not "Jude threw Fairwind")

- **Transcript says:** in his debrief, Merrick credits **Jude** with throwing Fairwind into the water ("Jude did the throwing off into the water"). — `transcripts.lst`: `Wealsun/3rd/Merrick_Jamis_debrief_3rd_Wealsun` (≈ lines 43–50).
- **Manuscript establishes instead:** **Gouge** threw Fairwind over the edge (Ch. 37, "'Go drink with the fish, then,' Gouge said, and threw him over"; and Ch. 43, where Gouge owns it). **Jude** killed the captured **Toli** on the plank bridge and pitched that body into the water (Ch. 36). Ch. 44's Merrick account was corrected to match: Fairwind "end[s] grappling Gouge at the edge… that was how he went in himself," while "Jude killed the one Toli." Merrick's transcript mix-up (he was at the rear) is treated as the error, not canon.

## Structural — the manuscript split into two books (Book One: Ch. 1–48; Book Two: Ch. 1–8)

- **What changed:** the manuscript was divided into two volumes. **Book One** keeps chapters **1–48** and is titled *The Brewing Storm*; the manuscript directory `manuscript/chapters/` was renamed **`manuscript/The_Brewing_Storm_book1_chapters/`**. The former **Ch. 49–56** became **Book Two, Ch. 1–8** in the new directory **`manuscript/The_Scarlet_Thread_book2_chapters/`**. Chapter *titles were kept*, except that Book 2 Ch. 2 was later retitled from *What Jamis Already Knew* to *A Vintage from Keoland* (the volume title *The Scarlet Thread* went to the book, not the chapter); only the numbers (and the H1 ordinals) were reset. **Book Two is titled *The Scarlet Thread***, and each book's chapter directory is named with its title at the front — `manuscript/The_Brewing_Storm_book1_chapters/` and `manuscript/The_Scarlet_Thread_book2_chapters/`.
- **Old → new (Book Two):** 49→1 *The Prince's Charge*; 50→2 *A Vintage from Keoland* (retitled from *What Jamis Already Knew*); 51→3 *The Tower and the Storm to Come*; 52→4 *What Paul Wanted*; 53→5 *The First Cantrip*; 54→6 *The Wager*; 55→7 *What Paul Knew of the Toli*; 56→8 *Copper and Sulfur*.
- **Parts renumbered for Book Two:** the old **PART SEVEN (Debriefing in Monmurg)** straddled the book boundary (it opened at old Ch. 43, in Book One). Book Two's opening three chapters were given a fresh **PART ONE: DEBRIEFING IN MONMURG** header (added to Book 2 Ch. 1), and the old **PART EIGHT: THE FOURTH DAY** (old Ch. 52) became **PART TWO: THE FOURTH DAY** (Book 2 Ch. 4). Book One retains PART ZERO–SEVEN.
- **Transcripts split:** the eleven transcripts that source Book Two (the tail of `Wealsun/3rd/` — `Paul_briefs_Jeon`, `Jude_travels_to_Jamises_office`, `Judes_conversation_w_Jamis`, `Judes_conversation_w_Jamis_end` — and all of `Wealsun/4th/`) were moved to **`transcripts/book2/`** (subpaths preserved), with their own **`transcripts/book2/transcripts.lst`**. The root `transcripts/transcripts.lst` now lists Book One only, ending at `Wealsun/3rd/Long_term_reaction_to_The_Brewing_Storm` (the Ch. 48 close). Both `.lst` files remain the authoritative source of truth for their book.
- **Citation convention:** references to the renumbered chapters are written **"Book 2 Ch. N"** in `worldbuilding/` and this file, to distinguish them from Book One's "Ch. NN." Cross-references were updated accordingly (`magic_system.md`, `The_Anti-Sahaugin_Powder.md`, and this file); shared worldbuilding/character ledgers stay at the project root and serve both books. Book Two's continuity dependencies are indexed in `manuscript/The_Scarlet_Thread_book2_chapters/CONTINUITY.md`.
- **Note:** earlier entries in this file that say "the book runs 56 chapters" predate the split and describe the pre-split single-volume state; read them as historical.

## Book 2 Ch. 7 — the Port Toli prince is Sacnon, not the transcript's "Sconforth"

- **Transcript says:** the ruling prince of Port Toli is named "Sconforth." — `transcripts/book2/transcripts.lst`: `Wealsun/4th/Pauls_thoughts_on_the_day_4th_Wealsun`.
- **Manuscript establishes instead:** the Prince of Port Toli is **Sacnon Toli** (`worldbuilding/The_Sea_Principalities.md`; Book 1 Ch. 9, 11, 13). "Sconforth" was a table mis-naming; corrected to **Sacnon** in Book 2 Ch. 7 and in `The_Scarlet_Thread_book2_chapters/CONTINUITY.md`. (Not to be confused with **Secundforth**, the Viscount of Burle / ruling family of mainland Salinmoor — a separate house entirely.)
- **Why:** keeps the Toli ruler's name consistent with the worldbuilding ledger and Book One.
