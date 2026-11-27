<p align="center">
  <img src="assets/liaura-coin-oficial.png" alt="LiAura Coin (LIA) Banner" width="100%">
</p>

# LiAura Coin (LIA)

**LiAura Coin (LIA)** is an independent Layer-1 privacy cryptocurrency based on CryptoNote / Monero (`v0.18.5.4`), using **Proof of Work (RandomX)**, **CLSAG**, **Bulletproofs+**, and **View Tags**, with a transparent fixed-cap monetary policy.

## Verified Network & Monetary Specifications

| Parameter | Value |
|---|---|
| **Name / Symbol** | LiAura Coin (`LIA`) |
| **Consensus** | Proof of Work — RandomX |
| **Maximum Supply** | `5,000,000 LIA` (12 decimal places) |
| **Mining Allocation (95%)** | `4,750,000 LIA` |
| **Founders Reserve (5%)** | `250,000 LIA` (24 tranches every `43,800` blocks) |
| **Tail Emission** | None (`0`) |
| **Genesis Premine** | None (`GENESIS_TX="013c01ff000000"`, `GENESIS_NONCE=10000`) |
| **Mainnet Ports** | P2P `19080` / RPC `19081` / Prefix `0x114` |
| **Public HTTPS Node** | `https://node.serviupedidos.com.br` |

## Public Infrastructure & Mining

- **Block Explorer:** [https://node.serviupedidos.com.br/explorer/](https://node.serviupedidos.com.br/explorer/)
- **Public Mining Pool:** [https://worcester-population-charged-sold.trycloudflare.com/pool/](https://worcester-population-charged-sold.trycloudflare.com/pool/)
- **Pool Stats API:** `https://worcester-population-charged-sold.trycloudflare.com/pool/api/stats`
- **Public Seed Node (P2P):** `node.serviupedidos.com.br:19080` (`168.227.237.253:19080`)
- **Stratum Mining Endpoint:** `bore.pub:43824` (`RandomX rx/0`, `1.0%` fee)

### Mine LIA with XMRig

```bash
xmrig -o bore.pub:43824 -u YOUR_LIA_WALLET_ADDRESS -p x -a rx/0
```

## Official Launch — Mainnet Live

**LiAura Coin (LIA) has officially launched.** Its independent Layer-1 mainnet is operational, with dedicated network infrastructure, wallet software, and confirmed on-chain transfers. LiAura is a live blockchain project, not a concept or an upcoming test network.

- **Mainnet:** Live, using RandomX Proof of Work and the published LiAura network parameters.
- **Implemented Technology:** Unified `v1..v16` hardfork schedule, deterministic A/B builds (`liaurad`, `liaura-wallet-cli`, `liaura-wallet-rpc`), and LiAura Wallet Desktop `v1.2.0-https` (`.deb`, SHA-256 `151a26a3b86e697818a698b07f4a1fa2ef94a183930aad74837aff1ed0314ff2`). Mainnet transfers have been verified.
- **Public Expansion:** Documentation and the HTTPS node endpoint are published. Wider distribution, exchange integrations, and ecosystem adoption are separate milestones; no exchange listing is claimed.
- **Security Transparency:** An independent external security/cryptographic audit has not yet been completed. Existing technical verifications are internal.
- **Ecosystem Roadmap:** **LiAura Motion**, **LiAura Convites**, and **MMORPG Elaris** (no launch dates promised).

## Documentation

- [WHITEPAPER.md](WHITEPAPER.md) / [WHITEPAPER-PTBR.md](WHITEPAPER-PTBR.md)
- [TOKENOMICS.md](TOKENOMICS.md)
- [TECHNICAL-OVERVIEW.md](TECHNICAL-OVERVIEW.md)
- [ROADMAP.md](ROADMAP.md)
- [SECURITY.md](SECURITY.md)
- [EXCHANGE-LISTING.md](EXCHANGE-LISTING.md)
- [SOURCE-PUBLICATION-PROPOSAL.md](SOURCE-PUBLICATION-PROPOSAL.md)
- [LICENSE](LICENSE) (BSD-3-Clause, preserving The Monero Project attribution)

## Official Mining Pool

- **Stratum Endpoint:** `bore.pub:43824`
- **Algorithm:** RandomX (`rx/0`)
- **Pool Fee:** `1%`
- **Minimum Payout:** `1 LIA` (automatic payouts)
- **Maturity Depth:** `60 blocks`

### Quick Start (`xmrig`)

```bash
xmrig -o bore.pub:43824 -u YOUR_LIAURA_WALLET -p worker1 -a rx/0 --donate-level=0
```
