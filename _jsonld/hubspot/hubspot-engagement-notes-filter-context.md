---
class_count: 2
classes:
- FilterGroup
- Filter
context_file: json-ld/hubspot-engagement-notes-filter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-filter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Engagement Notes Filter from HubSpot.
layout: jsonld
name: Hubspot Engagement Notes Filter Context
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
- container: set
  name: filters
  type: reference
- container: ''
  name: propertyName
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: highValue
  type: string
property_count: 6
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-engagement-notes-filter-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FilterGroup\": \"hubspot:FilterGroup\",\n    \"filters\": {\n      \"@id\": \"hubspot:filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Filter\": \"hubspot:Filter\",\n    \"propertyName\": {\n      \"@id\": \"hubspot:propertyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"hubspot:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"hubspot:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"hubspot:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"highValue\": {\n      \"@id\": \"hubspot:highValue\",\n      \"@type\": \"xsd:string\"\n  \
  \  }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-filter-context.jsonld
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
