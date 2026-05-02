---
api_specs:
- filename: harbor-compliance-openapi.yml
  format: yaml
  label: Harbor Compliance API
  slug: harbor-compliance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/harbor-compliance/refs/heads/main/openapi/harbor-compliance-openapi.yml
class_count: 0
classes: []
context_file: json-ld/harbor-compliance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/harbor-compliance/refs/heads/main/json-ld/harbor-compliance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Harbor Compliance from Harbor Compliance.
layout: jsonld
name: Harbor Compliance Context
namespaces:
- prefix: hc
  uri: https://api.harborcompliance.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: legal
  uri: http://www.w3.org/ns/legal#
properties:
- container: ''
  name: Entity
  type: ''
- container: ''
  name: License
  type: ''
- container: ''
  name: RegisteredAgent
  type: ''
- container: ''
  name: Filing
  type: ''
- container: ''
  name: ServiceOrder
  type: ''
property_count: 5
provider_name: Harbor Compliance
provider_slug: harbor-compliance
slug: harbor-compliance-context
source_filename: harbor-compliance-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hc\": \"https://api.harborcompliance.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"legal\": \"http://www.w3.org/ns/legal#\",\n\n    \"Entity\": {\n      \"@id\": \"hc:Entity\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:legalName\",\n        \"entity_type\": \"hc:entityType\",\n        \"state_of_formation\": \"hc:stateOfFormation\",\n        \"ein\": \"hc:ein\",\n        \"status\": \"hc:complianceStatus\",\n        \"registered_agent\": {\n          \"@id\": \"hc:hasRegisteredAgent\",\n          \"@type\": \"@id\"\n        },\n        \"licenses\": {\n          \"@id\": \"hc:hasLicense\",\n          \"@container\": \"@set\"\n        },\n        \"filings\": {\n          \"@id\": \"hc:hasFiling\",\n          \"@container\": \"@set\"\n        },\n        \"foreign_qualifications\"\
  : {\n          \"@id\": \"hc:foreignQualification\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"License\": {\n      \"@id\": \"hc:License\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"license_type\": \"hc:licenseType\",\n        \"jurisdiction\": \"hc:jurisdiction\",\n        \"license_number\": \"hc:licenseNumber\",\n        \"status\": \"hc:licenseStatus\",\n        \"issued_date\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:date\"\n        },\n        \"expiration_date\": {\n          \"@id\": \"hc:expirationDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"renewal_date\": {\n          \"@id\": \"hc:renewalDate\",\n          \"@type\": \"xsd:date\"\n        },\n\
  \        \"fee\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"RegisteredAgent\": {\n      \"@id\": \"hc:RegisteredAgent\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"agent_name\": \"schema:name\",\n        \"address\": \"schema:address\",\n        \"jurisdiction\": \"hc:jurisdiction\",\n        \"status\": \"hc:serviceStatus\",\n        \"service_start\": {\n          \"@id\": \"hc:serviceStart\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Filing\": {\n      \"@id\": \"hc:Filing\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"filing_type\": \"hc:filingType\",\n        \"jurisdiction\": \"hc:jurisdiction\",\n        \"due_date\": {\n          \"@id\": \"hc:dueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"hc:filingStatus\",\n        \"filed_date\": {\n          \"@id\": \"hc:filedDate\",\n          \"@type\": \"xsd:date\"\n  \
  \      },\n        \"fee\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"ServiceOrder\": {\n      \"@id\": \"hc:ServiceOrder\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"service_type\": \"hc:serviceType\",\n        \"jurisdiction\": \"hc:jurisdiction\",\n        \"status\": \"hc:orderStatus\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completed_at\": {\n          \"@id\": \"hc:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"estimated_completion\": {\n          \"@id\": \"hc:estimatedCompletion\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/harbor-compliance/refs/heads/main/json-ld/harbor-compliance-context.jsonld
tags:
- Business Licensing
- Compliance
- Legal
- Regulatory
- JSON-LD
- Linked Data
- Semantic Web
---
