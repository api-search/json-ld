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
