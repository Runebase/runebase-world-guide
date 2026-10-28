---
title: "The store and the basket"
---

# The store and the basket

The store sells you items for credits and buys them back; the basket holds what you gathered and cooked. How credits get in and out of the game is in [Credits and RUNES](credits-and-runes.md).

## The store

**Where:** `/store`. Pick a category and an item, then **Buy** or **Sell** and type how many. Some other menus open the store on an item (the [Crown of Chaos](../games/crown-of-chaos/attacking.md) menu's **Buy [Chaos Relic](../items/keys-and-cards.md#chaos-relic)**), and the store's delivery announcements have **Buy …** buttons for what just arrived.

**What the screen shows:** your credits, how many of the item you have, the price to **Buy** one and what **Sell** pays for one (with its percent), the store's own balance and the Crown of Chaos pool.

- **The price on the screen is what you pay**, to the last fraction of a credit: one costs exactly the price shown, several of a fixed-price item exactly the price × the amount (crafting materials: below), and you get exactly the amount. On top of that the game adds **5% of what you pay to the Crown of Chaos pool**; you don't pay it.
- **Selling pays exactly the amount the screen shows** × how many you sell, and takes exactly that many. Most items sell back for 75% of their price (the [Forgotten Throne Elixir](../items/store-consumables.md#forgotten-throne-elixir) for 2.5%). The **[Trade Post](buildings.md#what-each-building-does)** building adds 0.15% of the price per level (75% becomes 90% at level 100; the elixir's 2.5% becomes 17.5%), and the screen shows it.
- **The store pays from its own balance**, which grows with every purchase in your server. When it doesn't have enough for your sale, the sale is refused and you keep your items. The [Party Store](buildings.md#what-each-building-does) building gives no store discount.
- **Every purchase and sale is one line** in your credits history, and one in the store's **Purchase History** button: newest first, 25 a page, with how many, the total and the price of one.
- **When the store says no, only you see why**, and nothing changes: an amount that isn't a whole number above 0, more than your wallet holds, selling more than you have, more than the store has in stock, a full pouch.
- **At the same moment:** a double click, two devices, or two players after the last one never pay twice, sell twice or get more than the store has: one goes through, the other is told why. A buy or sell box you closed never takes over your next purchase.
- **Scrap:** every day (from 00:00 UTC) your first 5 scrap cost a quarter of the price (25 credits instead of 100), wood, leather and metal together; after that, full price. The screen shows the price of your next one. The store never sells more scrap than it has, and your pouch must have room (100 of each kind per pouch level). The store gets 5 scrap every hour. Scrap can't be sold back.
- **Crafting materials** (for Hack & Slash) have no fixed price: the fewer the store has, the dearer they are (the table below). Each one you buy costs the price at the stock left, so buying several costs more than the shown price × the amount, and the next price goes up; selling raises the stock and lowers the price. The screen always shows the next one's price. Selling back what you just bought pays exactly 75% of what you paid (never more). At most 10,000 in one purchase or sale, and the store doesn't buy a material it already has more than 1,000,000 of. The store gets 3 random materials every 3 hours, and from players' sales.
- **The price can move while you look:** if another player buys a crafting material first, yours costs the price at the stock left after theirs. The message after your purchase always says what you paid.

| Rule | Value |
|---|---|
| Discounted scrap a day | 5 |
| A discounted scrap costs | 25% of the price (75% off) |
| Added to the Crown of Chaos pool on every purchase | 5% of what you pay |
| Scrap delivered to the store | 5 every hour |
| Crafting materials delivered to the store | 3 every 3 hours |
| Most crafting materials in one purchase or sale | 10,000 |
| The store stops buying a crafting material it has more than | 1,000,000 |

**Crafting materials:** the price of one, in credits, by how many the store has (a sale pays 75% of the price at one more):

| Material | Base cost | Stock 1 | Stock 2 | Stock 5 | Stock 20 | Stock 100 | Stock 1,000 |
|---|---|---|---|---|---|---|---|
| [Standard Essence](../items/materials.md#standard-essence) | 1.5 credits | 30.74 | 15.74 | 6.72 | 2.16 | 0.84 | 0.38 |
| [Elemental Core](../items/materials.md#elemental-core) | 4.5 credits | 92.23 | 47.21 | 20.17 | 6.49 | 2.51 | 1.14 |
| [Primal Source](../items/materials.md#primal-source) | 13.5 credits | 276.7 | 141.64 | 60.5 | 19.48 | 7.53 | 3.43 |
| [Basic Residue](../items/materials.md#basic-residue) | 4.5 credits | 92.23 | 47.21 | 20.17 | 6.49 | 2.51 | 1.14 |
| [Enigmatic Nexus](../items/materials.md#enigmatic-nexus) | 13.5 credits | 276.7 | 141.64 | 60.5 | 19.48 | 7.53 | 3.43 |
| [Mystical Node](../items/materials.md#mystical-node) | 40.5 credits | 830.09 | 424.93 | 181.5 | 58.43 | 22.6 | 10.3 |
| [Elite Essence](../items/materials.md#elite-essence) | 13.5 credits | 276.7 | 141.64 | 60.5 | 19.48 | 7.53 | 3.43 |
| [Radiant Shard](../items/materials.md#radiant-shard) | 40.5 credits | 830.09 | 424.93 | 181.5 | 58.43 | 22.6 | 10.3 |
| [Shattered Prism](../items/materials.md#shattered-prism) | 121.5 credits | 2,490.26 | 1,274.79 | 544.49 | 175.29 | 67.81 | 30.9 |
| [Engraving Tool](../items/materials.md#engraving-tool) | 1.5 credits | 30.74 | 15.74 | 6.72 | 2.16 | 0.84 | 0.38 |

| Category | Item | Price | Sells back for (without a Trade Post) |
|---|---|---|---|
| Spices | [Anchovy Powder](../items/ingredients.md#anchovy-powder) | 1 credit | 0.75 credits (75%) |
| Spices | [Smoked Paprika](../items/ingredients.md#smoked-paprika) | 2 credits | 1.5 credits (75%) |
| Spices | [Sumac](../items/ingredients.md#sumac) | 3 credits | 2.25 credits (75%) |
| Spices | [Old Bay Seasoning](../items/ingredients.md#old-bay-seasoning) | 4 credits | 3 credits (75%) |
| Spices | [Wasabi](../items/ingredients.md#wasabi) | 8 credits | 6 credits (75%) |
| Spices | [Cumin](../items/ingredients.md#cumin) | 5 credits | 3.75 credits (75%) |
| Spices | [Sichuan Peppercorns](../items/ingredients.md#sichuan-peppercorns) | 5 credits | 3.75 credits (75%) |
| Spices | [Dill](../items/ingredients.md#dill) | 8 credits | 6 credits (75%) |
| Spices | [Rosemary](../items/ingredients.md#rosemary) | 10 credits | 7.5 credits (75%) |
| Spices | [Lemon](../items/ingredients.md#lemon) | 25 credits | 18.75 credits (75%) |
| Sauces | [Sawmill Gravy](../items/ingredients.md#sawmill-gravy) | 1 credit | 0.75 credits (75%) |
| Sauces | [Mustard Cream Sauce](../items/ingredients.md#mustard-cream-sauce) | 2 credits | 1.5 credits (75%) |
| Sauces | [Lingonberry Sauce](../items/ingredients.md#lingonberry-sauce) | 3 credits | 2.25 credits (75%) |
| Sauces | [Cranberry Glaze](../items/ingredients.md#cranberry-glaze) | 4 credits | 3 credits (75%) |
| Sauces | [Blackberry Balsamic Glaze](../items/ingredients.md#blackberry-balsamic-glaze) | 8 credits | 6 credits (75%) |
| Sauces | [Juniper Berry Demi-Glace](../items/ingredients.md#juniper-berry-demi-glace) | 5 credits | 3.75 credits (75%) |
| Sauces | [Huckleberry Sauce](../items/ingredients.md#huckleberry-sauce) | 5 credits | 3.75 credits (75%) |
| Sauces | [Blueberry Sauce](../items/ingredients.md#blueberry-sauce) | 8 credits | 6 credits (75%) |
| Sauces | [Cherry Sauce](../items/ingredients.md#cherry-sauce) | 10 credits | 7.5 credits (75%) |
| Consumables | [Fishing Beer](../items/store-consumables.md#fishing-beer) | 3 credits | 2.25 credits (75%) |
| Consumables | [Hunting Weed](../items/store-consumables.md#hunting-weed) | 3 credits | 2.25 credits (75%) |
| Consumables | [Einherjar's Barrier Draught](../items/store-consumables.md#einherjars-barrier-draught) | 850 credits | 637.5 credits (75%) |
| Consumables | [Skadi's Retribution Brew](../items/store-consumables.md#skadis-retribution-brew) | 850 credits | 637.5 credits (75%) |
| Consumables | [Frigg's Resurgence Elixir](../items/store-consumables.md#friggs-resurgence-elixir) | 850 credits | 637.5 credits (75%) |
| Consumables | [Forgotten Throne Elixir](../items/store-consumables.md#forgotten-throne-elixir) | 8,000 credits | 200 credits (2.5%) |
| Building Supplies | [Toolbox](../items/materials.md#toolbox) | 1,250 credits | 937.5 credits (75%) |
| Building Supplies | [Nail](../items/materials.md#nail) | 2.5 credits | 1.875 credits (75%) |
| Building Supplies | [Rope](../items/materials.md#rope) | 10 credits | 7.5 credits (75%) |
| Playtime Provisions | [Runes Pattern Card](../items/keys-and-cards.md#runes-pattern-card) | 50 credits | 37.5 credits (75%) |
| Playtime Provisions | [Chaos Relic](../items/keys-and-cards.md#chaos-relic) | 2 credits | 1.5 credits (75%) |
| Pet Items | [Common Pet Token](../items/pet-items.md#common-pet-token) | 5 credits | 3.75 credits (75%) |
| Pet Items | [Uncommon Pet Token](../items/pet-items.md#uncommon-pet-token) | not sold | 7.5 credits (75%) |
| Pet Items | [Rare Pet Token](../items/pet-items.md#rare-pet-token) | not sold | 11.25 credits (75%) |
| Pet Items | [Epic Pet Token](../items/pet-items.md#epic-pet-token) | not sold | 15 credits (75%) |
| Pet Items | [Legendary Pet Token](../items/pet-items.md#legendary-pet-token) | not sold | 18.75 credits (75%) |
| Pet Items | [Mythical Pet Token](../items/pet-items.md#mythical-pet-token) | not sold | 22.5 credits (75%) |
| Pet Items | [Common Pet Food](../items/pet-items.md#common-pet-food) | 1 credit | 0.75 credits (75%) |
| Pet Items | [Uncommon Pet Food](../items/pet-items.md#uncommon-pet-food) | 1.5 credits | 1.125 credits (75%) |
| Pet Items | [Rare Pet Food](../items/pet-items.md#rare-pet-food) | 2 credits | 1.5 credits (75%) |
| Pet Items | [Epic Pet Food](../items/pet-items.md#epic-pet-food) | 2.5 credits | 1.875 credits (75%) |
| Pet Items | [Legendary Pet Food](../items/pet-items.md#legendary-pet-food) | 3 credits | 2.25 credits (75%) |
| Pet Items | [Mythical Pet Food](../items/pet-items.md#mythical-pet-food) | 3.5 credits | 2.625 credits (75%) |
| Pet Items | [Common Pet Cure](../items/pet-items.md#common-pet-cure) | 10 credits | 7.5 credits (75%) |
| Pet Items | [Uncommon Pet Cure](../items/pet-items.md#uncommon-pet-cure) | 15 credits | 11.25 credits (75%) |
| Pet Items | [Rare Pet Cure](../items/pet-items.md#rare-pet-cure) | 20 credits | 15 credits (75%) |
| Pet Items | [Epic Pet Cure](../items/pet-items.md#epic-pet-cure) | 25 credits | 18.75 credits (75%) |
| Pet Items | [Legendary Pet Cure](../items/pet-items.md#legendary-pet-cure) | 30 credits | 22.5 credits (75%) |
| Pet Items | [Mythical Pet Cure](../items/pet-items.md#mythical-pet-cure) | 35 credits | 26.25 credits (75%) |
| Pet Items | [Common Pet Wash Kit](../items/pet-items.md#common-pet-wash-kit) | 5 credits | 3.75 credits (75%) |
| Pet Items | [Uncommon Pet Wash Kit](../items/pet-items.md#uncommon-pet-wash-kit) | 6 credits | 4.5 credits (75%) |
| Pet Items | [Rare Pet Wash Kit](../items/pet-items.md#rare-pet-wash-kit) | 7 credits | 5.25 credits (75%) |
| Pet Items | [Epic Pet Wash Kit](../items/pet-items.md#epic-pet-wash-kit) | 8 credits | 6 credits (75%) |
| Pet Items | [Legendary Pet Wash Kit](../items/pet-items.md#legendary-pet-wash-kit) | 9 credits | 6.75 credits (75%) |
| Pet Items | [Mythical Pet Wash Kit](../items/pet-items.md#mythical-pet-wash-kit) | 10 credits | 7.5 credits (75%) |
| Scrap Resources | [Wood Scrap](../items/materials.md#wood-scrap) | 100 credits | can't be sold |
| Scrap Resources | [Leather Scrap](../items/materials.md#leather-scrap) | 100 credits | can't be sold |
| Scrap Resources | [Metal Scrap](../items/materials.md#metal-scrap) | 100 credits | can't be sold |

## The basket

`/basket` shows what you gathered and cooked. **[Swordfish Kebabs with Lemon and Rosemary](../items/dishes.md#swordfish-kebabs-with-lemon-and-rosemary)** can be eaten from the basket: each one gives **15 experience**. More than you have, or an amount that isn't a whole number, eats nothing.

## Tips

- Sell what you don't need: most items sell for 75% of their price, more with a Trade Post.
- Buy up to 5 scrap a day: those cost a quarter of the price.
- Crafting materials are cheapest when the store has many: after a delivery, or after other players sold theirs. Buying the last few is expensive.
