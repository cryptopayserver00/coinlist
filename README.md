# CoinList

The collection of tokens for the mainnet and testnet supported by the service.

This package includes a JSON schema for token lists.

The JSON schema represents the technical specification for a token list which can be used in a dApp interface.

## What are token lists?

CryptoPayServer Token Lists is a specification for lists of token metadata (e.g. chain, address, decimals, ...) that can be used by any dApp interfaces that needs one or more lists of tokens.

Anyone can create and maintain a token list, as long as they follow the specification.

Specifically an instance of a token list is a [JSON](https://www.json.org/json-en.html) blob that contains a list of [ERC20](https://github.com/ethereum/eips/issues/20) token metadata for use in dApp user interfaces. Token list JSON must validate against the [JSON schema](https://json-schema.org/) in order to be used in the CryptoPayServer interface. Tokens on token lists, and token lists themselves, are tagged so that users can easily find tokens.

## Here

The networks currently supported by CoinList are:

- Bitcoin
- Ethereum
- Solana
- Binance Smart Chain
- Litecoin
- Ton
- Tron
- ......

You can directly see it [here](./CoinList.json).