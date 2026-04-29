---
class_count: 8
classes:
- HubDBTable
- HubDBColumn
- HubDBTableCreateRequest
- HubDBRow
- HubDBRowCreateRequest
- CollectionResponseHubDBTable
- CollectionResponseHubDBRow
- Paging
context_file: json-ld/hubspot-cms-hubdb-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-cms-hubdb-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Cms Hubdb Api from HubSpot.
layout: jsonld
name: Hubspot Cms Hubdb Api Context
namespaces:
- prefix: hubspot
  uri: https://developers.hubspot.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: label
  type: string
- container: set
  name: columns
  type: reference
- container: ''
  name: published
  type: boolean
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: publishedAt
  type: dateTime
- container: ''
  name: type
  type: string
- container: set
  name: options
  type: reference
- container: ''
  name: values
  type: reference
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: next
  type: reference
property_count: 15
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-cms-hubdb-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"HubDBTable\": \"hubspot:HubDBTable\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"label\": {\n      \"@id\": \"hubspot:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"columns\": {\n      \"@id\": \"hubspot:columns\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"published\": {\n      \"@id\": \"hubspot:published\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rowCount\": {\n      \"@id\": \"hubspot:rowCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n\
  \      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"publishedAt\": {\n      \"@id\": \"hubspot:publishedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"HubDBColumn\": \"hubspot:HubDBColumn\",\n    \"type\": {\n      \"@id\": \"hubspot:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\": \"hubspot:options\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"HubDBTableCreateRequest\": \"hubspot:HubDBTableCreateRequest\",\n    \"HubDBRow\": \"hubspot:HubDBRow\",\n    \"values\": {\n      \"@id\": \"hubspot:values\",\n      \"@type\": \"@id\"\n    },\n    \"HubDBRowCreateRequest\": \"hubspot:HubDBRowCreateRequest\",\n    \"CollectionResponseHubDBTable\": \"hubspot:CollectionResponseHubDBTable\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"\
  @id\"\n    },\n    \"CollectionResponseHubDBRow\": \"hubspot:CollectionResponseHubDBRow\",\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-cms-hubdb-api-context.jsonld
tags:
- Analytics
- Commerce
- Content
- CRM
- Customer Service
- Email Marketing
- Marketing
- Marketing Automation
- Operations
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
