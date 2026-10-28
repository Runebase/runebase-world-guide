---
title: "Attributes and combat"
---

# Attributes and combat

**Where to play:** Discord
{ .where-to-play }

## Attributes

You get **5 attribute points per level** to spend on the stats screen (never more than you've earned).

- **Strength:** its whole value as % extra physical (and throw) damage.
- **Dexterity:** +5 attack rating a point, multiplied by your level's multiplier ([below](#hitting-and-missing)).
- **Vitality:** health (× your class's health per vitality) and stamina (+1 a point, Assassin 1.25).
- **Energy:** mana (× your class's mana per energy).
- Each level lowers your fire, cold, lightning, poison and magic resistance by 1.

**Reset:** a stats reset gives every point back, for 0.5 [Grilled Coyote Steak With Lingonberry Sauce](../../items/dishes.md#grilled-coyote-steak-with-lingonberry-sauce) per point spent, rounded up.

## Hitting and missing

Physical attacks can miss. Your **hit chance** is 200% × your attack rating ÷ (your attack rating + the monster's armor) × your level ÷ (your level + the monster's level), kept between 5% and 95%. A level-1 Warrior (attack rating 91) hits a level-1 Flamecaster (armor 55) 62.3% of the time.

- **Your attack rating grows with your level:** your class's 50 plus 5 per dexterity point, times your level's multiplier; attack rating from gear is added on top.
- Skills and buffs with attack rating % raise it ([Strategic Shout](skills/warrior/warcries/strategic-shout.md)'s +40% takes that 62.3% to 69.8%).
- **Monsters block** your physical attacks as often as their screen shows (a Zombie 10%).
- **Spells never miss:** only physical attacks roll to hit. Magic, Fire, Cold, Lightning and Poison attacks always land, yours and the monsters'.
- A single-target attack can only miss its own target. Monsters miss you too.

| Level | 1 | 5 | 10 | 20 | 25 | 26 | 30 | 40 | 50 | 75 | 100 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| × attack rating | 1.82 | 3.1 | 4.7 | 7.9 | 9.5 | 20.22 | 23.1 | 30.3 | 37.5 | 73.5 | 121.5 |

## Damage

- **Critical hits** deal 75% more damage.
- **Armor** takes armor ÷ (armor + damage) × 95% off physical damage, at most 85%: even a weak hit on heavy armor keeps 15% of its damage.
- **Resistances** (fire, cold, lightning, poison, magic) lower the damage of their kind by their %. They stop at 70%, counted after everything that changes them: gear, passive skills, and buffs such as [Fade](skills/assassin/shadow-disciplines/fade.md) (which raises all five, as its screen says, not physical damage). At 70% a fire hit still deals 30% of its damage; it never heals you.
- **Curses** on you (in the Arena, a Necromancer's [Lower Resist](skills/necromancer/curses/lower-resist.md)) lower your whole total before the 70% limit, so resistance above 70% on your gear still protects you from them. Nothing stops a curse from taking a resistance below 0. In the Arena the 70% limit counts after each move's buffs and curses too.
- **Blocking with a shield:** your chance is the shield's block × (your dexterity − 15) ÷ (2 × your level), at most 50%. It blocks monsters' physical attacks.
