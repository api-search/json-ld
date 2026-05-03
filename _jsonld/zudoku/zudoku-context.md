---
api_specs:
- filename: zudoku-configuration-api-openapi.yml
  format: yaml
  label: Zudoku Configuration API
  slug: configuration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zudoku/refs/heads/main/openapi/zudoku-configuration-api-openapi.yml
class_count: 12
classes:
- name
- description
- url
- version
- license
- author
- documentation
- apiReference
- openApiDocument
- playground
- search
- staticSiteGeneration
context_file: json-ld/zudoku-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zudoku/refs/heads/main/json-ld/zudoku-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zudoku from Zudoku.
layout: jsonld
name: Zudoku Context
namespaces:
- prefix: zudoku
  uri: https://zudoku.dev/schema/
- prefix: openapi
  uri: https://spec.openapis.org/oas/v3.0/
properties:
- container: ''
  name: ZudokuConfig
  type: SoftwareApplication
- container: ''
  name: ApiReference
  type: APIReference
- container: ''
  name: AuthenticationConfig
  type: ''
- container: ''
  name: ThemeConfig
  type: ''
- container: ''
  name: Plugin
  type: SoftwareApplication
- container: ''
  name: NavigationItem
  type: SiteNavigationElement
- container: ''
  name: SidebarItem
  type: SiteNavigationElement
property_count: 7
provider_name: Zudoku
provider_slug: zudoku
slug: zudoku-context
source_filename: zudoku-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"zudoku\": \"https://zudoku.dev/schema/\",\n    \"openapi\": \"https://spec.openapis.org/oas/v3.0/\",\n    \"ZudokuConfig\": {\n      \"@id\": \"zudoku:ZudokuConfig\",\n      \"@type\": \"SoftwareApplication\",\n      \"@context\": {\n        \"topNavigation\": \"zudoku:topNavigation\",\n        \"sidebar\": \"zudoku:sidebar\",\n        \"apis\": \"zudoku:apis\",\n        \"docs\": \"zudoku:docs\",\n        \"authentication\": \"zudoku:authentication\",\n        \"theme\": \"zudoku:theme\",\n        \"metadata\": \"zudoku:metadata\",\n        \"plugins\": \"zudoku:plugins\",\n        \"redirects\": \"zudoku:redirects\",\n        \"basePath\": \"zudoku:basePath\",\n        \"page\": \"zudoku:page\"\n      }\n    },\n    \"ApiReference\": {\n      \"@id\": \"zudoku:ApiReference\",\n      \"@type\": \"APIReference\",\n      \"@context\": {\n        \"type\": \"zudoku:referenceType\",\n        \"input\": \"zudoku:input\"\
  ,\n        \"navigationId\": \"zudoku:navigationId\",\n        \"label\": \"name\",\n        \"serverUrl\": \"zudoku:serverUrl\"\n      }\n    },\n    \"AuthenticationConfig\": {\n      \"@id\": \"zudoku:AuthenticationConfig\",\n      \"@context\": {\n        \"type\": \"zudoku:authType\",\n        \"clientId\": \"zudoku:clientId\",\n        \"issuer\": \"zudoku:issuer\",\n        \"scopes\": \"zudoku:scopes\",\n        \"redirectUri\": \"zudoku:redirectUri\"\n      }\n    },\n    \"ThemeConfig\": {\n      \"@id\": \"zudoku:ThemeConfig\",\n      \"@context\": {\n        \"light\": \"zudoku:lightTheme\",\n        \"dark\": \"zudoku:darkTheme\",\n        \"fonts\": \"zudoku:fonts\"\n      }\n    },\n    \"Plugin\": {\n      \"@id\": \"zudoku:Plugin\",\n      \"@type\": \"SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"name\",\n        \"config\": \"zudoku:pluginConfig\"\n      }\n    },\n    \"NavigationItem\": {\n      \"@id\": \"zudoku:NavigationItem\",\n      \"@type\"\
  : \"SiteNavigationElement\",\n      \"@context\": {\n        \"id\": \"identifier\",\n        \"label\": \"name\",\n        \"default\": \"zudoku:defaultPath\"\n      }\n    },\n    \"SidebarItem\": {\n      \"@id\": \"zudoku:SidebarItem\",\n      \"@type\": \"SiteNavigationElement\",\n      \"@context\": {\n        \"type\": \"zudoku:sidebarItemType\",\n        \"id\": \"identifier\",\n        \"label\": \"name\",\n        \"link\": \"url\",\n        \"items\": \"zudoku:childItems\"\n      }\n    },\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"version\": \"softwareVersion\",\n    \"license\": \"license\",\n    \"author\": \"author\",\n    \"documentation\": \"documentation\",\n    \"apiReference\": \"zudoku:apiReference\",\n    \"openApiDocument\": \"zudoku:openApiDocument\",\n    \"playground\": \"zudoku:playground\",\n    \"search\": \"zudoku:search\",\n    \"staticSiteGeneration\": \"zudoku:staticSiteGeneration\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zudoku/refs/heads/main/json-ld/zudoku-context.jsonld
tags:
- Developer Tools
- Documentation
- JSON-LD
- Linked Data
- Semantic Web
---
