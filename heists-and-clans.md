---
title: Heists and clans
permalink: /heists-and-clans/
---

[← All pages]({{ '/' | relative_url }})

# Heists and clans

In a heist you steal **experience** from another player, not credits. Buffs, gear, pets, a building and a clan change the odds. Every heist counts on a monthly ladder; its best players win a role, and the ladder can pay RUNES prizes.

**Where:** `/heist` (pick the player and the attack type), or `/start` → **Activities** → **Heist** for the heist menu (joining, buffs, gear, clans, the attack guide). `/heistboard` shows the ladders, `/browseclans` lists the clans.

## Joining and leaving

- **Join** from the heist menu (**Join** → **Confirm join**). You need a minimum amount of experience, which the menu shows ("You need at least … experience to join the heist games!"). Only players who joined can heist and be heisted.
- If your experience drops below that minimum after a heist, you lose your place in the heist game.
- **Leaving puts you in a protective bubble:** nobody can heist you, and you can't heist. The bubble has limits:



| Rule | Limit |
|---|---|
| Leaving the heist (a bubble), per calendar month | 3 |
| Earliest bubble after joining | 2 days |
| No bubble in the last days of the month | 3 days |
| Waiting time to rejoin after bubble 1 of the month | 24 hours |
| Waiting time to rejoin after bubble 2 of the month | 48 hours |
| Registering a clan | 15,000 credits |
| Members in a clan | at most 5 |
| Accepted joins per clan per month | at most 10 |



- After your **3rd** bubble of a month you can't rejoin until the next month begins: the heist menu's join button stays locked, and `/rolepanel` refuses privately.
- Joining stays open in the month's last 3 days; only leaving is closed then.
- Left in an earlier month, or lost your place? In a new month you can rejoin right away (with enough experience).

## Energy and hits

- You have **3 heist energy** a day, and you can be heisted **6 times** a day. Both refill at 00:00 UTC.
- An attack costs 1 energy (unless you recover it, below). Every heist on you uses one of your 6 daily hits, also a blocked one.
- **Mímisbrunnr** (in the heist menu): sacrifice an eye, once a month, to refill your heist energy and your daily hits. It's closed in the last 3 days of the month.

A heist is refused, and nothing changes, when you're out of energy, when you target yourself, a player in a bubble or who never joined, a player who left the server, a player already hit 6 times today, or a member of your own clan. If you haven't joined, `/heist` tells you heists aren't enabled for you.

## One heist

The attacker gains **10** experience and the defender loses **10**, plus the attack type you chose:

| Attack type | Effect |
|---|---|
| +1 Increased Experience Gain | you gain 1 more |
| +1 Increased Opponent Experience Loss | the defender loses 1 more |
| +5% Recovery Chance | 5% more chance to keep your energy |
| +3% Gain Retribution Fury | 3% chance to earn a Retribution Fury charge |
| +4% Gain Assault Fortification | 4% chance to earn an Assault Fortification charge |

Then the chances roll:

- **Recovery:** the attack costs no energy (it still scores its energy on the ladder).
- **Block:** the defender blocks; nobody gains or loses experience, but it's still one of the defender's daily hits.
- **Counter-attack:** the defender strikes back: the defender wins back 10 and the attacker loses 10 (so with the default attack type, the attacker ends at +1 and the defender at 0). It counts as a hit on the attacker's ladder, not on their daily hits.
- **Deflect:** the heist lands on another heister instead, who takes the hit; the defender is untouched (and gets a deflect on their stats). It never lands on a member of the attacker's clan; with nobody to take it, there's no deflection.

Nobody's experience goes below 0: a defender with 4 experience loses 4, and the attacker still gains the full amount.

After each heist the attacker gets a private message ("Heist Energy Left: n/3"), and the heist channel shows everyone what happened: each side's buffs, the experience moved, the scores, energy and hits.

## Buffs

Eat a buff from the heist menu's **Heist Buffs**; each one you eat is one **charge**. **Every charge you hold that applies to your side is used on every heist you're in, one charge each**, whether it changed the outcome or not.

