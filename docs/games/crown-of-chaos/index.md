---
title: "Crown of Chaos"
---

# Crown of Chaos

**Where to play:** Discord
{ .where-to-play }

![Crown of Chaos](../../assets/icons/header/crown-of-chaos.webp){ .gi .gi-picture width="240" height="240" loading="lazy" }

One player in the realm holds **the Crown**. The Crown earns a point every minute it holds on; everyone else spends **[Chaos Relics](../../items/keys-and-cards.md#chaos-relic)** to attack it. When the Crown's health reaches 0, the reign ends: the old Crown is paid the realm's **Crown pool** in credits, a RUNES reward and experience, and the next Crown is **drawn from the attackers, weighted by their points**.

**Where:** `/start` → **Activities** → **Crown Of Chaos**. The menu shows the Crown, its health, the pool ("Accumulated Crown Tax", also on the attack screen and in the store), your buffs, and the buttons to attack, pick runes, learn skills and eat buffs. The Crown also sees its own skills there.

## How a reign works

- A new Crown starts with its full health and a **seizure bubble** of 30 minutes: nobody can attack until it runs out, or until the new Crown removes it (**Remove Bubble**). <!-- Production's length; the tests run with 1 minute. --> Attacks against a bubble spend nothing.
- Every minute (**a round**) the Crown gets 1 point, regenerates a little, and bleeds and seeds on it run ([the round](round-and-reign.md#the-round-every-minute)).
- The longer a Crown holds on, the more damage it takes (the **handicap**: [the round](round-and-reign.md#the-round-every-minute)).
- The reign ends when an attack or a round brings the Crown's health to 0, or when the Crown leaves the server.
- A restart of the bot keeps the reign as it was: the Crown and its role, its bleeds, bubble and silence, the attackers' mana and cooldowns.

The Crown's numbers before any skills, buildings, pets and buffs:

| Before skills, buildings, pets and buffs | Value |
|---|---|
| The Crown's maximum health | 1,000 |
| Regeneration | 1 health every 5 points |
| Cooldown on each attacker after an attack | 15 s |
| Dodge | 0% |
| Resurgence | 3% of the maximum health a round for 10 rounds; cooldown 1 hour |
| Blood Purge cooldown | 20 minutes |
| Defuse cooldown | 15 minutes |
| Mana Drain | 10% of the attacker's maximum mana a hit, for 5 minutes; cooldown 45 minutes |
| Bubble | 5 minutes; cooldown 1 hour |
| Tax pile on a hit | 5% chance, 1% of the pool |
| Tax pile on a round | 10% chance, 3% of the pool |
| An attacker's mana | 1,000, +10 a round |

## In this section

| Page | What you'll find |
|---|---|
| [Attacking the Crown](attacking.md) | [Chaos Relics](../../items/keys-and-cards.md#chaos-relic), cooldowns, runes and damage, mana and attack skills |
| [Holding the Crown](holding-the-crown.md) | the Crown's own skills, defensive runes, buildings |
| [Skills](skills/index.md) | skill points and resets, a page per skill |
| [Buffs](buffs.md) | the two Crown of Chaos dishes and their charges |
| [The round and the reign](round-and-reign.md) | the minute round, points, the end of a reign, the pool |
| [The weekly ladder](weekly-ladder.md) | the weekly score, the winners role, the RUNES payout |

## Quests

An attack that completes the **Damage Dealt** [quest](../../account/quests.md#every-quest) pays its experience (25) to the attacker, and a round that completes the Crown's **Points Earned** quest pays the Crown its experience (65), on top of anything else.

## Tips

- Watch the attack reports: they show the Crown's rune and its value, so you can pick the rune with the most steps above it (the one valued just below the Crown's).
- Bleeds and seeds keep earning you points every round; Blood Purge and Defuse are the Crown's answers.
- As the Crown, cycle several defensive runes so attackers can't read your next one, and save Bubble and Resurgence for heavy attacks.
- Keep your mana for the skill that matters: only the skill you pick costs mana.
