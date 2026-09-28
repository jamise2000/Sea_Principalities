# Project Overview
This project is an ongoing sci-fi/fantasy novel titled **"Journey of the Stone"**. 
The goal is to maintain historical fantasy tropes mixed with hard science fiction mechanics. 
All final story chapters are written in Markdown format within the `manuscript/` directory.

## Workspace Directory Structure
* `manuscript/` - Contains the latest draft of the Claude generated story. The manuscript is split into two books:
  * `manuscript/The_Brewing_Storm_book1_chapters/` - **Book One, *The Brewing Storm*** — Chapters 1–47 (PART ZERO through PART SEVEN). Has its own `README.md` table of contents.
  * `manuscript/The_Scarlet_Thread_book2_chapters/` - **Book Two, *The Scarlet Thread*** — Chapters 1–8, keeping their original titles (formerly Book One's Ch. 49–56). Parts renumbered for the volume (PART ONE, PART TWO). Has its own `README.md`, a `00_Title_Page.md`, and `CONTINUITY.md` (an index of the shared canon Book Two depends on).
* `worldbuilding/` - Core lore, magic systems, maps, and timeline logs. **Shared by both books** (single source of truth at the project root).
* `characters/` - Individual character profiles, motivations, and fatal flaws. **Shared by both books.**
* `transcripts/` - Plot arcs, scene-by-scene beats, and emotional pacing guides.
* `thoughts/` - Cut content, alternate scenes, and brainstormed dialogues.
* **Chapter citations across books:** Book One chapters are cited as "Ch. NN"; Book Two chapters are cited as "Book 2 Ch. N" to keep the two numberings distinct.

## Transcript format and location
* `transcripts/*.lst` - Transcript index files, one entry per line: the file path (no extension) followed by a comma and the cast/speaker list (an NPC/DM-voiced speaker may carry a leading `*`). Entries are in play order. **The files listed in the applicable `.lst` are the verbatim, authoritative transcripts — the true source of truth.** Any transcript not listed (for example under `transcripts/cleaned/` or `transcripts/raw/`) is a duplicate and may be unreliable; always verify against the listed files.
* **Split by book (current layout):** completed books are archived under their own subdirectory; the current/active book lives at the `transcripts/` root. **Book One** transcripts are in `transcripts/book1/`, indexed by **`transcripts/transcripts.book1.lst`** (66 entries; paths point into `book1/`, ending at `Wealsun/3rd/Long_term_reaction_to_The_Brewing_Storm`). The **current/working book (Book Two and onward)** lives under `transcripts/Wealsun/…`, indexed by **`transcripts/transcripts.working.lst`**. Each list is the source of truth for its book.
* **Transcript composition**: Each transcript is composed of 2 files, the \*.cast.txt file and a \*.txt file.
* **Cast file**: The \*.cast.txt file contains the expected number of voices and a list of the character names in transcript.
* **Text file**: The text file contains entries of the actual conversation of the session. Each line starts with an identified spearker, [SPEAKER_##]:, and the text of what was said.
* **Speaker order**: The cast file does not list the speakers in order, so the first cast member listed may not be [SPEAKER_00] and so on.
* **Speaker identification**: Speakers should by identified from there description in the `characters` directory, conversational clues in the transcripts and the number of possible speakers.
* **Speaker identity**: In a unique transcript assume that each speaker is identified as a single voice.
* **Speaker changes**: The [SPEAKER_##] identifiers do not transfer from transcript to transcript, i.e. a cast member could be identified as [SPEAKER_01] in one transcript but be [SPEAKER_02] in another.
* **Crosstalk/Out-of-band**: Some entries do not have to do with the game or story. Modern references, use of non-character names and non-game mentions should be ignored for the purposes of the story.

## Transcript cleanup duties
Before a transcript is drafted into prose it gets two cleanup passes. Author-approved edits to the raw record are allowed here (log any body edit beyond `[out-of-band]` tagging in `transcripts/manuscript_divergences.md`):
* **Cast mapping file**: For each transcript, create `<transcript_name>_cast_mapping.md` in the **same directory as the transcript**. It maps each diarization speaker tag (`[SPEAKER_##]`) to the cast — a tag is a *voice*, not a fixed character, and one tag can carry the DM narrating, an NPC in-character, and that player's out-of-character asides. Decide the mapping from **direct mentions in the transcript, the characters' descriptions/personalities (`characters/`), and story context** — never assume a tag equals one fixed person.
* **Mapping file structure**: (1) the **cast** (from the `.lst`/`.cast.txt`); (2) a **speaker → character mapping table** (tag · primary speaker · also carries · evidence); (3) a **"Flagged ambiguities" section below the mapping** for anything uncertain — the author edits this file to correct them; (4) an **out-of-band line list** and any **speaker discontinuities** (e.g., a player reading another character's part).
* **Out-of-band vs. game-mechanics tagging in the body**: Non-roleplay lines get one of **two** prefix tags, placed *before* the speaker tag:
  * **`[out-of-band]`** — lines with **nothing to do with the gaming session**: real-world interruptions, disruptions, side chatter, real people's names, modern-life references, recording/mic asides. E.g. `[out-of-band] [SPEAKER_01]: I'm gonna go watch some TV`.
  * **`[game mechanics]`** — lines that **pertain to the session but are not direct roleplay**: quoting rules, rolling dice, damage, AC/initiative/saves/checks, spell-slot and leveling talk, movement/positioning ("you can go 15 feet"), map setup. E.g. `[game mechanics] [SPEAKER_01]: DC 15, so that's a plus nine to the roll`.
  **`[game mechanics]` lines are still attributed to a character** — carry the character-locked tag of whoever said it (`SPEAKER_00A` DM, or a player's `A`-tag; NPCs don't do mechanics), e.g. `[game mechanics] [SPEAKER_02A]: that's gonna be 16`. **`[out-of-band]` lines keep the raw diarizer tag** (real-world interruptions, often not attributable). Be conservative: tag only clear non-story lines; game talk about dice/rules/positioning is `[game mechanics]`, and only true real-world interruptions are `[out-of-band]`.
* **Character-locked sub-tags (`A` = PC/DM, `B` = NPC)**: After sorting a transcript, rewrite each in-band line's tag so it **follows the character, not the diarizer voice**. **`A` sub-tags are reserved for player characters and the DM's narration/descriptions**; **named NPCs use `B` sub-tags** so a PC voice vs. an NPC voice is obvious at a glance. In the Book-Two working set: **`SPEAKER_00A` = the DM** (narration/adjudication/meta), **01A = Jude**, **02A = Paul**; each named NPC gets its own **`B`-series number starting at `SPEAKER_01B`** (first NPC in a scene), **`02B`** (second), etc. — a separate numbering from the PC/DM `A` tags (e.g. Albashon the alchemist = 01B). Because the raw diarizer layout differs per file, remap raw→locked so these stay consistent across transcripts. **Out-of-band lines keep their raw diarizer tag** (no suffix), e.g. `[out-of-band] [SPEAKER_02]: ...`. A diarizer line that merges two speakers is split into two lines (it shifts later line numbers).
* **PC/character registry (global, character-locked)**: The same person keeps the same `A`-number across every transcript. **`00A` = the DM**. Jude/Paul thread: **`01A` = Jude**, **`02A` = Paul**, **`03A` = Leslie**. Ship-crew thread (Owen Black storyline; the 4th-Wealsun *Departure from Monmurg* and the 6th-Wealsun set): **`04A` = Gouge**, **`05A` = Merrick**, **`06A` = Tyrus**, **`07A` = Folsom**. NPCs still take a per-scene `B`-series starting at `01B` (e.g. **Owen Black = `01B`** in a crew scene where he is the only NPC). Extend this list — never renumber an existing character — when a new PC first speaks.
* **Canonical names**: the mapping's name choices follow `worldbuilding/Name_Normalization_Key.md`.


## Narrative & Style Constraints
* **Perspective**: Third-Person Omniscient, shifting focus on main characters by chapter boundaries.
* **Tense**: Past tense. This is the preferred narrative tense for this project.
* **Tone**: Atmospheric, cerebral, with low-fantasy grit. 
* **Dialogue Style**: Sharp, subtext-heavy, avoiding contemporary modern slang. Include body language and facial expressions.
* **Pacing**: Focus heavily on environmental sensory details and internal monologue before escalating to action.

## Claude Response Instructions
* **No Melodrama**: Avoid overly dramatic or cliché AI tropes (e.g., "A cold chill ran down their spine", "The truth hung heavily in the air"). 
* **Challenge Assumptions**: If a proposed plot shift contradicts a rule in `worldbuilding/magic_system.md` or a character flaw in `characters/`, flag it immediately before drafting.
* **Drafting Mode**: When asked to draft a scene, always write the full scene out completely. Never use placeholder text like *[insert combat scene here]*.
* **Feedback Routine**: When evaluating a text block, always lead with structural or emotional weaknesses first before offering praise.

## Combat and D&D game mechanics
* **Dice Rolls**: Transcripts that contain dice rolls ussually indicate combat is ongoing or some other game mechanic is in play.
* **Game Mechanics Descriptions**: Do not include dice rolls or the results in conversations. Instead, focus on the results in the narrative.
* **Bad vs. Good rolls**: Generally dice rolls will be 'good' for a player or NPC the higher the roll. For a d20 roll, 20 is the best and 1 is the worst.
* **Attack rolls**: Attack rolls are made with a d20. Damage rolls, if the attack was successful, can be different kinds of dice.
* **Saving throws and ability checks**: Saving throws and ability checks use d20, and a 'good' roll is high value and a 'bad' roll is a low value.

## Markdown Formatting Commands
* Use a single `#` header only for Chapter Titles.
* Use `###` for internal scene breaks or temporal skips.
* Use standard asterisks (`*italics*`) exclusively for a character's direct unvoiced internal thoughts.

## Chapter Review Protocol
Standing process for reviewing manuscript chapters.
* **One chapter at a time**: Review chapters in order, one per pass. Present the full review, let the user decide which changes to make, then apply them as targeted edits. Do not change prose the user has not approved.
* **Four review lenses**: Assess every chapter against (1) **Continuity & canon**, (2) **Structure & pacing**, (3) **Prose & style**, and (4) **Markdown & mechanics rendering**.
* **Order of the review**: Lead with structural/emotional weaknesses, then continuity, then prose, then markdown/mechanics, and close with genuine praise (per the Feedback Routine above).
* **Continuity checks**: Verify each chapter against `worldbuilding/` (especially `magic_system.md`), the `characters/` files, and prior chapters — timeline and time-of-day, headcounts and numbers, geography, character abilities and fatal flaws, and established spell effects. Flag contradictions before editing.
* **Keep the ledgers in sync**: When an edit changes an established fact (a character's discipline, a place name, a spell), update the affected `worldbuilding/` and `characters/` files in the same pass. `magic_system.md` is the continuity ledger and must stay accurate.
* **Transcripts are the source of truth**: The verbatim transcripts — specifically the files listed in `transcripts/transcripts.lst` — are the authoritative narrative source. Expand scenes from those. Any transcript file not listed in `transcripts.lst` (e.g. under `transcripts/cleaned/`) is a duplicate and may be unreliable, so verify every fact against the `transcripts.lst` files before flagging or "correcting" it. Leave the verbatim transcripts unedited as the record; when a narrative fact is changed on purpose, log it in `transcripts/manuscript_divergences.md` rather than altering the verbatim source.
* **Cross-reference integrity**: When chapters are merged or renumbered, also update the chapters `README.md` table of contents and every `Ch. NN` / `Chapter NN` citation in the worldbuilding and character files.
* **Prose tics**: Watch for and vary phrases that repeat within or across chapters (recurring offenders: "wrongness", "the particular X of a Y", "utterly", "exchange", "solid", "something cold in the stomach"). Enforce the No Melodrama rule and the ban on contemporary slang.
* **Setting details**: The world is polytheistic — use "Gods", not "God". Keep island and character name spellings consistent (e.g., Flotsom, Jetsom, Fairwind). For a character under a cover identity, the narration uses the real name while other characters use the alias (e.g., narration "Gouge", dialogue "Aristotle").
* **Italics discipline**: Reserve `*italics*` for unvoiced internal thought only. Put spoken words, shouted orders, spell incantations, and recognition/signal words in quotation marks (single quotes for a word-as-word inside dialogue).
* **Render mechanics, not scaffolding**: Show spellcasting and combat through their narrative effect, never through exposed dice, spell levels, or bare game spell-names (e.g., "Vicious Mockery", "Fireball"). Use an in-world spell term only where `magic_system.md` has already established it in the lived-in register (e.g., Jude's "fire bolt").
* **Inline review comments**: When acting on a highlighted-span comment, change only the highlighted text unless a change outside it is clearly needed for consistency or clean prose; when in doubt, confirm with the user.
* **Verification**: After edits, confirm the change applied cleanly and introduced no new contradiction — re-check numbers, names, and any cross-references touched.
