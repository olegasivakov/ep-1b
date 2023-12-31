# EP-1b: The mempool search JSON RPC call to BSC node

## Overview

### Usecases

### Context

### Technical analysis
Includes EP-0 bugfixes adopted for BSC node.

### How to test

### How to deploy

## Usage

### 1. Improve your node

Copy the next files to ethnode sourcecode and build ```geth``` as usual:
- ```./core/tx_list.go```
- ```./core/tx_pool.go```
- ```./eth/api_backend.go```
- ```./internal/ethapi/api.go```
- ```./internal/ethapi/backend.go```
- ```./internal/web3ext/web3ext.go```
- ```./les/api_backend.go```
- ```./light/txpool.go```

> [!IMPORTANT]
> Compare files! Only EP-1 and EP-0 rows are needed!

> [!NOTE]
> See ```// EP-0``` and ```// EP-1``` lines in the sourcecode.

### 2. RPC call

## Notes

> [!NOTE]
> Based on ethnode release v1.2.11 (https://github.com/bnb-chain/bsc/releases/tag/v1.2.11) commit 7a19cd2.

> [!NOTE]
> Main version EP-1 is available for Ethereum node: https://github.com/olegasivakov/ep-1

## License

[![GitHub license](https://img.shields.io/badge/license-MIT-lightgrey.svg?maxAge=2592000)](https://raw.githubusercontent.com/apollostack/apollo-ios/master/LICENSE)

MIT
