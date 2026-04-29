---
class_count: 8
classes:
- BatchNotesResponse
- BatchError
- BatchCreateNotesRequest
- BatchReadNotesRequest
- BatchReadInput
- BatchUpdateNotesRequest
- BatchUpdateInput
- BatchArchiveNotesRequest
context_file: json-ld/hubspot-engagement-notes-batch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-batch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Engagement Notes Batch from HubSpot.
layout: jsonld
name: Hubspot Engagement Notes Batch Context
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
  name: status
  type: string
- container: set
  name: results
  type: reference
- container: ''
  name: requestedAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: set
  name: errors
  type: reference
- container: ''
  name: links
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: context
  type: reference
- container: set
  name: inputs
  type: reference
- container: set
  name: properties
  type: string
- container: set
  name: propertiesWithHistory
  type: string
- container: ''
  name: idProperty
  type: string
- container: ''
  name: id
  type: string
property_count: 15
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-engagement-notes-batch-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BatchNotesResponse\": \"hubspot:BatchNotesResponse\",\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"requestedAt\": {\n      \"@id\": \"hubspot:requestedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"hubspot:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errors\": {\n      \"@id\": \"hubspot:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"links\"\
  : {\n      \"@id\": \"hubspot:links\",\n      \"@type\": \"@id\"\n    },\n    \"BatchError\": \"hubspot:BatchError\",\n    \"category\": {\n      \"@id\": \"hubspot:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"hubspot:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"hubspot:context\",\n      \"@type\": \"@id\"\n    },\n    \"BatchCreateNotesRequest\": \"hubspot:BatchCreateNotesRequest\",\n    \"inputs\": {\n      \"@id\": \"hubspot:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchReadNotesRequest\": \"hubspot:BatchReadNotesRequest\",\n    \"properties\": {\n      \"@id\": \"hubspot:properties\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertiesWithHistory\": {\n      \"@id\": \"hubspot:propertiesWithHistory\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idProperty\": {\n      \"@id\"\
  : \"hubspot:idProperty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchReadInput\": \"hubspot:BatchReadInput\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchUpdateNotesRequest\": \"hubspot:BatchUpdateNotesRequest\",\n    \"BatchUpdateInput\": \"hubspot:BatchUpdateInput\",\n    \"BatchArchiveNotesRequest\": \"hubspot:BatchArchiveNotesRequest\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-notes-batch-context.jsonld
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
