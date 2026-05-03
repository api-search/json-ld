---
api_specs:
- filename: opencost-openapi.yml
  format: yaml
  label: OpenCost API
  slug: opencost-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/openapi/opencost-openapi.yml
class_count: 0
classes: []
context_file: json-ld/opencost-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/json-ld/opencost-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Opencost from OpenCost.
layout: jsonld
name: Opencost Context
namespaces:
- prefix: opencost
  uri: https://www.opencost.io/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Allocation
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: CloudCost
  type: ''
property_count: 3
provider_name: OpenCost
provider_slug: opencost
slug: opencost-context
source_filename: opencost-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"opencost\": \"https://www.opencost.io/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Allocation\": {\n      \"@id\": \"opencost:Allocation\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"cpuCost\": {\"@id\": \"opencost:cpuCost\", \"@type\": \"xsd:decimal\"},\n        \"ramCost\": {\"@id\": \"opencost:ramCost\", \"@type\": \"xsd:decimal\"},\n        \"pvCost\": {\"@id\": \"opencost:pvCost\", \"@type\": \"xsd:decimal\"},\n        \"networkCost\": {\"@id\": \"opencost:networkCost\", \"@type\": \"xsd:decimal\"},\n        \"sharedCost\": {\"@id\": \"opencost:sharedCost\", \"@type\": \"xsd:decimal\"},\n        \"externalCost\": {\"@id\": \"opencost:externalCost\", \"@type\": \"xsd:decimal\"},\n        \"totalCost\": {\"@id\": \"opencost:totalCost\", \"@type\": \"xsd:decimal\"},\n        \"\
  minutes\": {\"@id\": \"opencost:minutes\", \"@type\": \"xsd:decimal\"}\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"opencost:Asset\",\n      \"@context\": {\n        \"type\": \"opencost:assetType\",\n        \"totalCost\": {\"@id\": \"opencost:totalCost\", \"@type\": \"xsd:decimal\"},\n        \"cpuCost\": {\"@id\": \"opencost:cpuCost\", \"@type\": \"xsd:decimal\"},\n        \"ramCost\": {\"@id\": \"opencost:ramCost\", \"@type\": \"xsd:decimal\"},\n        \"providerID\": \"opencost:providerID\"\n      }\n    },\n\n    \"CloudCost\": {\n      \"@id\": \"opencost:CloudCost\",\n      \"@context\": {\n        \"netCost\": {\"@id\": \"opencost:netCost\", \"@type\": \"xsd:decimal\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/json-ld/opencost-context.jsonld
tags:
- Cloud Cost Management
- CNCF
- FinOps
- Kubernetes
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
