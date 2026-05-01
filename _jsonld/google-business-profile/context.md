---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Business Profile API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-business-profile/refs/heads/main/openapi/openapi.yml
class_count: 13
classes:
- LocalBusiness
- name
- description
- address
- telephone
- url
- openingHoursSpecification
- review
- aggregateRating
- photo
- geo
- category
- priceRange
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-business-profile/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Business Profile.
layout: jsonld
name: context Context
namespaces:
- prefix: gbp
  uri: https://mybusiness.googleapis.com/v4/
properties: []
property_count: 0
provider_name: Google Business Profile
provider_slug: google-business-profile
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gbp\": \"https://mybusiness.googleapis.com/v4/\",\n    \"LocalBusiness\": \"schema:LocalBusiness\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"address\": \"schema:address\",\n    \"telephone\": \"schema:telephone\",\n    \"url\": \"schema:url\",\n    \"openingHoursSpecification\": \"schema:openingHoursSpecification\",\n    \"review\": \"schema:review\",\n    \"aggregateRating\": \"schema:aggregateRating\",\n    \"photo\": \"schema:photo\",\n    \"geo\": \"schema:geo\",\n    \"category\": \"schema:additionalType\",\n    \"priceRange\": \"schema:priceRange\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-business-profile/refs/heads/main/json-ld/context.jsonld
tags:
- Business Profiles
- Google
- Local Business
- Locations
- Reviews
- JSON-LD
- Linked Data
- Semantic Web
---
