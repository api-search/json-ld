---
class_count: 0
classes: []
context_file: json-ld/state-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-state/refs/heads/main/json-ld/state-context.jsonld
description: JSON-LD context defining the semantic vocabulary for State from Department of State.
layout: jsonld
name: State Context
namespaces:
- prefix: state
  uri: https://api-evangelist.com/department-of-state/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: TravelAdvisory
  type: ''
- container: ''
  name: Embassy
  type: ''
- container: ''
  name: Visa
  type: ''
- container: ''
  name: Passport
  type: ''
- container: ''
  name: CountryInformation
  type: ''
property_count: 5
provider_name: Department of State
provider_slug: department-of-state
slug: state-context
source_filename: state-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"state\": \"https://api-evangelist.com/department-of-state/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"TravelAdvisory\": {\n      \"@id\": \"state:TravelAdvisory\",\n      \"@context\": {\n        \"country\": \"schema:addressCountry\",\n        \"title\": \"schema:name\",\n        \"advisoryLevel\": { \"@id\": \"state:advisoryLevel\", \"@type\": \"xsd:integer\" },\n        \"description\": \"schema:description\",\n        \"publishedDate\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:date\" },\n        \"lastUpdated\": { \"@id\": \"dcterms:modified\", \"@type\": \"xsd:dateTime\" },\n        \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" }\n      }\n    },\n    \"Embassy\": {\n      \"@id\": \"state:Embassy\",\n      \"@context\"\
  : {\n        \"name\": \"schema:name\",\n        \"country\": \"schema:addressCountry\",\n        \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n        \"telephone\": \"schema:telephone\",\n        \"address\": \"schema:address\",\n        \"lat\": { \"@id\": \"geo:lat\", \"@type\": \"xsd:decimal\" },\n        \"long\": { \"@id\": \"geo:long\", \"@type\": \"xsd:decimal\" }\n      }\n    },\n    \"Visa\": {\n      \"@id\": \"state:Visa\",\n      \"@context\": {\n        \"category\": \"state:visaCategory\",\n        \"description\": \"schema:description\",\n        \"purpose\": \"state:visaPurpose\"\n      }\n    },\n    \"Passport\": {\n      \"@id\": \"state:Passport\",\n      \"@context\": {\n        \"type\": \"state:passportType\",\n        \"fee\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n        \"processingTime\": \"state:processingTime\"\n      }\n    },\n    \"CountryInformation\": {\n      \"@id\": \"state:CountryInformation\",\n      \"@context\"\
  : {\n        \"country\": \"schema:addressCountry\",\n        \"summary\": \"schema:description\",\n        \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-state/refs/heads/main/json-ld/state-context.jsonld
tags:
- Federal Government
- Foreign Affairs
- Travel
- Consular
- Visas
- Passports
- JSON-LD
- Linked Data
- Semantic Web
---
