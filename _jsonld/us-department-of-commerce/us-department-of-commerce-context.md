---
api_specs:
- filename: commerce-gov-api-openapi.yml
  format: yaml
  label: Commerce.gov API
  slug: commercegov-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-department-of-commerce/refs/heads/main/openapi/commerce-gov-api-openapi.yml
class_count: 11
classes:
- CommerceNewsArticle
- CommerceBlogPost
- CommerceImage
- CommerceBureau
- id
- type
- title
- body
- summary
- tags
- author
context_file: json-ld/us-department-of-commerce-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-department-of-commerce/refs/heads/main/json-ld/us-department-of-commerce-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Department Of Commerce from US Department of Commerce.
layout: jsonld
name: Us Department Of Commerce Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: commerce
  uri: https://www.commerce.gov/ns/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gov
  uri: http://www.w3.org/ns/org#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: changed
  type: dateTime
- container: ''
  name: url
  type: reference
- container: ''
  name: field_image
  type: reference
- container: ''
  name: Department
  type: ''
- container: ''
  name: bureaus
  type: ''
property_count: 6
provider_name: US Department of Commerce
provider_slug: us-department-of-commerce
slug: us-department-of-commerce-context
source_filename: us-department-of-commerce-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"commerce\": \"https://www.commerce.gov/ns/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gov\": \"http://www.w3.org/ns/org#\",\n\n    \"CommerceNewsArticle\": \"schema:NewsArticle\",\n    \"CommerceBlogPost\": \"schema:BlogPosting\",\n    \"CommerceImage\": \"schema:ImageObject\",\n    \"CommerceBureau\": \"schema:GovernmentOrganization\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"title\": \"schema:headline\",\n    \"body\": \"schema:articleBody\",\n    \"summary\": \"schema:abstract\",\n    \"created\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"changed\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"field_image\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"\
  @id\"\n    },\n    \"tags\": \"schema:keywords\",\n    \"author\": \"schema:author\",\n\n    \"Department\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"name\": \"US Department of Commerce\",\n      \"url\": \"https://www.commerce.gov\",\n      \"sameAs\": [\n        \"https://www.wikidata.org/wiki/Q11762\",\n        \"https://dbpedia.org/resource/United_States_Department_of_Commerce\"\n      ]\n    },\n\n    \"bureaus\": {\n      \"Census Bureau\": \"https://www.census.gov\",\n      \"Bureau of Economic Analysis\": \"https://www.bea.gov\",\n      \"International Trade Administration\": \"https://www.trade.gov\",\n      \"NOAA\": \"https://www.noaa.gov\",\n      \"NIST\": \"https://www.nist.gov\",\n      \"USPTO\": \"https://www.uspto.gov\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-department-of-commerce/refs/heads/main/json-ld/us-department-of-commerce-context.jsonld
tags:
- Commerce
- Federal Government
- Open Data
- Trade
- Economic Data
- Climate
- Standards
- JSON-LD
- Linked Data
- Semantic Web
---
