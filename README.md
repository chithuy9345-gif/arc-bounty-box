# arc-bounty-box

USDC bounty board on Arc testnet.

- Chain ID: `5042002`
- RPC: `https://rpc.testnet.arc.network`
- USDC: `0x3600000000000000000000000000000000000000`
- Explorer: https://testnet.arcscan.app

## Contract

`src/BountyBox.sol` records USDC payments and emits accounting events.

## Build

```bash
forge build
```

## Deployment

- Contract: `0x6f45e06aFCb7903022C98Ab36971D7eD069BD874`
- Tx: `inferred-from-nonce`
- Explorer: https://testnet.arcscan.app/address/0x6f45e06aFCb7903022C98Ab36971D7eD069BD874
