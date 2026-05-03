---
api_specs:
- filename: shopify-storefront-openapi.yml
  format: yaml
  label: Shopify Storefront API
  slug: shopify-storefront-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/openapi/shopify-storefront-openapi.yml
class_count: 43
classes:
- Product
- id
- title
- description
- descriptionHtml
- handle
- vendor
- productType
- tags
- availableForSale
- priceRange
- variants
- images
- featuredImage
- ProductVariant
- sku
- price
- compareAtPrice
- weight
- selectedOptions
- Collection
- products
- Cart
- checkoutUrl
- totalQuantity
- cost
- lines
- discountCodes
- Customer
- email
- firstName
- lastName
- phone
- acceptsMarketing
- addresses
- MoneyV2
- amount
- currencyCode
- Image
- url
- altText
- width
- height
context_file: json-ld/shopify-storefront-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/json-ld/shopify-storefront-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shopify Storefront from Shopify Storefront API.
layout: jsonld
name: Shopify Storefront Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: shopify
  uri: https://shopify.dev/docs/api/storefront/latest/objects/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: publishedAt
  type: dateTime
property_count: 1
provider_name: Shopify Storefront API
provider_slug: shopify-storefront
slug: shopify-storefront-context
source_filename: shopify-storefront-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"shopify\": \"https://shopify.dev/docs/api/storefront/latest/objects/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:Product\",\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"descriptionHtml\": \"schema:description\",\n    \"handle\": \"schema:identifier\",\n    \"vendor\": \"schema:brand\",\n    \"productType\": \"schema:category\",\n    \"tags\": \"schema:keywords\",\n    \"availableForSale\": \"schema:availability\",\n    \"publishedAt\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"priceRange\": \"schema:offers\",\n    \"variants\": \"schema:hasVariant\",\n    \"images\": \"schema:image\",\n    \"featuredImage\": \"schema:image\",\n\n    \"ProductVariant\": \"schema:ProductModel\",\n    \"sku\": \"schema:sku\",\n    \"price\": \"schema:price\"\
  ,\n    \"compareAtPrice\": \"schema:originalPrice\",\n    \"weight\": \"schema:weight\",\n    \"selectedOptions\": \"schema:additionalProperty\",\n\n    \"Collection\": \"schema:CollectionPage\",\n    \"products\": \"schema:hasPart\",\n\n    \"Cart\": \"schema:Order\",\n    \"checkoutUrl\": \"schema:url\",\n    \"totalQuantity\": \"schema:orderQuantity\",\n    \"cost\": \"schema:priceSpecification\",\n    \"lines\": \"schema:orderedItem\",\n    \"discountCodes\": \"schema:discount\",\n\n    \"Customer\": \"schema:Person\",\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"phone\": \"schema:telephone\",\n    \"acceptsMarketing\": \"schema:hasOfferCatalog\",\n    \"addresses\": \"schema:address\",\n\n    \"MoneyV2\": \"schema:MonetaryAmount\",\n    \"amount\": \"schema:value\",\n    \"currencyCode\": \"schema:currency\",\n\n    \"Image\": \"schema:ImageObject\",\n    \"url\": \"schema:url\",\n    \"altText\": \"schema:alternateName\"\
  ,\n    \"width\": \"schema:width\",\n    \"height\": \"schema:height\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shopify-storefront/refs/heads/main/json-ld/shopify-storefront-context.jsonld
tags:
- Commerce
- Ecommerce
- Headless
- GraphQL
- Storefront
- Products
- Cart
- Checkout
- JSON-LD
- Linked Data
- Semantic Web
---
