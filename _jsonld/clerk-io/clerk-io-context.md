---
class_count: 0
classes: []
context_file: json-ld/clerk-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/clerk-io/refs/heads/main/json-ld/clerk-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Clerk Io from Clerk.io.
layout: jsonld
name: Clerk Io Context
namespaces:
- prefix: clerk
  uri: https://clerk.io/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Product
  type: ''
- container: ''
  name: Category
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Recommendation
  type: ''
property_count: 5
provider_name: Clerk.io
provider_slug: clerk-io
slug: clerk-io-context
source_filename: clerk-io-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"clerk\": \"https://clerk.io/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"id\": \"schema:productID\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"price\": \"schema:price\",\n        \"currency\": \"schema:priceCurrency\",\n        \"image\": \"schema:image\",\n        \"url\": \"schema:url\",\n        \"brand\": \"schema:brand\",\n        \"categories\": \"clerk:categories\",\n        \"stock\": \"clerk:stock\"\n      }\n    },\n\n    \"Category\": {\n      \"@id\": \"schema:CategoryCode\",\n      \"@context\": {\n        \"id\": \"schema:codeValue\",\n        \"name\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"parent\": \"clerk:parent\"\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Order\"\
  ,\n      \"@context\": {\n        \"id\": \"schema:orderNumber\",\n        \"customer\": \"schema:customer\",\n        \"products\": \"clerk:products\",\n        \"time\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"total\": \"schema:totalPrice\"\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"Recommendation\": {\n      \"@id\": \"clerk:Recommendation\",\n      \"@context\": {\n        \"slot\": \"clerk:slot\",\n        \"products\": \"clerk:products\",\n        \"score\": \"clerk:score\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/clerk-io/refs/heads/main/json-ld/clerk-io-context.jsonld
tags:
- AI
- Commerce
- E-Commerce
- Email Marketing
- Personalization
- Recommendations
- Search
- JSON-LD
- Linked Data
- Semantic Web
---
