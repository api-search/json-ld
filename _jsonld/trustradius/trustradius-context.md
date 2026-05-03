---
api_specs:
- filename: trustradius-public-openapi.yml
  format: yaml
  label: TrustRadius Public API
  slug: trustradius-public-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/openapi/trustradius-public-openapi.yml
- filename: trustradius-reviews-openapi.yml
  format: yaml
  label: TrustRadius Reviews API
  slug: trustradius-reviews-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/openapi/trustradius-reviews-openapi.yml
class_count: 9
classes:
- Product
- id
- name
- description
- vendorName
- websiteUrl
- Review
- title
- Category
context_file: json-ld/trustradius-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/json-ld/trustradius-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trustradius from TrustRadius.
layout: jsonld
name: Trustradius Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tr
  uri: https://www.trustradius.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: slug
  type: string
- container: ''
  name: trScore
  type: decimal
- container: ''
  name: reviewCount
  type: integer
- container: ''
  name: categories
  type: schema:Thing
- container: ''
  name: body
  type: string
- container: list
  name: pros
  type: ''
- container: list
  name: cons
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: verified
  type: boolean
- container: ''
  name: ratings
  type: schema:Rating
- container: ''
  name: overall
  type: decimal
- container: ''
  name: usability
  type: decimal
- container: ''
  name: support
  type: decimal
- container: ''
  name: likelihoodToRecommend
  type: decimal
- container: ''
  name: valueForMoney
  type: decimal
- container: ''
  name: featureRichness
  type: decimal
- container: ''
  name: reviewer
  type: schema:Person
- container: ''
  name: title_reviewer
  type: ''
- container: ''
  name: industry
  type: string
- container: ''
  name: companySize
  type: string
- container: ''
  name: productCount
  type: integer
property_count: 22
provider_name: TrustRadius
provider_slug: trustradius
slug: trustradius-context
source_filename: trustradius-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tr\": \"https://www.trustradius.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:SoftwareApplication\",\n    \"id\": \"schema:identifier\",\n    \"slug\": {\"@id\": \"tr:slug\", \"@type\": \"xsd:string\"},\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"vendorName\": \"schema:provider\",\n    \"websiteUrl\": \"schema:url\",\n    \"trScore\": {\"@id\": \"tr:trScore\", \"@type\": \"xsd:decimal\"},\n    \"reviewCount\": {\"@id\": \"schema:reviewCount\", \"@type\": \"xsd:integer\"},\n    \"categories\": {\"@id\": \"schema:applicationCategory\", \"@type\": \"schema:Thing\"},\n\n    \"Review\": \"schema:Review\",\n    \"title\": \"schema:name\",\n    \"body\": {\"@id\": \"schema:reviewBody\", \"@type\": \"xsd:string\"},\n    \"pros\": {\"@id\": \"tr:pros\", \"@container\": \"@list\"},\n    \"cons\":\
  \ {\"@id\": \"tr:cons\", \"@container\": \"@list\"},\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"updatedAt\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n    \"verified\": {\"@id\": \"tr:verified\", \"@type\": \"xsd:boolean\"},\n\n    \"ratings\": {\"@id\": \"schema:reviewRating\", \"@type\": \"schema:Rating\"},\n    \"overall\": {\"@id\": \"schema:ratingValue\", \"@type\": \"xsd:decimal\"},\n    \"usability\": {\"@id\": \"tr:usabilityRating\", \"@type\": \"xsd:decimal\"},\n    \"support\": {\"@id\": \"tr:supportRating\", \"@type\": \"xsd:decimal\"},\n    \"likelihoodToRecommend\": {\"@id\": \"tr:likelihoodToRecommend\", \"@type\": \"xsd:decimal\"},\n    \"valueForMoney\": {\"@id\": \"tr:valueForMoney\", \"@type\": \"xsd:decimal\"},\n    \"featureRichness\": {\"@id\": \"tr:featureRichness\", \"@type\": \"xsd:decimal\"},\n\n    \"reviewer\": {\"@id\": \"schema:author\", \"@type\": \"schema:Person\"},\n    \"title_reviewer\"\
  : {\"@id\": \"schema:jobTitle\"},\n    \"industry\": {\"@id\": \"schema:industry\", \"@type\": \"xsd:string\"},\n    \"companySize\": {\"@id\": \"tr:companySize\", \"@type\": \"xsd:string\"},\n\n    \"Category\": \"schema:CategoryCode\",\n    \"productCount\": {\"@id\": \"tr:productCount\", \"@type\": \"xsd:integer\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trustradius/refs/heads/main/json-ld/trustradius-context.jsonld
tags:
- B2B Software Reviews
- Buyer Intelligence
- Intent Data
- Software Reviews
- Reviews
- Product Reviews
- Categories
- JSON-LD
- Linked Data
- Semantic Web
---
