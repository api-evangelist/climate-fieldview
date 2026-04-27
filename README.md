# Climate FieldView (climate-fieldview)
Climate FieldView is a digital agriculture platform from Bayer (originally developed by The Climate Corporation) that gives growers, agronomists, and agribusiness partners a single view of field-level operations. The platform ingests as-planted, as-applied, and as-harvested data from field equipment, combines it with imagery, weather, and soil layers, and exposes those agronomic datasets through a REST API at api.climate.com.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/climate-fieldview/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Agriculture, Bayer, Crop Data, Field Boundaries, Harvest, OAuth2, Planting, Precision Ag

## Timestamps

- **Created:** 2025-03-05
- **Modified:** 2026-04-26

## APIs

### Climate FieldView Platform API
The Climate FieldView Platform API is a partner-oriented REST API for reading and writing field-level agronomic data on behalf of growers who have linked their FieldView account. Endpoints expose fields (with GeoJSON boundaries), planting layers, harvest layers, application activities, and soil sample results, and use OAuth 2.0 access tokens passed in the Authorization header. The token endpoint is https://api.climate.com/api/oauth/token; data endpoints live under https://api.climate.com/api/v4 and return JSON with paginated list responses.

**Human URL:** [https://dev.fieldview.com/](https://dev.fieldview.com/)

**Base URL:** https://api.climate.com

#### Tags

- Agriculture, Bayer, Crop Data, Field Boundaries, Harvest, OAuth2, Planting, Precision Ag

#### Properties

- [Documentation](https://dev.fieldview.com/technical-documentation/)
- [Authentication](https://dev.fieldview.com/api-details/)
- [FAQ](https://dev.fieldview.com/faq/)
- [ChangeLog](https://dev.fieldview.com/technical-documentation/next-versions/)
- [SDKs](https://github.com/TheClimateCorporation/api-example)
- [OpenAPI](openapi/climate-fieldview-platform-openapi.yml)

## Common Properties

- [Website](https://climate.com/)
- [Portal](https://dev.fieldview.com/)
- [Documentation](https://dev.fieldview.com/technical-documentation/)
- [Authentication](https://dev.fieldview.com/api-details/)
- [Getting Started](https://dev.fieldview.com/faq/)
- [Terms of Service](https://climate.com/en-us/legal/terms-of-service.html)
- [Privacy Policy](https://climate.com/legal/privacy-policy)
- [GitHub Org](https://github.com/TheClimateCorporation/api-example)
- [Partners](https://climate.com/partners)
- [OpenAPI](openapi/climate-fieldview-platform-openapi.yml)
- [JSON Schema](json-schema/climate-fieldview-field-schema.json)
- [JSON-LD Context](json-ld/climate-fieldview-context.jsonld)
- [Spectral Ruleset](rules/climate-fieldview-rules.yml)
- [Naftiko Capabilities](capabilities/climate-fieldview-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
