---
api_specs:
- filename: datocms-content-management-api.yml
  format: yaml
  label: DatoCMS Content Management API
  slug: datocms
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/openapi/datocms-content-management-api.yml
class_count: 0
classes: []
context_file: json-ld/datocms-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/json-ld/datocms-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Datocms from DatoCMS.
layout: jsonld
name: Datocms Context
namespaces:
- prefix: datocms
  uri: https://www.datocms.com/docs/content-management-api/
properties:
- container: ''
  name: Site
  type: ''
- container: ''
  name: Item
  type: ''
- container: ''
  name: ItemType
  type: ''
- container: ''
  name: Field
  type: ''
- container: ''
  name: Upload
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Webhook
  type: ''
property_count: 7
provider_name: DatoCMS
provider_slug: datocms
slug: datocms-context
source_filename: datocms-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"datocms\": \"https://www.datocms.com/docs/content-management-api/\",\n    \"Site\": {\n      \"@id\": \"datocms:resources/site\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"domain\": \"https://schema.org/url\",\n        \"locales\": \"https://schema.org/inLanguage\"\n      }\n    },\n    \"Item\": {\n      \"@id\": \"datocms:resources/item\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"attributes\": \"https://schema.org/additionalProperty\",\n        \"created_at\": \"https://schema.org/dateCreated\",\n        \"updated_at\": \"https://schema.org/dateModified\",\n        \"published_at\": \"https://schema.org/datePublished\",\n        \"status\": \"https://schema.org/status\"\n      }\n    },\n    \"ItemType\": {\n  \
  \    \"@id\": \"datocms:resources/item-type\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"api_key\": \"https://schema.org/identifier\",\n        \"singleton\": \"https://schema.org/option\"\n      }\n    },\n    \"Field\": {\n      \"@id\": \"datocms:resources/field\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"label\": \"https://schema.org/name\",\n        \"api_key\": \"https://schema.org/identifier\",\n        \"field_type\": \"https://schema.org/additionalType\",\n        \"validators\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"Upload\": {\n      \"@id\": \"https://schema.org/MediaObject\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"url\": \"https://schema.org/url\",\n        \"size\": \"https://schema.org/contentSize\",\n        \"format\": \"https://schema.org/encodingFormat\",\n \
  \       \"alt\": \"https://schema.org/description\",\n        \"title\": \"https://schema.org/name\"\n      }\n    },\n    \"Environment\": {\n      \"@id\": \"datocms:resources/environment\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"primary\": \"https://schema.org/option\",\n        \"forked_from\": \"https://schema.org/isBasedOn\"\n      }\n    },\n    \"Webhook\": {\n      \"@id\": \"datocms:resources/webhook\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"url\": \"https://schema.org/url\",\n        \"events\": \"https://schema.org/event\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/json-ld/datocms-context.jsonld
tags:
- CMS
- Content Delivery
- Content Management
- GraphQL
- Headless CMS
- JSON-LD
- Linked Data
- Semantic Web
---
