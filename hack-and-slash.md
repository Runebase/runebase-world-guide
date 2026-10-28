---
title: Hack & Slash
permalink: /hack-and-slash/
---

[← All pages]({{ '/' | relative_url }})

# Hack & Slash

The bot's role-playing game: pick a class, fight **quick battles** against monsters, bring down the **Jotnar** giants together with the server, and duel other players in the **Arena**. You learn skills, collect gear, craft items and trade them at the auction house.

**Where:** `/hackslash` opens the Hack & Slash menu (quick battles, stats, skills, the Arena), `/equipment` your gear and inventory, `/craft` crafting.

## Classes

There are 7 classes. **Each class is its own character**, with its own attributes, skills, gear, inventory and condition; switching class and back keeps everything. Your **level is your rank** in the realm, the same for every class.

A new character gets its class's attributes and its full health, mana and stamina (what the class screen shows), and its class's weapon: a Short Sword for the Warrior and the Paladin, a Javelin for the Hunter, a Short Staff for the Wizard, a Katar for the Assassin, a Wand for the Necromancer and a Club for the Druid. All but the Wizard and the Necromancer also get a Buckler.



| Class | Strength | Dexterity | Vitality | Energy | Health per vitality | Mana per energy | Stamina per vitality | A new character: health, mana, stamina |
|---|---|---|---|---|---|---|---|---|
| Warrior | 30 | 20 | 25 | 10 | 4 | 1 | 1 | 100, 10, 92 |
| Hunter | 20 | 25 | 20 | 15 | 3 | 1.5 | 1 | 60, 23, 84 |
| Wizard | 10 | 5 | 10 | 35 | 2 | 2 | 1 | 20, 70, 74 |
| Assassin | 20 | 20 | 20 | 25 | 3 | 1.75 | 1.25 | 60, 44, 95 |
| Necromancer | 15 | 25 | 15 | 25 | 2 | 2 | 1 | 30, 50, 79 |
| Paladin | 25 | 20 | 25 | 15 | 3 | 1.5 | 1 | 75, 23, 89 |
| Druid | 15 | 20 | 25 | 20 | 2 | 2 | 1 | 50, 40, 84 |



## Attributes

