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
* `transcipts/transcripts.lst` - Contains a list of the transcript file entries and the subdirectories they are located in. Transcripts are listed in order. **The files listed in `transcripts.lst` are the verbatim, authoritative transcripts — the true source of truth.** Any transcript file NOT listed in `transcripts.lst` (for example, anything under `transcripts/cleaned/`) is a duplicate and may be unreliable; always verify against the `transcripts.lst` files.
* **Split by book:** the root `transcripts/transcripts.lst` now lists **Book One** only (ending at `Wealsun/3rd/Long_term_reaction_to_The_Brewing_Storm`). The **Book Two** transcripts live under `transcripts/book2/` with their own authoritative list, `transcripts/book2/transcripts.lst` (paths relative to `transcripts/book2/`). Each book's `.lst` is the source of truth for that book.
* **Transcript composition**: Each transcript is composed of 2 files, the \*.cast.txt file and a \*.txt file.
* **Cast file**: The \*.cast.txt file contains the expected number of voices and a list of the character names in transcript.
* **Text file**: The text file contains entries of the actual conversation of the session. Each line starts with an identified spearker, [SPEAKER_##]:, and the text of what was said.
* **Speaker order**: The cast file does not list the speakers in order, so the first cast member listed may not be [SPEAKER_00] and so on.
* **Speaker identification**: Speakers should by identified from there description in the `characters` directory, conversational clues in the transcripts and the number of possible speakers.
* **Speaker identity**: In a unique transcript assume that each speaker is identified as a single voice.
* **Speaker changes**: The [SPEAKER_##] identifiers do not transfer from transcript to transcript, i.e. a cast member could be identified as [SPEAKER_01] in one transcript but be [SPEAKER_02] in another.
* **Crosstalk/Out-of-band**: Some entries do not have to do with the game or story. Modern references, use of non-character names and non-game mentions should be ignored for the purposes of the story.


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
