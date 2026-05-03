# CCH Tagetik

CCH Tagetik (a Wolters Kluwer solution) is a comprehensive Corporate Performance Management platform covering financial close and consolidation, extended planning and analysis, ESG and regulatory reporting, and corporate tax management. The platform exposes data via OData v4 REST APIs and SCIM, enabling integration with Power BI, Qlik, SAP HANA, and other BI tools.

**APIs.json URL:** https://raw.githubusercontent.com/api-evangelist/tagetik/refs/heads/main/apis.yml

## APIs

### CCH Tagetik OData API

OData v4 REST API providing read access to CCH Tagetik financial and analytical workspace data. Enables external tools such as Power BI, Qlik, and custom integrations to query financial models, consolidation data, and analytical workspace datasets.

- **Documentation:** https://help.tagetik.com
- **Power BI Connector:** https://learn.microsoft.com/en-us/power-query/connectors/wolters-kluwer-cch-tagetik
- **OpenAPI Spec:** [openapi/cch-tagetik-odata-openapi.yml](openapi/cch-tagetik-odata-openapi.yml)

### CCH Tagetik SCIM API

SCIM v2 API for automated user provisioning and deprovisioning, supporting Microsoft Entra ID (Azure AD) integration.

- **Documentation:** https://docs.microsoft.com/azure/active-directory/saas-apps/cch-tagetik-tutorial

## Artifacts

### OpenAPI Specifications

| API | File |
|---|---|
| CCH Tagetik OData API | [openapi/cch-tagetik-odata-openapi.yml](openapi/cch-tagetik-odata-openapi.yml) |

### JSON Schemas

| Schema | File |
|---|---|
| Financial Record | [json-schema/cch-tagetik-financial-record-schema.json](json-schema/cch-tagetik-financial-record-schema.json) |

### JSON Structures

| Structure | File |
|---|---|
| Financial Record | [json-structure/cch-tagetik-financial-record-structure.json](json-structure/cch-tagetik-financial-record-structure.json) |

### JSON-LD Contexts

| Context | File |
|---|---|
| CCH Tagetik | [json-ld/tagetik-context.jsonld](json-ld/tagetik-context.jsonld) |

### Examples

| Example | File |
|---|---|
| Query Financial Data | [examples/cch-tagetik-query-financial-data-example.json](examples/cch-tagetik-query-financial-data-example.json) |

### Spectral Rules

| Ruleset | File |
|---|---|
| CCH Tagetik OData Rules | [rules/cch-tagetik-odata-rules.yml](rules/cch-tagetik-odata-rules.yml) |

### Naftiko Capabilities

#### Shared Definitions

| API | File |
|---|---|
| CCH Tagetik OData | [capabilities/shared/cch-tagetik-odata.yaml](capabilities/shared/cch-tagetik-odata.yaml) |

#### Workflow Capabilities

| Workflow | Description | File |
|---|---|---|
| Financial Reporting | Query financial consolidation and analytical workspace data for close and reporting workflows | [capabilities/financial-reporting.yaml](capabilities/financial-reporting.yaml) |

### Vocabulary

| Vocabulary | File |
|---|---|
| CCH Tagetik | [vocabulary/tagetik-vocabulary.yml](vocabulary/tagetik-vocabulary.yml) |

## Resources

- **Website:** https://www.wolterskluwer.com/en/solutions/cch-tagetik
- **Documentation:** https://help.tagetik.com
- **Technology Integrations:** https://www.wolterskluwer.com/en/solutions/cch-tagetik/technology-integrations
- **Support:** https://www.wolterskluwer.com/en/solutions/cch-tagetik/services/support
- **Training:** https://www.academy.registration.tagetik.com

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
