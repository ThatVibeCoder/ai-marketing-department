# How to work in this repo

This is the owner's marketing department. Before any writing or content task, read `business.md` and everything in `brand/` — that's the shared brain, and everything you make has to match it.

If a brain file is still an empty stub, stop and ask for what you need instead of guessing. Generic output written around a missing file is worse than a question.

Each department is a folder under `departments/` (marketing, sales, IT / Systems — a real company shape, one person can own each). Each team is a folder inside its department, and each hire is a folder inside its team, holding a job description and its skills. When asked to act as a hire, read that hire's file first and stay inside its edges. Finished work goes in an `output/` folder next to the hire that made it.

File new things where they belong: brand-level material in `brand/`, work product with its hire. No loose files at the root — if something has no obvious home, ask before inventing one.

## Memory — where corrections live

Three places hold memory. Each hire file and team file says so too, so you don't have to remember this rule to follow it.

- **Business-wide** (voice, who you sell to, brand facts): fix `business.md` or the right file in `brand/`. This is already the rule for content work — a voice miss gets fixed in `brand/voice.md`, not repeated per hire.
- **One hire's own habits** (specific to how THIS hire should work, not a brand fact): write it in that hire's own `Memory` section, in their `.md` file.
- **A whole team's habits** (once a team has more than one hire and they should all do something the same way): write it in that team's `Memory` section, in `team.md`.

When to write it down: the moment the owner says "always" or "remember" about something, write it right then. If the same correction happens twice without being told to remember it, write it the second time — don't wait for a third.

Skills don't get their own memory. A skill is a job a hire knows how to do, and it stays a clean set of steps so it still works if it's ever shared outside this department. Anything learned about how the owner wants that job done belongs with the hire running it, not inside the skill file.

## The org chart stays true

`org-chart.html` at the root is the visual of this department. Its data block is generated from the real `departments/` tree — never hand-edit it. Each hire's live-or-seeded state comes from the **Status:** line in that hire's own file, never from guessing. Any time a team, hire, or skill is added, renamed, or removed, regenerate the data block (reread the folders, rewrite the `const DEPT` object, update the `generated` date) before saving work to GitHub. If the owner asks to "see the team" or "update the org chart," this is the file.

## Standing security rules (every session, every build)

These bind always, not just when someone remembers to ask:
- Keys live in the `.env` file only — that exact name, a dot then env, nothing else — and any call that uses a key happens server-side, never in code a browser downloads.
- Nothing secret ever goes in a page, a skill file, or a chat message. The owner pastes a key once, into add-a-key, and never again.
- Before any save that changed pages or wiring, run the code reviewer's review-changes. Before anything public ships, run the security checker.
- A leaked key means a NEW key from the tool's own site and the old one turned off. Deleting the file is not the fix.

## The program days

When the owner names a program day ("I'm on day 1.4") — or describes a GOAL one of the days serves (the routing table in `program/README.md` maps both) — read that day's file in `program/` and run it exactly — the questions, the order, the filing map, the ending. The Skool classroom teaches the why; this repo carries the how. If no file exists for the day they name, say so plainly instead of improvising.

## Summoning a team

When the owner says "summon my [team]" for a job, read that team's `team.md` first — pre-built teams carry Summon sections that name the order hires run in. Follow the choreography, planner first when one exists, and report at each hire's handoff in plain words.
