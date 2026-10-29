---
title: "Expeditions"
icon: guide/nav
nav_emoji: "🧭"
---

# 🧭 Expeditions

**Where to play:** Discord
{ .where-to-play }

An idle activity: you spend energy, wait while your expedition runs, and come back to what it found. Expeditions bring back scrap, crafting materials and credits. <span class="gi-m">![](../assets/icons/emoji/fishin.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Fishing](fishing.md)</span> and <span class="gi-m">🏹&nbsp;[hunting](hunting.md)</span> work the same way.

**Where:** `/start` → **Activities** → **Expeditions** lets you pick how much energy to spend, and holds the **Expedition Buffs** menu.

## How a trip works

1. You choose how much energy to spend. Each energy is **10 seconds** of trip, longer with a resource building (see below).
2. While the trip runs you're busy: you can't start another expedition, fishing trip or hunt until it's over (the bot tells you, privately, that you're already busy and until when).
3. Every second of the trip is one roll for its scrap, and one roll on the trip's extra prizes (crafting materials, pet items, tokens, credits and more; the table is at the end of this page).
   - Each scrap found is its own prize, as in fishing and hunting: when your pouch is full, the scrap that still fits is paid and the rest isn't. The result lists what was paid and, apart, what your pouch had no room for (**Unable to loot Pouch full**); **Today's loot** on the menu counts only what was paid (with the trips' experience and quest rewards).
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

Expeditions also move your <span class="gi-m">![](../assets/icons/emoji/quest.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[quests](../account/quests.md#every-quest)</span>: the expedition quests count the seconds of your expeditions. A quest that reaches its goal completes on its own and pays its reward once.

The expedition board counts expedition seconds.

## The three expeditions

Each looks for one kind of scrap:

| Expedition | Finds, chance each second | Longer with | Better odds with |
|---|---|---|---|
| Deep Excavation | ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Metal Scrap](../items/materials/scrap.md#metal-scrap) 8% | <span class="gi-m">![](../assets/icons/building/iron-mine.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Iron Mine](../account/buildings.md#what-each-building-does)</span> (+1 second per energy per level) | Mining Pick |
| Woodland Logging Expedition | ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Wood Scrap](../items/materials/scrap.md#wood-scrap) 8% | <span class="gi-m">![](../assets/icons/building/lumber-yard.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Lumber Yard](../account/buildings.md#what-each-building-does)</span> (+1 second per energy per level) | Wood Axe |
| Nature Expedition | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Leather Scrap](../items/materials/scrap.md#leather-scrap) 8% | <span class="gi-m">![](../assets/icons/building/tannery.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Tannery](../account/buildings.md#what-each-building-does)</span> (+1 second per energy per level) | Skinning Knife |

- Each energy of an expedition lasts **10 seconds plus the level of its resource building** (<span class="gi-m">![](../assets/icons/building/iron-mine.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Iron Mine](../account/buildings.md#what-each-building-does)</span> for Deep Excavation, <span class="gi-m">![](../assets/icons/building/lumber-yard.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Lumber Yard](../account/buildings.md#what-each-building-does)</span> for Woodland Logging, <span class="gi-m">![](../assets/icons/building/tannery.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Tannery](../account/buildings.md#what-each-building-does)</span> for Nature Expedition): with Iron Mine level 2, one energy of Deep Excavation is 12 seconds, 12 rolls.
- The expedition menu shows each expedition's time for the energy you pick and its scrap chance (with your utility and pet), the way the trip then uses them. **Expedition Secondary Loot Info** lists the extra prizes.
- Credits from an expedition go straight into your wallet.

## Utilities: Wood Axe, Skinning Knife, Mining Pick

Crafted for credits in `/start` → **Inventory** → **Utilities**. Every level adds **0.05 percentage points** to the chance of finding its scrap: on its expedition (<span class="gi-m">⛏️&nbsp;[Mining Pick](#utilities-wood-axe-skinning-knife-mining-pick)</span> on Deep Excavation, <span class="gi-m">🪓&nbsp;[Wood Axe](#utilities-wood-axe-skinning-knife-mining-pick)</span> on Woodland Logging, <span class="gi-m">🔪&nbsp;[Skinning Knife](#utilities-wood-axe-skinning-knife-mining-pick)</span> on Nature Expedition), in fishing's extra prizes (Mining Pick for <span class="gi-m">![](../assets/icons/item/metal-scrap.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Metal Scrap](../items/materials/scrap.md#metal-scrap)</span>, Wood Axe for <span class="gi-m">![](../assets/icons/item/wood-scrap.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Wood Scrap](../items/materials/scrap.md#wood-scrap)</span>), in hunting's (Skinning Knife for <span class="gi-m">![](../assets/icons/item/leather-scrap.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Leather Scrap](../items/materials/scrap.md#leather-scrap)</span>), and in the other prize tables that have that scrap (votes, bumps, chat, dice, heists, treasure chests and more). With exactly the price in your wallet you can craft it. **Level n needs rank n** (the screen shows it as "User Level"): below it the craft button is off, and a click on an older one crafts nothing and tells you, privately, the rank you need.

| Utility | Raises | Each level | Level 1 | Level 2 | Level 3 | Level 5 | Level 10 | Level 25 | Level 50 |
|---|---|---|---|---|---|---|---|---|---|
| 🪓 Wood Axe | Wood Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |
| 🔪 Skinning Knife | Leather Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |
| ⛏️ Mining Pick | Metal Scrap | +0.05 points | 350 credits | 612 credits | 875 credits | 1,400 credits | 2,712 credits | 6,650 credits | 13,212 credits |

## Buffs

| Buff | Where it comes from | Used by |
|---|---|---|
| ![Braised Rabbit with Mustard Cream Sauce](../assets/icons/item/braised-rabbit-with-mustard-cream-sauce.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } [Braised Rabbit with Mustard Cream Sauce](../items/consumables/meat-dishes.md#braised-rabbit-with-mustard-cream-sauce) | cooked: 2 <span class="gi-m">![](../assets/icons/item/rabbit.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Rabbit](../items/ingredients/meat.md#rabbit)</span> + 2 <span class="gi-m">![](../assets/icons/item/mustard-cream-sauce.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Mustard Cream Sauce](../items/ingredients/sauces.md#mustard-cream-sauce)</span> | expeditions |

- **<span class="gi-m">![](../assets/icons/item/braised-rabbit-with-mustard-cream-sauce.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Braised Rabbit with Mustard Cream Sauce](../items/consumables/meat-dishes.md#braised-rabbit-with-mustard-cream-sauce)</span>:** eat it in **Expeditions** → **Expedition Buffs**. Each one is a charge that adds **2 seconds** to one energy of an expedition: an expedition uses **one charge per energy**. Fishing and hunting never use them.
- The expedition menu shows the buffs you have and the trip time they give.

## Pets

Your active pet helps while it's **awake** and cared for (see <span class="gi-m">🐾&nbsp;[Pets](../account/pets.md)</span> for every pet, its perks and when they work). Its expedition perk adds its points to one expedition's scrap. Asleep, or below the perk's conditions, the pet adds nothing. The pet counts if it's active and awake when the trip ends: a pet changed during the trip gives its perks, one put to sleep gives none.

## Buildings that help

All in <span class="gi-m">🏗️&nbsp;[Buildings](../account/buildings.md)</span>:

- **<span class="gi-m">![](../assets/icons/building/expedition-command-center.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Expedition Command Center](../account/buildings.md#what-each-building-does)</span>**: +1 expedition energy a day per level.
- **[Lumber Yard, Iron Mine, Tannery](../account/buildings.md#resource-buildings)**: +1 second per energy on their expedition, per level.
- **<span class="gi-m">![](../assets/icons/building/arcane-reliquary.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Arcane Reliquary](../account/buildings.md#what-each-building-does)</span>**: the expeditions' crafting materials are 0.25% (of their own chance) likelier per level.

Everything adds up once: a utility, a pet perk, the resource building, the Command Center and <span class="gi-m">![](../assets/icons/item/braised-rabbit-with-mustard-cream-sauce.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Braised Rabbit](../items/consumables/meat-dishes.md#braised-rabbit-with-mustard-cream-sauce)</span> on one expedition each count exactly once.

## Extra prizes, every second

Without utilities, pets or buildings. Each second rolls once on this table, whichever of the three expeditions it is (at most one prize a second).

| Prize | Chance each second |
|---|---|
| ![Standard Essence](../assets/icons/item/standard-essence.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Standard Essence](../items/materials/hack-and-slash-crafting-materials.md#standard-essence) | 0.4% |
| ![Elemental Core](../assets/icons/item/elemental-core.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Elemental Core](../items/materials/hack-and-slash-crafting-materials.md#elemental-core) | 0.2% |
| ![Primal Source](../assets/icons/item/primal-source.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Primal Source](../items/materials/hack-and-slash-crafting-materials.md#primal-source) | 0.08% |
| ![Basic Residue](../assets/icons/item/basic-residue.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Basic Residue](../items/materials/hack-and-slash-crafting-materials.md#basic-residue) | 0.2% |
| ![Enigmatic Nexus](../assets/icons/item/enigmatic-nexus.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Enigmatic Nexus](../items/materials/hack-and-slash-crafting-materials.md#enigmatic-nexus) | 0.08% |
| ![Mystical Node](../assets/icons/item/mystical-node.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Mystical Node](../items/materials/hack-and-slash-crafting-materials.md#mystical-node) | 0.04% |
| ![Elite Essence](../assets/icons/item/elite-essence.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Elite Essence](../items/materials/hack-and-slash-crafting-materials.md#elite-essence) | 0.08% |
| ![Radiant Shard](../assets/icons/item/radiant-shard.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Radiant Shard](../items/materials/hack-and-slash-crafting-materials.md#radiant-shard) | 0.04% |
| ![Shattered Prism](../assets/icons/item/shattered-prism.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Shattered Prism](../items/materials/hack-and-slash-crafting-materials.md#shattered-prism) | 0.02% |
| ![Engraving Tool](../assets/icons/item/engraving-tool.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Engraving Tool](../items/materials/hack-and-slash-crafting-materials.md#engraving-tool) | 0.8% |
| ![Chaos Relic](../assets/icons/item/chaos-relic.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Chaos Relic](../items/keys-and-cards/cards-and-relics.md#chaos-relic) | 1% |
| ![Common Pet Token](../assets/icons/item/common-pet-token.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Common Pet Token](../items/pet-items/pet-tokens.md#common-pet-token) | 0.5% |
| 1 <span class="gi-m">📦&nbsp;[Pet Token](../items/pet-items/pet-tokens.md)</span> (Uncommon, Rare, Epic, Legendary, Mythical) | 0.25% each |
| 1 <span class="gi-m">🍖&nbsp;[Pet Food](../items/pet-items/pet-food.md)</span> (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 <span class="gi-m">💊&nbsp;[Pet Cure](../items/pet-items/pet-cures.md)</span> (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 <span class="gi-m">🛁&nbsp;[Pet Wash Kit](../items/pet-items/pet-wash-kits.md)</span> (Common, Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 0.5 to 5 credits | 15% |
| nothing | 71.31% |

## Tips

- Spend the day's energy before 00:00 UTC: the refill doesn't carry leftovers over.
- <span class="gi-m">![](../assets/icons/item/braised-rabbit-with-mustard-cream-sauce.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Braised Rabbit](../items/consumables/meat-dishes.md#braised-rabbit-with-mustard-cream-sauce)</span> is used one per energy: a 10-energy expedition uses 10.
