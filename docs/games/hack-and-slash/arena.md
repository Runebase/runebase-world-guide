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
- Auras, buffs and debuffs count once a move: a <span class="gi-m">![](../../assets/icons/class/paladin.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Paladin](classes/paladin.md)</span>'s <span class="gi-m">![](../../assets/icons/skill/paladin/might.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Might](skills/paladin/auras/might.md)</span> hits as hard on the fifth move as on the first. An aura that lowers enemy resistances (<span class="gi-m">![](../../assets/icons/skill/paladin/conviction.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Conviction](skills/paladin/auras/conviction.md)</span>) lowers only your opponent's, on your move and theirs, and only their magical resistances (fire, cold, lightning, poison and magic), like the <span class="gi-m">![](../../assets/icons/skill/necromancer/lower-resist.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Lower Resist](skills/necromancer/curses/lower-resist.md)</span> curse.
- Your gear does in a duel what it does against monsters ([item bonuses](gear-and-crafting.md#item-bonuses)). <span class="gi-m">![](../../assets/icons/skill/paladin/conversion.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Conversion](skills/paladin/battle-skills/conversion.md)</span>, the skill's or your gear's, never converts your opponent, as in Diablo II: the hit deals its damage and they fight on; it can convert one of their minions (a golem, a summon), which then fights for you. Gear's chance to make a hit bleed works on your opponent and their minions too: a physical hit that lands may make them bleed like the <span class="gi-m">![](../../assets/icons/class/warrior.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Warrior](classes/warrior.md)</span>'s <span class="gi-m">![](../../assets/icons/skill/warrior/wound.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Wound](skills/warrior/combat-skills/wound.md)</span> at rank 1.
