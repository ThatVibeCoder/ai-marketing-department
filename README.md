# Your Marketing Department

This is your company's marketing department, built as files instead of headcount. Claude reads and writes these files to actually run the work.

## How this works

You don't build this alone. Open claude in this folder and talk to it the way you'd talk to a new hire. Out loud is fine, that's what Wispr Flow is for. Claude reads the files here for context before it does anything, and it writes back into them as the department grows.

Before touching anything, claude reads `business.md` and everything in `brand/` first. That's the shared brain every department works from. If you're claude reading this right now, same rule applies to you.

## The hierarchy, in five lines

- This repo is your whole marketing department. `business.md` and `brand/` are the shared brain everyone works from.
- `departments/` holds the divisions of the company: marketing, sales, IT / Systems.
- Inside each department, every team is a folder: content-team, dev-team, website-team.
- Inside each team, every hire is a folder with one file describing its one job.
- Each hire has `skills/`, the things it knows how to do on command, and `program/` holds the classroom days claude can run for you.

## One rule

Never edit structure you don't understand yet. The classroom builds it with you, day by day.

## The honest fine print
This template teaches a way of working. It doesn't run your business for you, and it can't guarantee anything about your accounts, your keys, your platforms, or your results. You own those. The security habits built in here (the env file, the sweeps, the checks) reduce risk; nothing eliminates it. When something involves money, credentials, or other people's data, slow down and check it yourself. That's true with this repo and without it.
