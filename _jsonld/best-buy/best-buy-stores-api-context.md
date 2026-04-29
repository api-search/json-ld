---
class_count: 5
classes:
- ErrorResponse
- StoreListResponse
- Store
- StoreService
- name
context_file: json-ld/best-buy-stores-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/json-ld/best-buy-stores-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Best Buy Stores Api from Best Buy.
layout: jsonld
name: Best Buy Stores Api Context
namespaces:
- prefix: bb
  uri: https://developer.bestbuy.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: status
  type: integer
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: from
  type: integer
- container: ''
  name: to
  type: integer
- container: ''
  name: total
  type: integer
- container: ''
  name: currentPage
  type: integer
- container: ''
  name: totalPages
  type: integer
- container: ''
  name: queryTime
  type: string
- container: ''
  name: totalTime
  type: string
- container: set
  name: stores
  type: string
- container: ''
  name: storeId
  type: integer
- container: ''
  name: longName
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: address2
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zipcode
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: lat
  type: double
- container: ''
  name: lng
  type: double
- container: ''
  name: distance
  type: double
- container: ''
  name: storeType
  type: string
- container: ''
  name: hours
  type: string
- container: ''
  name: gmtOffset
  type: integer
- container: set
  name: services
  type: string
- container: ''
  name: service
  type: string
property_count: 27
provider_name: Best Buy
provider_slug: best-buy
slug: best-buy-stores-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bb\": \"https://developer.bestbuy.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorResponse\": \"bb:ErrorResponse\",\n    \"StoreListResponse\": \"bb:StoreListResponse\",\n    \"Store\": \"bb:Store\",\n    \"StoreService\": \"bb:StoreService\",\n    \"status\": {\n      \"@id\": \"bb:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error\": {\n      \"@id\": \"bb:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"bb:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"bb:from\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"to\": {\n      \"@id\": \"bb:to\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"bb:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currentPage\": {\n      \"\
  @id\": \"bb:currentPage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPages\": {\n      \"@id\": \"bb:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"queryTime\": {\n      \"@id\": \"bb:queryTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalTime\": {\n      \"@id\": \"bb:totalTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stores\": {\n      \"@id\": \"bb:stores\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeId\": {\n      \"@id\": \"bb:storeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"longName\": {\n      \"@id\": \"bb:longName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"bb:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address2\": {\n      \"@id\": \"bb:address2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"bb:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n\
  \      \"@id\": \"bb:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zipcode\": {\n      \"@id\": \"bb:zipcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"bb:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lat\": {\n      \"@id\": \"bb:lat\",\n      \"@type\": \"xsd:double\"\n    },\n    \"lng\": {\n      \"@id\": \"bb:lng\",\n      \"@type\": \"xsd:double\"\n    },\n    \"distance\": {\n      \"@id\": \"bb:distance\",\n      \"@type\": \"xsd:double\"\n    },\n    \"storeType\": {\n      \"@id\": \"bb:storeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hours\": {\n      \"@id\": \"bb:hours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gmtOffset\": {\n      \"@id\": \"bb:gmtOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"services\": {\n      \"@id\": \"bb:services\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"bb:service\",\n      \"@type\":\
  \ \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/json-ld/best-buy-stores-api-context.jsonld
tags:
- Retail
- Consumer Electronics
- E-Commerce
- Products
- Stores
- JSON-LD
- Linked Data
- Semantic Web
---
