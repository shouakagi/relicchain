# Relicchain

_History stays, ownership moves: tokenize real-world memorabilia without moving it_

## Summary

A platform that lets venues and teams mint RWA tokens for physical memorabilia kept on display, while ownership trades on Solana via USDC. QR/NFC codes link each item to its on-chain twin, showing provenance, custody status, and enabling instant purchase or offers.

## Target users

Venues, sports teams, artists, and global collector fans

## Problem

Historical and cultural memorabilia sits idle in storage or display cases, generating no ongoing economic value for owners or venues.

## Solution

Separate physical custody from economic ownership: the item stays in a vault/venue while its token representing ownership moves freely on-chain with automatic royalty splits.

## MVP features

- Asset registration & minting with unique Asset ID linked to QR/NFC tag
- Custody Status tracker (displayed/vaulted/redeemable) synced on-chain
- USDC marketplace for buying/selling ownership tokens with offer system
- Automatic royalty split to organizer/artist/venue/platform on each trade
- Physical redemption flow with token lock/burn mechanism

## Chains

Solana

## Tech

Anchor, Solana Pay, USDC SPL, React, Next.js, NFC/QR scanning SDK, Metaplex

## Category

Infrastructure

## Why now

RWA tokenization is gaining regulatory clarity and USDC rails on Solana make instant global settlement for collectibles feasible for the first time.

## Roadmap

- Partner with one venue/event for a live PoC with 3-5 iconic items
- Build legal framework for custody and ownership rights transfer
- Expand to multiple venues and launch secondary marketplace with liquidity incentives
