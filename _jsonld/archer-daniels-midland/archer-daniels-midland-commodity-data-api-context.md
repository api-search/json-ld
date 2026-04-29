---
class_count: 7
classes:
- ErrorResponse
- Commodity
- CommodityList
- Product
- ProductList
- Location
- LocationList
context_file: json-ld/archer-daniels-midland-commodity-data-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/json-ld/archer-daniels-midland-commodity-data-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Archer Daniels Midland Commodity Data Api from Archer Daniels Midland.
layout: jsonld
name: Archer Daniels Midland Commodity Data Api Context
namespaces:
- prefix: adm
  uri: https://api.adm.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: currentPrice
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: priceDate
  type: date
- container: ''
  name: commodities
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: category
  type: string
- container: ''
  name: applications
  type: string
- container: ''
  name: protein
  type: decimal
- container: ''
  name: description
  type: string
- container: ''
  name: products
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: locations
  type: string
property_count: 22
provider_name: Archer Daniels Midland
provider_slug: archer-daniels-midland
slug: archer-daniels-midland-commodity-data-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adm\": \"https://api.adm.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorResponse\": \"adm:ErrorResponse\",\n    \"message\": {\n      \"@id\": \"adm:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"adm:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Commodity\": \"adm:Commodity\",\n    \"id\": {\n      \"@id\": \"adm:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"adm:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adm:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentPrice\": {\n      \"@id\": \"adm:currentPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"adm:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"adm:unit\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"priceDate\": {\n      \"@id\": \"adm:priceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"CommodityList\": \"adm:CommodityList\",\n    \"commodities\": {\n      \"@id\": \"adm:commodities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"adm:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Product\": \"adm:Product\",\n    \"category\": {\n      \"@id\": \"adm:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applications\": {\n      \"@id\": \"adm:applications\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protein\": {\n      \"@id\": \"adm:protein\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"description\": {\n      \"@id\": \"adm:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductList\": \"adm:ProductList\",\n    \"products\": {\n      \"@id\": \"adm:products\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Location\": \"adm:Location\",\n    \"country\": {\n      \"@id\": \"adm:country\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"adm:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"adm:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"adm:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"adm:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"LocationList\": \"adm:LocationList\",\n    \"locations\": {\n      \"@id\": \"adm:locations\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/json-ld/archer-daniels-midland-commodity-data-api-context.jsonld
tags:
- Agriculture
- Food Processing
- Commodities
- Supply Chain
- Fortune 100
- Nutrition
- JSON-LD
- Linked Data
- Semantic Web
---
