# Creem (creem)

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