| Buff | Effect | Used when |
|---|---|---|
| Wild Turkey with Cranberry Glaze | +2 experience gained | attacking; also in your counter-attack |
| Fried Squirrel with Sawmill Gravy | the defender loses 1 more | attacking; also in your counter-attack |
| Grilled Eel with Sichuan Peppercorns | 5% chance to keep the energy | attacking |
| Moose with Blueberry Sauce | 10% chance to block | defending; attacking, only when you're counter-attacked |
| Seared Tuna with Wasabi Butter | 3% chance to counter-attack | defending |
| Mackerel and Smoked Paprika | 1 less experience lost | defending; attacking, only when you're counter-attacked |
| Einherjar's Barrier Draught (super buff) | 100% block | defending; attacking, only when you're counter-attacked |
| Skadi's Retribution Brew (super buff) | 100% counter-attack | defending |
| Frigg's Resurgence Elixir (super buff) | 100% chance to keep the energy | attacking |
| Retribution Fury (earned) | 100% counter-attack | defending |
| Assault Fortification (earned) | 100% block | defending; attacking, only when you're counter-attacked |

- A buff used "only when you're counter-attacked" (Moose, Mackerel, Barrier Draught, Assault Fortification) stays when you attack and nobody strikes back.
- **Super buffs:** at most **5** a month. You must be on this month's heist ladder: you are once you joined, attacked or were attacked this month (in the heist since an earlier month, you're refused until then, and nothing is taken). For a clan member, the clan must be on this month's clan ladder too (opening the heist menu puts it there); both count them. A 6th is refused and nothing is taken.
- **Super buff charges you haven't used are gone at the month change:** the new month's first run resets them to 0. Your other buffs stay.
- **Earned buffs** come from the attack types above, and from gear and pets that add a chance to earn them: each win adds one charge.



| Buff | Where it comes from |
|---|---|
| Wild Turkey with Cranberry Glaze | cooked: 2 Wild Turkey + 2 Cranberry Glaze |
| Fried Squirrel with Sawmill Gravy | cooked: 2 Squirrel + 1 Sawmill Gravy |
| Grilled Eel with Sichuan Peppercorns | cooked: 2 Eel + 4 Sichuan Peppercorns |
| Moose with Blueberry Sauce | cooked: 2 Moose + 2 Blueberry Sauce |
| Seared Tuna with Wasabi Butter | cooked: 2 Tuna + 6 Wasabi |
| Mackerel and Smoked Paprika | cooked: 2 Mackerel + 4 Smoked Paprika |
| Einherjar's Barrier Draught | 850 credits in the store (a super buff) |
| Skadi's Retribution Brew | 850 credits in the store (a super buff) |
| Frigg's Resurgence Elixir | 850 credits in the store (a super buff) |



## Gear

Heist gear is crafted with scrap from the heist gear menu (it costs exactly the scrap listed). You wear one item per slot: shield, weapon, helm, armor and ring. Equipping another item in a slot takes the first one off.

