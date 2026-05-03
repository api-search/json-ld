---
class_count: 0
classes: []
context_file: json-ld/w3c-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/w3c/refs/heads/main/json-ld/w3c-context.jsonld
description: JSON-LD context defining the semantic vocabulary for W3C from W3C.
layout: jsonld
name: W3C Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: w3c
  uri: https://www.w3.org/2001/01/owl-features#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: TechnicalReport
  type: reference
- container: ''
  name: Specification
  type: reference
- container: ''
  name: WorkingGroup
  type: reference
- container: ''
  name: shortname
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: date
  type: date
- container: ''
  name: latestVersion
  type: reference
- container: ''
  name: editors
  type: reference
- container: ''
  name: deliverers
  type: reference
- container: ''
  name: Editor
  type: reference
- container: ''
  name: name
  type: string
- container: ''
  name: affiliation
  type: reference
- container: ''
  name: W3CRecommendation
  type: ''
- container: ''
  name: WCAG
  type: schema:TechArticle
- container: ''
  name: JSONLD
  type: schema:TechArticle
- container: ''
  name: WebAssembly
  type: schema:TechArticle
- container: ''
  name: VerifiableCredential
  type: schema:TechArticle
property_count: 19
provider_name: W3C
provider_slug: w3c
slug: w3c-context
source_filename: w3c-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"w3c\": \"https://www.w3.org/2001/01/owl-features#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"TechnicalReport\": {\n      \"@id\": \"schema:TechArticle\",\n      \"@type\": \"@id\"\n    },\n\n    \"Specification\": {\n      \"@id\": \"schema:TechArticle\",\n      \"@type\": \"@id\"\n    },\n\n    \"WorkingGroup\": {\n      \"@id\": \"org:OrganizationalUnit\",\n      \"@type\": \"@id\"\n    },\n\n    \"shortname\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"status\": {\n      \"\
  @id\": \"schema:creativeWorkStatus\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"date\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"latestVersion\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n\n    \"editors\": {\n      \"@id\": \"schema:editor\",\n      \"@type\": \"@id\"\n    },\n\n    \"deliverers\": {\n      \"@id\": \"schema:contributor\",\n      \"@type\": \"@id\"\n    },\n\n    \"Editor\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"affiliation\": {\n      \"@id\": \"schema:affiliation\",\n      \"@type\": \"@id\"\n    },\n\n    \"W3CRecommendation\": {\n      \"@id\": \"schema:TechArticle\"\n    },\n\n    \"WCAG\": {\n      \"@id\": \"w3c:WCAG\",\n      \"@type\": \"schema:TechArticle\"\n    },\n\n    \"JSONLD\": {\n      \"@id\": \"w3c:JSONLD\",\n      \"@type\": \"schema:TechArticle\"\
  \n    },\n\n    \"WebAssembly\": {\n      \"@id\": \"w3c:WebAssembly\",\n      \"@type\": \"schema:TechArticle\"\n    },\n\n    \"VerifiableCredential\": {\n      \"@id\": \"w3c:VerifiableCredential\",\n      \"@type\": \"schema:TechArticle\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/w3c/refs/heads/main/json-ld/w3c-context.jsonld
tags:
- Accessibility
- Standards
- Web
- Web Standards
- JSON-LD
- Linked Data
- Semantic Web
---
