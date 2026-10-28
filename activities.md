---
title: Fishing, hunting and expeditions
permalink: /activities/
---

[← All pages]({{ '/' | relative_url }})

# Fishing, hunting and expeditions

Three idle activities: you spend energy, wait while your trip runs, and come back to a catch. Fishing and hunting fill your basket with fish and meat for cooking; expeditions bring back scrap, crafting materials and credits.

**Where:** `/fish` and `/hunt` go on a one-energy trip straight away. `/start` → **Activities** → **Fish**, **Hunt** or **Expeditions** lets you pick how much energy to spend, and holds the crafting, equipment and buff menus.

## How a trip works

1. You choose how much energy to spend. Each energy is **10 seconds** of trip (expeditions: longer with a resource building, see below).
2. While the trip runs you're busy: you can't start another fishing trip, hunt or expedition until it's over (the bot tells you, privately, that you're already busy and until when).
3. Every second of the trip is one roll for a catch, and one roll on the trip's extra prizes (scrap, pet items, tokens and more; the tables are at the end of this page).
4. At the end you get your catch, your experience and your quest progress, and the trip counts on the leaderboards.

A trip pays exactly once. Clicking twice, or using two devices, starts one trip and spends the energy once. If the bot restarts during your trip, the trip is finished when the bot is back, and paid once.

## Energy



| Activity | Energy each day | Most energy | Seconds per energy |
|---|---|---|---|
| Fishing | 10 + Fishing Club level | 22 (level 12, rank 96) | 10 (+2 per Fishing Beer) |
| Hunting | 10 + Hunting Cabin level | 22 (level 12, rank 96) | 10 (+2 per Hunting Weed) |
| Expeditions | 5 + Expedition Command Center level | 25 (level 20, rank 100) | 10 + the level of the expedition's resource building (+2 per Braised Rabbit charge) |



- Energy refills at **00:00 UTC** every day. The refill sets your energy to the day's full amount; it doesn't add to what you had left.
- A trip that runs over midnight still pays once.
- **Out of fishing or hunting energy?** A **Pan-Fried Trout with Lemon and Dill** pays for one more energy of fishing, a **Wild Boar with Cherry Sauce** for one more energy of hunting. They are only used for the energy your daily energy doesn't cover, never while you still have energy. With neither, the trip doesn't start and nothing is spent: `/fish` and `/hunt` tell you so privately, with your fishing or hunting menu (your energy, when it refills), and a **Go Fishing** / **Go Hunting** button on a menu from earlier tells you privately and leaves the menu as it was.
- Expeditions have no such dish: without expedition energy, expeditions can't be started.

## Experience, quests and leaderboards

| Trip | Experience |
|---|---|
| Fishing | 1 per energy |
| Hunting | 1 per energy |
| Expeditions | 3 per energy |

Trips also move your quests: the Fishing and Hunting quests count the energy you spend, the quest for each fish or animal counts what you catch of it (Hunting - Elk counts your elk), and the expedition quests count the seconds of your expeditions. A quest that reaches its goal completes on its own and pays its reward once.

The fishing and hunting leaderboards count the seconds of your trips (beer and weed seconds included); the expedition board counts expedition seconds.

## Rods and rifles

You craft them in the **Fish** menu (**Craft Fishing Pole**) and the **Hunt** menu (**Craft Hunting Rifle**) for scrap from your pouch. You can own one of each. Without one, you only catch Anchovy (fishing) or Squirrel (hunting).



| Item | Crafting cost (wood / metal / leather scrap) | Catches, chance each second |
|---|---|---|
| no rod | – | Anchovy 5% |
| Skathi's Rod | 6 / 1 / 2 | Anchovy 5%, Mackerel 5%, Sardines 5% |
| Gaul's Glimmer | 41 / 16 / 20 | Cod 5%, Tuna 5%, Tilapia 5% |
| Freyja's Spar | 200 / 50 / 60 | Eel 5%, Trout 5%, Swordfish 5% |
| no rifle | – | Squirrel 5% |
| Savage Model 11 | 1 / 6 / 2 | Squirrel 5%, Rabbit 5%, Coyote 5% |
| Winchester Model 70 | 16 / 41 / 20 | Wild Turkey 5%, Pheasant 5%, White-tailed Deer 5% |
| Weatherby Mark V | 50 / 200 / 60 | Elk 5%, Moose 5%, Wild Boar 5% |



- Equip a rod or rifle in its menu. **The one equipped when the trip ends decides the catch**, so a swap during a trip counts.
- With more than one rod (or rifle) you can turn on **rotative** fishing (hunting): each second of the trip rolls on the next one in turn. With only one, the switch isn't offered and a trip never rotates.
- Crafting costs exactly the scrap shown. With a scrap short, or an item you already own, the Craft button is off.

