---
class_count: 0
classes: []
context_file: json-ld/nops-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nops/refs/heads/main/json-ld/nops-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nops from nOps.
layout: jsonld
name: Nops Context
namespaces:
- prefix: nops
  uri: https://app.nops.io/
properties:
- container: ''
  name: MapMigrationProject
  type: ''
- container: ''
  name: MapMigrationProduct
  type: ''
- container: ''
  name: MapMigrationResource
  type: ''
- container: ''
  name: Scheduler
  type: ''
property_count: 4
provider_name: nOps
provider_slug: nops
slug: nops-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"nops\": \"https://app.nops.io/\",\n    \"MapMigrationProject\": {\n      \"@id\": \"nops:map-migration-project\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"status\": \"https://schema.org/status\",\n        \"created_at\": \"https://schema.org/dateCreated\",\n        \"updated_at\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"MapMigrationProduct\": {\n      \"@id\": \"nops:map-migration-product\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"project_id\": {\n          \"@id\": \"nops:map-migration-project\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"MapMigrationResource\": {\n      \"@id\": \"nops:map-migration-resource\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\"\
  ,\n        \"resource_type\": \"https://schema.org/category\",\n        \"resource_id\": \"https://schema.org/identifier\",\n        \"project_id\": {\n          \"@id\": \"nops:map-migration-project\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Scheduler\": {\n      \"@id\": \"nops:scheduler\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"enabled\": \"https://schema.org/actionStatus\",\n        \"project_id\": \"https://schema.org/identifier\",\n        \"schedule\": \"https://schema.org/Schedule\",\n        \"resources\": \"https://schema.org/hasPart\",\n        \"created_at\": \"https://schema.org/dateCreated\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nops/refs/heads/main/json-ld/nops-context.jsonld
tags:
- Costs
- FinOps
- JSON-LD
- Linked Data
- Semantic Web
---
