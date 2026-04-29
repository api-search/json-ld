---
class_count: 23
classes:
- Call
- PropertyHistory
- CallCollectionResponse
- CallSearchResponse
- BatchCallsResponse
- BatchError
- CallCreateRequest
- CallUpdateRequest
- BatchCreateCallsRequest
- BatchReadCallsRequest
- BatchReadInput
- BatchUpdateCallsRequest
- BatchUpdateInput
- BatchArchiveCallsRequest
- CallSearchRequest
- FilterGroup
- Filter
- SortOption
- AssociationInput
- AssociationType
- GdprDeleteRequest
- Paging
- NextPage
context_file: json-ld/hubspot-engagement-calls-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-calls-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Engagement Calls Api from HubSpot.
layout: jsonld
name: Hubspot Engagement Calls Api Context
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
  name: properties
  type: reference
- container: ''
  name: propertiesWithHistory
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: archived
  type: boolean
- container: ''
  name: archivedAt
  type: dateTime
- container: ''
  name: value
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: sourceType
  type: string
- container: ''
  name: sourceId
  type: string
- container: ''
  name: sourceLabel
  type: string
- container: ''
  name: updatedByUserId
  type: integer
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: total
  type: integer
- container: ''
  name: status
  type: string
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
  name: associations
  type: reference
- container: set
  name: inputs
  type: reference
- container: ''
  name: idProperty
  type: string
- container: set
  name: filterGroups
  type: reference
- container: set
  name: sorts
  type: reference
- container: ''
  name: query
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: after
  type: string
- container: set
  name: filters
  type: reference
- container: ''
  name: propertyName
  type: string
- container: ''
  name: operator
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: highValue
  type: string
- container: ''
  name: direction
  type: string
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
- container: ''
  name: objectId
  type: string
- container: ''
  name: next
  type: reference
- container: ''
  name: link
  type: string
property_count: 46
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-engagement-calls-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Call\": \"hubspot:Call\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"hubspot:properties\",\n      \"@type\": \"@id\"\n    },\n    \"propertiesWithHistory\": {\n      \"@id\": \"hubspot:propertiesWithHistory\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"archived\": {\n      \"@id\": \"hubspot:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"archivedAt\": {\n      \"@id\": \"hubspot:archivedAt\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"PropertyHistory\": \"hubspot:PropertyHistory\",\n    \"value\": {\n      \"@id\": \"hubspot:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"hubspot:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sourceType\": {\n      \"@id\": \"hubspot:sourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceId\": {\n      \"@id\": \"hubspot:sourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceLabel\": {\n      \"@id\": \"hubspot:sourceLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedByUserId\": {\n      \"@id\": \"hubspot:updatedByUserId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CallCollectionResponse\": \"hubspot:CallCollectionResponse\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"CallSearchResponse\": \"\
  hubspot:CallSearchResponse\",\n    \"total\": {\n      \"@id\": \"hubspot:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"BatchCallsResponse\": \"hubspot:BatchCallsResponse\",\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedAt\": {\n      \"@id\": \"hubspot:requestedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"hubspot:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errors\": {\n      \"@id\": \"hubspot:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"links\": {\n      \"@id\": \"hubspot:links\",\n      \"@type\": \"@id\"\n    },\n    \"BatchError\": \"hubspot:BatchError\",\n    \"category\": {\n      \"@id\": \"hubspot:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"hubspot:message\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"hubspot:context\",\n      \"@type\": \"@id\"\n    },\n    \"CallCreateRequest\": \"hubspot:CallCreateRequest\",\n    \"associations\": {\n      \"@id\": \"hubspot:associations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"CallUpdateRequest\": \"hubspot:CallUpdateRequest\",\n    \"BatchCreateCallsRequest\": \"hubspot:BatchCreateCallsRequest\",\n    \"inputs\": {\n      \"@id\": \"hubspot:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchReadCallsRequest\": \"hubspot:BatchReadCallsRequest\",\n    \"idProperty\": {\n      \"@id\": \"hubspot:idProperty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchReadInput\": \"hubspot:BatchReadInput\",\n    \"BatchUpdateCallsRequest\": \"hubspot:BatchUpdateCallsRequest\",\n    \"BatchUpdateInput\": \"hubspot:BatchUpdateInput\",\n    \"BatchArchiveCallsRequest\": \"hubspot:BatchArchiveCallsRequest\"\
  ,\n    \"CallSearchRequest\": \"hubspot:CallSearchRequest\",\n    \"filterGroups\": {\n      \"@id\": \"hubspot:filterGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"sorts\": {\n      \"@id\": \"hubspot:sorts\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"query\": {\n      \"@id\": \"hubspot:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"hubspot:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilterGroup\": \"hubspot:FilterGroup\",\n    \"filters\": {\n      \"@id\": \"hubspot:filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Filter\": \"hubspot:Filter\",\n    \"propertyName\": {\n      \"@id\": \"hubspot:propertyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"hubspot:operator\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"values\": {\n      \"@id\": \"hubspot:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"highValue\": {\n      \"@id\": \"hubspot:highValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SortOption\": \"hubspot:SortOption\",\n    \"direction\": {\n      \"@id\": \"hubspot:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociationInput\": \"hubspot:AssociationInput\",\n    \"to\": {\n      \"@id\": \"hubspot:to\",\n      \"@type\": \"@id\"\n    },\n    \"types\": {\n      \"@id\": \"hubspot:types\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"AssociationType\": \"hubspot:AssociationType\",\n    \"associationCategory\": {\n      \"@id\": \"hubspot:associationCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationTypeId\": {\n      \"@id\": \"hubspot:associationTypeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"GdprDeleteRequest\": \"hubspot:GdprDeleteRequest\",\n\
  \    \"objectId\": {\n      \"@id\": \"hubspot:objectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n    \"NextPage\": \"hubspot:NextPage\",\n    \"link\": {\n      \"@id\": \"hubspot:link\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-engagement-calls-api-context.jsonld
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