- **Without Tactical Shift** (the default), your **neutral** set counts both when you attack and when you defend.
- **With Tactical Shift** (**Enable Tactical Shift** in the heist menu), your **offensive** set counts when you attack and your **defensive** set when you defend; the neutral set rests.
- An attacking bonus only works when you attack, a defending bonus when you defend (and when you're counter-attacked).



| Item | Slot | When attacking | When defending | Crafting cost (wood / metal / leather scrap) |
|---|---|---|---|---|
| Ironbark Bulwark | shield | – | Block Chance +4% | 250 / 300 / 50 |
| Sif's Nature's Embrace | shield | Recovery Chance +2% | – | 300 / 50 / 250 |
| Njord's Serene Barrier | shield | – | Lessen Exp Loss -1 | 250 / 200 / 150 |
| Baldur's Deflective Guard | shield | – | Deflect Chance +2% | 200 / 300 / 125 |
| Odin's Furyblade | weapon | Increased Exp Gain +1 | – | 225 / 275 / 100 |
| Freyja's Enchanting Whisper | weapon | Recovery Chance +3% | – | 200 / 100 / 300 |
| Valkyrie's Vengeance | weapon | – | Counter-Attack Chance +2% | 275 / 150 / 175 |
| Forseti's Judgment | weapon | Increased Opponent Exp Loss +1 | – | 200 / 200 / 200 |
| Baldur's Shimmering Helm | helm | – | Deflect Chance +1% | 125 / 300 / 200 |
| Valkyrie's Vengeful Visor | helm | – | Counter-Attack Chance +1.25% | 75 / 300 / 250 |
| Mimir's Cap of Insight | helm | Recovery Chance +1.5% | – | 100 / 150 / 375 |
| Baldur's Reflective Shell | armor | – | Deflect Chance +3% | 125 / 575 / 250 |
| Skadi's Rejuvenating Shroud | armor | Recovery Chance +1.5%, Gain Retribution Fury (Counter Attack Buff) +2% | – | 100 / 225 / 625 |
| Einherjar's Rejuvenating Cuirass | armor | Recovery Chance +1.5%, Gain Assault Fortification (Block Buff) +1.75% | – | 100 / 625 / 225 |
| Baldur's Gleaming Band | ring | – | Deflect Chance +1.25% | 75 / 175 / 50 |
| Einherjar's Wrathful Loop | ring | Gain Assault Fortification (Block Buff) +1% | Counter-Attack Chance +0.25% | 50 / 200 / 50 |
| Skadi's Frostbite Ward | ring | Gain Retribution Fury (Counter Attack Buff) +1% | Block Chance +0.25% | 25 / 200 / 75 |



## Pets, buildings, clans

- **Pets:** your active pet's heist perk counts while it's awake and cared for; asleep, it doesn't. Every pet's perks: [Pets]({{ '/pets/' | relative_url }}).
- **Thieves Den** (a building): +0.035% chance per level that an attack keeps its energy.
- **Heist Clan Protection:** a defender who is in a clan loses 1 less experience.

## Clans

- **Register** a clan from the clan menu: it costs **15,000 credits** (the only clan action that costs credits). With fewer credits, or a name already taken, nothing is spent.
- **Join** by request: find a clan with `/browseclans` (every open clan, page by page) and ask to join; the leader accepts or declines. A full clan can't accept. If you founded your own clan meanwhile, the leader is told you're already in a clan.
- The leader can pass the leadership and kick members. When the last member leaves, the clan closes.
- Clanmates can't heist each other, and a deflection never lands in the attacker's clan.
- A heist between members of two clans also counts for both clans' ladders.

Prize tables are without utilities: a Wood Axe, Skinning Knife or Mining Pick raises the scrap rows ([activities]({{ '/activities/' | relative_url }})).



| Prize | Chance per roll |
|---|---|
| 1 Gold Key | 1% |
| 1 Silver Key | 2% |
| 1 Bronze Key | 4% |
| 2 Mystery Card | 2% |
| 1 Mystery Card | 10% |
| 1 Runes Pattern Card | 5% |
| 1 Metal Scrap | 10% |
| 1 Wood Scrap | 10% |
| 1 Nail | 2% |
| 1 Rope | 0.5% |
| 1 Chaos Relic | 3.5% |
| 1 Engraving Tool | 3.5% |
| 1 Common Pet Token | 1% |
| 1 Pet Token (Uncommon, Rare, Epic, Legendary, Mythical) | 0.5% each |
| 1 to 10 credits | 25% |
| nothing | 18% |



Every heist gives the attacker **one** draw of this table, also when it's blocked, counter-attacked or deflected; the defender draws nothing.

## Score, ladders and prizes

Your heist score is: **5 per energy used + 1.25 × experience gained (rounded) − experience lost + 3 per hit taken.** The energy counts even when it was recovered; a blocked hit counts nothing. The ladder counts each heist's full amounts: a defender with less experience than the heist takes still has the full loss on the ladder.

- `/heistboard` shows this month's clan ladder first, then the all-time clans, this month's players and the all-time players, 10 to a page.
- **Monthly winners:** last month's **top 5** heisters get the heist winners role, and only they keep it. A player whose month ended at zero or below gets no role.
- **Winning clan:** on the 1st, the members of last month's best clan get the clan winners role, and only they keep it. A clan whose month ended at zero or below wins nothing.
- **Monthly RUNES prizes,** when the staff pay them (on the Runebase server): last month's best heisters share **2% of the realm's RUNES wallet** by rank (table below); only positive scores are paid. Only the staff pay the clans' prize (it's never paid automatically): the best clans share **1.5%** by clan rank, split equally among each clan's members. Players who left the server are left out, and the next player moves up. A month is paid once.

**Heisters**



| Rank | Shares of the pool, each |
|---|---|
| 1 | 15 |
| 2 | 12 |
| 3 | 10 |
| 4 to 5 | 6 |
| 6 to 10 | 4 |
| 11 to 25 | 2 |
| 26 to 50 | 1 |



**Clans**



| Clan rank | Shares of the pool, each |
|---|---|
| 1 | 20 |
| 2 | 15 |
| 3 | 10 |
| 4 to 5 | 6 |
| 6 to 10 | 3 |



## Tips

- Every charge that applies to your side is used on every heist: eat buffs for the heists you're about to do.
- A clan protects you (1 less experience lost) and keeps clanmates from heisting you.
- Super buffs are limited to 5 a month.
