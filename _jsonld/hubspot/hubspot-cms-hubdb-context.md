---
class_count: 0
classes: []
context_file: json-ld/hubspot-cms-hubdb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-cms-hubdb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Cms Hubdb from HubSpot.
layout: jsonld
name: Hubspot Cms Hubdb Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: HubDBTable
  type: ''
- container: ''
  name: HubDBColumn
  type: ''
- container: ''
  name: HubDBTableCreateRequest
  type: ''
- container: ''
  name: HubDBRow
  type: ''
- container: ''
  name: HubDBRowCreateRequest
  type: ''
- container: ''
  name: CollectionResponseHubDBTable
  type: ''
- container: ''
  name: CollectionResponseHubDBRow
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 9
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-cms-hubdb-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"HubDBTable\": {\n      \"@id\": \"ns:HubDBTable\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"columns\": \"ns:columns\",\n        \"published\": {\n          \"@id\": \"ns:published\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"rowCount\": {\n          \"@id\": \"ns:rowCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"ns:publishedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"HubDBColumn\": {\n      \"@id\": \"ns:HubDBColumn\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"options\": \"ns:options\"\n      }\n    },\n    \"HubDBTableCreateRequest\": {\n      \"@id\": \"ns:HubDBTableCreateRequest\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"columns\": \"ns:columns\"\n      }\n    },\n    \"HubDBRow\": {\n      \"@id\": \"ns:HubDBRow\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"values\": \"ns:values\",\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"HubDBRowCreateRequest\": {\n      \"@id\": \"ns:HubDBRowCreateRequest\",\n      \"@context\": {\n        \"values\": \"ns:values\"\n      }\n    },\n    \"CollectionResponseHubDBTable\": {\n      \"@id\": \"ns:CollectionResponseHubDBTable\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CollectionResponseHubDBRow\"\
  : {\n      \"@id\": \"ns:CollectionResponseHubDBRow\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": \"ns:next\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-cms-hubdb-context.jsonld
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
