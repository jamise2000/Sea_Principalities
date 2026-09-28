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

- **Transcript says:** Helm Island lies "between the Monmurg Peninsula and Flotsom Island." — `transcripts/cleaned/Jude_Paul_travel_to_Helm_Island_2nd_Wealsun_CLEANED.txt` (≈ line 7)
- **Manuscript establishes instead:** The large island the Helm sits beside, to the **east**, is **Jetsom**. **Flotsom** lies to the **south** of Monmurg and the Helm (and is the eastern lighthouse's relay target). — Ch. 17 *The Corsair* ("between the peninsula and the looming bulk of Jetsom Island"); `worldbuilding/Helm_Island.md`.
- **Why:** The transcript misnames the neighboring isle — the author's geography is the authority here. Jetsom is the eastern island beside the Helm; Flotsom is the southern one. The manuscript is correct; the transcript line is the error. (Note also the spelling: the manuscript uses "Flotsom"/"Jetsom," the raw transcript "Flotsom.")

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
- **"Captain" now reserved for ship's captains only (later pass).** Per an explicit authorial rule, the word "captain" is used *only* for someone who captains a ship; every land/staff use was changed. Garrison-leader references became "commander" in the Ch. 28 close (the four in the merged rousing scene, formerly Ch. 29, plus "the household captain" → "the commander"), Ch. 30 (two), Ch. 43, and Book 2 Ch. 3. Other non-ship uses also changed: the Redshore gate's "guard captain" → "guard commander" (Ch. 1); "captained mercenary companies" → "led mercenary companies" (Ch. 5); the personal superiors Folsom, Merrick, and Tyrus each call "my captain" → "my commander" (Ch. 34, 47; Book 2 Ch. 1); and Jeon's figurative "good captains and good fighters" → "good commanders and good fighters" (Book 2 Ch. 2).
- **Left as genuine ship's captains (do not change):** Captain Richard and every "the captain" for him aboard the corsair (Ch. 15, 17); the merchant-ship captain (Ch. 1); the corsair's captain during the return voyage (Ch. 43); Captain Nado, Merrick's father, a fleet navigator (Ch. 13); the privateer "captains like Cross" (Ch. 13); the naval "captains stationed" at Redshore (Ch. 45); and the pirate epithet "Captain Crimson" (Ch. 2, 11).
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

## Ch. 43 — Gouge threw Fairwind; Jude killed the Toli (not "Jude threw Fairwind")

- **Transcript says:** in his debrief, Merrick credits **Jude** with throwing Fairwind into the water ("Jude did the throwing off into the water"). — `transcripts.lst`: `Wealsun/3rd/Merrick_Jamis_debrief_3rd_Wealsun` (≈ lines 43–50).
- **Manuscript establishes instead:** **Gouge** threw Fairwind over the edge (Ch. 37, "'Go drink with the fish, then,' Gouge said, and threw him over"; and Ch. 43, where Gouge owns it). **Jude** killed the captured **Toli** on the plank bridge and pitched that body into the water (Ch. 36). the merged debrief (Ch. 43) was corrected to match: Fairwind "end[s] grappling Gouge at the edge… that was how he went in himself," while "Jude killed the one Toli." Merrick's transcript mix-up (he was at the rear) is treated as the error, not canon.

## Structural — the manuscript split into two books (Book One: Ch. 1–47; Book Two: Ch. 1–8)

- **What changed:** the manuscript was divided into two volumes. **Book One** keeps chapters **1–47** and is titled *The Brewing Storm*; the manuscript directory `manuscript/chapters/` was renamed **`manuscript/The_Brewing_Storm_book1_chapters/`**. The former **Ch. 49–56** became **Book Two, Ch. 1–8** in the new directory **`manuscript/The_Scarlet_Thread_book2_chapters/`**. Chapter *titles were kept*, except that Book 2 Ch. 2 was later retitled from *What Jamis Already Knew* to *A Vintage from Keoland* (the volume title *The Scarlet Thread* went to the book, not the chapter); only the numbers (and the H1 ordinals) were reset. **Book Two is titled *The Scarlet Thread***, and each book's chapter directory is named with its title at the front — `manuscript/The_Brewing_Storm_book1_chapters/` and `manuscript/The_Scarlet_Thread_book2_chapters/`.
- **Old → new (Book Two):** 49→1 *The Prince's Charge*; 50→2 *A Vintage from Keoland* (retitled from *What Jamis Already Knew*); 51→3 *The Tower and the Storm to Come*; 52→4 *What Paul Wanted*; 53→5 *The First Cantrip*; 54→6 *The Wager*; 55→7 *What Paul Knew of the Toli*; 56→8 *Copper and Sulfur*.
- **Parts renumbered for Book Two:** the old **PART SEVEN (Debriefing in Monmurg)** straddled the book boundary (it opened at old Ch. 43, in Book One). Book Two's opening three chapters were given a fresh **PART ONE: DEBRIEFING IN MONMURG** header (added to Book 2 Ch. 1), and the old **PART EIGHT: THE FOURTH DAY** (old Ch. 52) became **PART TWO: THE FOURTH DAY** (Book 2 Ch. 4). Book One retains PART ZERO–SEVEN.
- **Transcripts split:** the eleven transcripts that source Book Two (the tail of `Wealsun/3rd/` — `Paul_briefs_Jeon`, `Jude_travels_to_Jamises_office`, `Judes_conversation_w_Jamis`, `Judes_conversation_w_Jamis_end` — and all of `Wealsun/4th/`) were moved to **`transcripts/book2/`** (subpaths preserved), with their own **`transcripts/book2/transcripts.lst`**. The root `transcripts/transcripts.lst` now lists Book One only, ending at `Wealsun/3rd/Long_term_reaction_to_The_Brewing_Storm` (the Ch. 47 close). Both `.lst` files remain the authoritative source of truth for their book.
- **Citation convention:** references to the renumbered chapters are written **"Book 2 Ch. N"** in `worldbuilding/` and this file, to distinguish them from Book One's "Ch. NN." Cross-references were updated accordingly (`magic_system.md`, `The_Anti-Sahaugin_Powder.md`, and this file); shared worldbuilding/character ledgers stay at the project root and serve both books. Book Two's continuity dependencies are indexed in `manuscript/The_Scarlet_Thread_book2_chapters/CONTINUITY.md`.
- **Note:** earlier entries in this file that say "the book runs 56 chapters" predate the split and describe the pre-split single-volume state; read them as historical.

## Book 2 Ch. 7 — the Port Toli prince is Sacnon, not the transcript's "Sconforth"

- **Transcript says:** the ruling prince of Port Toli is named "Sconforth." — `transcripts/book2/transcripts.lst`: `Wealsun/4th/Pauls_thoughts_on_the_day_4th_Wealsun`.
- **Manuscript establishes instead:** the Prince of Port Toli is **Sacnon Toli** (`worldbuilding/The_Sea_Principalities.md`; Book 1 Ch. 9, 11, 13). "Sconforth" was a table mis-naming; corrected to **Sacnon** in Book 2 Ch. 7 and in `The_Scarlet_Thread_book2_chapters/CONTINUITY.md`. (Not to be confused with **Secundforth**, the Viscount of Burle / ruling family of mainland Salinmoor — a separate house entirely.)
- **Why:** keeps the Toli ruler's name consistent with the worldbuilding ledger and Book One.

## Structural — Ch. 43 and Ch. 44 merged into one joint debrief (Book One now 47 chapters)

- **What changed:** the two back-to-back debrief chapters — **Ch. 43, *What Gouge Told Jamis*** and **Ch. 44, *What Merrick Told Jamis*** — were merged into a single joint scene, **Ch. 43, *What Gouge and Merrick Told Jamis***, in which the two report to Jamis together and corroborate each other. The powder-history exposition was tightened: Gouge produces Admiral Flotsom's book (paying off Ch. 42), establishing that he and Merrick have read the history, so Jamis supplies only the new intelligence rather than lecturing it. The private Gouge/Jude character assessments were preserved as a one-on-one word between Jamis and Merrick after Gouge is dismissed. Jamis also raises, without naming it, the possibility of a hidden organization moving Berghof, the Toli, and Gradsul alike (the Scarlet Brotherhood is deliberately not named here).
- **Renumbering:** with the two chapters now one, every later chapter shifted down by one. The old **Ch. 45–48** are now **Ch. 44–47**; Book One runs **47 chapters**. The `README.md`, the chapter H1 headings, and the `Ch. NN` cross-references in `worldbuilding/` and this file were updated to match. PART SEVEN still opens on Ch. 43.
- **Originals preserved:** the pre-merge **Ch. 43** (*What Gouge Told Jamis*) and **Ch. 44** (*What Merrick Told Jamis*) were kept, unedited, in `manuscript/The_Brewing_Storm_book1_chapters/superseded/`.
- **Sources:** the merged chapter draws on both `Wealsun/3rd/Gouge_Jamis_debrief` and `Wealsun/3rd/Merrick_Jamis_debrief` (a structural combination, not a change of fact).
- **Reading old references:** a citation to an old Ch. 45-or-later means the chapter now numbered one lower; anything that pointed at the old Ch. 44 now lives in the merged Ch. 43.

## Adaptation — early-cast load reduced in Ch. 3 / Ch. 11 (Priority #4)

To ease the front-loaded faction load in PART ZERO–ONE, two threads that paid off nowhere in either book were cut from the Ch. 3 briefing (and the Ch. 11 recap tightened):

- **Seebo Beren** (the gnome alchemist traveling with Phranck, "seeking a cure") — cut entirely. He appeared only in Ch. 3 and had no later payoff in Book One or Book Two.
- **The Duke of Gradsul's Suel-bride bargain** — cut. It appeared only in Ch. 3; the Toli–Gradsul–Berghof alliance it implied is already carried by the Scarlet Brotherhood passage in the same chapter.

**Kept as a deliberate seed:** the **black sickness** and the **Sons of Olan** (the necromantic cult behind it) remain in Ch. 3 and Ch. 11, trimmed to a concise mention. Per the author, the black sickness pays off in later Book Two chapters, so it must not be cut.

The Ch. 11 council recap was also lightly compressed (the definitional aside on what an Inquisitor is) to reduce restatement of Ch. 3. These are adaptation trims, not contradictions of the transcript.

## Book 2 Ch. 8 — the alchemist's name is Albashon (transcript's "Varen"/"Viren" corrected)

- **Transcript says:** the master alchemist of the Foreign District is named **"Varen"** (`transcripts.lst`: `Wealsun/4th/Jude_in_Alchemy_shop_4th_Wealsun`, line 1; and a garbled "Viren," line 32).
- **Manuscript / ledgers establish instead:** his name is **Albashon** — the name he is given in `Wealsun/4th/Leslies_introduction_4th_Wealsun` ("His name is Albashon"), and the form used across `characters/Minor_characters.md`, `characters/Leslie.md`, and `worldbuilding/The_Anti-Sahaugin_Powder.md`.
- **Action taken (author ruling: "make it consistent across the worldbuilding files and the transcripts"):** the two name tokens in `Jude_in_Alchemy_shop` (lines 1 and 32) were changed from **Varen/Viren to Albashon**. Line 32 remains a garbled sentence in the raw record ("you hand Albashon to Gils" — intended sense: Jude hands the sahuagin gills to the alchemist); only the name token was normalized.
- **Note:** this is the second verbatim transcript body edited for a name (after `Owen_shows_his_face`); all other transcript bodies remain the raw record.

## Powder canon (author rulings) — figures to reconcile in the manuscript

Author rulings on the anti-sahaugin powder (recorded in `worldbuilding/The_Anti-Sahaugin_Powder.md`, `magic_system.md`, `The_Orb_of_the_Dragon_Turtle.md`, `The_Dragon_Isles.md`). Two of them **supersede numbers currently in the chapters** — flagged here so a later pass brings the prose into line rather than treating the ledger as the error:

- **Supply cutoff is ~40 years ago, not 20.** Book 2 Ch. 8 (and its earlier ledger wording) has the recovered sample "about twenty years old." Canon is now **~40 years** since the supply was cut off (a fact "not common knowledge"). Reconcile Ch. 8.
- **~25 barrels is the whole remaining supply in Monmurg's hands = 21 on the island + 4 rafted home.** Book 2 Ch. 2 reads "twenty-five … on the island / four rafted home." Canon: only **21** were on the island; with the **4** rafted home that makes **25 total** remaining to the Prince of Monmurg. Reconcile Ch. 2's wording (island figure is 21; 25 is the standing total).
- **No manuscript change needed** for these (already consistent or new): the compound **is copper sulfate** but is never named so — Albashon calls it **vitriolum** (blue vitriol) / "copper and sulfur, combined in a way few know," and his "sulfur and iron" = **iron sulfate** (green vitriol); it was **invented and mass-produced by the Duke of Berghof** (the Fieraxian attribution is a mistaken assumption); eradication dates **CY 427–430**; **Pocra Sententia** is a primary powder staging ground and Cain's fortress; and **the dragon scheme is part of the powder scheme** (isolate Monmurg + seal the stores → defenseless against the sahaugin).

## Book 2 Ch. 8 — the transmuter is Zafar Azane (transcript's "Zafar Zane" corrected)

- **Transcript says:** in the alchemist scene, Albashon names the great Keoland transmuter "**Zafar Zane**" (`Wealsun/4th/Jude_in_Alchemy_shop`, line 274).
- **Canon:** his name is **Zafar Azane** (`worldbuilding/magic_system.md`, `characters/Jamis.md`, Name Normalization Key). Normalized in that line at the author's instruction. (The Book One transcript `Wealsun/3rd/Party_considers_options` line 872 still reads "Zafar Zane"; leave for the Book One cleanup pass.)

## Book 2 Ch. 7-era — Jamis names the great Suel houses (added dialogue)

- **Author addition (speaker-review pass):** in `Wealsun/3rd/Judes_conversation_w_Jamis`, Jamis's answer about who Keoland's civil war is "between" was extended from "Well, the Dukes." to **"Well, the Dukes, and the great Suel Houses of that nation."** — tying the succession conflict to the great Suel houses (see `Name_Normalization_Key.md`, "The great Suel houses"). Content change to the raw transcript, made deliberately.


## Jude_and_Paul_visit_Alchemist (3rd/4th Wealsun) — author ASR/dialogue corrections
- **L36** (Albashon): "I remember you as your friend." → **"I remember you. Who is your friend?"**
- **L170** (Albashon): "It's inert to us." → **"It's inert to us in this concentration and form."**
- **L195** (Albashon): "This was made by the Phyraxians." → **"This was made by the Duke and possibly the Fieraxians themselves."** (ASR "Phyraxians" → **Fieraxians**)
- **L282** (Albashon): "This is the life of Transvienter." → **"This is the life of a transmuter."** ("Transvienter" was ASR for the profession **transmuter**, NOT a name/alias.)
- **L293** (Albashon): "I don't know him." → **"I don't know him well."**


## Jude_in_Alchemy_shop (4th Wealsun) — author dialogue correction
- **L117** (Albashon): "Oh, well, in Keoland necromancy is not forbidden." → **"Oh, well, in Keoland necromancy is forbidden but not here."**


## Paul_goes_to_fetch_formula (4th Wealsun) — author corrections
- **L111** (DM): "…Joanne Moraine's died." → **"…Jeon's marines died."** ("Joanne Moraine" was ASR for **Jeon's marines** — the Monmurg fleet took casualties.)
- **L116 — SPLIT:** DM "…the Marines that brought you back…" | **Paul** "Aren't they technically still fighting there?"


## Paul_hurries_toward_the_fire (4th Wealsun) — author correction
- **L260** (DM): "…begin moving this way into the war." → **"…into the warren."** (ASR "war" → **Warren**)

## Paul_examines_Alchemists_body (4th Wealsun)
- L85 "We have the cards." → "We have the carts." (ASR)
- L98 "If I were a Jew, what would I do?" → "If I were Jude, what would I do?" (ASR)
- L1 header "At 2 p.m." is wrong — scene is night (follows the nighttime fire/raid); correct to evening/night.

## Departure_from_Monmurg (4th Wealsun)
- L1 "Fourth of Well, Son" → "Fourth of Wealsun" (ASR).
- L21 "the Sloof's deck plant" → "the sloop's deck plan" (ASR).
- L116 "that fling floating" → "that thing floating" (ASR).
- L146 "sahagin" / L156 "Azur sea" → "sahuagin" / "Azure Sea".
- L223 "Finest, Toli, rung" → "finest Toli rum" (ASR).
- L225–226 "Black is your heart / is my last name" → "Black **as** your heart, boy! / Black **as** my last name!" (author).
- L270/288/333/356 "Kane Toli / King Toli / Kane Tully" → "Cain Toli".
- L281/301 "Selinmore / Selenmore" → "Selinmore".
- L297–301/354 "Laplar / Lord Balin / the plaw" → **the Plar** of Salinmoor, Lord Gloin Baywin (author confirms "Laplar" = "the Plar").
- L311 "Sac Nontoli" → "Sacnon Toli".
- L341 "the arrows go on" → "the hours go on" (ASR).
- L367/373 "Owen Blackwell" / "the Blackwell family" → Folsom misspeaks; canon is "Owen Black" with no Blackwell family — flag Owen's L373 assent.
- L394 "Flossum" → "Flotsam".

## While_Owen_Slept (4th Wealsun)
- L9 "Bart" / L134 "op-munk" — ASR garbles (drop/repair in prose).
- L46 "Evan's ego" / L102 "how long has Ellen been asleep" → "Owen".
- L28 "Kane Tolley" → "Cain Toli".
- L95–96 "sahagin" → "sahuagin".
- L159–161 heavily garbled ASR (possible OOC) — review/trim.

## Passage_through_Dragon_Isles (5th Wealsun)
- L1/L603 "Whalesun" → "Wealsun".
- L66 "I don't mean to cry" → "I don't mean to pry" (ASR).
- L466 "a supply as large as the Hound did" → "…as large as the Helm did" (ASR).
- Cain Toli garbles throughout ("Kane Tolley / Caintoli / Cain Tole / Kane totally / King Toli / Keitoly") → "Cain Toli".
- L857 "a lynch called Aserach" → "a lich called Acerak" (= Ujor Udias; the Orb of the Dragon Turtle).
- L858 "Exit told Cain Tolley" → "Ixid" (necromancer of the Sons of Olan).
- L118 "Sacknon Toli" → "Sacnon Toli"; L83 "Selenmore" → "Selinmore".
- L69-72/L81 "Hull Marshes / Hula Martian" → "Hull Marshes"; L118/L454 "Berghoff/Berkhoff" → "Berghof".
- L95/L675 "sahagin" → "sahuagin"; L157 "Azur Sea" → "Azure Sea".
- "Seaghost / seagulls / sea ghost" → the "Sea Ghost" (Cain Toli's cutter).
- NOTE (canon reveal): the artifact = the Orb of the Dragon Turtle; it CONTROLS the turtle dragons, and Cain Toli is using it to pull them off the Dragon Isles — the on-page answer to why the isles fell silent.

## Owens_suspicians (5th Wealsun)
- "Kane and Toli / Kane Tolley / Cain Tolley" → "Cain Toli".
- L8 "Jameis" → "Jamis"; L8 "Prince Gian" → "Prince Jeon" (ASR).
- L27/29/30 "Goug" → "Gouge".
- L9/10/17 "NATO / Captain Nato" → "Captain Nado" (Merrick's father).
- L38 "pouring himself a dream of it" → "a dram of it" (ASR).
- L43 "a shot of the Black Realm" → "the black rum" (ASR).

## Making_Redshore (6th Wealsun)
- L64 "the Dig of Grasel" → "the Duke of Gratzel" (ASR).
- L86/L158 "Keogs / Keog marines" → "Keoland / Keoish".
- L113 "prince of Burghoff" → "Berghof".
- L127 "charter room" → the "Chart Room" (the Redshore bar; Owen says "chart room" at L153).
- Song (L100-116) is Folsom's satire "O Monmurg" — retain as his performed lyrics.

## Folsom_tells_Merrick_what_he_has_learned (6th Wealsun)
- L2 "sixth of Whale Sun" → "Wealsun".
- Acerak garbles ("Azzagon / Agath / Azrek / Asarak / Aserach") → "Acerak".
- "Keintoli / Cane Tolis / Can Toli" → "Cain Toli".
- L74-81 "Gion / Gian" → "Jeon" (Prince Jeon).
- L162 "Salimor" → "Salinmoor".
- CANON: History check gives Acerak = lich of Salinmoor ~600 yrs ago, warred with House of Gratzel; Sons of Olan named for Lord Olan, a vampire Acerak created (reconcile with Name Key "Count Olan's master").

## Discussions_in_the_Chart_Room (6th Wealsun)
- "Prince John / Gian / Gion / Jean" → "Prince Jeon".
- L104 "Cain Tolley" → "Cain Toli".
- L152 "Hell Island" → "Helm Island".
- L165 "Calceres" → "Corsairs" (ship type).
- L178 "he is Sewell" → "he is Suel" (the mob leader is a Suel man; NOT a name).
- L68 "Gian would never do this to his sister" → "Jeon would never do this to the Sea Principalities" (author).

## Blood_on_the_Charts (6th Wealsun)
- Combat log — ~90% mechanics; only the in-story beats (see cast_mapping) go into prose.
- The mob leader = the Toli/Suel muscle from the Chart Room ambush; he yields "I was only paid for this" (L1434).
- L159 "Medellas" = Modelos (real-world beer, out-of-band).

## Owen_shows_his_face (6th Wealsun)
- Torus (NPC, Cain Toli's Suel handler) is distinct from Tyrus (PC). "a soul"(69)/"Asul"(156)/"Toli reaches down"(121) → Torus.
- L50/74 "Portoli" → "Port Toli".
- L76/112/116 "Kane/Cain/Keoland totally" → "Cain Toli".
- L87 "the stone" → "the Orb" (Orb of the Dragon Turtle).
- L89 "the Lich Azorak" → "Acerak".
- L102 "Folsom goes, I mean not Folsom, Owen Black says…" — speaker is Owen (DM self-correction).
- L181 "Owen Blackwell" → "Owen Black".
- PLOT: Owen's betrayal — he sells Folsom to Cain Toli (via Torus); Folsom blinds Owen with the rum and escapes.

## Owen_and_Torus_plan (6th Wealsun)
- DM interlude (Owen + Torus, DM-voiced); Torus's closing interior monologue kept as DM narration.
- L11/15 "Kane-Toli's island" → "Cain Toli".
- L58 "Jameis" → "Jamis"; "Red Shore" → "Redshore".
- L55 "Redshore's minute arms" → "armsmen / minute-men".
- CANON: "the gift of Insamiar" (the special draught / poison Owen used) is an addictive drug tied to the Followers of Insamiar — NOT yet in Name_Normalization_Key.md; recommend adding.

## Merrick_Tyrus_and_Gouge_look_for_Folsom (6th Wealsun)
- "principality / Principalities coins" → "Sea-Principality gold"; L48 "gold points" → "gold coins".
- L70/126 "Tim Tufts / three Tufts" → DM slang for the hired toughs.
- "Toli rats" → Torus's Toli hirelings; L203 "sacked outside" → "stacked outside".
- Tyrus (PC) throughout; the NPC Torus does not appear here.

## Gouge_waits_in_the_dark (6th Wealsun)
- L63/105 "King Toli / Caintoli" → "Cain Toli".
- L57 "a Toli, a Toli friend" → Torus.
- L112 "Rumwood" → the black rum (Toli/Port-Toli rum).
- L123 "the phone's under protection" → "he's / Folsom's under protection" (ASR).
- L5 "Terry" = real player name (out-of-band), not a character.

## The Party Waits for Owen's Return (6th Wealsun)
Speaker-tag character-lock applied (crew registry: DM 00A, Gouge 04A, Merrick 05A, Tyrus 06A, Folsom 07A; no NPC speaks). Class-feature disambiguation: Tyrus=Lay on Hands (190–191), Gouge=Second Wind (fighter, 212–215), Merrick=coastline Expertise (rogue, 171–174), Folsom=first-hand capture account.

ASR / name fixes:
- "King Tolley" / "Cain Tolley" / "Cain" (47–60) → **Cain Toli**. The DM explicitly corrects at 57–60: there is no King Tolley.
- "a crater that black we're on" (105) → "a **crate of that black [rum]**" (cf. 195 "that crate of black rum").
- "Himx comes back" (115) → "**He** comes back."
- "An N to stay in" (165) → "an **inn** to stay in."
- "this whole aisle went" (172) → "this whole **isle**."
- "Shadows, me, said, I'll stay up watching" (204) → "[In the] shadows… I said, I'll stay up watching."

Canon / continuity:
- Owen's betrayal is now confirmed on-page to the whole party; they name **the artifact** (the Orb) as what Owen/Torus were pressing Folsom about, and that **Tyrus slept through** the earlier reveal (cf. *While Owen Slept*), so he doesn't yet know about it (71 "what artifact?", 73 "you were sleeping").
- Party decision: **stay** (not flee by sea — slow ship, turtle-dragons at the Dragon Isles), hole up on the **hill above the dock**, light the ship's lanterns as bait/signal, set a two-and-two watch. Sets up the return-to-Redshore watch storyline.
- **"gift of Insamiar"** entry for `Name_Normalization_Key.md` still pending (recommended from *Owen and Torus Plan*).

## Jude and Leslie Take Shelter (4th Wealsun)
Speaker-tag character-lock applied (Jude/Paul registry: DM 00A, Jude 01A, Leslie 03A; NPC Ferd = 01B). Very bleed-heavy file — DM and Ferd share raw02; Jude's raw01 carries heavy DM/Ferd bleed. Separated three ways by content.

ASR / name fixes:
- "walk in deferreds" (68) → "walk in [to] **Ferd's**" (the tavern name garbled).
- "Black Owen" (243) → **Owen Black** (Ferd corrects in-scene at 244).
- "Janice" (157) → the thieves'-guild master (name garbled; author to confirm canonical spelling).
- "the Duke of the Parkhouse" (216) → likely **Duke of Berghof / Plar of Hokar**.
- "Medio Jungle" (71) → **Amedio**; "Hul Marshes" (71) → **Hool Marshes**.

Canon / continuity:
- Sets the Paul/Jude thread on the evening of the 4th of Wealsun: Jude and Leslie escape the sewers into Blood Alley (Foreign District) and hole up at Ferd's, a mercenary tavern where Jude keeps a room.
- Plot threads surfaced (delivered largely as OOC recall, tagged [game mechanics] so nothing is lost): Jude's rogue contact **Gregory** (tasked 2nd Wealsun, due to report 7th) is investigating guild-master **Janice** (8 months in post) for Toli/Scarlet-Brotherhood ties; Gouge's crew and **Owen Black** were in the Harbor District the night a Marine bard sang a politically reckless song.
- **Cain Toli is not common knowledge** in-world (DM ruling, 189) — Jude declines to start a Toli rumor.
- The tavern's cheap whiskey is a **nerve-deadening poison**; Leslie the alchemist identifies it and refuses.
- **OOC name-slip (297):** the masked man Jude references is **Paul**; keep him "the masked man" in Jude's in-scene dialogue.

Split candidate (not applied, flagged): 336 "Jude says, I need a trance." (DM frame + Jude quote on one line).

### Jude and Leslie Take Shelter — author review round 1 (corrections)
Re-tags: 66, 86, 88, 98 → Leslie (03A); 113 → Ferd (01B); 114, 251 → Jude (01A).
Body edit: 276 → "I got plenty of brain cells, but I want more, not less." (Leslie).
Ferd-garble body edits (author ruling that ASR "her/hers/deferred" = Ferd): 43 & 44 "hers" → "Ferd's"; 68 "walk in deferreds" → "walk in to Ferd's"; 69 "I nod deferred" → "I nod to Ferd"; 79 "walk up to her" → "walk up to Ferd". Line 124 "her" left unchanged (a real female — the masked attacker). Added "her/hers/deferred → Ferd/Ferd's" to Name_Normalization_Key guidance for this speaker.

## Leslie Ponders His Future (4th Wealsun)
Speaker-tag character-lock applied (DM 00A, Leslie 03A). ENTIRELY out-of-character: Leslie's player and the DM plan his character build. No in-scene roleplay — 67 lines tagged [game mechanics], 4 lines [out-of-band].

Notes:
- "Ryan" (7) = the DM's real name (OOC); not a character.
- Character direction (reference only): Leslie is a level-2 transmuter aiming for the Inventor + Alchemist feats (levels 4 and 8); wants to bring an industrial revolution — a factory/brand, hiring inventors. Starts with 10 gold from his late master Albashon, whose shop of knowledge/materials he intends to explore (sets up the next scene).
- [out-of-band] 64-67 = real-world pencil interruption.
- Place names (OOC): Greyhawk City, Gratzel, "Iola Drah" (ASR; author to confirm), Monmurg.

## Paul Waits for Jude (5th Wealsun)
Speaker-tag character-lock applied (DM 00A, Paul 02A; NPCs: palace guard 01B, servant 02B — numbered by appearance). Two diarizer voices; DM voices both NPCs. 6 lines [game mechanics], 4 [out-of-band].

Canon / continuity:
- The six non-responsive captives are drug-addled and "dreaming" (16-22, 61-63); one mutters "the dragon, the dragon" (74). Strongly reads as the Insamiar drug-rite (the black-dragon "Blessing"/"gift of Insamiar"; cf. worldbuilding/Insamiar_the_Black.md) — ties the Scarlet-Brotherhood raiders to that cult/drug. Flagged for author.
- Paul jails the suspects (two dangerous SB members in the most secure cells, five armed guards); releases the six drugged ones ("catch and release"); keeps the two for later; reads a book on torture to prepare. Jude arrives at the front gate at the end (sets up Jude_reports_to_Paul / the interrogation scenes).

Normalizations / flags:
- "methed out" (60) → "drugged / drugged senseless" in prose (Paul's modern phrasing).
- [out-of-band] 110-113 = modern-reference jokes about the torture book ("A Noob's Guide," "Torture for dummies"); the book itself is a real in-story item.
- Split candidates left merged (flagged in cast mapping): 26, 44. Embedded prisoner mutter at 74 kept in DM narration.

## Jude and Leslie Return to the Lab (5th Wealsun)
Speaker-tag character-lock applied (DM 00A, Jude 01A, Leslie 03A; NPCs: shop-cordon sergeant 01B, north-gate guard 02B — by appearance). Three voices, bleed-heavy. 5 lines [game mechanics], 0 out-of-band.

ASR / name fixes:
- "Paul Ribeiro" / "Paul Rivero" / "Paul Rivera" (115-124, 149, 185) → **Paul Revero**.
- "1 p.m. in the morning" (8, also 50, 62, 107) → **1 a.m.**
- "the Palix District" (89) / "Upper City" (94) → the palace/Upper-City guard (author to confirm "Palix" district name).
- "red-eye black rum" (49) → red-eye / black rum (Ferd's stock).

Canon / continuity:
- ~1 a.m., 5th Wealsun: Jude wakes Leslie and they go to check the burned alchemist shop. Jude fears he torched it with fire spells during the raid; Leslie recalls his master bleeding black ooze from his eyes (assassin's poison).
- Shop is cordoned by five Upper-City guardsmen; a sergeant refuses passage and won't help reach Paul Revero ("a prince of the city"). Jude opts to fetch Paul from the palace rather than risk the Warrens.
- At the north gate (~1:30 a.m.) a guard recognizes Jude as "the wizard" (who trains Paul) — sets up Jude reuniting with Paul (Jude_reports_to_Paul).
- Worldbuilding: the "Row of the Gods" — rented foreign temples + hawkers + a red-light strip in the Foreign District. (The "pharaoh"/"Vestal Virgins" lines are real-world analogies for flavor, not literal.)

Flags: guard frame+quote lines 113, 124 kept on the NPC tag (split candidates); 189 "Let him see me" garbled (attributed to gate guard); 82-83 possible solicitor NPC (kept as Jude); 110 "Jude, we're just walking past" attributed to Leslie (vocative).

### Jude and Leslie Return to the Lab — author review round 1 (corrections)
- 115 re-tagged Jude (01A) → guard (01B); body "Order Paul Ribeiro." → "Order of Paul Revero." (sergeant citing whose order closed the area).
- Body edits: 8 "1 p.m. in the morning" → "1 am in the morning"; 89 "Palix District" → "Palace District"; 91 "You walked over some kind of an anthill." → "Kicked over some kind of an anthill."
- Remaining Paul-name garbles (116 "Ribeiro", 124 "Rivero", 149/185 "Rivera") left as raw record; normalize to Paul Revero in prose.

## Jude Reports to Paul (5th Wealsun)
Speaker-tag character-lock applied (DM 00A, Jude 01A, Paul 02A, Leslie 03A; NPC servant 01B). EXCEPTIONALLY bleed-heavy — Paul (raw01) and Jude (raw02) trade tags constantly; separated by content. 11 lines [game mechanics], 8 [out-of-band]. PC ID anchors: Paul recounts going to HIS palace for HIS books + holds the prisoners (raw01); Jude reports the raid/master's death + wants to interrogate (raw02).

Canon / continuity (important):
- The GIFT OF INSAMIAR is named on-page (84-88): the poison that killed Albashon (black fluid from the eyes), distinct from his physical wound. Matches the author ruling (poison; dragon-origin a rumor). Cross-ref worldbuilding/Insamiar_the_Black.md.
- The dying master's "I know what Paul needs" = the ANTI-SAHAUGIN POWDER (98-104), tied to Paul's face; Jude can't recreate it from memory — raises stakes on recovering the burned shop's contents (magicked firebox). Cross-ref worldbuilding/The_Anti-Sahaugin_Powder.md.
- A female Scarlet-Brotherhood captive is held in Paul's dungeon (likely the masked raid attacker) — interrogation target for the next scenes. Party heads down to the dungeons at the end.

ASR / name fixes:
- "Paul Rivero" / "Paul Rivera" (5,7,25,245) -> Paul Revero.
- "Prince Jean's" (2) -> Prince Jeon's.
- "the fifth of the well sun" (1) -> the 5th of Wealsun.
- "Scarlet of the Brotherhood" / "Skrull Brotherhood" (61,138,160) -> Scarlet Brotherhood.
- "Absalon's Methods of Torture" (7) = the torture manual (confirm canonical spelling).

Flags: severe Paul/Jude bleed (needs full author scan); Leslie's babble sometimes on other tags (63-66, 196-200, 245-248); Rodiger confusion (173-178); mixed lines left merged (78, 206). [out-of-band] 249-255 = Canada/Keoland real-world riff; 281 = "pizza".

### Jude Reports to Paul — author review round 1 (corrections; file now 283 lines)
- Re-tags to Paul (02A): 32, 63, 64, and old-74 "I believe I did" (now line 75).
- Re-tag to Leslie (03A): 69 "Uh, blame Jude for that."
- Split at 73: "Well, I mean... Oh, I did grab the body, yes." -> 73 "Well, I mean..." (Jude 01A) + 74 "Oh, I did grab the body, yes." (Paul 02A). Later lines shift +1.
- Body edits: 52 "my boy" -> "my guardsmen" (Paul is with his guardsmen, sees the fireball, knows it's Jude); 56 "It's an alchemy show." -> "It's a fireworks show."; 234 (old 233) -> Leslie 03A: "No, red is your favorite color, you just don't know it yet."; 248 (old 247) -> "Right. Like it matters you are a prince."

## Jude and Paul Interrogate Prisoners (5th Wealsun)
Speaker-tag character-lock applied (DM 00A, Jude 01A, Paul 02A, Leslie 03A; NPCs: jailer/guard 01B, female prisoner 02B). Bleed-heavy on PC tags. 4 lines [game mechanics], 4 [out-of-band].

Canon / continuity:
- THE TRANSFORMED = YUAN-TI (7-22): the captured Scarlet-Brotherhood agents are people transmuted into snake-people (fangs, slit eyes, scales) by eastern transmuters to serve as slaves; Albashon had described them. Significant reveal about the Brotherhood's agents. (No dedicated Yuan-ti worldbuilding file yet — recommend one.)
- FANG-VENOM (94, 189-197): Jude milks a pale-green toxin from the prisoners' fangs as a working poison sample, tied to the alchemist's murder / the Gift of Insamiar thread. Author to confirm whether this snake-venom IS the Gift of Insamiar or a related toxin.
- Female prisoner curses in Ancient Suel ("You've failed, you foolish elf") - Suel/Brotherhood link.

ASR / name fixes:
- "Paul Ribeiro" (1) -> Paul Revero; "Walesun" (1) -> Wealsun.
- "the Yontai" (20) -> the Yuan-ti; "Ancient Soul" (65) -> Ancient Suel; "Absalon" (19) -> Albashon; "a nit check" (13) -> int/knowledge check.
- "Dr. Mangala" (122) = real-world ref (~Dr. Mengele); recast or cut for prose.

Flags: does the male prisoner speak? Line 70 "The alchemist is dead." attributed to Jude (could be the male prisoner -> would need 03B). Combined frame+quote lines 56/65/129 kept on NPC tags (split candidates). Garbled table cross-talk 174-179 (178 "Dude, wake up" = OOB). [out-of-band] 91/93 = "Pokemon catcher" (the man-catcher pole is a real item).

### Jude and Paul Interrogate Prisoners — author review round 1 (corrections)
- 110 "Who can lift a 50-ton block?" re-tagged Leslie (03A) -> Jude (01A).
- Body edits: 44 "tries to sit in her face" -> "tries to study her face"; 69 "I look at the mail" -> "I look at the male".
- Confirmed no change: 77 Jude asking Paul; 121 "Workers." = Leslie.

## Jude and Paul Interrogation (cont.) (5th Wealsun)
Speaker-tag character-lock applied. NOTE different diarizer layout than the prior file: raw00=Leslie(03A), raw01=DM(00A)+male prisoner(01B), raw02=Paul(02A), raw03=Jude(01A). Very bleed-heavy; prisoner separated from DM by content. 21 lines [game mechanics], 1 [out-of-band].

Canon / continuity (major):
- Insamiar = ancient black dragon; the Yuan-ti snake-cult (Scarlet Brotherhood) worships it and takes snake-form VOLUNTARILY to "hear the dragon." Ties Brotherhood -> Insamiar. (Recommend a Yuan-ti worldbuilding file; cross-link Insamiar_the_Black.md.)
- The Gift of Insamiar = "a liquid from the dragon's self," causing insanity / "complete clarity" / "passage into consciousness." On-page CULT assertion of dragon-origin (author ruling: treat as in-world claim/rumor). Fang-venom + "Samovar/Insamiar Plague" ("Black Plague in the marshlands") are this thread. "the Negrado" (160) = the nigredo (alchemical blackening).
- Motive for Albashon's murder: he was developing a COUNTER to the Gift (to abrogate its effects / ease the afflicted before the war); Brotherhood killed him to stop it, and to stop Paul recreating the anti-sahaugin powder ("the powder Cain Toli took from the Helm"). Cross-ref The_Anti-Sahaugin_Powder.md.
- JUDE-CORRUPTION foreshadowing: the prisoner marks Jude (an elf, "colder eyes than the others") as susceptible to the Gift / hearing the dragon's call; "in time he will fall and succumb." Thread to watch.

ASR / name fixes:
- Samyar/Insigniar/Nsemiar/Samiar/Samovar/"Gift of Insanity" -> Insamiar / Gift of Insamiar / Insamiar Plague.
- "the Negrado" (160) -> the nigredo. "Sewell"/"Sewell Brotherhood" -> Scarlet Brotherhood / Suel (by context).
- "Kane Toli" (377) -> Cain Toli; "Paul Ribeiro" (4,368) -> Paul Revero; "the Helm" -> Helm Island; "white/yellow powder" -> anti-sahaugin powder; "fifth of Whale's son" (1) -> 5th of Wealsun.
- "Dave" (69, OOB) and "Tom" (216) = real player names; drop in prose.

Flags: prisoner/DM split on raw01 needs verification (esp. 225-232, 254-263, 286-291, 349-387); base PC mapping (raw02=Paul, raw03=Jude); 273-280 "I am the book" riff left on Paul (possible OOB); guard's lone reply (32) folded into DM narration; female prisoner does not speak here.

### Jude and Paul Interrogation (cont.) — author review round 1 (corrections)
- 69 NOT out-of-band: Paul (02A) "Come on, Jude" (reasoning with Jude). "Dave" = misheard "Jude". File now has zero out-of-band lines.
- 216 "a fork, Tom?" -> "a forked tongue." ("Tom" = misheard "tongue", not a real name). Both earlier "real player name" flags were garbles.
- Re-tags: 136 -> Paul (02A, repeating "Insamiar"); 161 ("What's that?") -> Leslie (03A, alchemy); 273-280 ("I am the book...") -> Leslie (03A); 298 ("A cheap slave") -> Leslie (03A); 243 ("Then he lets on") -> DM (00A) narration.
- Body edits: 131 -> "It is Insamiar's call."; 135 -> "Insamiar."; 136 -> "Insamiar."; 240 -> "...a very cold crowd."; 318 -> "The guard brings you a spoon."

## Jude and Paul Confer (5th Wealsun)
Speaker-tag character-lock applied. Diarizer layout: raw00=DM(00A), raw01=Leslie(03A), raw02=Paul(02A), raw03=Jude(01A). No NPCs. Bleed-heavy comedic negotiation. 0 game mechanics, 8 [out-of-band].

Canon / continuity:
- Albashon's hidden "knowledge box": a stone secret compartment UNDER HIS BED holding gold/silver and his notes/recipes - incl. material on the Gift/Insamiar "black plague" and the anti-sahaugin powder. Party's next objective: return to the burnt shop to open it.
- Leslie treated as Albashon's heir/inheritor; his mass-production/inventor ambition ("Leslie the Great," CEO, factory) folded into the deal for the powder's manufacture (Paul offers lab/tower/funding/proprietorship, backed by royal family).
- Monmurg = richest city in the Flanaess; Paul's uncle = richest man in it (211-212).
- "Toothless" = party nickname for the de-fanged male Yuan-ti prisoner.

ASR / name fixes:
- "5th of Whale Sun" (1) -> 5th of Wealsun; "the Flaness" -> the Flanaess; "sahuagin" -> sahaugin.

Flags: bleed-heavy; firebox exchange 8-21 tangled (10->Leslie, 11-17->Jude, 18-20->Paul); DM tag carries Paul/Leslie bleed (40-44->Paul, 23->Leslie); Paul lines on Jude tag (18-20, 207-209, 84). [out-of-band] 50-53 (OOC "brainwash this kid... hypotheticals") and 249-252 ("third Gatorade" table banter).

## Jude, Paul and Leslie Collect the Alchemy Tomes (5th Wealsun)
Speaker-tag character-lock applied. Diarizer layout: raw00=DM(00A), raw01=Leslie(03A), raw02=Jude(01A), raw03=Paul(02A). NPC: guard 01B. Bleed-heavy. 18 lines [game mechanics], 1 [out-of-band].

Canon / continuity (important):
- PAUL'S ORIGIN stated on-page (275-276): "a disfigured bastard son of the dead sister of Prince Jeon - still wealthy." Confirms Paul = disfigured, illegitimate nephew of Prince Jeon.
- PAUL'S SECRET LAB: a concealed door in his closet -> cliff-side tunnels/guard-rooms with arrow slits over the bay (old pirate-era fortification, "long forgotten") -> a hidden apartment + laboratory. New location; worldbuilding note recommended.
- Albashon's research = ~3 books, ~8 scrolls, potions in a stone box opened only by a secret master-apprentice cipher/word ONLY LESLIE knows. Lord Jamis tasked Paul with finding the anti-sahaugin powder recipe; giving the research to Lord Jamis floated and REJECTED.
- Jude recaps the shop attack (105-129): knock ~15-20 min after Paul left, master stabbed in the face + poisoned ("that black dragon, Sam[iar]"=Insamiar), Jude dragged him, found the hidden assistant (Leslie), cast wall of fire, escaped via sewers; master died of the poison not the wound.

ASR / name fixes:
- "Prince John" (275) -> Prince Jeon; "Lord Jameis" (230,234) -> Lord Jamis.
- "tensor's floating desk/disc" -> Tenser's Floating Disc; "the cantrips light" -> the Light cantrip.
- "Avenue of the Gods" (84) -> Row/Avenue of the Gods; "that black dragon, Sam, whatever" (122) -> Insamiar; "the Burbell" (88) uncertain (author to confirm); "sahuagin" -> sahaugin.

Flags: bleed-heavy; Paul lines on DM tag (280,283,289,322,391-392) reassigned to Paul; Leslie bodyguard/CEO (359-361) + fake-fire riff (385-386) reassigned to Leslie; 8-11 female-caster (10-11 could be Jude); 31 guard "what about feeding, sir?" (01B); 32/35-36 -> Jude (could be Paul); 234 mixed Jude/Paul. [out-of-band] 338 = DM "I'm going to have so much fun writing this."
