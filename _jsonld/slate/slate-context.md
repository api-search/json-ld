---
class_count: 0
classes: []
context_file: json-ld/slate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/slate/refs/heads/main/json-ld/slate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Slate from Slate.
layout: jsonld
name: Slate Context
namespaces:
- prefix: slate
  uri: https://slatedocs.github.io/slate/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ApiDocumentationPage
  type: ''
- container: ''
  name: LanguageTab
  type: ''
- container: ''
  name: IncludeFile
  type: ''
- container: ''
  name: CodeSample
  type: ''
- container: ''
  name: TableOfContentsEntry
  type: ''
- container: ''
  name: MetaTag
  type: ''
- container: ''
  name: SlateProject
  type: ''
property_count: 7
provider_name: Slate
provider_slug: slate
slug: slate-context
source_filename: slate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"slate\": \"https://slatedocs.github.io/slate/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ApiDocumentationPage\": {\n      \"@id\": \"slate:ApiDocumentationPage\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"languageTabs\": {\n          \"@id\": \"slate:languageTabs\",\n          \"@container\": \"@set\"\n        },\n        \"includes\": {\n          \"@id\": \"slate:includes\",\n          \"@container\": \"@set\"\n        },\n        \"search\": {\n          \"@id\": \"slate:search\"\n        },\n        \"codeClipboard\": {\n          \"@id\": \"slate:codeClipboard\"\n        },\n        \"tocFooters\": {\n          \"@id\": \"slate:tocFooters\",\n          \"\
  @container\": \"@set\"\n        },\n        \"meta\": {\n          \"@id\": \"slate:meta\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"LanguageTab\": {\n      \"@id\": \"slate:LanguageTab\",\n      \"@context\": {\n        \"identifier\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"label\": {\n          \"@id\": \"schema:name\"\n        }\n      }\n    },\n\n    \"IncludeFile\": {\n      \"@id\": \"slate:IncludeFile\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"CodeSample\": {\n      \"@id\": \"slate:CodeSample\",\n      \"@context\":\
  \ {\n        \"language\": {\n          \"@id\": \"schema:programmingLanguage\"\n        },\n        \"source\": {\n          \"@id\": \"schema:text\"\n        },\n        \"label\": {\n          \"@id\": \"schema:name\"\n        }\n      }\n    },\n\n    \"TableOfContentsEntry\": {\n      \"@id\": \"slate:TableOfContentsEntry\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"anchor\": {\n          \"@id\": \"slate:anchor\"\n        },\n        \"level\": {\n          \"@id\": \"slate:level\"\n        },\n        \"children\": {\n          \"@id\": \"slate:children\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MetaTag\": {\n      \"@id\": \"slate:MetaTag\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"content\": {\n          \"@id\": \"schema:description\"\n        }\n      }\n    },\n\n    \"SlateProject\": {\n      \"@id\": \"slate:SlateProject\"\
  ,\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"repositoryUrl\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        },\n        \"version\": {\n          \"@id\": \"schema:version\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"pages\": {\n          \"@id\": \"slate:pages\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/slate/refs/heads/main/json-ld/slate-context.jsonld
tags:
- API Documentation
- Developer Tools
- Documentation
- Markdown
- Ruby
- Static Site Generator
- Three-Panel
- JSON-LD
- Linked Data
- Semantic Web
---
