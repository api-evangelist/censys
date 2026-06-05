# Censys (censys)

Censys is an internet intelligence and attack surface management platform that continuously scans the public IPv4 space, IPv6 announced ranges, and the global certificate transparency ecosystem to produce a comprehensive public dataset of internet-connected hosts, services, certificates, and web properties. The Censys Platform exposes this data through a unified REST API supporting host/web/certificate search, collections, threat hunting, adversary investigation, asset graph traversal, and supply-chain intelligence — making it a primary alternative to Shodan for security researchers, SOC teams, threat hunters, and attack-surface management programs.

**APIs.json:** [https://search.censys.io/api](https://search.censys.io/api)

## Tags

- Security
- Internet Intelligence
- Attack Surface Management
- Threat Hunting
- Cyber Threat Intelligence
- OSINT
- Internet Scanning
- Certificates
- Asset Discovery

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Censys Platform API

The Censys Platform API is the unified next-generation interface to the Censys internet intelligence dataset. It supersedes the legacy Censys Search v1/v2 APIs and Censys ASM API by exposing global asset lookups (hosts, certificates, web properties), Collections, Threat Hunting (CensEye, fingerprints, threats), Adversary Investigation (live discovery scans, certificate-to-host pivots), Account Management (organizations, credits, audit logs), Supply Chain Intelligence, and Tags / Comments through a single Personal Access Token model and Censys Query Language (CenQL).

- **Human URL:** [https://docs.censys.com/reference](https://docs.censys.com/reference)
- **Base URL:** `https://api.platform.censys.io`

#### Tags

- Security
- Internet Intelligence
- Threat Hunting
- Attack Surface Management
- Certificates

#### Properties

- [Documentation](https://docs.censys.com)
- [API Reference](https://docs.censys.com/reference)
- [OpenAPI](openapi/censys-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/censys-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/censys-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman](postman/censys-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Postman](postman/censys-asm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Authentication](https://accounts.censys.io/settings/personal-access-tokens)
- [Quickstart](https://docs.censys.com/docs/platform-quickstart)
- [SDK](https://pypi.org/project/censys-platform/)
- [SDK](https://github.com/censys/censys-sdk-typescript)
- [SDK](https://github.com/censys/censys-sdk-go)
- [SDK](https://pypi.org/project/censys/)
- [Changelog](https://docs.censys.com/changelog)
- [J S O N- L D](json-ld/censys-platform-context.jsonld)

### Censys Asset Graph API

The Censys Asset Graph API powers attack-surface graph traversal. It lets customers define asset graphs from seed assets (IPs, domains, certificates), execute graph build runs, page through the resulting nodes (assets) and edges (relationships), manage excluded assets, and pull risk findings per asset_id. It is the dedicated graph-construction layer that complements the Platform API's per-record host/cert/web lookups.

- **Human URL:** [https://docs.censys.com](https://docs.censys.com)
- **Base URL:** `https://graph.data.censys.io`

#### Tags

- Security
- Attack Surface Management
- Asset Graph
- Risk

#### Properties

- [Documentation](https://docs.censys.com)
- [OpenAPI](openapi/censys-asset-graph-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/censys-asset-graph.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/censys-asset-graph.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://github.com/censys/censys-asset-graph-sdk-go)
- [J S O N- L D](json-ld/censys-asset-graph-context.jsonld)

## Common Properties

- [Website](https://censys.com)
- [Portal](https://platform.censys.io)
- [Sign Up](https://accounts.censys.io/register)
- [Pricing](https://censys.com/pricing/)
- [Terms of Service](https://censys.com/terms-of-service/)
- [Privacy Policy](https://censys.com/privacy-policy/)
- [Status Page](https://status.censys.io)
- [Blog](https://censys.com/blog/)
- [Support](https://support.censys.io)
- [GitHub Organization](https://github.com/censys)
- [C L I](https://github.com/censys/cencli)
- [Tools](https://github.com/censys/censys-splunk)
- [Tools](https://github.com/censys/censys-platform-splunk-soar)
- [Tools](https://github.com/censys/censys-googlesecops-dashboard)
- [Tools](https://github.com/censys/censys-cloud-connector)
- [Tools](https://github.com/censys/censys-maltego)
- [Tools](https://github.com/censys/censys-recon-ng)
- [Tools](https://github.com/censys/nmap-censys)
- [Tools](https://github.com/censys/recog)
- [Tools](https://github.com/schwarztim/sec-censys-mcp)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Plans](plans/censys-plans-pricing.yml)
- [Rate Limits](rate-limits/censys-rate-limits.yml)
- [Fin Ops](finops/censys-finops.yml)
- [Spectral Rules](rules/censys-spectral-rules.yml)
- [Vocabulary](vocabulary/censys-vocabulary.yml)
- [J S O N- L D](json-ld/censys-context.jsonld)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
