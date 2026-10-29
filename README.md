# Runebase World Guide

How the Runebase games work: the Discord bot today, the Runebase World web app
and its MMORPG later. Published at https://runebase.github.io/runebase-world-guide/.

Everything here is generated from `docs/player-guide` in the Runebase Discord
bot's repository (`npm run guide:publish`): edit the guide there, never here.
Every rule in it is proven by the bot's tests, and the numbers come from the
game data.

The site is MkDocs Material with mike (`requirements.txt`): every version
of the guide is a folder on the `gh-pages` branch, which
`.github/workflows/publish.yml` builds on every push and deploys to GitHub
Pages (Pages source: GitHub Actions). `next` is the guide to the coming update
(`main`); a tag `vX.Y.Z` (`npm run guide:publish -- --release` at a
release) is that release's guide, built once and then left as it was; the
newest is also `latest`, where the site opens. To look at it locally:
`pip install -r requirements.txt`, then `mkdocs serve`.
