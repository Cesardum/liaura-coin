# LiAura Coin (LIA) — Technical Whitepaper

## 1. Abstract
LiAura Coin (LIA) is a privacy-preserving Layer-1 cryptocurrency derived from the CryptoNote/Monero (`v0.18.5.4`) protocol. It combines RandomX CPU-oriented Proof of Work with RingCT, CLSAG signatures, Bulletproofs+, and View Tags, under a fixed 5,000,000 LIA supply cap with zero tail emission and zero genesis premine.

## 2. Consensus & Privacy
- **PoW Algorithm:** RandomX (`DIFFICULTY_TARGET_V2 = 120s`, `DIFFICULTY_WINDOW = 720`, `DIFFICULTY_CUT = 60`).
- **Hardfork Schedule:** Unified `v1..v16` active from initial blocks, enforcing modern ring size (16), CLSAG, Bulletproofs+, and View Tags.
- **Network Isolation:** Mainnet prefix `0x114`, P2P `19080`, RPC `19081`, `GENESIS_TX="013c01ff000000"`, `GENESIS_NONCE=10000`.

## 3. Monetary Policy
- **Maximum Supply:** `5,000,000 LIA` (`5,000,000 * 10^12` atomic units).
- **Mining Budget (95%):** `4,750,000 LIA`.
- **Founders Reserve (5%):** `250,000 LIA`, vested in 24 tranches every `43,800` blocks (blocks `43,800` to `1,051,200`).
- **Tail Emission:** None.
