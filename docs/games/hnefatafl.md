---
title: "Hnefatafl"
icon: guide/nav
nav_emoji: "⚔️"
---

# ⚔️ Hnefatafl

**Where to play:** Discord
{ .where-to-play }

The Viking board game, new in this release, against the bot or against another player. Hnefatafl has its own leaderboards (all-time and monthly).

**Where:** `/start` → **Activities** → **Hnefatafl**.

## The rules

Two sides on an **11 × 11** board (the Copenhagen rules):

- **The attackers** (24 pieces) move first and win by **surrounding the King on all four sides**. A King on the edge of the board can't be captured.
- **The defenders** (12 pieces and the King, who starts on the throne in the middle) win when **the King reaches a corner**.
- **Encirclement:** the attackers also win when their move closes a ring around the King and **every** remaining defender, so that none of them can reach the edge of the board. Pieces move in straight lines, so attackers touching corner to corner close the ring. A ring with a gap, a defender left outside it, or a ring that leaves the King room to reach the edge is no encirclement.
- **Exit fort:** the defenders also win when, after their move, the King stands on the edge of the board, can still move, and is walled in by defenders the attackers can never capture: only defenders and the edge around the King's free squares, and every one of those defenders backed (on each line, across and along, at least one neighbour the attackers can never take: the edge, the King's free squares, or another such defender). A wall piece with open squares on both sides of a line, an attacker touching the King's squares, or a King with no free square is no fort. The King inside his fort but off the edge isn't a win yet; back on the edge it is.
- Pieces move in straight lines, any number of free squares, and can't jump. Only the King may stop on the throne or the corners.
- A piece is captured when it's **sandwiched** between two enemies (a corner and the empty throne count as enemies). Moving into a sandwich yourself is safe. A row of defenders along the edge can be captured by a shieldwall.
- A side with no legal move loses.
- **The same position a third time is a draw:** when the same pieces stand on the same squares with the same side to move for the third time in a game (counted over the whole game), the game ends in a draw, whichever side repeats (the published Copenhagen rules make a repetition a loss for the King's side instead). Moving a piece out and back while your opponent does the same ends the game on the 8th such move.
- A move that breaks the rules is refused and the board stays as it was.

## Against the bot (Singleplayer)

**Hnefatafl** → **Singleplayer**: pick a difficulty and your side (the King's side, the attackers, or random), then start. The attackers move first, so as the King's side you find the bot's opening move already played. Type your moves into **Make Move** as `from-to` (`f8-f9`); the bot answers each one. A move that breaks the rules is refused privately and the board stays.

| Difficulty | The bot thinks |
|---|---|
| easy | 1 move ahead, and picks among its nearly best moves at random |
| medium | 2 moves ahead |
| hard | 3 moves ahead |

**Forfeit** asks first (**Cancel** keeps playing); **Yes, forfeit** ends that game as a loss, once (clicked again, it says privately that the game is already over, and it never ends a newer game). A new game can start right away: unlike chess, there's no wait between games.

A win pays credits and maybe scrap, by difficulty (table below); every way of winning counts (the King's escape, a capture, an encirclement, an exit fort, no legal move left). A loss and a forfeit pay nothing. **Only the first 5 wins of a UTC day pay**; the 6th says so and pays nothing. Hnefatafl gives no experience: its Win quests pay their other rewards. A draw (a position played a third time) pays nothing, counts for no Win quest, and isn't one of your 5 paid wins.

| Difficulty | Credits (always) | Also, each on its own chance |
|---|---|---|
| easy | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 15 to 25 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Leather Scrap](../items/materials/scrap.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Metal Scrap](../items/materials/scrap.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Wood Scrap](../items/materials/scrap.md#wood-scrap) 25% |
| medium | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 25 to 50 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Leather Scrap](../items/materials/scrap.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Metal Scrap](../items/materials/scrap.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Wood Scrap](../items/materials/scrap.md#wood-scrap) 25% |
| hard | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 50 to 85 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Leather Scrap](../items/materials/scrap.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Metal Scrap](../items/materials/scrap.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Wood Scrap](../items/materials/scrap.md#wood-scrap) 25% |

## Against other players (ranked)

### The challenge

**Hnefatafl** → **Multiplayer** (the lobby): pick your side (random, the King's side or the attackers) and the member to challenge. Your challenge is posted in the server's Hnefatafl channel, mentioning them (no DM), with who plays which side and **Accept** and **Decline**, which only they can use; they also find it in their lobby (**Refresh**) with **Accept** and **Decline**; your lobby lists it with **Cancel**. When they accept or decline, you cancel, or the challenge expires, the post and your lobby say so at once, and the post's buttons go. **Accept** on the post shows them their board privately, and the game is on. Every challenge in your lobby has its buttons, the ones sent to you first. A challenge nobody answers expires after **30 minutes** (a restart gives a waiting challenge a fresh 30 minutes).

A server without a Hnefatafl channel can't take challenges: yours is refused privately and nothing is sent (an admin sets the channel with `/config`, **Hnefatafl Channel**).

You can't challenge yourself or a bot, and you can have one open challenge or game with the same player at a time. Anything refused (a late Accept, a second click, a button that isn't yours, a move from an old screen) is answered privately and changes nothing.

### How a game ends

The King escapes to a corner, the King is captured, the attackers ring in the King and every defender (encirclement), the King holds an exit fort, the side to move has no legal move, the same position comes a third time (a draw), a player resigns (**Resign**), or the player to move doesn't move within **15 minutes** (they lose). The game then leaves both lobbies.

**Resign** asks first, on your turn or your opponent's: **Cancel** brings your board back, **Yes, resign** ends the game at once as a loss for you, and both screens say so. **Yes, resign** clicked twice ends the game once (the second click is told privately that the game is over), and a **Yes, resign** left from an earlier game never ends a newer one.

### Your screen follows the game

Challenges, moves and endings come without a DM (only the notice after a restart still does). Instead, your Hnefatafl message follows the game: the board you last looked at, or your lobby if you haven't opened the game. When your opponent moves, it shows their move and, on your turn, your **Make Move**; when the game ends (a move, a resignation, a timeout), both players' messages show the result, with a note when the game scored no ranked points. Leave Multiplayer for the Hnefatafl menu or Singleplayer and that message is left alone; your lobby shows your games when you come back.

Discord lets the bot update a message through your last click for 15 minutes. After that, a message in the channel is still updated; a private one can't be (open your lobby to see the game). The board **Accept** on the post showed you is private.

### Ranked points

Multiplayer games score **ranked points** on the Hnefatafl leaderboards: **25 for a win, 5 for a loss, 12 each for a draw**. To stop farming:

- a game only scores when both sides made at least 10 moves (a game resigned in its first moves scores nothing);
- the same two players score at most **3** ranked games a day (another opponent still scores);
- a player scores at most **5** ranked games a day, whoever the opponents are;
- you can't challenge yourself.

A draw comes from playing the same position a third time (see the rules above), and scores 12 each, once.

The boards: `/leaderboard` → **All-Time Hnefatafl Points** or **Monthly Hnefatafl Points**, best first.

Only the side to move may move, each player from their own screen; a move sent from a second **Make Move** after yours is refused (it isn't your turn), and so is a move sent after the game ended. A move and a resignation at the same moment end the game once and score once. An abandoned game times out once, within the same limits. A restart never counts against you: as in <span class="gi-m">♟️&nbsp;[chess](chess.md)</span>, the player to move gets a DM and 15 minutes.

## Tips

- Hnefatafl pays only 5 wins a day; a hard win pays the most.
