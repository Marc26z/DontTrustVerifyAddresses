# DontTrustVerifyAddresses

A single-file, offline Bitcoin address derivation tool.

`index.html` is the complete application: open it directly in a browser, or visit the GitHub Pages URL. There is no build step, no server, no dependencies, and no network traffic.

## Features

- Single-signature addresses: Legacy (P2PKH), Nested SegWit (P2SH-P2WPKH), Native SegWit (P2WPKH), and Taproot (P2TR)
- Multisig: 2–15 cosigner xpubs, legacy P2SH, nested P2SH-P2WSH, and native P2WSH, with optional BIP67 key sorting
- Account xpub or BIP39 recovery-phrase input (single-signature)
- Generate 1–10,000 addresses, preview, copy, print, or download as numbered text, plain addresses, or CSV
- Mainnet and testnet, configurable account/chain/start index and custom derivation path templates
- Local implementation of BIP32, BIP39, BIP44/49/84/86, BIP48, BIP67, Base58Check, Bech32, and Bech32m

## Privacy

Bitcoin addresses and extended public keys (xpubs) **cannot spend funds**, but they are sensitive: they reveal balances, transaction history, and wallet structure. Keep generated files private.

A BIP39 recovery phrase **is secret** and can spend funds. Only enter one on a trusted, offline machine. Nothing is stored or transmitted by this page.

## Verify before you trust

Compare the first generated address with your wallet's receive screen before printing a large batch.

## Source

The original single file is preserved as `DontTrustVerifyAddresses.html`; `index.html` is the identical copy served by GitHub Pages.
