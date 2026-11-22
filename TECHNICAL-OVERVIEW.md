# LiAura Coin (LIA) — Technical Overview

## 1. Architecture & Binaries
- **`liaurad`:** Full node daemon (P2P `19080`, Admin RPC `19081`, Restricted Public RPC `19089` behind HTTPS).
- **`liaura-wallet-cli`:** Command-line wallet (`LiAura 'Genesis'`).
- **`liaura-wallet-rpc`:** JSON-RPC wallet backend used by exchanges and **LiAura Wallet Desktop (`v1.2.0-https`)**.

## 2. Security & Wallet Architecture
- Local `liaura-wallet-rpc` binds strictly to `127.0.0.1` with per-session HTTP Digest Auth (`0600` config file).
- Remote HTTPS connections use an ephemeral `127.0.0.1` proxy with strict TLS verification (`rejectUnauthorized: true`), DNS-rebinding IP pinning, and path allowlisting.
- Private keys and 25-word mnemonic seeds never leave the user's device.
