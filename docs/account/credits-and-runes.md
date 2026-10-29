---
title: "Credits and RUNES"
icon: guide/nav
nav_icon: "assets/icons/emoji/pouch.webp"
---

# ![Pouch](../assets/icons/emoji/pouch.webp){ .gi .gi-title width="64" height="64" loading="lazy" } Credits and RUNES

**<span class="gi-m">![](../assets/icons/emoji/pouch.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Credits](#getting-credits)</span>** are the bot's money. You earn them in the games, spend them in the store and elsewhere, and you can take them out of the game as Credits tokens on the Runebase blockchain, or bring RUNES in. Some prizes are paid in **<span class="gi-m">![](../assets/icons/currency/runes.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[RUNES](#runes-prizes)</span>** directly, from the realm's RUNES wallet.

**Where:** `/pouch` shows your balance, with **Withdraw** and **Buy Credits**. `/withdraw` withdraws directly.

`/pouch` shows the pouch's level, your credits, and the <span class="gi-m">![](../assets/icons/item/bronze-key.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Bronze](../items/keys-and-cards/treasure-keys.md#bronze-key)</span>, <span class="gi-m">![](../assets/icons/item/silver-key.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Silver](../items/keys-and-cards/treasure-keys.md#silver-key)</span> and <span class="gi-m">![](../assets/icons/item/gold-key.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Gold Keys](../items/keys-and-cards/treasure-keys.md#gold-key)</span>, <span class="gi-m">![](../assets/icons/item/mystery-card.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Mystery Cards](../items/keys-and-cards/cards-and-relics.md#mystery-card)</span> and <span class="gi-m">![](../assets/icons/item/wood-scrap.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Wood](../items/materials/scrap.md#wood-scrap)</span>, <span class="gi-m">![](../assets/icons/item/leather-scrap.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Leather](../items/materials/scrap.md#leather-scrap)</span> and <span class="gi-m">![](../assets/icons/item/metal-scrap.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Metal Scrap](../items/materials/scrap.md#metal-scrap)</span> it holds, each next to the room it has: per pouch level 40 Bronze, 20 Silver and 10 Gold Keys, 50 Mystery Cards and 100 of each scrap (level 2 holds twice that). Its buttons: **Upgrade Pouch**, **Buy Credits**, **Withdraw**, **Withdrawal History** and **Credits Change History**.

## Getting credits

- **From the games:** expeditions, piles, chests, chess and Hnefatafl wins, quests, WordWeaver, Loot Reels, dice, heists and more (each game's page has its prize table). A single credit prize above **25,000 credits** is withheld instead of paid, and announced in the payout channel. The Crown of Chaos pool is the one exception: it's paid in full.
- **Gifts** from other players (`/gift`, see <span class="gi-m">🎁&nbsp;[Gifts](gifts.md)</span>).
- **The <span class="gi-m">![](../assets/icons/building/iron-bank.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Iron Bank](buildings.md#the-iron-bank)</span>** pays interest on credits you store in it (<span class="gi-m">🏗️&nbsp;[Buildings](buildings.md)</span>).
- **Deposits** and **buying credits with Hermes** (below).

## Typing an amount

Wherever you type an amount of credits (a gift, an <span class="gi-m">![](../assets/icons/building/iron-bank.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Iron Bank](buildings.md#the-iron-bank)</span> deposit, a withdrawal, buying credits with Hermes, an auction's prices and bids) it's read the same way:

- **A plain number:** `5`, `2.5`, `0.00000001`. Spaces around it don't matter.
- **8 decimals at most, rounded down:** `1.000000009` is 1 credit, never more than you typed.
- **Anything else is refused, only you see it, and nothing moves:** `0x10`, `1e3`, `+5`, `1,5` (use a point), `1 000`, `Infinity`.
- Store quantities are whole numbers written the same way (`5`, not `5e0`).

## Deposits

**Pouch → Buy Credits** shows your deposit address (it's made for you the first time; if the Runebase node is down, the menu says so and the address comes once it's back).

- **RUNES or Credits tokens sent to your deposit address become credits 1:1.**
- The bot sees the payment (you get a DM), then credits your wallet at **6 confirmations** (another DM).
- Each deposit is credited exactly once, however often the bot hears about it. A deposit made while the bot was offline is found and credited when it's back.
- If the Runebase node or the bot's database has a hiccup while your deposit comes in, the bot tries again with the next block: a deposit is never skipped, and still credited only once.
- One payment to several deposit addresses gives each player the sum sent to their own address.
- A staking reward paid to a deposit address is not a deposit.
- The deposit that verifies you as a <span class="gi-m">🧱&nbsp;[super staker](super-stakers.md)</span> goes to this same address and is credited like any other.

## Buying credits with Hermes

**Pouch → Buy Credits → Buy Credits With Hermes**, type the amount, **Accept Purchase**. Hermes charges your RUNES and the bot credits **exactly the amount you asked for (1 RUNES = 1 credit)**, once. Fractions are fine (2.5 credits); an amount that isn't [a plain number](#typing-an-amount) is refused, only you see it, and Hermes isn't asked.

- If Hermes refuses, nothing is credited and you see why, in plain words.
- The bot only credits an answer from Hermes that is about your purchase, for exactly that amount. If Hermes' answer gets lost, the screen says Hermes may have charged you and doesn't offer the purchase again (so you can't pay twice); the purchase isn't credited automatically, it's logged for the staff to sort out, so ask them. The same when Hermes' answer doesn't say what it charged, or your purchase was changed or settled by the staff while Hermes was answering: never credited twice.

## Withdrawals

`/withdraw` (address and amount), or **Pouch → Withdraw**. Only you see the result.

- **The address must be a Runebase address starting with R**, and not your own deposit address.
- **At least 1 credit**, at most your balance, [typed as a plain number](#typing-an-amount) (`2.000000009` withdraws 2). **No fee:** exactly the amount you withdraw is sent.
- Your credits leave your wallet at once and the withdrawal is **queued**. The bot then sends it as Credits tokens and you get a DM ("Your withdrawal has been accepted", with the transaction), and another when it's **confirmed** at 6 confirmations. Your pouch history shows each withdrawal with its transaction.
- If the Runebase node is down, `/withdraw` says so and nothing moves. If the node goes down after you queued, or the bot's wallet is short, the withdrawal stays queued and goes out later, once.
- Withdrawals can be paused by the staff; a queued withdrawal then waits and goes out once they resume.
- If the network refuses a withdrawal before it is sent, your credits are refunded, once, and you get a DM saying so.
- **A withdrawal is never sent twice.** If the bot can't tell whether it went out (the node didn't answer clearly, or the bot stopped in the middle), it stays **pending** in your withdrawal history: the bot doesn't send it again or refund it on its own, and the staff check it and settle it.
- Two withdrawals of your whole balance at the same moment: one is queued, the other is refused. Credits you spend after queuing can't touch the queued amount.

## RUNES prizes

Dice, treasure chests, scratch cards and Crown of Chaos pay some prizes in RUNES: **a percentage of the realm's RUNES wallet**, sent to you as a tip by the tipbot (Hermes). The prize tables show the percentages.

- If the tipbot is offline, the dice roll, chest or scratch card says so, only to you, and nothing is spent; also when the bot can't read the realm's RUNES wallet (it lost the tipbot for over a minute). A Crown's reign still ends then, without RUNES.
- **The realm's RUNES wallet must hold more than 1 RUNES to pay RUNES prizes.** With 1 RUNES or less every game still plays and pays everything else: the dice roll (experience, the prize draw, the cooldown), chests open, scratch cards are dealt and collected, a Crown's reign ends with its pool and experience. The prize tables show no RUNES, and a RUNES prize is shown as **not paid: the realm's RUNES wallet is empty**.
- **RUNES are paid only in a server whose tipbot is connected** (today the Runebase server; the other servers are connected after the update). Until then a server plays like one with an empty wallet: the prize tables show no RUNES, a RUNES prize is shown as **not paid: RUNES prizes aren't connected in this server yet**, and everything else is paid.
- **No single RUNES prize is more than 1% of the realm's wallet.** A prize above that would be a mistake in a prize table: the whole roll or card fails and nothing of it is paid (no experience, no item, no tip), and you can try again.
- **A tip is never sent twice.** Each prize's tip is on record from the moment you win it. If the bot restarts right after your win, or the tipbot doesn't confirm the tip, the bot doesn't send it again on its own: the realm's admins are told, check the tipbot, and settle it by hand.

## Tips

- Double-check the withdrawal address: it must start with R.
- Deposits take 6 confirmations; you get a DM when the bot first sees yours.
