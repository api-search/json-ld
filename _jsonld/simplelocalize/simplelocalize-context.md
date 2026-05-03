---
api_specs:
- filename: docs
  format: yaml
  label: SimpleLocalize Translation API
  slug: translation-api
  spec_type: OpenAPI
  url: https://api.simplelocalize.io/openapi/docs
class_count: 17
classes:
- Translation
- Language
- Project
- Customer
- key
- namespace
- language
- text
- reviewStatus
- customerId
- name
- description
- apiKey
- translationCount
- SoftwareApplication
- WebAPI
- Service
context_file: json-ld/simplelocalize-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/json-ld/simplelocalize-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Simplelocalize from SimpleLocalize.
layout: jsonld
name: Simplelocalize Context
namespaces:
- prefix: sl
  uri: https://simplelocalize.io/schema/
properties:
- container: ''
  name: modifiedAt
  type: schema:DateTime
- container: ''
  name: createdAt
  type: schema:DateTime
- container: set
  name: languages
  type: reference
property_count: 3
provider_name: SimpleLocalize
provider_slug: simplelocalize
slug: simplelocalize-context
source_filename: simplelocalize-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sl\": \"https://simplelocalize.io/schema/\",\n    \"Translation\": \"sl:Translation\",\n    \"Language\": \"sl:Language\",\n    \"Project\": \"sl:Project\",\n    \"Customer\": \"sl:Customer\",\n    \"key\": \"sl:key\",\n    \"namespace\": \"sl:namespace\",\n    \"language\": \"sl:language\",\n    \"text\": \"sl:text\",\n    \"reviewStatus\": \"sl:reviewStatus\",\n    \"customerId\": \"sl:customerId\",\n    \"modifiedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"apiKey\": \"sl:apiKey\",\n    \"translationCount\": \"sl:translationCount\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"languages\": {\n      \"@id\": \"sl:hasLanguage\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"\
  SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"WebAPI\": \"schema:WebAPI\",\n    \"Service\": \"schema:Service\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/json-ld/simplelocalize-context.jsonld
tags:
- Localization
- Translation
- Internationalization
- JSON-LD
- Linked Data
- Semantic Web
---
