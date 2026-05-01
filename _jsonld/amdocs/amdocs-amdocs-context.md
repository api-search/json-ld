---
api_specs:
- filename: amdocs-connectx-openapi.yml
  format: yaml
  label: Amdocs connectX BSS API
  slug: amdocs-connectx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/openapi/amdocs-connectx-openapi.yml
class_count: 4
classes:
- Amdocs Customer
- email
- createdAt
- updatedAt
context_file: json-ld/amdocs-amdocs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-ld/amdocs-amdocs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amdocs Amdocs from Amdocs.
layout: jsonld
name: Amdocs Amdocs Context
namespaces:
- prefix: amdocs
  uri: https://amdocs.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: customerId
  type: string
- container: ''
  name: customerType
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: companyName
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: billingAddress
  type: string
- container: set
  name: subscriptions
  type: string
property_count: 11
provider_name: Amdocs
provider_slug: amdocs
slug: amdocs-amdocs-context
source_filename: amdocs-amdocs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amdocs\": \"https://amdocs.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Amdocs Customer\": \"amdocs:Amdocs Customer\",\n    \"customerId\": {\n      \"@id\": \"amdocs:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerType\": {\n      \"@id\": \"amdocs:customerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amdocs:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"amdocs:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"amdocs:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"amdocs:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"companyName\": {\n      \"@id\": \"amdocs:companyName\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"amdocs:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"amdocs:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"amdocs:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptions\": {\n      \"@id\": \"amdocs:subscriptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-ld/amdocs-amdocs-context.jsonld
tags:
- Telecom
- BSS
- OSS
- Billing
- Customer Management
- MVNO
- 5G
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
