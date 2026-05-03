---
class_count: 10
classes:
- name
- description
- url
- SoftwareApplication
- SoftwareSourceCode
- TechArticle
- Tags
- Documentation
- License
- Repository
context_file: json-ld/templates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/templates/refs/heads/main/json-ld/templates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Templates from Templates.
layout: jsonld
name: Templates Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: templates
  uri: https://api-evangelist.com/topics/templates/
properties:
- container: ''
  name: template
  type: reference
- container: ''
  name: templateEngine
  type: reference
- container: ''
  name: templateSyntax
  type: schema:Text
- container: ''
  name: targetLanguage
  type: schema:Text
- container: ''
  name: codeGenerator
  type: reference
- container: ''
  name: scaffoldingTool
  type: reference
- container: ''
  name: templateVariable
  type: schema:Text
- container: ''
  name: outputFormat
  type: schema:Text
property_count: 8
provider_name: Templates
provider_slug: templates
slug: templates-context
source_filename: templates-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"templates\": \"https://api-evangelist.com/topics/templates/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"TechArticle\": \"schema:TechArticle\",\n    \"template\": {\n      \"@id\": \"templates:template\",\n      \"@type\": \"@id\"\n    },\n    \"templateEngine\": {\n      \"@id\": \"templates:templateEngine\",\n      \"@type\": \"@id\"\n    },\n    \"templateSyntax\": {\n      \"@id\": \"templates:templateSyntax\",\n      \"@type\": \"schema:Text\"\n    },\n    \"targetLanguage\": {\n      \"@id\": \"templates:targetLanguage\",\n      \"@type\": \"schema:Text\"\n    },\n    \"codeGenerator\": {\n      \"@id\": \"templates:codeGenerator\",\n      \"@type\": \"@id\"\n    },\n    \"scaffoldingTool\"\
  : {\n      \"@id\": \"templates:scaffoldingTool\",\n      \"@type\": \"@id\"\n    },\n    \"templateVariable\": {\n      \"@id\": \"templates:templateVariable\",\n      \"@type\": \"schema:Text\"\n    },\n    \"outputFormat\": {\n      \"@id\": \"templates:outputFormat\",\n      \"@type\": \"schema:Text\"\n    },\n    \"Tags\": \"schema:keywords\",\n    \"Documentation\": \"schema:documentation\",\n    \"License\": \"schema:license\",\n    \"Repository\": \"schema:codeRepository\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/templates/refs/heads/main/json-ld/templates-context.jsonld
tags:
- Templates
- API Design
- Code Generation
- Documentation
- OpenAPI
- AsyncAPI
- JSON-LD
- Linked Data
- Semantic Web
---
