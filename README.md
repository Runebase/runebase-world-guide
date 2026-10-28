# Runebase World Guide

How the Runebase games work: the Discord bot today, the Runebase World web app
and its MMORPG later. Published at https://runebase.github.io/runebase-world-guide/.

Everything here is generated from `docs/player-guide` in the Runebase Discord
bot's repository (`npm run guide:publish`): edit the guide there, never here.
Every rule in it is proven by the bot's tests, and the numbers come from the
game data.

The site is MkDocs Material (`requirements.txt`), built and deployed by
`.github/workflows/publish.yml` on every push to `main` (Pages source:
GitHub Actions). To look at it locally: `pip install -r requirements.txt`,
then `mkdocs serve`.
