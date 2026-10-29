---
title: "The round and the reign"
icon: guide/nav
nav_emoji: "📊"
---

# 📊 The round and the reign

**Where to play:** Discord
{ .where-to-play }

## The round, every minute

- The Crown gets **1 point**: on the reign, on the Crown of Chaos leaderboards (all-time and monthly, with their top-10 roles) and on the weekly ladder. Every 5th point it regenerates health.
- Every attacker's points shrink by 0.35%, and every attacker gets mana back.
- <span class="gi-m">![](../../assets/icons/crown-skill/bleed.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Bleeds](skills/offensive/bleed.md)</span> and <span class="gi-m">![](../../assets/icons/crown-skill/doomseed.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[seeds](skills/offensive/doomseed.md)</span> on the Crown run; their damage counts for whoever cast them. A bleed or a detonation can end the reign.
- Sometimes the round drops a **tax pile** (3% of the pool) in the Crown of Chaos channel, collected like a credit pile. A hit can drop one too (1% of the pool). Each tax pile is for **3, 4 or 5 players** (drawn for each pile, the pile says how many), who get equal shares, rounded down; what the rounding leaves over stays in the pool. An empty pool drops no pile.
- **The handicap:** once the first 30 minutes of a reign are over, every round adds 1000% ÷ 10,080 to the Crown's handicap (up to 1,000% after 7 days), and every attack's damage is multiplied by (1 + handicap). A former Crown's handicap shrinks at a quarter of that speed, until it's gone. **Handicap List** on the Crown of Chaos menu shows everyone's handicap, ten players a page (**Next**, **Previous**). The attack report (and a bleed's or seed's message) shows the extra damage: none when nothing was dealt (a dodge, a miss, or a hit the Bubble absorbed). The handicaps are reset once a week: on Monday at 00:00 UTC (or, if the bot was down then, when it starts again that week).

## Points

Your **points** in a reign are the damage you dealt (bleeds and detonations included), shrinking a little every round. **The final blow adds 200 points.** The **Attack Score Board** ranks the attackers by points (and shows their damage), ten a page (**Next**, **Previous**): that's the order of the draw for the next Crown and of the top-three RUNES shares.

## The end of a reign

When an attack or a round's bleed brings the Crown to 0:

1. **The next Crown is drawn** among everyone with points in this reign who is still in the server: each player's chance is exactly their share of all the points. The draw is posted with its roll and each player's range (300 points of 750 is "0.00-299.99", the next player's starts at 300.00, and so on); a player with 0 points has no chance. The final blow's 200 points help, but don't crown you by themselves. When nobody who attacked the reign is still here, the next Crown is drawn among the server's players instead: someone with an account who is still a member, never a bot and never the Crown that just fell, behind the usual seizure bubble; the channel says so. If nobody in the server can take it yet, the channel says so too, and a reign starts at the first minute's round after someone can.
2. **The old Crown gets the whole pool** in credits, once (the one prize not capped at 25,000 credits). The pool starts again at 0.
3. **<span class="gi-m">![](../../assets/icons/currency/runes.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[RUNES](../../account/credits-and-runes.md#runes-prizes)</span>** (a share of the realm's RUNES wallet, tipped): the old Crown gets **0.000032407% per point**, counting at most **19,999 points**; the final blow gets 3.5% of that while still in the server (a bleed or seed of a player who left can land it: their share stays in the wallet, and the end result says so), and the top three by points still in the server 5%, 3.5% and 1.5% of it (someone who left the server gets no share, and the next one moves up).
4. **Experience:** the old Crown gets 0.85 × its points, at most **8,999**; a <span class="gi-m">![](../../assets/icons/emoji/quest.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[quest](../../account/quests.md)</span> completed in the same round (Points Earned) pays its experience on top (a 1,000-point reign: 850 + the quest's 65; an 11,000-point reign: 8,999 + 65).
5. The Crown role moves to the new Crown, who starts with a seizure bubble.

- Two final blows at the same moment (a round and an attack, two attackers, a double click) end the reign once and pay the pool once. An attack and the minute's round at the same moment both count, one after the other.
- A restart of the bot in the middle of a round: the round counts entirely or not at all, and the next minute's round counts once.
- A Crown who is still in the server keeps the reign even if the bot briefly thinks otherwise: only a Crown Discord confirms as gone loses it.
- If the tipbot is unreachable, the reign still ends and the pool is paid; no RUNES are tipped or promised. When the realm's RUNES wallet holds 1 RUNES or less, or its RUNES prizes aren't connected yet (every server but the Runebase server, until after the update), the reign ends the same way, the pool and the experience paid, and the end result says why no RUNES were paid.

## A Crown who leaves the server

A Crown who leaves the server **loses the reign without any reward**: until the next round, attacks on them are refused (nothing is spent); then the round ends the reign, the next Crown is drawn from the attackers still in the server (with none of them still here, among the server's players, as above), and the pool stays for the next reign.

## The pool

The pool grows with **5% of every store purchase** in the realm and the **unclaimed shares of expired credit piles**. It shrinks by <span class="gi-m">![](../../assets/icons/crown-skill/robin-hood.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Robin Hood](skills/offensive/robin-hood.md)</span> and <span class="gi-m">![](../../assets/icons/crown-skill/black-hood.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Black Hood](skills/offensive/black-hood.md)</span> steals and the tax piles (a tax pile takes its credits from the pool only when it appears: one that can't be posted, or a restart before it appears, leaves them in the pool). The old Crown gets what's left when the reign ends.
