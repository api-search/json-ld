---
api_specs:
- filename: brewpage-openapi.yml
  format: yaml
  label: BrewPage API
  slug: api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/brewpage/refs/heads/main/openapi/brewpage-openapi.yml
class_count: 21
classes:
- HTMLPage
- MarkdownPage
- File
- Site
- KVStore
- JSONDocument
- ShortLink
- Namespace
- AbuseReport
- OwnerToken
- namespace
- ownerToken
- format
- ttlDays
- passwordProtected
- showTopBar
- views
- downloads
- entry
- files
- content
context_file: json-ld/brewpage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/brewpage/refs/heads/main/json-ld/brewpage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Brewpage from BrewPage.
layout: jsonld
name: Brewpage Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: brewpage
  uri: https://brewpage.app/ns#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: link
  type: reference
- container: ''
  name: ownerLink
  type: reference
- container: ''
  name: filename
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: size
  type: integer
- container: ''
  name: contentType
  type: string
property_count: 9
provider_name: BrewPage
provider_slug: brewpage
slug: brewpage-context
source_filename: brewpage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"brewpage\": \"https://brewpage.app/ns#\",\n    \"HTMLPage\": \"brewpage:HTMLPage\",\n    \"MarkdownPage\": \"brewpage:MarkdownPage\",\n    \"File\": \"schema:MediaObject\",\n    \"Site\": \"brewpage:Site\",\n    \"KVStore\": \"brewpage:KVStore\",\n    \"JSONDocument\": \"brewpage:JSONDocument\",\n    \"ShortLink\": \"brewpage:ShortLink\",\n    \"Namespace\": \"brewpage:Namespace\",\n    \"AbuseReport\": \"brewpage:AbuseReport\",\n    \"OwnerToken\": \"brewpage:OwnerToken\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"namespace\": \"brewpage:namespace\",\n    \"link\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"ownerLink\": {\n      \"@id\": \"brewpage:ownerLink\",\n      \"@type\": \"@id\"\n    },\n    \"ownerToken\": \"brewpage:ownerToken\"\
  ,\n    \"filename\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": \"brewpage:format\",\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ttlDays\": \"brewpage:ttlDays\",\n    \"passwordProtected\": \"brewpage:passwordProtected\",\n    \"showTopBar\": \"brewpage:showTopBar\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"views\": \"brewpage:views\",\n    \"downloads\": \"brewpage:downloads\",\n    \"size\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"contentType\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entry\": \"brewpage:entry\",\n    \"files\": \"brewpage:files\",\n    \"content\": \"schema:text\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/brewpage/refs/heads/main/json-ld/brewpage-context.jsonld
tags:
- Hosting
- Markdown
- HTML
- AI Artifacts
- File Hosting
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
