# Updates

Your repo does not update itself. That's deliberate, and here's the mechanism.

## Why it doesn't auto-update

You cloned this template and filled it with your own business: your ICP, your voice, your contrarian take, your hires' memory, your whole department. From that point on, your copy and the template's copy are two different things. A real update tool (`git pull`, a merge, a rebase) cannot tell the difference between "the template changed this file" and "you changed this file." It reconciles both, and something gets overwritten. For an owner running this alone, that is a power tool pointed at your own business, so this repo does not use one.

Instead, updates arrive as fetches. You ask for one named piece, claude pulls that exact path from the public template on GitHub, and places it in your repo. Nothing pulls, nothing merges, nothing reconciles versions behind your back.

## Your own answers are never touched

Two kinds of files live here. Your identity files, `business.md` at the root and everything under `brand/`, are yours for good; a drop never writes to them, whatever you ask for. Everything else (departments, hires, skills, program days, the operator skills in `.claude/skills/`) is template material, and that is what a drop can add to or replace.

## How to see what's new

Open `CHANGELOG.md` at the root. It's written for you, not for engineers: newest first, plain words, who each change is actually for, and the exact line to say if you want it. Your `VERSION` file holds one number, the generation your repo was cloned or last checked in at. Anything in the changelog above your number is something you don't have yet.

You can also just ask: "what's new since I cloned this" or "is there anything in the template I'm missing." Claude reads `VERSION` and `CHANGELOG.md` and tells you plainly.

## How to take one thing

Say what you want in plain words: "add the payments agent from the template," "get me the latest version of the ICP day," "grab whatever's new for the newsletter team." Claude fetches that one file or folder from the public template and places it where it belongs in your repo. Nothing else moves. If you already have a file at that path, claude says so before touching anything and lets you choose: keep yours, take the new one, or see both side by side first.

## Taking nothing is a fine choice

Most of what ships to the template will not be for you. A drop for a business that sells physical products does not help a service business, and the other way around. Read the changelog, take what applies, skip the rest. There is no penalty for staying on an older version of a hire you are not using, and no requirement to ever run an update at all.
