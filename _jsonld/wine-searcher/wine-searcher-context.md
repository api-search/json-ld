---
api_specs:
- filename: wine-searcher-openapi.yml
  format: yaml
  label: Wine-Searcher API
  slug: wine-searcher-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/openapi/wine-searcher-openapi.yml
class_count: 15
classes:
- MerchantListing
- WineProducer
- WineRegion
- WineVintage
- Product
- price
- priceCurrency
- name
- description
- url
- GeoCoordinates
- latitude
- longitude
- addressCountry
- Organization
context_file: json-ld/wine-searcher-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/json-ld/wine-searcher-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wine Searcher from Wine-Searcher.
layout: jsonld
name: Wine Searcher Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: wine
  uri: https://www.wine-searcher.com/vocab#
- prefix: gs1
  uri: https://www.gs1.org/voc/
properties:
- container: ''
  name: Wine
  type: reference
- container: ''
  name: wineName
  type: string
- container: ''
  name: vintage
  type: string
- container: ''
  name: producer
  type: reference
- container: ''
  name: region
  type: string
- container: ''
  name: grape
  type: string
- container: ''
  name: alcoholByVolume
  type: decimal
- container: ''
  name: criticScore
  type: decimal
- container: ''
  name: priceAverage
  type: decimal
- container: ''
  name: priceMin
  type: decimal
- container: ''
  name: priceMax
  type: decimal
- container: ''
  name: listingCount
  type: integer
- container: ''
  name: merchantName
  type: string
- container: ''
  name: bottleSize
  type: string
- container: ''
  name: offerType
  type: string
- container: ''
  name: purchaseLink
  type: reference
property_count: 16
provider_name: Wine-Searcher
provider_slug: wine-searcher
slug: wine-searcher-context
source_filename: wine-searcher-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"wine\": \"https://www.wine-searcher.com/vocab#\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n\n    \"Wine\": {\n      \"@id\": \"wine:Wine\",\n      \"@type\": \"@id\"\n    },\n    \"MerchantListing\": \"wine:MerchantListing\",\n    \"WineProducer\": \"wine:WineProducer\",\n    \"WineRegion\": \"wine:WineRegion\",\n    \"WineVintage\": \"wine:WineVintage\",\n\n    \"wineName\": {\n      \"@id\": \"wine:wineName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vintage\": {\n      \"@id\": \"wine:vintage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"producer\": {\n      \"@id\": \"wine:producer\",\n      \"@type\": \"@id\"\n    },\n    \"region\": {\n      \"@id\": \"wine:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grape\": {\n      \"@id\": \"wine:grape\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alcoholByVolume\"\
  : {\n      \"@id\": \"wine:alcoholByVolume\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"criticScore\": {\n      \"@id\": \"wine:criticScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"priceAverage\": {\n      \"@id\": \"wine:priceAverage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"priceMin\": {\n      \"@id\": \"wine:priceMin\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"priceMax\": {\n      \"@id\": \"wine:priceMax\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"listingCount\": {\n      \"@id\": \"wine:listingCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"merchantName\": {\n      \"@id\": \"wine:merchantName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bottleSize\": {\n      \"@id\": \"wine:bottleSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offerType\": {\n      \"@id\": \"wine:offerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchaseLink\": {\n      \"@id\": \"wine:purchaseLink\",\n      \"@type\": \"@id\"\n   \
  \ },\n    \"Product\": \"schema:Product\",\n    \"price\": \"schema:price\",\n    \"priceCurrency\": \"schema:priceCurrency\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"GeoCoordinates\": \"schema:GeoCoordinates\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"addressCountry\": \"schema:addressCountry\",\n    \"Organization\": \"schema:Organization\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wine-searcher/refs/heads/main/json-ld/wine-searcher-context.jsonld
tags:
- Data
- Marketplace
- Wine
- Prices
- Merchants
- Vintages
- Critics
- JSON-LD
- Linked Data
- Semantic Web
---
