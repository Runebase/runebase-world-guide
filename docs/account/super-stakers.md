---
title: "Super stakers"
icon: guide/nav
nav_emoji: "🧱"
---

# 🧱 Super stakers

A super staker is a Runebase wallet that stakes for others: holders delegate their RUNES to it, and it produces blocks with their weight. Register yours with the bot and the server can see how reliably it produces blocks: every 8 hours it earns a point if it did, and a reliable one with delegations holds the super staker role.

Open it from `/start` → **Activities** → **Super Stakers**.

## The list

**Super Stakers** lists every registered super staker that is verified (one still waiting for its verification isn't listed): its address, its owner, its delegates, its **score** (its points out of its cycles, as a percentage: 3 points in 4 cycles is **75% (3/4)**) and the blocks it produced. **How to become a Super Staker** and **How to Delegate** walk you through the wallet's setup.

## Registering yours

1. **My Super Staker** → **Register Super Staker Address**, and type your super staker's address. An address the Runebase node calls invalid is refused ("You entered an invalid address!"), and nothing is registered.
2. The screen then asks you to **verify** it: send **any amount of RUNES from that address** to the deposit address it shows (your own deposit address, the same as **Pouch → Buy Credits**).
3. Only a payment **from the super staker's address** verifies it; one from any other address doesn't. Once it's verified the bot tells you by DM, and your super staker is in the list.

The RUNES you sent aren't lost: like any [deposit](credits-and-runes.md#deposits), they become credits in your wallet at 6 confirmations.

## A point every 8 hours

At **00:00, 08:00 and 16:00 UTC** every verified super staker gets a **cycle**, and a **point** if it produced a block in the last 8 hours. Your score is your points out of your cycles. **Each cycle counts once:** should the cycle ever run twice within the same 8 hours, the second run counts nothing and posts nothing.

The results are posted in the server's experience channel: who earned a point, who failed to produce a block in the past 8 hours, and who got or lost the role.

## The super staker role

At each cycle:

- **You get the role** when your super staker has at least one delegation and produced a block within the last **72 hours**.
- **You lose it** when it has no delegations left, or produced no block for more than 72 hours.

So a super staker that stops producing blocks keeps the role for 3 days, but gets no points meanwhile; one whose delegators all left loses it at the next cycle.

## Tips

- Keep your super staker's wallet online and staking: every 8 hours without a block is a cycle without a point.
- Verify from the super staker's own address: a payment from any other address does nothing for the verification (it's still credited as a deposit).
