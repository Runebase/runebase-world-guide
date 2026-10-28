---
title: "Credits and RUNES"
---

# Credits and RUNES

**Credits** are the bot's money. You earn them in the games, spend them in the store and elsewhere, and you can take them out of the game as Credits tokens on the Runebase blockchain, or bring RUNES in. Some prizes are paid in **RUNES** directly, from the realm's RUNES wallet.

**Where:** `/pouch` shows your balance, with **Withdraw** and **Buy Credits**. `/withdraw` withdraws directly.

`/pouch` shows the pouch's level, your credits, and the Bronze, Silver and [Gold Keys](../items/keys-and-cards.md#gold-key), [Mystery Cards](../items/keys-and-cards.md#mystery-card) and Wood, Leather and [Metal Scrap](../items/materials.md#metal-scrap) it holds, each next to the room it has: per pouch level 40 Bronze, 20 Silver and 10 Gold Keys, 50 Mystery Cards and 100 of each scrap (level 2 holds twice that). Its buttons: **Upgrade Pouch**, **Buy Credits**, **Withdraw**, **Withdrawal History** and **Credits Change History**.

## Getting credits

- **From the games:** expeditions, piles, chests, chess and Hnefatafl wins, quests, WordWeaver, Loot Reels, dice, heists and more (each game's page has its prize table). A single credit prize above **25,000 credits** is withheld instead of paid, and announced in the payout channel. The Crown of Chaos pool is the one exception: it's paid in full.
- **Gifts** from other players (`/gift`, see [Gifts and the convert market](gifts-and-convert-market.md)).
- **The Iron Bank** pays interest on credits you store in it ([Buildings](buildings.md)).
- **Deposits** and **buying credits with Hermes** (below).

## Deposits

**Pouch → Buy Credits** shows your deposit address (it's made for you the first time; if the Runebase node is down, the menu says so and the address comes once it's back).

- **RUNES or Credits tokens sent to your deposit address become credits 1:1.**
- The bot sees the payment (you get a DM), then credits your wallet at **6 confirmations** (another DM).
- Each deposit is credited exactly once, however often the bot hears about it. A deposit made while the bot was offline is found and credited when it's back.
- One payment to several deposit addresses gives each player the sum sent to their own address.
- A staking reward paid to a deposit address is not a deposit.

## Buying credits with Hermes

**Pouch → Buy Credits → Buy Credits With Hermes**, type the amount, **Accept Purchase**. Hermes charges your RUNES and the bot credits **exactly the amount you asked for (1 RUNES = 1 credit)**, once. Fractions are fine (2.5 credits).

- If Hermes refuses, nothing is credited and you see why.
- The bot only credits an answer from Hermes that is about your purchase, for exactly that amount. If Hermes' answer gets lost, the screen says Hermes may have charged you and doesn't offer the purchase again (so you can't pay twice); the purchase isn't credited automatically, it's logged for the staff to sort out, so ask them.

## Withdrawals

`/withdraw` (address and amount), or **Pouch → Withdraw**. Only you see the result.

- **The address must be a Runebase address starting with R**, and not your own deposit address.
- **At least 1 credit**, at most your balance. **No fee:** exactly the amount you withdraw is sent.
- Your credits leave your wallet at once and the withdrawal is **queued**. The bot then sends it as Credits tokens and you get a DM ("Your withdrawal has been accepted", with the transaction), and another when it's **confirmed** at 6 confirmations. Your pouch history shows each withdrawal with its transaction.
- If the Runebase node is down, `/withdraw` says so and nothing moves. If the node goes down after you queued, or the bot's wallet is short, the withdrawal stays queued and goes out later, once.
- Withdrawals can be paused by the staff; a queued withdrawal then waits and goes out once they resume.
- If the network refuses a withdrawal before it is sent, your credits are refunded, once.
- Two withdrawals of your whole balance at the same moment: one is queued, the other is refused. Credits you spend after queuing can't touch the queued amount.

## RUNES prizes

Dice, treasure chests, scratch cards and Crown of Chaos pay some prizes in RUNES: **a percentage of the realm's RUNES wallet**, sent to you as a tip by the tipbot (Hermes). The prize tables show the percentages.

- If the tipbot is offline, the dice roll, chest or scratch card says so, and nothing is spent.
- If the realm's tipbot session isn't active, no RUNES are tipped: the prize is recorded as not paid.

## Tips

- Double-check the withdrawal address: it must start with R.
- Deposits take 6 confirmations; you get a DM when the bot first sees yours.
