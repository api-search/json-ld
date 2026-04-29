---
class_count: 5
classes:
- Page
- CollectionResponsePage
- PageCreateRequest
- PageUpdateRequest
- Paging
context_file: json-ld/hubspot-cms-pages-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-cms-pages-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Cms Pages Api from HubSpot.
layout: jsonld
name: Hubspot Cms Pages Api Context
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
  name: htmlTitle
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: currentState
  type: string
- container: ''
  name: contentTypeCategory
  type: integer
- container: ''
  name: publishDate
  type: dateTime
- container: ''
  name: metaDescription
  type: string
- container: ''
  name: url
  type: ''
- container: ''
  name: domain
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: templatePath
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: archived
  type: boolean
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: layoutSections
  type: reference
- container: ''
  name: next
  type: reference
property_count: 20
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-cms-pages-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Page\": \"hubspot:Page\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"htmlTitle\": {\n      \"@id\": \"hubspot:htmlTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"hubspot:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"hubspot:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentState\": {\n      \"@id\": \"hubspot:currentState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentTypeCategory\": {\n      \"@id\": \"hubspot:contentTypeCategory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publishDate\": {\n      \"@id\":\
  \ \"hubspot:publishDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"metaDescription\": {\n      \"@id\": \"hubspot:metaDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\"\n    },\n    \"domain\": {\n      \"@id\": \"hubspot:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"hubspot:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templatePath\": {\n      \"@id\": \"hubspot:templatePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"archived\": {\n      \"@id\": \"hubspot:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CollectionResponsePage\": \"hubspot:CollectionResponsePage\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"PageCreateRequest\": \"hubspot:PageCreateRequest\",\n    \"layoutSections\": {\n      \"@id\": \"hubspot:layoutSections\",\n      \"@type\": \"@id\"\n    },\n    \"PageUpdateRequest\": \"hubspot:PageUpdateRequest\",\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-cms-pages-api-context.jsonld
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
