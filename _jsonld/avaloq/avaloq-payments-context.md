---
api_specs:
- filename: avaloq-banking-openapi.yml
  format: yaml
  label: Avaloq Banking API
  slug: avaloq-banking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/openapi/avaloq-banking-openapi.yml
- filename: avaloq-wealth-management-openapi.yml
  format: yaml
  label: Avaloq Wealth Management API
  slug: avaloq-wealth-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/openapi/avaloq-wealth-management-openapi.yml
- filename: avaloq-payments-openapi.yml
  format: yaml
  label: Avaloq Payments API
  slug: avaloq-payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/openapi/avaloq-payments-openapi.yml
- filename: avaloq-client-management-openapi.yml
  format: yaml
  label: Avaloq Client Management API
  slug: avaloq-client-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/openapi/avaloq-client-management-openapi.yml
- filename: avaloq-trading-openapi.yml
  format: yaml
  label: Avaloq Trading API
  slug: avaloq-trading-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/openapi/avaloq-trading-openapi.yml
- filename: avaloq-compliance-openapi.yml
  format: yaml
  label: Avaloq Compliance & Risk API
  slug: avaloq-compliance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/openapi/avaloq-compliance-openapi.yml
class_count: 0
classes: []
context_file: json-ld/avaloq-payments-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/json-ld/avaloq-payments-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Avaloq Payments from Avaloq.
layout: jsonld
name: Avaloq Payments Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: http://schema.org/
properties:
- container: ''
  name: amount
  type: ''
- container: ''
  name: currency
  type: ''
- container: ''
  name: executionDate
  type: http://www.w3.org/2001/XMLSchema#date
- container: ''
  name: id
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: valueDate
  type: http://www.w3.org/2001/XMLSchema#date
- container: ''
  name: total
  type: http://www.w3.org/2001/XMLSchema#integer
- container: ''
  name: offset
  type: http://www.w3.org/2001/XMLSchema#integer
property_count: 8
provider_name: Avaloq
provider_slug: avaloq
slug: avaloq-payments-context
source_filename: avaloq-payments-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://api.avaloq.com/payments#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"http://schema.org/\",\n    \"amount\": {\n      \"@id\": \"http://schema.org/price\"\n    },\n    \"currency\": {\n      \"@id\": \"http://schema.org/priceCurrency\"\n    },\n    \"executionDate\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#date\"\n    },\n    \"id\": {\n      \"@id\": \"http://schema.org/identifier\"\n    },\n    \"status\": {\n      \"@id\": \"http://schema.org/status\"\n    },\n    \"valueDate\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#date\"\n    },\n    \"total\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n    },\n    \"offset\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/json-ld/avaloq-payments-context.jsonld
tags:
- Banking
- Digital Banking
- Financial Services
- Fintech
- Payments
- Wealth Management
- JSON-LD
- Linked Data
- Semantic Web
---
