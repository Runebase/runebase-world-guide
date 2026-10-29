---
title: "Dice"
---

# Dice

**Where to play:** Discord
{ .where-to-play }

A quick game of luck: roll two dice for experience, a <span class="gi-m">![](../assets/icons/currency/runes.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[RUNES](../account/credits-and-runes.md#runes-prizes)</span> prize and a prize draw.

`/roll` in the dice channel. A roll pays **experience by the sum you roll** (the rarer the sum, the more), a **RUNES prize** tipped to you (also by the sum), and **one** prize draw from the dice prize table (below). Then the dice wait **2 hours** (the bot tells you when you can roll again); after that you roll again and are paid again. <!-- The cooldown is production's; the tests run with 5 seconds. -->

- The RUNES prize is a share of the realm's RUNES wallet at the moment you roll, the percentage in the table below for your sum: with 1,000,000 RUNES in the wallet, a 7 pays 1.6 RUNES and a double six 9.6 RUNES.
- Every roll's result has a **Roll Dice** button: anyone can press it to roll their own dice (during your cooldown it rolls nothing and tells you, privately, when you can roll again). You can also roll from `/start` → **Activities** → **Dice**.
- A roll outside the dice channel answers you privately and posts the result in the dice channel.
- If the tipbot is offline, the roll says so and nothing changes; also when the bot can't read the realm's RUNES wallet. When that wallet holds 1 RUNES or less, the roll is refused, only to you, and nothing changes.
- Two rolls at the same moment: one is paid, the other gets the cooldown, also from two devices (`/roll` and the dice menu).
- The cooldown survives a restart of the bot, and the dice menu always counts down to the time a roll would be refused until.
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

Prize tables are without utilities: a <span class="gi-m">🪓&nbsp;[Wood Axe](expeditions.md#utilities-wood-axe-skinning-knife-mining-pick)</span>, <span class="gi-m">🔪&nbsp;[Skinning Knife](expeditions.md#utilities-wood-axe-skinning-knife-mining-pick)</span> or <span class="gi-m">⛏️&nbsp;[Mining Pick](expeditions.md#utilities-wood-axe-skinning-knife-mining-pick)</span> raises the scrap rows.

| Prize | Chance per roll |
|---|---|
| ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 to 15 credits | 8% |
| ![Runes Pattern Card](../assets/icons/item/runes-pattern-card.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Runes Pattern Card](../items/keys-and-cards.md#runes-pattern-card) | 1% |
| ![Nail](../assets/icons/item/nail.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Nail](../items/materials.md#nail) | 2% |
| ![Rope](../assets/icons/item/rope.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Rope](../items/materials.md#rope) | 0.5% |
| ![Engraving Tool](../assets/icons/item/engraving-tool.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Engraving Tool](../items/materials.md#engraving-tool) | 3.5% |
| ![Chaos Relic](../assets/icons/item/chaos-relic.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 10 [Chaos Relic](../items/keys-and-cards.md#chaos-relic) | 5% |
| ![Common Pet Token](../assets/icons/item/common-pet-token.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Common Pet Token](../items/pet-items.md#common-pet-token) | 1% |
| 1 [Pet Token](../items/pet-items.md#pet-tokens) (Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Leather Scrap](../items/materials.md#leather-scrap) | 25% |
| ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Metal Scrap](../items/materials.md#metal-scrap) | 25% |
| ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Wood Scrap](../items/materials.md#wood-scrap) | 25% |
| nothing | 1.5% |

## Tips

- Roll the dice whenever the cooldown is over: every roll pays experience and a RUNES prize.
