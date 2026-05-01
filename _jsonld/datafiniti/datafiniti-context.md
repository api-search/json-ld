---
api_specs:
- filename: datafiniti-api.yml
  format: yaml
  label: Datafiniti API
  slug: datafiniti-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datafiniti/refs/heads/main/openapi/datafiniti-api.yml
class_count: 0
classes: []
context_file: json-ld/datafiniti-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/datafiniti/refs/heads/main/json-ld/datafiniti-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Datafiniti from Datafiniti.
layout: jsonld
name: Datafiniti Context
namespaces:
- prefix: datafiniti
  uri: https://docs.datafiniti.co/reference/
properties:
- container: ''
  name: Business
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: Property
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: SearchRequest
  type: ''
property_count: 5
provider_name: Datafiniti
provider_slug: datafiniti
slug: datafiniti-context
source_filename: datafiniti-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"datafiniti\": \"https://docs.datafiniti.co/reference/\",\n    \"Business\": {\n      \"@id\": \"https://schema.org/LocalBusiness\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"address\": \"https://schema.org/address\",\n        \"categories\": \"https://schema.org/category\",\n        \"phones\": \"https://schema.org/telephone\",\n        \"websites\": \"https://schema.org/url\",\n        \"primaryCategories\": \"https://schema.org/category\"\n      }\n    },\n    \"Product\": {\n      \"@id\": \"https://schema.org/Product\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"brand\": \"https://schema.org/brand\",\n        \"categories\": \"https://schema.org/category\",\n        \"prices\": \"https://schema.org/offers\",\n        \"manufacturer\"\
  : \"https://schema.org/manufacturer\",\n        \"asins\": \"https://schema.org/sku\",\n        \"upc\": \"https://schema.org/gtin12\"\n      }\n    },\n    \"Property\": {\n      \"@id\": \"https://schema.org/RealEstateListing\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"address\": \"https://schema.org/address\",\n        \"geoLocation\": \"https://schema.org/geo\",\n        \"listingPrices\": \"https://schema.org/price\",\n        \"numBedroom\": \"https://schema.org/numberOfBedrooms\",\n        \"numBathroom\": \"https://schema.org/numberOfBathroomsTotal\",\n        \"lotSize\": \"https://schema.org/lotSize\"\n      }\n    },\n    \"Person\": {\n      \"@id\": \"https://schema.org/Person\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"emails\": \"https://schema.org/email\",\n        \"phones\": \"https://schema.org/telephone\",\n        \"addresses\":\
  \ \"https://schema.org/address\"\n      }\n    },\n    \"SearchRequest\": {\n      \"@id\": \"datafiniti:search-and-downloads\",\n      \"@context\": {\n        \"query\": \"https://schema.org/query\",\n        \"num_records\": \"https://schema.org/numberOfItems\",\n        \"download\": \"https://schema.org/option\",\n        \"format\": \"https://schema.org/encodingFormat\",\n        \"view\": \"https://schema.org/view\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/datafiniti/refs/heads/main/json-ld/datafiniti-context.jsonld
tags:
- Business Data
- Data Aggregation
- Data as a Service
- People Data
- Product Data
- Property Data
- JSON-LD
- Linked Data
- Semantic Web
---
