# Rexswap




## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"` 


## Contributions

**Please open all pull requests against the `master` branch.** 
CI checks will run against all PRs.

## Accessing Rexswap V1

The Rexswap supports swapping against, and migrating or removing liquidity from Rexswap V1. However,
if you would like to use Rexswap V1, the Rexswap V1 interface for mainnet and testnets is accessible via IPFS gateways 
linked from the [v1.0.0 release]
