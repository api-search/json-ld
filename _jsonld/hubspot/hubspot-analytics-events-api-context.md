---
class_count: 6
classes:
- EventInstance
- EventInstanceCollection
- EventTypeCollection
- Paging
- PagingNext
- PagingPrevious
context_file: json-ld/hubspot-analytics-events-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-analytics-events-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Analytics Events Api from HubSpot.
layout: jsonld
name: Hubspot Analytics Events Api Context
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
  name: eventType
  type: string
- container: ''
  name: objectId
  type: string
- container: ''
  name: objectType
  type: string
- container: ''
  name: occurredAt
  type: dateTime
- container: ''
  name: properties
  type: reference
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: set
  name: eventTypes
  type: string
- container: ''
  name: next
  type: reference
- container: ''
  name: prev
  type: reference
- container: ''
  name: after
  type: string
- container: ''
  name: link
  type: string
- container: ''
  name: before
  type: string
property_count: 14
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-analytics-events-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EventInstance\": \"hubspot:EventInstance\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"hubspot:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectId\": {\n      \"@id\": \"hubspot:objectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectType\": {\n      \"@id\": \"hubspot:objectType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"occurredAt\": {\n      \"@id\": \"hubspot:occurredAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"properties\": {\n      \"@id\": \"hubspot:properties\",\n      \"@type\": \"@id\"\n    },\n    \"EventInstanceCollection\": \"hubspot:EventInstanceCollection\",\n    \"results\":\
  \ {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"EventTypeCollection\": \"hubspot:EventTypeCollection\",\n    \"eventTypes\": {\n      \"@id\": \"hubspot:eventTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n    \"prev\": {\n      \"@id\": \"hubspot:prev\",\n      \"@type\": \"@id\"\n    },\n    \"PagingNext\": \"hubspot:PagingNext\",\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"hubspot:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PagingPrevious\": \"hubspot:PagingPrevious\",\n    \"before\": {\n      \"@id\": \"hubspot:before\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-analytics-events-api-context.jsonld
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
