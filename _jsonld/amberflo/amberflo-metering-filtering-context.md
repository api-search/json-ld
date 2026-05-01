---
api_specs:
- filename: amberflo-metering-openapi.yaml
  format: yaml
  label: Amberflo Metering API
  slug: metering-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/openapi/amberflo-metering-openapi.yaml
- filename: amberflo-billing-openapi.yaml
  format: yaml
  label: Amberflo Billing API
  slug: billing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/openapi/amberflo-billing-openapi.yaml
class_count: 1
classes:
- FilteringRule
context_file: json-ld/amberflo-metering-filtering-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-metering-filtering-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amberflo Metering Filtering from Amberflo.
layout: jsonld
name: Amberflo Metering Filtering Context
namespaces:
- prefix: amberflo
  uri: https://amberflo.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: meterApiName
  type: string
- container: ''
  name: ruleId
  type: string
- container: ''
  name: dimensionName
  type: string
- container: set
  name: dimensionValues
  type: string
- container: ''
  name: action
  type: string
property_count: 5
provider_name: Amberflo
provider_slug: amberflo
slug: amberflo-metering-filtering-context
source_filename: amberflo-metering-filtering-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amberflo\": \"https://amberflo.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FilteringRule\": \"amberflo:FilteringRule\",\n    \"meterApiName\": {\n      \"@id\": \"amberflo:meterApiName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleId\": {\n      \"@id\": \"amberflo:ruleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensionName\": {\n      \"@id\": \"amberflo:dimensionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensionValues\": {\n      \"@id\": \"amberflo:dimensionValues\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"amberflo:action\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-metering-filtering-context.jsonld
tags:
- Usage-Based Billing
- Metering
- FinOps
- AI Cost Management
- Billing
- Monetization
- JSON-LD
- Linked Data
- Semantic Web
---
