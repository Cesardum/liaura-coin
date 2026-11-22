# Exchange & Listing Technical Information — LiAura Coin (LIA)

**Disclaimer:** No exchange (including Bitget, FreiExchange) or data aggregator (including CoinGecko) has reviewed, confirmed, or approved LiAura Coin (LIA). No listing application has been submitted.

## 1. Internal Technical Interface (CryptoNote / Monero-Derived)
- **Daemon:** `liaurad` (P2P `19080`, Admin RPC `19081` local-only).
- **Wallet Backend:** `liaura-wallet-rpc` (JSON-RPC methods: `get_address`, `create_address`, `get_balance`, `get_transfers`, `transfer`, `get_transfer_by_txid`).
- **Address Prefix:** `0x114` (Mainnet addresses start with `Rk...`).
- **Coinbase Maturity:** `60` blocks.

## 2. General Readiness & Pending Items (Budget: R$ 0)
- **Internally Verified:** Technical whitepaper, tokenomics, controlled Mainnet transfer test, deterministic A/B release builds.
- **Not Yet Available / Unverified:** Public C++ source-code repository, public block explorer, independent external security audit, and exchange-specific commercial/technical requirements (which must be verified directly with each platform's official documentation).
