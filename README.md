# Foundation Building Materials

API Evangelist network profile for **Foundation Building Materials (FBM)** — a
leading North American distributor of interior building products (drywall,
steel framing, acoustic ceilings, insulation, and complementary construction
supplies), headquartered in Santa Ana, California. FBM serves commercial and
residential contractors across the United States and Canada through a national
branch network and the unified MyFBM ordering portal.

- Canonical URL: <https://www.myfbm.com>
- Legacy URL (redirects): <https://www.fbmsales.com>
- Network registry: [api-evangelist/network](https://github.com/api-evangelist/network)

## At a glance

- **Brand families:** FBM, RIS, Pacific Source, Unified Door
- **Customer portal:** [MyFBM](https://www.myfbm.com) — web + iOS / Android, ~5,099 SKUs catalogued, inventory visibility, per-unit + bulk (MSF/MLF) pricing
- **Recent moves:**
  - **Apr 2025** — Acquired KCG/Rew Materials, adding 800 employees and 45 distribution branches across 23 states ([news](https://www.myfbm.com/news)).
  - **Aug 2025** — Lowe's announced an agreement to acquire FBM ([news](https://www.myfbm.com/news)).
  - **Apr 2026** — Launched **Quick Order Entry (QOE)** — converts PDFs, photos, or handwritten POs into confirmed orders within 24 hours.

## Public API surface

**None.** FBM does not currently publish:

- A developer portal or API reference
- OpenAPI / AsyncAPI / JSON Schema specifications
- An SDK, CLI, or public integration program
- A GitHub organization
- A documented EDI / punchout / partner-API offering

FBM's external digital surface is buyer-facing only — search, ordering, order
tracking, account management — and is not exposed as a programmable API.
The closest analogue to an order-ingestion API is the human-in-the-loop
**Quick Order Entry** service, which ingests PDFs/photos of purchase orders
and returns confirmed orders within 24 hours via FBM operations staff.

This repository therefore catalogues FBM's **business surface** rather than a
programmable one, so the API Evangelist network can place it relative to
peer distributors and watch for any future digital/API-product moves
(especially in the context of the pending Lowe's acquisition).

## Artifacts in this repo

| File | Purpose |
|---|---|
| [`apis.yml`](./apis.yml) | apis.json/0.20 index — company-level properties, customer-portal links, news, FAQ, contact, careers, social, compliance. No `apis:` entries (no public APIs to document). |
| `README.md` | This file. |

No `openapi/`, `asyncapi/`, `json-schema/`, `capabilities/`, `rules/`,
`examples/`, or `vocabulary/` directories are present — per pipeline policy,
artifact folders are only created when there is real content to back them.

## Related profiles

FBM sits in the broader building-products distribution segment alongside
companies like Beacon Building Products, GMS Inc., ABC Supply, US LBM, and
SRS Distribution. The pending Lowe's acquisition will be tracked here as it
closes and any post-merger digital-integration program emerges.

---

Maintained by [Kin Lane](https://apievangelist.com) as part of the
[API Evangelist Network](https://github.com/api-evangelist/network).
