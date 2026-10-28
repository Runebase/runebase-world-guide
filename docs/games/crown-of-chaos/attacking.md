---
title: "Attacking the Crown"
---

# Attacking the Crown

**Where to play:** Discord
{ .where-to-play }

**Attack The Crown**, pick an **offensive rune** (each option shows its value in this reign) and, if you like, an **attack skill**, then attack.

- **Each attack costs one [Chaos Relic](../../items/keys-and-cards.md#chaos-relic)** (2 credits in the store; you can also **Buy [Chaos Relic](../../items/keys-and-cards.md#chaos-relic)** from the Crown of Chaos menu, and 5% of what you pay goes into the pool). Without a relic the attack button is off. A double click spends one relic once.
- **Then you wait** for the cooldown before your next attack (the bot says "Attack Cooldown"; nothing is spent). The cooldown is the Crown's 15 s, plus the Crown's [Fractured Time](skills/defensive/fractured-time.md) and Temporal Nexus, minus your [Blood Rush](skills/offensive/blood-rush.md), and **never under 3 seconds**.
- The Crown can't attack itself.

## Runes and damage

In a reign, each of the 24 runes has a value from 1 to 24 (the menus and the attack reports show it). **Every reign draws new values:** when a new Crown takes over, the 24 values are shuffled again, so a rune that was strong last reign may be weak now. The Crown has a **current defensive rune**, and every attack faces it:

- Your damage comes from how many steps your rune's value is above the Crown's rune's value (a value of 24 against 14 is 10 steps; 24 against 22 is 2): **3 damage per step**. <!-- Production's damage per step; the tests run with 50. -->
- The counting goes on past 24 and starts again at 1, so **a rune valued below the Crown's still hits**: 9 against 10 is 23 steps, the most there is, and 3 against 10 is 17.
- **The same value misses:** "The crown defended without taking damage!" The relic is still spent.
- After every attack (a hit, a miss or a dodge) the Crown's rune moves on to the next one in its list. Each public attack report shows both runes with their values.
- On top of the steps come your extra damage ([Brutal Strike](skills/offensive/brutal-strike.md), the [White-tailed Deer](../../items/dishes.md#white-tailed-deer-with-juniper-berry-demi-glace) [buff](buffs.md), [pets](../../account/pets.md#perks)), less the Crown's damage reduction (the [Blackened Tilapia](../../items/dishes.md#blackened-tilapia-with-cumin-slaw) [buff](buffs.md), pets), multiplied by the Crown's handicap. A pet's perks count only while it's awake and well cared for ([Pets](../../account/pets.md)).
- The Crown can **dodge** ([Veil of Shadows](skills/defensive/veil-of-shadows.md), pets): a dodged attack deals nothing but still costs the relic.

## Mana and attack skills

You have **1,000 mana**, and you get 10 back every round (more with [Abyssal Mana Tide](skills/offensive/abyssal-mana-tide.md)), up to 1,000. Only the attack skill you pick costs mana, once. Without enough mana, the attack goes on without the skill and costs no mana.

- **[Brutal Strike](skills/offensive/brutal-strike.md):** extra damage on the hit.
- **[Bleed](skills/offensive/bleed.md):** on a hit, the Crown bleeds for some rounds; each round's bleed damage counts as your damage. A new bleed of yours replaces your old one.
- **[Doomseed](skills/offensive/doomseed.md):** on a hit, plants a seed that detonates after its rounds (fewer with [Premature Bloom](skills/offensive/premature-bloom.md)); **[Thornburst](skills/offensive/thornburst.md)** gives a detonation a chance to make the Crown bleed too (not a detonation the Crown's Bubble absorbs). A new seed of yours replaces your old one, and its rounds start again.
- **[Robin Hood](skills/offensive/robin-hood.md):** on a damaging hit, steals a share of the pool and splits it evenly among the reign's attackers. **[Black Hood](skills/offensive/black-hood.md):** steals a share for you alone. Each steals exactly its share; the rounding remainder stays in the pool.
- **[Silence](skills/offensive/silence.md):** on a hit, the Crown can't use Resurgence, Blood Purge, Defuse or Mana Drain for the silence's duration (Bubble still works).
