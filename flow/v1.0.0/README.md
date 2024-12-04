# v1.0.0

## Contract Deployed

- SablierFlow
- FlowNFTDescriptor

## Sources

- Commit: [10b5bf3](https://github.com/sablier-labs/flow/commit/10b5bf315bd07a9926d18f89cc68698d8d87eea9)
- Package: [@sablier/flow@1.0.0](https://npmjs.com/package/@sablier/flow/v/1.0.0)

## Compiler Settings

| Setting        | Value    |
| :------------- | :------- |
| Version        | 0.8.26   |
| EVM            | Shanghai |
| Optimizer      | Yes      |
| Optimizer Runs | 10,000   |
| Via IR         | true     |

### Linea Compiler Settings

Due to the lack of [EIP-3855](https://eips.ethereum.org/EIPS/eip-3855) support, we had to use the following settings for
Linea:

| Setting        | Value  |
| :------------- | :----- |
| Version        | 0.8.26 |
| EVM            | Paris  |
| Optimizer      | Yes    |
| Optimizer Runs | 10,000 |
| Via IR         | true   |

### IoTex and Tangle

Due to the lack of Foundry support and for newer Solidity versions, we had to use the following settings for IoTex and
Tangle:

| Setting        | Value  |
| :------------- | :----- |
| Version        | 0.8.20 |
| EVM            | Paris  |
| Optimizer      | Yes    |
| Optimizer Runs | 10,000 |
| Via IR         | true   |

## Salts

The CREATE2 salts used during deployment:

### Mainnets

| Chain           | Salt                          |
| :-------------- | :---------------------------- |
| Arbitrum One    | ChainID 42161, Version 1.0.0  |
| Avalanche       | ChainID 43114, Version 1.0.0  |
| Base            | ChainID 8453, Version 1.0.0   |
| Blast           | ChainID 81457, Version 1.0.0  |
| BNB Smart Chain | ChainID 56, Version 1.0.0     |
| Core Dao        | ChainID 1116, Version 1.0.0   |
| Gnosis          | ChainID 100, Version 1.0.0    |
| IoTex           | No Salt                       |
| Lightlink       | No Salt                       |
| Linea           | ChainID 59144, Version 1.0.0  |
| Mainnet         | ChainID 1, Version 1.0.0      |
| Meld            | No Salt                       |
| Mode            | No Salt                       |
| Morph           | No Salt                       |
| Optimism        | ChainID 10, Version 1.0.0     |
| Polygon         | ChainID 137, Version 1.0.0    |
| Scroll          | ChainID 534352, Version 1.0.0 |
| Superseed       | ChainID 5330, Version 1.0.0   |
| Taiko Mainnet   | ChainID 167000, Version 1.0.0 |
| Tangle          | No Salt                       |
| zkSync Era      | No Salt                       |

### Testnets

| Chain             | Salt                             |
| :---------------- | :------------------------------- |
| Arbitrum Sepolia  | ChainID 421614, Version 1.0.0    |
| Base Sepolia      | ChainID 84532, Version 1.0.0     |
| Berachain Bartio  | ChainID 80084, Version 1.0.0     |
| Blast Sepolia     | ChainID 168587773, Version 1.0.0 |
| Linea Sepolia     | No Salt                          |
| Mode Sepolia      | No Salt                          |
| Morph Holesky     | No Salt                          |
| Optimism Sepolia  | ChainID 11155420, Version 1.0.0  |
| Sepolia           | ChainID 11155111, Version 1.0.0  |
| Superseed Sepolia | ChainID 53302, Version 1.0.0     |
| Taiko Hekla       | ChainID 167009, Version 1.0.0    |
| zkSync Sepolia    | No Salt                          |
