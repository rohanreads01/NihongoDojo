# I Built My Own Japanese-Learning App

Last winter a friend invited me on a weekend trip with a couple of his buddies. One of them religiously spent 20-30 mins daily on Duolingo learning Arabic—phone in hand, answering multiple-choice questions even from the motel bathroom. (You could hear the chime through the door.)

The dedication was infectious. I really got motivated to join in, not Arabic of course, my language of chose, no points for guessing was Japanese. 

## Where the Mainstream Tools Fell Short

Thirty days into my own Duolingo streak I realized something was off. The app was great for **phrases**, less so for the **system** behind them. It felt like memorizing a single dance routine instead of learning the full dance form.

I spent nights **Googling, Reddit-scrolling, YouTube-binging, ChatGPT-questioning**. The consensus: Duolingo lacked both *structure* and *context*.

- **Structure**: a clear path from building blocks of the language to usable sentence.
- **Context**: real sentences you can see, hear, and reuse.

For me Tofugu’s guides and WaniKani fixed the structure gap. Core-6000 word lists and *Minna no Nihongo* tackled context—yet everything lived in different tabs. Switching tools every ten minutes shattered my flow.

## Decision: Build the Tool I Wanted to Use

I’m not a software engineer—my coding résumé is a bit of Python from an ed-tech stint—but GPT-4 can write and debug code if you feed it precise prompts. That closed the skills gap enough to try.

I also treated the project as a **mini product-development lab**:

| Step | “Learner” voice | PM voice |
| --- | --- | --- |
| Spot the pain | “Why am I juggling six tabs to learn one verb?” | Map the journey, note drop-offs |
| Define success | “Can this guide a beginner to solid basics?” | Re-use proven methods, don’t reinvent the wheel |
| Scope the MVP | “Ship something tiny that works.” | Prioritise the loop; park nice-to-haves |

The loop I cared about was simple:

**Learn something → review it → learn the next thing → review again.**

along with over all progress. 

## The Metrics That Keep Us Honest

**Focus metric**

| Name | What it means | Why it matters |
| --- | --- | --- |
| **Weekly Productive Learners (WPL)** | In any rolling 7-day window, users who finish **at least one Learn session and one Review session** | Counts people who are both learning *and* revising—healthy, repeat use of the core loop. If WAPL climbs, we’re winning on both acquisition *and* retention. |

**Level-1 (L1) checks**

| Metric | Plain-English test |
| --- | --- |
| **7-day retention of WAPL** | Do last week’s engaged learners come back this week? |
| **Median learning velocity** | How many checkpoints does a typical learner clear each week? |
| **Review accuracy rate** | Are reviews mostly right answers, not lucky taps? |

Together they make sure growth isn’t hiding churn, that people are truly progressing, and that nobody is speed-running without understanding.

**But WPL isn’t perfect.**

It treats a single-card dabble the same as a 50-card grind, so effort levels get blurred. And because it only looks seven days back, a learner can vanish in week two while the metric still looks healthy.

**Reality check:** I’m not a full product owner, never have been—WPL is simply the best-guess yard-stick for v0. As soon as real usage data lands we’ll stress-test it and swap in a better signal if one emerges. Until then it’s all theory and optimism…fingers crossed we’ll turn it into hard evidence soon.

## The App in Its MVP form

- **Step-by-step roadmap:** A simple checklist walks you from the basics (kana) to everyday kanji and vocabulary, so you never wonder “what should I learn next?”
- **Real-life examples:** Each new word comes with three sample sentences you can read, listen to, and copy—practical use, not random flashcards.
- **Instant pronunciation help:** Tap any word or sentence to hear it spoken aloud, then echo it back for quick speaking practice.
- **Clutter-free design:** Clean screens, and zero flashy game tricks—just you and the language.
- **Completely free:** No paywalls, no upsells—and the code’s open if you’re curious.

## Credit where credit is due

- **The Ultimate WaniKani Deck (All 60 Levels, Updated Mnemonics)** – An Anki deck.
    
    I was able to extract the textual information from this deck. The Kanji, levels, and mnemonics were sourced from here. However, I could not extract the audio/sound files.
    
- **A list of 6000 frequently used Japanese words with audio files** – Found attached to a Reddit post linked here:
    
    [Reddit Link](https://www.reddit.com/r/LearnJapanese/comments/s2iop/comment/c4aju68/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
    
- **Wallpapers** – Many of the wallpapers used are from Freepik.
- **Tofugu's "Learn Japanese" blog** – Especially their **Learn Hiragana** and **Learn Katakana** guides.

These are the main resources I used to build the tool.

## Takeaways

- **AI tools close the skill gap.** Thanks to ChatGPT, someone like me—who’s not a pro coder—can still spin up working code once I give it clear instructions.
- **Start tiny and focused.** A small, no-frills first version beats an endless feature wish-list; getting it into people’s hands early gives real feedback instead of guesses.
- **Track real progress, not vanity stats.** Good metrics show where learning stalls—something a simple “streak” counter can easily hide.

## What’s Next

The alpha build is in the hands of a small group of early learners. Their activity and feedback will steer the next sprints—features ship only when the data says they solve real pain.


[Full build updates week by week](https://www.notion.so/Build-Journey-Updates-1e5f3f26c58d80baba33db0cadafc508?pvs=21) 

*Thanks for reading; I’m off to learn with the tool I wanted all along.*
