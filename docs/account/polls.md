---
title: "Polls"
icon: guide/nav
nav_emoji: "🙋"
---

# 🙋 Polls

`/poll` posts a poll (**🙋 Poll #N**) with a button per answer. **Your vote weighs your experience ÷ 350** (rounded down); under 350 experience you can't vote. You vote once. When the time is up, the result shows every answer's weight and voters, and the winner. A poll running when the bot restarts keeps going.

- **One vote, whatever you click:** two clicks at once (on two answers too) count one vote, and the other click says "We already received a vote from you". Two players voting at the same moment both count, and the poll shows the tally after both.
- **The poll ends when its time is up:** a vote that comes as it ends isn't counted ("This poll has ended: your vote wasn't counted."), and a poll's button after the end (on a screen that still shows it, or copied anywhere else, another server included) says "This poll has ended: it takes no more votes."
- Only the poll's own answer buttons count: anything else is refused ("That answer isn't on this poll: pick one of its buttons.").

Every answer to your click is private: only you see it.
