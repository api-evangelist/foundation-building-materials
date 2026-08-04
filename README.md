# Foundation Building Materials

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
