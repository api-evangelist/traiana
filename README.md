# Traiana (traiana)

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

Traiana, part of CME Group and now operating under OSTTRA, is a leading market infrastructure technology provider offering pre-trade risk monitoring and automated post-trade processing for listed and OTC trading. Its Harmony network connects over 1,000 firms via a cloud-based platform supporting 15,000 cross-asset trading relationships and handling $2 trillion in daily transaction volume across FX, equities, equity derivatives, and exchange-traded derivatives.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Fintech
- Foreign Exchange
- Post-Trade Processing
- Risk Management

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Traiana Harmony Trade Processing API

The Traiana Harmony Trade Processing API provides cross-asset post-trade processing capabilities through the Harmony network. It enables automated trade allocation, matching, confirmation, give-up messaging, and reporting across FX, equities, equity derivatives, and exchange-traded derivatives. Harmony connects over 1,000 firms and supports 15,000 cross-asset trading relationships, handling $2 trillion in daily transaction volume.

- **Human URL:** [https://www.cmegroup.com/services/traiana.html](https://www.cmegroup.com/services/traiana.html)

#### Tags

- Fintech
- Foreign Exchange
- Post-Trade Processing
- Trade Matching

#### Properties

- [Documentation](https://www.cmegroup.com/services/traiana.html)
- [OpenAPI](openapi/traiana-harmony-trade-processing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/traiana-harmony-trade-processing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/traiana-harmony-trade-processing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/trade.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/allocation.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/give-up.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/traiana-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Traiana Harmony CreditLink API

The Traiana Harmony CreditLink API provides real-time pre-trade and post-trade credit risk management across prime-brokered, cleared, and bilateral relationships. CreditLink is composed of the Designation Notice Manager (DNM), Tri-Party Limit Manager (TPL), and ECN Limit Manager (ELM), enabling limit monitoring, breach detection, credit line modification, and trading termination in real time through integration with exchange APIs.

- **Human URL:** [https://www.cmegroup.com/services/traiana.html](https://www.cmegroup.com/services/traiana.html)

#### Tags

- Credit Risk
- Fintech
- Foreign Exchange
- Risk Management

#### Properties

- [Documentation](https://www.cmegroup.com/services/traiana.html)
- [OpenAPI](openapi/traiana-harmony-creditlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/traiana-harmony-creditlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/traiana-harmony-creditlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/credit-limit.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/traiana-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Traiana Harmony NetLink API

The Traiana Harmony NetLink API provides netting, settlement orchestration, and trade compression services. NetLink enables counterparties to perform on-demand intraday netting of FX transactions, pre-settlement netting for equities, and trade compression between retail brokers and executing brokers. It reduces settlement risk and optimizes intraday liquidity through PvP settlement orchestration, including same-day settlement.

- **Human URL:** [https://www.cmegroup.com/services/traiana.html](https://www.cmegroup.com/services/traiana.html)

#### Tags

- Fintech
- Netting
- Settlement
- Trade Compression

#### Properties

- [Documentation](https://www.cmegroup.com/services/traiana.html)
- [OpenAPI](openapi/traiana-harmony-netlink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/traiana-harmony-netlink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/traiana-harmony-netlink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/netting-session.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/settlement.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/traiana-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [GitHub Organization](https://github.com/traiana)
- [LinkedIn](https://www.linkedin.com/company/traiana)
- [Documentation](https://www.cmegroup.com/services/traiana.html)
- [Documentation](https://osttra.com/services/post-trade-processing/trade-processing/)
- [Support](https://osttra.com/support/)
- [Spectral Rules](rules/traiana-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Vocabulary](vocabulary/traiana-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
