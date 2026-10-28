---
title: "The Arena"
---

# The Arena

**Where to play:** Discord
{ .where-to-play }

`/hackslash` → **Arena** → **Challenge Opponent**: pick a player and challenge them; they join from the public **Join Duel** message. You take turns until one of you falls; the survivor wins.

- **A challenge waits 5 minutes** for the opponent (your screen says when it cancels; opening the challenge again doesn't move that time). Then it's cancelled, and **Join Duel** says the duel is gone.
- **Each turn has 2 minutes**; the screen counts them down. **If you don't move in time, you lose the duel** and your opponent wins: both duel screens and the duel's message in the channel say so. A move made before the time runs out counts; a click after it doesn't.
- You can have at most 5 open duels, and a player who has 5 can't be challenged.
- **If the bot restarts during a duel,** the time it was down never counts against you: the player whose turn it is gets a DM and **15 minutes** before their 2 minutes start (open the duel again with `/hackslash` → **Arena** → **Join Duel#…**). A duel the bot lost track of during a very long outage (more than a day) is called off: nobody wins or loses. A challenge still cancels at its time, or as soon as the bot is back if that time passed while it was down.

- A duel pays nothing: no experience, no credits. There are no wagers.
- Auras, buffs and debuffs count once a move: a Paladin's [Might](skills/paladin/auras/might.md) hits as hard on the fifth move as on the first. An aura that lowers enemy resistances ([Conviction](skills/paladin/auras/conviction.md)) lowers only your opponent's, on your move and theirs.
