---
api_specs:
- filename: jetbrains-space-openapi.yml
  format: yaml
  label: JetBrains Space HTTP API
  slug: space-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-space-openapi.yml
- filename: jetbrains-teamcity-openapi.yml
  format: yaml
  label: JetBrains TeamCity REST API
  slug: teamcity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-teamcity-openapi.yml
- filename: jetbrains-youtrack-openapi.yml
  format: yaml
  label: JetBrains YouTrack REST API
  slug: youtrack-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-youtrack-openapi.yml
- filename: jetbrains-hub-openapi.yml
  format: yaml
  label: JetBrains Hub REST API
  slug: hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-hub-openapi.yml
- filename: jetbrains-marketplace-openapi.yml
  format: yaml
  label: JetBrains Marketplace API
  slug: marketplace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/openapi/jetbrains-marketplace-openapi.yml
class_count: 11
classes:
- id
- type
- name
- description
- url
- email
- dateCreated
- dateModified
- SoftwareApplication
- Organization
- Person
context_file: json-ld/jetbrains-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/json-ld/jetbrains-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jetbrains from JetBrains.
layout: jsonld
name: Jetbrains Context
namespaces:
- prefix: jetbrains
  uri: https://www.jetbrains.com/ns/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Issue
  type: ''
- container: ''
  name: Build
  type: ''
- container: ''
  name: BuildAgent
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Space
  type: ''
property_count: 7
provider_name: JetBrains
provider_slug: jetbrains
slug: jetbrains-context
source_filename: jetbrains-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"jetbrains\": \"https://www.jetbrains.com/ns/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"email\": \"schema:email\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"Organization\": \"schema:Organization\",\n    \"Person\": \"schema:Person\",\n    \"Project\": {\n      \"@id\": \"jetbrains:Project\",\n      \"@context\": {\n        \"key\": \"jetbrains:projectKey\",\n        \"archived\": \"jetbrains:archived\"\n      }\n    },\n    \"Issue\": {\n      \"@id\": \"jetbrains:Issue\",\n      \"@context\": {\n        \"idReadable\": \"jetbrains:readableId\",\n        \"summary\": \"schema:headline\",\n        \"reporter\": \"schema:author\",\n        \"resolved\": \"jetbrains:resolvedDate\"\
  ,\n        \"commentsCount\": \"schema:commentCount\"\n      }\n    },\n    \"Build\": {\n      \"@id\": \"jetbrains:Build\",\n      \"@context\": {\n        \"buildNumber\": \"jetbrains:buildNumber\",\n        \"status\": \"jetbrains:buildStatus\",\n        \"state\": \"jetbrains:buildState\",\n        \"branchName\": \"jetbrains:branchName\",\n        \"buildTypeId\": \"jetbrains:buildTypeId\",\n        \"startDate\": \"schema:startDate\",\n        \"finishDate\": \"schema:endDate\",\n        \"agent\": \"jetbrains:buildAgent\"\n      }\n    },\n    \"BuildAgent\": {\n      \"@id\": \"jetbrains:BuildAgent\",\n      \"@context\": {\n        \"connected\": \"jetbrains:connected\",\n        \"enabled\": \"jetbrains:enabled\",\n        \"authorized\": \"jetbrains:authorized\",\n        \"ip\": \"jetbrains:ipAddress\",\n        \"pool\": \"jetbrains:agentPool\"\n      }\n    },\n    \"Plugin\": {\n      \"@id\": \"jetbrains:Plugin\",\n      \"@context\": {\n        \"xmlId\": \"jetbrains:pluginXmlId\"\
  ,\n        \"vendor\": \"schema:provider\",\n        \"downloads\": \"jetbrains:downloadCount\",\n        \"rating\": \"schema:aggregateRating\",\n        \"version\": \"schema:softwareVersion\",\n        \"compatibleProducts\": \"jetbrains:compatibleProducts\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"jetbrains:User\",\n      \"@context\": {\n        \"login\": \"jetbrains:login\",\n        \"fullName\": \"schema:name\",\n        \"avatarUrl\": \"schema:image\",\n        \"banned\": \"jetbrains:banned\",\n        \"groups\": \"schema:memberOf\"\n      }\n    },\n    \"Space\": {\n      \"@id\": \"jetbrains:Space\",\n      \"@context\": {\n        \"channel\": \"jetbrains:chatChannel\",\n        \"codeReview\": \"jetbrains:codeReview\",\n        \"automation\": \"jetbrains:automationJob\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jetbrains/refs/heads/main/json-ld/jetbrains-context.jsonld
tags:
- CI/CD
- Developer Tools
- IDE
- JSON-LD
- Linked Data
- Semantic Web
---
