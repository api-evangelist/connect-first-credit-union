# connectFirst Credit Union (connect-first-credit-union)

connectFirst Credit Union is a member-owned, cooperative financial institution headquartered in Calgary, Alberta, formed on May 3, 2021 by amalgamating four Alberta credit unions (First Calgary Financial, Chinook Financial, Mountain View Financial, and Legacy Financial). At its peak it held over CAD $6 billion in assets under administration and served more than 128,000 members across 41 branches in Central and Southern Alberta.

Members voted in November 2023 to merge with Servus Credit Union. The legal amalgamation closed **May 1, 2024** as "Connect First and Servus Credit Union Ltd." (~CAD $29.3B assets, 600,000+ members), and the unified brand realigned to **Servus Credit Union** in January 2025. The `connectfirstcu.com` domain now 301-redirects to `servus.ca`.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/connect-first-credit-union/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/connect-first-credit-union/refs/heads/main/apis.yml)

## Open-Finance & API Posture

- **No first-party developer portal.** Probes of `developer.connectfirstcu.com`, `api.connectfirstcu.com`, and `developers.connectfirstcu.com` do not resolve (no DNS/connection). There is no public developer console, API reference, or downloadable OpenAPI/Swagger.
- **Digital banking** is delivered via the **Celero Xpress** platform (powered by ebankIT), with core and banking-technology through the **Central 1 / Celero** cooperative ecosystem — not a self-published API surface.
- **Consumer data access is aggregator-based.** Third-party access is available through open-banking aggregators (Plaid coverage is confirmed) rather than a first-party data-sharing API.
- **Canadian open finance is voluntary.** The federal Consumer-Driven Banking framework (Budget 2024 / Fall Economic Statement 2024, overseen by the FCAC) is legislated but **not yet operational**, so no mandated open-banking API exists for this institution. No documented FDX participation and no stated 1033-style posture (a U.S. construct that does not apply in Canada).
- **Shared Canadian rails** (Interac e-Transfer, Payments Canada RTR/Lynx) are consumed as a member of the cooperative banking system; no institution-specific API around them is published.

This is an **identity-only** record: the institution exposes no public API. It is retained under its own slug for lineage, with the note that the operating entity is now Servus Credit Union.

## Tags

- Financial Services
- Banking
- Canada
- Credit Union
- Alberta
- Cooperative
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. connectFirst Credit Union does not publish a public API or developer portal.

## Common Properties

- [Website](https://www.connectfirstcu.com/) (redirects to servus.ca following the 2024 merger)
- [Blog / News](https://connectfirstcu.com/en/news/news-and-announcments)
- [LinkedIn](https://www.linkedin.com/company/connect-first-credit-union)
- [Privacy Policy](https://servus.ca/privacy) (successor entity)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
