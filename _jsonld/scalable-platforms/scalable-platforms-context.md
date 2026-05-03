---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Vercel REST API
  slug: ''
  spec_type: OpenAPI
  url: https://openapi.vercel.sh/
- filename: openapi.yaml
  format: yaml
  label: Netlify API
  slug: ''
  spec_type: OpenAPI
  url: https://open-api.netlify.com/
- filename: openapi.yaml
  format: yaml
  label: Cloudflare API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/cloudflare/api-schemas/main/openapi.yaml
- filename: api-docs
  format: yaml
  label: Heroku Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://devcenter.heroku.com/api-docs
- filename: openapi.yaml
  format: yaml
  label: Fly.io Machines API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/superfly/fly-openapi/refs/heads/main/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Render API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/renderinc/openapi-specs/main/openapi.yaml
- filename: openapi.json
  format: json
  label: Northflank API
  slug: ''
  spec_type: OpenAPI
  url: https://api.northflank.com/v1/openapi.json
class_count: 18
classes:
- id
- name
- description
- provider
- appId
- appName
- environment
- status
- url
- gitCommit
- build
- runtime
- scaling
- scaleToZero
- region
- createdAt
- readyAt
- tags
context_file: json-ld/scalable-platforms-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalable-platforms/refs/heads/main/json-ld/scalable-platforms-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalable Platforms from Scalable Platforms.
layout: jsonld
name: Scalable Platforms Context
namespaces:
- prefix: plat
  uri: https://raw.githubusercontent.com/api-evangelist/scalable-platforms/main/json-ld/scalable-platforms-context.jsonld#
properties:
- container: ''
  name: PlatformDeployment
  type: reference
- container: ''
  name: PaaSPlatform
  type: reference
- container: ''
  name: EdgeFunction
  type: reference
- container: ''
  name: BuildPipeline
  type: reference
- container: ''
  name: ServerlessFunction
  type: reference
- container: ''
  name: PreviewDeployment
  type: reference
- container: list
  name: regions
  type: ''
property_count: 7
provider_name: Scalable Platforms
provider_slug: scalable-platforms
slug: scalable-platforms-context
source_filename: scalable-platforms-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"plat\": \"https://raw.githubusercontent.com/api-evangelist/scalable-platforms/main/json-ld/scalable-platforms-context.jsonld#\",\n\n    \"PlatformDeployment\": {\n      \"@id\": \"plat:PlatformDeployment\",\n      \"@type\": \"@id\",\n      \"comment\": \"A deployment of an application on a PaaS platform.\"\n    },\n    \"PaaSPlatform\": {\n      \"@id\": \"plat:PaaSPlatform\",\n      \"@type\": \"@id\",\n      \"comment\": \"A Platform-as-a-Service provider abstracting infrastructure management.\"\n    },\n    \"EdgeFunction\": {\n      \"@id\": \"plat:EdgeFunction\",\n      \"@type\": \"@id\",\n      \"comment\": \"A serverless function running at the network edge close to users.\"\n    },\n    \"BuildPipeline\": {\n      \"@id\": \"plat:BuildPipeline\",\n      \"@type\": \"@id\",\n      \"comment\": \"The CI/CD pipeline that compiles, tests, and deploys application code.\"\n   \
  \ },\n    \"ServerlessFunction\": {\n      \"@id\": \"plat:ServerlessFunction\",\n      \"@type\": \"@id\",\n      \"comment\": \"A function executed on-demand in a managed serverless runtime.\"\n    },\n    \"PreviewDeployment\": {\n      \"@id\": \"plat:PreviewDeployment\",\n      \"@type\": \"@id\",\n      \"comment\": \"An ephemeral deployment created per pull request for review.\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"provider\": \"plat:provider\",\n    \"appId\": \"plat:appId\",\n    \"appName\": \"schema:name\",\n    \"environment\": \"plat:environment\",\n    \"status\": \"schema:status\",\n    \"url\": \"schema:url\",\n    \"gitCommit\": \"plat:gitCommit\",\n    \"build\": \"plat:build\",\n    \"runtime\": \"plat:runtime\",\n    \"scaling\": \"plat:scaling\",\n    \"scaleToZero\": \"plat:scaleToZero\",\n    \"region\": \"plat:region\",\n    \"regions\": {\n      \"@id\": \"plat:regions\",\n      \"\
  @container\": \"@list\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"readyAt\": \"schema:dateModified\",\n    \"tags\": \"schema:keywords\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalable-platforms/refs/heads/main/json-ld/scalable-platforms-context.jsonld
tags:
- Cloud Infrastructure
- Deployment
- Developer Experience
- DevOps
- PaaS
- Platform
- Scalability
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
