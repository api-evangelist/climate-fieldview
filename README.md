# Climate FieldView (climate-fieldview)

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

Climate FieldView is a digital agriculture platform from Bayer (originally developed by The Climate Corporation) that gives growers, agronomists, and agribusiness partners a single view of field-level operations. The platform ingests as-planted, as-applied, and as-harvested data from field equipment, combines it with imagery, weather, and soil layers, and exposes those agronomic datasets through a REST API at api.climate.com. Authentication is via OAuth 2.0 authorization-code grant, and resources include fields, planting and harvest activities, application records, and soil samples.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/climate-fieldview/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/climate-fieldview/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Agriculture
- Bayer
- Crop Data
- Field Boundaries
- Harvest
- OAuth2
- Planting
- Precision Ag

## Timestamps

- **Created:** 2025-03-05
- **Modified:** 2026-05-19

## APIs

### Climate FieldView Platform API

The Climate FieldView Platform API is a partner-oriented REST API for reading and writing field-level agronomic data on behalf of growers who have linked their FieldView account. Endpoints expose fields (with GeoJSON boundaries), planting layers, harvest layers, application activities, and soil sample results, and use OAuth 2.0 access tokens passed in the Authorization header. The token endpoint is https://api.climate.com/api/oauth/token; data endpoints live under https://api.climate.com/api/v4 and return JSON with paginated list responses.

- **Human URL:** [https://dev.fieldview.com/](https://dev.fieldview.com/)
- **Base URL:** `https://api.climate.com`

#### Tags

- Agriculture
- Bayer
- Crop Data
- Field Boundaries
- Harvest
- OAuth2
- Planting
- Precision Ag

#### Properties

- [Documentation](https://dev.fieldview.com/technical-documentation/)
- [Authentication](https://dev.fieldview.com/api-details/)
- [F A Q](https://dev.fieldview.com/faq/)
- [Changelog](https://dev.fieldview.com/technical-documentation/next-versions/)
- [S D Ks](https://github.com/TheClimateCorporation/api-example)
- [OpenAPI](openapi/climate-fieldview-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/climate-fieldview-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/climate-fieldview-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/climate-llc)
- [Website](https://climate.com/)
- [Portal](https://dev.fieldview.com/)
- [Documentation](https://dev.fieldview.com/technical-documentation/)
- [Authentication](https://dev.fieldview.com/api-details/)
- [Getting Started](https://dev.fieldview.com/faq/)
- [Terms of Service](https://climate.com/en-us/legal/terms-of-service.html)
- [Privacy Policy](https://climate.com/legal/privacy-policy)
- [Git Hub Org](https://github.com/TheClimateCorporation/api-example)
- [Partners](https://climate.com/partners)
- [OpenAPI](openapi/climate-fieldview-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/climate-fieldview-field-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/climate-fieldview-context.jsonld)
- [Spectral Rules](rules/climate-fieldview-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
