---
api_specs:
- filename: linguatools-collocations-openapi.yml
  format: yaml
  label: Linguatools Collocations API
  slug: collocations
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linguatools/refs/heads/main/openapi/linguatools-collocations-openapi.yml
class_count: 6
classes:
- Collocation
- basis
- collocate
- relation
- language
- partOfSpeech
context_file: json-ld/linguatools-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/linguatools/refs/heads/main/json-ld/linguatools-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Linguatools from Linguatools.
layout: jsonld
name: Linguatools Context
namespaces:
- prefix: linguatools
  uri: https://linguatools.org/ns#
properties:
- container: ''
  name: significance
  type: decimal
- container: list
  name: examples
  type: ''
property_count: 2
provider_name: Linguatools
provider_slug: linguatools
slug: linguatools-context
source_filename: linguatools-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"linguatools\": \"https://linguatools.org/ns#\",\n    \"Collocation\": \"linguatools:Collocation\",\n    \"basis\": \"linguatools:basis\",\n    \"collocate\": \"linguatools:collocate\",\n    \"relation\": \"linguatools:relation\",\n    \"significance\": {\n      \"@id\": \"linguatools:significance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"examples\": {\n      \"@id\": \"linguatools:examples\",\n      \"@container\": \"@list\"\n    },\n    \"language\": \"linguatools:language\",\n    \"partOfSpeech\": \"linguatools:partOfSpeech\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/linguatools/refs/heads/main/json-ld/linguatools-context.jsonld
tags:
- Collocations
- Dictionary
- English
- Language
- Linguistics
- NLP
- JSON-LD
- Linked Data
- Semantic Web
---
