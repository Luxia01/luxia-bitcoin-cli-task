# luxia-bitcoin-cli-task
luxia-bitcoin-cli-task
# Bitcoin CLI Task

## Introduction
This task involves interacting with the Bitcoin network via CLI. We will use both a built-in Bitcoin node wallet and a separate Bitcoin wallet.

## Steps

### 1. Synchronize Bitcoin Node with Testnet

To start the Bitcoin node in testnet mode, execute the following command:
```bash
bitcoind -testnet -daemon
tail -f ~/.bitcoin/testnet3/debug.log
