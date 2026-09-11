# The Brewing Storm — Book One
## Proofreader's Correction List (Uncorrected Page Proof)

**Status: SIGNED OFF — items 1–4 applied.** The author approved items 1–4; all four are implemented in the chapter files and the proof PDF has been regenerated. The two continuity queries (A, B) were deferred to the full editorial review. Final verification passed: 0 straight quotes remain, curly opening/closing marks balance exactly (1,945 each), all three ellipses are the single "…" glyph, "Onwallian" and "camaraderie" are consistent, and the 304-page PDF compiles clean. *(Two conversion artifacts caught and fixed during sign-off: interrupted-dialogue dashes `word—"` and one italic-adjacent quote had smart-quoted to the wrong direction; both corrected.)*

**Method:** Full read of all 48 chapters, plus an automated scan for doubled words, double spaces, doubled articles, "could of," unbalanced dialogue quotes, spacing around punctuation, and common misspellings. The manuscript is exceptionally clean — the automated scan returned **zero** mechanical defects (no typos, no doubled words, no unbalanced quotes, em-dashes all proper). The items below are the complete set of real findings.

---

## Editorial Review — Second Pass (after the full four-lens review of Ch. 1–47)

**Status: manuscript CLEAN; proof regenerated.** Following the chapter-by-chapter editorial review, the automated proofread scan was re-run over the current 47-chapter Book One and returned **zero** defects: no residual straight quotes, no ASCII/spaced ellipses, curly opening/closing marks balanced, no unbalanced paragraphs, no doubled words, no double spaces, no "could/should/would of," no space-before-punctuation. Every variant-prone name resolves to a single spelling.

*Note on numbering:* since the first proofread, the former Ch. 29 was merged into Ch. 28 and the former Ch. 38–39 merged into one, so Book One is now **47 chapters**. The first-pass items above reference the older numbering (e.g., the old "Ch. 45 Cider" is now **Ch. 44**; old "Ch. 48 Confession" is now **Ch. 47**). All first-pass items (1–4) remain applied.

**Consistency corrections made and verified during the review:**

- **Island names** standardized to **Flotsom** / **Jetsom** (stray "Flotsam"/"Floatsam"/"Jetsam" fixed in `Fairwind.md`, `The_Sea_Principalities.md`, `The_Rise_of_the_Sea_Principalities.md`, `manuscript_divergences.md`).
- **Creature name** standardized to **turtle dragon** (the hyphenated "dragon-turtle" in Ch. 43 and spaced "dragon turtle" in Ch. 3, `Jeon.md`, `The_Sea_Principalities.md` all corrected). "Dragon Isles" (place) left intact.
- **Powder-makers** renamed **Fhoraxians → Feiraxians** across `The_Anti-Sahaugin_Powder.md`, `magic_system.md`, and Book 2 Ch. 8.
- **Ch. 44:** "the power of Baywin" → **Gloin Baywin, Plar of Salinmoor** (resolves old query **B** below); "three hundred lost comrades" → "two hundred" (matches the ~200 corsair losses from a 250-Marine force).
- **Ch. 47:** the Keoland king slain at the **Siege of Westkeep** corrected from "Lucian the Fourth" → **Tavish III** (per `The_Sea_Principalities.md`).
- **Marine count** reconciled book-wide: **250 embarked**, ~**200 aboard and lost** with the corsair, ~50 ashore.

**Ledgers updated in the same passes:** new `worldbuilding/The_Sahaugin.md` (four-hour-ashore rule); `Merrick.md` (ranger spellcasting — "magic of reading the world"; Nado's death-by-sahaugin rumor); `Folsom.md` (green song-stone; medium height); `Gouge.md` / Ch. 12 (Assassin's Guild razing reconciled — Jude present, Jamis's order); `magic_system.md` (homunculus is Paul's alone, Magic Missile now cast on-page, Tenser's Floating Disk, Folsom's song-stone); `Owen_Black.md` (Owen/Gouge history direction corrected); `Guide_to_Salinmoor.md` (Appleyard, Turtle/Lizard Island).

