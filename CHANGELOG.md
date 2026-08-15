# Changelog

What is new in this template, and what to do about it.

Your repo does not update on its own. Nothing here changes your files until you ask for it, one piece at a time. This file exists so you can see what you do not have yet and decide, on your own terms, whether you want it.

Newest first. Each entry says what changed, who it is actually for, and the exact line to say to your claude if you want to take it.

The `VERSION` file at the root holds one number: the generation your repo was cloned or last checked in at. Any entry below with a higher number than your `VERSION` is something you do not have yet.

---

## Version 1, 2026-08-15

**What's new.** This is the starting department, not a drop, there is nothing to compare it to yet. It is what a fresh clone of this template holds as of today:

- The shared brain: `business.md` and `brand/` (voice.md, icp.md, contrarian-take.md, channels.md, colors.md, typography.md, offer.md), every one of them an empty shape waiting on your own answers.
- Three departments (Marketing, Sales, IT / Systems) under `departments/`, 8 teams, 27 hires, each hire a folder with a job description and its own `skills/`.
- The skills you run yourself, in `.claude/skills/`: brain-dump-your-business (start here, it fills `business.md` and everything else builds on it), company-brain-dump, run-my-marketing-checkup, audit-my-site, ship-my-landing-page, set-up-my-code-base, make-this-a-pdf. You never memorize their names, you say what you want and claude picks.
- The lessons themselves live in the classroom, not in here. The classroom teaches the why on video, and points you at the skill that does the work.
- The update system itself: this file and `VERSION` to see what has shipped since your clone, and the github agent's add-from-template skill (`departments/it-systems/dev-team/github-agent/skills/add-from-template/SKILL.md`) to fetch one piece when you want it.
- `knowledge/` and `routines/`, empty and correct for now, they fill in as your department grows.
- `org-chart.html` at the root, the live visual of your team, generated from the real `departments/` tree.
- The security rules in `CLAUDE.md`: keys live in `.env` only, nothing secret in a page or a skill file, a code review before any save that touches pages or wiring, a security check before anything public ships.

**Who it's for.** Everyone. This is what you start with, there is nothing to fetch, you already have all of it.

**To take it.** Nothing to say. If this file is sitting in your own repo, it is already yours.

---

Future entries above this one will describe one drop at a time: small enough to read in ten seconds and decide.
