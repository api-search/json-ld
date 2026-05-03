---
api_specs:
- filename: trpc-openapi.yml
  format: yaml
  label: tRPC HTTP Protocol
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/openapi/trpc-openapi.yml
class_count: 19
classes:
- code
- Router
- Procedure
- Query
- Mutation
- Subscription
- type
- path
- input
- output
- meta
- method
- protect
- summary
- description
- tags
- message
- stack
- httpStatus
context_file: json-ld/trpc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/json-ld/trpc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trpc from tRPC.
layout: jsonld
name: Trpc Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: tRPC
provider_slug: trpc
slug: trpc-context
source_filename: trpc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://trpc.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"code\": \"https://schema.org/SoftwareSourceCode\",\n\n    \"Router\": \"schema:APIReference\",\n    \"Procedure\": \"schema:EntryPoint\",\n    \"Query\": \"schema:EntryPoint\",\n    \"Mutation\": \"schema:EntryPoint\",\n    \"Subscription\": \"schema:EntryPoint\",\n\n    \"type\": \"schema:additionalType\",\n    \"path\": \"schema:urlTemplate\",\n    \"input\": \"schema:parameterInput\",\n    \"output\": \"schema:result\",\n    \"meta\": \"schema:additionalProperty\",\n    \"method\": \"schema:httpMethod\",\n    \"protect\": \"schema:requiresSubscription\",\n    \"summary\": \"schema:abstract\",\n    \"description\": \"schema:description\",\n    \"tags\": \"schema:keywords\",\n    \"message\": \"schema:text\",\n    \"code\": \"schema:identifier\",\n    \"stack\": \"schema:codeRepository\",\n    \"httpStatus\"\
  : \"httpStatusCode\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trpc/refs/heads/main/json-ld/trpc-context.jsonld
tags:
- API Composition
- API Framework
- BFF
- End-to-End Type Safety
- RPC
- TypeScript
- JSON-LD
- Linked Data
- Semantic Web
---
