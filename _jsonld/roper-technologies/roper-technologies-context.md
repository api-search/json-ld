---
class_count: 0
classes: []
context_file: json-ld/roper-technologies-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roper-technologies/refs/heads/main/json-ld/roper-technologies-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roper Technologies from Roper Technologies.
layout: jsonld
name: Roper Technologies Context
namespaces:
- prefix: roper
  uri: https://www.ropertech.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: RoperTechnologies
  type: schema:Corporation
- container: ''
  name: Subsidiary
  type: schema:Organization
- container: ''
  name: SoftwareProduct
  type: schema:SoftwareApplication
- container: ''
  name: BusinessSegment
  type: ''
property_count: 4
provider_name: Roper Technologies
provider_slug: roper-technologies
slug: roper-technologies-context
source_filename: roper-technologies-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"roper\": \"https://www.ropertech.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"RoperTechnologies\": {\n      \"@id\": \"roper:RoperTechnologies\",\n      \"@type\": \"schema:Corporation\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"url\": { \"@id\": \"schema:url\" },\n        \"tickerSymbol\": { \"@id\": \"schema:tickerSymbol\" },\n        \"exchange\": { \"@id\": \"schema:exchange\" },\n        \"subsidiaries\": { \"@id\": \"schema:subOrganization\" },\n        \"numberOfEmployees\": { \"@id\": \"schema:numberOfEmployees\" }\n      }\n    },\n\n    \"Subsidiary\": {\n      \"@id\": \"roper:Subsidiary\",\n      \"@type\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\"\
  \ },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"url\": { \"@id\": \"schema:url\" },\n        \"industry\": { \"@id\": \"schema:industry\" },\n        \"segment\": { \"@id\": \"roper:segment\" },\n        \"parentOrganization\": { \"@id\": \"schema:parentOrganization\" }\n      }\n    },\n\n    \"SoftwareProduct\": {\n      \"@id\": \"roper:SoftwareProduct\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"applicationCategory\": { \"@id\": \"schema:applicationCategory\" },\n        \"operatingSystem\": { \"@id\": \"schema:operatingSystem\" },\n        \"publisher\": { \"@id\": \"schema:publisher\" },\n        \"url\": { \"@id\": \"schema:url\" }\n      }\n    },\n\n    \"BusinessSegment\": {\n      \"@id\": \"roper:BusinessSegment\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n    \
  \    \"description\": { \"@id\": \"schema:description\" },\n        \"revenuePercentage\": { \"@id\": \"roper:revenuePercentage\" }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roper-technologies/refs/heads/main/json-ld/roper-technologies-context.jsonld
tags:
- B2B Software
- Enterprise Software
- Fortune 500
- Healthcare IT
- Insurance Technology
- Legal Technology
- SaaS
- Vertical Software
- JSON-LD
- Linked Data
- Semantic Web
---
