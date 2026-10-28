---
title: Dice, treasure chests, piles and keys
permalink: /dice-chests-piles/
---

[← All pages]({{ '/' | relative_url }})

# Dice, treasure chests, piles and keys

Quick games of luck: roll the dice, open treasure chests with keys, and be first to grab the piles of credits, keys, scrap and building supplies that appear in the server's channels.

## Dice

`/roll` in the dice channel. A roll pays **experience by the sum you roll** (the rarer the sum, the more), a **RUNES prize** tipped to you (also by the sum), and **one** prize draw from the dice prize table (below). Then the dice wait **2 hours** (the bot tells you when you can roll again); after that you roll again and are paid again. <!-- The cooldown is production's; the tests run with 5 seconds. -->

- The RUNES prize is a share of the realm's RUNES wallet at the moment you roll, the percentage in the table below for your sum: with 1,000,000 RUNES in the wallet, a 7 pays 1.6 RUNES and a double six 9.6 RUNES.
- Every roll's result has a **Roll Dice** button: anyone can press it to roll their own dice (during your cooldown it rolls nothing and tells you, privately, when you can roll again). You can also roll from `/start` → **Activities** → **Dice**.
- A roll outside the dice channel answers you privately and posts the result in the dice channel.
- If the tipbot is offline, the roll says so and nothing changes.
- Two rolls at the same moment: one is paid, the other gets the cooldown.
- The **dice leaderboards** count each roll's dice score.



