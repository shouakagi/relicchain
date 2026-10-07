# Relicchain
![Relicchain logo](assets/logo.png)

**History stays, ownership moves: tokenize real-world memorabilia without moving it.**

## Overview

Relicchain is a platform that lets venues and teams mint RWA tokens for physical memorabilia kept on display, while ownership trades on Solana via USDC. QR/NFC codes link each item to its on-chain twin, showing provenance, custody status, and enabling instant purchase or offers.

## Problem

Historical and cultural memorabilia sits idle in storage or display cases, generating no ongoing economic value for the owners or venues that hold it. These items could be generating revenue and deepening fan engagement, but there's no simple way to make that happen without moving or risking the physical object.

## Solution

Relicchain separates physical custody from economic ownership. The item stays safely in a vault or on display, while its token representing ownership moves freely on-chain, with automatic royalty splits to the organizer, artist, venue, and platform on every trade.

## Features (MVP)

- Asset registration & minting with a unique Asset ID linked to a QR/NFC tag
- Custody Status tracker (displayed / vaulted / redeemable) synced on-chain
- USDC marketplace for buying/selling ownership tokens with an offer system
- Automatic royalty split to organizer/artist/venue/platform on each trade
- Physical redemption flow with token lock/burn mechanism

## Tech stack

Anchor, Solana Pay, USDC SPL, React, Next.js, NFC/QR scanning SDK, Metaplex

## How it works

```
[Physical Item] --QR/NFC tag-- [Asset ID / NFT on Solana]
       |                              |
  Custody Status                Ownership Token
 (displayed/vaulted/            (tradeable via
   redeemable)                   USDC marketplace)
       |                              |
       +---------- synced on-chain ---+
                     |
          Trade executes --> Royalty split
          (organizer/artist/venue/platform)
```

Users scan the QR/NFC tag to view an item's history, custody status, and current market offers. Venues mint the Asset ID via Metaplex, custody status syncs on-chain, and all trades settle instantly through a USDC marketplace built with Anchor and Solana Pay.

## Roadmap

- Partner with one venue/event for a live PoC with 3-5 iconic items
- Build legal framework for custody and ownership rights transfer
- Expand to multiple venues and launch a secondary marketplace with liquidity incentives

## Pitch

See our one-minute pitch deck at [docs/pitch.pdf](docs/pitch.pdf) and the spoken script at [docs/pitch-script.md](docs/pitch-script.md).

## Team

- Name / Role — [GitHub](#) / [Twitter](#)
- Name / Role — [GitHub](#) / [Twitter](#)
- Name / Role — [GitHub](#) / [Twitter](#)

---

🎬 Pitch video: [docs/pitch-video.mp4](docs/pitch-video.mp4)
