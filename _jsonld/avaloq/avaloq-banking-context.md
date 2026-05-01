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
context_file: json-ld/avaloq-banking-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/json-ld/avaloq-banking-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Avaloq Banking from Avaloq.
layout: jsonld
name: Avaloq Banking Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: http://schema.org/
properties:
- container: ''
  name: total
  type: http://www.w3.org/2001/XMLSchema#integer
- container: ''
  name: offset
  type: http://www.w3.org/2001/XMLSchema#integer
- container: ''
  name: id
  type: ''
- container: ''
  name: amount
  type: ''
- container: ''
  name: currency
  type: ''
- container: ''
  name: valueDate
  type: http://www.w3.org/2001/XMLSchema#date
- container: ''
  name: bookingDate
  type: http://www.w3.org/2001/XMLSchema#date
- container: ''
  name: description
  type: ''
- container: ''
  name: type
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: email
  type: ''
- container: ''
  name: phone
  type: ''
- container: ''
  name: dateOfBirth
  type: http://www.w3.org/2001/XMLSchema#date
- container: ''
  name: clientSince
  type: http://www.w3.org/2001/XMLSchema#date
- container: ''
  name: balance
  type: http://www.w3.org/2001/XMLSchema#decimal
- container: ''
  name: availableBalance
  type: http://www.w3.org/2001/XMLSchema#decimal
- container: ''
  name: openedDate
  type: http://www.w3.org/2001/XMLSchema#date
property_count: 17
provider_name: Avaloq
provider_slug: avaloq
slug: avaloq-banking-context
source_filename: avaloq-banking-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://api.avaloq.com/banking#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"http://schema.org/\",\n    \"total\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n    },\n    \"offset\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#integer\"\n    },\n    \"id\": {\n      \"@id\": \"http://schema.org/identifier\"\n    },\n    \"amount\": {\n      \"@id\": \"http://schema.org/price\"\n    },\n    \"currency\": {\n      \"@id\": \"http://schema.org/priceCurrency\"\n    },\n    \"valueDate\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#date\"\n    },\n    \"bookingDate\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#date\"\n    },\n    \"description\": {\n      \"@id\": \"http://schema.org/description\"\n    },\n    \"type\": {\n      \"@id\": \"http://schema.org/additionalType\"\n    },\n    \"status\": {\n      \"@id\": \"http://schema.org/status\"\n    },\n\
  \    \"email\": {\n      \"@id\": \"http://schema.org/email\"\n    },\n    \"phone\": {\n      \"@id\": \"http://schema.org/telephone\"\n    },\n    \"dateOfBirth\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#date\"\n    },\n    \"clientSince\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#date\"\n    },\n    \"balance\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#decimal\"\n    },\n    \"availableBalance\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#decimal\"\n    },\n    \"openedDate\": {\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#date\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/json-ld/avaloq-banking-context.jsonld
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
