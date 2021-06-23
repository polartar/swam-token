# SwapMatic Token SWAM

SwapMatic Token SWAM is a multi-chain asset that utilizes a cryptographically secure EVMBridge to maintain balances on Matic Network and Ethereum Mainnet. The supply of 100,000,000 tokens can reside on Matic Network or Ethereum. The starting point is 0 supply on Ethereum Mainnet and 100,000,000 tokens on Matic.

EMVBridge transactions are validated and secured by the contract owner's signature AND can be monitored with blockchain explorers.

Website: https://web.swapmatic.io

## Mainnet contracts
- Matic: TOKEN_CONTRACT= https://explorer-mainnet.maticvigil.com/address/0x820fe232433248732749C039EBcA0d43588Ad06d/read-contract
- Matic portal: FOREIGN_PORTAL_CONTRACT=https://explorer-mainnet.maticvigil.com/address/0xd1f9DED8849A87AE404fb9d885E7f6a81f07309c/read-contract
- Ethereum: HOME_BRIDGEABLE_CONTRACT=https://etherscan.io/address/0x368306eb52c8313fd398418c8220ddd560940e68#code

## Test contracts
- Mumbai: HOME_BRIDGEABLE_CONTRACT=https://explorer-mumbai.maticvigil.com/address/0x495029c478BC182555bBeBe48A614F39e572BA0D/read-contract
- Goerli: HOME_BRIDGEABLE_CONTRACT=https://goerli.etherscan.io/token/0xa396d78f1aedf43877f48a32cad7666315a67c4e

## BSC contracts
- Matic: HOME_BRIDGEABLE_CONTRACT=https://explorer-mainnet.maticvigil.com/address/0xd1f9DED8849A87AE404fb9d885E7f6a81f07309c/contracts
- BSC: HOME_BRIDGEABLE_CONTRACT=https://bscscan.com/address/0x1B3Ae9Af39607C44fd884F17E7FfA688BFF03581#readContract

## Matic-to-Mainnet .env

```
# Token Portal Properties
PORT=***

# Ethereum Properties
# Validator Private key
PRIVATE_KEY=***

# Bridgeable Token contract - Home is Ethereum Mainnet
HOME_ETHEREUM_PROVIDER_URL=https://mainnet.infura.io/v3/***
HOME_BRIDGEABLE_CONTRACT=0x368306eb52c8313fd398418c8220ddd560940e68

# ERC20 Portal contract - Foreign is Matic Network
FOREIGN_ETHEREUM_PROVIDER_URL=https://rpc-mainnet.maticvigil.com
FOREIGN_PORTAL_CONTRACT=0xd1f9DED8849A87AE404fb9d885E7f6a81f07309c

# ERC20 - Matic ERC20
TOKEN_CONTRACT=0x820fe232433248732749C039EBcA0d43588Ad06d
```

## Links
- EVMBridge: https://github.com/talentdev2020/swam-bridge
- App: https://swapmatic.io/swap
- Markets: https://blocktimeworld.com/swapmatic-markets/
- Mining: https://blocktimeworld.com/swam-liquidity-mining/
- Gitcoin: https://gitcoin.co/grants/1075/blocktime
