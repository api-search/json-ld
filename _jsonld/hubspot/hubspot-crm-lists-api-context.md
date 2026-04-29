---
class_count: 8
classes:
- List
- CollectionResponseList
- ListCreateRequest
- Membership
- CollectionResponseMembership
- MembershipChangeRequest
- MembershipChangeResponse
- Paging
context_file: json-ld/hubspot-crm-lists-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-lists-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Lists Api from HubSpot.
layout: jsonld
name: Hubspot Crm Lists Api Context
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
  name: listId
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: listType
  type: string
- container: ''
  name: objectTypeId
  type: string
- container: ''
  name: processingStatus
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: filterBranch
  type: reference
- container: ''
  name: memberCount
  type: integer
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: processingType
  type: string
- container: ''
  name: recordId
  type: string
- container: ''
  name: addedAt
  type: dateTime
- container: set
  name: recordIdsToAdd
  type: string
- container: set
  name: recordIdsToRemove
  type: string
- container: set
  name: recordIdsAdded
  type: string
- container: set
  name: recordIdsAlreadyMember
  type: string
- container: set
  name: recordIdsRemoved
  type: string
- container: set
  name: recordIdsMissing
  type: string
- container: ''
  name: next
  type: reference
property_count: 21
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-crm-lists-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"List\": \"hubspot:List\",\n    \"listId\": {\n      \"@id\": \"hubspot:listId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"listType\": {\n      \"@id\": \"hubspot:listType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectTypeId\": {\n      \"@id\": \"hubspot:objectTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingStatus\": {\n      \"@id\": \"hubspot:processingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"filterBranch\"\
  : {\n      \"@id\": \"hubspot:filterBranch\",\n      \"@type\": \"@id\"\n    },\n    \"memberCount\": {\n      \"@id\": \"hubspot:memberCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CollectionResponseList\": \"hubspot:CollectionResponseList\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"ListCreateRequest\": \"hubspot:ListCreateRequest\",\n    \"processingType\": {\n      \"@id\": \"hubspot:processingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Membership\": \"hubspot:Membership\",\n    \"recordId\": {\n      \"@id\": \"hubspot:recordId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addedAt\": {\n      \"@id\": \"hubspot:addedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CollectionResponseMembership\": \"hubspot:CollectionResponseMembership\",\n    \"MembershipChangeRequest\":\
  \ \"hubspot:MembershipChangeRequest\",\n    \"recordIdsToAdd\": {\n      \"@id\": \"hubspot:recordIdsToAdd\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordIdsToRemove\": {\n      \"@id\": \"hubspot:recordIdsToRemove\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MembershipChangeResponse\": \"hubspot:MembershipChangeResponse\",\n    \"recordIdsAdded\": {\n      \"@id\": \"hubspot:recordIdsAdded\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordIdsAlreadyMember\": {\n      \"@id\": \"hubspot:recordIdsAlreadyMember\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordIdsRemoved\": {\n      \"@id\": \"hubspot:recordIdsRemoved\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordIdsMissing\": {\n      \"@id\": \"hubspot:recordIdsMissing\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-lists-api-context.jsonld
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
