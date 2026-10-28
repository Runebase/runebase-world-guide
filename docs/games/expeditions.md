---
title: "Expeditions"
---

# Expeditions

**Where to play:** Discord
{ .where-to-play }

An idle activity: you spend energy, wait while your expedition runs, and come back to what it found. Expeditions bring back scrap, crafting materials and credits. [Fishing](fishing.md) and [hunting](hunting.md) work the same way.

**Where:** `/start` → **Activities** → **Expeditions** lets you pick how much energy to spend, and holds the **Expedition Buffs** menu.

## How a trip works

1. You choose how much energy to spend. Each energy is **10 seconds** of trip, longer with a resource building (see below).
2. While the trip runs you're busy: you can't start another expedition, fishing trip or hunt until it's over (the bot tells you, privately, that you're already busy and until when).
3. Every second of the trip is one roll for its scrap, and one roll on the trip's extra prizes (crafting materials, pet items, tokens, credits and more; the table is at the end of this page).
4. At the end you get what it found, your experience and your quest progress, and the trip counts on the leaderboards.

A trip pays exactly once. Clicking twice, or using two devices, starts one trip and spends the energy once. If the bot restarts during your trip, the trip is finished when the bot is back, and paid once.

## Energy

| Activity | Energy each day | Most energy | Seconds per energy |
|---|---|---|---|
| Expeditions | 5 + Expedition Command Center level | 25 (level 20, rank 100) | 10 + the level of the expedition's resource building (+2 per Braised Rabbit charge) |

- Energy refills at **00:00 UTC** every day. The refill sets your energy to the day's full amount; it doesn't add to what you had left.
- A trip that runs over midnight still pays once.
- Expeditions have no dish for more energy (fishing and hunting have one): without expedition energy, expeditions can't be started. If you click an expedition without the energy it needs (say, spent on another device), the bot tells you privately and leaves the menu as it was.

## Experience, quests and leaderboards

An expedition pays **3 experience per energy**.

