# magento (magento)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Overview of the Adobe Commerce and Magento Open Source REST API documentation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Magento REST API

The Adobe Commerce (Magento) REST API provides a comprehensive set of endpoints for interacting with all major aspects of an e-commerce store, including catalog management, orders, customers, inventory, shipping, and payments. It supports three authentication mechanisms: OAuth 1.0a for third-party integrations, token-based authentication for mobile apps and administrators, and guest access for select public endpoints.

- **Human URL:** [https://developer.adobe.com/commerce/webapi/rest/](https://developer.adobe.com/commerce/webapi/rest/)
- **Base URL:** `https://your-store.example.com/rest`

#### Tags

- Catalog
- Customers
- E-Commerce
- Orders
- Products
- REST

#### Properties

- [Documentation](https://developer.adobe.com/commerce/webapi/rest/)
- [Documentation](https://developer.adobe.com/commerce/webapi/rest/reference/)
- [OpenAPI](openapi/magento-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/magento-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magento-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Magento GraphQL API

The Adobe Commerce GraphQL API offers a flexible, query-driven interface designed primarily for building headless storefronts and progressive web applications. It exposes a single endpoint and allows clients to request exactly the data they need through queries and mutations covering catalog browsing, product search, cart management, checkout, customer accounts, and order history.

- **Human URL:** [https://developer.adobe.com/commerce/webapi/graphql/](https://developer.adobe.com/commerce/webapi/graphql/)
- **Base URL:** `https://your-store.example.com/graphql`

#### Tags

- Cart
- Catalog
- E-Commerce
- GraphQL
- Headless Commerce
- Storefront

#### Properties

- [Documentation](https://developer.adobe.com/commerce/webapi/graphql/)
- [Documentation](https://developer.adobe.com/commerce/webapi/graphql/reference/)
- [Postman Collection](collections/magento-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magento-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Magento SOAP API

The Adobe Commerce SOAP API exposes the same service contracts as the REST API through a WSDL 1.2 interface compliant with WS-I 2.0 Basic Profile. It allows enterprise systems and legacy integrations to interact with Adobe Commerce store data using standard SOAP tooling. Developers can retrieve the WSDL for any service or combination of services by appending query parameters to the SOAP endpoint URL.

- **Human URL:** [https://developer.adobe.com/commerce/webapi/get-started/soap-web-api-calls/](https://developer.adobe.com/commerce/webapi/get-started/soap-web-api-calls/)
- **Base URL:** `https://your-store.example.com/soap`

#### Tags

- E-Commerce
- Integration
- SOAP
- Web Services

#### Properties

- [Documentation](https://developer.adobe.com/commerce/webapi/get-started/soap-web-api-calls/)
- [W S D L](wsdl/magento-soap.wsdl)
- [Postman Collection](collections/magento-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magento-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Commerce Webhooks

Adobe Commerce Webhooks enable developers to configure synchronous HTTP callbacks that fire when specific events occur within a Commerce instance, allowing external systems to react in real time to store activity. Webhooks can intercept and modify request data before Commerce processes it, or trigger outbound notifications after an event completes.

- **Human URL:** [https://developer.adobe.com/commerce/extensibility/webhooks/](https://developer.adobe.com/commerce/extensibility/webhooks/)
- **Base URL:** `https://api.example.com`

#### Tags

- E-Commerce
- Events
- Extensibility
- Real-Time
- Webhooks

#### Properties

- [Documentation](https://developer.adobe.com/commerce/extensibility/webhooks/)
- [AsyncAPI](asyncapi/magento-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/magento-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magento-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Commerce Admin UI SDK

The Adobe Commerce Admin UI SDK enables App Builder developers to extend the Commerce Admin panel with custom menus, pages, and UI components built as out-of-process applications. Rather than modifying the Commerce codebase directly, developers build React-based UIs hosted on Adobe App Builder infrastructure and surface them inside the Admin through the SDK's extension point mechanism.

- **Human URL:** [https://developer.adobe.com/commerce/extensibility/admin-ui-sdk/](https://developer.adobe.com/commerce/extensibility/admin-ui-sdk/)
- **Base URL:** `https://api.example.com`

#### Tags

- Admin Panel
- App Builder
- E-Commerce
- Extensibility
- UI Extensions

#### Properties

- [Documentation](https://developer.adobe.com/commerce/extensibility/admin-ui-sdk/)
- [Postman Collection](collections/magento-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magento-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Commerce Eventing

Adobe Commerce Eventing provides an asynchronous event-driven integration framework that publishes Commerce business events to Adobe I/O Events, enabling App Builder applications and other Adobe Experience Cloud services to subscribe and react to store activity. Supported event types cover the full commerce lifecycle including order placement, customer registration, product updates, inventory changes, and payment processing.

- **Human URL:** [https://developer.adobe.com/commerce/extensibility/events/](https://developer.adobe.com/commerce/extensibility/events/)
- **Base URL:** `https://api.example.com`

#### Tags

- Adobe I/O
- App Builder
- E-Commerce
- Events
- Extensibility

#### Properties

- [Documentation](https://developer.adobe.com/commerce/extensibility/events/)
- [AsyncAPI](asyncapi/magento-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/magento-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/magento-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/magento)
- [LinkedIn](https://www.linkedin.com/company/adobe-commerce)
- [JSON-LD](json-ld/magento-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/magento-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/magento-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
