# Source Code Publication Proposal (Pending Owner Authorization)

**Note:** Full C++ source code has **not** been pushed automatically. This proposal documents what is required before publishing.

## 1. Inventory & Submodules
- **Source tree:** `<local-liaura-src>` (branch `liaura-identity-rebrand`, commit `a81e122`, based on `liaura-unified-hf-132`).
- **Submodules:** `external/randomx`, `external/rapidjson`, `external/supercop`, `external/trezor-common`.
- **License:** `BSD-3-Clause` (`LICENSE` preserving The Monero Project copyright).

## 2. Reproducible Build & Tests
- Build with `SOURCE_DATE_EPOCH`, `-ffile-prefix-map`, `-DLIAURA_RELEASE_BUILD=ON`.
- Automated tests: `preflight_readonly_117.py --run-tests`, `test_hardfork_124.py`, `test_private_testnet_131.py`, and Wallet `npm test` + `test-https-proxy.js`.

## 3. Pre-Publication Secret Review
- Confirm zero private keys, seeds, passwords, or internal SSH/VPS credentials exist in tracked files before pushing.
