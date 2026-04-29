---
api_specs:
- filename: cpsc-recalls-openapi.yml
  format: yaml
  label: CPSC Recalls API
  slug: recalls
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consumer-product-safety-commission/refs/heads/main/openapi/cpsc-recalls-openapi.yml
class_count: 0
classes: []
context_file: json-ld/consumer-product-safety-commission-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/consumer-product-safety-commission/refs/heads/main/json-ld/consumer-product-safety-commission-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Consumer Product Safety Commission from Consumer Product Safety Commission.
layout: jsonld
name: Consumer Product Safety Commission Context
namespaces:
- prefix: cpsc
  uri: https://www.cpsc.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Recall
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: Hazard
  type: ''
property_count: 3
provider_name: Consumer Product Safety Commission
provider_slug: consumer-product-safety-commission
slug: consumer-product-safety-commission-context
source_filename: consumer-product-safety-commission-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cpsc\": \"https://www.cpsc.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Recall\": {\n      \"@id\": \"cpsc:Recall\",\n      \"@context\": {\n        \"id\": \"cpsc:RecallID\",\n        \"recallNumber\": \"cpsc:RecallNumber\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"consumerContact\": \"cpsc:ConsumerContact\",\n        \"recallDate\": {\n          \"@id\": \"cpsc:RecallDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"lastPublishDate\": {\n          \"@id\": \"cpsc:LastPublishDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"products\": \"cpsc:Products\",\n        \"images\": \"cpsc:Images\",\n        \"injuries\"\
  : \"cpsc:Injuries\",\n        \"manufacturers\": \"cpsc:Manufacturers\",\n        \"retailers\": \"cpsc:Retailers\",\n        \"importers\": \"cpsc:Importers\",\n        \"distributors\": \"cpsc:Distributors\",\n        \"manufacturerCountries\": \"cpsc:ManufacturerCountries\",\n        \"hazards\": \"cpsc:Hazards\",\n        \"remedies\": \"cpsc:Remedies\",\n        \"remedyOptions\": \"cpsc:RemedyOptions\"\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"cpsc:Product\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"model\": \"cpsc:Model\",\n        \"type\": \"cpsc:Type\",\n        \"categoryID\": \"cpsc:CategoryID\",\n        \"numberOfUnits\": \"cpsc:NumberOfUnits\"\n      }\n    },\n\n    \"Hazard\": {\n      \"@id\": \"cpsc:Hazard\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"hazardType\": \"cpsc:HazardType\",\n        \"hazardTypeID\": \"cpsc:HazardTypeID\"\n      }\n   \
  \ }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/consumer-product-safety-commission/refs/heads/main/json-ld/consumer-product-safety-commission-context.jsonld
tags:
- Consumer Protection
- Federal Government
- Hazards
- Open Data
- Product Safety
- Recalls
- JSON-LD
- Linked Data
- Semantic Web
---
