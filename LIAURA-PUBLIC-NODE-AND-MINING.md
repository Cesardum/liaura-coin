# Configuração de Nó Público (Nautilus) e Mineração Externa

**Nota:** Nenhuma alteração foi feita no Serviu Delivery, Nginx, PM2 ou firewall nesta etapa.

## 1. Nó Público Nautilus (`168.227.237.253`)

- **P2P Público:** porta `19080/tcp` aberta para peers externos.
- **RPC Público Restrito (para carteiras):** `--restricted-rpc --rpc-bind-ip 127.0.0.1 --rpc-bind-port 19089` atrás de proxy reverso TLS/HTTPS (ex.: `node.liaura.org` quando domínio for apontado), com *rate limiting*.
- **RPC Administrativo (`19081`):** manter estritamente em `127.0.0.1`, nunca expor à internet.

## 2. Mineração Externa (Mainnet)

```bash
./liaurad --add-priority-node 168.227.237.253:19080 --start-mining <SEU_ENDERECO_LIA> --mining-threads 4
```
- Consultar altura e dificuldade: `curl -s http://127.0.0.1:19081/json_rpc -d '{"jsonrpc":"2.0","id":"0","method":"get_info"}'`.
