---
class_count: 0
classes: []
context_file: json-ld/hubspot-crm-tickets-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-tickets-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Tickets from HubSpot.
layout: jsonld
name: Hubspot Crm Tickets Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Ticket
  type: ''
- container: ''
  name: CollectionResponseTicket
  type: ''
- container: ''
  name: BatchResponseTicket
  type: ''
- container: ''
  name: SimplePublicObjectInput
  type: ''
- container: ''
  name: BatchReadInput
  type: ''
- container: ''
  name: BatchCreateInput
  type: ''
- container: ''
  name: BatchUpdateInput
  type: ''
- container: ''
  name: BatchArchiveInput
  type: ''
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
  name: Association
  type: ''
- container: ''
  name: CollectionResponseAssociation
  type: ''
- container: ''
  name: Paging
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 15
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-crm-tickets-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Ticket\": {\n      \"@id\": \"ns:Ticket\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"archived\": {\n          \"@id\": \"ns:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"associations\": \"ns:associations\"\n      }\n    },\n    \"CollectionResponseTicket\": {\n      \"@id\": \"ns:CollectionResponseTicket\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"\
  xsd:string\"\n        }\n      }\n    },\n    \"BatchResponseTicket\": {\n      \"@id\": \"ns:BatchResponseTicket\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\",\n        \"completedAt\": {\n          \"@id\": \"ns:completedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"SimplePublicObjectInput\": {\n      \"@id\": \"ns:SimplePublicObjectInput\",\n      \"@context\": {\n        \"properties\": \"ns:properties\"\n      }\n    },\n    \"BatchReadInput\": {\n      \"@id\": \"ns:BatchReadInput\",\n      \"@context\": {\n        \"properties\": \"ns:properties\",\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchCreateInput\": {\n      \"@id\": \"ns:BatchCreateInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchUpdateInput\": {\n      \"@id\": \"ns:BatchUpdateInput\",\n      \"@context\"\
  : {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"BatchArchiveInput\": {\n      \"@id\": \"ns:BatchArchiveInput\",\n      \"@context\": {\n        \"inputs\": \"ns:inputs\"\n      }\n    },\n    \"SearchRequest\": {\n      \"@id\": \"ns:SearchRequest\",\n      \"@context\": {\n        \"filterGroups\": \"ns:filterGroups\",\n        \"sorts\": \"ns:sorts\",\n        \"query\": {\n          \"@id\": \"ns:query\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"limit\": {\n          \"@id\": \"ns:limit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"after\": {\n          \"@id\": \"ns:after\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"FilterGroup\": {\n      \"@id\": \"ns:FilterGroup\",\n      \"@context\": {\n        \"filters\": \"ns:filters\"\n      }\n    },\n    \"Filter\": {\n      \"@id\": \"ns:Filter\",\n      \"@context\": {\n        \"propertyName\": {\n          \"\
  @id\": \"ns:propertyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operator\": {\n          \"@id\": \"ns:operator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Association\": {\n      \"@id\": \"ns:Association\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CollectionResponseAssociation\": {\n      \"@id\": \"ns:CollectionResponseAssociation\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": \"ns:next\"\n    \
  \  }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-tickets-context.jsonld
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
