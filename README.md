# WeWork (wework)

WeWork is a global flexible-workspace provider operating roughly 600 owned coworking locations and a Coworking Partner Network of 2,000+ third-party spaces across 20+ countries. The company filed for Chapter 11 bankruptcy on November 6, 2023 and emerged on May 30, 2024 as a private company majority-owned by real estate technology vendor Yardi Systems (60%), with SoftBank affiliates retaining roughly 20%. John Santora was appointed CEO in June 2024.

WeWork exposes a Partner API for two integrator types: Supply Partners (operators contributing spaces to WeWork's inventory) and Demand Partners (resellers and platforms booking WeWork inventory on behalf of end users). The portal's verbatim description: "Our APIs allow you access to inventory worldwide and enable you to integrate our platform into your own applications and services." The full API reference is gated behind Auth0 sign-in and is not publicly browsable, so no OpenAPI specifications, endpoint paths, schemas, rate-limit policies, or pricing terms could be catalogued from public sources.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/wework/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=wework-api-evangelist&utm_content=repo)

## Tags

- Coworking, Flexible Workspace, Real Estate, Workspace Booking, Workplace Management, Bookings, Inventory

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### WeWork Partner API

The WeWork Partner API exposes the company's global workspace inventory to integrators. Documented capability domains include Identity (user lookup), Locations, Inventory, Availability and Calendaring, Booking, and Keycard Access. Authentication uses service tokens, and access requires a partner application and review process. The reference documentation is gated behind Auth0, so endpoint paths and schemas are not publicly catalogable.

**Human URL:** [https://developers.wework.com](https://developers.wework.com)

#### Tags

- Partner API, Bookings, Inventory, Locations, Availability, Calendaring, Identity, Keycard Access

#### Properties

- [Developer Portal](https://developers.wework.com)
- [Documentation](https://developers.wework.com/docs)
- [API Reference](https://developers.wework.com/docs/api-reference)
- [Quickstart](https://developers.wework.com/docs/quick-start)
- [Release Notes](https://developers.wework.com/docs/release-notes)
- [Authentication / Service Tokens](https://developers.wework.com/how-to-guides/how-to-create-service-tokens)
- [Sign Up / Request Access](https://developers.wework.com/quick-start/request-access/submit-app-for-review)
- [Partner With Us](https://www.wework.com/info/partner-with-us)

### WeWork Workplace

WeWork Workplace is the company's SaaS workplace-management platform sold to enterprises and landlords. No public API documentation, OpenAPI spec, or integration surface for Workplace could be located; the dedicated marketing site at workplace.wework.com returned HTTP 403 during research.

**Human URL:** [https://www.wework.com](https://www.wework.com)

#### Tags

- Workplace Management, Enterprise, SaaS

#### Properties

- [Portal](https://www.wework.com)

## Common Properties

- [Portal](https://www.wework.com)
- [Developer Portal](https://developers.wework.com)
- [Documentation](https://developers.wework.com/docs)
- [API Reference](https://developers.wework.com/docs/api-reference)
- [Quickstart](https://developers.wework.com/docs/quick-start)
- [Release Notes](https://developers.wework.com/docs/release-notes)
- [Authentication](https://developers.wework.com/how-to-guides/how-to-create-service-tokens)
- [Sign Up](https://developers.wework.com/quick-start/request-access/submit-app-for-review)
- [Partners](https://www.wework.com/info/partner-with-us)
- [Login (Members)](https://members.wework.com)
- [Help Center](https://help.wework.com)
- [Newsroom](https://newsroom.wework.com)
- [Contact](https://www.wework.com/contact-us)
- [Privacy](https://www.wework.com/legal/privacy)
- [Terms of Service](https://www.wework.com/legal/terms-of-service)
- [Cookie Policy](https://www.wework.com/legal/cookie-policy)
- [Accessibility](https://www.wework.com/legal/accessibility)
- [Careers](https://careers.wework.com)
- [GitHub Organization](https://github.com/wework)
- [LinkedIn](https://www.linkedin.com/company/wework)

## Engineering Tools (Not Partner API SDKs)

The WeWork GitHub organization (`github.com/wework`, 36 public repos, most last touched 2022-2023) publishes internal engineering tools rather than Partner API client SDKs. Notable repos:

- [speccy](https://github.com/wework/speccy) — OpenAPI 3.0.x linter (842 stars)
- [json-schema-to-openapi-schema](https://github.com/wework/json-schema-to-openapi-schema) — JSON Schema to OpenAPI Schema converter (220 stars)
- [grabbit](https://github.com/wework/grabbit) — Go transactional message bus on RabbitMQ (100 stars)
- [ray](https://github.com/wework/ray) — WeWork design system resources (55 stars)

No official Partner API SDK (Python, JavaScript, Ruby, Go, Java, .NET) was located in the org or on package registries.

## Notable Absences

- No publicly accessible OpenAPI / Swagger / AsyncAPI specification
- No public endpoint paths or request/response schemas (entire reference sits behind Auth0)
- No public pricing or rate-limit documentation for the Partner API
- No public status page (status.wework.com / wework.com/info/status both 404)
- No RSS / changelog feed for release notes (release notes themselves are auth-gated)
- No official Partner API SDK or CLI on GitHub or package registries
- No public WeWork Workplace API documentation

## Post-Restructuring Context

WeWork emerged from Chapter 11 in mid-2024 having shed approximately $4 billion in debt and cancelled leases at roughly 160 of its 450 owned locations. The new majority owner, Yardi Systems, is itself a long-standing real estate technology vendor — meaning WeWork's developer surface is now embedded in a portfolio of property-tech assets rather than operated as a standalone tech-company API platform. The Partner API has survived the restructuring intact based on the live developer portal at developers.wework.com.
