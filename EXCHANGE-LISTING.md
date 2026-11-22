# Exchange & Listing Technical Guide — LiAura Coin (LIA)

## 1. Native Blockchain Integration (CryptoNote / Monero-Derived)
- **Daemon:** `liaurad` (P2P `19080`, Admin RPC `19081` local-only).
- **Wallet Backend:** `liaura-wallet-rpc` (standard Monero JSON-RPC: `get_address`, `create_address`, `get_balance`, `get_transfers`, `transfer`, `get_transfer_by_txid`).
- **Address Prefix:** `0x114` (Mainnet addresses start with `Rk...`, subaddresses supported).
- **Recommended Deposit Confirmations:** `10`–`20` blocks (`60` blocks for coinbase/mining maturity).

## 2. Platform Requirements Checklist (Budget: R$ 0)

### Bitget
- **Confirmed:** Public whitepaper, tokenomics, GitHub repo, active Mainnet node.
- **Unverified / Pending:** Public source code repository, block explorer URL, independent security audit, commercial/liquidity review.

### FreiExchange
- **Confirmed:** Native CryptoNote/Monero daemon + `liaura-wallet-rpc` compatibility, zero-premine specs.
- **Unverified / Pending:** Public source code URL, block explorer URL, formal listing application (not submitted).

### CoinGecko Preview
- **Confirmed:** Tokenomics, project overview, public GitHub & release assets.
- **Unverified / Pending:** Active exchange/market data (volume/price), block explorer URL, public source code.
