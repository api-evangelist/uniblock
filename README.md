# Uniblock (uniblock)

Uniblock is a Web3 infrastructure platform that provides a standardized API aggregating data from hundreds of DEXs and cross-chain bridges, abstracting the complexity of multi-chain development into a single endpoint. The platform completed $5.2 million in financing with $7.5 million in total funding.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Blockchain
- Web3

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### Uniblock Unified API

The Uniblock Unified API provides a single standardized interface for interacting with multiple blockchain networks and data providers. It offers higher-level endpoints for common data needs including token metadata and balances, NFT collections and assets, transaction lookups, and market data for pricing and analytics.

- **Human URL:** [https://docs.uniblock.dev/docs/unified-api-overview](https://docs.uniblock.dev/docs/unified-api-overview)
- **Base URL:** `https://api.uniblock.dev`

#### Tags

- Blockchain
- Market Data
- NFTs
- Tokens
- Transactions
- Web3

#### Properties

- [Documentation](https://docs.uniblock.dev/docs/unified-api-overview)
- [OpenAPI](openapi/uniblock-unified-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uniblock-unified-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uniblock-unified-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/uniblock-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Uniblock Direct API

The Uniblock Direct API gives developers access to provider-specific endpoints exactly as offered by upstream blockchain data providers. This is intended for use cases where a specific method is not yet abstracted into the Unified API, allowing direct pass-through access to providers like Alchemy, SimpleHash, TonAPI, and others. Requests follow the pattern of specifying the provider and endpoint path, while still benefiting from Uniblock's routing, retry, and failover infrastructure.

- **Human URL:** [https://docs.uniblock.dev/docs/direct-api-overview](https://docs.uniblock.dev/docs/direct-api-overview)
- **Base URL:** `https://api.uniblock.dev/direct/v1`

#### Tags

- Blockchain
- Pass-Through
- Providers
- Web3

#### Properties

- [Documentation](https://docs.uniblock.dev/docs/direct-api-overview)
- [OpenAPI](openapi/uniblock-direct-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uniblock-direct-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uniblock-direct-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Uniblock JSON-RPC API

The Uniblock JSON-RPC API provides a single endpoint for standard JSON-RPC calls across hundreds of blockchain networks. Rather than managing individual node provider connections for each chain, developers can send JSON-RPC requests through Uniblock which automatically selects the best upstream node provider. This supports standard Ethereum and EVM-compatible JSON-RPC methods, as well as Solana and other chain-specific RPC interfaces, with built-in failover and automatic retries.

- **Human URL:** [https://docs.uniblock.dev/reference/unified-api-reference-overview](https://docs.uniblock.dev/reference/unified-api-reference-overview)
- **Base URL:** `https://api.uniblock.dev`

#### Tags

- Blockchain
- EVM
- JSON-RPC
- Nodes
- Web3

#### Properties

- [Documentation](https://docs.uniblock.dev/reference/unified-api-reference-overview)
- [OpenAPI](openapi/uniblock-json-rpc-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uniblock-json-rpc-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uniblock-json-rpc-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/uniblock-dapp)
- [JSON-LD](json-ld/uniblock-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/uniblock-token-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/uniblock-nft-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/uniblock-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/uniblock-webhook-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Website](https://uniblock.dev/)
- [Portal](https://docs.uniblock.dev/)
- [Documentation](https://docs.uniblock.dev/docs/welcome-to-uniblock)
- [Getting Started](https://docs.uniblock.dev/docs/uniblock-quickstart-guide)
- [Blog](https://www.uniblock.dev/blog)
- [Features](https://www.uniblock.dev/features)
- [Integrations](https://www.uniblock.dev/integrations)
- [Chains](https://www.uniblock.dev/chains)
- [Login](https://app.uniblock.dev/)
- [Spectral  Rules](rules/uniblock-rules.yml)
- [Vocabulary](vocabulary/uniblock-vocabulary.yml)
- [Capabilities](capabilities/blockchain-data.yaml)
- [L L Ms Txt](https://docs.uniblock.dev/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
