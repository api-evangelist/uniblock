# Uniblock (uniblock)
Uniblock is a Web3 infrastructure platform that aggregates data from hundreds of decentralized exchanges and cross-chain bridges into a single standardized API endpoint. Their developer platform abstracts the complexity of multi-chain blockchain development, with auto-routing that directs API calls to the best available data provider based on reliability, cost, and performance across 300+ blockchains and 55+ providers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Web3, Blockchain, APIs

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-03-24

## APIs

### Uniblock Unified API
The Uniblock Unified API provides a single standardized interface for interacting with multiple blockchain networks and data providers. It offers higher-level endpoints for common data needs including token metadata and balances, NFT collections and assets, transaction lookups, and market data for pricing and analytics. The API abstracts away the differences between upstream providers like Alchemy, Moralis, and Covalent, automatically routing requests to the best provider based on reliability, cost, and performance.

**Human URL:** [https://docs.uniblock.dev/docs/unified-api-overview](https://docs.uniblock.dev/docs/unified-api-overview)


#### Tags:

 - Web3, Blockchain, Tokens, NFTs, Transactions, Market Data

#### Properties

- [Documentation](https://docs.uniblock.dev/docs/unified-api-overview)
- [OpenAPI](openapi/uniblock-unified-api-openapi.yml)
- [AsyncAPI](asyncapi/uniblock-webhooks-asyncapi.yml)

### Uniblock Direct API
The Uniblock Direct API gives developers access to provider-specific endpoints exactly as offered by upstream blockchain data providers. This is intended for use cases where a specific method is not yet abstracted into the Unified API, allowing direct pass-through access to providers like Alchemy, SimpleHash, TonAPI, and others. Requests follow the pattern of specifying the provider and endpoint path, while still benefiting from Uniblock's routing, retry, and failover infrastructure.

**Human URL:** [https://docs.uniblock.dev/docs/direct-api-overview](https://docs.uniblock.dev/docs/direct-api-overview)


#### Tags:

 - Web3, Blockchain, Providers, Pass-Through

#### Properties

- [Documentation](https://docs.uniblock.dev/docs/direct-api-overview)
- [OpenAPI](openapi/uniblock-direct-api-openapi.yml)

### Uniblock JSON-RPC API
The Uniblock JSON-RPC API provides a single endpoint for standard JSON-RPC calls across hundreds of blockchain networks. Rather than managing individual node provider connections for each chain, developers can send JSON-RPC requests through Uniblock which automatically selects the best upstream node provider. This supports standard Ethereum and EVM-compatible JSON-RPC methods, as well as Solana and other chain-specific RPC interfaces, with built-in failover and automatic retries.

**Human URL:** [https://docs.uniblock.dev/reference/unified-api-reference-overview](https://docs.uniblock.dev/reference/unified-api-reference-overview)


#### Tags:

 - Web3, Blockchain, JSON-RPC, Nodes, EVM

#### Properties

- [Documentation](https://docs.uniblock.dev/reference/unified-api-reference-overview)
- [OpenAPI](openapi/uniblock-json-rpc-api-openapi.yml)

## Common Properties

- [Website](https://uniblock.dev/)
- [Portal](https://docs.uniblock.dev/)
- [Documentation](https://docs.uniblock.dev/docs/welcome-to-uniblock)
- [Getting Started](https://docs.uniblock.dev/docs/uniblock-quickstart-guide)
- [Blog](https://www.uniblock.dev/blog)
- [Features](https://www.uniblock.dev/features)
- [Integrations](https://www.uniblock.dev/integrations)
- [Chains](https://www.uniblock.dev/chains)
- [Login](https://app.uniblock.dev/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
