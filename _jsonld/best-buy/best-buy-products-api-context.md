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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bb\": \"https://developer.bestbuy.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CategoryRef\": \"bb:CategoryRef\",\n    \"ErrorResponse\": \"bb:ErrorResponse\",\n    \"ProductListResponse\": \"bb:ProductListResponse\",\n    \"Product\": \"bb:Product\",\n    \"id\": {\n      \"@id\": \"bb:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"status\": {\n      \"@id\": \"bb:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error\": {\n      \"@id\": \"bb:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"bb:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"bb:from\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"to\": {\n      \"@id\": \"bb:to\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"total\": {\n      \"@id\": \"bb:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currentPage\": {\n      \"@id\": \"bb:currentPage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPages\": {\n      \"@id\": \"bb:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"queryTime\": {\n      \"@id\": \"bb:queryTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalTime\": {\n      \"@id\": \"bb:totalTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partial\": {\n      \"@id\": \"bb:partial\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"canonicalUrl\": {\n      \"@id\": \"bb:canonicalUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextCursorMark\": {\n      \"@id\": \"bb:nextCursorMark\",\n      \"@type\": \"xsd:string\"\n    },\n    \"products\": {\n      \"@id\": \"bb:products\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"bb:sku\",\n      \"@type\": \"xsd:integer\"\n  \
  \  },\n    \"regularPrice\": {\n      \"@id\": \"bb:regularPrice\",\n      \"@type\": \"xsd:double\"\n    },\n    \"salePrice\": {\n      \"@id\": \"bb:salePrice\",\n      \"@type\": \"xsd:double\"\n    },\n    \"onSale\": {\n      \"@id\": \"bb:onSale\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"bb:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelNumber\": {\n      \"@id\": \"bb:modelNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortDescription\": {\n      \"@id\": \"bb:shortDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"longDescription\": {\n      \"@id\": \"bb:longDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"bb:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"addToCartUrl\": {\n      \"@id\": \"bb:addToCartUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inStoreAvailability\": {\n      \"@id\": \"bb:inStoreAvailability\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"onlineAvailability\": {\n      \"@id\": \"bb:onlineAvailability\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"bb:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"class\": {\n      \"@id\": \"bb:class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classId\": {\n      \"@id\": \"bb:classId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subclass\": {\n      \"@id\": \"bb:subclass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subclassId\": {\n      \"@id\": \"bb:subclassId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"department\": {\n      \"@id\": \"bb:department\",\n      \"@type\": \"xsd:string\"\n    },\n    \"departmentId\": {\n      \"@id\": \"bb:departmentId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"categoryPath\": {\n      \"@id\": \"bb:categoryPath\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerReviewCount\": {\n  \
  \    \"@id\": \"bb:customerReviewCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"customerReviewAverage\": {\n      \"@id\": \"bb:customerReviewAverage\",\n      \"@type\": \"xsd:double\"\n    },\n    \"priceUpdateDate\": {\n      \"@id\": \"bb:priceUpdateDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/json-ld/best-buy-products-api-context.jsonld
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
