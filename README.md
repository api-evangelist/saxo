# Saxo Bank

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
