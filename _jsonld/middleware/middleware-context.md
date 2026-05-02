---
class_count: 3
classes:
- name
- description
- url
context_file: json-ld/middleware-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/middleware/refs/heads/main/json-ld/middleware-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Middleware from Middleware.
layout: jsonld
name: Middleware Context
namespaces:
- prefix: Observability
  uri: https://schema.org/Service
- prefix: InfrastructureMonitoring
  uri: https://schema.org/Service
- prefix: APM
  uri: https://schema.org/Service
- prefix: LogManagement
  uri: https://schema.org/Service
- prefix: RealUserMonitoring
  uri: https://schema.org/Service
- prefix: DatabaseMonitoring
  uri: https://schema.org/Service
- prefix: ContainerMonitoring
  uri: https://schema.org/Service
- prefix: SyntheticMonitoring
  uri: https://schema.org/Service
- prefix: ServerlessMonitoring
  uri: https://schema.org/Service
- prefix: LLMObservability
  uri: https://schema.org/Service
properties:
- container: ''
  name: Middleware
  type: SoftwareApplication
property_count: 1
provider_name: Middleware
provider_slug: middleware
slug: middleware-context
source_filename: middleware-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"Middleware\": {\n      \"@id\": \"https://middleware.io\",\n      \"@type\": \"SoftwareApplication\"\n    },\n    \"Observability\": \"https://schema.org/Service\",\n    \"InfrastructureMonitoring\": \"https://schema.org/Service\",\n    \"APM\": \"https://schema.org/Service\",\n    \"LogManagement\": \"https://schema.org/Service\",\n    \"RealUserMonitoring\": \"https://schema.org/Service\",\n    \"DatabaseMonitoring\": \"https://schema.org/Service\",\n    \"ContainerMonitoring\": \"https://schema.org/Service\",\n    \"SyntheticMonitoring\": \"https://schema.org/Service\",\n    \"ServerlessMonitoring\": \"https://schema.org/Service\",\n    \"LLMObservability\": \"https://schema.org/Service\"\n  },\n  \"@type\": \"SoftwareApplication\",\n  \"name\": \"Middleware\",\n  \"description\": \"Cloud-native observability platform\
  \ offering full-stack monitoring including infrastructure, APM, logs, RUM, database, container, synthetic, serverless, and LLM observability.\",\n  \"url\": \"https://middleware.io\",\n  \"applicationCategory\": \"Observability\"\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/middleware/refs/heads/main/json-ld/middleware-context.jsonld
tags:
- AI Operations
- APM
- API Monitoring
- Container Monitoring
- Database Monitoring
- Infrastructure Monitoring
- LLM Observability
- Log Management
- Observability
- Real User Monitoring
- Synthetic Monitoring
- JSON-LD
- Linked Data
- Semantic Web
---
