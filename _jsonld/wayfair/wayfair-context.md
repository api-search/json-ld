---
api_specs:
- filename: wayfair-supplier-api.yml
  format: yaml
  label: Wayfair Supplier API
  slug: wayfair-supplier-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/openapi/wayfair-supplier-api.yml
class_count: 5
classes:
- GraphQLError
- GraphQLRequest
- GraphQLResponse
- TokenRequest
- TokenResponse
context_file: json-ld/wayfair-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/json-ld/wayfair-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wayfair from Wayfair.
layout: jsonld
name: Wayfair Context
namespaces:
- prefix: wf
  uri: https://developer.wayfair.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: message
  type: string
- container: set
  name: locations
  type: ''
- container: ''
  name: line
  type: integer
- container: ''
  name: column
  type: integer
- container: set
  name: path
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: variables
  type: reference
- container: ''
  name: operationName
  type: string
- container: ''
  name: data
  type: reference
- container: set
  name: errors
  type: ''
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: accessToken
  type: string
- container: ''
  name: tokenType
  type: string
- container: ''
  name: expiresIn
  type: integer
property_count: 15
provider_name: Wayfair
provider_slug: wayfair
slug: wayfair-context
source_filename: wayfair-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wf\": \"https://developer.wayfair.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GraphQLError\": \"wf:GraphQLError\",\n    \"GraphQLRequest\": \"wf:GraphQLRequest\",\n    \"GraphQLResponse\": \"wf:GraphQLResponse\",\n    \"TokenRequest\": \"wf:TokenRequest\",\n    \"TokenResponse\": \"wf:TokenResponse\",\n    \"message\": {\n      \"@id\": \"wf:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"wf:locations\",\n      \"@container\": \"@set\"\n    },\n    \"line\": {\n      \"@id\": \"wf:line\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"column\": {\n      \"@id\": \"wf:column\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"path\": {\n      \"@id\": \"wf:path\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n  \
  \    \"@id\": \"wf:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variables\": {\n      \"@id\": \"wf:variables\",\n      \"@type\": \"@id\"\n    },\n    \"operationName\": {\n      \"@id\": \"wf:operationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"wf:data\",\n      \"@type\": \"@id\"\n    },\n    \"errors\": {\n      \"@id\": \"wf:errors\",\n      \"@container\": \"@set\"\n    },\n    \"clientId\": {\n      \"@id\": \"wf:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"wf:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessToken\": {\n      \"@id\": \"wf:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenType\": {\n      \"@id\": \"wf:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresIn\": {\n      \"@id\": \"wf:expires_in\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wayfair/refs/heads/main/json-ld/wayfair-context.jsonld
tags:
- E-Commerce
- Furniture
- Home Goods
- Retail
- Suppliers
- GraphQL
- JSON-LD
- Linked Data
- Semantic Web
---
