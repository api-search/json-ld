---
api_specs:
- filename: marko-api.yml
  format: yaml
  label: Aramark Marko API
  slug: marko-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aramark/refs/heads/main/openapi/marko-api.yml
class_count: 15
classes:
- ErrorResponse
- OrganizationUnit
- OrganizationResponse
- Service
- ServiceResponse
- Product
- ProductResponse
- ProfitCenter
- ProfitCenterResponse
- RevenueSnapshot
- RevenueSnapshotResponse
- POSTransaction
- POSResponse
- id
- name
context_file: json-ld/aramark-marko-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aramark/refs/heads/main/json-ld/aramark-marko-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aramark Marko Api from Aramark.
layout: jsonld
name: Aramark Marko Api Context
namespaces:
- prefix: aramark
  uri: https://marko.aramark.net/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: active
  type: boolean
- container: set
  name: allergens
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: averageTicket
  type: decimal
- container: ''
  name: calories
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: count
  type: integer
- container: set
  name: data
  type: string
- container: ''
  name: items
  type: integer
- container: ''
  name: locationCount
  type: integer
- container: ''
  name: locationId
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: price
  type: decimal
- container: ''
  name: profitCenterId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: totalRevenue
  type: decimal
- container: ''
  name: transactionCount
  type: integer
- container: ''
  name: transactionId
  type: string
- container: ''
  name: type
  type: string
property_count: 24
provider_name: Aramark
provider_slug: aramark
slug: aramark-marko-api-context
source_filename: aramark-marko-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aramark\": \"https://marko.aramark.net/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorResponse\": \"aramark:ErrorResponse\",\n    \"OrganizationUnit\": \"aramark:OrganizationUnit\",\n    \"OrganizationResponse\": \"aramark:OrganizationResponse\",\n    \"Service\": \"aramark:Service\",\n    \"ServiceResponse\": \"aramark:ServiceResponse\",\n    \"Product\": \"aramark:Product\",\n    \"ProductResponse\": \"aramark:ProductResponse\",\n    \"ProfitCenter\": \"aramark:ProfitCenter\",\n    \"ProfitCenterResponse\": \"aramark:ProfitCenterResponse\",\n    \"RevenueSnapshot\": \"aramark:RevenueSnapshot\",\n    \"RevenueSnapshotResponse\": \"aramark:RevenueSnapshotResponse\",\n    \"POSTransaction\": \"aramark:POSTransaction\",\n    \"POSResponse\": \"aramark:POSResponse\",\n    \"active\": {\n      \"@id\": \"aramark:active\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"allergens\": {\n      \"@id\": \"aramark:allergens\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"aramark:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"averageTicket\": {\n      \"@id\": \"aramark:averageTicket\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"calories\": {\n      \"@id\": \"aramark:calories\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"aramark:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"aramark:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"count\": {\n      \"@id\": \"aramark:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"aramark:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": \"dcterms:identifier\",\n    \"items\": {\n      \"@id\": \"aramark:items\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"locationCount\": {\n      \"@id\": \"aramark:locationCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"locationId\": {\n      \"@id\": \"aramark:locationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"aramark:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"parentId\": {\n      \"@id\": \"aramark:parentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"aramark:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"aramark:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"aramark:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"profitCenterId\": {\n      \"@id\": \"aramark:profitCenterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aramark:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\"\
  : {\n      \"@id\": \"aramark:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"totalRevenue\": {\n      \"@id\": \"aramark:totalRevenue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transactionCount\": {\n      \"@id\": \"aramark:transactionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"transactionId\": {\n      \"@id\": \"aramark:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aramark:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aramark/refs/heads/main/json-ld/aramark-marko-api-context.jsonld
tags:
- Food Services
- Facilities Management
- Uniform Services
- Data Platform
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
