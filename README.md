# Uniblock (uniblock)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
