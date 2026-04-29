---
class_count: 1
classes:
- SortOption
context_file: json-ld/hubspot-engagement-notes-sort-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-sort-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Engagement Notes Sort from HubSpot.
layout: jsonld
name: Hubspot Engagement Notes Sort Context
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
  name: propertyName
  type: string
- container: ''
  name: direction
  type: string
property_count: 2
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-engagement-notes-sort-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SortOption\": \"hubspot:SortOption\",\n    \"propertyName\": {\n      \"@id\": \"hubspot:propertyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"hubspot:direction\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-sort-context.jsonld
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
