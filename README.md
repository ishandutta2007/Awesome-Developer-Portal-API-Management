# Awesome-Developer-Portal-API-Management

## Top Developer Portal & API Management Ecosystem

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

| Product | Company Size (Valuation / Revenue) | Description | Starting Pricing | Free Tier / Trial Limits |
|---------|-----------------------------------|-------------|------------------|--------------------------|
| **[Apigee (Google Cloud)](https://cloud.google.com/apigee)** | **Valuation: ~$3.5T** (Parent: Alphabet/Google); **Revenue: ~$470B/yr** | Enterprise API management platform with gateway, analytics, developer portal, and monetization. Pay-as-you-go environment billing + per-request analytics. Developer portal included with up to 3 custom domains. | **$0.50/hour per environment** (~$365/month) + $20 per 1M API calls | **60-day free evaluation** (Apigee eval environment with full feature access, plus standard $300 GCP trial credits) |
| **[Postman](https://www.postman.com/)** | **Valuation: $5.6B**; **Revenue: ~$313M/yr** | API development, documentation, and collaboration platform with Collections, Mock Servers, Monitors, and CLI. | **$9/month per user** (Solo/Basic billed annually) or $19/user/month (Team) | **Free forever plan**: 1 user seat, unlimited collection runs, up to 3 active mock servers, up to 1,000 cloud API requests/month |
| **[Kong Konnect](https://konghq.com/)** | **Valuation: $2.0B**; **Revenue: >$100M ARR** | Managed API lifecycle platform with hosted control planes, distributed data-plane gateways, and developer portal. | **$25/month** (Serverless control plane) or **$500/month** (Dedicated Cloud Gateway control plane including 1M requests) | **30-day free trial**: Enterprise features, unlimited gateway traffic during trial, 30 days analytics retention |
| **[SwaggerHub](https://swagger.io/tools/swaggerhub/)** | **Valuation: >$1.8B** (Parent: SmartBear); **Revenue: ~$150M+ ARR** | Collaborative OpenAPI design and documentation platform with standardized governance, style checks, and hosted portals. | **$64.80/month per user** (Individual/Team plan) | **Free forever plan**: 1 user, public API definitions only, limited domain component libraries (or **14-day free trial** for Team features) |
| **[Stoplight](https://stoplight.io/)** | **Valuation: >$1.8B** (Parent: SmartBear); **Revenue: ~$150M+ ARR** | API design-first platform with visual OpenAPI editor, style guides, hosted documentation hubs, and Prism mock servers. | **$44/month** (Basic plan, includes 3 users) | **Free forever plan**: 1 user, 1 active workspace project (or **14-day free trial** for Team workspace features) |
| **[WSO2 API Manager](https://wso2.com/api-manager/)** | **Valuation: ~$600M** (Acquired by EQT); **Revenue: ~$100M+ ARR** | Fully open-source capable hybrid/cloud API management suite with control plane, gateway, and developer portal. | **$119/month** (Growth plan: up to 10 Managed Interfaces, 10M Gateway Events) | **30-day free trial**: 5 Managed Interfaces, 1M Gateway Events, 1 Developer Portal included, no credit card required |
| **[Gravitee](https://www.gravitee.io/)** | **Valuation: ~$222M** ($125M+ raised); **Revenue: ~$25M+ ARR** | Event-native and REST API management platform with unlimited users on all tiers. Native support for Kafka, MQTT, and webhooks. | **$2,500/month** (Planet tier: 1 production + 1 non-production gateway, 1 module, Gold support) | **Free forever (Community Edition)**: Apache 2.0 license, self-hosted at unlimited scale and users (or **14-day hosted Cloud trial**) |
| **[Tyk](https://tyk.io/)** | **Valuation: ~$140M**; **Revenue: ~$15M–$18M/yr** | Hybrid/Cloud API management platform with API gateway, developer portal, and dashboard. Open-core model. | **$600/month** (Core entry cloud tier; custom quote for Professional/Enterprise architecture) | **Free forever (Tyk Gateway OSS)**: MPL 2.0 license, unlimited traffic (or **48-hour Tyk Cloud trial** / **30-day Self-Managed trial license**) |
| **[ReadMe](https://readme.com/)** | **Valuation: ~$50M–$100M**; **Revenue: ~$8M–$11M ARR** | Interactive developer hub and documentation portal with API reference generation, live explorer, Git sync, and metrics. | **$250/month** (Pro plan billed annually; or $0 Starter) | **Free forever plan (Starter)**: 1 custom domain, full API reference docs, Git sync, MCP server integration (or **14-day Pro trial**) |

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