**Query status:** old query **B (Baywin)** is now **RESOLVED**. Old query **A (Sacnon vs. Sconforth, the Toli prince's name — cross-book)** remains **OPEN**, to be settled when Book Two is reviewed.

**Proof regenerated & final verification (this pass):** 47 chapters, **299 pages**, trim confirmed **432 × 648 pts** (6×9), **0 LaTeX errors**. Author byline set to **James A. Edwards** (recorded in `About_the_author.md`; the manuscript title page previously carried none). Text: curly quotes balance exactly (**1,885** open / 1,885 close), **0** residual straight quotes, **0** ASCII/spaced ellipses, **0** unbalanced paragraphs. Title page, TOC, part dividers, chapter openers, running heads, and the Ch. 44 verse (song set with bold section labels) all render correctly. Proof at `proofs/The_Brewing_Storm_Book1_page_proofs.pdf`.

---

### 1. Typography — straight quotes → typographic (curly) quotes  *(global)*

The manuscript uses straight quotes and apostrophes throughout: **3,890** straight double-quotes (`"`) and **2,329** straight apostrophes (`'`), with zero curly quotes anywhere. A printed book uses typographic quotation marks (" " ' '). This is a single global conversion, applied carefully so that leading apostrophes in elisions read as ' (e.g., *'Course*, *'em*, *'tis*), not '.

- **Recommendation:** Apply globally at implementation. (The current proof deliberately shows straight quotes, faithful to the source; the corrected proof will show curly.)

### 2. Ellipsis style — inconsistent (3 instances, 2 styles)

Three ellipses appear in the book, in two different styles, with no single house style:

- **Ch. 12** (*Masks and Measures*): "I know what a homunculus is **. . .** a myth" — spaced periods.
- **Ch. 45** (*Cider at the Barracks*): "for your entertainment, I bring you**...** Folsom!" — closed ASCII dots.
- **Ch. 48** (*Confession in the Foreign District*): "**That's...** not good," Tyrus said — closed ASCII dots.

- **Recommendation:** Pick one house style and apply to all three. Options: (a) typographic ellipsis "…"; (b) spaced periods ". . ." throughout; (c) closed "..." throughout. My suggestion: the single-glyph "…" for a clean printed look.

### 3. Spelling consistency — "Onwalian" vs "Onwallian"

The demonym for Onwal is spelled two ways:

- **Ch. 1** (*The Envoy from Idee*): "the **Onwalian** trader" — one *l*.
- **Ch. 43** (*What Gouge Told Jamis*): "The strange **Onwallian** ship" — two *l*'s.

(The place-name root "Onwal" is consistent everywhere; only the adjective disagrees.)

- **Recommendation:** Standardize to one. Ch. 43 was revised more recently to "Onwallian"; if that's the intended form, change Ch. 1 to match — otherwise change Ch. 43 to "Onwalian." **Author's pick.**

### 4. Spelling/usage — "comradery"

- **Ch. 43** (*What Gouge Told Jamis*): "the undeniable draw of **comradery** and revelry."

"Comradery" is an accepted informal variant, but "**camaraderie**" is the conventional printed spelling.

- **Recommendation:** Change to "camaraderie" unless the informal register is intended. **Author's pick.**

---

### Continuity queries — beyond proof scope, flagged for the full review

These are not proof-level typos; they are name/consistency questions better settled in the complete editorial review. Listed here so they are not lost.

- **A. The Toli prince's name — cross-book conflict.** Book One names the ruling Prince of Port Toli **"Sacnon"** (Ch. 9, 11, 13: "Prince Sacnon," "Sacnon Toli"). Book Two (Ch. 7, *What Paul Knew of the Toli*) names him **"Sconforth."** One of the two is wrong, or they are different people. Needs reconciling across both books. *(Note: "Cain Toli," the artifact-holding adventurer with the* Sea Ghost*, is a separate character and is consistent.)*
- **B. "the power of Baywin" vs "the power of Westkeep."** Ch. 45 (Owen's drunk tale) names "a soldier they called **the power of Baywin**." The worldbuilding ledger (`magic_system.md`) refers to "**the power of Westkeep**," who holds the northern reach along the Hool. If these are the same figure, the names must agree; if distinct, no change needed. Owen is an unreliable narrator here, so this may be intentional — **author to confirm.**

---

### Sign-off

Nothing applied. On your marks I will: implement the approved corrections as targeted edits, keep the worldbuilding/character ledgers in sync where a name changes, regenerate the 6×9 proof PDF, and run the final sign-off check before "sending to the printer."
