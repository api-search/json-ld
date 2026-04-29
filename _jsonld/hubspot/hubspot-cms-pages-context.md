---
class_count: 0
classes: []
context_file: json-ld/hubspot-cms-pages-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-cms-pages-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Cms Pages from HubSpot.
layout: jsonld
name: Hubspot Cms Pages Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Page
  type: ''
- container: ''
  name: CollectionResponsePage
  type: ''
- container: ''
  name: PageCreateRequest
  type: ''
- container: ''
  name: PageUpdateRequest
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 6
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-cms-pages-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Page\": {\n      \"@id\": \"ns:Page\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"htmlTitle\": {\n          \"@id\": \"ns:htmlTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slug\": {\n          \"@id\": \"ns:slug\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currentState\": {\n          \"@id\": \"ns:currentState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentTypeCategory\": {\n          \"@id\": \"ns:contentTypeCategory\",\n          \"@type\": \"xsd:integer\"\n        },\n \
  \       \"publishDate\": {\n          \"@id\": \"ns:publishDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metaDescription\": {\n          \"@id\": \"ns:metaDescription\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"ns:url\",\n          \"@type\": \"xsd:string\"\n        },\n        \"domain\": {\n          \"@id\": \"ns:domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"ns:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"templatePath\": {\n          \"@id\": \"ns:templatePath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"archived\": {\n          \"@id\": \"ns:archived\",\n          \"@type\": \"xsd:boolean\"\
  \n        }\n      }\n    },\n    \"CollectionResponsePage\": {\n      \"@id\": \"ns:CollectionResponsePage\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PageCreateRequest\": {\n      \"@id\": \"ns:PageCreateRequest\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"htmlTitle\": {\n          \"@id\": \"ns:htmlTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slug\": {\n          \"@id\": \"ns:slug\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metaDescription\": {\n          \"@id\": \"ns:metaDescription\",\n          \"@type\": \"xsd:string\"\n        },\n        \"domain\": {\n          \"@id\": \"ns:domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"ns:language\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"templatePath\": {\n          \"@id\": \"ns:templatePath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"layoutSections\": \"ns:layoutSections\"\n      }\n    },\n    \"PageUpdateRequest\": {\n      \"@id\": \"ns:PageUpdateRequest\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"htmlTitle\": {\n          \"@id\": \"ns:htmlTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slug\": {\n          \"@id\": \"ns:slug\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metaDescription\": {\n          \"@id\": \"ns:metaDescription\",\n          \"@type\": \"xsd:string\"\n        },\n        \"layoutSections\": \"ns:layoutSections\"\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": \"ns:next\"\n      }\n    },\n    \"Error\": {\n      \"@id\":\
  \ \"ns:Error\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-cms-pages-context.jsonld
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
