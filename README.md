# Creem (creem)

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

Creem is a merchant-of-record payments platform built for SaaS and AI startups. Its REST API handles products, hosted checkouts, customers, subscriptions, transactions, discounts, and software license keys, while Creem acts as the merchant of record to manage global sales tax, VAT, fraud, and compliance on the seller's behalf.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/creem/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/creem/refs/heads/main/apis.yml)

## Tags

- Payments
- Merchant of Record
- Subscriptions
- SaaS
- Billing

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Creem Products API

Create, retrieve, and search products for one-time or recurring billing, including price, currency, billing type and period, tax mode, and license-key configuration.

- **Human URL:** [https://docs.creem.io/api-reference/endpoint/create-product](https://docs.creem.io/api-reference/endpoint/create-product)
- **Base URL:** `https://api.creem.io/v1`

#### Tags

- Products
- Catalog
- Billing

#### Properties

- [Documentation](https://docs.creem.io/api-reference/endpoint/create-product)
- [API Reference](https://docs.creem.io/api-reference/endpoint/search-products)
- [OpenAPI](openapi/creem-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creem.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creem.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creem Checkouts API

Create hosted checkout sessions that return a Creem-hosted checkout URL, attach products, discounts, customers, custom fields, and metadata, and retrieve a session's status and resulting order.

- **Human URL:** [https://docs.creem.io/api-reference/endpoint/create-checkout](https://docs.creem.io/api-reference/endpoint/create-checkout)
- **Base URL:** `https://api.creem.io/v1`

#### Tags

- Checkout
- Payments
- Hosted

#### Properties

- [Documentation](https://docs.creem.io/features/checkout/checkout-api)
- [API Reference](https://docs.creem.io/api-reference/endpoint/create-checkout)
- [OpenAPI](openapi/creem-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creem.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creem.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creem Customers API

Retrieve customers by id or email and generate self-service customer billing portal links so customers can manage their own subscriptions, invoices, and payment methods.

- **Human URL:** [https://docs.creem.io/api-reference/endpoint/get-customer](https://docs.creem.io/api-reference/endpoint/get-customer)
- **Base URL:** `https://api.creem.io/v1`

#### Tags

- Customers
- Billing Portal

#### Properties

- [Documentation](https://docs.creem.io/api-reference/endpoint/get-customer)
- [API Reference](https://docs.creem.io/api-reference/endpoint/get-billing-link)
- [OpenAPI](openapi/creem-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creem.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creem.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creem Subscriptions API

Retrieve and search subscriptions and manage their lifecycle - cancel, update, upgrade to a different product, pause, and resume - across active, trialing, paused, past_due, expired, and canceled states.

- **Human URL:** [https://docs.creem.io/api-reference/endpoint/get-subscription](https://docs.creem.io/api-reference/endpoint/get-subscription)
- **Base URL:** `https://api.creem.io/v1`

#### Tags

- Subscriptions
- Recurring
- Lifecycle

#### Properties

- [Documentation](https://docs.creem.io/api-reference/endpoint/get-subscription)
- [API Reference](https://docs.creem.io/api-reference/endpoint/upgrade-subscription)
- [OpenAPI](openapi/creem-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creem.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creem.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creem Transactions API

Retrieve a single transaction by id and search transactions filtered by customer, product, and date range for payment reconciliation and reporting.

- **Human URL:** [https://docs.creem.io/api-reference/endpoint/get-transaction](https://docs.creem.io/api-reference/endpoint/get-transaction)
- **Base URL:** `https://api.creem.io/v1`

#### Tags

- Transactions
- Payments
- Reporting

#### Properties

- [Documentation](https://docs.creem.io/api-reference/endpoint/get-transaction)
- [API Reference](https://docs.creem.io/api-reference/endpoint/search-transactions)
- [OpenAPI](openapi/creem-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creem.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creem.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creem Discounts API

Create, retrieve, search, and delete promotional discount codes (percentage or fixed amount) that can be applied to checkout sessions and subscriptions.

- **Human URL:** [https://docs.creem.io/api-reference/endpoint/create-discount](https://docs.creem.io/api-reference/endpoint/create-discount)
- **Base URL:** `https://api.creem.io/v1`

#### Tags

- Discounts
- Coupons
- Promotions

#### Properties

- [Documentation](https://docs.creem.io/api-reference/endpoint/create-discount)
- [API Reference](https://docs.creem.io/api-reference/endpoint/delete-discount)
- [OpenAPI](openapi/creem-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creem.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creem.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creem Licenses API

Validate, activate, and deactivate software license keys and their per-device instances, with activation limits and expiry, for distributing and enforcing licensed software.

- **Human URL:** [https://docs.creem.io/api-reference/endpoint/validate-license](https://docs.creem.io/api-reference/endpoint/validate-license)
- **Base URL:** `https://api.creem.io/v1`

#### Tags

- Licenses
- License Keys
- Activation

#### Properties

- [Documentation](https://docs.creem.io/features/license-keys)
- [API Reference](https://docs.creem.io/api-reference/endpoint/validate-license)
- [OpenAPI](openapi/creem-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creem.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creem.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Creem Webhooks API

HMAC-SHA256 signed event notifications for checkout, subscription, refund, and dispute events, delivered to seller-configured endpoints for keeping application state in sync with Creem.

- **Human URL:** [https://docs.creem.io/learn/webhooks/introduction](https://docs.creem.io/learn/webhooks/introduction)
- **Base URL:** `https://api.creem.io/v1`

#### Tags

- Webhooks
- Events
- HMAC

#### Properties

- [Documentation](https://docs.creem.io/learn/webhooks/introduction)
- [API Reference](https://docs.creem.io/learn/webhooks/event-types)
- [OpenAPI](openapi/creem-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/creem.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/creem.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/armitage-labs)
- [LinkedIn](https://www.linkedin.com/company/creem-io)
- [Website](https://www.creem.io/)
- [Documentation](https://docs.creem.io)
- [Plans](plans/creem-plans-pricing.yml)
- [Rate Limits](rate-limits/creem-rate-limits.yml)
- [Fin Ops](finops/creem-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
