---
api_specs:
- filename: techrepublic-wordpress-rest-api-openapi.yml
  format: yaml
  label: TechRepublic WordPress REST API
  slug: wordpress-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/techrepublic/refs/heads/main/openapi/techrepublic-wordpress-rest-api-openapi.yml
class_count: 29
classes:
- Post
- id
- date
- date_gmt
- modified
- modified_gmt
- slug
- status
- link
- rendered
- protected
- Category
- Tag
- count
- description
- name
- taxonomy
- parent
- Author
- url
- avatar_urls
- MediaItem
- alt_text
- caption
- media_type
- mime_type
- source_url
- media_details
- Page
context_file: json-ld/techrepublic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/techrepublic/refs/heads/main/json-ld/techrepublic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Techrepublic from TechRepublic.
layout: jsonld
name: Techrepublic Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: wp
  uri: https://api.w.org/
- prefix: techrepublic
  uri: https://www.techrepublic.com/
properties:
- container: ''
  name: title
  type: reference
- container: ''
  name: content
  type: reference
- container: ''
  name: excerpt
  type: reference
- container: ''
  name: author
  type: reference
- container: ''
  name: featured_media
  type: reference
- container: list
  name: categories
  type: ''
- container: list
  name: tags
  type: ''
property_count: 7
provider_name: TechRepublic
provider_slug: techrepublic
slug: techrepublic-context
source_filename: techrepublic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"wp\": \"https://api.w.org/\",\n    \"techrepublic\": \"https://www.techrepublic.com/\",\n\n    \"Post\": \"schema:Article\",\n    \"id\": \"@id\",\n    \"date\": \"schema:datePublished\",\n    \"date_gmt\": \"schema:datePublished\",\n    \"modified\": \"schema:dateModified\",\n    \"modified_gmt\": \"schema:dateModified\",\n    \"slug\": \"schema:identifier\",\n    \"status\": \"schema:creativeWorkStatus\",\n    \"link\": \"schema:url\",\n    \"title\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"@id\"\n    },\n    \"content\": {\n      \"@id\": \"schema:articleBody\",\n      \"@type\": \"@id\"\n    },\n    \"excerpt\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"@id\"\n    },\n    \"author\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"@id\"\n    },\n    \"featured_media\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n\
  \    },\n    \"categories\": {\n      \"@id\": \"schema:about\",\n      \"@container\": \"@list\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@list\"\n    },\n    \"rendered\": \"schema:text\",\n    \"protected\": \"schema:isAccessibleForFree\",\n\n    \"Category\": \"schema:DefinedTerm\",\n    \"Tag\": \"schema:DefinedTerm\",\n    \"count\": \"schema:articleCount\",\n    \"description\": \"schema:description\",\n    \"name\": \"schema:name\",\n    \"taxonomy\": \"schema:inDefinedTermSet\",\n    \"parent\": \"schema:parentItem\",\n\n    \"Author\": \"schema:Person\",\n    \"url\": \"schema:url\",\n    \"avatar_urls\": \"schema:image\",\n\n    \"MediaItem\": \"schema:ImageObject\",\n    \"alt_text\": \"schema:alternateName\",\n    \"caption\": \"schema:caption\",\n    \"media_type\": \"schema:encodingFormat\",\n    \"mime_type\": \"schema:encodingFormat\",\n    \"source_url\": \"schema:contentUrl\",\n    \"media_details\": \"schema:associatedMedia\"\
  ,\n\n    \"Page\": \"schema:WebPage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/techrepublic/refs/heads/main/json-ld/techrepublic-context.jsonld
tags:
- Enterprise IT
- Media
- Technology News
- Content
- Publishing
- JSON-LD
- Linked Data
- Semantic Web
---