### Enhancements

Each rod and rifle has its own enhancement, upgraded from the crafting screen for scrap. Every level adds **0.1 percentage points** to each of that item's three catches (not to your other rods). The crafting screen's "Chance: 5.3% per Second" (Skathi's Rod at enhancement level 3) is exactly what a trip rolls. Each level needs a rank of twice the level (the crafting screen shows it as "User Level"): below it the upgrade button is off, and a click on an older one upgrades nothing and tells you, privately, the rank you need. The costs below are wood / metal / leather scrap.



| Item | Enhancement | Each level | Level 1 (rank 2) | Level 2 (rank 4) | Level 10 (rank 20) | Level 25 (rank 50) | Level 50 (rank 100) |
|---|---|---|---|---|---|---|---|
| Skathi's Rod | Glacier Glider | +0.1 points on each of its catches | 5 / 1 / 3 | 7 / 2 / 5 | 27 / 9 / 18 | 63 / 21 / 42 | 123 / 41 / 82 |
| Gaul's Glimmer | Moonlit Mirage | +0.1 points on each of its catches | 16 / 6 / 8 | 22 / 8 / 11 | 70 / 28 / 35 | 160 / 64 / 80 | 310 / 124 / 155 |
| Freyja's Spar | Runebound Rouser | +0.1 points on each of its catches | 52 / 22 / 15 | 70 / 30 / 20 | 210 / 90 / 60 | 472 / 202 / 135 | 910 / 390 / 260 |
| Savage Model 11 | Phantomstrike Optics | +0.1 points on each of its catches | 1 / 5 / 3 | 2 / 7 / 5 | 9 / 27 / 18 | 21 / 63 / 42 | 41 / 123 / 82 |
| Winchester Model 70 | Precision Prowler | +0.1 points on each of its catches | 16 / 6 / 8 | 22 / 8 / 11 | 70 / 28 / 35 | 160 / 64 / 80 | 310 / 124 / 155 |
| Weatherby Mark V | Tempest Vision | +0.1 points on each of its catches | 52 / 22 / 15 | 70 / 30 / 20 | 210 / 90 / 60 | 472 / 202 / 135 | 910 / 390 / 260 |



## Utilities: Wood Axe, Skinning Knife, Mining Pick

Crafted for credits in `/start` → **Inventory** → **Utilities**. Every level adds **0.05 percentage points** to the chance of finding its scrap: in fishing's extra prizes (Mining Pick for Metal Scrap, Wood Axe for Wood Scrap), in hunting's (Skinning Knife for Leather Scrap), on its expedition (Mining Pick on Deep Excavation, Wood Axe on Woodland Logging, Skinning Knife on Nature Expedition), and in the other prize tables that have that scrap (votes, bumps, chat, dice, heists, treasure chests and more). With exactly the price in your wallet you can craft it. **Level n needs rank n** (the screen shows it as "User Level"): below it the craft button is off, and a click on an older one crafts nothing and tells you, privately, the rank you need.



| Utility | Raises | Each level | Level 1 | Level 2 | Level 3 | Level 5 | Level 10 | Level 25 | Level 50 |
|---|---|---|---|---|---|---|---|---|---|
| Wood Axe | Wood Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |
| Skinning Knife | Leather Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |
| Mining Pick | Metal Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |



## Buffs



| Buff | Where it comes from | Used by |
|---|---|---|
| Fishing Beer | 3 credits in the store; the Party Store | fishing |
| Hunting Weed | 3 credits in the store; the Party Store | hunting |
| Pan-Fried Trout with Lemon and Dill | cooked: 2 Trout + 4 Dill + 1 Lemon | fishing, when the energy is gone |
| Wild Boar with Cherry Sauce | cooked: 2 Wild Boar + 6 Cherry Sauce | hunting, when the energy is gone |
| Braised Rabbit with Mustard Cream Sauce | cooked: 2 Rabbit + 2 Mustard Cream Sauce | expeditions |



- **Fishing Beer / Hunting Weed** (bought from the store, also from the fishing menu, or collected at the Party Store): each one adds **2 seconds** to one energy of a trip, so a trip uses **one per energy**, at most. A 3-energy trip with 2 beers lasts 34 seconds. The extra seconds roll for catches and extra prizes like any other second, and count on the leaderboard. Experience and the Fishing and Hunting quests count energy, so the extra seconds add none; a fish caught in them counts for its fish quest like any other.
- **Braised Rabbit with Mustard Cream Sauce:** eat it in **Expeditions** → **Expedition Buffs**. Each one is a charge that adds **2 seconds** to one energy of an expedition: an expedition uses **one charge per energy**. Fishing and hunting never use them.
- The trip menus show the buffs you have and the trip time they give.

## Pets

Your active pet helps while it's **awake** and cared for (see [Pets]({{ '/pets/' | relative_url }}) for every pet, its perks and when they work). Its fishing perk adds its points to one fish, its hunting perk to one animal, its expedition perk to one expedition's scrap. A perk for a fish your rod doesn't catch does nothing: a Mackerel perk needs Skathi's Rod. Asleep, or below the perk's conditions, the pet adds nothing.

## Expeditions

Three expeditions, each looking for one kind of scrap:



| Expedition | Finds, chance each second | Longer with | Better odds with |
|---|---|---|---|
| Deep Excavation | 1 Metal Scrap 8% | Iron Mine (+1 second per energy per level) | Mining Pick |
| Woodland Logging Expedition | 1 Wood Scrap 8% | Lumber Yard (+1 second per energy per level) | Wood Axe |
| Nature Expedition | 1 Leather Scrap 8% | Tannery (+1 second per energy per level) | Skinning Knife |



- Each energy of an expedition lasts **10 seconds plus the level of its resource building** (Iron Mine for Deep Excavation, Lumber Yard for Woodland Logging, Tannery for Nature Expedition): with Iron Mine level 2, one energy of Deep Excavation is 12 seconds, 12 rolls.
- The expedition menu shows each expedition's time for the energy you pick and its scrap chance (with your utility and pet), the way the trip then uses them. **Expedition Secondary Loot Info** lists the extra prizes.
- Credits from an expedition go straight into your wallet.

## Buildings that help

All in [Buildings]({{ '/buildings/' | relative_url }}):

- **Fishing Club**, **Hunting Cabin**: +1 fishing / hunting energy a day per level. **Expedition Command Center**: +1 expedition energy a day per level.
- **Lumber Yard**, **Iron Mine**, **Tannery**: +1 second per energy on their expedition, per level.
- **Arcane Reliquary**: the expeditions' crafting materials are 0.25% (of their own chance) likelier per level.

Everything adds up once: a rod enhancement, a pet perk, beer and an energy building on one trip each count exactly once.

## Extra prizes, every second

Without utilities, pets or buildings. Each second rolls once on its activity's table below (at most one prize a second).

**Fishing**



| Prize | Chance each second |
|---|---|
| 1 Metal Scrap | 0.15% |
| 1 Wood Scrap | 0.15% |
| 6 Chaos Relic | 0.15% |
| 1 Common Pet Token | 0.5% |
| 1 Pet Token (Uncommon, Rare, Epic, Legendary, Mythical) | 0.25% each |
| 1 Pet Food (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 Pet Cure (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 Pet Wash Kit (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| nothing | 88.8% |



**Hunting**



| Prize | Chance each second |
|---|---|
| 1 Leather Scrap | 0.3% |
| 6 Chaos Relic | 0.15% |
| 1 Common Pet Token | 0.5% |
| 1 Pet Token (Uncommon, Rare, Epic, Legendary, Mythical) | 0.25% each |
| 1 Pet Food (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 Pet Cure (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 Pet Wash Kit (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| nothing | 88.8% |



**Expeditions** (any of the three)



| Prize | Chance each second |
|---|---|
| 1 Standard Essence | 0.4% |
| 1 Elemental Core | 0.2% |
| 1 Primal Source | 0.08% |
| 1 Basic Residue | 0.2% |
| 1 Enigmatic Nexus | 0.08% |
| 1 Mystical Node | 0.04% |
| 1 Elite Essence | 0.08% |
| 1 Radiant Shard | 0.04% |
| 1 Shattered Prism | 0.02% |
| 1 Engraving Tool | 0.8% |
| 3 Chaos Relic | 1% |
| 1 Common Pet Token | 0.5% |
| 1 Pet Token (Uncommon, Rare, Epic, Legendary, Mythical) | 0.25% each |
| 1 Pet Food (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 Pet Cure (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 Pet Wash Kit (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 0.5 to 5 credits | 15% |
| nothing | 71.31% |



## Tips

- Spend the day's energy before 00:00 UTC: the refill doesn't carry leftovers over.
- A rod's enhancement only helps its own three fish, and a pet perk only helps a fish your rod catches: match your pet to your rod.
- Beer, weed and rabbit are used one per energy: a 10-energy trip uses 10.
