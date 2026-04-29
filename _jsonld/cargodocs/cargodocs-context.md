---
api_specs:
- filename: cargodocs-partner-openapi.yml
  format: yaml
  label: CargoDocs Partner API
  slug: partner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/openapi/cargodocs-partner-openapi.yml
- filename: cargodocs-issuer-openapi.yml
  format: yaml
  label: CargoDocs Issuer API
  slug: issuer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/openapi/cargodocs-issuer-openapi.yml
- filename: cargodocs-customer-openapi.yml
  format: yaml
  label: CargoDocs Customer Data/Docs API
  slug: customer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/openapi/cargodocs-customer-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cargodocs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/json-ld/cargodocs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cargodocs from CargoDocs.
layout: jsonld
name: Cargodocs Context
namespaces:
- prefix: cargodocs
  uri: https://api.cargodocs.com/v3/
properties:
- container: ''
  name: BillOfLading
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Document
  type: ''
- container: ''
  name: Counterparty
  type: ''
- container: ''
  name: Customer
  type: ''
property_count: 5
provider_name: CargoDocs
provider_slug: cargodocs
slug: cargodocs-context
source_filename: cargodocs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cargodocs\": \"https://api.cargodocs.com/v3/\",\n    \"BillOfLading\": {\n      \"@id\": \"cargodocs:BillOfLading\",\n      \"@context\": {\n        \"documentId\": \"cargodocs:documentId\",\n        \"documentType\": \"cargodocs:documentType\",\n        \"transactionId\": \"cargodocs:transactionId\",\n        \"status\": \"cargodocs:status\",\n        \"draftId\": \"cargodocs:draftId\",\n        \"shipperDetails\": \"cargodocs:shipperDetails\",\n        \"consigneeDetails\": \"cargodocs:consigneeDetails\",\n        \"cargoDetails\": \"cargodocs:cargoDetails\",\n        \"issuedAt\": {\n          \"@id\": \"cargodocs:issuedAt\",\n          \"@type\": \"DateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"cargodocs:createdAt\",\n          \"@type\": \"DateTime\"\n        }\n      }\n    },\n    \"Transaction\": {\n      \"@id\": \"cargodocs:Transaction\",\n      \"@context\": {\n        \"\
  transactionId\": \"cargodocs:transactionId\",\n        \"status\": \"cargodocs:status\",\n        \"createdAt\": {\n          \"@id\": \"cargodocs:createdAt\",\n          \"@type\": \"DateTime\"\n        },\n        \"documentCount\": {\n          \"@id\": \"cargodocs:documentCount\",\n          \"@type\": \"Integer\"\n        }\n      }\n    },\n    \"Document\": {\n      \"@id\": \"cargodocs:Document\",\n      \"@context\": {\n        \"documentId\": \"cargodocs:documentId\",\n        \"documentType\": \"cargodocs:documentType\",\n        \"status\": \"cargodocs:status\",\n        \"createdAt\": {\n          \"@id\": \"cargodocs:createdAt\",\n          \"@type\": \"DateTime\"\n        }\n      }\n    },\n    \"Counterparty\": {\n      \"@id\": \"cargodocs:Counterparty\",\n      \"@context\": {\n        \"counterpartyId\": \"cargodocs:counterpartyId\",\n        \"counterpartyName\": \"cargodocs:counterpartyName\"\n      }\n    },\n    \"Customer\": {\n      \"@id\": \"cargodocs:Customer\"\
  ,\n      \"@context\": {\n        \"customerId\": \"cargodocs:customerId\",\n        \"customerName\": \"cargodocs:customerName\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cargodocs/refs/heads/main/json-ld/cargodocs-context.jsonld
tags:
- Bills of Lading
- Documentation
- eBoL
- EssDocs
- MLETR
- Shipping
- Supply Chain
- Trade
- Trade Finance
- Warehouse Warrants
- JSON-LD
- Linked Data
- Semantic Web
---