You get **5 attribute points per level** to spend on the stats screen (never more than you've earned).

- **Strength:** its whole value as % extra physical (and throw) damage.
- **Dexterity:** +5 attack rating a point, multiplied by your level's multiplier (below).
- **Vitality:** health (× your class's health per vitality) and stamina (+1 a point, Assassin 1.25).
- **Energy:** mana (× your class's mana per energy).
- Each level lowers your fire, cold, lightning, poison and magic resistance by 1.

**Reset:** a stats reset gives every point back, for 0.5 Grilled Coyote Steak With Lingonberry Sauce per point spent, rounded up.

## Skills

Each class has three skill trees.

- **Skill points:** one per level, and the default Throw skill holds one, so a level-3 character has 2 to spend. You can't spend more than you have, and a skill takes at most 20 points.
- A skill needs its level and the skills listed before it (the tables below).
- **Reset:** 5 Grilled Sardines with Sumac Yogurt Sauce in total, whatever the points; it leaves only the base skills.
- **Using skills:** on the battle screen you pick a main and a secondary skill; each is a button with its mana cost ("Bonk [💙2]"), charged once when used. A skill you can't use (not enough mana, not in the right shape, or without the weapon it needs, like Magic Arrow without a bow) shows as **Attack** and makes the regular attack instead, for free.
- **What a skill does at each rank is what its skill screen shows**: the battle uses the same numbers.

### Free resets at the release

Every character that existed before this release gets **one free attribute reset and one free skill reset**: the reset screen says **free**, nothing is spent, and it's used once (also on a double click). After it, resets cost their steaks and sardines again. New characters don't get them.

### How skills work in battle

| Kind | What happens (examples the tests play) |
|---|---|
| attack | hits the selected monster (Bonk adds its flat damage, then its %) |
| area | hits every monster (Cleave) |
| volley | several hits, after the first on random living monsters (Strafe rank 1: 3 arrows) |
| chain | "targets N" hits N times, hopping between monsters (Guided Arrow rank 1: 4 hits) |
| explodes | the target takes the hit and the explosion, its neighbours the explosion (Fire Ball) |
| burn, poison | ticks once a round for its rounds (Inferno "rounds 4" ticks 4 times; Fire Wall burns every monster) |
| buff | on you for its rounds (Battle Cry +35% damage, Battle Orders +40% health, Strategic Shout +40% attack rating, Cloak of Shadows dodge and avoid, War Cry parry) |
| debuff | on the monster (Amplify Damage: +15% physical damage taken; Inner Sight: −40 armor on every monster; Howl: −10% armor). Casting it again replaces it |
| aura | works while it's your main or secondary skill (Might +20% physical damage, Holy Fire burns every monster, Concentration mana steal) |
| heal | Paladin Heal: 10% of your maximum health |
| stun | a stunned monster skips its attack (Tornado; a Screech stun lasts the round; Tempest Bind for its rounds) |
| shapeshift | Werewolf and Werebear: the Druid skills that need the shape fall back to the regular attack without it |
| summon | a minion fights at your side for its rounds (Clay Golem rank 1: 275 health, 10 rounds; Raise Skeleton needs a corpse) |
| charges | every third use releases the charged effect (Tiger Strike) |
| passive | always on (some only with their weapon) |

Mirror (Warrior) copies your attack at its own damage bonus (−50% at rank 1). Paladin Cleansing removes your debuffs and heals 5%.

Every skill at rank 1 and rank 20 (mana is the cost when used):

**Warrior**



| Tree | Skill | Level | Kind | Rank 1 | Rank 20 | Needs |
|---|---|---|---|---|---|---|
| Combat Skills | Mirror | 1 | summon | damageBonus % -50, rounds 6, mana 2 | damageBonus % 45, rounds 63, mana 40 |  |
| Combat Skills | Bonk | 1 | attack | damage 1, damageBonus % 50, attackBonus % 20, mana 2 | damage 20, damageBonus % 145, attackBonus % 115, mana 2 |  |
| Combat Skills | Parry | 6 | passive | parry % 5 | parry % 24 |  |
| Combat Skills | Double Swing | 6 | explodes | damageBonus % 100, attackBonus % 15, mana 2 | damageBonus % 100, attackBonus % 110, mana 2 | Bonk |
| Combat Skills | Stun | 12 | attack | damageBonus % 5, stun % 15 | damageBonus % 100, stun % 63 | Bonk |
| Combat Skills | Double Throw | 12 | attack | damageBonus % 100, attackBonus % 15, mana 2 | damageBonus % 100, attackBonus % 110, mana 2 | a throwing weapon, Double Swing |
| Combat Skills | Strategic Strike | 18 | attack | damageBonus % 20, attackBonus % 40, mana 2 | damageBonus % 115, attackBonus % 135, mana 2 | Parry |
| Combat Skills | Wound | 18 | debuff | damage % 50, rounds 4, mana 2 | damage % 145, rounds 10, mana 2 | Stun |
| Combat Skills | Critical Throw | 24 | passive | criticalStrike % 10, attackBonus % 40 | criticalStrike % 48, attackBonus % 135 | a throwing weapon, Double Throw |
| Combat Skills | Cleave | 30 | area | damageBonus % 50, mana 2 | damageBonus % 145, mana 2 | Strategic Strike, Wound |
| Combat Skills | Concentrated Strike | 30 | attack | damageBonus % 35, criticalStrike % 2, mana 2 | damageBonus % 415, criticalStrike % 21, mana 50 | Wound |
| Warcries | Howl | 1 | area debuff | reducedArmor % 10, rounds 4 | reducedArmor % 48, rounds 12 |  |
| Warcries | Relieve | 1 | passive | heal % 10 | heal % 29 |  |
| Warcries | Strategic Shout | 6 | buff | attackBonus % 40, rounds 4 | attackBonus % 135, rounds 8 | Howl |
| Warcries | Screech | 6 | area debuff | stun % 10, rounds 4, mana 2 | stun % 48, rounds 10, mana 2 | Howl |
| Warcries | Critical Hit | 12 | passive | criticalStrike % 5 | criticalStrike % 24 | Relieve |
| Warcries | Battle Cry | 18 | buff | damageBonus % 35, rounds 4, mana 2 | damageBonus % 225, rounds 10, mana 2 | Strategic Shout |
| Warcries | Battle Orders | 24 | buff | healthBonus % 40, rounds 7, mana 2 | healthBonus % 135, rounds 45, mana 2 | Screech |
| Warcries | Healing Hit | 24 | passive | heal % 1 | heal % 11 | Critical Hit |
| Warcries | War Cry | 30 | buff | parryBonus % 30, rounds 4, mana 2 | parryBonus % 125, rounds 14, mana 2 | Battle Cry, Battle Orders |
| Warcries | Battle Command | 30 | area debuff | damage % 10, rounds 5, mana 2 | damage % 105, rounds 15, mana 2 | Battle Cry, Battle Orders |
| Combat Masteries | Swordsman | 1 | passive | damageBonus % 28, attackBonus % 40, criticalStrike % 5 | damageBonus % 123, attackBonus % 192, criticalStrike % 81 | a sword |
| Combat Masteries | Axeman | 1 | passive | damageBonus % 28, attackBonus % 40, criticalStrike % 5 | damageBonus % 123, attackBonus % 192, criticalStrike % 81 | an axe |
| Combat Masteries | Maceman | 1 | passive | damageBonus % 28, attackBonus % 40, criticalStrike % 5 | damageBonus % 123, attackBonus % 192, criticalStrike % 81 | a mace |
| Combat Masteries | Polearm Master | 6 | passive | damageBonus % 28, attackBonus % 40, criticalStrike % 5 | damageBonus % 123, attackBonus % 192, criticalStrike % 81 | a polearm |
| Combat Masteries | Throwing Master | 6 | passive | damageBonus % 28, attackBonus % 40, criticalStrike % 5 | damageBonus % 123, attackBonus % 192, criticalStrike % 81 | a throwing weapon |
| Combat Masteries | Spearman | 6 | passive | damageBonus % 28, attackBonus % 40, criticalStrike % 5 | damageBonus % 123, attackBonus % 192, criticalStrike % 81 | a spear or javelin |
| Combat Masteries | Retaliate | 12 | passive | retaliationChance % 10 | retaliationChance % 67 |  |
| Combat Masteries | Though Skin | 18 | passive | defenseBonus % 50 | defenseBonus % 145 |  |
| Combat Masteries | Critical Kick | 24 | passive | criticalStrike % 5 | criticalStrike % 24 | Retaliate |
| Combat Masteries | Resistance | 30 | passive | resistance % 2 | resistance % 40 | Though Skin |



**Hunter**



| Tree | Skill | Level | Kind | Rank 1 | Rank 20 | Needs |
|---|---|---|---|---|---|---|
| Bow and Crossbow Skills | Magic Arrow | 1 | attack | magicDamage 2-5, attackBonus % 10, damageBonus % 10, mana 2 | magicDamage 40-100, attackBonus % 181, damageBonus % 105, mana 0 | a bow |
| Bow and Crossbow Skills | Fire Arrow | 1 | attack | fireDamage 3-5, attackBonus % 10, damageBonus % 3, mana 3 | fireDamage 60-100, attackBonus % 181, damageBonus % 41, mana 3 | a bow |
| Bow and Crossbow Skills | Cold Arrow | 6 | attack | coldDamage 1-1, attackBonus % 10, damageBonus % 3, freeze % 15, rounds 2, mana 3 | coldDamage 20-20, attackBonus % 181, damageBonus % 41, freeze % 72, rounds 12, mana 3 | a bow |
| Bow and Crossbow Skills | Multiple Shot | 6 | area | damageBonus % -45, mana 2 | damageBonus % 240, mana 2 | a bow, Magic Arrow |
| Bow and Crossbow Skills | Exploding Arrow | 12 | explodes | fireDamage 10-15, damageBonus % -30, mana 2 | fireDamage 124-186, damageBonus % 122, mana 2 | a bow, Fire Arrow |
| Bow and Crossbow Skills | Ice Arrow | 18 | attack | coldDamage 6-10, attackBonus % 20, freeze % 20, rounds 2, mana 3 | coldDamage 120-124, attackBonus % 191, freeze % 77, rounds 6, mana 3 | a bow, Cold Arrow |
| Bow and Crossbow Skills | Guided Arrow | 18 | chain | targets 4, damageBonus % -18, mana 3 | targets 10, damageBonus % 115, mana 9 | a bow, Cold Arrow, Multiple Shot |
| Bow and Crossbow Skills | Strafe | 24 | attack | volley 3, damageBonus % 5, attackBonus % 30, mana 2 | volley 11, damageBonus % 100, attackBonus % 125, mana 2 | a bow, Guided Arrow |
| Bow and Crossbow Skills | Immolation Arrow | 24 | attack | fireDamage 20-20, burn 13-25, rounds 2, mana 2 | fireDamage 115-115, burn 260-272, rounds 8, mana 2 | a bow, Exploding Arrow |
| Bow and Crossbow Skills | Freezing Arrow | 30 | explodes | coldDamage 40-50, attackBonus % 40, freeze % 40, rounds 2, mana 3 | coldDamage 230-240, attackBonus % 211, freeze % 78, rounds 6, mana 3 | a bow, Guided Arrow, Ice Arrow |
| Passive and Magic Skills | Inner Sight | 1 | area debuff | reducedArmor 40, rounds 4, mana 2 | reducedArmor 325, rounds 12, mana 2 |  |
| Passive and Magic Skills | Critical Strike | 1 | passive | criticalStrike % 10 | criticalStrike % 67 |  |
| Passive and Magic Skills | Dodge | 6 | passive | dodgeChance % 5 | dodgeChance % 43 |  |
| Passive and Magic Skills | Slow Missiles | 12 | buff | reducedMissileDamage % 5, rounds 6, mana 2 | reducedMissileDamage % 43, rounds 44, mana 2 | Inner Sight |
| Passive and Magic Skills | Avoid | 12 | passive | avoidMissiles % 5 | avoidMissiles % 43 | Dodge |
| Passive and Magic Skills | Penetrate | 18 | passive | attackBonus % 35 | attackBonus % 225 | Critical Strike |
| Passive and Magic Skills | Decoy | 24 | summon | healthBonus % -30, rounds 10, mana 2 | healthBonus % 65, rounds 48, mana 2 | Slow Missiles |
| Passive and Magic Skills | Evade | 24 | passive | dodgeChance % 3, avoidMissiles % 3 | dodgeChance % 22, avoidMissiles % 22 | Avoid |
| Passive and Magic Skills | Valkyrie | 30 | summon | hp 528, damageBonus % 0, attackBonus % 40, defenseBonus % 0, rounds 6, mana 2 | hp 2200, damageBonus % 475, attackBonus % 800, defenseBonus % 190, rounds 44, mana 40 | Evade, Decoy |
| Passive and Magic Skills | Pierce | 30 | passive | pierce % 20 | pierce % 58 | Penetrate |
| Javelin and Spear Skills | Jab | 1 | attack | volley 3, damageBonus % -15, attackBonus % 10, mana 2 | volley 3, damageBonus % 42, attackBonus % 181, mana 40 | a javelin, a spear or javelin |
| Javelin and Spear Skills | Power Strike | 6 | attack | lightningDamage 1-16, attackBonus % 20, mana 2 | lightningDamage 1-358, attackBonus % 248, mana 40 | a javelin, a spear or javelin, Jab |
| Javelin and Spear Skills | Poison Javelin | 6 | attack | poisonDamage 25-37, mana 2 | poisonDamage 424-512, mana 40 | a javelin, a throwing weapon |
| Javelin and Spear Skills | Impale | 12 | attack | damageBonus % 300, criticalStrike % 5, mana 2 | damageBonus % 775, criticalStrike % 43, mana 40 | a javelin, a spear or javelin, Jab |
| Javelin and Spear Skills | Lightning Bolt | 12 | attack | lightningDamage 1-40, mana 2 | lightningDamage 1-610, mana 40 | a javelin, a throwing weapon, Poison Javelin |
| Javelin and Spear Skills | Charged Strike | 18 | explodes | lightningDamage 1-30, mana 2 | lightningDamage 1-334, mana 40 | a javelin, a spear or javelin, Lightning Bolt, Power Strike |
| Javelin and Spear Skills | Plague Javelin | 18 | explodes | poisonDamage 23-37, attackBonus % 30, mana 2 | poisonDamage 384-455, attackBonus % 201, mana 40 | a javelin, a throwing weapon, Lightning Bolt |
| Javelin and Spear Skills | Fend | 24 | area | damageBonus % 70, attackBonus % 40, mana 2 | damageBonus % 260, attackBonus % 230, mana 40 | a javelin, a spear or javelin, Impale |
| Javelin and Spear Skills | Lightning Strike | 30 | chain | targets 2, lightningDamage 1-25, mana 2 | targets 10, lightningDamage 1-310, mana 40 | a javelin, a spear or javelin, Charged Strike |
| Javelin and Spear Skills | Lightning Fury | 30 | area | lightningDamage 1-60, mana 2 | lightningDamage 1-725, mana 40 | a javelin, a throwing weapon, Plague Javelin |



**Wizard**



| Tree | Skill | Level | Kind | Rank 1 | Rank 20 | Needs |
|---|---|---|---|---|---|---|
| Fire Spells | Fire Bolt | 1 | attack, spell | fireDamage 4-7, mana 2 | fireDamage 61-121, mana 21 |  |
| Fire Spells | Warmth | 1 | passive | manaRegen % 2 | manaRegen % 24.8 |  |
| Fire Spells | Inferno | 6 | attack, spell | burn 13-25, rounds 4, mana 2 | burn 260-272, rounds 14, mana 21 |  |
| Fire Spells | Blaze | 12 | buff, spell | fireDamageBonus % 15, rounds 4, mana 2 | fireDamageBonus % 72, rounds 23, mana 21 | Inferno |
| Fire Spells | Fire Ball | 12 | explodes, spell | fireDamage 6-15, mana 2 | fireDamage 101-243, mana 21 | Fire Bolt |
| Fire Spells | Fire Wall | 18 | area debuff, spell | burn 10-12, rounds 10, mana 2 | burn 181-202, rounds 48, mana 21 | Blaze |
| Fire Spells | Enchant | 18 | buff | fireDamageOnWeapon 6-15, rounds 10, mana 2 | fireDamageOnWeapon 101-243, rounds 105, mana 21 | Warmth, Fire Ball |
| Fire Spells | Meteor | 24 | explodes, spell | fireDamage 88-110, stun % 10, burn 25-48, rounds 2, mana 2 | fireDamage 563-623, stun % 10, burn 310-333, rounds 6, mana 40 | Fire Ball, Fire Wall |
| Fire Spells | Fire Mastery | 30 | passive | fireDamageBonus % 30 | fireDamageBonus % 163 |  |
| Fire Spells | Hydra | 30 | summon | fireDamage 14-19, rounds 10, mana 2 | fireDamage 128-171, rounds 29, mana 21 | Enchant |
| Lightning Spells | Charged Bolt | 1 | area, spell | lightningDamage 1-12, mana 2 | lightningDamage 1-240, mana 21 |  |
| Lightning Spells | Static Field | 1 | area debuff, spell | lightningDamage 1-30, stun % 50, rounds 3, mana 2 | lightningDamage 1-315, stun % 88, rounds 3, mana 21 |  |
| Lightning Spells | Telekinesis | 6 | passive | manaBonus % 4 | manaBonus % 80 |  |
| Lightning Spells | Nova | 12 | area, spell | lightningDamage 1-30, stun % 2, mana 2 | lightningDamage 1-505, stun % 40, mana 21 | Static Field |
| Lightning Spells | Lightning | 12 | attack, spell | lightningDamage 1-43, mana 2 | lightningDamage 1-423, mana 21 | Charged Bolt |
| Lightning Spells | Chain Lightning | 18 | chain, spell | lightningDamage 1-35, targets 5, mana 3 | lightningDamage 1-415, targets 24, mana 22 | Lightning |
| Lightning Spells | Teleport | 18 | passive | decreaseStaminaCost 1 | decreaseStaminaCost 10 | Telekinesis |
| Lightning Spells | Thunder Storm | 24 | buff, spell | lightningDamage 1-30, stun % 3, procChance 35, rounds 15, mana 2 | lightningDamage 1-505, stun % 18, procChance 92, rounds 72, mana 21 | Nova, Chain Lightning |
| Lightning Spells | Energy Shield | 24 | buff, spell | manaShield % 20, rounds 10, mana 5 | manaShield % 100, rounds 48, mana 24 | Chain Lightning, Teleport |
| Lightning Spells | Lightning Mastery | 30 | passive | lightningDamageBonus % 30 | lightningDamageBonus % 163 |  |
| Cold Spells | Ice Bolt | 1 | attack, spell | coldDamage 3-6, mana 2 | coldDamage 79-120, mana 2 |  |
| Cold Spells | Frozen Armor | 1 | buff, spell | defenseBonus % 50, rounds 20, mana 2 | defenseBonus % 145, rounds 115, mana 21 |  |
| Cold Spells | Frost Nova | 6 | area, spell | coldDamage 1-2, freeze % 20, rounds 2, mana 3 | coldDamage 39-59, freeze % 77, rounds 2, mana 22 |  |
| Cold Spells | Ice Blast | 6 | attack, spell | coldDamage 8-12, freeze % 20, rounds 2, mana 3 | coldDamage 198-278, freeze % 96, rounds 4, mana 22 | Ice Bolt |
| Cold Spells | Shiver Armor | 12 | buff, spell | defenseBonus % 15, coldDamage 4-10, freeze % 5, defenseAttackDebuffRounds 2, rounds 30, mana 2 | defenseBonus % 129, coldDamage 80-200, freeze % 9, defenseAttackDebuffRounds 6, rounds 125, mana 21 | Frozen Armor, Ice Blast |
| Cold Spells | Glacial Spike | 18 | explodes, spell | coldDamage 17-26, freeze % 20, rounds 2, mana 3 | coldDamage 264-349, freeze % 96, rounds 4, mana 22 | Ice Blast |
| Cold Spells | Blizzard | 24 | area, spell | coldDamage 51-86, freeze % 20, rounds 2, mana 3 | coldDamage 621-694, freeze % 96, rounds 4, mana 22 | Frost Nova, Glacial Spike |
| Cold Spells | Chilling Armor | 24 | buff, spell | defenseBonus % 15, attack Ice Blast, procChance 25, rounds 20, mana 2 | defenseBonus % 129, attack Ice Blast, procChance 82, rounds 115, mana 21 | Shiver Armor |
| Cold Spells | Frozen Orb | 30 | chain, spell | coldDamage 51-86, freeze % 5, targets 3, rounds 2, mana 3 | coldDamage 621-694, freeze % 24, targets 6, rounds 4, mana 22 | Blizzard |
| Cold Spells | Cold Mastery | 30 | passive | coldDamageBonus % 30 | coldDamageBonus % 163 |  |



**Assassin**



| Tree | Skill | Level | Kind | Rank 1 | Rank 20 | Needs |
|---|---|---|---|---|---|---|
| Martial Arts | Tiger Strike | 1 | attack | attackBonus % 25, damageBonus % 100, mana 2 | attackBonus % 215, damageBonus % 480, mana 2 |  |
| Martial Arts | Dragon Talon | 1 | passive | attackBonus % 20, repeatingAttack 0 | attackBonus % 400, repeatingAttack 3 |  |
| Martial Arts | Fists of Fire | 6 | attack | fireDamage 6-10, burn 9-15, rounds 3, mana 2 | fireDamage 101-105, burn 161-167, rounds 7, mana 2 |  |
| Martial Arts | Dragon Claw | 6 | passive | damageBonus % 10 | damageBonus % 105 | Dragon Talon |
| Martial Arts | Cobra Strike | 12 | attack | attackBonus % 25, lifeSteal % 40, manaSteal % 40, mana 2 | attackBonus % 215, lifeSteal % 135, manaSteal % 135, mana 2 | Tiger Strike |
| Martial Arts | Claws of Thunder | 18 | attack | attackBonus % 25, lightningDamage 1-80, targets 3, mana 2 | attackBonus % 215, lightningDamage 1-460, targets 9, mana 2 | Fists of Fire |
| Martial Arts | Dragon Tail | 18 | chain | damageBonus % 85, targets 2, mana 2 | damageBonus % 465, targets 4, mana 21 | Dragon Claw |
| Martial Arts | Blades of Ice | 24 | attack | attackBonus % 25, coldDamage 15-35, freeze % 20, rounds 2, mana 2 | attackBonus % 215, coldDamage 205-225, freeze % 58, rounds 6, mana 2 | Claws of Thunder |
| Martial Arts | Dragon Flight | 24 | passive | fireDamage 22-44 | fireDamage 231-253 | Dragon Tail |
| Martial Arts | Phoenix Strike | 30 | attack | attackBonus % 25, coldDamage 17-35, fireDamage 22-44, lightningDamage 1-45, mana 2 | attackBonus % 215, coldDamage 169-187, fireDamage 231-253, lightningDamage 1-330, mana 2 | Cobra Strike, Blades of Ice |
| Shadow Disciplines | Claw Mastery | 1 | passive | attackBonus % 30, damageBonus % 35, criticalStrike % 3 | attackBonus % 220, damageBonus % 111, criticalStrike % 60 | a claw |
| Shadow Disciplines | Psychic Hammer | 1 | debuff | reducedArmor % 20, stun % 100, rounds 2 | reducedArmor % 77, stun % 100, rounds 4 |  |
| Shadow Disciplines | Burst of Speed | 6 | area | damageBonus % -50, attackBonus % 10 | damageBonus % 140, attackBonus % 200 | Claw Mastery |
| Shadow Disciplines | Weapon Block | 12 | passive | blockChance % 15 | blockChance % 62.5 | a claw, Claw Mastery |
| Shadow Disciplines | Cloak of Shadows | 12 | buff | dodgeChance % 10, avoidMissiles % 10, rounds 15, mana 2 | dodgeChance % 57.5, avoidMissiles % 57.5, rounds 110, mana 2 | Psychic Hammer |
| Shadow Disciplines | Fade | 18 | buff, spell | allResistance % 2, rounds 15, mana 2 | allResistance % 40, rounds 110, mana 2 | Burst of Speed |
| Shadow Disciplines | Shadow Warrior | 18 | summon | hp 376, defenseBonus % 0, rounds 6, mana 2 | hp 1421, defenseBonus % 228, rounds 44, mana 40 | Weapon Block, Cloak of Shadows |
| Shadow Disciplines | Mind Blast | 24 | area debuff, spell | confusion % 5, rounds 6, mana 2 | confusion % 24, rounds 44, mana 40 | Cloak of Shadows |
| Shadow Disciplines | Venom | 30 | passive | poisonDamage 60-80 | poisonDamage 345-365 | Fade |
| Shadow Disciplines | Shadow Master | 30 | passive | damageBonus % 20, rounds 2 | damageBonus % 210, rounds 40 | Shadow Warrior |
| Traps | Fire Blast | 1 | explodes, spell | fireDamage 3-4, mana 2 | fireDamage 79-80, mana 2 |  |
| Traps | Shock Web | 6 | area, spell | lightningDamage 1-10, mana 2 | lightningDamage 1-143, mana 2 | Fire Blast |
| Traps | Blade Sentinel | 6 | attack, spell | physicalDamage 6-10, volley 3, mana 2 | physicalDamage 82-86, volley 9, mana 2 |  |
| Traps | Charged Bolt Sentry | 12 | summon, spell | lightningDamage 1-7, rounds 4, mana 2 | lightningDamage 1-121, rounds 42, mana 2 | Shock Web |
| Traps | Wake of Fire | 12 | summon, spell | fireDamage 5-10, rounds 4, mana 2 | fireDamage 81-105, rounds 42, mana 2 | Fire Blast |
| Traps | Blade Fury | 18 | area, spell | physicalDamage 11-15, mana 2 | physicalDamage 125-148, mana 2 | Blade Sentinel, Wake of Fire |
| Traps | Lightning Sentry | 24 | summon, spell | lightningDamage 1-24, rounds 4, mana 2 | lightningDamage 1-309, rounds 42, mana 2 | Charged Bolt Sentry |
| Traps | Wake of Inferno | 24 | summon, spell | burn 12-30, rounds 4, mana 2 | burn 221-239, rounds 42, mana 2 | Wake of Fire |
| Traps | Death Sentry | 30 | summon, spell | lightningDamage 1-56, targets 2, rounds 4, mana 2 | lightningDamage 1-531, targets 8, rounds 42, mana 2 | Lightning Sentry |
| Traps | Blade Shield | 30 | buff, spell | defenseBonus % 1, physicalDamage 1-30, procChance 100, rounds 15, mana 2 | defenseBonus % 20, physicalDamage 58-315, procChance 100, rounds 72, mana 2 | Blade Fury |



**Necromancer**



| Tree | Skill | Level | Kind | Rank 1 | Rank 20 | Needs |
|---|---|---|---|---|---|---|
| Summoning Spells | Raise Skeleton | 1 | summon, spell | hp 35, defense 30, maxRaised 1, physicalDamage 3-5, rounds 30, mana 2 | hp 510, defense 410, maxRaised 6, physicalDamage 60-100, rounds 68, mana 40 | a corpse |
| Summoning Spells | Skeleton Mastery | 1 | passive | healthBonus % 2.5, rounds 2 | healthBonus % 50, rounds 21 | Raise Skeleton |
| Summoning Spells | Clay Golem | 6 | summon, spell | hp 275, physicalDamage 4-9, attackBonus % 40, rounds 10, mana 2 | hp 2175, physicalDamage 42-85, attackBonus % 800, rounds 67, mana 40 |  |
| Summoning Spells | Golem Mastery | 12 | passive | healthBonus % 2.5, rounds 3 | healthBonus % 50, rounds 60 | Clay Golem |
| Summoning Spells | Raise Skeletal Mage | 12 | summon, spell | hp 80, defense 10, maxRaised 1, rounds 30, mana 2 | hp 555, defense 200, maxRaised 6, rounds 68, mana 40 | a corpse, Raise Skeleton |
| Summoning Spells | Blood Golem | 18 | summon, spell | hp 637, physicalDamage 12-33, lifeSteal % 25, rounds 6, mana 2 | hp 3240, physicalDamage 145-318, lifeSteal % 44, rounds 44, mana 40 | Clay Golem |
| Summoning Spells | Summon Resist | 24 | passive | allResistance % 15 | allResistance % 53 | Golem Mastery |
| Summoning Spells | Iron Golem | 24 | summon, spell | hp 1000, physicalDamage 4-5, defenseBonus % 0, rounds 20, mana 2 | hp 10500, physicalDamage 80-100, defenseBonus % 380, rounds 210, mana 40 | Blood Golem |
| Summoning Spells | Fire Golem | 30 | summon, spell | hp 1013, fireDamage 52-128, rounds 6, mana 2 | hp 3236, fireDamage 527-603, rounds 44, mana 40 | Iron Golem |
| Summoning Spells | Revive | 30 | summon, spell | damageBonus % 15, maxRaised 4, rounds 10, mana 2 | damageBonus % 300, maxRaised 6, rounds 48, mana 40 | a corpse, Iron Golem, Raise Skeletal Mage |
| Poison and Bone Spells | Teeth | 1 | area, spell | magicDamage 3-5, mana 2 | magicDamage 41-62, mana 2 |  |
| Poison and Bone Spells | Bone Armor | 1 | buff, spell | physicalDamageShield 30, rounds 5, mana 2 | physicalDamageShield 315, rounds 43, mana 2 |  |
| Poison and Bone Spells | Poison Dagger | 6 | passive | poisonDamage 7-15 | poisonDamage 121-167 |  |
| Poison and Bone Spells | Corpse Explosion | 6 | attack, spell | corpseExplosion % 30, mana 2 | corpseExplosion % 125, mana 2 | a corpse, Teeth |
| Poison and Bone Spells | Bone Wall | 12 | passive | magicalDamageShield 30 | magicalDamageShield 315 | Bone Armor |
| Poison and Bone Spells | Poison Explosion | 18 | explodes, spell | poisonDamage 15-42, rounds 3, mana 2 | poisonDamage 167-365, rounds 5, mana 2 | Poison Dagger, Corpse Explosion |
| Poison and Bone Spells | Bone Spear | 18 | attack, spell | magicDamage 20-40, mana 2 | magicDamage 210-420, mana 2 | Corpse Explosion |
| Poison and Bone Spells | Bone Prison | 24 | passive | magicDamage 15-25 | magicDamage 148-310 | Bone Wall, Bone Spear |
| Poison and Bone Spells | Poison Nova | 30 | area, spell | poisonDamage 35-62, rounds 3, mana 2 | poisonDamage 377-632, rounds 5, mana 2 | Poison Explosion |
| Poison and Bone Spells | Bone Spirit | 30 | chain, spell | magicDamage 20-40, targets 2, mana 2 | magicDamage 210-420, targets 7, mana 2 | Bone Spear |
| Curses | Dim Vision | 1 | area debuff, spell | decreaseMagicResistance % 15, rounds 10, mana 2 | decreaseMagicResistance % 110, rounds 105, mana 2 |  |
| Curses | Amplify Damage | 1 | area debuff, spell | increasePhysicalDamageTaken % 15, rounds 10, mana 2 | increasePhysicalDamageTaken % 110, rounds 105, mana 2 |  |
| Curses | Weaken | 6 | area debuff, spell | decreaseDamageDealt % 10, rounds 10, mana 2 | decreaseDamageDealt % 48, rounds 105, mana 2 | Amplify Damage |
| Curses | Iron Maiden | 12 | area debuff, spell | reflectPhysicalDamage % 100, rounds 10, mana 2 | reflectPhysicalDamage % 290, rounds 105, mana 2 | Amplify Damage |
| Curses | Terror | 12 | area debuff, spell | stun % 10, rounds 10, mana 2 | stun % 48, rounds 105, mana 2 | Weaken |
| Curses | Confuse | 18 | area debuff, spell | confusion % 10, rounds 10, mana 2 | confusion % 48, rounds 105, mana 2 | Dim Vision |
| Curses | Life Tap | 18 | area debuff, spell | lifeTap % 10, rounds 10, mana 2 | lifeTap % 48, rounds 105, mana 2 | Iron Maiden |
| Curses | Attract | 24 | area debuff, spell | attractToMinions % 1, rounds 10, mana 2 | attractToMinions % 20, rounds 105, mana 2 | Confuse |
| Curses | Decrepify | 24 | area debuff, spell | decreaseDefense % 5, stun % 2, rounds 10, mana 2 | decreaseDefense % 62, stun % 12, rounds 105, mana 2 | Terror |
| Curses | Lower Resist | 30 | area debuff, spell | lowerAllResistance % 10, rounds 10, mana 2 | lowerAllResistance % 48, rounds 105, mana 2 | Life Tap, Decrepify |



**Paladin**



| Tree | Skill | Level | Kind | Rank 1 | Rank 20 | Needs |
|---|---|---|---|---|---|---|
| Battle Skills | Sacrifice | 1 | attack | attackBonus % 20, damageBonus % 180, damageToSelf % 7 | attackBonus % 400, damageBonus % 560, damageToSelf % 1.02 |  |
| Battle Skills | Smite | 1 | attack | damageBonus % 30, stun % 5, mana 2 | damageBonus % 600, stun % 72, mana 21 | a shield |
| Battle Skills | Holy Bolt | 6 | attack, spell | magicDamage 10-10, mana 2 | magicDamage 200-200, mana 2 |  |
| Battle Skills | Zeal | 12 | attack | attackBonus % 10, damageBonus % 6, targets 1, mana 2 | attackBonus % 200, damageBonus % 120, targets 4, mana 21 | Sacrifice |
| Battle Skills | Charge | 12 | explodes | damageBonus % 100, mana 2 | damageBonus % 860, mana 40 | a shield, Smite |
| Battle Skills | Vengeance | 18 | explodes | lightningDamage 1-15, fireDamage 6-12, coldDamage 6-12, mana 2 | lightningDamage 1-148, fireDamage 82-183, coldDamage 82-183, mana 21 | Zeal |
| Battle Skills | Blessed Hammer | 18 | chain, spell | magicDamage 20-30, stun % 15, targets 1, mana 2 | magicDamage 210-315, stun % 53, targets 3, mana 40 | Holy Bolt |
| Battle Skills | Conversion | 24 | attack | conversionChance % 1, maxRaised 1, rounds 10, mana 2 | conversionChance % 4.8, maxRaised 3, rounds 48, mana 2 | Vengeance |
| Battle Skills | Holy Shield | 24 | buff, spell | defenseBonus % 25, blockBonus % 15, smiteDamage 3-6, rounds 10, mana 2 | defenseBonus % 500, blockBonus % 34, smiteDamage 41-101, rounds 105, mana 40 | a shield, Charge, Blessed Hammer |
| Battle Skills | Fist of the Heavens | 30 | chain, spell | lightningDamage 1-60, targets 2, mana 2 | lightningDamage 1-630, targets 6, mana 40 | Conversion, Blessed Hammer |
| Sanctified Protector | Prayer | 1 | buff, spell | healthRegen % 1, rounds 2, mana 2 | healthRegen % 5.75, rounds 13, mana 21 |  |
| Sanctified Protector | Radiant Counter | 1 | passive | retaliationChance % 10 | retaliationChance % 48 | a shield |
| Sanctified Protector | Defiance | 6 | passive | defenseBonus % 50 | defenseBonus % 145 |  |
| Sanctified Protector | Radiant Reflection | 6 | passive | magicDamage 8-15 | magicDamage 84-167 | a shield, Radiant Counter |
| Sanctified Protector | Heal | 12 | heal, spell | heal % 10, mana 2 | heal % 17, mana 40 | Prayer |
| Sanctified Protector | Radiant Explosion | 12 | passive | magicDamage 8-15 | magicDamage 84-167 | a shield, Radiant Reflection |
| Sanctified Protector | Summon Divine Protector | 18 | summon, spell | physicalDamage 3-5, hp 750, maxRaised 2, rounds 15, mana 2 | physicalDamage 22-195, hp 10250, maxRaised 2, rounds 72, mana 40 | Defiance, Heal |
| Sanctified Protector | Cleansing | 24 | heal, spell | heal % 5, mana 3 | heal % 15, mana 22 | Heal |
| Sanctified Protector | Sanctified Divine Ward | 30 | passive | hp 150, stun % 3, rounds 4 | hp 3000, stun % 7, rounds 10 | Summon Divine Protector |
| Sanctified Protector | Salvation | 30 | passive | manaBonus % 2 | manaBonus % 40 |  |
| Auras | Might | 1 | aura | physicalDamageBonus % 20 | physicalDamageBonus % 305 |  |
| Auras | Holy Fire | 6 | aura, spell | fireDamage 6-10 | fireDamage 120-200 | Might |
| Auras | Thorns | 6 | aura | reflectPhysicalDamage % 25 | reflectPhysicalDamage % 215 |  |
| Auras | Blessed Aim | 12 | aura | attackBonus % 25 | attackBonus % 215 | Might |
| Auras | Concentration | 18 | aura | manaSteal % 3 | manaSteal % 41 | Blessed Aim |
| Auras | Holy Freeze | 18 | aura, spell | freeze % 10 | freeze % 48 | Holy Fire |
| Auras | Holy Shock | 24 | aura, spell | lightningDamage 1-30 | lightningDamage 1-410 | Holy Freeze |
| Auras | Sanctuary | 24 | aura, spell | healthBonus % 10 | healthBonus % 105 | Holy Freeze |
| Auras | Fanaticism | 30 | aura | pierce % 3 | pierce % 41 | Concentration |
| Auras | Conviction | 30 | aura, spell | lowerAllResistance % 5 | lowerAllResistance % 53 | Sanctuary |



**Druid**



| Tree | Skill | Level | Kind | Rank 1 | Rank 20 | Needs |
|---|---|---|---|---|---|---|
| Elemental Skills | Tempest Bind | 1 | debuff, spell | stun % 100, rounds 1, mana 3 | stun % 100, rounds 3, mana 3 |  |
| Elemental Skills | Firestorm | 1 | area, spell | fireDamage 3-6, mana 2 | fireDamage 60-120, mana 2 |  |
| Elemental Skills | Molten Boulder | 6 | explodes, spell | fireDamage 6-15, mana 2 | fireDamage 101-243, mana 2 | Firestorm |
| Elemental Skills | Arctic Blast | 6 | explodes, spell | coldDamage 5-10, freeze % 15, rounds 2, mana 3 | coldDamage 119-162, freeze % 63, rounds 4, mana 3 |  |
| Elemental Skills | Fissure | 12 | attack, spell | fireDamage 25-35, mana 2 | fireDamage 329-434, mana 40 | Molten Boulder |
| Elemental Skills | Cyclone Armor | 12 | buff, spell | magicalDamageShield 35, physicalDamage 10-15, procChance 100, rounds 15, mana 2 | magicalDamageShield 320, physicalDamage 143-224, procChance 100, rounds 72, mana 2 | Arctic Blast |
| Elemental Skills | Twister | 18 | chain, spell | physicalDamage 25-30, stun % 35, targets 2, mana 2 | physicalDamage 253-391, stun % 54, targets 5, mana 2 | Cyclone Armor |
| Elemental Skills | Volcano | 24 | explodes, spell | fireDamage 25-35, stun % 10, mana 2 | fireDamage 329-434, stun % 67, mana 40 | Fissure |
| Elemental Skills | Tornado | 24 | attack, spell | physicalDamage 51-73, stun % 100, mana 2 | physicalDamage 526-738, stun % 100, mana 40 | Twister |
| Elemental Skills | Armageddon | 30 | area, spell | fireDamage 88-110, stun % 10, burn 25-48, rounds 2, mana 2 | fireDamage 563-623, stun % 48, burn 310-333, rounds 6, mana 40 | Volcano, Hurricane |
| Elemental Skills | Hurricane | 30 | buff, spell | physicalDamage 23-30, stun % 3, rounds 15, mana 2 | physicalDamage 308-391, stun % 18, rounds 72, mana 2 | Tornado |
| Shape Shifting Skills | Werewolf | 1 | shapeshift buff, spell | pierce % 6, attackBonus % 10, rounds 10, mana 2 | pierce % 25, attackBonus % 200, rounds 105, mana 2 |  |
| Shape Shifting Skills | Lycanthropy | 1 | passive | healthBonus % 5, rounds 5, mana 2 | healthBonus % 62, rounds 62, mana 2 | Werewolf |
| Shape Shifting Skills | Werebear | 6 | shapeshift buff, spell | defenseBonus % 20, damageBonus % 3, healthBonus % 10, rounds 10, mana 2 | defenseBonus % 210, damageBonus % 60, healthBonus % 105, rounds 105, mana 2 |  |
| Shape Shifting Skills | Feral Rage | 12 | attack | damageBonus % 30, lifeSteal % 10, mana 2 | damageBonus % 410, lifeSteal % 105, mana 2 | Werewolf |
| Shape Shifting Skills | Maul | 12 | area | damageBonus % 5, mana 2 | damageBonus % 100, mana 2 | Werebear |
| Shape Shifting Skills | Rabies | 18 | attack | poisonDamage 15-23, rounds 3, mana 2 | poisonDamage 148-346, rounds 7, mana 2 | Feral Rage |
| Shape Shifting Skills | Fire Claws | 18 | explodes | damageBonus % 10, fireDamage 19-35, mana 2 | damageBonus % 105, fireDamage 209-320, mana 2 | Feral Rage, Maul |
| Shape Shifting Skills | Hunger | 24 | attack | lifeSteal % 50, manaSteal % 50, attackBonus % 50, mana 2 | lifeSteal % 335, manaSteal % 335, attackBonus % 240, mana 40 | Fire Claws |
| Shape Shifting Skills | Shock Wave | 24 | area, spell | physicalDamage 25-33, stun % 30, mana 2 | physicalDamage 367-470, stun % 49, mana 40 | Maul |
| Shape Shifting Skills | Fury | 30 | chain | targets 2, damageBonus % 0, mana 3 | targets 8, damageBonus % 285, mana 9 | Rabies |
| Summoning Skills | Raven | 1 | summon, spell | physicalDamage 2-3, maxRaised 1, rounds 15, mana 2 | physicalDamage 40-60, maxRaised 3, rounds 72, mana 2 |  |
| Summoning Skills | Poison Creeper | 1 | summon, spell | poisonDamage 2-4, hp 50, rounds 15, mana 2 | poisonDamage 40-80, hp 1000, rounds 72, mana 2 |  |
| Summoning Skills | Oak Sage | 6 | summon, spell | healthBonus % 10, hp 75, rounds 15, mana 2 | healthBonus % 200, hp 1500, rounds 72, mana 2 |  |
| Summoning Skills | Summon Spirit Wolf | 6 | summon, spell | physicalDamage 5-10, hp 150, maxRaised 2, rounds 15, mana 2 | physicalDamage 62-162, hp 1100, maxRaised 6, rounds 72, mana 2 | Raven |
| Summoning Skills | Carrion Vine | 12 | passive | poisonDamage 6-10 | poisonDamage 101-162 | Poison Creeper |
| Summoning Skills | Heart of Wolverine | 18 | passive | lifeSteal % 5 | lifeSteal % 62 | Oak Sage |
| Summoning Skills | Summon Dire Wolf | 18 | passive | damageBonus % 25, pierce % 1, hp 75, rounds 3 | damageBonus % 310, pierce % 20, hp 1500, rounds 60 | Oak Sage, Summon Spirit Wolf |
| Summoning Skills | Solar Creeper | 24 | passive | hp 100, rounds 5, explosiveAttack % 15 | hp 2000, rounds 100, explosiveAttack % 43.5 | Carrion Vine |
| Summoning Skills | Spirit of Barbs | 30 | passive | damageBonus % 5 | damageBonus % 100 | Heart of Wolverine |
| Summoning Skills | Summon Grizzly | 30 | summon, spell | physicalDamage 25-40, stun % 5, hp 1500, rounds 15, mana 2 | physicalDamage 215-458, stun % 24, hp 4350, rounds 72, mana 2 | Summon Dire Wolf |



## Quick battles

`/hackslash` → **Quick Battle**: pick the zone (Shadowed Caverns, Twilight Forest, Frozen Tundra), the monster level and the difficulty, then **Start QuickBattle**.

- **Monster level:** 1 to 100, 25 levels a page; the menu opens on your own level. Levels more than 5 below yours say **(No Experience)**: those monsters pay no experience.
- **Difficulty:** ×1 to ×6.75, in steps of 0.25. It multiplies the monsters' health, armor, damage and attack rating, adds the multiplier minus 1 (rounded) to their block, and makes items a little likelier (below).
- **The monsters:** a battle has **2 to 5** of them, of the zone and level you picked. Each is the zone's usual monster unless it rolls one of the others, at the chances the setup screen shows. The rare ones (Werewolf, Werebear, Yeti) come 2% of the time each and are worth 5 experience.
- **A quick battle costs 20 stamina** (less with the Wizard's Teleport). Pressed twice with stamina for one battle, it starts one battle and takes the stamina once.
- **Out of stamina:** **Restore Stamina now** spends one **Pheasant with Blackberry Balsamic Glaze** and fills your stamina to its maximum.
- Each click of a skill button is one round: you attack, then the monsters attack you (a stunned monster skips its attack).
- **Dying:** a dead character can't start a new battle (nothing is charged). Heal with one **Anchovy with Anchovy Powder** (health and mana back to full), then **Return to QuickBattle** (5 stamina) to finish the same battle.
- **Before a battle**, or on the results screen for the next one, you can pick **Elk with Huckleberry Sauce** (double damage) and **Baked Cod with Old Bay Butter** (+25% experience); each is spent once.

**A won battle pays once:**

- **Experience:** 2 per monster, 5 for a rare one, +25% with Baked Cod. A monster more than 5 levels below you gives nothing.
- The quick battle leaderboards count the win.
- A roll on the battle prize table (credits go to your wallet).
- Items the monsters drop: each monster rolls once for an item, at the quality chances its setup screen shows (table below); loot each one once into your inventory. The Arcane Reliquary raises the Magic and Rare chances.
- Dying pays nothing; a battle left unfinished pays nothing, and starting another doesn't pay for it. Clicking the last attack twice, showing the results again or reopening an old battle pays nothing more.



| Prize | Chance per won battle |
|---|---|
| 0.1 to 10 credits | 6.5% |
| 1 Runes Pattern Card | 0.3% |
| 1 Chaos Relic | 0.3% |
| 1 Leather Scrap | 0.5% |
| 1 Metal Scrap | 0.5% |
| 1 Wood Scrap | 0.5% |
| 1 Nail | 3% |
| 1 Rope | 0.5% |
| 1 Engraving Tool | 8% |
| nothing | 79.9% |



Which monsters spawn, at level 1 (the same at every level):



| Zone | Monster | Spawns | Experience |
|---|---|---|---|
| Shadowed Caverns | Zombie | the rest (40%) | 2 |
| Shadowed Caverns | Stormclaw | 30% | 2 |
| Shadowed Caverns | Flamecaster | 30% | 2 |
| Twilight Forest | Wolf | the rest (36%) | 2 |
| Twilight Forest | Bear | 30% | 2 |
| Twilight Forest | Snake | 30% | 2 |
| Twilight Forest | Werewolf | 2% | 5 |
| Twilight Forest | Werebear | 2% | 5 |
| Frozen Tundra | Frozen Wolf | the rest (38%) | 2 |
| Frozen Tundra | Yeti | 2% | 5 |
| Frozen Tundra | Ice Elemental | 15% | 2 |
| Frozen Tundra | Frost Wraith | 15% | 2 |
| Frozen Tundra | Frost Troll | 15% | 2 |
| Frozen Tundra | Artic Fox | 15% | 2 |



The item each monster rolls for:



| Item quality | A monster at ×1 | A monster at ×6.75 | A rare monster at ×1 |
|---|---|---|---|
| Low Quality | 0.5% | 0.443% | 0.35% |
| Superior | 0.5% | 0.787% | 1.5% |
| Rare | 0.5% | 1.08% | 33% |
| Magic | 8% | 11.45% | 20% |
| Normal | 25% | 29.03% | 10% |
| no item | 65.5% | 57.22% | 35.15% |



### Hitting and missing

Physical attacks can miss. Your **hit chance** is 200% × your attack rating ÷ (your attack rating + the monster's armor) × your level ÷ (your level + the monster's level), kept between 5% and 95%. A level-1 Warrior (attack rating 91) hits a level-1 Flamecaster (armor 55) 62.3% of the time.

- **Your attack rating grows with your level:** your class's 50 plus 5 per dexterity point, times your level's multiplier; attack rating from gear is added on top.
- Skills and buffs with attack rating % raise it (Strategic Shout's +40% takes that 62.3% to 69.8%).
- **Monsters block** your physical attacks as often as their screen shows (a Zombie 10%).
- **Spells never miss:** only physical attacks roll to hit. Magic, Fire, Cold, Lightning and Poison attacks always land, yours and the monsters'.
- A single-target attack can only miss its own target. Monsters miss you too.



| Level | 1 | 5 | 10 | 20 | 25 | 26 | 30 | 40 | 50 | 75 | 100 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| × attack rating | 1.82 | 3.1 | 4.7 | 7.9 | 9.5 | 20.22 | 23.1 | 30.3 | 37.5 | 73.5 | 121.5 |



### Damage

- **Critical hits** deal 75% more damage.
- **Armor** takes armor ÷ (armor + damage) × 95% off physical damage, at most 85%: even a weak hit on heavy armor keeps 15% of its damage.
- **Resistances** (fire, cold, lightning, poison, magic) lower the damage of their kind by their %. Gear and passive skills can raise them to 70% at most.
- **Blocking with a shield:** your chance is the shield's block × (your dexterity − 15) ÷ (2 × your level), at most 50%. It blocks monsters' physical attacks.

## Condition, repairs and gear

- **Condition:** at 00:00 UTC the class you have selected refills its health, mana and stamina; your other classes keep what they had. **Pheasant with Blackberry Balsamic Glaze** fills your stamina to its maximum.
- **Wear:** every round there's a 5% chance one of your equipped items loses 1 durability, and 1.5% with every monster attack, whether it hits you or not (leggings too).
- **Repairs:** 1 credit per missing durability point on a Normal item, 2 on an Exceptional one, 3 on an Elite one (a Circlet 1.11). The cost shown, item by item or all at once, is exactly what you pay; durability goes back to the maximum. Without the credits, nothing changes.
- **Equipment:** equipping puts the item in its slot and the replaced one back in your inventory (a two-handed weapon also takes off the shield). Gear you're not strong or experienced enough for stays in your inventory. An item's armor, enhanced defense, dodge and avoid count.
- **Inventory:** destroy an item, disassemble it into one crafting material of its quality and tier, or keep it in your stash.
- The [buildings]({{ '/buildings/' | relative_url }}) Training Grounds, Arcane Library, Healing Spring, Mana Well, Fitness Foundry and Traveler's Camp make your characters stronger; the Arcane Reliquary makes Magic and Rare drops likelier.

## Crafting

`/craft` (or Equipment → Craft):

- **Craft Items:** pick the type, family, item and quality: an item costs **3 crafting materials and 1 scrap**, goes into your inventory and pays 1 experience. Without the materials, the button is off.
- **Convert Crafting Materials:** 3 of a material make 1 of the next tier, for a small credit fee (3 Standard Essence → 1 Elemental Core for 0.3 credits).
- **Inscriptions:** a Magic inscription costs 1 Engraving Tool, a Rare one 3. It's added inactive; activate it to make it the item's inscription.

## The auction house

List an item from your inventory: the listing fee shown on the duration menu is what you pay. It's the duration's fee (table) × the item's tier (Normal 1, Exceptional 2, Elite 3) × its quality: a Magic Exceptional item costs 2.5 times the fee. You can have at most 5 auctions running.

- A bid takes your credits; when someone outbids you, you get them back in full. A buyout pays the seller and refunds the last bidder; the winner claims the item.
- The seller can cancel: the bidder gets the bid back and the seller claims the item back.
- When an auction runs out, the seller is paid the highest bid; with no bids, the item goes back to the seller.
- Claiming with a full inventory says so, and the item stays claimable. The same item can't be listed and equipped at once, and two players can't buy out the same auction.



| Quality | × the fee |
|---|---|
| Low Quality | 0.5 |
| Normal | 1 |
| Superior | 1.15 |
| Magic | 1.25 |
| Rare | 1.4 |
| Set | 1.5 |
| Unique | 1.5 |
| Crafted | 1.6 |





| Auction lasts | Listing fee (a Normal item of a Normal base) |
|---|---|
| 15 minutes | 0.003 credits |
| 1 hour | 0.005 credits |
| 4 hours | 0.01 credits |
| 8 hours | 0.02 credits |
| 1 day | 0.04 credits |
| 3 days | 0.06 credits |
| 1 week | 0.08 credits |
| 3 weeks | 0.1 credits |



## The Jotnar: a world boss

A giant appears in the Hack & Slash channel once every 3 hours. Press **Attack Giant** to fight it from your own battle screen; each attack costs 5 stamina. It's built for the whole server: its base health is 85,000, and it escapes after 30 minutes.

- **Bigger servers meet bigger giants:** up to 100 members a giant has its base health, with 1,000 members half again as much, with 10,000 twice as much; each giant also varies from 80% to 120% of that.
- **You hit it as if it were your own level:** its level doesn't make you miss more.
- **When it falls,** its 500 credits are split by damage: each fighter gets exactly their share of the damage times the pool, rounded down. Experience is 50 plus 2 for every 1% of the damage you dealt, up to 150 (a giant beaten alone pays 500 credits and 150 experience).
- **When it escapes,** it pays only if the server took at least 5% of its health together. Then its fighters share half the pool, by damage, scaled to 25% plus 0.75% for every 1% of its health taken: a giant that escapes with 40% of its health gone pays 55% of 250 credits. Experience is 60% (30 plus 1.2 per 1% of the damage you dealt) at the same scale, loot chances are 70%, and the top three get bonus loot only if they dealt at least 25% of the damage. Hit hard together: bringing it down pays far more.
- Each giant pays once. Items it drops go to the first player who picks them up.

## The Arena

`/hackslash` → **Arena** → **Challenge Opponent**: pick a player and challenge them; they join from the public **Join Duel** message. You take turns until one of you falls; the survivor wins.

- **A challenge waits 5 minutes** for the opponent (your screen says when it cancels). Then it's cancelled, and **Join Duel** says the duel is gone.
- **Each turn has 2 minutes**; the screen counts them down.
- You can have at most 5 open duels, and a player who has 5 can't be challenged.

- A duel pays nothing: no experience, no credits. There are no wagers.
- Auras, buffs and debuffs count once a move: a Paladin's Might hits as hard on the fifth move as on the first.

## Tips

- Dexterity and attack-rating gear make you hit more often; a pure strength build misses more.
- Pick monsters near your level: those more than 5 levels below you give no experience.
- Use your free resets after the release to rebuild your characters for the new hit chance.
- Keep an Anchovy with Anchovy Powder for when a battle goes wrong.
