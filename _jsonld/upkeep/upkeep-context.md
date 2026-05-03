---
api_specs:
- filename: upkeep-openapi.yml
  format: yaml
  label: UpKeep API
  slug: upkeep
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upkeep/refs/heads/main/openapi/upkeep-openapi.yml
class_count: 5
classes:
- WorkOrder
- Asset
- Location
- Part
- PurchaseOrder
context_file: json-ld/upkeep-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/upkeep/refs/heads/main/json-ld/upkeep-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Upkeep from UpKeep.
layout: jsonld
name: Upkeep Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: upkeep
  uri: https://api.onupkeep.com/api/v2/
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
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: dueDate
  type: date
- container: ''
  name: estimatedHours
  type: decimal
- container: ''
  name: actualHours
  type: decimal
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: name
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: purchaseDate
  type: date
- container: ''
  name: purchaseCost
  type: decimal
- container: ''
  name: address
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: partNumber
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: unitCost
  type: decimal
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: locationId
  type: string
- container: ''
  name: assetId
  type: string
property_count: 24
provider_name: UpKeep
provider_slug: upkeep
slug: upkeep-context
source_filename: upkeep-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"upkeep\": \"https://api.onupkeep.com/api/v2/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"WorkOrder\": \"schema:Order\",\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"title\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"upkeep:status\", \"@type\": \"xsd:string\" },\n    \"priority\": { \"@id\": \"upkeep:priority\", \"@type\": \"xsd:string\" },\n    \"dueDate\": { \"@id\": \"schema:scheduledTime\", \"@type\": \"xsd:date\" },\n    \"estimatedHours\": { \"@id\": \"upkeep:estimatedHours\", \"@type\": \"xsd:decimal\" },\n    \"actualHours\": { \"@id\": \"upkeep:actualHours\", \"@type\": \"xsd:decimal\" },\n    \"completedAt\": { \"@id\": \"schema:endDate\", \"@type\": \"xsd:dateTime\" },\n\n    \"Asset\"\
  : \"schema:Product\",\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"serialNumber\": { \"@id\": \"schema:serialNumber\", \"@type\": \"xsd:string\" },\n    \"model\": { \"@id\": \"schema:model\", \"@type\": \"xsd:string\" },\n    \"manufacturer\": { \"@id\": \"schema:manufacturer\", \"@type\": \"xsd:string\" },\n    \"purchaseDate\": { \"@id\": \"schema:purchaseDate\", \"@type\": \"xsd:date\" },\n    \"purchaseCost\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n\n    \"Location\": \"schema:Place\",\n    \"address\": { \"@id\": \"schema:address\", \"@type\": \"xsd:string\" },\n    \"parentId\": { \"@id\": \"upkeep:parentLocation\", \"@type\": \"xsd:string\" },\n\n    \"Part\": \"schema:Product\",\n    \"partNumber\": { \"@id\": \"schema:productID\", \"@type\": \"xsd:string\" },\n    \"quantity\": { \"@id\": \"schema:inventoryLevel\", \"@type\": \"xsd:integer\" },\n    \"unitCost\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n\
  \n    \"PurchaseOrder\": \"schema:Order\",\n\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updatedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n    \"locationId\": { \"@id\": \"upkeep:locationId\", \"@type\": \"xsd:string\" },\n    \"assetId\": { \"@id\": \"upkeep:assetId\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/upkeep/refs/heads/main/json-ld/upkeep-context.jsonld
tags:
- CMMS
- Maintenance Management
- Asset Management
- Facility Management
- Work Orders
- JSON-LD
- Linked Data
- Semantic Web
---
