# Awesome-Developer-Portal-API-Management

# Top Developer Portal & API Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on API Gateways, Developer Portals & Lifecycle Governance*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Portal & API Management**. These tools help organizations expose APIs securely, onboard developers with self-service portals, enforce rate limits and authentication, and monitor API usage—covering everything from gateway infrastructure to documentation portals and lifecycle governance.

**Examples** include Apigee, Kong Konnect, Gravitee, WSO2 API Manager, Tyk, SwaggerHub, Stoplight, ReadMe, and Postman (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted API gateways, open-source developer portals, and community-driven API tooling—ideal for organizations seeking data sovereignty and predictable costs over per-request or per-gateway SaaS billing. The open-source landscape is genuinely strong: **Tyk Gateway** is MPL-licensed with a paid portal layer , **WSO2 API Manager** is fully Apache-2.0 with a free trial , and **Gravitee** offers an Apache-2.0 community edition alongside its paid Planet tier . Note that **Kong's open-source gateway is separate from Konnect**—the managed control plane starts at $500/month per control plane [citation:3].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Apigee (Google Cloud)](https://cloud.google.com/apigee)** | Enterprise API management platform with gateway, analytics, developer portal, and monetization. **Pay-as-you-go** billing for gateway nodes (per minute), API analytics (per request analyzed), and networking usage—no upfront commitment [citation:12]. Developer portal included with up to 3 custom domains [citation:2]. | Pay-as-you-go (gateway nodes per-minute + analytics per-request); Subscription: quote-only | **60-day free evaluation plan** [citation:12] |
| **[Kong Konnect](https://konghq.com/)** | Managed API lifecycle platform with control plane, gateways, and developer portal. **Konnect Plus: $500/month per Dedicated Cloud Gateway control plane** (includes 1M API requests, 5 Serverless Gateways, 2 Hybrid Gateways, 2 DCGW). Serverless control plane $25/month; Hybrid $200/month. Overage: $200/month per additional 1M requests; **$200/month per additional Developer Portal** [citation:3]. | Plus: **$500/month per control plane** (1M requests); Enterprise: custom | **30-day free trial**: full Enterprise functionality, no Gateway limits, analytics retained 30 days [citation:3] |
| **[Gravitee](https://www.gravitee.io/)** | API management with **unlimited users on all tiers**. **Planet tier: $2,500/month** for 1 production + 1 non-production Gateway, 1 module of choice, and Gold Support. Galaxy/Universe add more gateways and modules. Event-native support for Kafka, MQTT, Solace, RabbitMQ [citation:7]. | Planet: **$2,500/month** (1 prod + 1 non-prod gateway, 1 module) [citation:7] | **Community Edition**: Apache 2.0, free at any scale; **cloud trial** via website [citation:7] |
| **[WSO2 API Manager](https://wso2.com/api-manager/)** | Fully open-source API management suite with control plane, gateway, and developer portal. **Growth plan: from $119/month** for up to 10 Managed Interfaces and 10M Gateway Events. Developer Portal add-on $100/month. **Self-hosted Enterprise** available with custom pricing [citation:8]. | Growth: **from $119/month** (10 interfaces, 10M events); Enterprise: custom | **30-day free trial**: 5 Managed Interfaces, 1M Gateway Events, 1 Developer Portal, no credit card [citation:8] |
| **[Tyk](https://tyk.io/)** | Open-core API gateway (**Tyk Gateway and Pump are MPL 2.0, free**). Paid components: Dashboard, Developer Portal, Operator, MDCB. **No public list pricing**—plans quoted by sales. Core is usage-based (per API); Professional is architecture-based (data planes, environments, control planes), unlimited APIs and calls [citation:9]. | Quote-only (Core usage-based; Professional flat by architecture) [citation:9] | **Self-Managed trial license** available via request; Tyk Gateway OSS free forever (MPL 2.0) [citation:9] |
| **[SwaggerHub](https://swagger.io/tools/swaggerhub/)** | OpenAPI-centric platform with API design, documentation, and collaboration. Software Advice lists starting price at **$64.80/month** per user . | **$64.80/month** per user [citation:5] | Free version available; free trial offered [citation:5] |
| **[Stoplight](https://stoplight.io/)** | API design-first platform with visual OpenAPI editor, style guides, and workspace collaboration. **Basic: $44/month** (first 3 users free); **Startup: $113/month** (first 8 users free); **Pro Team: $362/month** (first 15 users free) . | Basic: **$44/month**; Startup: $113; Pro Team: $362  | No free tier for team workspaces; paid plans include free user slots  |
| **[ReadMe](https://readme.com/)** | API documentation and developer hub platform. **Starter: $0** (custom domain, API reference, Git sync, usage metrics, MCP server). **Pro: $250/month** (annual billing) adds team collaboration, private docs, custom MDX, CSS/HTML. Ask AI add-on $150/month [citation:4]. | Starter: **$0**; Pro: **$250/month** (annual) [citation:4] | **Starter (free)**: custom domain, API reference, Git sync, MCP server; **14-day Pro trial** [citation:4] |
| **[Postman](https://www.postman.com/)** | API development environment with Collections, Mock Servers, Monitors, and CLI. March 2026 restructure made collection runs unlimited but removed team workspaces from free plan. | Solo: $9/month; Team: $19/user/month | **Free**: 1 user only, unlimited collection runs, no team workspace |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Tyk Gateway](https://github.com/TykTechnologies/tyk)** | [![Stars](https://img.shields.io/github/stars/TykTechnologies/tyk?style=social&color=white)](https://github.com/TykTechnologies/tyk/stargazers) | **Open-source API gateway (MPL 2.0).** Dashboard, Developer Portal, and MDCB are paid components. Supports REST, GraphQL, TCP, and UDP. MCP Gateway implements 2025-11-25 MCP revision. **No lock-in**: if a Tyk license lapses, existing APIs keep serving traffic; API definitions can be exported to run on the open-source Gateway [citation:9]. |
| **[WSO2 API Manager](https://github.com/wso2/product-apim)** | [![Stars](https://img.shields.io/github/stars/wso2/product-apim?style=social&color=white)](https://github.com/wso2/product-apim/stargazers) | **Fully open-source (Apache 2.0) API management suite.** Control plane, gateway, and developer portal. Self-hosted free to run; enterprise support via subscription. The only tool in this list with a **free trial that includes a developer portal** (5 interfaces, 1M events) [citation:8]. |
| **[Gravitee API Management (OSS)](https://github.com/gravitee-io/gravitee-api-management)** | [![Stars](https://img.shields.io/github/stars/gravitee-io/gravitee-api-management?style=social&color=white)](https://github.com/gravitee-io/gravitee-api-management/stargazers) | **Apache-2.0 open-core API management.** Covers HTTP and event-driven APIs (Kafka, MQTT, webhooks). Community Edition is **free at any scale with unlimited users**. AI/LLM features (Agent Management, MCP proxy) are paid add-ons [citation:7]. |
| **[Azure API Management Developer Portal](https://github.com/Azure/api-management-developer-portal)** | [![Stars](https://img.shields.io/github/stars/Azure/api-management-developer-portal?style=social&color=white)](https://github.com/Azure/api-management-developer-portal/stargazers) | **Self-hosted developer portal for Azure API Management.** ~486 stars, actively updated. Reusable examples of APIM policies included. The portal itself is open-source; the APIM service is Azure-managed [citation:1]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Kong Gateway (OSS)](https://github.com/Kong/kong)** | [![Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers) | The most widely deployed open-source API gateway. Lua/OpenResty-based with rich plugin ecosystem. **Separate from Konnect**—the managed control plane requires a paid subscription [citation:3]. |
| **[KrakenD](https://github.com/krakend/krakend-ce)** | [![Stars](https://img.shields.io/github/stars/krakend/krakend-ce?style=social&color=white)](https://github.com/krakend/krakend-ce/stargazers) | Ultra-fast stateless API gateway in Go with declarative configuration. Aggregates multiple backend services into a single API endpoint without code. |
| **[Fusio](https://github.com/apioo/fusio)** | [![Stars](https://img.shields.io/github/stars/apioo/fusio?style=social&color=white)](https://github.com/apioo/fusio/stargazers) | Self-hosted API management platform (~2,118 stars per OpenAPI Tooling listing). PHP-based with OpenAPI 3.0 support [citation:10]. |

**Frameworks for building custom systems**: Combine **Tyk Gateway** or **Kong OSS** for API routing and policy enforcement, **WSO2 API Manager** for a complete open-source management suite with developer portal, and **Gravitee Community Edition** for event-native API support—creating a fully self-hosted API management stack without per-request or per-gateway SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- API management platforms handle authentication tokens and route all API traffic; enforce least-privilege policies, rate limiting, and audit logging.
- **Pricing models vary dramatically and are frequently opaque.** Tyk has **no public list pricing by design** [citation:9]. Kong's initial quotes often start **30–50% above what buyers ultimately pay** [citation:13]. Apigee's pay-as-you-go bills per gateway node-minute plus per analyzed request [citation:12]. **Open-source alternatives eliminate per-request fees but require operational effort**: WSO2 offers the most complete free trial including a developer portal [citation:8], Gravitee's Community Edition is free at any scale with unlimited users [citation:7], and Tyk's Gateway has no lock-in if a license lapses [citation:9]. Always validate current pricing and feature availability against vendor pages before committing.

---

**Made for API architects, platform engineers, and organizations building developer-facing infrastructure.**  
Let's make developer portals and API management more open, governed, and cost-predictable.
