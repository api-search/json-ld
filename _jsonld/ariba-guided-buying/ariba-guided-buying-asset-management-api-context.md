---
class_count: 8
classes:
- Requisition
- BatchAssetUpdateRequest
- AssetLineItemUpdate
- CountResponse
- AssetLineItem
- description
- RequisitionsResponse
- BatchUpdateResponse
context_file: json-ld/ariba-guided-buying-asset-management-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/json-ld/ariba-guided-buying-asset-management-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ariba Guided Buying Asset Management Api from Ariba Guided Buying.
layout: jsonld
name: Ariba Guided Buying Asset Management Api Context
namespaces:
- prefix: ariba
  uri: https://openapi.ariba.com/schema/
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
  name: title
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: updatedDate
  type: dateTime
- container: set
  name: lineItems
  type: string
- container: set
  name: updates
  type: string
- container: ''
  name: requisitionId
  type: string
- container: ''
  name: lineItemId
  type: string
- container: ''
  name: assetNumber
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: assetCategory
  type: string
- container: ''
  name: quantity
  type: integer
- container: set
  name: requisitions
  type: string
- container: ''
  name: processed
  type: integer
- container: ''
  name: succeeded
  type: integer
- container: ''
  name: failed
  type: integer
property_count: 17
provider_name: Ariba Guided Buying
provider_slug: ariba-guided-buying
slug: ariba-guided-buying-asset-management-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ariba\": \"https://openapi.ariba.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Requisition\": \"ariba:Requisition\",\n    \"id\": {\n      \"@id\": \"ariba:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"ariba:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"ariba:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdDate\": {\n      \"@id\": \"ariba:createdDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedDate\": {\n      \"@id\": \"ariba:updatedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lineItems\": {\n      \"@id\": \"ariba:lineItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchAssetUpdateRequest\": \"ariba:BatchAssetUpdateRequest\",\n    \"updates\"\
  : {\n      \"@id\": \"ariba:updates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssetLineItemUpdate\": \"ariba:AssetLineItemUpdate\",\n    \"requisitionId\": {\n      \"@id\": \"ariba:requisitionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineItemId\": {\n      \"@id\": \"ariba:lineItemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetNumber\": {\n      \"@id\": \"ariba:assetNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CountResponse\": \"ariba:CountResponse\",\n    \"count\": {\n      \"@id\": \"ariba:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AssetLineItem\": \"ariba:AssetLineItem\",\n    \"description\": \"schema:description\",\n    \"assetCategory\": {\n      \"@id\": \"ariba:assetCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"ariba:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"RequisitionsResponse\": \"ariba:RequisitionsResponse\",\n   \
  \ \"requisitions\": {\n      \"@id\": \"ariba:requisitions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchUpdateResponse\": \"ariba:BatchUpdateResponse\",\n    \"processed\": {\n      \"@id\": \"ariba:processed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"succeeded\": {\n      \"@id\": \"ariba:succeeded\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failed\": {\n      \"@id\": \"ariba:failed\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/json-ld/ariba-guided-buying-asset-management-api-context.jsonld
tags:
- B2B
- Catalog
- ERP
- Procurement
- Requisitions
- SAP
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
