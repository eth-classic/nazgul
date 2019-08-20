# Nazgul testnet

[![Join the chat at https://gitter.im/eth-classic/nazgul](https://badges.gitter.im/eth-classic/nazgul.svg)](https://gitter.im/eth-classic/nazgul?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A temporary Atlantis-enabled, fucking proof-of-work testnet for Ethereum Classic used by Whiteblock.

Atlantis Hardfork: `0`

### Parity Ethereum

Required version: 2.5.6+

```bash
parity --chain ./parity.json
```

### Geth Classic

Required version: 6.0.8+

```bash
geth --chain ./gethc.json
```

### Multi Geth

Required version: 1.9.2+

##### Genesis file (legacy)

```bash
geth init --datadir ~/.ethereum/nazgul ./mgeth.json
geth --datadir ~/.ethereum/nazgul --networkid 88

```

##### Parity chain spec (experimental)

```bash
geth --chainspec.parity ./parity.json
```
