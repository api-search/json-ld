---
api_specs:
- filename: princess-beef-heavy-industries-giftshop-openapi.yml
  format: yaml
  label: Pb33f Giftshop API
  slug: giftshop-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/princess-beef-heavy-industries/refs/heads/main/openapi/princess-beef-heavy-industries-giftshop-openapi.yml
class_count: 0
classes: []
context_file: json-ld/princess-beef-heavy-industries-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/princess-beef-heavy-industries/refs/heads/main/json-ld/princess-beef-heavy-industries-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Princess Beef Heavy Industries from Princess Beef Heavy Industries.
layout: jsonld
name: Princess Beef Heavy Industries Context
namespaces:
- prefix: pb33f
  uri: https://pb33f.io/wiretap/giftshop-api/
properties:
- container: ''
  name: Product
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 2
provider_name: Princess Beef Heavy Industries
provider_slug: princess-beef-heavy-industries
slug: princess-beef-heavy-industries-context
source_filename: princess-beef-heavy-industries-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"pb33f\": \"https://pb33f.io/wiretap/giftshop-api/\",\n    \"Product\": {\n      \"@id\": \"pb33f:Product\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"shortCode\": \"https://schema.org/sku\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"price\": \"https://schema.org/price\",\n        \"category\": \"https://schema.org/category\",\n        \"image\": \"https://schema.org/image\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"pb33f:Error\",\n      \"@context\": {\n        \"type\": \"https://schema.org/url\",\n        \"title\": \"https://schema.org/name\",\n        \"status\": \"https://schema.org/httpStatusCode\",\n        \"detail\": \"https://schema.org/description\",\n        \"instance\": \"https://schema.org/url\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/princess-beef-heavy-industries/refs/heads/main/json-ld/princess-beef-heavy-industries-context.jsonld
tags:
- Commerce
- Documentation
- Editors
- Governance
- Platform
- Products
- Rules
- JSON-LD
- Linked Data
- Semantic Web
---
