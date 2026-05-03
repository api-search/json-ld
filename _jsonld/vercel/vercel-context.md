---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Vercel REST API
  slug: vercel-rest-api
  spec_type: OpenAPI
  url: https://openapi.vercel.sh/
- filename: vercel-ai-gateway-openapi.yml
  format: yaml
  label: Vercel AI Gateway API
  slug: vercel-ai-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/openapi/vercel-ai-gateway-openapi.yml
- filename: vercel-v0-platform-openapi.yml
  format: yaml
  label: V0 Platform API
  slug: v0-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/openapi/vercel-v0-platform-openapi.yml
class_count: 30
classes:
- Deployment
- Project
- Domain
- EdgeFunction
- AIModel
- ChatSession
- GeneratedApp
- deploymentId
- projectId
- projectName
- teamId
- teamSlug
- framework
- deploymentUrl
- previewUrl
- productionUrl
- modelId
- provider
- modelName
- contextWindow
- inputTokenPrice
- outputTokenPrice
- chatId
- message
- generatedFiles
- filePath
- fileContent
- region
- buildDuration
- status
context_file: json-ld/vercel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/json-ld/vercel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vercel from Vercel.
layout: jsonld
name: Vercel Context
namespaces:
- prefix: vercel
  uri: https://vercel.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 2
provider_name: Vercel
provider_slug: vercel
slug: vercel-context
source_filename: vercel-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vercel\": \"https://vercel.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Deployment\": \"vercel:Deployment\",\n    \"Project\": \"vercel:Project\",\n    \"Domain\": \"vercel:Domain\",\n    \"EdgeFunction\": \"vercel:EdgeFunction\",\n    \"AIModel\": \"vercel:AIModel\",\n    \"ChatSession\": \"vercel:ChatSession\",\n    \"GeneratedApp\": \"vercel:GeneratedApp\",\n\n    \"deploymentId\": \"schema:identifier\",\n    \"projectId\": \"schema:identifier\",\n    \"projectName\": \"schema:name\",\n    \"teamId\": \"schema:identifier\",\n    \"teamSlug\": \"schema:identifier\",\n    \"framework\": \"vercel:framework\",\n    \"deploymentUrl\": \"schema:url\",\n    \"previewUrl\": \"schema:url\",\n    \"productionUrl\": \"schema:url\",\n\n    \"modelId\": \"schema:identifier\",\n    \"provider\": \"schema:provider\",\n    \"modelName\": \"schema:name\",\n    \"contextWindow\": \"vercel:contextWindow\"\
  ,\n    \"inputTokenPrice\": \"schema:price\",\n    \"outputTokenPrice\": \"schema:price\",\n\n    \"chatId\": \"schema:identifier\",\n    \"message\": \"schema:text\",\n    \"generatedFiles\": \"schema:hasPart\",\n    \"filePath\": \"schema:name\",\n    \"fileContent\": \"schema:text\",\n\n    \"region\": \"schema:addressRegion\",\n    \"buildDuration\": \"schema:duration\",\n    \"status\": \"schema:status\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/json-ld/vercel-context.jsonld
tags:
- AI Gateways
- Gateways
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
