# Project Overview
This project is an ongoing sci-fi/fantasy novel titled **"Journey of the Stone"**. 
The goal is to maintain historical fantasy tropes mixed with hard science fiction mechanics. 
All final story chapters are written in Markdown format within the `manuscript/` directory.

## Workspace Directory Structure
* `manuscript/` - Contains the latest draft of the Claude generated story.
* `worldbuilding/` - Core lore, magic systems, maps, and timeline logs.
* `characters/` - Individual character profiles, motivations, and fatal flaws.
* `transcripts/` - Plot arcs, scene-by-scene beats, and emotional pacing guides.
* `thoughts/` - Cut content, alternate scenes, and brainstormed dialogues.

## Transcript format and location
* `transcipts/transcripts.lst` - Contains a list of the transcript file entries and the subdirectories they are located in. Transcripts are listed in order.
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
