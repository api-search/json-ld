---
class_count: 0
classes: []
context_file: json-ld/cheerio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cheerio/refs/heads/main/json-ld/cheerio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cheerio from Cheerio.
layout: jsonld
name: Cheerio Context
namespaces:
- prefix: cheerio
  uri: https://cheerio.js.org/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: spdx
  uri: https://spdx.org/licenses/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: SoftwareLibrary
  type: ''
- container: ''
  name: ParsedDocument
  type: ''
- container: ''
  name: Selector
  type: ''
property_count: 3
provider_name: Cheerio
provider_slug: cheerio
slug: cheerio-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cheerio\": \"https://cheerio.js.org/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"spdx\": \"https://spdx.org/licenses/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"SoftwareLibrary\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"license\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"@id\"\n        },\n        \"version\": \"schema:softwareVersion\",\n        \"runtime\": \"cheerio:runtime\",\n        \"packageManager\": \"cheerio:packageManager\",\n        \"homepage\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"repository\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ParsedDocument\"\
  : {\n      \"@id\": \"cheerio:ParsedDocument\",\n      \"@context\": {\n        \"source\": \"cheerio:source\",\n        \"format\": \"cheerio:format\",\n        \"encoding\": \"cheerio:encoding\",\n        \"rootElement\": \"cheerio:rootElement\"\n      }\n    },\n\n    \"Selector\": {\n      \"@id\": \"cheerio:Selector\",\n      \"@context\": {\n        \"expression\": \"cheerio:expression\",\n        \"engine\": \"cheerio:engine\",\n        \"matchedCount\": {\n          \"@id\": \"cheerio:matchedCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cheerio/refs/heads/main/json-ld/cheerio-context.jsonld
tags:
- Data Extraction
- DOM
- HTML
- HTML Parsing
- jQuery
- MIT License
- Node.js
- npm
- Open Source
- Parser
- Scraping
- Server-side
- Web Scraping
- XML
- JSON-LD
- Linked Data
- Semantic Web
---
