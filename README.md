# Uniblock

Uniblock is a Web3 infrastructure platform that provides a standardized API aggregating data from hundreds of DEXs and cross-chain bridges, abstracting the complexity of multi-chain development into a single endpoint. The platform automatically routes API calls to the best available data provider based on reliability, cost, and performance across 300+ blockchains and 55+ providers.

## APIs

### Uniblock Unified API

The Unified API provides higher-level endpoints for token metadata, NFT data, transactions, and market pricing across hundreds of blockchain networks.

- **Base URL:** https://api.uniblock.dev/uni/v1
- **Documentation:** https://docs.uniblock.dev/docs/unified-api-overview
- **OpenAPI:** [openapi/uniblock-unified-api-openapi.yml](openapi/uniblock-unified-api-openapi.yml)

### Uniblock Direct API

The Direct API provides pass-through access to provider-specific endpoints for use cases not yet covered by the Unified API.

- **Base URL:** https://api.uniblock.dev/direct/v1
- **Documentation:** https://docs.uniblock.dev/docs/direct-api-overview
- **OpenAPI:** [openapi/uniblock-direct-api-openapi.yml](openapi/uniblock-direct-api-openapi.yml)

### Uniblock JSON-RPC API

The JSON-RPC API provides a single endpoint for standard JSON-RPC calls across hundreds of blockchain networks with built-in failover.

- **Documentation:** https://docs.uniblock.dev/reference/unified-api-reference-overview
- **OpenAPI:** [openapi/uniblock-json-rpc-api-openapi.yml](openapi/uniblock-json-rpc-api-openapi.yml)

## Artifacts

### OpenAPI Specs

| File | Description |
|------|-------------|
| [openapi/uniblock-unified-api-openapi.yml](openapi/uniblock-unified-api-openapi.yml) | Unified API — tokens, NFTs, transactions, market data across 300+ chains |
| [openapi/uniblock-direct-api-openapi.yml](openapi/uniblock-direct-api-openapi.yml) | Direct API — pass-through to upstream providers |
| [openapi/uniblock-json-rpc-api-openapi.yml](openapi/uniblock-json-rpc-api-openapi.yml) | JSON-RPC API — unified node access |

### AsyncAPI

| File | Description |
|------|-------------|
| [asyncapi/uniblock-webhooks-asyncapi.yml](asyncapi/uniblock-webhooks-asyncapi.yml) | Webhook events for blockchain data notifications |

### Capabilities

| File | Description |
|------|-------------|
| [capabilities/blockchain-data.yaml](capabilities/blockchain-data.yaml) | Workflow capability for multi-chain blockchain data (REST + MCP) |
| [capabilities/shared/uniblock-unified-api.yaml](capabilities/shared/uniblock-unified-api.yaml) | Shared per-API definition for Unified API |

### JSON Schema

| File | Description |
|------|-------------|
| [json-schema/uniblock-token-schema.json](json-schema/uniblock-token-schema.json) | Token metadata and balance schema |
| [json-schema/uniblock-nft-schema.json](json-schema/uniblock-nft-schema.json) | NFT metadata and collection schema |
| [json-schema/uniblock-transaction-schema.json](json-schema/uniblock-transaction-schema.json) | Transaction data schema |
| [json-schema/uniblock-webhook-event-schema.json](json-schema/uniblock-webhook-event-schema.json) | Webhook event payload schema |

### JSON Structure

| File | Description |
|------|-------------|
| [json-structure/uniblock-token-structure.json](json-structure/uniblock-token-structure.json) | Field-level documentation for the Token entity |

### JSON-LD

| File | Description |
|------|-------------|
| [json-ld/uniblock-context.jsonld](json-ld/uniblock-context.jsonld) | JSON-LD context for blockchain data linked data semantics |

### Examples

| File | Description |
|------|-------------|
| [examples/uniblock-get-token-metadata-example.json](examples/uniblock-get-token-metadata-example.json) | Example GET token metadata request for USDC on Ethereum |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/uniblock-rules.yml](rules/uniblock-rules.yml) | Spectral ruleset for Uniblock API conventions |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/uniblock-vocabulary.yml](vocabulary/uniblock-vocabulary.yml) | Blockchain, Web3, DeFi, NFT, and Uniblock platform vocabulary |

## Properties

- [Website](https://uniblock.dev/)
- [Developer Portal](https://docs.uniblock.dev/)
- [Documentation](https://docs.uniblock.dev/docs/welcome-to-uniblock)
- [Getting Started](https://docs.uniblock.dev/docs/uniblock-quickstart-guide)
- [Blog](https://www.uniblock.dev/blog)
- [Features](https://www.uniblock.dev/features)
- [Integrations](https://www.uniblock.dev/integrations)
- [Chains](https://www.uniblock.dev/chains)
- [Login](https://app.uniblock.dev/)
