---
api_specs:
- filename: gitbook-gitbook-api-openapi.yml
  format: yaml
  label: GitBook
  slug: gitbook
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gitbook/refs/heads/main/openapi/gitbook-gitbook-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/gitbook-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/gitbook/refs/heads/main/json-ld/gitbook-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Gitbook from GitBook.
layout: jsonld
name: Gitbook Context
namespaces:
- prefix: gitbook
  uri: https://docs.gitbook.com/developers/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Space
  type: ''
- container: ''
  name: Page
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: ChangeRequest
  type: ''
- container: ''
  name: DocsSite
  type: ''
- container: ''
  name: Collection
  type: ''
property_count: 7
provider_name: GitBook
provider_slug: gitbook
slug: gitbook-context
source_filename: gitbook-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gitbook\": \"https://docs.gitbook.com/developers/\",\n    \"Organization\": {\n      \"@id\": \"gitbook:organization\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\",\n        \"urls\": \"https://schema.org/url\"\n      }\n    },\n    \"Space\": {\n      \"@id\": \"gitbook:space\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"emoji\": \"https://schema.org/character\",\n        \"visibility\": \"https://schema.org/accessMode\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\",\n        \"deletedAt\": \"https://schema.org/dateDeleted\",\n        \"urls\"\
  : \"https://schema.org/url\"\n      }\n    },\n    \"Page\": {\n      \"@id\": \"gitbook:page\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"kind\": \"https://schema.org/additionalType\",\n        \"path\": \"https://schema.org/urlTemplate\",\n        \"pages\": \"https://schema.org/hasPart\",\n        \"document\": \"https://schema.org/text\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"gitbook:user\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"displayName\": \"https://schema.org/name\",\n        \"email\": \"https://schema.org/email\",\n        \"photoURL\": \"https://schema.org/image\",\n        \"urls\": \"https://schema.org/url\"\n      }\n    },\n    \"ChangeRequest\": {\n      \"@id\": \"gitbook:change-request\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\"\
  ,\n        \"number\": \"https://schema.org/position\",\n        \"subject\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"status\": \"https://schema.org/status\",\n        \"createdBy\": {\n          \"@id\": \"gitbook:user\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\",\n        \"mergedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"DocsSite\": {\n      \"@id\": \"gitbook:docs-site\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"hostname\": \"https://schema.org/url\",\n        \"urls\": \"https://schema.org/url\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Collection\": {\n      \"@id\": \"gitbook:collection\"\
  ,\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/gitbook/refs/heads/main/json-ld/gitbook-context.jsonld
tags:
- Content
- Documentation
- Experience
- Integrations
- Platform
- SDKs
- JSON-LD
- Linked Data
- Semantic Web
---
