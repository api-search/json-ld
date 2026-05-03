---
class_count: 0
classes: []
context_file: json-ld/vitepress-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vitepress/refs/heads/main/json-ld/vitepress-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vitepress from VitePress.
layout: jsonld
name: Vitepress Context
namespaces:
- prefix: vitepress
  uri: https://vitepress.dev/vocab#
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
  name: VitePressProject
  type: ''
- container: ''
  name: VitePressPage
  type: ''
- container: ''
  name: VitePressThemeConfig
  type: ''
- container: ''
  name: VitePressNavItem
  type: ''
- container: ''
  name: VitePressSidebarItem
  type: ''
- container: ''
  name: VitePressHero
  type: ''
- container: ''
  name: VitePressFeature
  type: ''
- container: ''
  name: VitePressDataLoader
  type: ''
- container: ''
  name: VitePressSocialLink
  type: ''
property_count: 9
provider_name: VitePress
provider_slug: vitepress
slug: vitepress-context
source_filename: vitepress-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vitepress\": \"https://vitepress.dev/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"doap\": \"http://usefulinc.com/ns/doap#\",\n\n    \"VitePressProject\": {\n      \"@id\": \"vitepress:Project\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"lang\": {\n          \"@id\": \"schema:inLanguage\"\n        },\n        \"base\": {\n          \"@id\": \"vitepress:base\"\n        },\n        \"srcDir\": {\n          \"@id\": \"vitepress:sourceDirectory\"\n        },\n        \"outDir\": {\n          \"@id\": \"vitepress:outputDirectory\"\n        },\n        \"themeConfig\": {\n          \"@id\": \"vitepress:themeConfig\"\n        },\n        \"locales\": {\n          \"@id\"\
  : \"vitepress:locales\",\n          \"@container\": \"@index\"\n        },\n        \"lastUpdated\": {\n          \"@id\": \"vitepress:lastUpdated\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"VitePressPage\": {\n      \"@id\": \"vitepress:Page\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"dcterms:title\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"relativePath\": {\n          \"@id\": \"vitepress:relativePath\"\n        },\n        \"filePath\": {\n          \"@id\": \"vitepress:filePath\"\n        },\n        \"frontmatter\": {\n          \"@id\": \"vitepress:frontmatter\"\n        },\n        \"lastUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"headers\": {\n          \"@id\": \"vitepress:headers\",\n\
  \          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"VitePressThemeConfig\": {\n      \"@id\": \"vitepress:ThemeConfig\",\n      \"@context\": {\n        \"logo\": {\n          \"@id\": \"schema:logo\"\n        },\n        \"siteTitle\": {\n          \"@id\": \"schema:name\"\n        },\n        \"nav\": {\n          \"@id\": \"vitepress:navigation\",\n          \"@container\": \"@list\"\n        },\n        \"sidebar\": {\n          \"@id\": \"vitepress:sidebar\"\n        },\n        \"socialLinks\": {\n          \"@id\": \"schema:sameAs\",\n          \"@container\": \"@set\"\n        },\n        \"footer\": {\n          \"@id\": \"vitepress:footer\"\n        },\n        \"editLink\": {\n          \"@id\": \"vitepress:editLink\"\n        },\n        \"search\": {\n          \"@id\": \"vitepress:search\"\n        }\n      }\n    },\n\n    \"VitePressNavItem\": {\n      \"@id\": \"vitepress:NavItem\",\n      \"@context\": {\n        \"text\": {\n          \"@id\": \"\
  schema:name\"\n        },\n        \"link\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"items\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@list\"\n        },\n        \"activeMatch\": {\n          \"@id\": \"vitepress:activeMatch\"\n        }\n      }\n    },\n\n    \"VitePressSidebarItem\": {\n      \"@id\": \"vitepress:SidebarItem\",\n      \"@context\": {\n        \"text\": {\n          \"@id\": \"schema:name\"\n        },\n        \"link\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"items\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@list\"\n        },\n        \"collapsed\": {\n          \"@id\": \"vitepress:collapsed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"base\": {\n          \"@id\": \"vitepress:basePath\"\n        }\n      }\n    },\n\n    \"VitePressHero\": {\n      \"@id\": \"vitepress:Hero\",\n   \
  \   \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"text\": {\n          \"@id\": \"schema:description\"\n        },\n        \"tagline\": {\n          \"@id\": \"schema:slogan\"\n        },\n        \"image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"actions\": {\n          \"@id\": \"schema:potentialAction\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"VitePressFeature\": {\n      \"@id\": \"vitepress:Feature\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"schema:name\"\n        },\n        \"details\": {\n          \"@id\": \"schema:description\"\n        },\n        \"link\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"linkText\": {\n          \"@id\": \"vitepress:linkText\"\n        },\n        \"icon\": {\n          \"@id\": \"schema:image\"\n        }\n      }\n    },\n\n    \"VitePressDataLoader\"\
  : {\n      \"@id\": \"vitepress:DataLoader\",\n      \"@context\": {\n        \"watch\": {\n          \"@id\": \"vitepress:watchPattern\",\n          \"@container\": \"@set\"\n        },\n        \"load\": {\n          \"@id\": \"vitepress:loadFunction\"\n        }\n      }\n    },\n\n    \"VitePressSocialLink\": {\n      \"@id\": \"schema:ContactPoint\",\n      \"@context\": {\n        \"icon\": {\n          \"@id\": \"schema:name\"\n        },\n        \"link\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"ariaLabel\": {\n          \"@id\": \"schema:description\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vitepress/refs/heads/main/json-ld/vitepress-context.jsonld
tags:
- Documentation
- Markdown
- Open Source
- Static Site Generator
- Vite
- Vue
- JSON-LD
- Linked Data
- Semantic Web
---
