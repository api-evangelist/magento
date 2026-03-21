# Magento (magento)
Adobe Commerce (Magento) is an enterprise e-commerce platform that provides merchants with a flexible, scalable foundation for building online stores. Its developer platform at developer.adobe.com/commerce offers REST, GraphQL, and SOAP APIs along with extensibility tools including webhooks, eventing, and an Admin UI SDK for building out-of-process integrations and headless storefronts.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - E-Commerce, REST, GraphQL, SOAP, Webhooks, Events, Extensibility

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### Magento REST API
The Adobe Commerce (Magento) REST API provides a comprehensive set of endpoints for interacting with all major aspects of an e-commerce store, including catalog management, orders, customers, inventory, shipping, and payments. It supports three authentication mechanisms: OAuth 1.0a for third-party integrations, token-based authentication for mobile apps and administrators, and guest access for select public endpoints. The API follows REST conventions and returns JSON responses, enabling developers to build integrations, automate store operations, and power headless commerce storefronts.

**Human URL:** [https://developer.adobe.com/commerce/webapi/rest/](https://developer.adobe.com/commerce/webapi/rest/)


#### Tags:

 - E-Commerce, REST, Products, Orders, Customers, Catalog

#### Properties

- [Documentation](https://developer.adobe.com/commerce/webapi/rest/)
- [Documentation](https://developer.adobe.com/commerce/webapi/rest/reference/)
- [OpenAPI](openapi/magento-rest-api-openapi.yml)

### Magento GraphQL API
The Adobe Commerce GraphQL API offers a flexible, query-driven interface designed primarily for building headless storefronts and progressive web applications. It exposes a single endpoint and allows clients to request exactly the data they need through queries and mutations covering catalog browsing, product search, cart management, checkout, customer accounts, and order history. The API is optimized for performance with support for the Adobe Commerce Application Server, which keeps the GraphQL process resident in memory to reduce per-request bootstrapping overhead.

**Human URL:** [https://developer.adobe.com/commerce/webapi/graphql/](https://developer.adobe.com/commerce/webapi/graphql/)


#### Tags:

 - E-Commerce, GraphQL, Storefront, Catalog, Cart, Headless Commerce

#### Properties

- [Documentation](https://developer.adobe.com/commerce/webapi/graphql/)
- [Documentation](https://developer.adobe.com/commerce/webapi/graphql/reference/)

### Magento SOAP API
The Adobe Commerce SOAP API exposes the same service contracts as the REST API through a WSDL 1.2 interface compliant with WS-I 2.0 Basic Profile. It allows enterprise systems and legacy integrations to interact with Adobe Commerce store data using standard SOAP tooling. While REST and GraphQL are the recommended interfaces for new integrations, the SOAP API remains supported for backwards compatibility with existing enterprise middleware and ERP systems.

**Human URL:** [https://developer.adobe.com/commerce/webapi/get-started/soap-web-api-calls/](https://developer.adobe.com/commerce/webapi/get-started/soap-web-api-calls/)


#### Tags:

 - E-Commerce, SOAP, Web Services, Integration

#### Properties

- [Documentation](https://developer.adobe.com/commerce/webapi/get-started/soap-web-api-calls/)
- [WSDL](wsdl/magento-soap.wsdl)

### Adobe Commerce Webhooks
Adobe Commerce Webhooks enable developers to configure synchronous HTTP callbacks that fire when specific events occur within a Commerce instance, allowing external systems to react in real time to store activity. Webhooks can intercept and modify request data before Commerce processes it, or trigger outbound notifications after an event completes. They are commonly used to integrate with external order management systems, fraud detection services, ERP platforms, and third-party fulfilment workflows.

**Human URL:** [https://developer.adobe.com/commerce/extensibility/webhooks/](https://developer.adobe.com/commerce/extensibility/webhooks/)


#### Tags:

 - E-Commerce, Webhooks, Events, Extensibility, Real-Time

#### Properties

- [Documentation](https://developer.adobe.com/commerce/extensibility/webhooks/)
- [AsyncAPI](asyncapi/magento-webhooks-asyncapi.yml)

### Adobe Commerce Admin UI SDK
The Adobe Commerce Admin UI SDK enables App Builder developers to extend the Commerce Admin panel with custom menus, pages, and UI components built as out-of-process applications. Rather than modifying the Commerce codebase directly, developers build React-based UIs hosted on Adobe App Builder infrastructure and surface them inside the Admin through the SDK's extension point mechanism. The SDK supports authentication, iframe-based rendering, and communication between the embedded app and the Commerce Admin host.

**Human URL:** [https://developer.adobe.com/commerce/extensibility/admin-ui-sdk/](https://developer.adobe.com/commerce/extensibility/admin-ui-sdk/)


#### Tags:

 - E-Commerce, Extensibility, Admin Panel, App Builder, UI Extensions

#### Properties

- [Documentation](https://developer.adobe.com/commerce/extensibility/admin-ui-sdk/)

### Adobe Commerce Eventing
Adobe Commerce Eventing provides an asynchronous event-driven integration framework that publishes Commerce business events to Adobe I/O Events, enabling App Builder applications and other Adobe Experience Cloud services to subscribe and react to store activity. Supported event types cover the full commerce lifecycle including order placement, customer registration, product updates, inventory changes, and payment processing. The eventing system decouples Commerce from downstream integrations, improving resilience and scalability compared to synchronous webhook or polling approaches.

**Human URL:** [https://developer.adobe.com/commerce/extensibility/events/](https://developer.adobe.com/commerce/extensibility/events/)


#### Tags:

 - E-Commerce, Events, App Builder, Extensibility, Adobe I/O

#### Properties

- [Documentation](https://developer.adobe.com/commerce/extensibility/events/)
- [AsyncAPI](asyncapi/magento-events-asyncapi.yml)

## Common Properties

- [Portal](https://developer.adobe.com/commerce/)
- [Documentation](https://developer.adobe.com/commerce/docs/)
- [Website](https://business.adobe.com/products/magento/magento-commerce.html)
- [PrivacyPolicy](https://www.adobe.com/privacy/policy.html)
- [TermsOfService](https://www.adobe.com/legal/terms.html)
- [Support](https://developer.adobe.com/commerce/contributor/community/)
- [Blog](https://business.adobe.com/blog/the-latest/commerce)
- [Login](https://account.adobe.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
