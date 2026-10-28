---
title: Crown of Chaos
permalink: /crown-of-chaos/
---

[← All pages]({{ '/' | relative_url }})

# Crown of Chaos

One player in the realm holds **the Crown**. The Crown earns a point every minute it holds on; everyone else spends **Chaos Relics** to attack it. When the Crown's health reaches 0, the reign ends: the old Crown is paid the realm's **Crown pool** in credits, a RUNES reward and experience, and the next Crown is **drawn from the attackers, weighted by their points**.

**Where:** `/start` → **Activities** → **Crown Of Chaos**. The menu shows the Crown, its health, the pool ("Accumulated Crown Tax", also on the attack screen and in the store), your buffs, and the buttons to attack, pick runes, learn skills and eat buffs. The Crown also sees its own skills there.

## How a reign works

- A new Crown starts with its full health and a **seizure bubble** of 30 minutes: nobody can attack until it runs out, or until the new Crown removes it (**Remove Bubble**). <!-- Production's length; the tests run with 1 minute. --> Attacks against a bubble spend nothing.
- Every minute (**a round**) the Crown gets 1 point, regenerates a little, and bleeds and seeds on it run (below).
- The longer a Crown holds on, the more damage it takes (the **handicap**, below).
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



## Attacking the Crown

**Attack The Crown**, pick an **offensive rune** (each option shows its value in this reign) and, if you like, an **attack skill**, then attack.

- **Each attack costs one Chaos Relic** (2 credits in the store; you can also **Buy Chaos Relic** from the Crown of Chaos menu, and 5% of what you pay goes into the pool). Without a relic the attack button is off. A double click spends one relic once.
- **Then you wait** for the cooldown before your next attack (the bot says "Attack Cooldown"; nothing is spent). The cooldown is the Crown's 15 s, plus the Crown's Fractured Time and Temporal Nexus, minus your Blood Rush, and **never under 3 seconds**.
- The Crown can't attack itself.

### Runes and damage

In a reign, each of the 24 runes has a value from 1 to 24 (the menus and the attack reports show it). **Every reign draws new values:** when a new Crown takes over, the 24 values are shuffled again, so a rune that was strong last reign may be weak now. The Crown has a **current defensive rune**, and every attack faces it:

- Your damage comes from how many steps your rune's value is above the Crown's rune's value (a value of 24 against 14 is 10 steps; 24 against 22 is 2): **3 damage per step**. <!-- Production's damage per step; the tests run with 50. -->
- The counting goes on past 24 and starts again at 1, so **a rune valued below the Crown's still hits**: 9 against 10 is 23 steps, the most there is, and 3 against 10 is 17.
- **The same value misses:** "The crown defended without taking damage!" The relic is still spent.
- After every attack (a hit, a miss or a dodge) the Crown's rune moves on to the next one in its list. Each public attack report shows both runes with their values.
- On top of the steps come your extra damage (Brutal Strike, the White-tailed Deer buff, pets), less the Crown's damage reduction (the Blackened Tilapia buff, pets), multiplied by the Crown's handicap. A pet's perks count only while it's awake and well cared for ([Pets]({{ '/pets/' | relative_url }})).
- The Crown can **dodge** (Veil of Shadows, pets): a dodged attack deals nothing but still costs the relic.

### Mana and attack skills

You have **1,000 mana**, and you get 10 back every round (more with Abyssal Mana Tide), up to 1,000. Only the attack skill you pick costs mana, once. Without enough mana, the attack goes on without the skill and costs no mana.

