---
api_specs:
- filename: wikidata-mediawiki-openapi.yml
  format: yaml
  label: Wikibase REST API
  slug: wikibase-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/openapi/wikidata-mediawiki-openapi.yml
class_count: 10
classes:
- Property
- Item
- Sitelink
- ItemCreate
- Statement
- StatementCreate
- DataValue
- Wikidata Entity
- PatchRequest
- url
context_file: json-ld/wikidata-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/json-ld/wikidata-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wikidata from Wikidata.
layout: jsonld
name: Wikidata Context
namespaces:
- prefix: wd
  uri: http://www.wikidata.org/entity/
- prefix: wdt
  uri: http://www.wikidata.org/prop/direct/
- prefix: wikibase
  uri: http://wikiba.se/ontology#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: datatype
  type: string
- container: ''
  name: labels
  type: reference
- container: ''
  name: descriptions
  type: reference
- container: ''
  name: aliases
  type: reference
- container: ''
  name: statements
  type: reference
- container: ''
  name: sitelinks
  type: reference
- container: ''
  name: title
  type: string
- container: set
  name: badges
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: bot
  type: boolean
- container: ''
  name: rank
  type: string
- container: ''
  name: property
  type: reference
- container: set
  name: qualifiers
  type: reference
- container: set
  name: references
  type: reference
- container: ''
  name: hash
  type: string
- container: set
  name: parts
  type: reference
- container: ''
  name: content
  type: string
- container: ''
  name: lastrevid
  type: integer
- container: ''
  name: modified
  type: dateTime
- container: set
  name: patch
  type: reference
- container: ''
  name: op
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: from
  type: string
- container: set
  name: tags
  type: string
property_count: 27
provider_name: Wikidata
provider_slug: wikidata
slug: wikidata-context
source_filename: wikidata-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wd\": \"http://www.wikidata.org/entity/\",\n    \"wdt\": \"http://www.wikidata.org/prop/direct/\",\n    \"wikibase\": \"http://wikiba.se/ontology#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"Property\": \"wikibase:Property\",\n    \"Item\": \"wikibase:Item\",\n    \"Sitelink\": \"wikibase:Sitelink\",\n    \"ItemCreate\": \"wikibase:ItemCreate\",\n    \"Statement\": \"wikibase:Statement\",\n    \"StatementCreate\": \"wikibase:StatementCreate\",\n    \"DataValue\": \"wikibase:DataValue\",\n    \"Wikidata Entity\": \"wikibase:Wikidata Entity\",\n    \"PatchRequest\": \"wikibase:PatchRequest\",\n    \"id\": {\n      \"@id\": \"wd:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"wd:type\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"datatype\": {\n      \"@id\": \"wd:datatype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labels\": {\n      \"@id\": \"wd:labels\",\n      \"@type\": \"@id\"\n    },\n    \"descriptions\": {\n      \"@id\": \"wd:descriptions\",\n      \"@type\": \"@id\"\n    },\n    \"aliases\": {\n      \"@id\": \"wd:aliases\",\n      \"@type\": \"@id\"\n    },\n    \"statements\": {\n      \"@id\": \"wd:statements\",\n      \"@type\": \"@id\"\n    },\n    \"sitelinks\": {\n      \"@id\": \"wd:sitelinks\",\n      \"@type\": \"@id\"\n    },\n    \"title\": {\n      \"@id\": \"wd:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"badges\": {\n      \"@id\": \"wd:badges\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"wd:comment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bot\": {\n      \"@id\": \"wd:bot\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rank\": {\n      \"@id\": \"\
  wd:rank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"property\": {\n      \"@id\": \"wd:property\",\n      \"@type\": \"@id\"\n    },\n    \"qualifiers\": {\n      \"@id\": \"wd:qualifiers\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"references\": {\n      \"@id\": \"wd:references\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"hash\": {\n      \"@id\": \"wd:hash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parts\": {\n      \"@id\": \"wd:parts\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"content\": {\n      \"@id\": \"wd:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastrevid\": {\n      \"@id\": \"wd:lastrevid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modified\": {\n      \"@id\": \"wd:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"patch\": {\n      \"@id\": \"wd:patch\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n   \
  \ \"op\": {\n      \"@id\": \"wd:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"wd:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"wd:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"wd:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"wd:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wikidata/refs/heads/main/json-ld/wikidata-context.jsonld
tags:
- Knowledge Graph
- Linked Data
- Open Data
- Semantic Web
- SPARQL
- Wikipedia
- JSON-LD
- Linked Data
- Semantic Web
---
