---
class_count: 19
classes:
- Association
- AssociationType
- AssociationDefinition
- AssociationLabel
- CreateAssociationInput
- ObjectReference
- AssociationTypeInput
- BatchAssociationReadInput
- BatchAssociationCreateInput
- BatchAssociationCreateItem
- BatchAssociationArchiveInput
- BatchAssociationArchiveItem
- CreateLabelInput
- AssociationResult
- BatchAssociationResponse
- PagingNext
- Paging
- AssociationDefinitionCollection
- AssociationLabelCollection
context_file: json-ld/hubspot-crm-associations-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-associations-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hubspot Crm Associations Api from HubSpot.
layout: jsonld
name: Hubspot Crm Associations Api Context
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
  name: toObjectId
  type: string
- container: set
  name: associationTypes
  type: reference
- container: ''
  name: associationCategory
  type: string
- container: ''
  name: associationTypeId
  type: integer
- container: ''
  name: label
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: fromObjectTypeId
  type: string
- container: ''
  name: toObjectTypeId
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: inverseLabel
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: typeId
  type: integer
- container: ''
  name: to
  type: reference
- container: set
  name: types
  type: reference
- container: set
  name: inputs
  type: reference
- container: ''
  name: from
  type: reference
- container: ''
  name: paging
  type: reference
- container: ''
  name: status
  type: string
- container: set
  name: results
  type: reference
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
  name: after
  type: string
- container: ''
  name: link
  type: string
- container: ''
  name: next
  type: reference
property_count: 28
provider_name: HubSpot
provider_slug: hubspot
slug: hubspot-crm-associations-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"hubspot\": \"https://developers.hubspot.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Association\": \"hubspot:Association\",\n    \"toObjectId\": {\n      \"@id\": \"hubspot:toObjectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationTypes\": {\n      \"@id\": \"hubspot:associationTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"AssociationType\": \"hubspot:AssociationType\",\n    \"associationCategory\": {\n      \"@id\": \"hubspot:associationCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationTypeId\": {\n      \"@id\": \"hubspot:associationTypeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"label\": {\n      \"@id\": \"hubspot:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociationDefinition\": \"hubspot:AssociationDefinition\"\
  ,\n    \"id\": {\n      \"@id\": \"hubspot:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fromObjectTypeId\": {\n      \"@id\": \"hubspot:fromObjectTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toObjectTypeId\": {\n      \"@id\": \"hubspot:toObjectTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"inverseLabel\": {\n      \"@id\": \"hubspot:inverseLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"hubspot:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociationLabel\": \"hubspot:AssociationLabel\",\n    \"typeId\": {\n      \"@id\": \"hubspot:typeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CreateAssociationInput\": \"hubspot:CreateAssociationInput\",\n    \"to\": {\n      \"@id\": \"hubspot:to\",\n      \"@type\": \"@id\"\n    },\n    \"types\": {\n      \"@id\": \"hubspot:types\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n\
  \    },\n    \"ObjectReference\": \"hubspot:ObjectReference\",\n    \"AssociationTypeInput\": \"hubspot:AssociationTypeInput\",\n    \"BatchAssociationReadInput\": \"hubspot:BatchAssociationReadInput\",\n    \"inputs\": {\n      \"@id\": \"hubspot:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"BatchAssociationCreateInput\": \"hubspot:BatchAssociationCreateInput\",\n    \"BatchAssociationCreateItem\": \"hubspot:BatchAssociationCreateItem\",\n    \"from\": {\n      \"@id\": \"hubspot:from\",\n      \"@type\": \"@id\"\n    },\n    \"BatchAssociationArchiveInput\": \"hubspot:BatchAssociationArchiveInput\",\n    \"BatchAssociationArchiveItem\": \"hubspot:BatchAssociationArchiveItem\",\n    \"CreateLabelInput\": \"hubspot:CreateLabelInput\",\n    \"AssociationResult\": \"hubspot:AssociationResult\",\n    \"paging\": {\n      \"@id\": \"hubspot:paging\",\n      \"@type\": \"@id\"\n    },\n    \"BatchAssociationResponse\": \"hubspot:BatchAssociationResponse\"\
  ,\n    \"status\": {\n      \"@id\": \"hubspot:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"hubspot:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"requestedAt\": {\n      \"@id\": \"hubspot:requestedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"hubspot:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"hubspot:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"numErrors\": {\n      \"@id\": \"hubspot:numErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errors\": {\n      \"@id\": \"hubspot:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"links\": {\n      \"@id\": \"hubspot:links\",\n      \"@type\": \"@id\"\n    },\n    \"PagingNext\": \"hubspot:PagingNext\",\n    \"after\": {\n      \"@id\": \"hubspot:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  link\": {\n      \"@id\": \"hubspot:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Paging\": \"hubspot:Paging\",\n    \"next\": {\n      \"@id\": \"hubspot:next\",\n      \"@type\": \"@id\"\n    },\n    \"AssociationDefinitionCollection\": \"hubspot:AssociationDefinitionCollection\",\n    \"AssociationLabelCollection\": \"hubspot:AssociationLabelCollection\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hubspot/refs/heads/main/json-ld/hubspot-crm-associations-api-context.jsonld
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
