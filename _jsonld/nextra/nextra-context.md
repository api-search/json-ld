---
class_count: 0
classes: []
context_file: json-ld/nextra-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nextra/refs/heads/main/json-ld/nextra-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nextra from Nextra.
layout: jsonld
name: Nextra Context
namespaces:
- prefix: nextra
  uri: https://nextra.site/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: doap
  uri: http://usefulinc.com/ns/doap#
properties:
- container: ''
  name: NextraConfig
  type: ''
- container: ''
  name: PageMapItem
  type: ''
- container: ''
  name: MdxFile
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: MetaJsonFile
  type: ''
- container: ''
  name: FrontMatter
  type: ''
- container: ''
  name: Heading
  type: ''
- container: ''
  name: ReadingTime
  type: ''
- container: ''
  name: DocsThemeConfig
  type: ''
- container: ''
  name: SoftwarePackage
  type: ''
property_count: 10
provider_name: Nextra
provider_slug: nextra
slug: nextra-context
source_filename: nextra-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nextra\": \"https://nextra.site/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n\n    \"NextraConfig\": {\n      \"@id\": \"nextra:NextraConfig\",\n      \"@context\": {\n        \"defaultShowCopyCode\": {\n          \"@id\": \"nextra:defaultShowCopyCode\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"staticImage\": {\n          \"@id\": \"nextra:staticImage\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"readingTime\": {\n          \"@id\": \"nextra:readingTime\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"codeHighlight\": {\n          \"@id\": \"nextra:codeHighlight\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"contentDirBasePath\": {\n          \"@id\": \"nextra:contentDirBasePath\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"latex\": \"nextra:latex\",\n        \"search\": \"nextra:search\",\n        \"mdxOptions\": \"nextra:mdxOptions\"\n      }\n    },\n\n    \"PageMapItem\": {\n      \"@id\": \"nextra:PageMapItem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"route\": {\n          \"@id\": \"nextra:route\",\n          \"@type\": \"xsd:string\"\n        },\n        \"children\": {\n          \"@id\": \"nextra:children\",\n          \"@container\": \"@set\"\n        },\n        \"frontMatter\": \"nextra:frontMatter\"\n      }\n    },\n\n    \"MdxFile\": {\n      \"@id\": \"nextra:MdxFile\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"route\": {\n          \"@id\": \"nextra:route\",\n          \"@type\": \"xsd:string\"\n        },\n        \"frontMatter\": \"nextra:frontMatter\"\n      }\n    },\n\n    \"Folder\": {\n      \"@id\": \"nextra:Folder\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n      \
  \  \"route\": {\n          \"@id\": \"nextra:route\",\n          \"@type\": \"xsd:string\"\n        },\n        \"children\": {\n          \"@id\": \"nextra:children\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MetaJsonFile\": {\n      \"@id\": \"nextra:MetaJsonFile\",\n      \"@context\": {\n        \"data\": \"nextra:metaData\"\n      }\n    },\n\n    \"FrontMatter\": {\n      \"@id\": \"nextra:FrontMatter\",\n      \"@context\": {\n        \"title\": \"dcterms:title\",\n        \"description\": \"dcterms:description\",\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n        \"tag\": \"schema:keywords\",\n        \"readingTime\": \"nextra:readingTime\"\n      }\n    },\n\n    \"Heading\": {\n      \"@id\": \"nextra:Heading\",\n      \"@context\": {\n        \"depth\": {\n          \"@id\": \"nextra:depth\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"value\": \"schema:name\",\n\
  \        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ReadingTime\": {\n      \"@id\": \"nextra:ReadingTime\",\n      \"@context\": {\n        \"text\": \"schema:description\",\n        \"minutes\": {\n          \"@id\": \"nextra:minutes\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"time\": {\n          \"@id\": \"nextra:time\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"words\": {\n          \"@id\": \"nextra:words\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"DocsThemeConfig\": {\n      \"@id\": \"nextra:DocsThemeConfig\",\n      \"@context\": {\n        \"docsRepositoryBase\": {\n          \"@id\": \"nextra:docsRepositoryBase\",\n          \"@type\": \"@id\"\n        },\n        \"darkMode\": {\n          \"@id\": \"nextra:darkMode\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"copyPageButton\": {\n          \"@id\": \"\
  nextra:copyPageButton\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"navigation\": \"nextra:navigation\",\n        \"sidebar\": \"nextra:sidebar\",\n        \"toc\": \"nextra:toc\",\n        \"feedback\": \"nextra:feedback\",\n        \"i18n\": {\n          \"@id\": \"nextra:i18n\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SoftwarePackage\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\",\n        \"license\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"@id\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"repository\": {\n          \"@id\": \"doap:repository\",\n          \"@type\": \"@id\"\n        },\n        \"keywords\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\"\
  : \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nextra/refs/heads/main/json-ld/nextra-context.jsonld
tags:
- Documentation
- MDX
- Next.js
- Open Source
- Static Site Generator
- JSON-LD
- Linked Data
- Semantic Web
---
