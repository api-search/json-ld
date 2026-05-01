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
- Address
context_file: json-ld/amberflo-billing-address-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-billing-address-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amberflo Billing Address from Amberflo.
layout: jsonld
name: Amberflo Billing Address Context
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
  name: verified
  type: boolean
- container: ''
  name: line1
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: country
  type: string
property_count: 6
provider_name: Amberflo
provider_slug: amberflo
slug: amberflo-billing-address-context
source_filename: amberflo-billing-address-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amberflo\": \"https://amberflo.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"amberflo:Address\",\n    \"verified\": {\n      \"@id\": \"amberflo:verified\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"line1\": {\n      \"@id\": \"amberflo:line1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"amberflo:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"amberflo:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"amberflo:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"amberflo:country\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/json-ld/amberflo-billing-address-context.jsonld
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
