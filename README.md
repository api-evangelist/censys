# Censys (censys)
Censys is an internet intelligence and attack surface management platform that continuously scans the public IPv4 space, IPv6 announced ranges, and the global certificate transparency ecosystem to produce a comprehensive public dataset of internet-connected hosts, services, certificates, and web properties. The Censys Platform exposes this data through a unified REST API supporting host/web/certificate search, collections, threat hunting, adversary investigation, asset graph traversal, and supply-chain intelligence — making it a primary alternative to Shodan for security researchers, SOC teams, threat hunters, and attack-surface management programs.

**URL:** [Visit APIs.json URL](https://docs.censys.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Security, Internet Intelligence, Attack Surface Management, Threat Hunting, Cyber Threat Intelligence, OSINT, Internet Scanning, Certificates, Asset Discovery

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Censys Platform API
The Censys Platform API is the unified next-generation interface to the Censys internet intelligence dataset. It supersedes the legacy Censys Search v1/v2 APIs and Censys ASM API by exposing global asset lookups (hosts, certificates, web properties), Collections, Threat Hunting (CensEye, fingerprints, threats), Adversary Investigation (live discovery scans, certificate-to-host pivots), Account Management (organizations, credits, audit logs), Supply Chain Intelligence, and Tags / Comments through a single Personal Access Token model and Censys Query Language (CenQL).

**Human URL:** [https://docs.censys.com/reference](https://docs.censys.com/reference)

**Base URL:** `https://api.platform.censys.io`

#### Tags:

 - Security, Internet Intelligence, Threat Hunting, Attack Surface Management, Certificates

#### Properties

- [Documentation](https://docs.censys.com)
- [APIReference](https://docs.censys.com/reference)
- [OpenAPI](openapi/censys-platform-openapi.yml)
- [Postman](postman/censys-search.postman_collection.json)
- [Postman — Censys ASM Postman Collection](postman/censys-asm.postman_collection.json)
- [Authentication — Personal Access Tokens](https://accounts.censys.io/settings/personal-access-tokens)
- [Quickstart](https://docs.censys.com/docs/platform-quickstart)
- [SDK — Python SDK (censys-platform)](https://pypi.org/project/censys-platform/)
- [SDK — TypeScript SDK](https://github.com/censys/censys-sdk-typescript)
- [SDK — Go SDK](https://github.com/censys/censys-sdk-go)
- [SDK — Python SDK Legacy (censys-python)](https://pypi.org/project/censys/)
- [ChangeLog](https://docs.censys.com/changelog)
- [NaftikoCapability](capabilities/platform-account-management.yaml)
- [NaftikoCapability](capabilities/platform-adversary-investigation.yaml)
- [NaftikoCapability](capabilities/platform-collections.yaml)
- [NaftikoCapability](capabilities/platform-global-data.yaml)
- [NaftikoCapability](capabilities/platform-supply-chain-intelligence.yaml)
- [NaftikoCapability](capabilities/platform-tags-and-comments.yaml)
- [NaftikoCapability](capabilities/platform-threat-hunting.yaml)
- [JSON-LD](json-ld/censys-platform-context.jsonld)


### Censys Asset Graph API
The Censys Asset Graph API powers attack-surface graph traversal. It lets customers define asset graphs from seed assets (IPs, domains, certificates), execute graph build runs, page through the resulting nodes (assets) and edges (relationships), manage excluded assets, and pull risk findings per asset_id. It is the dedicated graph-construction layer that complements the Platform API's per-record host/cert/web lookups.

**Human URL:** [https://docs.censys.com](https://docs.censys.com)

**Base URL:** `https://graph.data.censys.io`

#### Tags:

 - Security, Attack Surface Management, Asset Graph, Risk

#### Properties

- [Documentation](https://docs.censys.com)
- [OpenAPI](openapi/censys-asset-graph-openapi.yml)
- [SDK — Go SDK (Asset Graph)](https://github.com/censys/censys-asset-graph-sdk-go)
- [NaftikoCapability](capabilities/asset-graph-asset-graphs.yaml)
- [NaftikoCapability](capabilities/asset-graph-assets.yaml)
- [NaftikoCapability](capabilities/asset-graph-excluded-assets.yaml)
- [NaftikoCapability](capabilities/asset-graph-graph-executions.yaml)
- [NaftikoCapability](capabilities/asset-graph-risks.yaml)
- [NaftikoCapability](capabilities/asset-graph-seeds.yaml)
- [NaftikoCapability](capabilities/asset-graph-shards.yaml)
- [JSON-LD](json-ld/censys-asset-graph-context.jsonld)

## Common Properties

- [Website](https://censys.com)
- [Portal](https://platform.censys.io)
- [SignUp](https://accounts.censys.io/register)
- [Pricing](https://censys.com/pricing/)
- [TermsOfService](https://censys.com/terms-of-service/)
- [PrivacyPolicy](https://censys.com/privacy-policy/)
- [StatusPage](https://status.censys.io)
- [Blog](https://censys.com/blog/)
- [Support](https://support.censys.io)
- [GitHubOrganization](https://github.com/censys)
- [CLI — cencli — Censys Platform CLI](https://github.com/censys/cencli)
- [Tools — Splunk Add-on and Apps](https://github.com/censys/censys-splunk)
- [Tools — Splunk SOAR Connector](https://github.com/censys/censys-platform-splunk-soar)
- [Tools — Google SecOps Dashboard](https://github.com/censys/censys-googlesecops-dashboard)
- [Tools — Censys Unified Cloud Connector (AWS / Azure / GCP)](https://github.com/censys/censys-cloud-connector)
- [Tools — Maltego Transforms](https://github.com/censys/censys-maltego)
- [Tools — recon-ng Modules](https://github.com/censys/censys-recon-ng)
- [Tools — nmap NSE Script](https://github.com/censys/nmap-censys)
- [Tools — Recog — Pattern Recognition](https://github.com/censys/recog)
- [Tools — MCP Server (Community — sec-censys-mcp)](https://github.com/schwarztim/sec-censys-mcp)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [Plans](plans/censys-plans-pricing.yml)
- [RateLimits](rate-limits/censys-rate-limits.yml)
- [FinOps](finops/censys-finops.yml)
- [SpectralRules](rules/censys-spectral-rules.yml)
- [Vocabulary](vocabulary/censys-vocabulary.yml)
- [JSON-LD](json-ld/censys-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Global Internet Asset Index | Continuously refreshed host, service, certificate, and web-property dataset spanning the public IPv4 space, announced IPv6 ranges, and the global Certificate Transparency log ecosystem. |
| Censys Query Language (CenQL) | Unified, expressive query language used across hosts, certificates, and web properties — replaces the legacy Censys Search Language (CSL). |
| Collections | Saved asset groupings that can be queried, aggregated, and monitored with events, webhooks, and email notifications. |
| Threat Hunting (CensEye) | Automated pivot engine that hunts adversary infrastructure across host endpoints, fingerprints, certificates, and threats with on-demand discovery scans. |
| Adversary Investigation | Certificate-to-host and host-to-endpoint pivots, value-count enrichment, and live re-scan endpoints purpose-built for investigating malicious infrastructure. |
| Asset Graph | Graph-based attack surface composition — define seeds, build graphs, page through assets/edges, manage exclusions, and read per-asset risks. |
| Supply Chain Intelligence | Track third-party supplier exposure and supply-chain risk against the Censys asset dataset. |
| Account Management | Organization, membership, invitation, audit-log, credit, and per-user credit-usage APIs for tenant administration. |
| Tags and Comments | First-class annotation surface for tagging and commenting on assets across the platform. |
| Integrations (Splunk, SOAR, Google SecOps, Maltego, recon-ng, nmap) | Official connectors and community tooling for the major SOC / threat-intel ecosystems. |
| Legacy Search and ASM Compatibility | Censys Search v1/v2 and Censys ASM APIs remain available during the migration window; ASM endpoints are not deprecated. |

## Use Cases

| Name | Description |
|------|-------------|
| External Attack Surface Management | Discover unknown assets, monitor exposure, and prioritize risk across an organization's internet-facing footprint. |
| Threat Hunting | Pivot across certificates, services, and endpoints to track adversary infrastructure with CensEye-driven discovery scans. |
| Adversary Investigation | Investigate IPs, certificates, and hosts associated with known malicious activity; rescan suspect infrastructure on demand. |
| SOC Triage and Enrichment | Enrich alerts in Splunk / SOAR / Google SecOps with Censys host, service, and certificate context. |
| Vulnerability Discovery | Identify exposed services, deprecated TLS versions, and known-vulnerable software footprints at internet scale. |
| Certificate Inventory | Search the certificate-transparency-backed corpus for organizational PKI inventory and rogue/expired cert detection. |
| Subdomain and Asset Discovery | Enumerate subdomains and related assets via certificate, DNS, and IP-graph pivots. |
| Supply Chain Risk | Track supplier exposure and weak links across third-party internet-facing assets. |
| Academic and Internet Measurement Research | Long-running Censys research mission supporting peer-reviewed internet-scale measurement studies. |

## Integrations

| Name | Description |
|------|-------------|
| Splunk | Censys Splunk Add-on and Apps for SIEM enrichment and dashboards. |
| Splunk SOAR | Censys SOAR connector for automated response playbooks. |
| Google SecOps (Chronicle) | Censys Google SecOps dashboard for SOC operations on Chronicle. |
| Microsoft Sentinel | Documented integration path for ingesting Censys data into Sentinel. |
| Maltego | Censys Maltego transforms for graph-based investigations. |
| recon-ng | Censys modules for the recon-ng reconnaissance framework. |
| nmap | NSE script that leverages Censys data for passive recon. |
| AWS / Azure / GCP | Censys Unified Cloud Connector pulls cloud-native asset inventory into Censys ASM. |
| Jira and ServiceNow | ASM ticketing/workflow integrations for asset and risk remediation tracking. |
| Postman | Censys-published Postman collections for Search and ASM APIs. |

## Solutions

| Name | Description |
|------|-------------|
| Censys Platform | Unified next-gen Censys interface for search, collections, threat hunting, and asset graph traversal. |
| Censys Attack Surface Management (ASM) | Continuous external attack-surface monitoring with risk scoring, integrations, and remediation workflows. |
| Censys Threat Hunting | Advanced pivoting, CensEye automation, Censys Threat Dataset, and on-demand scanning for proactive infrastructure hunting. |
| Censys Search (Legacy) | Original search.censys.io interface — Search v1/v2 APIs being migrated to the Platform API. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [censys-asset-graph-openapi.yml](openapi/censys-asset-graph-openapi.yml)
- [censys-platform-openapi.yml](openapi/censys-platform-openapi.yml)

### Postman Collections

- [censys-asm.postman_collection.json](postman/censys-asm.postman_collection.json)
- [censys-search.postman_collection.json](postman/censys-search.postman_collection.json)

### JSON Schema

1151 files in [`json-schema/`](json-schema/) — too many to enumerate individually.
- [asset-graph-activemq-schema.json](json-schema/asset-graph-activemq-schema.json)
- [asset-graph-amqp-protocol-schema.json](json-schema/asset-graph-amqp-protocol-schema.json)
- [asset-graph-amqp-schema.json](json-schema/asset-graph-amqp-schema.json)
- [asset-graph-amqp-version-schema.json](json-schema/asset-graph-amqp-version-schema.json)
- [asset-graph-analyticscapabilities-schema.json](json-schema/asset-graph-analyticscapabilities-schema.json)
- ... and 1146 more

### JSON Structure

1151 files in [`json-structure/`](json-structure/) — too many to enumerate individually.
- [asset-graph-activemq-structure.json](json-structure/asset-graph-activemq-structure.json)
- [asset-graph-amqp-protocol-structure.json](json-structure/asset-graph-amqp-protocol-structure.json)
- [asset-graph-amqp-structure.json](json-structure/asset-graph-amqp-structure.json)
- [asset-graph-amqp-version-structure.json](json-structure/asset-graph-amqp-version-structure.json)
- [asset-graph-analyticscapabilities-structure.json](json-structure/asset-graph-analyticscapabilities-structure.json)
- ... and 1146 more

### JSON-LD

- [censys-asset-graph-context.jsonld](json-ld/censys-asset-graph-context.jsonld)
- [censys-context.jsonld](json-ld/censys-context.jsonld)
- [censys-platform-context.jsonld](json-ld/censys-platform-context.jsonld)

### Examples

1151 files in [`examples/`](examples/) — too many to enumerate individually.
- [asset-graph-activemq-example.json](examples/asset-graph-activemq-example.json)
- [asset-graph-amqp-example.json](examples/asset-graph-amqp-example.json)
- [asset-graph-amqp-protocol-example.json](examples/asset-graph-amqp-protocol-example.json)
- [asset-graph-amqp-version-example.json](examples/asset-graph-amqp-version-example.json)
- [asset-graph-analyticscapabilities-example.json](examples/asset-graph-analyticscapabilities-example.json)
- ... and 1146 more

## Capabilities

Self-contained Naftiko capability files (one per OpenAPI tag). Each file inlines its REST and MCP exposers.

| Capability | API | Operations |
|------------|-----|-----------|
| [Censys Asset Graph — Asset Graphs](capabilities/asset-graph-asset-graphs.yaml) | Censys Asset Graph | 4 |
| [Censys Asset Graph — Assets](capabilities/asset-graph-assets.yaml) | Censys Asset Graph | 2 |
| [Censys Asset Graph — Excluded Assets](capabilities/asset-graph-excluded-assets.yaml) | Censys Asset Graph | 3 |
| [Censys Asset Graph — Graph Executions](capabilities/asset-graph-graph-executions.yaml) | Censys Asset Graph | 3 |
| [Censys Asset Graph — Risks](capabilities/asset-graph-risks.yaml) | Censys Asset Graph | 1 |
| [Censys Asset Graph — Seeds](capabilities/asset-graph-seeds.yaml) | Censys Asset Graph | 3 |
| [Censys Asset Graph — Shards](capabilities/asset-graph-shards.yaml) | Censys Asset Graph | 1 |
| [Censys Platform — Account Management](capabilities/platform-account-management.yaml) | Censys Platform | 11 |
| [Censys Platform — Adversary Investigation](capabilities/platform-adversary-investigation.yaml) | Censys Platform | 11 |
| [Censys Platform — Collections](capabilities/platform-collections.yaml) | Censys Platform | 8 |
| [Censys Platform — Global Data](capabilities/platform-global-data.yaml) | Censys Platform | 23 |
| [Censys Platform — Supply Chain Intelligence](capabilities/platform-supply-chain-intelligence.yaml) | Censys Platform | 4 |
| [Censys Platform — Tags and Comments](capabilities/platform-tags-and-comments.yaml) | Censys Platform | 12 |
| [Censys Platform — Threat Hunting](capabilities/platform-threat-hunting.yaml) | Censys Platform | 13 |

## Plans

- [censys-plans-pricing.yml](plans/censys-plans-pricing.yml)

## Rate Limits

- [censys-rate-limits.yml](rate-limits/censys-rate-limits.yml)

## FinOps

- [censys-finops.yml](finops/censys-finops.yml)

## Vocabulary

- [censys-vocabulary.yml](vocabulary/censys-vocabulary.yml) — Unified taxonomy mapping 9 resources, 6 actions, 14 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [censys-spectral-rules.yml](rules/censys-spectral-rules.yml) — 31 Spectral rules enforcing Censys API conventions.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
