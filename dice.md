---
title: Dice
permalink: /dice/
---

[← All pages]({{ '/' | relative_url }})

# Dice

A quick game of luck: roll two dice for experience, a RUNES prize and a prize draw.

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



Prize tables are without utilities: a Wood Axe, Skinning Knife or Mining Pick raises the scrap rows ([utilities]({{ '/expeditions/' | relative_url }}#utilities-wood-axe-skinning-knife-mining-pick)).



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



## Tips

- Roll the dice whenever the cooldown is over: every roll pays experience and a RUNES prize.
