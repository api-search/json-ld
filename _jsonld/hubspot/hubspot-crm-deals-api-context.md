---
class_count: 14
classes:
- Deal
- CollectionResponseDeal
- BatchResponseDeal
- SimplePublicObjectInput
- BatchReadInput
- BatchCreateInput
- BatchUpdateInput
- BatchArchiveInput
- SearchRequest
- FilterGroup
- Filter
- Association
- CollectionResponseAssociation
- Paging
context_file: json-ld/hubspot-crm-deals-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-deals-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Deals Api from HubSpot.
layout: jsonld
name: Hubspot Crm Deals Api Context
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
  name: associations
  type: reference
- container: set
  name: results
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: completedAt
  type: dateTime
- container: set
  name: inputs
  type: reference
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
- container: ''
  name: value
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: next
  type: reference
property_count: 22
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-crm-deals-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Deal\": \"hubspot:Deal\",\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"hubspot:properties\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\": \"hubspot:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"hubspot:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"archived\": {\n      \"@id\": \"hubspot:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"associations\": {\n      \"@id\": \"hubspot:associations\",\n      \"@type\": \"@id\"\n    },\n    \"CollectionResponseDeal\": \"hubspot:CollectionResponseDeal\",\n    \"results\": {\n      \"@id\": \"hubspot:results\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"BatchResponseDeal\": \"hubspot:BatchResponseDeal\",\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedAt\": {\n      \"@id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SimplePublicObjectInput\": \"hubspot:SimplePublicObjectInput\",\n    \"BatchReadInput\": \"hubspot:BatchReadInput\",\n    \"inputs\": {\n      \"@id\": \"hubspot:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchCreateInput\": \"hubspot:BatchCreateInput\",\n    \"BatchUpdateInput\": \"hubspot:BatchUpdateInput\",\n    \"BatchArchiveInput\": \"hubspot:BatchArchiveInput\",\n    \"SearchRequest\": \"hubspot:SearchRequest\",\n    \"filterGroups\": {\n      \"@id\": \"hubspot:filterGroups\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"@id\"\n    },\n    \"sorts\": {\n      \"@id\": \"hubspot:sorts\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"query\": {\n      \"@id\": \"hubspot:query\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"hubspot:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilterGroup\": \"hubspot:FilterGroup\",\n    \"filters\": {\n      \"@id\": \"hubspot:filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Filter\": \"hubspot:Filter\",\n    \"propertyName\": {\n      \"@id\": \"hubspot:propertyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"hubspot:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"hubspot:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Association\": \"hubspot:Association\",\n    \"type\":\
  \ {\n      \"@id\": \"hubspot:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CollectionResponseAssociation\": \"hubspot:CollectionResponseAssociation\",\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-deals-api-context.jsonld
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
