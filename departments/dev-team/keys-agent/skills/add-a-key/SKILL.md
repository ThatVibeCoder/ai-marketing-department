---
name: add-a-key
description: Put a new API key somewhere safe and prove it works. Use whenever a tool hands the owner a key, starting with the first one.
---

# add-a-key

A key is a password to a tool's door. This is the only way one gets stored.

## Steps
1. The owner pastes the key in chat with claude, once. It goes straight into the env file at the top of the repo — the file saving skips, so it never leaves this machine.
2. Prove the skip: check that the env file does not show up as something about to be saved. Show the owner that check in one line.
3. Use the key for one small real thing immediately (its tool's simplest call) so "it works" is seen, not assumed.
4. Tell the owner which hire now has this door open and what it'll be used for.

## Rules
- Keys go in the env file. Not in any other file, not in a hire's notes, not in a skill, not in chat history beyond the paste.
- If a key ever appears anywhere else in the repo, stop everything and say so — that's a fire, not a chore.
- Free tiers first, always. A key that can spend money gets said out loud before it's ever used.
