---
api_specs:
- filename: tiktok-business-openapi.yml
  format: yaml
  label: TikTok API for Business
  slug: tiktok-business-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-business-openapi.yml
- filename: tiktok-shop-openapi.yml
  format: yaml
  label: TikTok Shop API
  slug: tiktok-shop-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-shop-openapi.yml
- filename: tiktok-data-portability-openapi.yml
  format: yaml
  label: TikTok Data Portability API
  slug: tiktok-data-portability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/openapi/tiktok-data-portability-openapi.yml
class_count: 14
classes:
- campaign_id
- campaign_name
- advertiser_id
- objective_type
- budget
- order_id
- order_status
- product_id
- product_name
- sku_id
- line_items
- TikTokCampaign
- TikTokOrder
- TikTokProduct
context_file: json-ld/tiktok-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/json-ld/tiktok-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tiktok from TikTok.
layout: jsonld
name: Tiktok Context
namespaces:
- prefix: tiktok
  uri: https://www.tiktok.com/vocab/
properties: []
property_count: 0
provider_name: TikTok
provider_slug: tiktok
slug: tiktok-context
source_filename: tiktok-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tiktok\": \"https://www.tiktok.com/vocab/\",\n    \"campaign_id\": \"tiktok:campaignId\",\n    \"campaign_name\": \"name\",\n    \"advertiser_id\": \"tiktok:advertiserId\",\n    \"objective_type\": \"tiktok:objectiveType\",\n    \"budget\": \"tiktok:budget\",\n    \"order_id\": \"tiktok:orderId\",\n    \"order_status\": \"tiktok:orderStatus\",\n    \"product_id\": \"tiktok:productId\",\n    \"product_name\": \"name\",\n    \"sku_id\": \"tiktok:skuId\",\n    \"line_items\": \"itemListElement\",\n    \"TikTokCampaign\": \"tiktok:AdCampaign\",\n    \"TikTokOrder\": \"Order\",\n    \"TikTokProduct\": \"Product\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tiktok/refs/heads/main/json-ld/tiktok-context.jsonld
tags:
- Advertising
- Commerce
- Content
- E-Commerce
- Social Media
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
