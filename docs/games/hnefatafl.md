---
title: "Hnefatafl"
---

# Hnefatafl

**Where to play:** Discord
{ .where-to-play }

The Viking board game, new in this release, against the bot or against another player. Hnefatafl has its own leaderboards (all-time and monthly).

**Where:** `/start` → **Activities** → **Hnefatafl**.

## The rules

Two sides on an **11 × 11** board (the Copenhagen rules):

- **The attackers** (24 pieces) move first and win by **surrounding the King on all four sides**. A King on the edge of the board can't be captured.
- **The defenders** (12 pieces and the King, who starts on the throne in the middle) win when **the King reaches a corner**.
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

**Forfeit** ends the game at once (it doesn't ask) as a loss. A new game can start right away: unlike chess, there's no wait between games.

A win pays credits and maybe scrap, by difficulty (table below). A loss and a forfeit pay nothing. **Only the first 5 wins of a UTC day pay**; the 6th says so and pays nothing. Hnefatafl gives no experience: its Win quests pay their other rewards. A draw (a position played a third time) pays nothing, counts for no Win quest, and isn't one of your 5 paid wins.

| Difficulty | Credits (always) | Also, each on its own chance |
|---|---|---|
| easy | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 15 to 25 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Leather Scrap](../items/materials.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Metal Scrap](../items/materials.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Wood Scrap](../items/materials.md#wood-scrap) 25% |
| medium | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 25 to 50 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Leather Scrap](../items/materials.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Metal Scrap](../items/materials.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Wood Scrap](../items/materials.md#wood-scrap) 25% |
| hard | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 50 to 85 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Leather Scrap](../items/materials.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Metal Scrap](../items/materials.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Wood Scrap](../items/materials.md#wood-scrap) 25% |

## Against other players (ranked)

### The challenge

**Hnefatafl** → **Multiplayer** (the lobby): pick your side (random, the King's side or the attackers) and the member to challenge. They get a DM and find your challenge in their lobby (**Refresh**) with **Accept** and **Decline**; your lobby lists it with **Cancel**. Every challenge in your lobby has its buttons, the ones sent to you first. A challenge nobody answers expires after **30 minutes** (a restart gives a waiting challenge a fresh 30 minutes).

You can't challenge yourself or a bot, and you can have one open challenge or game with the same player at a time. Anything refused (a late Accept, a button that isn't yours, a move from an old screen) is answered privately.

### How a game ends

The King escapes to a corner, the King is captured, the side to move has no legal move, the same position comes a third time (a draw), a player resigns (**Resign**), or the player to move doesn't move within **15 minutes** (they lose). The player whose move or click ended the game sees the result on their screen; the game then leaves both lobbies (Discord doesn't tell the other player otherwise, nor whose turn it is: **Refresh** your lobby to see).

### Ranked points

Multiplayer games score **ranked points** on the Hnefatafl leaderboards: **25 for a win, 5 for a loss, 12 each for a draw**. To stop farming:

- a game only scores when both sides made at least 10 moves (a game resigned in its first moves scores nothing);
- the same two players score at most **3** ranked games a day (another opponent still scores);
- a player scores at most **5** ranked games a day, whoever the opponents are;
- you can't challenge yourself.

A draw comes from playing the same position a third time (see the rules above), and scores 12 each, once.

The boards: `/leaderboard` → **All-Time Hnefatafl Points** or **Monthly Hnefatafl Points**, best first.

Only the side to move may move, each player from their own screen; a move sent from a second **Make Move** after yours is refused (it isn't your turn), and so is a move sent after the game ended. A move and a resignation at the same moment end the game once and score once. An abandoned game times out once, within the same limits. A restart never counts against you: as in [chess](chess.md), the player to move gets a DM and 15 minutes.

## Tips

- Hnefatafl pays only 5 wins a day; a hard win pays the most.
