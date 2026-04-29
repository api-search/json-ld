---
api_specs:
- filename: argus-enterprise-core-openapi.yml
  format: yaml
  label: ARGUS Enterprise Core API
  slug: argus-enterprise-core
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/openapi/argus-enterprise-core-openapi.yml
- filename: argus-enterprise-webhooks-openapi.yml
  format: yaml
  label: ARGUS Enterprise Webhook API
  slug: argus-enterprise-webhooks
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/openapi/argus-enterprise-webhooks-openapi.yml
class_count: 0
classes: []
context_file: json-ld/argus-enterprise-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/json-ld/argus-enterprise-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argus Enterprise from ARGUS Enterprise.
layout: jsonld
name: Argus Enterprise Context
namespaces:
- prefix: argus
  uri: https://api.argusenterprise.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Property
  type: ''
- container: ''
  name: Portfolio
  type: ''
- container: ''
  name: Valuation
  type: ''
- container: ''
  name: Lease
  type: ''
- container: ''
  name: Tenant
  type: ''
- container: ''
  name: CashFlowProjection
  type: ''
- container: ''
  name: Report
  type: ''
- container: ''
  name: User
  type: ''
property_count: 8
provider_name: ARGUS Enterprise
provider_slug: argus-enterprise
slug: argus-enterprise-context
source_filename: argus-enterprise-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argus\": \"https://api.argusenterprise.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Property\": {\n      \"@id\": \"argus:Property\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"propertyType\": \"argus:propertyType\",\n        \"status\": \"argus:status\",\n        \"address\": \"schema:address\",\n        \"grossArea\": {\n          \"@id\": \"argus:grossArea\",\n          \"@type\": \"xsd:double\"\n        },\n        \"netLeasableArea\": {\n          \"@id\": \"argus:netLeasableArea\",\n          \"@type\": \"xsd:double\"\n        },\n        \"yearBuilt\": {\n          \"@id\": \"argus:yearBuilt\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numberOfUnits\": {\n          \"@id\": \"argus:numberOfUnits\",\n          \"@type\": \"xsd:integer\"\n        },\n\
  \        \"purchasePrice\": {\n          \"@id\": \"argus:purchasePrice\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currentMarketValue\": {\n          \"@id\": \"argus:currentMarketValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"occupancyRate\": {\n          \"@id\": \"argus:occupancyRate\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"Portfolio\": {\n      \"@id\": \"argus:Portfolio\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"strategy\": \"argus:investmentStrategy\",\n        \"totalProperties\": {\n          \"@id\": \"argus:totalProperties\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalMarketValue\": {\n          \"@id\": \"argus:totalMarketValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currency\": \"argus:currency\"\n      }\n    },\n\n    \"Valuation\": {\n      \"@id\": \"argus:Valuation\",\n\
  \      \"@context\": {\n        \"valuationDate\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"methodology\": \"argus:valuationMethodology\",\n        \"marketValue\": {\n          \"@id\": \"argus:marketValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"capRate\": {\n          \"@id\": \"argus:capitalizationRate\",\n          \"@type\": \"xsd:double\"\n        },\n        \"discountRate\": {\n          \"@id\": \"argus:discountRate\",\n          \"@type\": \"xsd:double\"\n        },\n        \"terminalCapRate\": {\n          \"@id\": \"argus:terminalCapRate\",\n          \"@type\": \"xsd:double\"\n        },\n        \"netOperatingIncome\": {\n          \"@id\": \"argus:netOperatingIncome\",\n          \"@type\": \"xsd:double\"\n        },\n        \"netPresentValue\": {\n          \"@id\": \"argus:netPresentValue\",\n          \"@type\": \"xsd:double\"\n        },\n        \"internalRateOfReturn\": {\n          \"\
  @id\": \"argus:internalRateOfReturn\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"Lease\": {\n      \"@id\": \"argus:Lease\",\n      \"@context\": {\n        \"tenantName\": \"schema:name\",\n        \"leaseType\": \"argus:leaseType\",\n        \"status\": \"argus:leaseStatus\",\n        \"startDate\": {\n          \"@id\": \"argus:leaseStartDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"argus:leaseEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"leasedArea\": {\n          \"@id\": \"argus:leasedArea\",\n          \"@type\": \"xsd:double\"\n        },\n        \"baseRent\": {\n          \"@id\": \"argus:baseRent\",\n          \"@type\": \"xsd:double\"\n        },\n        \"rentPerSquareFoot\": {\n          \"@id\": \"argus:rentPerSquareFoot\",\n          \"@type\": \"xsd:double\"\n        },\n        \"escalationRate\": {\n          \"@id\": \"argus:escalationRate\",\n          \"\
  @type\": \"xsd:double\"\n        },\n        \"escalationType\": \"argus:escalationType\"\n      }\n    },\n\n    \"Tenant\": {\n      \"@id\": \"argus:Tenant\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"industry\": \"argus:industry\",\n        \"creditRating\": \"argus:creditRating\",\n        \"contactName\": \"schema:contactPoint\",\n        \"contactEmail\": \"schema:email\",\n        \"contactPhone\": \"schema:telephone\",\n        \"activeLeases\": {\n          \"@id\": \"argus:activeLeases\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalLeasedArea\": {\n          \"@id\": \"argus:totalLeasedArea\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"CashFlowProjection\": {\n      \"@id\": \"argus:CashFlowProjection\",\n      \"@context\": {\n        \"startDate\": {\n          \"@id\": \"argus:projectionStartDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"\
  argus:projectionEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"frequency\": \"argus:cashFlowFrequency\",\n        \"currency\": \"argus:currency\"\n      }\n    },\n\n    \"Report\": {\n      \"@id\": \"argus:Report\",\n      \"@context\": {\n        \"reportType\": \"argus:reportType\",\n        \"title\": \"schema:name\",\n        \"status\": \"argus:reportStatus\",\n        \"generatedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": \"dcterms:creator\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"argus:User\",\n      \"@context\": {\n        \"username\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"role\": \"argus:userRole\",\n        \"lastLogin\": {\n          \"@id\": \"argus:lastLogin\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"active\": {\n\
  \          \"@id\": \"argus:active\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argus-enterprise/refs/heads/main/json-ld/argus-enterprise-context.jsonld
tags:
- Altus Group
- Asset Management
- Cash Flow Modeling
- Commercial Real Estate
- Portfolio Management
- Valuation
- JSON-LD
- Linked Data
- Semantic Web
---
