---
class_count: 15
classes:
- WebStandard
- Specification
- StandardsBody
- WorkingGroup
- LivingStandard
- WebAPI
- name
- description
- url
- version
- dateCreated
- dateModified
- identifier
- label
- definition
context_file: json-ld/web-standards-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/web-standards/refs/heads/main/json-ld/web-standards-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Web Standards from Web Standards.
layout: jsonld
name: Web Standards Context
namespaces:
- prefix: ws
  uri: https://webstandards.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: specificationUrl
  type: reference
- container: ''
  name: repositoryUrl
  type: reference
- container: ''
  name: standardsBodyUrl
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: maturityLevel
  type: string
- container: ''
  name: publishedYear
  type: integer
- container: ''
  name: browserSupport
  type: string
- container: ''
  name: category
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: relatedStandards
  type: reference
- container: set
  name: implementations
  type: string
- container: set
  name: editors
  type: string
- container: ''
  name: workingGroup
  type: string
- container: ''
  name: standardsBody
  type: string
property_count: 14
provider_name: Web Standards
provider_slug: web-standards
slug: web-standards-context
source_filename: web-standards-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ws\": \"https://webstandards.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"WebStandard\": \"ws:WebStandard\",\n    \"Specification\": \"ws:Specification\",\n    \"StandardsBody\": \"ws:StandardsBody\",\n    \"WorkingGroup\": \"ws:WorkingGroup\",\n    \"LivingStandard\": \"ws:LivingStandard\",\n    \"WebAPI\": \"ws:WebAPI\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"identifier\": \"dcterms:identifier\",\n    \"label\": \"skos:prefLabel\",\n    \"definition\": \"skos:definition\",\n\n    \"specificationUrl\": {\n      \"@id\": \"ws:specification_url\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"repositoryUrl\": {\n      \"@id\": \"ws:repository_url\",\n      \"@type\": \"@id\"\n    },\n    \"standardsBodyUrl\": {\n      \"@id\": \"ws:standards_body_url\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"ws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maturityLevel\": {\n      \"@id\": \"ws:maturity_level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publishedYear\": {\n      \"@id\": \"ws:published_year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"browserSupport\": {\n      \"@id\": \"ws:browser_support\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"ws:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"ws:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedStandards\": {\n      \"@id\": \"ws:related_standards\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n\
  \    },\n    \"implementations\": {\n      \"@id\": \"ws:implementations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"editors\": {\n      \"@id\": \"ws:editors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workingGroup\": {\n      \"@id\": \"ws:working_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standardsBody\": {\n      \"@id\": \"ws:standards_body\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/web-standards/refs/heads/main/json-ld/web-standards-context.jsonld
tags:
- Browser Compatibility
- CSS
- HTML
- Interoperability
- JavaScript
- Standards
- Web APIs
- Web Development
- JSON-LD
- Linked Data
- Semantic Web
---
