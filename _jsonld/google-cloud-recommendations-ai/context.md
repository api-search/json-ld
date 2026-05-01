---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud Recommendations AI API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-recommendations-ai/refs/heads/main/openapi/openapi.yml
class_count: 14
classes:
- CatalogItem
- UserEvent
- Recommendation
- catalogId
- categoryHierarchies
- eventType
- visitorId
- productMetadata
- priceRange
- recommendationToken
- placementId
- name
- description
- url
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-recommendations-ai/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud Recommendations AI.
layout: jsonld
name: context Context
namespaces:
- prefix: gcp
  uri: https://cloud.google.com/recommendations-ai#
properties: []
property_count: 0
provider_name: Google Cloud Recommendations AI
provider_slug: google-cloud-recommendations-ai
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcp\": \"https://cloud.google.com/recommendations-ai#\",\n    \"CatalogItem\": \"gcp:CatalogItem\",\n    \"UserEvent\": \"gcp:UserEvent\",\n    \"Recommendation\": \"gcp:Recommendation\",\n    \"catalogId\": \"gcp:catalogId\",\n    \"categoryHierarchies\": \"gcp:categoryHierarchies\",\n    \"eventType\": \"gcp:eventType\",\n    \"visitorId\": \"gcp:visitorId\",\n    \"productMetadata\": \"gcp:productMetadata\",\n    \"priceRange\": \"gcp:priceRange\",\n    \"recommendationToken\": \"gcp:recommendationToken\",\n    \"placementId\": \"gcp:placementId\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-recommendations-ai/refs/heads/main/json-ld/context.jsonld
tags:
- E-Commerce
- Google Cloud
- Machine Learning
- Personalization
- Recommendations
- Retail
- JSON-LD
- Linked Data
- Semantic Web
---