Expeditions also move your [quests](../account/quests.md#every-quest): the expedition quests count the seconds of your expeditions. A quest that reaches its goal completes on its own and pays its reward once.

The expedition board counts expedition seconds.

## The three expeditions

Each looks for one kind of scrap:

| Expedition | Finds, chance each second | Longer with | Better odds with |
|---|---|---|---|
| Deep Excavation | 1 [Metal Scrap](../items/materials.md#metal-scrap) 8% | [Iron Mine](../account/buildings.md#what-each-building-does) (+1 second per energy per level) | Mining Pick |
| Woodland Logging Expedition | 1 [Wood Scrap](../items/materials.md#wood-scrap) 8% | [Lumber Yard](../account/buildings.md#what-each-building-does) (+1 second per energy per level) | Wood Axe |
| Nature Expedition | 1 [Leather Scrap](../items/materials.md#leather-scrap) 8% | [Tannery](../account/buildings.md#what-each-building-does) (+1 second per energy per level) | Skinning Knife |

- Each energy of an expedition lasts **10 seconds plus the level of its resource building** (Iron Mine for Deep Excavation, Lumber Yard for Woodland Logging, Tannery for Nature Expedition): with Iron Mine level 2, one energy of Deep Excavation is 12 seconds, 12 rolls.
- The expedition menu shows each expedition's time for the energy you pick and its scrap chance (with your utility and pet), the way the trip then uses them. **Expedition Secondary Loot Info** lists the extra prizes.
- Credits from an expedition go straight into your wallet.

## Utilities: Wood Axe, Skinning Knife, Mining Pick

Crafted for credits in `/start` → **Inventory** → **Utilities**. Every level adds **0.05 percentage points** to the chance of finding its scrap: on its expedition (Mining Pick on Deep Excavation, Wood Axe on Woodland Logging, Skinning Knife on Nature Expedition), in fishing's extra prizes (Mining Pick for [Metal Scrap](../items/materials.md#metal-scrap), Wood Axe for [Wood Scrap](../items/materials.md#wood-scrap)), in hunting's (Skinning Knife for [Leather Scrap](../items/materials.md#leather-scrap)), and in the other prize tables that have that scrap (votes, bumps, chat, dice, heists, treasure chests and more). With exactly the price in your wallet you can craft it. **Level n needs rank n** (the screen shows it as "User Level"): below it the craft button is off, and a click on an older one crafts nothing and tells you, privately, the rank you need.

| Utility | Raises | Each level | Level 1 | Level 2 | Level 3 | Level 5 | Level 10 | Level 25 | Level 50 |
|---|---|---|---|---|---|---|---|---|---|
| Wood Axe | Wood Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |
| Skinning Knife | Leather Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |
| Mining Pick | Metal Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |

## Buffs

| Buff | Where it comes from | Used by |
|---|---|---|
| [Braised Rabbit with Mustard Cream Sauce](../items/dishes.md#braised-rabbit-with-mustard-cream-sauce) | cooked: 2 [Rabbit](../items/ingredients.md#rabbit) + 2 [Mustard Cream Sauce](../items/ingredients.md#mustard-cream-sauce) | expeditions |

- **[Braised Rabbit with Mustard Cream Sauce](../items/dishes.md#braised-rabbit-with-mustard-cream-sauce):** eat it in **Expeditions** → **Expedition Buffs**. Each one is a charge that adds **2 seconds** to one energy of an expedition: an expedition uses **one charge per energy**. Fishing and hunting never use them.
- The expedition menu shows the buffs you have and the trip time they give.

## Pets

Your active pet helps while it's **awake** and cared for (see [Pets](../account/pets.md) for every pet, its perks and when they work). Its expedition perk adds its points to one expedition's scrap. Asleep, or below the perk's conditions, the pet adds nothing.

## Buildings that help

All in [Buildings](../account/buildings.md):

- **[Expedition Command Center](../account/buildings.md#what-each-building-does)**: +1 expedition energy a day per level.
- **[Lumber Yard, Iron Mine, Tannery](../account/buildings.md#resource-buildings)**: +1 second per energy on their expedition, per level.
- **[Arcane Reliquary](../account/buildings.md#what-each-building-does)**: the expeditions' crafting materials are 0.25% (of their own chance) likelier per level.

Everything adds up once: a utility, a pet perk, the resource building, the Command Center and Braised Rabbit on one expedition each count exactly once.

## Extra prizes, every second

Without utilities, pets or buildings. Each second rolls once on this table, whichever of the three expeditions it is (at most one prize a second).

| Prize | Chance each second |
|---|---|
| 1 [Standard Essence](../items/materials.md#standard-essence) | 0.4% |
| 1 [Elemental Core](../items/materials.md#elemental-core) | 0.2% |
| 1 [Primal Source](../items/materials.md#primal-source) | 0.08% |
| 1 [Basic Residue](../items/materials.md#basic-residue) | 0.2% |
| 1 [Enigmatic Nexus](../items/materials.md#enigmatic-nexus) | 0.08% |
| 1 [Mystical Node](../items/materials.md#mystical-node) | 0.04% |
| 1 [Elite Essence](../items/materials.md#elite-essence) | 0.08% |
| 1 [Radiant Shard](../items/materials.md#radiant-shard) | 0.04% |
| 1 [Shattered Prism](../items/materials.md#shattered-prism) | 0.02% |
| 1 [Engraving Tool](../items/materials.md#engraving-tool) | 0.8% |
| 3 [Chaos Relic](../items/keys-and-cards.md#chaos-relic) | 1% |
| 1 [Common Pet Token](../items/pet-items.md#common-pet-token) | 0.5% |
| 1 [Pet Token](../items/pet-items.md#pet-tokens) (Uncommon, Rare, Epic, Legendary, Mythical) | 0.25% each |
| 1 [Pet Food](../items/pet-items.md#pet-food) (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 [Pet Cure](../items/pet-items.md#pet-cures) (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 [Pet Wash Kit](../items/pet-items.md#pet-wash-kits) (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 0.5 to 5 credits | 15% |
| nothing | 71.31% |

## Tips

- Spend the day's energy before 00:00 UTC: the refill doesn't carry leftovers over.
- Braised Rabbit is used one per energy: a 10-energy expedition uses 10.
