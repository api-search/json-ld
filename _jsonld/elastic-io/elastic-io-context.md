---
api_specs:
- filename: elastic-io-platform-api-openapi.yml
  format: yaml
  label: Elastic.io
  slug: elastic-io
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elastic-io/refs/heads/main/openapi/elastic-io-platform-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/elastic-io-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/elastic-io/refs/heads/main/json-ld/elastic-io-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Elastic Io from Elastic.io.
layout: jsonld
name: Elastic Io Context
namespaces:
- prefix: elasticio
  uri: https://api.elastic.io/v2/
properties:
- container: ''
  name: flow
  type: reference
- container: ''
  name: workspace
  type: reference
- container: ''
  name: contract
  type: reference
- container: ''
  name: credential
  type: reference
- container: ''
  name: component
  type: reference
- container: ''
  name: execution
  type: reference
- container: ''
  name: topic
  type: reference
- container: ''
  name: recipe
  type: reference
property_count: 8
provider_name: Elastic.io
provider_slug: elastic-io
slug: elastic-io-context
source_filename: elastic-io-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"elasticio\": \"https://api.elastic.io/v2/\",\n    \"flow\": {\n      \"@id\": \"elasticio:flows\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"status\": \"https://schema.org/status\",\n        \"flowType\": {\n          \"@id\": \"elasticio:flowType\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"graph\": {\n          \"@id\": \"elasticio:graph\",\n          \"@type\": \"@id\",\n          \"@context\": {\n            \"nodes\": {\n              \"@id\": \"elasticio:nodes\",\n              \"@container\": \"@list\"\n            },\n            \"edges\": {\n              \"@id\": \"elasticio:edges\",\n              \"@container\": \"@list\"\n            }\n          }\n        },\n        \"cron\": {\n          \"@id\": \"elasticio:cron\",\n          \"\
  @type\": \"https://schema.org/Text\"\n        },\n        \"workspace\": {\n          \"@id\": \"elasticio:workspaces\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"workspace\": {\n      \"@id\": \"elasticio:workspaces\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"workspaceType\": {\n          \"@id\": \"elasticio:workspaceType\",\n          \"@type\": \"https://schema.org/Text\"\n        },\n        \"contract\": {\n          \"@id\": \"elasticio:contracts\",\n          \"@type\": \"@id\"\n        },\n        \"members\": {\n          \"@id\": \"elasticio:members\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\
  \n      }\n    },\n    \"contract\": {\n      \"@id\": \"elasticio:contracts\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"status\": \"https://schema.org/status\",\n        \"workspaces\": {\n          \"@id\": \"elasticio:workspaces\",\n          \"@container\": \"@set\"\n        },\n        \"members\": {\n          \"@id\": \"elasticio:members\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"credential\": {\n      \"@id\": \"elasticio:credentials\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"component\": {\n          \"@id\": \"elasticio:components\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"component\": {\n      \"@id\": \"elasticio:components\",\n      \"@type\": \"@id\",\n      \"@context\"\
  : {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"title\": \"https://schema.org/headline\"\n      }\n    },\n    \"execution\": {\n      \"@id\": \"elasticio:executions\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"status\": \"https://schema.org/status\",\n        \"startedAt\": \"https://schema.org/startDate\",\n        \"finishedAt\": \"https://schema.org/endDate\"\n      }\n    },\n    \"topic\": {\n      \"@id\": \"elasticio:topics\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"schema\": {\n          \"@id\": \"elasticio:topicSchema\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"recipe\": {\n      \"@id\": \"elasticio:recipes\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"title\": \"https://schema.org/headline\",\n        \"description\": \"https://schema.org/description\"\n      }\n    }\n\
  \  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/elastic-io/refs/heads/main/json-ld/elastic-io-context.jsonld
tags:
- Integrations
- iPaaS
- SaaS Integration
- JSON-LD
- Linked Data
- Semantic Web
---
