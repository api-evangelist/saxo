# Saxo Bank

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

Saxo Bank provides an OpenAPI-based REST platform giving developers access to all resources and functionality required to build high-performance multi-asset trading applications. The API covers trading equities, forex, options, futures, and other instruments; real-time and streaming market data; order management; portfolio and account administration; reference data on thousands of tradable instruments; and event notification services.

## APIs

- **Saxo Bank OpenAPI** — REST + WebSocket API covering 17 service groups including Trading, Portfolio, Reference Data, Account History, Market Overview, Chart, Event Notifications, and more. Authenticated via OAuth 2.0.
- **Saxo Bank FIX Trading API** — FIX protocol interface for institutional clients requiring high-frequency and algorithmic trading access.

## Developer Resources

- [Developer Portal](https://www.developer.saxo/openapi/learn)
- [Reference Documentation](https://www.developer.saxo/openapi/referencedocs)
- [API Explorer](https://www.developer.saxo/openapi/explorer)
- [Rate Limiting](https://www.developer.saxo/openapi/learn/rate-limiting)
- [OpenAPI Support Centre](https://openapi.help.saxo/hc/en-us)
- [API Platform Overview](https://www.home.saxo/platforms/api)

## Authentication

OAuth 2.0 with support for Authorization Code Grant, PKCE, Certificate-Based, and Implicit flows. A 24-hour token is available directly from the developer portal for quick-start development.

## Environments

| Environment | Base URL | Cost |
|---|---|---|
| Simulation (SIM) | `https://gateway.saxobank.com/sim/openapi` | Free |
| Production | `https://gateway.saxobank.com/openapi` | Contact Saxo |

## Rate Limits

| Scope | Limit |
|---|---|
| Application daily | 10,000,000 requests/day |
| Session per service group | 120 requests/minute |
| Order placement | 1 order/second |

## Contact

- Email: openapisupport@saxobank.com
- Support: https://openapi.help.saxo/hc/en-us
