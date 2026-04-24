---
class_count: 6
classes:
- CategoryRef
- ErrorResponse
- ProductListResponse
- Product
- name
- url
context_file: json-ld/best-buy-products-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/json-ld/best-buy-products-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Best Buy Products Api from Best Buy.
layout: jsonld
name: Best Buy Products Api Context
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
  name: id
  type: string
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
- container: ''
  name: partial
  type: boolean
- container: ''
  name: canonicalUrl
  type: string
- container: ''
  name: nextCursorMark
  type: string
- container: set
  name: products
  type: string
- container: ''
  name: sku
  type: integer
- container: ''
  name: regularPrice
  type: double
- container: ''
  name: salePrice
  type: double
- container: ''
  name: onSale
  type: boolean
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: modelNumber
  type: string
- container: ''
  name: shortDescription
  type: string
- container: ''
  name: longDescription
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: addToCartUrl
  type: string
- container: ''
  name: inStoreAvailability
  type: boolean
- container: ''
  name: onlineAvailability
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: class
  type: string
- container: ''
  name: classId
  type: integer
- container: ''
  name: subclass
  type: string
- container: ''
  name: subclassId
  type: integer
- container: ''
  name: department
  type: string
- container: ''
  name: departmentId
  type: integer
- container: set
  name: categoryPath
  type: string
- container: ''
  name: customerReviewCount
  type: integer
- container: ''
  name: customerReviewAverage
  type: double
- container: ''
  name: priceUpdateDate
  type: dateTime
property_count: 38
provider_name: Best Buy
provider_slug: best-buy
slug: best-buy-products-api-context
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
