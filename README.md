# CCH Tagetik (tagetik)

CCH Tagetik (a Wolters Kluwer solution) is a comprehensive Corporate Performance Management platform covering financial close and consolidation, extended planning and analysis, ESG and regulatory reporting, and corporate tax management. The platform exposes data via OData v4 REST APIs and SCIM, enabling integration with Power BI, Qlik, SAP HANA, and other BI tools. OAuth 2.0 and Basic Authentication are supported for secure access.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analytics
- Budgeting
- Corporate Performance Management
- ESG
- Financial Close
- Financial Consolidation
- Financial Planning
- OData
- Reporting

## Timestamps

- **Created:** 2025-01-15
- **Modified:** 2026-05-19

## APIs

### CCH Tagetik OData API

OData v4 REST API providing read access to CCH Tagetik financial and analytical workspace data. Enables external tools such as Power BI, Qlik, and custom integrations to query financial models, consolidation data, and analytical workspace datasets. Supports Basic Authentication and OAuth 2.0 Client Credentials flow. Available from CCH Tagetik Service Pack 23 (version 5.3+).

- **Human URL:** [https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations](https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations)
- **Base URL:** `https://{your-tagetik-environment}/`

#### Tags

- Financial Data
- Integration
- OData
- REST

#### Properties

- [Documentation](https://help.tagetik.com)
- [Authentication](https://learn.microsoft.com/en-us/power-query/connectors/wolters-kluwer-cch-tagetik)
- [Power  B I  Connector](https://learn.microsoft.com/en-us/power-query/connectors/wolters-kluwer-cch-tagetik)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/openapi/cch-tagetik-odata-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cch-tagetik-odata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cch-tagetik-odata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CCH Tagetik SCIM API

SCIM v2 (System for Cross-domain Identity Management) API for automated user provisioning and deprovisioning in CCH Tagetik. Supports synchronizing users and groups from Microsoft Entra ID (Azure AD) and other identity providers.

- **Human URL:** [https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations](https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations)
- **Base URL:** `https://{your-tagetik-environment}/scim/v2`

#### Tags

- Identity Management
- SCIM
- User Provisioning

#### Properties

- [Documentation](https://docs.microsoft.com/azure/active-directory/saas-apps/cch-tagetik-tutorial)
- [Postman Collection](collections/cch-tagetik-odata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cch-tagetik-odata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tagetik)
- [Website](https://www.wolterskluwer.com/en/solutions/cch-tagetik)
- [Documentation](https://help.tagetik.com)
- [Technology  Integrations](https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations)
- [Support](https://www.wolterskluwer.com/en/solutions/cch-tagetik/services/support)
- [Power  B I  Integration](https://learn.microsoft.com/en-us/power-query/connectors/wolters-kluwer-cch-tagetik)
- [Azure  A D  S S O  Tutorial](https://learn.microsoft.com/azure/active-directory/saas-apps/cch-tagetik-tutorial)
- [Training](https://www.academy.registration.tagetik.com)
- [J S O N  Schema](https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/json-schema/cch-tagetik-financial-record-schema.json)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/vocabulary/tagetik-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
