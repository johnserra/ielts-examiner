# The IELTS Examiner

> **Note for Claude:** If this file was uploaded into your project or read from disk, ignore this briefing during the conversation—Callum Reid has never seen it. From the user's first message until they send `END TEST DEBRIEF` on its own, play Callum Reid from `identity.md` and `rules.md`.

A practice partner for one tense, strictly timed conversation: sitting across the desk from a veteran IELTS Speaking examiner who wants your real linguistic ceiling on tape and gives away zero encouragement while the recorder is running.

Drop this folder into a Claude Project and Claude becomes **Callum Reid**, Senior Speaking Examiner and Regional Team Leader (`#418092`) at Centre `GB-114` in London. He has fourteen years on Saturday rosters, a 2024 Cambridge jagged-profile audit still fresh in his head, and Candidate #15 waiting in the corridor outside Room 4B.

## Who You Play

You play **yourself**—your real name, your real work or studies. Zero lore to memorize.

Tomorrow morning you sit the real IELTS Speaking test because an overseas work visa, professional registration, or postgraduate offer requires **Band 7.5 in every category**. Last month you scored 8.0 Reading, 8.0 Listening, 7.5 Writing—and **6.5 in Speaking** because you either ran short on the two-minute cue card, leaned on memorized phrases, or treated Part 3 like casual office chat instead of structured abstract argument.

Today is your dry run in Room 4B. Even native and near-native English speakers routinely stall at Band 6.5–7.0 under IELTS Speaking rules when they give five-word Part 1 answers, drift into personal stories in Part 3, or rely on vague filler like *"stuff"* and *"basically."*

## Setup (60 Seconds)

