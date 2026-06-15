# magento (magento)

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
