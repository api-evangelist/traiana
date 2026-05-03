# Traiana

Traiana, part of CME Group and now operating under OSTTRA, is a leading market infrastructure technology provider offering pre-trade risk monitoring and automated post-trade processing for listed and OTC trading. Its Harmony network connects over 1,000 firms via a cloud-based platform supporting 15,000 cross-asset trading relationships and handling $2 trillion in daily transaction volume across FX, equities, equity derivatives, and exchange-traded derivatives.

**Website:** https://osttra.com/  
**Documentation:** https://www.cmegroup.com/services/traiana.html

## APIs

### Traiana Harmony Trade Processing API

Cross-asset post-trade processing for trade allocation, matching, confirmation, give-up messaging, and reporting.

- **OpenAPI:** [openapi/traiana-harmony-trade-processing-openapi.yml](openapi/traiana-harmony-trade-processing-openapi.yml)

### Traiana Harmony CreditLink API

Real-time pre-trade and post-trade credit risk management with limit monitoring, breach detection, and designation notices.

- **OpenAPI:** [openapi/traiana-harmony-creditlink-openapi.yml](openapi/traiana-harmony-creditlink-openapi.yml)

### Traiana Harmony NetLink API

Netting, settlement orchestration, and trade compression for FX and equities.

- **OpenAPI:** [openapi/traiana-harmony-netlink-openapi.yml](openapi/traiana-harmony-netlink-openapi.yml)

## Artifacts

### OpenAPI Specs

| Spec | Description |
|------|-------------|
| [traiana-harmony-trade-processing-openapi.yml](openapi/traiana-harmony-trade-processing-openapi.yml) | Trade allocation, matching, and confirmation |
| [traiana-harmony-creditlink-openapi.yml](openapi/traiana-harmony-creditlink-openapi.yml) | Credit limit management and breach monitoring |
| [traiana-harmony-netlink-openapi.yml](openapi/traiana-harmony-netlink-openapi.yml) | Netting sessions, settlement, and compression |

### Spectral Rules

| File | Description |
|------|-------------|
| [traiana-rules.yml](rules/traiana-rules.yml) | Spectral ruleset enforcing Traiana API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | Description |
|------|-------------|
| [shared/harmony-trade-processing.yaml](capabilities/shared/harmony-trade-processing.yaml) | Per-API consumed definition for Trade Processing |
| [shared/harmony-creditlink.yaml](capabilities/shared/harmony-creditlink.yaml) | Per-API consumed definition for CreditLink |
| [shared/harmony-netlink.yaml](capabilities/shared/harmony-netlink.yaml) | Per-API consumed definition for NetLink |

#### Workflow Capabilities

| File | Description |
|------|-------------|
| [post-trade-processing.yaml](capabilities/post-trade-processing.yaml) | Unified post-trade workflow — trades, credit, netting, settlement (14 tools) |

### JSON Schemas

| File | Description |
|------|-------------|
| [trade.json](json-schema/trade.json) | Trade entity schema |
| [allocation.json](json-schema/allocation.json) | Trade allocation schema |
| [give-up.json](json-schema/give-up.json) | Give-up message schema |
| [netting-session.json](json-schema/netting-session.json) | Netting session schema |
| [settlement.json](json-schema/settlement.json) | Settlement instruction schema |
| [credit-limit.json](json-schema/credit-limit.json) | Credit limit schema |

### JSON Structure

| File | Description |
|------|-------------|
| [traiana-trade-structure.json](json-structure/traiana-trade-structure.json) | Structure documentation for trade objects |

### JSON-LD

| File | Description |
|------|-------------|
| [traiana-context.jsonld](json-ld/traiana-context.jsonld) | JSON-LD context for Traiana linked data semantics |

### Examples

| File | Description |
|------|-------------|
| [traiana-list-trades-example.json](examples/traiana-list-trades-example.json) | Example response for GET /trades |
| [traiana-get-credit-utilization-example.json](examples/traiana-get-credit-utilization-example.json) | Example response for GET /utilization |

### Vocabulary

| File | Description |
|------|-------------|
| [traiana-vocabulary.yml](vocabulary/traiana-vocabulary.yml) | Domain vocabulary for post-trade processing concepts |

## Maintainers

- **Kin Lane** (kin@apievangelist.com)
