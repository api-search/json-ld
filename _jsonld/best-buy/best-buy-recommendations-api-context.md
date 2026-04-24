---
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
