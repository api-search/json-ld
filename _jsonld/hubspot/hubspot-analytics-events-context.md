---
class_count: 0
classes: []
context_file: json-ld/hubspot-analytics-events-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-analytics-events-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Analytics Events from HubSpot.
layout: jsonld
name: Hubspot Analytics Events Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: EventInstance
  type: ''
- container: ''
  name: EventInstanceCollection
  type: ''
- container: ''
  name: EventTypeCollection
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: PagingNext
  type: ''
- container: ''
  name: PagingPrevious
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ErrorDetail
  type: ''
property_count: 8
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-analytics-events-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"EventInstance\": {\n      \"@id\": \"ns:EventInstance\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"eventType\": {\n          \"@id\": \"ns:eventType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"objectId\": {\n          \"@id\": \"ns:objectId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"objectType\": {\n          \"@id\": \"ns:objectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"occurredAt\": {\n          \"@id\": \"ns:occurredAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\"\n      }\n    },\n    \"EventInstanceCollection\": {\n      \"@id\": \"ns:EventInstanceCollection\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n \
  \       \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"EventTypeCollection\": {\n      \"@id\": \"ns:EventTypeCollection\",\n      \"@context\": {\n        \"eventTypes\": \"ns:eventTypes\"\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": {\n          \"@id\": \"ns:next\",\n          \"@type\": \"xsd:string\"\n        },\n        \"prev\": {\n          \"@id\": \"ns:prev\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PagingNext\": {\n      \"@id\": \"ns:PagingNext\",\n      \"@context\": {\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"PagingPrevious\": {\n      \"@id\": \"ns:PagingPrevious\",\n      \"@context\": {\n        \"before\": {\n     \
  \     \"@id\": \"ns:before\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"ns:link\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\",\n        \"links\": \"ns:links\",\n        \"errors\": \"ns:errors\"\n      }\n    },\n    \"ErrorDetail\": {\n      \"@id\": \"ns:ErrorDetail\",\n      \"@context\": {\n        \"message\": {\n          \"@id\": \"ns:message\",\n    \
  \      \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subCategory\": {\n          \"@id\": \"ns:subCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"in\": {\n          \"@id\": \"ns:in\",\n          \"@type\": \"xsd:string\"\n        },\n        \"context\": \"ns:context\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-analytics-events-context.jsonld
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
