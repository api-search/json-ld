---
class_count: 36
classes:
- ProductListing
- Review
- Organization
- Person
- id
- type
- name
- description
- slug
- category
- subcategories
- vendor
- headquarters
- deploymentTypes
- organizationSizes
- pricingModel
- startingPrice
- hasFreeTrialOrDemo
- features
- integrations
- listingType
- overallRating
- easeOfUseRating
- valueForMoneyRating
- customerSupportRating
- reviewCount
- rating
- title
- body
- pros
- cons
- reviewer
- jobTitle
- industry
- verified
- helpful
context_file: json-ld/softwaresuggest-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/softwaresuggest/refs/heads/main/json-ld/softwaresuggest-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Softwaresuggest from SoftwareSuggest.
layout: jsonld
name: Softwaresuggest Context
namespaces:
- prefix: ss
  uri: https://api-evangelist.com/vocab/softwaresuggest#
- prefix: schema
  uri: https://schema.org/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: website
  type: reference
- container: ''
  name: founded
  type: gYear
- container: ''
  name: productUrl
  type: reference
- container: ''
  name: publishedAt
  type: dateTime
property_count: 4
provider_name: SoftwareSuggest
provider_slug: softwaresuggest
slug: softwaresuggest-context
source_filename: softwaresuggest-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ss\": \"https://api-evangelist.com/vocab/softwaresuggest#\",\n    \"schema\": \"https://schema.org/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ProductListing\": \"gr:ProductOrService\",\n    \"Review\": \"schema:Review\",\n    \"Organization\": \"schema:Organization\",\n    \"Person\": \"schema:Person\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"slug\": \"schema:identifier\",\n\n    \"category\": \"schema:applicationCategory\",\n    \"subcategories\": \"schema:applicationSubCategory\",\n    \"vendor\": \"schema:brand\",\n    \"website\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"founded\": {\n      \"@id\": \"schema:foundingDate\",\n      \"@type\": \"xsd:gYear\"\n    },\n    \"headquarters\": \"schema:address\",\n\n    \"deploymentTypes\"\
  : \"ss:deploymentTypes\",\n    \"organizationSizes\": \"ss:organizationSizes\",\n    \"pricingModel\": \"ss:pricingModel\",\n    \"startingPrice\": \"gr:hasCurrencyValue\",\n    \"hasFreeTrialOrDemo\": \"schema:offers\",\n    \"features\": \"schema:featureList\",\n    \"integrations\": \"ss:integrations\",\n    \"productUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"listingType\": \"ss:listingType\",\n\n    \"overallRating\": \"schema:ratingValue\",\n    \"easeOfUseRating\": \"ss:easeOfUseRating\",\n    \"valueForMoneyRating\": \"ss:valueForMoneyRating\",\n    \"customerSupportRating\": \"ss:customerSupportRating\",\n    \"reviewCount\": \"schema:reviewCount\",\n    \"rating\": \"schema:aggregateRating\",\n\n    \"title\": \"schema:name\",\n    \"body\": \"schema:reviewBody\",\n    \"pros\": \"ss:pros\",\n    \"cons\": \"ss:cons\",\n    \"reviewer\": \"schema:author\",\n    \"jobTitle\": \"schema:jobTitle\",\n    \"industry\": \"schema:industry\",\n \
  \   \"verified\": \"ss:verified\",\n    \"helpful\": \"ss:helpful\",\n    \"publishedAt\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/softwaresuggest/refs/heads/main/json-ld/softwaresuggest-context.jsonld
tags:
- Software Discovery
- Business Software
- SaaS
- Software Reviews
- B2B
- JSON-LD
- Linked Data
- Semantic Web
---
