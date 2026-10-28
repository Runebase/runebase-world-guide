---
title: "Gear, items and crafting"
---

# Gear, items and crafting

**Where to play:** Discord
{ .where-to-play }

## Condition, repairs and gear

- **Condition:** at 00:00 UTC the class you have selected refills its health, mana and stamina; your other classes keep what they had. **[Pheasant with Blackberry Balsamic Glaze](../../items/dishes.md#pheasant-with-blackberry-balsamic-glaze)** fills your stamina to its maximum.
- **Wear:** every round there's a 5% chance one of your equipped items loses 1 durability, and 1.5% with every monster attack, whether it hits you or not (leggings too).
- **Repairs:** 1 credit per missing durability point on a Normal item, 2 on an Exceptional one, 3 on an Elite one (a Circlet 1.11). The cost shown, item by item or all at once, is exactly what you pay; durability goes back to the maximum. Without the credits, nothing changes.
- **Equipment:** equipping puts the item in its slot and the replaced one back in your inventory (a two-handed weapon also takes off the shield). Gear you're not strong, nimble or experienced enough for stays in your inventory; the strength and dexterity from your other gear and its active inscriptions count toward a requirement (not the item's own). Gear you wear but no longer meet the requirements of (after an attribute reset, taking off a +strength item, or losing levels) gives nothing and shows red on the equipment screen until you meet them again: after a reset, spend your points again. Every bonus an item shows counts while you wear it ([item bonuses](#item-bonuses)).
- **Inventory:** destroy an item, disassemble it into one crafting material of its quality and tier, or keep it in your stash.
- The [buildings](../../account/buildings.md#what-each-building-does) Training Grounds, Arcane Library, Healing Spring, Mana Well, Fitness Foundry and Traveler's Camp make your characters stronger; the Arcane Reliquary makes Magic and Rare drops likelier.

## Crafting

`/craft` (or Equipment → Craft):

- **Craft Items:** pick the type, family, item and quality: an item costs **3 crafting materials and 1 scrap**, goes into your inventory and pays 1 experience. Without the materials, the button is off.
- **Convert Crafting Materials:** 3 of a material make 1 of the next tier, for a small credit fee (3 [Standard Essence](../../items/materials.md#standard-essence) → 1 [Elemental Core](../../items/materials.md#elemental-core) for 0.3 credits).
- **Inscriptions:** a Magic inscription costs 1 [Engraving Tool](../../items/materials.md#engraving-tool), a Rare one 3. It's drawn from the inscriptions your item's type and your level can get, each stat rolled in its range, and added inactive; activate it to make it the item's inscription (one at a time). Its bonuses then count like the item's own, its armor even on a ring or an amulet, its block on a shield.

## Item bonuses

What an item's screen says is what it does: each number below was checked in play, made from the game's own data, worn, and in a battle round. The item's screen shows the number it rolled; your stats screen moves by exactly that number while you wear it, and back when you take it off. A broken item (durability 0) gives nothing until it's repaired.

### Bonuses (magic and rare modifiers, inscriptions)

| Bonus | On the item's screen | What it does | Rolls on | Checked in play |
|---|---|---|---|---|
| Strength | "+N to strength" | Adds to your strength: +1% physical and throw damage a point, and it counts for strength requirements. | 4 magic prefixes, 1 magic suffix, 6 rare prefixes, 4 rare suffixes, 2 magic inscriptions, 2 rare inscriptions | yes (affixes, inBattle) |
| Dexterity | "+N to dexterity" | Adds to your dexterity like a point you spend: +5 attack rating a point × your level's multiplier, your block with a shield, and dexterity requirements. | 5 magic prefixes, 1 magic suffix, 11 rare prefixes, 5 rare suffixes, 1 magic inscription, 3 rare inscriptions | yes (affixes, inBattle) |
| Vitality | "+N to vitality" | Adds to your vitality: health (× your class's multiplier) and stamina. | 2 magic prefixes, 2 magic suffixes, 10 rare prefixes, 4 rare suffixes, 3 magic inscriptions, 3 rare inscriptions | yes (affixes) |
| Energy | "+N to energy" | Adds to your energy: mana (× your class's multiplier). | 2 magic prefixes, 4 magic suffixes, 10 rare prefixes, 2 rare suffixes, 1 magic inscription, 1 rare inscription | yes (affixes) |
| Attack rating | "+N to attack rating" | Adds to the attack rating of your attacks and kicks (flat: the level multiplier doesn't touch it): you miss less. | 1 rare prefix, 2 rare suffixes, 4 magic inscriptions, 2 rare inscriptions | yes (affixes, inBattle) |
| Enhanced defense | "Armor: N (upped from M)" | The item's own armor × (1 + its %): its screen shows the result as "Armor: N (upped from M)". | 5 magic prefixes, 4 rare prefixes, 2 rare suffixes | yes (affixes, baseStats, inBattle) |
| Enhanced damage | "Damage: N - M (upped from …)" | The weapon's own damage (and throw damage) × (1 + its %), rounded: its screen shows the result as "Damage: N - M (upped from …)", and that's what it hits for. | 2 magic prefixes, 1 magic suffix, 7 rare prefixes, 1 rare suffix | yes (affixes, baseStats, inBattle) |
| Life steal | "+N% Life Steal" | Heals you its % of the physical damage you deal (attacks and kicks). | 2 magic prefixes, 1 magic suffix, 1 magic inscription, 3 rare inscriptions | yes (affixes, inBattle) |
| Mana steal | "+N% Mana Steal" | Gives you its % of the physical damage you deal as mana. | 1 magic prefix, 1 magic suffix, 1 magic inscription, 1 rare inscription | yes (affixes, inBattle) |
| Stun | "+N% Stun" | Its chance, on each hit, to stun the monster: it skips its attack that round. | 1 rare prefix, 1 magic inscription | yes (affixes, inBattle) |
| Conversion | "+N% Conversion" | Its chance, on each hit, to turn the monster into an ally that fights for you, as the Paladin's Conversion does at rank 1: one at a time, for 10 rounds. With the Conversion skill it adds to the skill's chance. In the Arena it never converts your opponent (the hit deals its damage), only their minions. | 1 magic prefix | yes (affixes, inBattle, arena) |
| Critical strike | "+N% Critical Strike" | Its chance, on each hit, to deal +75% damage (before armor). | 1 magic prefix, 6 rare prefixes, 2 rare suffixes, 3 magic inscriptions, 4 rare inscriptions | yes (affixes, inBattle) |
| Bleed | "+N% chance to inflict Bleed (50% of your weapon damage a round for 4 rounds)" | Its chance, on each physical hit that lands, to make the monster bleed like the Warrior's Wound at rank 1: 50% of your weapon's damage (with your physical damage bonus) a round for 4 rounds, from the next round, on monsters and in the Arena on your opponent and their minions. A new bleed replaces the last one. | 1 magic prefix, 1 rare prefix, 1 rare suffix, 1 magic inscription, 1 rare inscription | yes (affixes, inBattle, arena) |
| Avoid | "+N% Avoid" | Its chance to avoid a ranged physical attack completely. | 2 rare prefixes, 4 rare suffixes | yes (affixes, inBattle) |
| Dodge | "+N% Dodge" | Its chance to dodge a melee physical attack that would have hit. | 1 magic prefix, 2 rare prefixes, 4 rare suffixes, 1 magic inscription | yes (affixes, inBattle) |
| Fire damage | "Fire Damage: N" | Adds its fire damage range to your attacks and attack skills (not to kicks). The monster's fire resistance lowers it; armor doesn't. | 1 magic prefix, 1 magic suffix, 1 rare prefix, 2 magic inscriptions, 2 rare inscriptions | yes (affixes, inBattle) |
| +% fire damage | "+N% Fire Damage" | Raises all your fire damage by its %. | 2 magic prefixes, 2 rare prefixes, 1 magic inscription, 3 rare inscriptions | yes (affixes, inBattle) |
| Fire resistance | "+N% to Fire Resistance" | A fire hit takes its % less (your total stops at 70%). | 1 magic suffix, 2 rare suffixes, 2 magic inscriptions, 2 rare inscriptions | yes (affixes, inBattle) |
| Reflect fire | "+N% Reflect Fire" | Sends its % of the fire damage a monster deals you back at it (its own resistance applies). | 2 magic prefixes, 2 rare prefixes, 1 rare inscription | yes (affixes, inBattle) |
| Cold damage | "Cold Damage: N" | Adds its cold damage range to your attacks and attack skills (not to kicks). The monster's cold resistance lowers it; armor doesn't. | 1 magic prefix, 1 magic suffix, 1 rare prefix, 1 rare suffix, 2 magic inscriptions, 1 rare inscription | yes (affixes, inBattle) |
| +% cold damage | "+N% Cold Damage" | Raises all your cold damage by its %. | 2 magic prefixes, 3 rare prefixes, 2 rare suffixes, 1 rare inscription | yes (affixes, inBattle) |
| Cold resistance | "+N% to Cold Resistance" | A cold hit takes its % less (your total stops at 70%). | 1 magic suffix, 2 rare suffixes, 2 magic inscriptions, 1 rare inscription | yes (affixes, inBattle) |
| Reflect cold | "+N% Reflect Cold" | Sends its % of the cold damage a monster deals you back at it (its own resistance applies). | 2 magic prefixes, 2 rare prefixes, 1 magic inscription, 1 rare inscription | yes (affixes, inBattle) |
| Lightning damage | "Lightning Damage: N" | Adds its lightning damage range to your attacks and attack skills (not to kicks). The monster's lightning resistance lowers it; armor doesn't. | 1 magic prefix, 1 magic suffix, 1 rare prefix, 2 magic inscriptions, 1 rare inscription | yes (affixes, inBattle) |
| +% lightning damage | "+N% Lightning Damage" | Raises all your lightning damage by its %. | 2 magic prefixes, 1 rare prefix, 1 magic inscription, 2 rare inscriptions | yes (affixes, inBattle) |
| Lightning resistance | "+N% to Lightning Resistance" | A lightning hit takes its % less (your total stops at 70%). | 1 magic suffix, 2 rare suffixes, 1 magic inscription, 1 rare inscription | yes (affixes, inBattle) |
| Reflect lightning | "+N% Reflect Lightning" | Sends its % of the lightning damage a monster deals you back at it (its own resistance applies). | 2 magic prefixes, 2 rare prefixes, 1 rare inscription | yes (affixes, inBattle) |
| Poison damage | "Poison Damage: N" | Adds its poison damage range to your attacks and attack skills (not to kicks). The monster's poison resistance lowers it; armor doesn't. | 1 magic prefix, 1 magic suffix, 1 rare prefix, 2 magic inscriptions, 1 rare inscription | yes (affixes, inBattle) |
| +% poison damage | "+N% Poison Damage" | Raises all your poison damage by its %. | 2 magic prefixes, 2 rare prefixes, 1 rare inscription | yes (affixes, inBattle) |
| Poison resistance | "+N% to Poison Resistance" | A poison hit takes its % less (your total stops at 70%). | 1 magic suffix, 2 rare suffixes, 1 magic inscription, 1 rare inscription | yes (affixes, inBattle) |
| Reflect poison | "+N% Reflect Poison" | Sends its % of the poison damage a monster deals you back at it (its own resistance applies). | 2 magic prefixes, 2 rare prefixes, 1 magic inscription, 1 rare inscription | yes (affixes, inBattle) |
| Magic damage | "Magic Damage: N" | Adds its magic damage range to your attacks and attack skills (not to kicks). The monster's magic resistance lowers it; armor doesn't. | 1 magic prefix, 1 magic suffix, 1 rare prefix, 1 magic inscription, 1 rare inscription | yes (affixes, inBattle) |
| +% magic damage | "+N% Magic Damage" | Raises all your magic damage by its %. | 2 magic prefixes, 2 rare prefixes, 1 rare suffix, 2 rare inscriptions | yes (affixes, inBattle) |
| Magic resistance | "+N% to Magic Resistance" | A magic hit takes its % less (your total stops at 70%). | 1 magic suffix, 1 rare suffix, 2 magic inscriptions, 1 rare inscription | yes (affixes, inBattle) |
| Reflect magic | "+N% Reflect Magic" | Sends its % of the magic damage a monster deals you back at it (its own resistance applies). | 2 magic prefixes, 2 rare prefixes, 1 rare inscription | yes (affixes, inBattle) |
| Reflect physical | "+N% Reflect Physical" | Sends its % of the physical damage a monster deals you back at it (its armor applies). | 2 magic prefixes, 2 rare prefixes, 2 magic inscriptions, 4 rare inscriptions | yes (affixes, inBattle) |
| Health regeneration | "+N% Health Regeneration" | Heals its % of your maximum health after every round (rounded up). | 2 magic prefixes, 2 magic suffixes, 3 rare prefixes, 2 rare suffixes, 2 magic inscriptions, 1 rare inscription | yes (affixes, inBattle) |
| Mana regeneration | "+N% Mana Regeneration" | Restores its % of your maximum mana after every round (rounded up). | 1 magic prefix, 1 magic suffix, 3 rare prefixes, 1 rare suffix, 3 magic inscriptions, 1 rare inscription | yes (affixes, inBattle) |
| Health bonus | "+N% Health Bonus" | Your health counts that much more: the battle screen shows it, and a hit takes that much less of it. | 1 magic suffix, 2 rare prefixes, 3 rare suffixes, 1 magic inscription, 1 rare inscription | yes (affixes, inBattle) |
| Mana bonus | "+N% Mana Bonus" | Your mana counts that much more: a skill costs that much less of it (rounded up). | 1 magic suffix, 3 rare prefixes, 1 rare inscription | yes (affixes, inBattle) |
| Stamina recovery | "+N% Chance to Recover Stamina" | Its chance that starting a quick battle (or returning to one) costs no stamina. | 1 magic suffix, 2 rare prefixes, 1 magic inscription | yes (affixes, hackSlashItemBonuses) |
| Retaliate kick | "+N% to Retaliate Kick" | Its chance to kick back (your boots' damage) a monster whose melee hit on you landed. | 2 magic suffixes, 4 rare suffixes, 1 rare inscription | yes (affixes, inBattle) |
| Retaliate smite | "+N% to Retaliate Smite (Requires Shield)" | With a shield, its chance to smite back (the shield's damage) a monster whose hit on you landed. | 2 magic suffixes, 5 rare suffixes, 1 rare inscription | yes (affixes, inBattle) |
| Armor (inscriptions) | its own line | An inscription's armor adds to the item's, on any item it can be on (rings and amulets too). | 3 magic inscriptions, 3 rare inscriptions | yes (inscriptions) |
| Block (inscriptions) | its own line | An inscription's block adds to the shield's block. | 2 magic inscriptions, 1 rare inscription | yes (inscriptions) |

### An item's own numbers

| Field | What it does | Checked in play |
|---|---|---|
| Damage | A weapon's damage is your regular attack's physical damage (two katars add up for an Assassin); boots' is your kick's, a shield's your smite's. | yes (baseStats, inBattle) |
| Throw damage | A javelin's or throwing weapon's throw damage is what your throws deal. | yes (baseStats) |
| Armor | Adds to your armor: monsters hit you less often and armor takes armor ÷ (armor + damage) × 95% off their physical hits (at most 85%). | yes (baseStats, inBattle) |
| Block | A shield's (and a Necromancer's shrunken head's) block becomes block × (dexterity − 15) ÷ (2 × level), at most 50%: a monster's physical hit is blocked under it. | yes (baseStats, inBattle) |
| Durability | Wears 1 at a time in battle; at 0 the item gives nothing until repaired. Bows, crossbows, javelins, throwing weapons, rings and amulets never wear. | yes (baseStats, battleFormulas) |
| Strength requirement | You can't equip it with less strength (your other gear and its inscriptions count, not the item's own bonus). Worn gear whose requirement you no longer meet (after an attribute reset, or taking off a +strength item) gives nothing and shows red on the equipment screen until you meet it again. | yes (hackSlashItemBonuses, baseStats) |
| Dexterity requirement | The same with dexterity. | yes (hackSlashItemBonuses, baseStats) |
| Level requirement | You can't equip it below that level (magic and rare modifiers can raise it); worn below it (levels can drop: heists, leaving the server), it gives nothing and shows red. | yes (hackSlashItemBonuses, baseStats) |
| Two handed | Equipping it takes off your shield; a shield takes it off. | yes (hackSlashInventory) |
| Stack | Shown on javelins and throwing weapons; nothing uses it up. | yes (baseStats) |
| Repair cost | A repair costs the missing durability × the item's tier (Normal 1, Exceptional 2, Elite 3) × this (only the Circlet: 1.11). | yes (battleFormulas) |
| Tier | Normal 1, Exceptional 2, Elite 3: the repair cost per point and the auction fee. | yes (battleFormulas) |
| Tier name | Normal, Exceptional or Elite. | yes (baseStats) |
| Drop level | Drops from monsters of this level and up. | yes (battleLoot) |
| Crafting scrap | The scrap crafting the item costs. | yes (hackSlashCrafting) |
| Sockets | Not used: some bases list 1–6 sockets in the data, but no item gets them and no screen shows them. | yes (baseStats) |
| Slots | Not used: belts list slots in the data, but no item gets them and no screen shows them. | yes (baseStats) |
| Name | The item's name. | yes (baseStats) |
| Family | The item's family (the crafting menu's second step). | yes (baseStats) |
| Type | Its slot, the class that can wear it, and the modifiers and inscriptions it can get. | yes (baseStats) |

### Qualities

| Quality | What it does | Checked in play |
|---|---|---|
| Low Quality | Damage and armor × 75% (rounded). | yes (baseStats) |
| Normal | The base's own damage and armor. | yes (baseStats) |
| Superior | +5–15% enhanced defense on armor, helms, shields, gloves, boots and belts; +5–15% enhanced damage on weapons. | yes (baseStats) |
| Magic | A prefix and/or a suffix from the magic modifiers. | yes (affixes) |
| Rare | A prefix and/or a suffix from the rare modifiers. | yes (affixes) |

## Weapons that skills need

A skill that needs a weapon works only with that weapon in your hand; without it, its button says **Attack** and makes the regular attack, for free.

| Weapon | Skills that need it |
|---|---|
| a bow | [Magic Arrow](skills/hunter/bow-and-crossbow-skills/magic-arrow.md) (Hunter), [Fire Arrow](skills/hunter/bow-and-crossbow-skills/fire-arrow.md) (Hunter), [Cold Arrow](skills/hunter/bow-and-crossbow-skills/cold-arrow.md) (Hunter), [Multiple Shot](skills/hunter/bow-and-crossbow-skills/multiple-shot.md) (Hunter), [Exploding Arrow](skills/hunter/bow-and-crossbow-skills/exploding-arrow.md) (Hunter), [Ice Arrow](skills/hunter/bow-and-crossbow-skills/ice-arrow.md) (Hunter), [Guided Arrow](skills/hunter/bow-and-crossbow-skills/guided-arrow.md) (Hunter), [Strafe](skills/hunter/bow-and-crossbow-skills/strafe.md) (Hunter), [Immolation Arrow](skills/hunter/bow-and-crossbow-skills/immolation-arrow.md) (Hunter), [Freezing Arrow](skills/hunter/bow-and-crossbow-skills/freezing-arrow.md) (Hunter) |
| a javelin | [Jab](skills/hunter/javelin-and-spear-skills/jab.md) (Hunter), [Power Strike](skills/hunter/javelin-and-spear-skills/power-strike.md) (Hunter), [Poison Javelin](skills/hunter/javelin-and-spear-skills/poison-javelin.md) (Hunter), [Impale](skills/hunter/javelin-and-spear-skills/impale.md) (Hunter), [Lightning Bolt](skills/hunter/javelin-and-spear-skills/lightning-bolt.md) (Hunter), [Charged Strike](skills/hunter/javelin-and-spear-skills/charged-strike.md) (Hunter), [Plague Javelin](skills/hunter/javelin-and-spear-skills/plague-javelin.md) (Hunter), [Fend](skills/hunter/javelin-and-spear-skills/fend.md) (Hunter), [Lightning Strike](skills/hunter/javelin-and-spear-skills/lightning-strike.md) (Hunter), [Lightning Fury](skills/hunter/javelin-and-spear-skills/lightning-fury.md) (Hunter) |
| a spear or javelin | [Spearman](skills/warrior/combat-masteries/spearman.md) (Warrior), [Jab](skills/hunter/javelin-and-spear-skills/jab.md) (Hunter), [Power Strike](skills/hunter/javelin-and-spear-skills/power-strike.md) (Hunter), [Impale](skills/hunter/javelin-and-spear-skills/impale.md) (Hunter), [Charged Strike](skills/hunter/javelin-and-spear-skills/charged-strike.md) (Hunter), [Fend](skills/hunter/javelin-and-spear-skills/fend.md) (Hunter), [Lightning Strike](skills/hunter/javelin-and-spear-skills/lightning-strike.md) (Hunter) |
| a throwing weapon | [Double Throw](skills/warrior/combat-skills/double-throw.md) (Warrior), [Critical Throw](skills/warrior/combat-skills/critical-throw.md) (Warrior), [Throwing Master](skills/warrior/combat-masteries/throwing-master.md) (Warrior), [Poison Javelin](skills/hunter/javelin-and-spear-skills/poison-javelin.md) (Hunter), [Lightning Bolt](skills/hunter/javelin-and-spear-skills/lightning-bolt.md) (Hunter), [Plague Javelin](skills/hunter/javelin-and-spear-skills/plague-javelin.md) (Hunter), [Lightning Fury](skills/hunter/javelin-and-spear-skills/lightning-fury.md) (Hunter) |
| a shield | [Smite](skills/paladin/battle-skills/smite.md) (Paladin), [Charge](skills/paladin/battle-skills/charge.md) (Paladin), [Holy Shield](skills/paladin/battle-skills/holy-shield.md) (Paladin), [Radiant Counter](skills/paladin/sanctified-protector/radiant-counter.md) (Paladin), [Radiant Reflection](skills/paladin/sanctified-protector/radiant-reflection.md) (Paladin), [Radiant Explosion](skills/paladin/sanctified-protector/radiant-explosion.md) (Paladin) |
| a claw | [Claw Mastery](skills/assassin/shadow-disciplines/claw-mastery.md) (Assassin), [Weapon Block](skills/assassin/shadow-disciplines/weapon-block.md) (Assassin) |
| a sword | [Swordsman](skills/warrior/combat-masteries/swordsman.md) (Warrior) |
| an axe | [Axeman](skills/warrior/combat-masteries/axeman.md) (Warrior) |
| a mace | [Maceman](skills/warrior/combat-masteries/maceman.md) (Warrior) |
| a polearm | [Polearm Master](skills/warrior/combat-masteries/polearm-master.md) (Warrior) |

