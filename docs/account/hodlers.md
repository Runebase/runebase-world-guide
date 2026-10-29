---
title: "Hodlers"
icon: guide/nav
nav_icon: "assets/icons/emoji/hodl.webp"
---

# ![Hodlers](../assets/icons/emoji/hodl.webp){ .gi .gi-title width="64" height="64" loading="lazy" } Hodlers

Hold RUNES in your own wallet and show it: link one of your Runebase addresses, and the bot gives you the **hodler role** its balance reaches. Open it from `/start` → **Ranks** → **Hodlers**.

## The roles

The **Hodlers** page lists the server's hodler roles, each with the RUNES balance it needs, the one you hold marked. Your linked address gets the highest role its balance reaches, and only that one: the bot checks every linked address again, one after another, for as long as it runs, so a balance that grows or shrinks moves your role up or down.

## Linking your address

1. The **Hodlers** page shows your own **hodler deposit address** (with its QR code) while no address is linked.
2. Send **any amount of RUNES** to it **from the address you want to link**. The payment is what proves the address is yours; it isn't credited to your wallet (that's your `/pouch` deposit address, a different one).
3. The address is linked: the page shows it, the bot tells you by DM, and you get the role its balance reaches.

## In more than one server

Each server has its own hodler roles, with its own balances; a server without any says "This server has no hodler roles yet." You can link **the same address in every server you play in**: each server shows its own hodler deposit address, and a payment to it links your address in that server only, so a wallet stays out of a server until you pay that server's address. One payment can pay several of your hodler deposit addresses at once and links each of them. Once linked, every server gives you its own role for the same balance.

An address belongs to one Discord account: if another player pays from an address you linked, they're refused, and their DM names the address.

## Unlinking

**Unlink Hodler Address** asks first: **Cancel** keeps it, **Confirm Unlink Hodler Address** unlinks it and your hodler role goes. The page then shows your hodler deposit address again, to link another one.