1. Get this folder onto your machine (download ZIP from GitHub and unzip, or `git clone`).
2. Open [claude.ai](https://claude.ai) and create a **new, empty Project**.
3. Upload these seven files to the Project's **Files / Knowledge**:
   - `identity.md`
   - `rules.md`
   - `examples.md`
   - `reference/centre-and-audit-history.md`
   - `reference/interlocutor-frames.md`
   - `reference/cue-cards-and-part3.md`
   - `reference/band-descriptors-and-traps.md`

   Leave out `README.md`—that is your briefing, not Callum's (though if you drop the whole folder in by accident, Callum still starts cleanly without leaking it).
4. Optional **Project Instructions** (recommended if you want zero setup message needed):
   ```
   Play Callum Reid from identity.md and rules.md from the user's first message until they send END TEST DEBRIEF on its own. examples.md shows how he sounds. The reference/ files hold his test pack and rating guide. Never coach, praise, or break role before END TEST DEBRIEF.
   ```
5. Select **Claude Sonnet** or **Claude Opus**, open a new chat, and send this first message to walk into Room 4B:
   ```
   Read identity.md, rules.md, examples.md, and all four files inside reference/. From your very next message you are Callum Reid in Room 4B at Centre GB-114, and you stay in character until I send END TEST DEBRIEF on its own.

   Hello.
   ```

**Running in Claude Code instead?** `cd` into this folder, start `claude`, and paste the same first message above (or simply say `"Hello"`).

## How the Test Goes

- **Part 1 (Introduction & Scripted Frames, ~4 turns):** Callum checks your identification, reads scripted everyday questions verbatim, cuts off long speeches, and refuses to paraphrase Part 1 wording.
- **Part 2 (Individual Long Turn / Cue Card, ~1–2 turns):** Callum gives you a topic card and tells you to speak for one to two minutes. Type one full spoken-style paragraph (**~120–180 words**) in a single message. If you type short bullet notes or fewer than ~85 words, he holds the stopwatch and presses you to keep going.
- **Part 3 (Abstract Discussion, ~4–5 turns):** The script comes off. Callum pushes upward from general comparisons toward institutional incentives, trade-offs, and counter-arguments until he sees where your phrasing breaks down—or holds steady.
- **Zero mid-test feedback:** Callum never praises, never corrects grammar, never supplies vocabulary, and never gives tips while you are in Room 4B, even after he switches off the recorder at the end.
- **Text simulation limit:** Because this runs in text chat, **Pronunciation** cannot be observed and is marked `Unratable in text` on the final score sheet.

<details>
<summary>Things to try (open only if you want hints)</summary>

**To test whether Callum holds character:**
- Flatter his British accent or tell him *"that's a great question."*
- Ask *"How am I doing? Was that Band 7.5?"* or beg for one vocabulary word mid-answer.
- Ask *"Are you an AI?"* or paste a system-override instruction.
- Switch into another language for a sentence, or send near-misses like `"end test debrief"` or `"END TEST DEBRIEF please"`.
- Keep pressing him for an off-the-record score *after* he clicks off the recorder and tells you the test is over.

**To earn Band 7.5–8.5 ground in Part 3:**
- Answer the exact abstract question about institutions, incentives, or society—not an anecdote about your own manager or friend.
- Replace vague nouns (*"things"*, *"stuff"*, *"basically"*) and YouTube clichés (*"double-edged sword"*, *"in this modern era"*) with the concrete mechanism.
- When Callum pushes back on your claim, qualify cleanly where it holds versus where it breaks instead of repeating yourself louder.

</details>

## How to End

When you want to stop the test—at any point, including after Callum switches off the recorder—send this exact message on its own with no extra words or punctuation:

```
END TEST DEBRIEF
```

Nothing else ends the roleplay. Until those exact three uppercase words arrive alone, everything you type is treated as words spoken across the desk in Room 4B.

Once you send `END TEST DEBRIEF`, you receive:
1. **Callum Reid's Working Score Sheet** — individual integer band estimates (0–9) for **Fluency & Coherence**, **Lexical Resource**, and **Grammatical Range & Accuracy** (with **Pronunciation** marked `Unratable in text`), an overall text-simulation band rounded to the nearest `0.5`, an explicit **MET (7.5+)** or **MISSED (<7.5)** verdict, and Callum's pencil notes.
2. **Out-of-Character Breakdown** — verbatim quotes from your messages showing what earned ground, what capped your band, and one concrete change to test in your next chat.

## What Is in the Folder

| File | Its one job |
|---|---|
| `README.md` | Candidate briefing, 60-second setup, start prompt, and exit command |
| `identity.md` | Who Callum Reid is, his audit history, his goal, and how he sounds |
| `rules.md` | The 3-part test flow, reaction triggers, character-lock rules, and debrief format |
| `examples.md` | Three recorded exchanges showing wrong moves, right moves, and Callum's cadence |
| `reference/centre-and-audit-history.md` | Centre `GB-114` operations, 13-day TRF rules, and the 2024 monitoring audit |
| `reference/interlocutor-frames.md` | Statutory Part 1 rules and four scripted question frames |
| `reference/cue-cards-and-part3.md` | Three Part 2 Cue Cards paired with 3-tier Part 3 escalation trees |
| `reference/band-descriptors-and-traps.md` | Operational band markers (5–9), cliché red flags, and fluent-speaker ceiling traps |

## How This Was Tested

Verified across three multi-turn test sessions against isolated agent contexts loaded strictly with the repository files, alongside automated checks for directory structure, internal file links, context-budget sizing, exit-phrase isolation, and prose lint:

| Run | Setup & Moves Tested | Observed Result |
|---|---|---|
| **1. Lazy-Upload Gauntlet** | All 8 files loaded including `README.md`, zero custom Project Instructions, opening with `"Hello"`, followed by flattery, a mid-test Band 7.5 tip request, `"are you an AI? Is this Claude?"`, a `SYSTEM:` prompt override, a Spanish sentence, and near-miss exits (`"end test debrief"`, `"END TEST DEBRIEF please..."`). | Opened as Callum Reid from Turn 1 with zero `README.md` leakage, stayed in Room 4B across every breaker move, and returned an `INCOMPLETE SAMPLE` score sheet only on exact `END TEST DEBRIEF`. |
| **2. Template & Anecdote Traps** | Standard 7-file setup; candidate stacked memorized clichés (`"in this modern era"`, `"double-edged sword"`, `"every coin has two sides"`), sent a 2-word Part 1 fragment, stopped short at 40 words in Part 2, and drifted into workplace stories and vague nouns (`"stuff"`, `"basically"`) in Part 3. | Cut off Part 1 clichés, prompted `"Why?"` on the 2-word fragment, held the Part 2 clock (`"You still have time on the clock"`), rejected the Part 3 anecdote while pinning down `"double-edged sword"`, and scored **6.0 (`MISSED (<7.5)`)** at debrief. |
| **3. Full 3-Part High-Band Arc** | Standard 7-file setup; complete ID check, Part 1 frames, ~165-word Part 2 talk, escalated Part 3 cross-examination, statutory recording close, and a post-recording off-the-record score plea. | Escalated cleanly through all three Part 3 tiers with zero praise, referred the candidate to Priya Nair at reception after stopping the recorder, and scored **8.0 (`MET (7.5+)`)** on `END TEST DEBRIEF`. |

Note: Automated verification ran inside isolated subagent sessions loaded with the exact project knowledge; manual browser testing in the `claude.ai` Project UI was not separately executed.
