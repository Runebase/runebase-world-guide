---
title: "Roles"
icon: guide/nav
nav_emoji: "🏷️"
---

# 🏷️ Roles

The top players of many <span class="gi-m">🏅&nbsp;[leaderboards](leaderboards.md)</span> hold a role, and `/rolepanel` has roles you can give yourself.

## Top roles

Many boards give a role to their **top 10** players (the experience board also to the top 20 and top 30). When you pass someone, the role moves to you; when you drop out, it goes to the next player.

- A board with fewer than 10 players who scored gives its role only to those who scored.
- After a restart, the roles match `/leaderboard` again. So they do within a minute when a server is switched on or its admins set a top role with `/config`, without a restart.
- On a tie at the last place the newer Discord account gets the role (the <span class="gi-m">🏅&nbsp;[leaderboards'](leaderboards.md)</span> order).
- Leaving the server takes you off the boards at once, and your top roles go to the next players. Points you'd lose while away don't put you back; coming back does.
- A player banned from the bot is off every board too, with no top role, paid ladder prize or winners role; lifting the ban puts them back with their scores.

## The Excellers role

Where the server has an **Excellers** role, it goes to every player whose 30-day experience (the Monthly Accelerator <span class="gi-m">🏅&nbsp;[leaderboard](leaderboards.md)</span>) is **above the server's requirement**: 65% of the average 30-day experience of the players above 350, rounded. For example, with two players above 350, at 360 and 700, the requirement is 345: 346 or 350 holds the role, 345 doesn't. The requirement is worked out again every day at 06:45 UTC (and announced in the server's chat channel), and the role follows your experience with every gain or loss, and at every restart.

## The role panel

`/rolepanel` shows the roles you can give yourself, one at a time (pick one in **Select Role**). Press **Earn** to take it or **Remove** to give it back. Some roles need a minimum amount of experience: below it, the panel shows the role with the button off. Only the player who opened the panel can use its buttons.

**Earn** only gives the role and **Remove** only takes it, whatever another screen did: from a panel opened before your other panel's click, Earn says "You already have the … role: nothing changed." (and Remove "You don't have the … role"), and a double click acts once. The heist's role works the same from the heist menu ([joining and leaving](../games/heists-and-clans/index.md#joining-and-leaving)).
