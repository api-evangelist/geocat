# GeoCat bv

GeoCat bv is a Dutch company built around the open-source geospatial stack, and is the primary maintainer of GeoNetwork, the catalogue software that runs a large share of Europe's INSPIRE metadata infrastructure. It sells GeoCat Bridge, GeoCat Live and hosted catalogue services, and runs a public demonstration estate serving both classic OGC web services and a modern OGC API - Features endpoint.

Profiled 2026-08-20 as part of the [OGC](../ogc/) standards-body pass — this organization is an
**OGC Explorer member** (Commercial, Netherlands), found in OGC's own
active-member roster and confirmed to serve a live OGC surface on its own host.

## APIs

| aid | name | base | contract |
|---|---|---|---|
| `geocat:ogc-web-services` | GeoCat bv OGC Web Services (WMS / WFS) | https://maps.geocat.net/geoserver/ows | 2 GetCapabilities |
| `geocat:ogc-api-features` | GeoCat bv OGC API - Features | https://maps.geocat.net/geoserver/ogc/features/v1 | 0 GetCapabilities |

## Provenance

Every GetCapabilities document under `openapi/` was retrieved **anonymously, with HTTP 200, on
2026-08-20** and is stored verbatim — it is the machine-readable contract for a classic OGC service,
which has no OpenAPI. Nothing here is derived from documentation.

Membership facts come from `https://portal.ogc.org/services/srv_active_members_csv_new.php`.
