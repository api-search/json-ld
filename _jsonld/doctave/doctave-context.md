---
api_specs:
- filename: doctave-doctave-openapi.yml
  format: yaml
  label: Doctave API
  slug: doctave
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doctave/refs/heads/main/openapi/doctave-doctave-openapi.yml
class_count: 33
classes:
- id
- type
- Site
- Deployment
- Page
- SearchResult
- name
- description
- slug
- customDomain
- repository
- branch
- visibility
- navigation
- theme
- status
- commitSha
- triggeredBy
- environment
- buildDuration
- deployDuration
- title
- content
- order
- snippet
- score
- query
- totalResults
- results
- createdAt
- updatedAt
- finishedAt
- url
context_file: json-ld/doctave-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/doctave/refs/heads/main/json-ld/doctave-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Doctave from Doctave.
layout: jsonld
name: Doctave Context
namespaces:
- prefix: doctave
  uri: https://www.doctave.com/ns#
properties:
- container: ''
  name: siteId
  type: reference
- container: ''
  name: buildLog
  type: reference
- container: ''
  name: parentId
  type: reference
property_count: 3
provider_name: Doctave
provider_slug: doctave
slug: doctave-context
source_filename: doctave-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"doctave\": \"https://www.doctave.com/ns#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Site\": \"doctave:Site\",\n    \"Deployment\": \"doctave:Deployment\",\n    \"Page\": \"doctave:Page\",\n    \"SearchResult\": \"doctave:SearchResult\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"slug\": \"doctave:slug\",\n    \"customDomain\": \"doctave:customDomain\",\n    \"repository\": \"schema:codeRepository\",\n    \"branch\": \"doctave:branch\",\n    \"visibility\": \"doctave:visibility\",\n    \"navigation\": \"doctave:navigation\",\n    \"theme\": \"doctave:theme\",\n    \"siteId\": {\n      \"@id\": \"doctave:siteId\",\n      \"@type\": \"@id\"\n    },\n    \"status\": \"doctave:status\",\n    \"commitSha\": \"doctave:commitSha\",\n    \"triggeredBy\": \"doctave:triggeredBy\",\n    \"environment\": \"doctave:environment\",\n    \"buildDuration\": \"doctave:buildDuration\"\
  ,\n    \"deployDuration\": \"doctave:deployDuration\",\n    \"buildLog\": {\n      \"@id\": \"doctave:buildLog\",\n      \"@type\": \"@id\"\n    },\n    \"title\": \"schema:headline\",\n    \"content\": \"schema:text\",\n    \"parentId\": {\n      \"@id\": \"doctave:parentId\",\n      \"@type\": \"@id\"\n    },\n    \"order\": \"schema:position\",\n    \"snippet\": \"doctave:snippet\",\n    \"score\": \"doctave:score\",\n    \"query\": \"doctave:query\",\n    \"totalResults\": \"doctave:totalResults\",\n    \"results\": \"doctave:results\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"finishedAt\": \"doctave:finishedAt\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/doctave/refs/heads/main/json-ld/doctave-context.jsonld
tags:
- Documentation
- OpenAPI
- Platform
- Portals
- JSON-LD
- Linked Data
- Semantic Web
---
