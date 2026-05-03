---
api_specs:
- filename: trustpilot-business-units-openapi.yml
  format: yaml
  label: Trustpilot Business Units API
  slug: trustpilot-business-units-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-business-units-openapi.yml
- filename: trustpilot-service-reviews-openapi.yml
  format: yaml
  label: Trustpilot Service Reviews API
  slug: trustpilot-service-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-service-reviews-openapi.yml
- filename: trustpilot-invitation-openapi.yml
  format: yaml
  label: Trustpilot Invitation API
  slug: trustpilot-invitation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-invitation-openapi.yml
- filename: trustpilot-product-reviews-openapi.yml
  format: yaml
  label: Trustpilot Product Reviews API
  slug: trustpilot-product-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/openapi/trustpilot-product-reviews-openapi.yml
class_count: 14
classes:
- Review
- id
- title
- status
- consumer
- displayName
- email
- BusinessUnit
- websiteUrl
- countryCode
- Invitation
- recipientEmail
- recipientName
- referenceNumber
context_file: json-ld/trustpilot-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/json-ld/trustpilot-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trustpilot from Trustpilot.
layout: jsonld
name: Trustpilot Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tp
  uri: https://developers.trustpilot.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: stars
  type: integer
- container: ''
  name: text
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: verificationLevel
  type: string
- container: ''
  name: reply
  type: schema:Comment
- container: ''
  name: trustScore
  type: decimal
- container: ''
  name: numberOfReviews
  type: integer
property_count: 9
provider_name: Trustpilot
provider_slug: trustpilot
slug: trustpilot-context
source_filename: trustpilot-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tp\": \"https://developers.trustpilot.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Review\": \"schema:Review\",\n    \"id\": \"schema:identifier\",\n    \"stars\": {\n      \"@id\": \"schema:reviewRating\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": \"schema:name\",\n    \"text\": {\n      \"@id\": \"schema:reviewBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"schema:inLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": \"schema:status\",\n    \"verificationLevel\": {\n      \"@id\": \"tp:verificationLevel\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"consumer\"\
  : \"schema:author\",\n    \"displayName\": \"schema:name\",\n    \"email\": \"schema:email\",\n\n    \"reply\": {\n      \"@id\": \"schema:comment\",\n      \"@type\": \"schema:Comment\"\n    },\n\n    \"BusinessUnit\": \"schema:Organization\",\n    \"trustScore\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"websiteUrl\": \"schema:url\",\n    \"countryCode\": \"schema:addressCountry\",\n    \"numberOfReviews\": {\n      \"@id\": \"schema:reviewCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Invitation\": \"schema:Offer\",\n    \"recipientEmail\": \"schema:email\",\n    \"recipientName\": \"schema:name\",\n    \"referenceNumber\": \"schema:orderNumber\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trustpilot/refs/heads/main/json-ld/trustpilot-context.jsonld
tags:
- Consumer Reviews
- Reviews
- Trust
- Ratings
- Business Profiles
- Product Reviews
- JSON-LD
- Linked Data
- Semantic Web
---
