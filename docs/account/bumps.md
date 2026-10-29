---
title: "Bumps"
---

# Bumps

Bump the server with Disboard's `/bump` (or Discord Home's). The bumper gets **10 experience**, a roll on the bump prize table and the **bumper role for 2 hours**, announced in the experience channel.

- A server can be bumped **once every 2 hours on each bump service** (Disboard, Discord Home): a `/bump` answered in that window pays nobody, and the bot says the server was already bumped.
- Two members' bumps answered at the same moment pay only one of them.
- The bumper role is taken back when its 2 hours are over (also across a bot restart).

The prize table is without utilities (a <span class="gi-m">🪓&nbsp;[Wood Axe](../games/expeditions.md#utilities-wood-axe-skinning-knife-mining-pick)</span>, <span class="gi-m">🔪&nbsp;[Skinning Knife](../games/expeditions.md#utilities-wood-axe-skinning-knife-mining-pick)</span> or <span class="gi-m">⛏️&nbsp;[Mining Pick](../games/expeditions.md#utilities-wood-axe-skinning-knife-mining-pick)</span> raises the scrap rows). A payout rolls its table once and pays at most one row, so the chances add up to at most 100%. The scrap rows come last: a utility makes them likelier and never takes anything from the other prizes (the <span class="gi-m">![](../assets/icons/item/engraving-tool.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Engraving Tool](../items/materials.md#engraving-tool)</span>, the <span class="gi-m">![](../assets/icons/item/chaos-relic.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Chaos Relic](../items/keys-and-cards.md#chaos-relic)</span>, the pet tokens and the credits keep their chances at every utility level); past 100% the last scrap row, <span class="gi-m">![](../assets/icons/item/wood-scrap.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Wood Scrap](../items/materials.md#wood-scrap)</span>, gives up what the other two gain. `/loottables` shows each prize's real chance for you. Every row of this table is played in the tests and pays exactly what it shows.

| Prize | Chance per bump |
|---|---|
| ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 5 to 15 credits | 8% |
| ![Nail](../assets/icons/item/nail.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Nail](../items/materials.md#nail) | 2% |
| ![Rope](../assets/icons/item/rope.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Rope](../items/materials.md#rope) | 0.4% |
| ![Common Pet Token](../assets/icons/item/common-pet-token.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Common Pet Token](../items/pet-items.md#common-pet-token) | 1% |
| 1 [Pet Token](../items/pet-items.md#pet-tokens) (Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| ![Chaos Relic](../assets/icons/item/chaos-relic.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Chaos Relic](../items/keys-and-cards.md#chaos-relic) | 5% |
| ![Engraving Tool](../assets/icons/item/engraving-tool.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Engraving Tool](../items/materials.md#engraving-tool) | 8% |
| ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Leather Scrap](../items/materials.md#leather-scrap) | 24.35% |
| ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Metal Scrap](../items/materials.md#metal-scrap) | 24.35% |
| ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Wood Scrap](../items/materials.md#wood-scrap) | 24.35% |
| nothing | 0.05% |

## Tips

- Bump when the 2-hour window is over: only the first bump in a window pays.
