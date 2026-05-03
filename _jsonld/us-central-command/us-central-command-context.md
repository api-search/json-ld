---
class_count: 1
classes:
- GovernmentOrganization
context_file: json-ld/us-central-command-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-central-command/refs/heads/main/json-ld/us-central-command-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Central Command from US Central Command.
layout: jsonld
name: Us Central Command Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: mil
  uri: https://www.centcom.mil/
properties:
- container: ''
  name: MilitaryCommand
  type: reference
- container: ''
  name: PressRelease
  type: reference
- container: ''
  name: MilitaryOperation
  type: reference
- container: ''
  name: commandName
  type: string
- container: ''
  name: areaOfResponsibility
  type: string
- container: ''
  name: headquarters
  type: reference
- container: ''
  name: commanderName
  type: string
- container: ''
  name: releaseDate
  type: date
- container: ''
  name: releaseTitle
  type: string
- container: ''
  name: releaseBody
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: partnerNation
  type: reference
- container: ''
  name: publisher
  type: reference
- container: ''
  name: description
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: modified
  type: date
property_count: 17
provider_name: US Central Command
provider_slug: us-central-command
slug: us-central-command-context
source_filename: us-central-command-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"mil\": \"https://www.centcom.mil/\",\n\n    \"MilitaryCommand\": {\n      \"@id\": \"schema:GovernmentOrganization\",\n      \"@type\": \"@id\"\n    },\n    \"PressRelease\": {\n      \"@id\": \"schema:NewsArticle\",\n      \"@type\": \"@id\"\n    },\n    \"MilitaryOperation\": {\n      \"@id\": \"schema:Event\",\n      \"@type\": \"@id\"\n    },\n\n    \"commandName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"areaOfResponsibility\": {\n      \"@id\": \"schema:areaServed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headquarters\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"@id\"\n    },\n    \"commanderName\": {\n      \"@id\": \"schema:employee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"releaseDate\": {\n      \"\
  @id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"releaseTitle\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"releaseBody\": {\n      \"@id\": \"schema:articleBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"schema:areaServed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerNation\": {\n      \"@id\": \"schema:affiliation\",\n      \"@type\": \"@id\"\n    },\n\n    \"GovernmentOrganization\": \"schema:GovernmentOrganization\",\n    \"publisher\": {\n      \"@id\": \"dct:publisher\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"@id\": \"dct:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"dct:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modified\": {\n      \"@id\": \"dct:modified\",\n      \"\
  @type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-central-command/refs/heads/main/json-ld/us-central-command-context.jsonld
tags:
- Federal Government
- Military
- Department of Defense
- National Security
- JSON-LD
- Linked Data
- Semantic Web
---
