---
class_count: 24
classes:
- CommercePayment
- CommercePaymentInput
- CommercePaymentPatch
- CommercePaymentCollection
- BatchReadRequest
- BatchReadInputItem
- BatchReadResponse
- BatchArchiveRequest
- BatchCreateRequest
- BatchCreateResponse
- BatchUpdateRequest
- BatchUpdateInputItem
- BatchUpdateResponse
- SearchRequest
- SearchResponse
- FilterGroup
- Filter
- SortOption
- AssociationInput
- AssociationType
- AssociationResult
- PropertyHistory
- Paging
- BatchError
context_file: json-ld/hubspot-commerce-payments-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-commerce-payments-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Commerce Payments Api from HubSpot.
layout: jsonld
name: Hubspot Commerce Payments Api Context
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
  name: associations
  type: reference
- container: ''
  name: propertiesWithHistory
  type: reference
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: set
  name: inputs
  type: reference
- container: ''
  name: idProperty
  type: string
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
- container: ''
  name: numErrors
  type: integer
- container: set
  name: errors
  type: reference
- container: ''
  name: links
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
  name: sorts
  type: reference
- container: set
  name: filterGroups
  type: reference
- container: ''
  name: total
  type: integer
- container: set
  name: filters
  type: reference
- container: ''
  name: propertyName
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: value
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
- container: ''
  name: next
  type: reference
- container: ''
  name: prev
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
- container: ''
  name: subCategory
  type: string
property_count: 47
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-commerce-payments-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CommercePayment\": \"hubspot:CommercePayment\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"hubspot:properties\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"archived\": {\n      \"@id\": \"hubspot:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"archivedAt\": {\n      \"@id\": \"hubspot:archivedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"associations\": {\n      \"@id\": \"hubspot:associations\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"propertiesWithHistory\": {\n      \"@id\": \"hubspot:propertiesWithHistory\",\n      \"@type\": \"@id\"\n    },\n    \"CommercePaymentInput\": \"hubspot:CommercePaymentInput\",\n    \"CommercePaymentPatch\": \"hubspot:CommercePaymentPatch\",\n    \"CommercePaymentCollection\": \"hubspot:CommercePaymentCollection\",\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"BatchReadRequest\": \"hubspot:BatchReadRequest\",\n    \"inputs\": {\n      \"@id\": \"hubspot:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"idProperty\": {\n      \"@id\": \"hubspot:idProperty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchReadInputItem\": \"hubspot:BatchReadInputItem\",\n    \"BatchReadResponse\": \"hubspot:BatchReadResponse\",\n    \"status\": {\n      \"@id\": \"hubspot:status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedAt\": {\n      \"@id\": \"hubspot:requestedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"hubspot:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"numErrors\": {\n      \"@id\": \"hubspot:numErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errors\": {\n      \"@id\": \"hubspot:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"links\": {\n      \"@id\": \"hubspot:links\",\n      \"@type\": \"@id\"\n    },\n    \"BatchArchiveRequest\": \"hubspot:BatchArchiveRequest\",\n    \"BatchCreateRequest\": \"hubspot:BatchCreateRequest\",\n    \"BatchCreateResponse\": \"hubspot:BatchCreateResponse\",\n    \"BatchUpdateRequest\": \"hubspot:BatchUpdateRequest\",\n    \"BatchUpdateInputItem\": \"hubspot:BatchUpdateInputItem\",\n    \"BatchUpdateResponse\"\
  : \"hubspot:BatchUpdateResponse\",\n    \"SearchRequest\": \"hubspot:SearchRequest\",\n    \"query\": {\n      \"@id\": \"hubspot:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"hubspot:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sorts\": {\n      \"@id\": \"hubspot:sorts\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"filterGroups\": {\n      \"@id\": \"hubspot:filterGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"SearchResponse\": \"hubspot:SearchResponse\",\n    \"total\": {\n      \"@id\": \"hubspot:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"FilterGroup\": \"hubspot:FilterGroup\",\n    \"filters\": {\n      \"@id\": \"hubspot:filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Filter\": \"hubspot:Filter\",\n    \"propertyName\"\
  : {\n      \"@id\": \"hubspot:propertyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"hubspot:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"hubspot:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"hubspot:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"highValue\": {\n      \"@id\": \"hubspot:highValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SortOption\": \"hubspot:SortOption\",\n    \"direction\": {\n      \"@id\": \"hubspot:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociationInput\": \"hubspot:AssociationInput\",\n    \"to\": {\n      \"@id\": \"hubspot:to\",\n      \"@type\": \"@id\"\n    },\n    \"types\": {\n      \"@id\": \"hubspot:types\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"AssociationType\": \"hubspot:AssociationType\",\n    \"associationCategory\"\
  : {\n      \"@id\": \"hubspot:associationCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationTypeId\": {\n      \"@id\": \"hubspot:associationTypeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AssociationResult\": \"hubspot:AssociationResult\",\n    \"PropertyHistory\": \"hubspot:PropertyHistory\",\n    \"timestamp\": {\n      \"@id\": \"hubspot:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"sourceType\": {\n      \"@id\": \"hubspot:sourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceId\": {\n      \"@id\": \"hubspot:sourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceLabel\": {\n      \"@id\": \"hubspot:sourceLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedByUserId\": {\n      \"@id\": \"hubspot:updatedByUserId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n    \"prev\": {\n   \
  \   \"@id\": \"hubspot:prev\",\n      \"@type\": \"@id\"\n    },\n    \"BatchError\": \"hubspot:BatchError\",\n    \"category\": {\n      \"@id\": \"hubspot:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"hubspot:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"hubspot:context\",\n      \"@type\": \"@id\"\n    },\n    \"subCategory\": {\n      \"@id\": \"hubspot:subCategory\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-commerce-payments-api-context.jsonld
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
