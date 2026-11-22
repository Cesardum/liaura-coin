# LiAura Coin (LIA) — Whitepaper Técnico (PT-BR)

## 1. Resumo
A LiAura Coin (LIA) é uma criptomoeda Layer-1 focada em privacidade, derivada da base CryptoNote/Monero (`v0.18.5.4`). Combina Proof of Work RandomX com RingCT, assinaturas CLSAG, Bulletproofs+ e View Tags, sob teto fixo de `5.000.000 LIA`, sem *tail emission* e sem pré-mineração no gênese.

## 2. Consenso e Privacidade
- **Algoritmo PoW:** RandomX (`DIFFICULTY_TARGET_V2 = 120s`, `DIFFICULTY_WINDOW = 720`, `DIFFICULTY_CUT = 60`).
- **Cronograma de Hardforks:** `v1..v16` unificado, garantindo *ring size* 16, CLSAG, Bulletproofs+ e View Tags.
- **Identidade Mainnet:** Prefixo `0x114`, P2P `19080`, RPC `19081`, `GENESIS_TX="013c01ff000000"`, `GENESIS_NONCE=10000`.

## 3. Política Monetária
- **Oferta Máxima:** `5.000.000 LIA` (12 casas decimais).
- **Reserva de Mineração (95%):** `4.750.000 LIA`.
- **Reserva dos Fundadores (5%):** `250.000 LIA`, liberados em 24 parcelas a cada `43.800` blocos (do bloco `43.800` ao `1.051.200`).
- **Emissão Residual:** Inexistente (*sem tail emission*).
