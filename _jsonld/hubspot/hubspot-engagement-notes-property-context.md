---
class_count: 1
classes:
- PropertyHistory
context_file: json-ld/hubspot-engagement-notes-property-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-property-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Engagement Notes Property from HubSpot.
layout: jsonld
name: Hubspot Engagement Notes Property Context
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
  name: value
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: sourceType
  type: string
- container: ''
  name: sourceId
  type: string
- container: ''
  name: sourceLabel
  type: string
- container: ''
  name: updatedByUserId
  type: integer
property_count: 6
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-engagement-notes-property-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PropertyHistory\": \"hubspot:PropertyHistory\",\n    \"value\": {\n      \"@id\": \"hubspot:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"hubspot:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sourceType\": {\n      \"@id\": \"hubspot:sourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceId\": {\n      \"@id\": \"hubspot:sourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceLabel\": {\n      \"@id\": \"hubspot:sourceLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedByUserId\": {\n      \"@id\": \"hubspot:updatedByUserId\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-property-context.jsonld
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
