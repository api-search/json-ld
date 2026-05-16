---
api_specs:
- filename: buywhere-openapi.yml
  format: yaml
  label: BuyWhere Product Catalog API
  slug: product-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/buywhere/refs/heads/main/openapi/buywhere-openapi.yml
class_count: 25
classes:
- id
- type
- Product
- Offer
- ItemList
- Category
- title
- description
- price
- original_price
- discount_pct
- currency
- country_code
- rating
- review_count
- category_path
- structured_specs
- comparison_attributes
- normalized_price_usd
- availability
- domain
- merchant_name
- slug
- parent_slug
- product_count
context_file: json-ld/buywhere-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/buywhere/refs/heads/main/json-ld/buywhere-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Buywhere from BuyWhere.
layout: jsonld
name: Buywhere Context
namespaces:
- prefix: buywhere
  uri: https://api.buywhere.ai/vocab#
properties:
- container: ''
  name: brand
  type: schema:Brand
- container: ''
  name: url
  type: reference
- container: ''
  name: image_url
  type: reference
- container: ''
  name: updated_at
  type: schema:DateTime
property_count: 4
provider_name: BuyWhere
provider_slug: buywhere
slug: buywhere-context
source_filename: buywhere-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"buywhere\": \"https://api.buywhere.ai/vocab#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Product\": \"schema:Product\",\n    \"Offer\": \"schema:Offer\",\n    \"ItemList\": \"schema:ItemList\",\n    \"Category\": \"buywhere:Category\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"brand\": {\n      \"@id\": \"schema:brand\",\n      \"@type\": \"schema:Brand\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"image_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"price\": \"schema:price\",\n    \"original_price\": \"buywhere:originalPrice\",\n    \"discount_pct\": \"buywhere:discountPercentage\",\n    \"currency\": \"schema:priceCurrency\",\n    \"country_code\": \"schema:areaServed\",\n    \"rating\": \"schema:aggregateRating\",\n    \"review_count\": \"schema:reviewCount\"\
  ,\n    \"category_path\": \"buywhere:categoryPath\",\n    \"structured_specs\": \"buywhere:structuredSpecs\",\n    \"comparison_attributes\": \"buywhere:comparisonAttributes\",\n    \"normalized_price_usd\": \"buywhere:normalizedPriceUSD\",\n    \"availability\": \"schema:itemAvailability\",\n    \"domain\": \"buywhere:merchantDomain\",\n    \"merchant_name\": \"schema:seller\",\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"slug\": \"buywhere:slug\",\n    \"parent_slug\": \"buywhere:parentSlug\",\n    \"product_count\": \"buywhere:productCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/buywhere/refs/heads/main/json-ld/buywhere-context.jsonld
tags:
- E-commerce
- Shopping
- Price Comparison
- SEA
- Southeast Asia
- AI Agents
- Product Catalog
- JSON-LD
- Linked Data
- Semantic Web
---
