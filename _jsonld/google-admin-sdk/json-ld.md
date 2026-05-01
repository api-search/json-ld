---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Admin SDK Directory API
  slug: google-admin-sdk-directory-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-admin-sdk/refs/heads/main/openapi/openapi.yml
class_count: 4
classes:
- name
- description
- url
- provider
context_file: json-ld/json-ld.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-admin-sdk/refs/heads/main/json-ld/json-ld.jsonld
description: JSON-LD context defining the semantic vocabulary for Json Ld from Google Admin SDK.
layout: jsonld
name: Json Ld Context
namespaces:
- prefix: admin
  uri: https://admin.googleapis.com/admin/directory/v1/
- prefix: goog
  uri: https://developers.google.com/workspace/admin/directory/reference/rest/v1/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Member
  type: ''
- container: ''
  name: OrgUnit
  type: ''
- container: ''
  name: Domain
  type: ''
property_count: 5
provider_name: Google Admin SDK
provider_slug: google-admin-sdk
slug: json-ld
source_filename: json-ld.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"admin\": \"https://admin.googleapis.com/admin/directory/v1/\",\n    \"goog\": \"https://developers.google.com/workspace/admin/directory/reference/rest/v1/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"User\": {\n      \"@id\": \"goog:users\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"primaryEmail\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"isAdmin\": \"schema:hasCredential\",\n        \"suspended\": \"schema:status\",\n        \"orgUnitPath\": \"schema:memberOf\",\n        \"creationTime\": \"schema:dateCreated\",\n        \"lastLoginTime\": \"schema:lastReviewed\"\n      }\n    },\n    \"Group\": {\n      \"@id\": \"goog:groups\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n       \
  \ \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"directMembersCount\": \"schema:size\"\n      }\n    },\n    \"Member\": {\n      \"@id\": \"goog:groups.members\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"role\": \"schema:roleName\",\n        \"type\": \"schema:additionalType\"\n      }\n    },\n    \"OrgUnit\": {\n      \"@id\": \"goog:orgunits\",\n      \"@context\": {\n        \"orgUnitId\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"orgUnitPath\": \"schema:url\",\n        \"parentOrgUnitPath\": \"schema:isPartOf\"\n      }\n    },\n    \"Domain\": {\n      \"@id\": \"goog:domains\",\n      \"@context\": {\n        \"domainName\": \"schema:name\",\n        \"isPrimary\": \"schema:mainEntity\",\n        \"verified\": \"schema:status\"\n      }\n    }\n  },\n  \"@type\": \"WebAPI\",\n  \"name\": \"\
  Google Admin SDK Directory API\",\n  \"description\": \"The Admin SDK Directory API enables management of users, groups, devices, organizational units, and domains in a Google Workspace domain.\",\n  \"url\": \"https://developers.google.com/workspace/admin/directory/reference/rest\",\n  \"provider\": {\n    \"@type\": \"Organization\",\n    \"name\": \"Google\",\n    \"url\": \"https://developers.google.com\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-admin-sdk/refs/heads/main/json-ld/json-ld.jsonld
tags:
- Administration
- Devices
- Directory
- Enterprise
- Google
- Google Workspace
- Groups
- Users
- JSON-LD
- Linked Data
- Semantic Web
---
