# WeWork (wework)

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
