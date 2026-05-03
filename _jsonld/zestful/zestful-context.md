---
api_specs:
- filename: zestful-openapi.yml
  format: yaml
  label: Zestful Ingredient Parser API
  slug: zestful
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/openapi/zestful-openapi.yml
class_count: 0
classes: []
context_file: json-ld/zestful-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/json-ld/zestful-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zestful from Zestful.
layout: jsonld
name: Zestful Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: zestful
  uri: https://zestfuldata.com/vocab#
- prefix: usda
  uri: https://fdc.nal.usda.gov/vocab#
properties:
- container: ''
  name: ingredientRaw
  type: schema:Text
- container: ''
  name: ingredientParsed
  type: reference
- container: ''
  name: quantity
  type: schema:Number
- container: ''
  name: unit
  type: schema:Text
- container: ''
  name: productSizeModifier
  type: schema:Text
- container: ''
  name: product
  type: schema:Text
- container: ''
  name: preparationNotes
  type: schema:Text
- container: ''
  name: confidence
  type: schema:Number
- container: ''
  name: usdaInfo
  type: reference
- container: ''
  name: fdcId
  type: schema:Text
- container: ''
  name: matchMethod
  type: schema:Text
- container: ''
  name: category
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: list
  name: results
  type: ''
- container: ''
  name: requestsRemaining
  type: schema:Integer
property_count: 15
provider_name: Zestful
provider_slug: zestful
slug: zestful-context
source_filename: zestful-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"zestful\": \"https://zestfuldata.com/vocab#\",\n    \"usda\": \"https://fdc.nal.usda.gov/vocab#\",\n\n    \"ingredientRaw\": {\n      \"@id\": \"zestful:ingredientRaw\",\n      \"@type\": \"schema:Text\"\n    },\n    \"ingredientParsed\": {\n      \"@id\": \"zestful:ingredientParsed\",\n      \"@type\": \"@id\"\n    },\n    \"quantity\": {\n      \"@id\": \"schema:quantity\",\n      \"@type\": \"schema:Number\"\n    },\n    \"unit\": {\n      \"@id\": \"schema:unitText\",\n      \"@type\": \"schema:Text\"\n    },\n    \"productSizeModifier\": {\n      \"@id\": \"zestful:productSizeModifier\",\n      \"@type\": \"schema:Text\"\n    },\n    \"product\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"schema:Text\"\n    },\n    \"preparationNotes\": {\n      \"@id\": \"zestful:preparationNotes\",\n      \"@type\": \"schema:Text\"\n    },\n    \"confidence\": {\n      \"@id\": \"\
  zestful:confidence\",\n      \"@type\": \"schema:Number\"\n    },\n    \"usdaInfo\": {\n      \"@id\": \"usda:foodMatch\",\n      \"@type\": \"@id\"\n    },\n    \"fdcId\": {\n      \"@id\": \"usda:fdcId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"matchMethod\": {\n      \"@id\": \"usda:matchMethod\",\n      \"@type\": \"schema:Text\"\n    },\n    \"category\": {\n      \"@id\": \"schema:category\",\n      \"@type\": \"schema:Text\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"schema:Text\"\n    },\n    \"results\": {\n      \"@id\": \"zestful:results\",\n      \"@container\": \"@list\"\n    },\n    \"requestsRemaining\": {\n      \"@id\": \"zestful:requestsRemaining\",\n      \"@type\": \"schema:Integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zestful/refs/heads/main/json-ld/zestful-context.jsonld
tags:
- Food
- Ingredients
- Parsers
- Recipes
- USDA
- JSON-LD
- Linked Data
- Semantic Web
---
