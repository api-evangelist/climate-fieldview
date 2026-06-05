# Climate FieldView (climate-fieldview)

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
