# opendata.gov.al (opendata-gov-al)

opendata.gov.al (Open Data Albania) is Albania's national government open-data portal — a **custom DCAT-AP-compliant platform** (Angular SPA over a bespoke REST API) with a SPARQL endpoint, harvested into data.europa.eu. It is **not** CKAN/DKAN.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/opendata-gov-al/refs/heads/main/apis.yml)

## Type
- **kind:** government  ·  **software:** custom (DCAT-AP, SPARQL)

## API
- **Open Data Albania REST API** — base `https://opendata.gov.al/api`. Action-style routes: `POST /api/Dataset/filter`, `GET /api/Dataset/get/{slug}`, `GET /api/DcatCategory`, `GET /api/Institution`.
- **SPARQL endpoint** — `https://opendata.gov.al/api/Sparql`.
- No public OpenAPI/Swagger located. Endpoint surface verified from the SPA JS bundle.
- **Note:** the live site is behind an F5 BIG-IP WAF that blocks non-browser clients (TLS/JA3 fingerprinting), so JSON payloads were not retrievable from automated probes; endpoint existence is verified.

## Timestamps
- **Created:** 2026-06-23
- **Modified:** 2026-06-23

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
