# Nó Público e Mineração — LiAura Coin (LIA)

**Status da Rede:** A Mainnet LiAura Coin está em **validação controlada/interna** (ainda não liberada para utilização comercial ampla).

## 1. Usuários Finais (Consulta e Carteira)

- Utilize a **LiAura Wallet `v1.2.0-https`** conectada ao endpoint HTTPS público `https://node.serviupedidos.com.br`.
- O RPC administrativo (`19081`) permanece estritamente local nos servidores e nunca deve ser exposto à internet.

## 2. Mineração Experimental (CPU / RandomX)

Procedimento experimental para operadores técnicos com nó local sincronizado (`liaurad`):

```bash
./liaurad --add-priority-node 168.227.237.253:19080 --start-mining <SEU_ENDERECO_LIA> --mining-threads 4
```
- **Maturação:** recompensas de mineração exigem `60` blocos de maturação antes de ficarem disponíveis para envio.
