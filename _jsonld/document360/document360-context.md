---
api_specs:
- filename: document360-document360-api-openapi.yml
  format: yaml
  label: Document360 API
  slug: document360-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/document360/refs/heads/main/openapi/document360-document360-api-openapi.yml
class_count: 31
classes:
- id
- type
- Article
- Category
- ProjectVersion
- DriveFolder
- DriveFile
- User
- Team
- title
- slug
- content
- contentMarkdown
- categoryId
- projectVersionId
- languageCode
- status
- createdAt
- modifiedAt
- order
- parentCategoryId
- name
- url
- size
- folderId
- parentId
- firstName
- lastName
- emailId
- roleName
- memberCount
context_file: json-ld/document360-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/document360/refs/heads/main/json-ld/document360-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Document360 from Document360.
layout: jsonld
name: Document360 Context
namespaces:
- prefix: document360
  uri: https://document360.com/ns#
properties: []
property_count: 0
provider_name: Document360
provider_slug: document360
slug: document360-context
source_filename: document360-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"document360\": \"https://document360.com/ns#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Article\": \"document360:Article\",\n    \"Category\": \"document360:Category\",\n    \"ProjectVersion\": \"document360:ProjectVersion\",\n    \"DriveFolder\": \"document360:DriveFolder\",\n    \"DriveFile\": \"document360:DriveFile\",\n    \"User\": \"document360:User\",\n    \"Team\": \"document360:Team\",\n    \"title\": \"schema:name\",\n    \"slug\": \"document360:slug\",\n    \"content\": \"schema:articleBody\",\n    \"contentMarkdown\": \"document360:contentMarkdown\",\n    \"categoryId\": \"document360:categoryId\",\n    \"projectVersionId\": \"document360:projectVersionId\",\n    \"languageCode\": \"schema:inLanguage\",\n    \"status\": \"document360:status\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"modifiedAt\": \"schema:dateModified\",\n    \"order\": \"document360:order\",\n    \"\
  parentCategoryId\": \"document360:parentCategoryId\",\n    \"name\": \"schema:name\",\n    \"url\": \"schema:url\",\n    \"size\": \"schema:contentSize\",\n    \"folderId\": \"document360:folderId\",\n    \"parentId\": \"document360:parentId\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"emailId\": \"schema:email\",\n    \"roleName\": \"document360:roleName\",\n    \"memberCount\": \"document360:memberCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/document360/refs/heads/main/json-ld/document360-context.jsonld
tags:
- Documentation
- Knowledge Base
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
