---
api_specs:
- filename: vlex-iceberg-anonymization-openapi.yml
  format: yaml
  label: vLex Iceberg Anonymization API
  slug: iceberg-anonymization-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/openapi/vlex-iceberg-anonymization-openapi.yml
- filename: vlex-iceberg-legal-research-openapi.yml
  format: yaml
  label: vLex Iceberg Legal Research API
  slug: iceberg-legal-research-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/openapi/vlex-iceberg-legal-research-openapi.yml
class_count: 11
classes:
- LegalDocument
- CaseLaw
- Statute
- Regulation
- Citation
- Entity
- Classification
- KeyPhrase
- LegalCase
- Legislation
- GovernmentPermit
context_file: json-ld/vlex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/json-ld/vlex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vlex from vLex.
layout: jsonld
name: Vlex Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: vlex
  uri: https://vlex.com/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: title
  type: ''
- container: ''
  name: document_type
  type: string
- container: ''
  name: jurisdiction
  type: string
- container: ''
  name: language
  type: ''
- container: ''
  name: full_text
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: raw_text
  type: string
- container: ''
  name: citation_type
  type: string
- container: ''
  name: year
  type: integer
- container: ''
  name: entity_type
  type: string
- container: ''
  name: confidence
  type: float
- container: ''
  name: start_offset
  type: integer
- container: ''
  name: end_offset
  type: integer
- container: list
  name: practice_areas
  type: ''
- container: list
  name: key_phrases
  type: ''
- container: list
  name: citations
  type: ''
- container: ''
  name: phrase
  type: string
- container: ''
  name: score
  type: float
- container: ''
  name: label
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: url
  type: reference
property_count: 23
provider_name: vLex
provider_slug: vlex
slug: vlex-context
source_filename: vlex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"vlex\": \"https://vlex.com/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"LegalDocument\": \"vlex:LegalDocument\",\n    \"CaseLaw\": \"vlex:CaseLaw\",\n    \"Statute\": \"vlex:Statute\",\n    \"Regulation\": \"vlex:Regulation\",\n    \"Citation\": \"vlex:Citation\",\n    \"Entity\": \"vlex:Entity\",\n    \"Classification\": \"vlex:Classification\",\n    \"KeyPhrase\": \"vlex:KeyPhrase\",\n\n    \"id\": {\"@id\": \"@id\"},\n    \"title\": {\"@id\": \"dct:title\"},\n    \"document_type\": {\"@id\": \"vlex:documentType\", \"@type\": \"xsd:string\"},\n    \"jurisdiction\": {\"@id\": \"vlex:jurisdiction\", \"@type\": \"xsd:string\"},\n    \"language\": {\"@id\": \"dct:language\"},\n    \"full_text\": {\"@id\": \"vlex:fullText\", \"@type\": \"xsd:string\"},\n    \"date\": {\"@id\": \"dct:date\", \"@type\": \"xsd:date\"\
  },\n\n    \"raw_text\": {\"@id\": \"vlex:rawText\", \"@type\": \"xsd:string\"},\n    \"citation_type\": {\"@id\": \"vlex:citationType\", \"@type\": \"xsd:string\"},\n    \"year\": {\"@id\": \"vlex:year\", \"@type\": \"xsd:integer\"},\n\n    \"entity_type\": {\"@id\": \"vlex:entityType\", \"@type\": \"xsd:string\"},\n    \"confidence\": {\"@id\": \"vlex:confidence\", \"@type\": \"xsd:float\"},\n    \"start_offset\": {\"@id\": \"vlex:startOffset\", \"@type\": \"xsd:integer\"},\n    \"end_offset\": {\"@id\": \"vlex:endOffset\", \"@type\": \"xsd:integer\"},\n\n    \"practice_areas\": {\"@id\": \"vlex:practiceAreas\", \"@container\": \"@list\"},\n    \"key_phrases\": {\"@id\": \"vlex:keyPhrases\", \"@container\": \"@list\"},\n    \"citations\": {\"@id\": \"vlex:citations\", \"@container\": \"@list\"},\n\n    \"phrase\": {\"@id\": \"vlex:phrase\", \"@type\": \"xsd:string\"},\n    \"score\": {\"@id\": \"vlex:score\", \"@type\": \"xsd:float\"},\n    \"label\": {\"@id\": \"vlex:label\", \"@type\"\
  : \"xsd:string\"},\n\n    \"name\": {\"@id\": \"schema:name\"},\n    \"description\": {\"@id\": \"schema:description\"},\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n\n    \"LegalCase\": \"schema:LegalCase\",\n    \"Legislation\": \"schema:Legislation\",\n    \"GovernmentPermit\": \"schema:GovernmentPermit\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/json-ld/vlex-context.jsonld
tags:
- AI
- Classification
- Legal Research
- Legal Tech
- Natural Language Processing
- Privacy
- JSON-LD
- Linked Data
- Semantic Web
---