- **Brutal Strike:** extra damage on the hit.
- **Bleed:** on a hit, the Crown bleeds for some rounds; each round's bleed damage counts as your damage. A new bleed of yours replaces your old one.
- **Doomseed:** on a hit, plants a seed that detonates after its rounds (fewer with Premature Bloom); **Thornburst** gives a detonation a chance to make the Crown bleed too (not a detonation the Crown's Bubble absorbs). A new seed of yours replaces your old one, and its rounds start again.
- **Robin Hood:** on a damaging hit, steals a share of the pool and splits it evenly among the reign's attackers. **Black Hood:** steals a share for you alone. Each steals exactly its share; the rounding remainder stays in the pool.
- **Silence:** on a hit, the Crown can't use Resurgence, Blood Purge, Defuse or Mana Drain for the silence's duration (Bubble still works).

### Skill points

Each skill tree (offensive and defensive) has **your rank + 30 points**. A skill holds at most 20. Add points with **Add 1 Skillpoint** or the amount box; a skill needs your rank to reach its level and its prerequisite skills (the menu says what's missing). **Reset Skills** takes back every skill of both trees for one **Forgotten Throne Elixir** (8,000 credits in the store), once.

What each skill does at its rank is what its screen shows:

**Offensive skills (for attackers)**



| Skill | Kind | Needs | Skill rank 1 | Skill rank 5 | Skill rank 10 | Skill rank 15 | Skill rank 20 |
|---|---|---|---|---|---|---|---|
| Brutal Strike | attack skill | your rank 1 | +1-4 extra damage; 1 mana | +5-8 extra damage; 7 mana | +10-13 extra damage; 14 mana | +15-18 extra damage; 22 mana | +20-23 extra damage; 29 mana |
| Abyssal Mana Tide | passive | your rank 1 | +1 mana a round | +5 mana a round | +10 mana a round | +15 mana a round | +20 mana a round |
| Blood Rush | passive | your rank 6, Brutal Strike | -1 s attack cooldown | -5 s attack cooldown | -10 s attack cooldown | -15 s attack cooldown | -20 s attack cooldown |
| Bleed | attack skill | your rank 12, Blood Rush | 1-3 bleed damage a round; 3 bleed rounds; 10 mana | 5-11 bleed damage a round; 5 bleed rounds; 18 mana | 10-21 bleed damage a round; 7 bleed rounds; 28 mana | 15-31 bleed damage a round; 10 bleed rounds; 38 mana | 20-41 bleed damage a round; 12 bleed rounds; 48 mana |
| Doomseed | attack skill | your rank 12 | 5-25 detonation damage; 15 rounds to detonation; 10 mana | 25-65 detonation damage; 15 rounds to detonation; 28 mana | 50-115 detonation damage; 15 rounds to detonation; 50 mana | 75-165 detonation damage; 15 rounds to detonation; 73 mana | 100-215 detonation damage; 15 rounds to detonation; 95 mana |
| Premature Bloom | passive | your rank 18, Doomseed | -1 rounds to detonation | -3 rounds to detonation | -6 rounds to detonation | -8 rounds to detonation | -11 rounds to detonation |
| Thornburst | passive | your rank 24, Doomseed, Bleed | 5% chance to bleed on detonation | 25% chance to bleed on detonation | 50% chance to bleed on detonation | 75% chance to bleed on detonation | 100% chance to bleed on detonation |
| Robin Hood | attack skill | your rank 12 | 0.025% of the pool, shared among the attackers; 5 mana | 0.125% of the pool, shared among the attackers; 9 mana | 0.25% of the pool, shared among the attackers; 14 mana | 0.375% of the pool, shared among the attackers; 19 mana | 0.5% of the pool, shared among the attackers; 24 mana |
| Black Hood | attack skill | your rank 18, Robin Hood | 0.0035% of the pool, to you; 5 mana | 0.0175% of the pool, to you; 9 mana | 0.035% of the pool, to you; 14 mana | 0.0525% of the pool, to you; 19 mana | 0.07% of the pool, to you; 24 mana |
| Silence | attack skill | your rank 24 | 35 s silence; 25 mana | 115 s silence; 125 mana | 215 s silence; 250 mana | 315 s silence; 375 mana | 415 s silence; 500 mana |



**Defensive skills (work while you hold the Crown)**



| Skill | Kind | Needs | Skill rank 1 | Skill rank 5 | Skill rank 10 | Skill rank 15 | Skill rank 20 |
|---|---|---|---|---|---|---|---|
| Throne of Endurance | passive | your rank 1 | +10% health | +50% health | +100% health | +150% health | +200% health |
| Iron Veins | passive | your rank 6, Throne of Endurance | -3.5% bleed damage | -17.5% bleed damage | -35% bleed damage | -52.5% bleed damage | -70% bleed damage |
| Hemostasis | passive | your rank 12, Iron Veins | -1 bleed rounds | -3 bleed rounds | -5 bleed rounds | -7 bleed rounds | -10 bleed rounds |
| Urgent Embind | passive | your rank 18, Hemostasis | -45 s Blood Purge cooldown | -225 s Blood Purge cooldown | -450 s Blood Purge cooldown | -675 s Blood Purge cooldown | -900 s Blood Purge cooldown |
| Veil of Shadows | passive | your rank 1 | +2% dodge | +4% dodge | +6.5% dodge | +9% dodge | +11.5% dodge |
| Fractured Time | passive | your rank 6, Veil of Shadows | +2 s attackers' cooldown | +6 s attackers' cooldown | +11 s attackers' cooldown | +16 s attackers' cooldown | +21 s attackers' cooldown |
| Grip of Stability | passive | your rank 6, Veil of Shadows | -0.44% tax pile chance on a round | -2.2% tax pile chance on a round | -4.4% tax pile chance on a round | -6.6% tax pile chance on a round | -8.8% tax pile chance on a round |
| Grip of Greed | passive | your rank 12, Grip of Stability | -0.24% tax pile chance on a hit | -1.2% tax pile chance on a hit | -2.4% tax pile chance on a hit | -3.6% tax pile chance on a hit | -4.8% tax pile chance on a hit |
| Swift Disarmament | passive | your rank 18 | -30 s Defuse cooldown | -150 s Defuse cooldown | -300 s Defuse cooldown | -450 s Defuse cooldown | -600 s Defuse cooldown |
| Siphon's Grasp | passive | your rank 24 | +15 s Mana Drain duration | +75 s Mana Drain duration | +150 s Mana Drain duration | +225 s Mana Drain duration | +300 s Mana Drain duration |



## Holding the Crown

### The Crown's skills

Only the Crown has these buttons. They cost nothing but their cooldown; clicking one again while it cools down changes nothing.

| Skill | What it does |
|---|---|
| Resurgence | heals 3% of the maximum health each of the next 10 rounds, never above the maximum; then waits an hour |
| Blood Purge | removes every bleed on the Crown, whoever cast it (seeds stay). With no bleed on the Crown it's refused and stays ready |
| Defuse | removes every seed waiting to detonate. With none, it's refused ("No detonations to defuse") and stays ready |
| Mana Drain | while it lasts, every hit on the Crown (not a miss) drains 10% of the attacker's mana, never below 0 |
| Bubble | while it lasts, attacks bounce off for free, bleeds on the Crown deal 0 but still run down, and a seed that detonates deals nothing and starts no Thornburst bleed (it's used up, and nothing of it hits after the Bubble). Remove Bubble ends it early. Then it waits an hour |

The cooldowns and durations, and what the defensive skills change, are in the tables above.

### Defensive runes

In **Defensive Runes**, pick up to 24 runes (the first becomes your current rune), move them up or down, and set the current one. Each line shows the rune's value in the running reign. While you hold the Crown, each attack faces your current rune and then moves it to the next in your list. A change you make while an attack is under way waits for that attack and is kept. Each attack report shows the Crown's defense streak (the attacks it has survived this reign), and your best streak is kept.

### Buildings

[Buildings]({{ '/buildings/' | relative_url }}) help the Crown: **Bastion of the Chosen** (+15 maximum health per level), **Pillar of the Undying** (every 5th point heals 1 + 3 per level) and **Temporal Nexus** (+1 second per level on each attacker's cooldown). A new Crown with Throne of Endurance starts with 1,000 × (1 + 10% per rank) health.

## Buffs

Eat them in **Crown Buffs**; each one you eat is a charge (at most 500 held). **One charge is used on every attack, whether it hits, misses or is dodged**; none when the attack bounces off a bubble or waits for a cooldown. The Crown Buffs screen shows the charges you hold.



| Buff | Effect, per charge | Cooked from |
|---|---|---|
| Blackened Tilapia with Cumin Slaw | 15 less damage from an attack on you as the Crown | 2 Tilapia + 6 Cumin |
| White-tailed Deer with Juniper Berry Demi-Glace | +15 damage on your attack | 2 White-tailed Deer + 2 Juniper Berry Demi-Glace |



## The round, every minute

- The Crown gets **1 point**: on the reign, on the Crown of Chaos leaderboards (all-time and monthly, with their top-10 roles) and on the weekly ladder. Every 5th point it regenerates health.
- Every attacker's points shrink by 0.35%, and every attacker gets mana back.
- Bleeds and seeds on the Crown run; their damage counts for whoever cast them. A bleed or a detonation can end the reign.
- Sometimes the round drops a **tax pile** (3% of the pool) in the Crown of Chaos channel, collected like a credit pile. A hit can drop one too (1% of the pool). Each tax pile is for **3, 4 or 5 players** (drawn for each pile, the pile says how many), who get equal shares, rounded down.
- **The handicap:** once the first 30 minutes of a reign are over, every round adds 1000% ÷ 10,080 to the Crown's handicap (up to 1,000% after 7 days), and every attack's damage is multiplied by (1 + handicap). A former Crown's handicap shrinks at a quarter of that speed. The attack report shows the extra damage, and the handicaps are reset once a week.

## Points

Your **points** in a reign are the damage you dealt (bleeds and detonations included), shrinking a little every round. **The final blow adds 200 points.** The **Attack Score Board** ranks the attackers by points (and shows their damage): that's the order of the draw for the next Crown and of the top-three RUNES shares.

## The end of a reign

When an attack or a round's bleed brings the Crown to 0:

1. **The next Crown is drawn** among everyone with points in this reign who is still in the server, weighted by points: each player's chance is their share of all the points. The draw is posted with its roll. The final blow's 200 points help, but don't crown you by themselves. When nobody still here has points, the realm's default Crown takes it.
2. **The old Crown gets the whole pool** in credits, once (the one prize not capped at 25,000 credits). The pool starts again at 0.
3. **RUNES** (a share of the realm's RUNES wallet, tipped): the old Crown gets **0.000032407% per point**, counting at most **19,999 points**; the final blow gets 3.5% of that, and the top three by points 5%, 3.5% and 1.5% of it.
4. **Experience:** the old Crown gets 0.85 × its points, at most **8,999**.
5. The Crown role moves to the new Crown, who starts with a seizure bubble.

- Two final blows at the same moment (a round and an attack, two attackers, a double click) end the reign once and pay the pool once.
- If the tipbot is unreachable, the reign still ends and the pool is paid; no RUNES are tipped or promised. Without the realm's tipbot session, the RUNES are recorded as not paid.

### A Crown who leaves the server

A Crown who leaves the server **loses the reign without any reward**: until the next round, attacks on them are refused (nothing is spent); then the round ends the reign, the next Crown is drawn from the attackers still in the server, and the pool stays for the next reign.

## The pool

The pool grows with **5% of every store purchase** in the realm and the **unclaimed shares of expired credit piles**. It shrinks by Robin Hood and Black Hood steals and the tax piles (a tax pile that can't be posted puts its credits back). The old Crown gets what's left when the reign ends.

## Quests

An attack that completes the **Damage Dealt** quest pays its experience (25) to the attacker, and a round that completes the Crown's **Points Earned** quest pays the Crown its experience (65), on top of anything else.

## The weekly ladder

Every ISO week (Monday 00:00 UTC to Sunday) has its own Crown of Chaos ladder. It scores what you did that week (the total is rounded down):



| Each … this week | Scores |
|---|---|
| Crowns Taken | 50 |
| Points Earned | 1 |
| Resurgences | 20 |
| Bleeds Purged | 5 |
| Defuses | 5 |
| Mana Drains | 2 |
| Silences | 10 |
| Bubbles | 15 |
| Attacks | 1 per 4 |
| Defends | 1 per 4 |
| Final Blows | 50 |



A Silence counts only when it lands: one that misses or is dodged scores nothing. Points Earned are the points you earn as the Crown; the Crown's skills count when used (Resurgences, Bubbles), per bleed purged or seed defused, and per hit its Mana Drain drained.

- On Monday (UTC), last week's **top 3** get the CoC Winners role.
- A tie goes to whoever reached the score first; players who left the server are left out.
- When the staff turn the weekly payouts on (on the Runebase server), last week's positive scores share **1% of the realm's RUNES wallet** by rank, once:



| Rank | Shares of the pool, each |
|---|---|
| 1 | 10 |
| 2 | 8 |
| 3 | 6 |
| 4 | 5 |
| 5 | 4 |
| 6 to 10 | 3 |
| 11 to 20 | 2 |
| 21 to 50 | 1 |
| 51 to 100 | 0.5 |



## Tips

- Watch the attack reports: they show the Crown's rune and its value, so you can pick the rune with the most steps above it (the one valued just below the Crown's).
- Bleeds and seeds keep earning you points every round; Blood Purge and Defuse are the Crown's answers.
- As the Crown, cycle several defensive runes so attackers can't read your next one, and save Bubble and Resurgence for heavy attacks.
- Keep your mana for the skill that matters: only the skill you pick costs mana.
