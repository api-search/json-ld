---
api_specs:
- filename: meddra-terminology-openapi.yml
  format: yaml
  label: MedDRA / WHO Drug Dictionary API
  slug: meddra-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/openapi/meddra-terminology-openapi.yml
class_count: 2
classes:
- MedDRATerm
- termText
context_file: json-ld/meddra-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/json-ld/meddra-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Meddra from meddra.
layout: jsonld
name: Meddra Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: meddra
  uri: https://www.meddra.org/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: code
  type: integer
- container: ''
  name: level
  type: string
- container: ''
  name: current
  type: boolean
- container: ''
  name: version
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: primarySOCCode
  type: integer
- container: ''
  name: primarySOCName
  type: string
- container: set
  name: allSOCLinks
  type: ''
- container: ''
  name: SOC
  type: skos:ConceptScheme
- container: ''
  name: HLGT
  type: skos:Concept
- container: ''
  name: HLT
  type: skos:Concept
- container: ''
  name: PT
  type: skos:Concept
- container: ''
  name: LLT
  type: skos:Concept
property_count: 13
provider_name: meddra
provider_slug: meddra
slug: meddra-context
source_filename: meddra-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"meddra\": \"https://www.meddra.org/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"MedDRATerm\": \"skos:Concept\",\n    \"code\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"termText\": \"skos:prefLabel\",\n    \"level\": {\n      \"@id\": \"meddra:hierarchyLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"current\": {\n      \"@id\": \"schema:activeStatus\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"schema:inLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primarySOCCode\": {\n      \"@id\": \"skos:broader\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"primarySOCName\": {\n      \"@id\": \"meddra:primarySOCName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"allSOCLinks\": {\n      \"@id\": \"skos:broaderTransitive\",\n      \"@container\": \"@set\"\n    },\n    \"SOC\": {\n      \"@id\": \"meddra:SystemOrganClass\",\n      \"@type\": \"skos:ConceptScheme\"\n    },\n    \"HLGT\": {\n      \"@id\": \"meddra:HighLevelGroupTerm\",\n      \"@type\": \"skos:Concept\"\n    },\n    \"HLT\": {\n      \"@id\": \"meddra:HighLevelTerm\",\n      \"@type\": \"skos:Concept\"\n    },\n    \"PT\": {\n      \"@id\": \"meddra:PreferredTerm\",\n      \"@type\": \"skos:Concept\"\n    },\n    \"LLT\": {\n      \"@id\": \"meddra:LowestLevelTerm\",\n      \"@type\": \"skos:Concept\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/meddra/refs/heads/main/json-ld/meddra-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
