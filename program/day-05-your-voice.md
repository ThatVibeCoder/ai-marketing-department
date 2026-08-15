# Day 5 - Build Your Voice

**Runs when the owner says:** "I'm on day 5", "build my voice", or anything that means teaching claude how they actually sound.

**The job:** derive how the owner really writes and talks from REAL samples, never from adjectives, then REWRITE `brand/voice.md` with executable rules. The test for every rule: does it change how a sentence gets written? "Friendly and authentic" fails that test. "Never more than one comma, swears occasionally, opens with the point" passes.

## Collect the raw material first
1. Ask for 3 to 5 things they actually wrote where they sound like themselves. Texts to a friend about work beat polished posts. Emails they dashed off beat anything they labored over.
2. Then one fresh sample: have them Wispr-ramble for two minutes about something in their business they care about. Raw speech is the truest sample there is.
3. If they have published content, take one piece, but weight it least; published stuff is usually them performing.
4. Then the negative space: "Send me two or three pieces of marketing from your industry that make you CRINGE." What they'd never sound like defines the banned list better than guessing does.

## Derive the rules
Study the samples for patterns, then write 5 to 8 rules, each one concrete enough to follow:
- Sentence length and rhythm: short and punchy, or long and rolling?
- Words and phrases they actually repeat: those are theirs, keep them.
- How they open (straight to the point? a story?) and how they close.
- Punctuation habits, contractions, casual grammar they use on purpose.
- **The banned list**: words they'd never say, plus the generic marketing words that would instantly not sound like them, derived from the cringe samples, not invented.
- **The dial**: where the voice runs looser and tighter, text-to-a-friend for a post, one notch straighter for a sales page. Same voice, two settings.
Kill any rule that's an adjective in disguise. If it doesn't change the next sentence someone writes, it's not a rule.

## Prove it before filing
Write each of three test sentences TWICE, once in the derived voice, once competent-but-generic, unlabeled: a post opener, a reply to a customer, one line of page copy. They pick which is theirs. If they can't tell, the rules aren't sharp yet. Adjust the rules from their reactions, not from taste.

## Rewrite brand/voice.md
Replace the whole stub with their answers under four headings: **The Sound** (one line: how they actually write and talk, in plain terms, not adjectives), **The Rules** (the 5 to 8 concrete rules derived above, including the dial), **The Banned List** (the words and phrases derived from the cringe samples), **Self-Check** (the standing test: "read it aloud, a stumble means rewrite"). Note at the bottom: every future correction the owner makes about sounding wrong updates THIS file, not just the draft that missed.

## The ending, always
Read the one-line sound back. If samples were too thin to derive real rules, write the rules you COULD derive, add "more voice samples" to business.md's Still to answer list (same mechanic as Day 1), and note in voice.md which rules are provisional. Save to GitHub (github agent's save-work skill, `departments/it-systems/dev-team/github-agent/skills/save-work/`). From this day forward, every writing hire reads this file first, which means from today, corrections compound instead of repeating.

## Done when
`brand/voice.md` holds all four headings filled with rules a stranger could follow and produce something that sounds like the owner, the test sentences passed their judgment, no stub text survives, and it's saved.