| Sum of the two dice | Chance | Experience | RUNES prize (% of the realm's RUNES wallet) | Dice score |
|---|---|---|---|---|
| 2 | 2.78% | 27 | 0.00096% | 6 |
| 3 | 5.56% | 14 | 0.00048% | 5 |
| 4 | 8.33% | 9 | 0.00032% | 4 |
| 5 | 11.11% | 7 | 0.00024% | 3 |
| 6 | 13.89% | 5 | 0.000192% | 2 |
| 7 | 16.67% | 5 | 0.00016% | 1 |
| 8 | 13.89% | 5 | 0.000192% | 2 |
| 9 | 11.11% | 7 | 0.00024% | 3 |
| 10 | 8.33% | 9 | 0.00032% | 4 |
| 11 | 5.56% | 14 | 0.00048% | 5 |
| 12 | 2.78% | 27 | 0.00096% | 6 |



Prize tables are without utilities: a Wood Axe, Skinning Knife or Mining Pick raises the scrap rows ([activities]({{ '/activities/' | relative_url }})).



| Prize | Chance per roll |
|---|---|
| 1 to 15 credits | 8% |
| 1 Runes Pattern Card | 1% |
| 1 Nail | 2% |
| 1 Rope | 0.5% |
| 1 Engraving Tool | 3.5% |
| 10 Chaos Relic | 5% |
| 1 Common Pet Token | 1% |
| 1 Pet Token (Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 Leather Scrap | 25% |
| 1 Metal Scrap | 25% |
| 1 Wood Scrap | 25% |
| nothing | 1.5% |



## Treasure chests

`/treasurechest` in the treasure chest channel shows the chest. **Loot treasure chest**, then pick a key: the chest spends exactly that key and **rolls its key's prize table three times** (credits, RUNES, items, experience). A chest whose three rolls all miss pays **1 experience**.

- Without that key, or with the tipbot offline, nothing is spent.
- One key clicked on two chest buttons at once opens one chest and spends the key once.
- Better keys pay the same prizes at the same chances, the same amount or more:



| Chance per roll | Bronze Key | Silver Key | Gold Key |
|---|---|---|---|
| 0.02% | 8 Mystery Card | 12 Mystery Card | 16 Mystery Card |
| 0.15% | 6 Mystery Card | 9 Mystery Card | 12 Mystery Card |
| 0.3% | 3 Mystery Card | 5 Mystery Card | 6 Mystery Card |
| 2% | 2 Mystery Card | 3 Mystery Card | 4 Mystery Card |
| 5% | 1 Mystery Card | 2 Mystery Card | 2 Mystery Card |
| 0.5% | 2 Runes Pattern Card | 2 Runes Pattern Card | 2 Runes Pattern Card |
| 2% | 1 Runes Pattern Card | 1 Runes Pattern Card | 1 Runes Pattern Card |
| 2% | 1 Chaos Relic | 2 Chaos Relic | 2 Chaos Relic |
| 0.005% | 50 experience | 75 experience | 100 experience |
| 0.1% | 25 experience | 38 experience | 50 experience |
| 0.25% | 10 experience | 15 experience | 20 experience |
| 0.5% | 10 experience | 15 experience | 20 experience |
| 1% | 5 experience | 8 experience | 10 experience |
| 2.5% | 3 experience | 5 experience | 6 experience |
| 0.5% | 1 Wood Scrap | 2 Wood Scrap | 2 Wood Scrap |
| 0.1% | 2 Wood Scrap | 3 Wood Scrap | 4 Wood Scrap |
| 0.25% | 1 Metal Scrap | 2 Metal Scrap | 2 Metal Scrap |
| 0.1% | 2 Metal Scrap | 3 Metal Scrap | 4 Metal Scrap |
| 0.25% | 1 Leather Scrap | 2 Leather Scrap | 2 Leather Scrap |
| 0.1% | 2 Leather Scrap | 3 Leather Scrap | 4 Leather Scrap |
| 0.01% | 0.064% of the realm's RUNES wallet | 0.096% of the realm's RUNES wallet | 0.128% of the realm's RUNES wallet |
| 0.5% | 0.01% of the realm's RUNES wallet | 0.015% of the realm's RUNES wallet | 0.02% of the realm's RUNES wallet |
| 1.5% | 0.00467% of the realm's RUNES wallet | 0.007% of the realm's RUNES wallet | 0.00933% of the realm's RUNES wallet |
| 3% | 0.00167% of the realm's RUNES wallet | 0.0025% of the realm's RUNES wallet | 0.00333% of the realm's RUNES wallet |
| 4% | 0.000667% of the realm's RUNES wallet | 0.001% of the realm's RUNES wallet | 0.00133% of the realm's RUNES wallet |
| 8% | 0.000333% of the realm's RUNES wallet | 0.0005% of the realm's RUNES wallet | 0.000667% of the realm's RUNES wallet |
| 2% | 1 Nail | 2 Nail | 2 Nail |
| 0.5% | 1 Rope | 2 Rope | 2 Rope |
| 0.8% | 50 credits | 75 credits | 100 credits |
| 2% | 25 credits | 37.5 credits | 50 credits |
| 4% | 12 credits | 18 credits | 24 credits |
| 6% | 5 credits | 7.5 credits | 10 credits |
| 0.75% | 1 Lemon | 2 Lemon | 2 Lemon |
|  | nothing: 49.32% | nothing: 49.32% | nothing: 49.32% |



**Getting keys:** key piles in the channels (below), the **Treasure Forge** building (a Bronze, Silver or Gold Key for 1, 2 or 3 Metal Scrap; [Buildings]({{ '/buildings/' | relative_url }})), heists, scratch cards and Loot Reels. Keys are kept in your pouch, which has room for a limited number per pouch level.

## Piles

Piles of credits, treasure keys, scrap and building supplies appear in the server's channels for a short time. To collect one, press its button and answer the **captcha**: the first players to answer correctly take the pile's slots.

- **Credit piles** are shared: each collector gets their share. Answering the captcha wrong, or collecting twice, pays nothing.
- A pile has a limited number of slots: when more players answer than there are slots, only the first ones are paid, and the others are told.
- When a credit pile expires, its unclaimed share goes to the **Crown of Chaos** pool.
- **Nail piles** come every hour: each of their players gets the same number of Nails (3 to 9, set when the pile appears) and 2 experience.

When they come, how long they stay and what they hold:



| Pile | Scheduled | Appears | Open for | Players | Each player gets |
|---|---|---|---|---|---|
| Bronze Key | every 15 minutes | a random moment up to 15 minutes later | 3 minutes | 2 | 1 Bronze Key |
| Silver Key | every 30 minutes | a random moment up to 30 minutes later | 3 minutes | 2 | 1 Silver Key |
| Gold Key | every hour | a random moment up to 1 hour later | 3 minutes | 2 | 1 Gold Key |
| Scrap (wood, metal or leather) | every hour | a random moment up to 1 hour later | 10 minutes | 4 to 8 | 1 scrap of the pile's kind |
| Rope | at 00:00, 08:00 and 16:00 UTC | a random moment up to 8 hours later | 25 minutes | 4 to 10 | 1 to 3 Ropes (the same for every player of the pile) |
| Nail | every hour | a random moment up to 2 hours later | 25 minutes | 4 to 10 | 3 to 9 Nails (the same for every player of the pile) |
| Credits | every hour, in every server | a random moment up to 1 hour later | 25 minutes | 3 to 6 | an equal share of 100 to 200 credits |



**Pile boards** (`/leaderboard`): the Scrap, Credits Pile and BuildingSupply Pile Collector boards, all-time and monthly, count **1 for each pile you collect**, whatever it held. The TreasureKey Finder board counts 1 for each key.

## Key hunt

The **Monthly TreasureKey Hunt Ladder** (`/leaderboard`, monthly boards) ranks the treasure key hunters of the calendar month: each key you find scores **1 point for a Bronze Key, 2 for a Silver Key, 3 for a Gold Key**. When the staff pay the monthly prizes (on the Runebase server), last month's best hunters share **0.75% of the realm's RUNES wallet** by rank:



| Rank | Shares of the pool, each |
|---|---|
| 1 | 12 |
| 2 | 10 |
| 3 | 8 |
| 4 to 5 | 5 |
| 6 to 10 | 3 |
| 11 to 25 | 1.5 |
| 26 to 50 | 0.75 |



A tie goes to whoever found their keys first, and players who left the server are left out.

## Tips

- Roll the dice whenever the cooldown is over: every roll pays experience and a RUNES prize.
- A Gold Key pays about twice what a Bronze Key pays, at the same odds.
- Piles go fast: answer the captcha quickly.
