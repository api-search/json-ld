---
class_count: 0
classes: []
context_file: json-ld/hubspot-crm-search-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-search-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Search from HubSpot.
layout: jsonld
name: Hubspot Crm Search Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: SearchRequest
  type: ''
- container: ''
  name: FilterGroup
  type: ''
- container: ''
  name: Filter
  type: ''
- container: ''
  name: Sort
  type: ''
- container: ''
  name: CRMObject
  type: ''
- container: ''
  name: SearchResponse
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 8
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-crm-search-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"SearchRequest\": {\n      \"@id\": \"ns:SearchRequest\",\n      \"@context\": {\n        \"filterGroups\": \"ns:filterGroups\",\n        \"sorts\": \"ns:sorts\",\n        \"query\": {\n          \"@id\": \"ns:query\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"limit\": {\n          \"@id\": \"ns:limit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"FilterGroup\": {\n      \"@id\": \"ns:FilterGroup\",\n      \"@context\": {\n        \"filters\": \"ns:filters\"\n      }\n    },\n    \"Filter\": {\n      \"@id\": \"ns:Filter\",\n      \"@context\": {\n        \"propertyName\": {\n          \"@id\": \"ns:propertyName\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"operator\": {\n          \"@id\": \"ns:operator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"highValue\": {\n          \"@id\": \"ns:highValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"values\": \"ns:values\"\n      }\n    },\n    \"Sort\": {\n      \"@id\": \"ns:Sort\",\n      \"@context\": {\n        \"propertyName\": {\n          \"@id\": \"ns:propertyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"direction\": {\n          \"@id\": \"ns:direction\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CRMObject\": {\n      \"@id\": \"ns:CRMObject\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"archived\": {\n          \"@id\": \"ns:archived\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"SearchResponse\": {\n      \"@id\": \"ns:SearchResponse\",\n      \"@context\": {\n        \"total\": {\n          \"@id\": \"ns:total\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": \"ns:next\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"errors\": \"ns:errors\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-search-context.jsonld
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
