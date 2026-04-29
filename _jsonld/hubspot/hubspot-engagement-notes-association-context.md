---
class_count: 2
classes:
- AssociationInput
- AssociationType
context_file: json-ld/hubspot-engagement-notes-association-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-association-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Engagement Notes Association from HubSpot.
layout: jsonld
name: Hubspot Engagement Notes Association Context
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
  name: to
  type: reference
- container: set
  name: types
  type: reference
- container: ''
  name: associationCategory
  type: string
- container: ''
  name: associationTypeId
  type: integer
property_count: 4
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-engagement-notes-association-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssociationInput\": \"hubspot:AssociationInput\",\n    \"to\": {\n      \"@id\": \"hubspot:to\",\n      \"@type\": \"@id\"\n    },\n    \"types\": {\n      \"@id\": \"hubspot:types\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"AssociationType\": \"hubspot:AssociationType\",\n    \"associationCategory\": {\n      \"@id\": \"hubspot:associationCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationTypeId\": {\n      \"@id\": \"hubspot:associationTypeId\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-association-context.jsonld
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
