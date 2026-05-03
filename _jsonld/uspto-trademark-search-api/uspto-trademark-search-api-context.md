---
api_specs:
- filename: uspto-trademark-search-api-openapi.yml
  format: yaml
  label: USPTO Trademark Search API Endpoints
  slug: uspto-trademark-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uspto-trademark-search-api/refs/heads/main/openapi/uspto-trademark-search-api-openapi.yml
class_count: 13
classes:
- TrademarkApplication
- TrademarkOwner
- ProsecutionEvent
- GoodsAndServicesClass
- Registered
- Pending
- Abandoned
- Expired
- STANDARD_CHARACTER
- DESIGN
- SOUND
- COLOR
- THREE_DIMENSIONAL
context_file: json-ld/uspto-trademark-search-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uspto-trademark-search-api/refs/heads/main/json-ld/uspto-trademark-search-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uspto Trademark Search Api from USPTO Trademark Search API.
layout: jsonld
name: Uspto Trademark Search Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tm
  uri: https://api-evangelist.github.io/uspto-trademark-search-api/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Trademark
  type: schema:CreativeWork
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: registrationNumber
  type: string
- container: ''
  name: wordMark
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusCode
  type: string
- container: ''
  name: filingDate
  type: date
- container: ''
  name: registrationDate
  type: date
- container: ''
  name: ownerName
  type: ''
- container: ''
  name: ownerAddress
  type: ''
- container: ''
  name: ownerCity
  type: ''
- container: ''
  name: ownerState
  type: ''
- container: ''
  name: ownerCountry
  type: ''
- container: ''
  name: ownerPostalCode
  type: ''
- container: ''
  name: goodsAndServices
  type: string
- container: list
  name: internationalClasses
  type: ''
- container: ''
  name: markType
  type: string
- container: ''
  name: firstUsedDate
  type: date
- container: ''
  name: firstUsedInCommerceDate
  type: date
- container: list
  name: prosecutionHistory
  type: ''
- container: ''
  name: correspondentName
  type: ''
- container: ''
  name: available
  type: boolean
- container: list
  name: conflictingMarks
  type: ''
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: recordCount
  type: integer
property_count: 25
provider_name: USPTO Trademark Search API
provider_slug: uspto-trademark-search-api
slug: uspto-trademark-search-api-context
source_filename: uspto-trademark-search-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tm\": \"https://api-evangelist.github.io/uspto-trademark-search-api/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Trademark\": {\n      \"@id\": \"tm:Trademark\",\n      \"@type\": \"schema:CreativeWork\"\n    },\n    \"TrademarkApplication\": \"tm:TrademarkApplication\",\n    \"TrademarkOwner\": \"tm:TrademarkOwner\",\n    \"ProsecutionEvent\": \"tm:ProsecutionEvent\",\n    \"GoodsAndServicesClass\": \"tm:GoodsAndServicesClass\",\n\n    \"serialNumber\": {\n      \"@id\": \"tm:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationNumber\": {\n      \"@id\": \"tm:registrationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wordMark\": {\n      \"@id\": \"tm:wordMark\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n\
  \      \"@id\": \"tm:statusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filingDate\": {\n      \"@id\": \"tm:filingDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"registrationDate\": {\n      \"@id\": \"tm:registrationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"ownerName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"ownerAddress\": {\n      \"@id\": \"schema:address\"\n    },\n    \"ownerCity\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"ownerState\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"ownerCountry\": {\n      \"@id\": \"schema:addressCountry\"\n    },\n    \"ownerPostalCode\": {\n      \"@id\": \"schema:postalCode\"\n    },\n    \"goodsAndServices\": {\n      \"@id\": \"tm:goodsAndServices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internationalClasses\": {\n      \"@id\": \"tm:internationalClasses\",\n      \"@container\": \"@list\"\n    },\n    \"markType\": {\n      \"@id\": \"tm:markType\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"firstUsedDate\": {\n      \"@id\": \"tm:firstUsedDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"firstUsedInCommerceDate\": {\n      \"@id\": \"tm:firstUsedInCommerceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"prosecutionHistory\": {\n      \"@id\": \"tm:prosecutionHistory\",\n      \"@container\": \"@list\"\n    },\n    \"correspondentName\": {\n      \"@id\": \"tm:correspondentName\"\n    },\n    \"available\": {\n      \"@id\": \"tm:available\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"conflictingMarks\": {\n      \"@id\": \"tm:conflictingMarks\",\n      \"@container\": \"@list\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"recordCount\": {\n      \"@id\": \"tm:recordCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Registered\": \"tm:Registered\",\n    \"Pending\": \"tm:Pending\",\n    \"Abandoned\": \"tm:Abandoned\",\n    \"Expired\"\
  : \"tm:Expired\",\n\n    \"STANDARD_CHARACTER\": \"tm:StandardCharacterMark\",\n    \"DESIGN\": \"tm:DesignMark\",\n    \"SOUND\": \"tm:SoundMark\",\n    \"COLOR\": \"tm:ColorMark\",\n    \"THREE_DIMENSIONAL\": \"tm:ThreeDimensionalMark\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uspto-trademark-search-api/refs/heads/main/json-ld/uspto-trademark-search-api-context.jsonld
tags:
- Brand
- Brand Protection
- Business
- Data
- Government Data
- Intellectual Property
- Legal
- Search
- Trademark
- USPTO
- JSON-LD
- Linked Data
- Semantic Web
---
