---
class_count: 0
classes: []
context_file: json-ld/redoc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/redoc/refs/heads/main/json-ld/redoc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Redoc from ReDoc.
layout: jsonld
name: Redoc Context
namespaces:
- prefix: redoc
  uri: https://redocly.com/redoc/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ApiDocumentation
  type: ''
- container: ''
  name: OpenAPISpec
  type: ''
- container: ''
  name: ThemeConfiguration
  type: ''
- container: ''
  name: TagGroup
  type: ''
- container: ''
  name: CodeSample
  type: ''
- container: ''
  name: LogoObject
  type: ''
- container: ''
  name: OperationBadge
  type: ''
- container: ''
  name: ServerObject
  type: ''
property_count: 8
provider_name: ReDoc
provider_slug: redoc
slug: redoc-context
source_filename: redoc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"redoc\": \"https://redocly.com/redoc/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ApiDocumentation\": {\n      \"@id\": \"redoc:ApiDocumentation\",\n      \"@context\": {\n        \"specUrl\": {\n          \"@id\": \"redoc:specUrl\",\n          \"@type\": \"@id\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"version\": {\n          \"@id\": \"schema:version\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"theme\": {\n          \"@id\": \"redoc:theme\"\n        },\n     \
  \   \"options\": {\n          \"@id\": \"redoc:options\"\n        }\n      }\n    },\n\n    \"OpenAPISpec\": {\n      \"@id\": \"redoc:OpenAPISpec\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"version\": {\n          \"@id\": \"schema:version\"\n        },\n        \"specVersion\": {\n          \"@id\": \"redoc:specVersion\"\n        },\n        \"servers\": {\n          \"@id\": \"redoc:servers\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"redoc:tags\",\n          \"@container\": \"@set\"\n        },\n        \"paths\": {\n          \"@id\": \"redoc:paths\",\n          \"@container\": \"@set\"\n        },\n        \"components\": {\n          \"@id\": \"redoc:components\"\n        }\n      }\n   \
  \ },\n\n    \"ThemeConfiguration\": {\n      \"@id\": \"redoc:ThemeConfiguration\",\n      \"@context\": {\n        \"spacing\": {\n          \"@id\": \"redoc:spacing\"\n        },\n        \"colors\": {\n          \"@id\": \"redoc:colors\"\n        },\n        \"typography\": {\n          \"@id\": \"redoc:typography\"\n        },\n        \"sidebar\": {\n          \"@id\": \"redoc:sidebar\"\n        },\n        \"rightPanel\": {\n          \"@id\": \"redoc:rightPanel\"\n        },\n        \"logo\": {\n          \"@id\": \"redoc:logo\"\n        }\n      }\n    },\n\n    \"TagGroup\": {\n      \"@id\": \"redoc:TagGroup\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"tags\": {\n          \"@id\": \"redoc:tags\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"CodeSample\": {\n      \"@id\": \"redoc:CodeSample\",\n      \"@context\": {\n        \"lang\": {\n          \"@id\": \"redoc:lang\"\n        },\n \
  \       \"label\": {\n          \"@id\": \"schema:name\"\n        },\n        \"source\": {\n          \"@id\": \"redoc:source\"\n        }\n      }\n    },\n\n    \"LogoObject\": {\n      \"@id\": \"redoc:LogoObject\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"backgroundColor\": {\n          \"@id\": \"redoc:backgroundColor\"\n        },\n        \"altText\": {\n          \"@id\": \"schema:alternateName\"\n        },\n        \"href\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"OperationBadge\": {\n      \"@id\": \"redoc:OperationBadge\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"color\": {\n          \"@id\": \"redoc:color\"\n        }\n      }\n    },\n\n    \"ServerObject\": {\n      \"@id\": \"redoc:ServerObject\",\n      \"@context\": {\n        \"url\": {\n          \"\
  @id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/redoc/refs/heads/main/json-ld/redoc-context.jsonld
tags:
- API Documentation
- Developer Tools
- Documentation
- OpenAPI
- Reference
- Renderer
- JSON-LD
- Linked Data
- Semantic Web
---
