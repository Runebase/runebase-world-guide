---
title: "Chess"
icon: guide/nav
nav_emoji: "♟️"
---

# ♟️ Chess

**Where to play:** Discord
{ .where-to-play }

Chess against the bot or against another player. Chess has its own leaderboards (all-time and monthly).

**Where:** `/start` → **Activities** → **Chess**.

## Against the bot (Singleplayer)

**Chess** → **Singleplayer**: pick your side (white, black or random) and a difficulty, then start the game and play against the bot. Pick your move from the menus or type it (SAN Input); the bot answers each move. A move typed wrong is refused on your board (with the moves you can play) and the bot doesn't move.

The bot is the Stockfish chess engine, at the strength of the difficulty:

| Difficulty | The bot plays like | It looks |
|---|---|---|
| easy | a beginner (rated 800) | 3 moves ahead, 0.15 seconds a move |
| medium | a strong club player (rated 2100) | 11 moves ahead, about 2 seconds a move |
| hard | at full strength | 30 moves ahead, up to 25 seconds a move |

The bot sees the whole game, every move played so far, not only the board as it stands: like a player at the table, it knows when a position has come up before.

**Forfeit** asks first (**Cancel** keeps playing); a forfeited game is a loss.

- **Only a win pays:** experience, credits and maybe scrap (table below), and chess points on the leaderboards:

  | Difficulty | Experience | Chess points |
  |---|---|---|
  | easy | 15 | 2 |
  | medium | 20 | 3 |
  | hard | 35 | 5 |

- A loss pays nothing, and neither does a draw or a forfeit. A game is drawn by a stalemate, insufficient material, the fifty-move rule, or **the same position a third time** (by your move or the bot's), and the screen says which.
- **Only the first 5 wins of a UTC day pay.** The next day pays again.
- A new game can start **3 hours** after your last one started.
- Wins also complete the [Chess - Win quests](../account/quests.md#every-quest), which pay their own experience and rewards.
- A win pays once, even when the winning move is clicked twice.

| Difficulty | Credits (always) | Also, each on its own chance |
|---|---|---|
| easy | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 15 to 25 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Leather Scrap](../items/materials/scrap.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Metal Scrap](../items/materials/scrap.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 1 [Wood Scrap](../items/materials/scrap.md#wood-scrap) 25% |
| medium | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 25 to 50 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Leather Scrap](../items/materials/scrap.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Metal Scrap](../items/materials/scrap.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 2 [Wood Scrap](../items/materials/scrap.md#wood-scrap) 25% |
| hard | ![Credits](../assets/icons/currency/credits.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 50 to 85 credits | ![Leather Scrap](../assets/icons/item/leather-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Leather Scrap](../items/materials/scrap.md#leather-scrap) 25%, ![Metal Scrap](../assets/icons/item/metal-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Metal Scrap](../items/materials/scrap.md#metal-scrap) 25%, ![Wood Scrap](../assets/icons/item/wood-scrap.webp){ .gi .gi-inline width="24" height="24" loading="lazy" } 3 [Wood Scrap](../items/materials/scrap.md#wood-scrap) 25% |

Credits always come; each scrap rolls on its own.

## Against other players (Multiplayer)

**A multiplayer game pays nothing:** no credits, experience, chess points or quest progress. You play for the game.

### The challenge

**Chess** → **Multiplayer**: pick the member to challenge, then the settings:

- **Public** (the board is shown in the server's chess channel, for everyone to watch) or **Private** (only the two of you see it);
- **Normal** (3 minutes a move) or **Blitz**: a clock for each side, from 5 to 125 minutes.

**Challenge User** posts the challenge in the chess channel, mentioning you both, with **Accept** and **Decline**: only the challenged player can answer. Your screen says it's sent and has **Cancel Challenge** until they answer, and the way back (**Activities Menu**, **Chess Menu**): you can wait elsewhere, and when they accept, that screen shows the game. A challenge nobody answers expires after **5 minutes** (the channel and your screen say so). The challenged player can also accept it from **View Active Games**.

You can't challenge yourself, a bot or someone who isn't in the server, and you can have one open challenge or game with the same player at a time (with other players, as many as you like). Anything refused changes nothing and says why: on your own screen (your menu or your board) for a second click, a move out of turn or a Cancel after the game started; privately under the challenge's message or on a button that isn't yours.

### Playing

Sides are drawn at random; white moves first. On your turn your screen has your moves: pick a piece and a move and press **Execute Move**, or type the move into **SAN Input** (`e4`, `Nf3`, `O-O`, `exd6`, `e8=Q`). Castling, en passant and promotion (to any piece) work both ways. A move that breaks the rules, or comes when it isn't your turn, is refused on your board, which says why and stays as it was. Your move shows on your opponent's screen with their moves, and a public game's board in the chess channel follows the game.

Discord lets the bot update your screen through your last click for 15 minutes, and a blitz game can run much longer. After that, a screen in the channel (the menu you challenged from) is still updated; a private one (the board **Accept** showed you) can't be: open **View Active Games** to see the board and your moves.

A game ends with a checkmate, a resignation, or in a draw by stalemate, insufficient material (a king against a king and a knight, for example), the fifty-move rule or **threefold repetition**: the same position a third time in the game ends it in a draw, whoever repeats it. A position is the same when the same pieces stand on the same squares with the same player to move, and the same castling and en passant captures possible (a king that walked out and back has lost its castling, so the position before isn't the same one). Both screens and the public board say how the game ended.

### Resigning

While a game runs, both players' screens have **Resign** (on your turn and on your opponent's). It asks first: **Cancel** brings your board back, **Yes, resign** ends the game at once as a loss for you. Your screen, your opponent's and the public board say who resigned and who won. A resigned game pays nothing, like every multiplayer game. **Yes, resign** clicked twice, or at the moment your opponent moves or a timer runs out, ends the game once (a second click is told privately that the game is already over).

### The timers

- **3 minutes a move:** when your time is up, the bot plays a random legal move for you, and both screens say so.
- **12 minutes away** (no click of yours for 12 minutes) and you forfeit: your opponent wins, and both screens say so.
- **Blitz:** your clock runs only during your turns. When it runs out you lose on time.

Only your own moves count: when your move and the turn timer's random move land at the same moment, your move is played; a timer that fires as the game ends doesn't change the result.

**If the bot restarts during your game,** a restart never counts against you: the player to move gets a DM and **15 minutes** before any timer counts again (a blitz clock is paused through them). A challenge waiting at a restart expires once it's 5 minutes old.

### Your games and your history

**View Active Games** lists your challenges and games: pick one to see your board again (your moves on your turn), to wait on (or cancel) a challenge you sent, or to accept one sent to you. It shows at most 25 (Discord's limit for a list): the games in progress first, then the challenges sent to you, then the ones you sent, newest first; with more, the screen says how many you have.

**Chess History** (in the Chess menu) shows every game you played, single player and multiplayer, as white or black, move by move. **Export FEN** gives you, privately, the position on the board at the move shown (finished games only).

## Tips

- Chess pays only 5 wins a day; a hard win pays the most.
