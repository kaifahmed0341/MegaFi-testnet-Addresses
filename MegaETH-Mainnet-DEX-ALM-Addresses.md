# megaETH Mainnet Deployment

**Network**: megaETH Mainnet  
**Chain ID**: 4326  
**Deployment Date**: December 22, 2025  
**Gas Price**: 2,000,000 wei (0.002 gwei)  
**Gas Limit**: 900,000,000

---

## Core Contracts

| Contract | Address | TX Hash | Block |
|----------|---------|---------|-------|
| CLTHelper | `0x80Dbfacfadb028d69E73168eA2b837A1Ee7788eD` | `0xb97a46955297cc48804e29ce86f4a2af8d98ced89da6fad72db7fad536c62ee4` | 3640054 |
| CLTModules | `0x82Ea0338cB0f35B3Fb77657b969576Ed08EFB58a` | `0xa4fcf1571f16b1a1d65101800003ae64d0b349af1074236a4bbfa56b1baf3798` | 3640058 |
| CLTTwapQuoter | `0x9fA7f39A0bFE0dD0C7F9863815A85d5190a59B30` | `0xc5d3386069ba9efe1929c147829b0fa47cec37a3e46c79e9bb86d212f9b3f0a6` | 3640063 |
| GovernanceFeeHandler | `0xbAcDDf64208a9e3177dE63E7da910b268b732B86` | `0x066d3db4bc80b891391c87b73bb5fb0a942b5af42f7d51448c5316e920191c67` | 3640066 |
| **CLTBase** | `0xeb3d3bCf5df5DF19689AfCCA4cD8Fdde7CE7aeF1` | `0xb715dfff3c03f6bb3dcf21bd35622254783d5dd83bc45a10820bd6ebf92eb75e` | 3640091 |

## Advanced Modules

| Contract | Address | TX Hash | Block |
|----------|---------|---------|-------|
| Modes | `0x9bF13D2feEe430e0D05482B09B8834f09a1e77BA` | `0x47d3991e936b987f9f562d3eba90b7beadb360916b128f8ff8e8480e9d85c7b6` | 3640095 |
| RebaseModule | `0x1f9bDe3F99d897BDF1b4BCFe52a1716aB030f894` | `0x733fe465522015a8449ad95995c7913890ff3e0e06c20a65d11aaa8a42864f3c` | 3640098 |

## Libraries

| Library | Address | TX Hash | Block |
|---------|---------|---------|-------|
| PoolActions | `0x93884a316eDf8b3bC8129B4C83fDbd69a71f60B9` | `0x849a43e3ac512c9453c6ef12b4af8dc9868f83cdf94ddc3678dd770905935aa3` | 3640070 |
| Position | `0x3C2b0DB9716d4E15797462F4231D25A5B1F32d43` | `0x3672003c6368109b7c13b862ec5eab3242d266f3e450af5cc8b9411aa605236d` | 3640073 |
| StrategyFeeShares | `0xcB86f9ffD88dDD1947b17AC8C6078A8646D10556` | `0xf495cb543c223f41db9d3a5d8a12a7cd478d32ebfea2b9a3469e1b8531ed4f71` | 3640076 |
| TransferHelper | `0x0a6315c290Dc5ee33714E77F1a6689d184C65C00` | `0x814abdb6b7077353526885f91d263a51a2b2d1ecca73a0f60db4edbe829a2d56` | 3640081 |
| UserPositions | `0x16463897f54B9E70c3b53379db373aC5587E730A` | `0x7b26fc7eda2a0b56a4f0cd54efd277172c04ca31b98c42f47c7547f02158cc47` | 3640084 |
| LiquidityShares | `0x819b6Cef85A0520897eFb6d8371c2DBD568203d9` | `0x62d75d451a228e9a9781b140d932fdee05bca1a711f846554a90b351f731df4d` | 3640087 |

---

## DEX Contracts

| Contract | Address |
|----------|---------|
| UniswapV3Factory | `0xbd4Ca451E3d28d053E7BE2738623Ed3d91709aa3` |
| PositionManager | `0xf2cA31CEfDD5B0814AB728A9C8358747dDd5da83` |
| PositionDescriptor | `0xc40a0aea1c3630C46DBBA0762F8A136E1742beB0` |
| NFTDescriptor Library | `0x3BA02Fb548AB983323A953Ba16Ba378A421c3258` |
| QuoterV2 | `0xe0253d48919521D1253587782B6fFF06bDE18D21` |

---

## Network Configuration

- **Owner**: `0x7eb4fa669716271f3b0e71a9d05ab3039af41e26`
- **WETH9**: `0x4200000000000000000000000000000000000006`
- **Factory**: `0xbd4Ca451E3d28d053E7BE2738623Ed3d91709aa3`

---

## Quick Reference

```
CLTHelper: 0x80Dbfacfadb028d69E73168eA2b837A1Ee7788eD
CLTModules: 0x82Ea0338cB0f35B3Fb77657b969576Ed08EFB58a
CLTTwapQuoter: 0x9fA7f39A0bFE0dD0C7F9863815A85d5190a59B30
GovernanceFeeHandler: 0xbAcDDf64208a9e3177dE63E7da910b268b732B86
CLTBase: 0xeb3d3bCf5df5DF19689AfCCA4cD8Fdde7CE7aeF1
Modes: 0x9bF13D2feEe430e0D05482B09B8834f09a1e77BA
RebaseModule: 0x1f9bDe3F99d897BDF1b4BCFe52a1716aB030f894
```

