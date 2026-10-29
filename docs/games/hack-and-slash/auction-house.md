---
title: "The auction house"
icon: guide/nav
nav_emoji: "🔨"
---

# 🔨 The auction house

**Where to play:** Discord
{ .where-to-play }

List an item from your inventory: the listing fee shown on the duration menu is what you pay. It's the duration's fee (table) × the item's tier (Normal 1, Exceptional 2, Elite 3) × its quality: a Magic Exceptional item costs 2.5 times the fee. Every kind of item can be listed, leg armor included, and is found under its type in the auction house's menu (the class items under "Class-Specific").

You can have at most 5 listings. A listing keeps its place until it's sold (bought out, or ended with a bid), or until you take back an item that didn't sell or that you cancelled (Claim Auctions): take those back to free their places. The inventory's Auction button shows how many you have (2/5) and is off at 5/5.

- **Prices** are [typed as plain numbers](../../account/credits-and-runes.md#typing-an-amount), rounded down to 8 decimals, from 0.00000001 up to 184,467,440,737.09551615 credits; the starting bid can't be above the buyout, and without a starting bid the buyout is the starting bid.
- **A bid** takes your credits; when someone outbids you, you get them back in full. Raising your own bid takes only the difference, and the confirmation says so. A bid at or above the buyout buys the auction at the buyout price ("buy auction #… for …").
- **A buyout** pays the seller and refunds the last bidder; the winner claims the item from Claim Auctions.
- **The seller can cancel**, even with a bid on it: the bidder gets the bid back and the seller takes the item back from Claim Auctions.
- **When an auction runs out**, the seller is paid the highest bid and the channel says who won; with no bids, nobody is paid and the item waits for the seller in Claim Auctions. This happens once, even if the bot was restarting at that moment.
- **Refusals are private:** a bid below the starting or current bid, more than you have, on your own auction, on an auction that ended or changed after your confirmation was shown (outbid, bought out, cancelled); a price in another form (`0x10`, `1e3`, `+5`, `1,5`) or out of range; a sixth listing; a claim already made on another screen, without a Hack & Slash character, or with a full inventory. Only you see the reason, the screen stays as it was, and nothing moves.
- **What the screens show** is what's stored: 8 auctions a page, the soonest to end first, each with its starting bid, buyout, current bid and bidder and its end; an auction's history, newest first; My Active Auctions (your running auctions) and Claim Auctions (what you can take).
- **Its own house:** the Hack & Slash auction house is separate from Runebase World's (the MMORPG's): its listings, bids, items and the 5-listing limit never mix with the other's.

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

