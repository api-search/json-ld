---
api_specs:
- filename: best-buy-products-api.yaml
  format: yaml
  label: Best Buy Products API
  slug: products-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/openapi/best-buy-products-api.yaml
- filename: best-buy-stores-api.yaml
  format: yaml
  label: Best Buy Stores API
  slug: stores-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/openapi/best-buy-stores-api.yaml
- filename: best-buy-recommendations-api.yaml
  format: yaml
  label: Best Buy Recommendations API
  slug: recommendations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/openapi/best-buy-recommendations-api.yaml
class_count: 3
classes:
- ErrorResponse
- RecommendationsResponse
- RecommendedProduct
context_file: json-ld/best-buy-recommendations-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/json-ld/best-buy-recommendations-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Best Buy Recommendations Api from Best Buy.
layout: jsonld
name: Best Buy Recommendations Api Context
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
  name: metadata
  type: string
- container: ''
  name: resultSet
  type: string
- container: ''
  name: count
  type: integer
- container: set
  name: results
  type: string
- container: ''
  name: sku
  type: integer
- container: ''
  name: names
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: images
  type: string
- container: ''
  name: standard
  type: string
- container: ''
  name: prices
  type: string
- container: ''
  name: regular
  type: double
- container: ''
  name: current
  type: double
- container: ''
  name: links
  type: string
- container: ''
  name: product
  type: string
- container: ''
  name: web
  type: string
- container: ''
  name: addToCart
  type: string
- container: ''
  name: rank
  type: integer
property_count: 20
provider_name: Best Buy
provider_slug: best-buy
slug: best-buy-recommendations-api-context
source_filename: best-buy-recommendations-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bb\": \"https://developer.bestbuy.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorResponse\": \"bb:ErrorResponse\",\n    \"RecommendationsResponse\": \"bb:RecommendationsResponse\",\n    \"RecommendedProduct\": \"bb:RecommendedProduct\",\n    \"status\": {\n      \"@id\": \"bb:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error\": {\n      \"@id\": \"bb:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"bb:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"bb:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultSet\": {\n      \"@id\": \"bb:resultSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"bb:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"results\": {\n\
  \      \"@id\": \"bb:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"bb:sku\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"names\": {\n      \"@id\": \"bb:names\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"bb:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"images\": {\n      \"@id\": \"bb:images\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standard\": {\n      \"@id\": \"bb:standard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prices\": {\n      \"@id\": \"bb:prices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regular\": {\n      \"@id\": \"bb:regular\",\n      \"@type\": \"xsd:double\"\n    },\n    \"current\": {\n      \"@id\": \"bb:current\",\n      \"@type\": \"xsd:double\"\n    },\n    \"links\": {\n      \"@id\": \"bb:links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"bb:product\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"web\": {\n      \"@id\": \"bb:web\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addToCart\": {\n      \"@id\": \"bb:addToCart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rank\": {\n      \"@id\": \"bb:rank\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/json-ld/best-buy-recommendations-api-context.jsonld
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
