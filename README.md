# Traiana (traiana)
Traiana, part of CME Group and now operating under OSTTRA, is a leading market infrastructure technology provider offering pre-trade risk monitoring and automated post-trade processing for listed and OTC trading. Its Harmony network connects over 1,000 firms via a cloud-based platform supporting 15,000 cross-asset trading relationships and handling $2 trillion in daily transaction volume across FX, equities, equity derivatives, and exchange-traded derivatives. Key services include trade matching and confirmation, give-up messaging, credit risk management through CreditLink, and netting and settlement orchestration through NetLink.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Fintech, Foreign Exchange, Risk Management, Post-Trade Processing

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-16 

## APIs

### Traiana Harmony Trade Processing API
The Traiana Harmony Trade Processing API provides cross-asset post-trade processing capabilities through the Harmony network. It enables automated trade allocation, matching, confirmation, give-up messaging, and reporting across FX, equities, equity derivatives, and exchange-traded derivatives. Harmony connects over 1,000 firms and supports 15,000 cross-asset trading relationships, handling $2 trillion in daily transaction volume.

**Human URL:** [https://www.cmegroup.com/services/traiana.html](https://www.cmegroup.com/services/traiana.html)


#### Tags:

 - Fintech, Post-Trade Processing, Trade Matching, Foreign Exchange

#### Properties

- [Documentation](https://www.cmegroup.com/services/traiana.html)
- [OpenAPI](openapi/traiana-harmony-trade-processing-openapi.yml)
- [JSONSchema](json-schema/trade.json)
- [JSONSchema](json-schema/allocation.json)
- [JSONSchema](json-schema/give-up.json)
- [JSONLD](json-ld/traiana-context.jsonld)

### Traiana Harmony CreditLink API
The Traiana Harmony CreditLink API provides real-time pre-trade and post-trade credit risk management across prime-brokered, cleared, and bilateral relationships. CreditLink is composed of the Designation Notice Manager (DNM), Tri-Party Limit Manager (TPL), and ECN Limit Manager (ELM), enabling limit monitoring, breach detection, credit line modification, and trading termination in real time through integration with exchange APIs.

**Human URL:** [https://www.cmegroup.com/services/traiana.html](https://www.cmegroup.com/services/traiana.html)


#### Tags:

 - Fintech, Risk Management, Credit Risk, Foreign Exchange

#### Properties

- [Documentation](https://www.cmegroup.com/services/traiana.html)
- [OpenAPI](openapi/traiana-harmony-creditlink-openapi.yml)
- [JSONSchema](json-schema/credit-limit.json)
- [JSONLD](json-ld/traiana-context.jsonld)

### Traiana Harmony NetLink API
The Traiana Harmony NetLink API provides netting, settlement orchestration, and trade compression services. NetLink enables counterparties to perform on-demand intraday netting of FX transactions, pre-settlement netting for equities, and trade compression between retail brokers and executing brokers. It reduces settlement risk and optimizes intraday liquidity through PvP settlement orchestration, including same-day settlement.

**Human URL:** [https://www.cmegroup.com/services/traiana.html](https://www.cmegroup.com/services/traiana.html)


#### Tags:

 - Fintech, Netting, Settlement, Trade Compression

#### Properties

- [Documentation](https://www.cmegroup.com/services/traiana.html)
- [OpenAPI](openapi/traiana-harmony-netlink-openapi.yml)
- [JSONSchema](json-schema/netting-session.json)
- [JSONSchema](json-schema/settlement.json)
- [JSONLD](json-ld/traiana-context.jsonld)

## Common Properties

- [Documentation](https://www.cmegroup.com/services/traiana.html)
- [Documentation](https://osttra.com/services/post-trade-processing/trade-processing/)
- [Support](https://osttra.com/support/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
