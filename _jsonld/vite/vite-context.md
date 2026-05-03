---
api_specs:
- filename: vite-javascript-api-openapi.yml
  format: yaml
  label: Vite JavaScript API
  slug: javascript-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/openapi/vite-javascript-api-openapi.yml
- filename: vite-plugin-api-openapi.yml
  format: yaml
  label: Vite Plugin API
  slug: plugin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/openapi/vite-plugin-api-openapi.yml
class_count: 8
classes:
- ViteConfig
- VitePlugin
- ViteDevServer
- ViteBuildResult
- ModuleNode
- HmrContext
- SoftwareApplication
- SoftwareLibrary
context_file: json-ld/vite-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/json-ld/vite-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vite from Vite.
layout: jsonld
name: Vite Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: vite
  uri: https://vitejs.dev/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: root
  type: string
- container: ''
  name: base
  type: string
- container: ''
  name: mode
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: host
  type: ''
- container: ''
  name: outDir
  type: string
- container: ''
  name: assetsDir
  type: string
- container: ''
  name: target
  type: ''
- container: ''
  name: sourcemap
  type: ''
- container: ''
  name: minify
  type: ''
- container: list
  name: plugins
  type: ''
- container: ''
  name: publicDir
  type: string
- container: ''
  name: cacheDir
  type: string
- container: ''
  name: envDir
  type: string
- container: ''
  name: envPrefix
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: version
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: license
  type: reference
- container: ''
  name: pluginName
  type: string
- container: ''
  name: enforce
  type: string
- container: ''
  name: apply
  type: ''
- container: ''
  name: config
  type: ''
- container: ''
  name: transform
  type: ''
- container: ''
  name: resolveId
  type: ''
- container: ''
  name: load
  type: ''
- container: ''
  name: handleHotUpdate
  type: ''
- container: ''
  name: transformIndexHtml
  type: ''
- container: ''
  name: configureServer
  type: ''
- container: ''
  name: moduleId
  type: string
- container: ''
  name: moduleFile
  type: string
- container: ''
  name: moduleUrl
  type: reference
- container: set
  name: importers
  type: ''
- container: set
  name: importedModules
  type: ''
- container: ''
  name: programmingLanguage
  type: ''
property_count: 36
provider_name: Vite
provider_slug: vite
slug: vite-context
source_filename: vite-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"vite\": \"https://vitejs.dev/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ViteConfig\": \"vite:ViteConfig\",\n    \"VitePlugin\": \"vite:VitePlugin\",\n    \"ViteDevServer\": \"vite:ViteDevServer\",\n    \"ViteBuildResult\": \"vite:ViteBuildResult\",\n    \"ModuleNode\": \"vite:ModuleNode\",\n    \"HmrContext\": \"vite:HmrContext\",\n\n    \"root\": {\"@id\": \"vite:root\", \"@type\": \"xsd:string\"},\n    \"base\": {\"@id\": \"vite:base\", \"@type\": \"xsd:string\"},\n    \"mode\": {\"@id\": \"vite:mode\", \"@type\": \"xsd:string\"},\n    \"port\": {\"@id\": \"vite:port\", \"@type\": \"xsd:integer\"},\n    \"host\": {\"@id\": \"vite:host\"},\n    \"outDir\": {\"@id\": \"vite:outDir\", \"@type\": \"xsd:string\"},\n    \"assetsDir\": {\"@id\": \"vite:assetsDir\", \"@type\": \"xsd:string\"},\n    \"target\": {\"@id\": \"vite:target\"},\n    \"sourcemap\"\
  : {\"@id\": \"vite:sourcemap\"},\n    \"minify\": {\"@id\": \"vite:minify\"},\n    \"plugins\": {\"@id\": \"vite:plugins\", \"@container\": \"@list\"},\n    \"publicDir\": {\"@id\": \"vite:publicDir\", \"@type\": \"xsd:string\"},\n    \"cacheDir\": {\"@id\": \"vite:cacheDir\", \"@type\": \"xsd:string\"},\n    \"envDir\": {\"@id\": \"vite:envDir\", \"@type\": \"xsd:string\"},\n    \"envPrefix\": {\"@id\": \"vite:envPrefix\"},\n\n    \"name\": {\"@id\": \"schema:name\"},\n    \"description\": {\"@id\": \"schema:description\"},\n    \"version\": {\"@id\": \"schema:version\"},\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"license\": {\"@id\": \"schema:license\", \"@type\": \"@id\"},\n\n    \"pluginName\": {\"@id\": \"vite:pluginName\", \"@type\": \"xsd:string\"},\n    \"enforce\": {\"@id\": \"vite:enforce\", \"@type\": \"xsd:string\"},\n    \"apply\": {\"@id\": \"vite:apply\"},\n    \"config\": {\"@id\": \"vite:config\"},\n    \"transform\": {\"@id\": \"vite:transform\"\
  },\n    \"resolveId\": {\"@id\": \"vite:resolveId\"},\n    \"load\": {\"@id\": \"vite:load\"},\n    \"handleHotUpdate\": {\"@id\": \"vite:handleHotUpdate\"},\n    \"transformIndexHtml\": {\"@id\": \"vite:transformIndexHtml\"},\n    \"configureServer\": {\"@id\": \"vite:configureServer\"},\n\n    \"moduleId\": {\"@id\": \"vite:moduleId\", \"@type\": \"xsd:string\"},\n    \"moduleFile\": {\"@id\": \"vite:moduleFile\", \"@type\": \"xsd:string\"},\n    \"moduleUrl\": {\"@id\": \"vite:moduleUrl\", \"@type\": \"@id\"},\n    \"importers\": {\"@id\": \"vite:importers\", \"@container\": \"@set\"},\n    \"importedModules\": {\"@id\": \"vite:importedModules\", \"@container\": \"@set\"},\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareLibrary\": \"schema:SoftwareLibrary\",\n    \"programmingLanguage\": {\"@id\": \"schema:programmingLanguage\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/json-ld/vite-context.jsonld
tags:
- Build Tools
- Bundler
- Development Server
- ESM
- Frontend
- Hot Module Replacement
- JavaScript
- Plugin API
- TypeScript
- Vite
- JSON-LD
- Linked Data
- Semantic Web
---
