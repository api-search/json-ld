---
api_specs:
- filename: shopper-approved-openapi.yml
  format: yaml
  label: Shopper Approved API
  slug: shopper-approved-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shopper-approved/refs/heads/main/openapi/shopper-approved-openapi.yml
class_count: 23
classes:
- Review
- reviewid
- name
- review
- headline
- verified
- location
- helpful
- unhelpful
- ProductReview
- product_id
- product_name
- SiteStats
- site_id
- count
- ratingValue
- five_star
- domain
- OrderSubmission
- orderid
- email
- followup
- products
context_file: json-ld/shopper-approved-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shopper-approved/refs/heads/main/json-ld/shopper-approved-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shopper Approved from Shopper Approved.
layout: jsonld
name: Shopper Approved Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: date
  type: date
- container: ''
  name: rating
  type: integer
property_count: 2
provider_name: Shopper Approved
provider_slug: shopper-approved
slug: shopper-approved-context
source_filename: shopper-approved-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Review\": \"schema:Review\",\n    \"reviewid\": \"schema:identifier\",\n    \"name\": \"schema:author\",\n    \"date\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"rating\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"review\": \"schema:reviewBody\",\n    \"headline\": \"schema:name\",\n    \"verified\": \"schema:isVerified\",\n    \"location\": \"schema:locationCreated\",\n    \"helpful\": \"schema:interactionCount\",\n    \"unhelpful\": \"schema:interactionCount\",\n\n    \"ProductReview\": \"schema:Review\",\n    \"product_id\": \"schema:identifier\",\n    \"product_name\": \"schema:name\",\n\n    \"SiteStats\": \"schema:AggregateRating\",\n    \"site_id\": \"schema:identifier\",\n    \"count\": \"schema:reviewCount\",\n    \"ratingValue\"\
  : \"schema:ratingValue\",\n    \"five_star\": \"schema:bestRating\",\n    \"domain\": \"schema:url\",\n\n    \"OrderSubmission\": \"schema:Order\",\n    \"orderid\": \"schema:orderNumber\",\n    \"email\": \"schema:email\",\n    \"followup\": \"schema:deliveryDate\",\n    \"products\": \"schema:orderedItem\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shopper-approved/refs/heads/main/json-ld/shopper-approved-context.jsonld
tags:
- Reviews
- Ratings
- Ecommerce
- Customer Feedback
- Social Proof
- JSON-LD
- Linked Data
- Semantic Web
---
