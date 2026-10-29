---
title: "The Jotnar"
icon: guide/nav
nav_emoji: "🗿"
---

# 🗿 The Jotnar: a world boss

**Where to play:** Discord
{ .where-to-play }

A giant appears in the Hack & Slash channel once every 3 hours. Press **Attack Giant** to fight it from your own battle screen; each attack costs 5 stamina. It's built for the whole server: its base health is 85,000, and it escapes after 30 minutes.

- **Bigger servers meet bigger giants:** up to 100 members a giant has its base health, with 1,000 members half again as much, with 10,000 twice as much; each giant also varies from 80% to 120% of that.
- **You hit it as if it were your own level:** its level doesn't make you miss more.
- **When it falls,** its 500 credits are split by damage among the fighters still in the server: each gets exactly their share of their damage times the pool, rounded down. Experience is 50 plus 2 for every 1% of the damage you dealt, up to 150 (a giant beaten alone pays 500 credits and 150 experience).
- **When it escapes,** it pays only if the server took at least 5% of its health together. Then its fighters share half the pool, by damage, scaled to 25% plus 0.75% for every 1% of its health taken: a giant that escapes with 40% of its health gone pays 55% of 250 credits. Experience is 60% (30 plus 1.2 per 1% of the damage you dealt) at the same scale, loot chances are 70%, and the top three get bonus loot only if they dealt at least 25% of the damage. Hit hard together: bringing it down pays far more.
- Each giant pays once. Items it drops go to the first player who picks them up.

## When it comes and goes

- **Each 3-hour window** (from midnight UTC: 00:00, 03:00, …, 21:00) brings one giant at a random moment, announced with the Jotnar role in the Hack & Slash channel, and with a **Join the Battle!** link in the server's announcements. Turn the role on or off in `/hackslash` → **Jotnar** → **Enable Notifications** / **Disable Notifications**.
- **Two giants can be up at once** when one comes late in its window and the next early in the next one: the Jotnar menu lists them all, and you can fight either.
- **A restart of the bot changes nothing:** a giant still standing keeps the time it had left, and one whose time ran out meanwhile escapes (and pays) as soon as the bot is back.

## Fighting it

- **Two ways in:** **Attack Giant** on its message opens your battle privately; `/hackslash` → **Jotnar** → **Join Battle** turns your Hack & Slash screen into your battle. Only you can use the buttons on your battle; anyone else is told they aren't theirs.
- **Each attack costs 5 stamina, hit or miss.** The giant loses exactly the damage your screen shows, and all of it counts as yours. The blow that brings it down counts only the health it had left.
- **Your skills:** pick your main and secondary skills on the battle screen; the attack buttons use them at their mana. Without the mana, the button attacks without the skill and spends none.
- **The giant hits back** at whoever attacked it, no one else, with its attacks at their odds (Thrymr: Frost Slam 40%, Glacial Breath and Icy Gale 30% each), as hard as your level makes them (a level-30 fighter takes 30% of their full damage, at least 10%), plus its aura every round. Below 80%, 50% and 25% of its health it summons a minion (at most two at a time), which hits every fighter after that, as hard as each fighter's level makes it, every round.
- **Its minions:** while one is up, your battle has a **Target** menu: the giant or a minion, numbered in the order they came (*Ice Elemental #1*), with their health. Your attacks hit the one you pick. Damage to a minion doesn't count toward your share (only the giant's health does), but a minion brought down stops hitting everyone. When a minion falls it leaves the menu and your target is the giant again; an attack or a pick aimed at a minion that has already fallen is refused privately, and costs nothing.
- **Falling in battle** costs only that attack's stamina: heal, and your damage is still yours. You can't attack while fallen.
- **Heal** spends one <span class="gi-m">![](../../assets/icons/item/anchovy-with-anchovy-powder.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Anchovy with Anchovy Powder](../../items/consumables/fish-dishes.md#anchovy-with-anchovy-powder)</span> for full health and mana; **Stamina** spends one <span class="gi-m">![](../../assets/icons/item/pheasant-with-blackberry-balsamic-glaze.webp){ .gi .gi-mention width="20" height="20" loading="lazy" }&nbsp;[Pheasant with Blackberry Balsamic Glaze](../../items/consumables/meat-dishes.md#pheasant-with-blackberry-balsamic-glaze)</span> for full stamina. Both ask first (**Accept** or **Back**), and spend nothing when there's nothing to restore, so a double click never costs two. Without one, **Accept** is off and the screen shows where to get one.
- **Animation** turns the battle picture off and on (the same switch as quick battles); **Cancel** closes your battle.
- **The giant's message** shows its health, the last hit and how many are fighting; **Leaderboard** shows you every fighter's damage and share (the top 10 by name); a fighter who has left the server shows without a share.

## The end

- **Brought down:** its message shows the top fighters with their damage and share, and a reward summary lists what each fighter got. Every fighter's loot grows with their share (more kinds of loot from 1%, 2%, 3% and 5% of the damage), the top three get bonus loot, and each giant type has loot of its own.
- **Dropped items:** a button each; the first to press it gets the item, and the button then shows who did. You need a Hack & Slash character to pick one up.
- **Escaped:** its message says how much of its health the server took and that partial rewards went out, or, below 5%, that it paid nothing.
- **Nothing is lost:** a giant brought down just before a restart of the bot pays its fighters as soon as the bot is back, once.
- **Leaving the server** before the giant is paid means no share: the fighters still in the server split the pool between them.

*Checked in play: fighting from both entrances, the giant's attacks at their odds, its minions and the Target menu, the hit chance at your own level, falling and healing, every refusal, someone else's buttons, double clicks on **Accept**, twelve fighters attacking at the same moment (no damage lost or counted twice, each paid once), the payouts against the reward rules (a fighter who left: nothing), the dropped items, the leaderboard, the end messages, and a restart before the payout.*
