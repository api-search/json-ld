---
class_count: 0
classes: []
context_file: json-ld/hubspot-crm-lists-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-lists-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Lists from HubSpot.
layout: jsonld
name: Hubspot Crm Lists Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: List
  type: ''
- container: ''
  name: CollectionResponseList
  type: ''
- container: ''
  name: ListCreateRequest
  type: ''
- container: ''
  name: Membership
  type: ''
- container: ''
  name: CollectionResponseMembership
  type: ''
- container: ''
  name: MembershipChangeRequest
  type: ''
- container: ''
  name: MembershipChangeResponse
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
slug: hubspot-crm-lists-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"List\": {\n      \"@id\": \"ns:List\",\n      \"@context\": {\n        \"listId\": {\n          \"@id\": \"ns:listId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"listType\": {\n          \"@id\": \"ns:listType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"objectTypeId\": {\n          \"@id\": \"ns:objectTypeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"processingStatus\": {\n          \"@id\": \"ns:processingStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"ns:createdAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"ns:updatedAt\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"filterBranch\": \"ns:filterBranch\",\n        \"memberCount\": {\n          \"@id\": \"ns:memberCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"CollectionResponseList\": {\n      \"@id\": \"ns:CollectionResponseList\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ListCreateRequest\": {\n      \"@id\": \"ns:ListCreateRequest\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"objectTypeId\": {\n          \"@id\": \"ns:objectTypeId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"processingType\": {\n          \"@id\": \"ns:processingType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"filterBranch\": \"ns:filterBranch\"\n      }\n    },\n    \"Membership\": {\n      \"@id\"\
  : \"ns:Membership\",\n      \"@context\": {\n        \"recordId\": {\n          \"@id\": \"ns:recordId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"addedAt\": {\n          \"@id\": \"ns:addedAt\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CollectionResponseMembership\": {\n      \"@id\": \"ns:CollectionResponseMembership\",\n      \"@context\": {\n        \"results\": \"ns:results\",\n        \"paging\": {\n          \"@id\": \"ns:paging\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"MembershipChangeRequest\": {\n      \"@id\": \"ns:MembershipChangeRequest\",\n      \"@context\": {\n        \"recordIdsToAdd\": \"ns:recordIdsToAdd\",\n        \"recordIdsToRemove\": \"ns:recordIdsToRemove\"\n      }\n    },\n    \"MembershipChangeResponse\": {\n      \"@id\": \"ns:MembershipChangeResponse\",\n      \"@context\": {\n        \"recordIdsAdded\": \"ns:recordIdsAdded\",\n        \"recordIdsAlreadyMember\": \"ns:recordIdsAlreadyMember\"\
  ,\n        \"recordIdsRemoved\": \"ns:recordIdsRemoved\",\n        \"recordIdsMissing\": \"ns:recordIdsMissing\"\n      }\n    },\n    \"Paging\": {\n      \"@id\": \"ns:Paging\",\n      \"@context\": {\n        \"next\": \"ns:next\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"correlationId\": {\n          \"@id\": \"ns:correlationId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-lists-context.jsonld
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
