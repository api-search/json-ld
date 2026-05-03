---
api_specs:
- filename: trefle-openapi.yml
  format: yaml
  label: Trefle API
  slug: trefle
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trefle/refs/heads/main/openapi/trefle-openapi.yml
class_count: 44
classes:
- id
- type
- Plant
- Species
- Kingdom
- Family
- Genus
- Distribution
- name
- description
- url
- image_url
- scientific_name
- common_name
- slug
- status
- rank
- family
- family_common_name
- genus
- genus_id
- synonyms
- edible
- edible_part
- vegetable
- distribution
- native
- introduced
- naturalised
- endemic
- growth
- light
- ph_minimum
- ph_maximum
- bloom_months
- fruit_months
- flower
- foliage
- specifications
- growth_habit
- toxicity
- tdwg_code
- tdwg_level
- species_count
context_file: json-ld/trefle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trefle/refs/heads/main/json-ld/trefle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trefle from Trefle.
layout: jsonld
name: Trefle Context
namespaces:
- prefix: trefle
  uri: https://trefle.io/ns/
- prefix: dwc
  uri: http://rs.tdwg.org/dwc/terms/
properties: []
property_count: 0
provider_name: Trefle
provider_slug: trefle
slug: trefle-context
source_filename: trefle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"trefle\": \"https://trefle.io/ns/\",\n    \"dwc\": \"http://rs.tdwg.org/dwc/terms/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Plant\": \"schema:Plant\",\n    \"Species\": \"dwc:Taxon\",\n    \"Kingdom\": \"dwc:Kingdom\",\n    \"Family\": \"dwc:Family\",\n    \"Genus\": \"dwc:Genus\",\n    \"Distribution\": \"trefle:Distribution\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"image_url\": \"schema:image\",\n    \"scientific_name\": \"dwc:scientificName\",\n    \"common_name\": \"dwc:vernacularName\",\n    \"slug\": \"trefle:slug\",\n    \"status\": \"dwc:taxonomicStatus\",\n    \"rank\": \"dwc:taxonRank\",\n    \"family\": \"dwc:family\",\n    \"family_common_name\": \"trefle:familyCommonName\",\n    \"genus\": \"dwc:genus\",\n    \"genus_id\": \"trefle:genusId\",\n    \"synonyms\": \"dwc:acceptedNameUsage\",\n    \"edible\"\
  : \"trefle:edible\",\n    \"edible_part\": \"trefle:ediblePart\",\n    \"vegetable\": \"trefle:vegetable\",\n    \"distribution\": \"trefle:distribution\",\n    \"native\": \"trefle:native\",\n    \"introduced\": \"trefle:introduced\",\n    \"naturalised\": \"trefle:naturalised\",\n    \"endemic\": \"trefle:endemic\",\n    \"growth\": \"trefle:growth\",\n    \"light\": \"trefle:light\",\n    \"ph_minimum\": \"trefle:phMinimum\",\n    \"ph_maximum\": \"trefle:phMaximum\",\n    \"bloom_months\": \"trefle:bloomMonths\",\n    \"fruit_months\": \"trefle:fruitMonths\",\n    \"flower\": \"trefle:flower\",\n    \"foliage\": \"trefle:foliage\",\n    \"specifications\": \"trefle:specifications\",\n    \"growth_habit\": \"trefle:growthHabit\",\n    \"toxicity\": \"trefle:toxicity\",\n    \"tdwg_code\": \"dwc:locationID\",\n    \"tdwg_level\": \"trefle:tdwgLevel\",\n    \"species_count\": \"trefle:speciesCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trefle/refs/heads/main/json-ld/trefle-context.jsonld
tags:
- Agriculture
- Botany
- Open Data
- Plants
- Science
- JSON-LD
- Linked Data
- Semantic Web
---
