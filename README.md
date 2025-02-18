# Relend Testnet Documentation
Documentation for Relend deployments across various L2 testnets. Each L2 has its own token and bridge implementation.

## Network Deployments

| L2 Network | Base Network | Base USDC | rUSDC Token | Bridge |
|------------|--------------|-----------|--------------|--------|
| Starknet | Sepolia | [View Contract](https://sepolia.etherscan.io/address/0x02eA187D39f8F612c7A16Ba5D05B21bbEA28eF82) | [View on Starkscan](https://sepolia.starkscan.co/token/0x01c5814d7b2e7e38f10d38128c8e5e219fe610fc7a36ad86b78afb325dd2d9bd) | [StarkGate Bridge](https://starkgate.starknet.io/bridge/deposit) |
| Hemi | Sepolia | [View Contract](https://sepolia.etherscan.io/address/0x02eA187D39f8F612c7A16Ba5D05B21bbEA28eF82) | [View Contract](https://sepolia.etherscan.io/address/0x48589961e8474B47baB878E4844BAB827Ea73A1e) | [Hemi Bridge](https://app.hemi.xyz/en/tunnel/) |
| Morph | Holesky | [View Contract](https://holesky.etherscan.io/address/0xe88a217b3C00eFf21e02B83991e0a1BAFeA084Ca) | [View Contract](https://holesky.etherscan.io/address/0x1593EC75d7Fd91F0bB921825453BfA6032915115) | [Morph Bridge](https://bridge.morphl2.io/) |
| Taiko | Holesky | [View Contract](https://holesky.etherscan.io/address/0xe88a217b3C00eFf21e02B83991e0a1BAFeA084Ca) | [View Contract](https://holesky.etherscan.io/address/0x3531756639083431DBE8E959f62bD93b5E4155b7) | [Taiko Bridge](https://bridge.taiko.xyz/) |
| Bitlayer | Holesky | [View Contract](https://holesky.etherscan.io/address/0xe88a217b3C00eFf21e02B83991e0a1BAFeA084Ca) | [View Contract](https://holesky.etherscan.io/address/0x61F3e9C2B078f6245513a40035B5Ff0592896e41) | [Bitlayer Bridge](https://www.bitlayer.org/bridge) |

### Quick Copy Addresses

#### Sepolia Base USDC

```solidity
0x02eA187D39f8F612c7A16Ba5D05B21bbEA28eF82
```

#### Holesky Base USDC

```solidity
0xe88a217b3C00eFf21e02B83991e0a1BAFeA084Ca
```

#### L2 Token Addresses

```solidity
// Starknet rUSDC
0x01c5814d7b2e7e38f10d38128c8e5e219fe610fc7a36ad86b78afb325dd2d9bd
// Hemi rUSDC
0x48589961e8474B47baB878E4844BAB827Ea73A1e
// Morph rUSDC
0x1593EC75d7Fd91F0bB921825453BfA6032915115
// Taiko rUSDC
0x3531756639083431DBE8E959f62bD93b5E4155b7
// Bitlayer rUSDC
0x61F3e9C2B078f6245513a40035B5Ff0592896e41
```
