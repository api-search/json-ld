---
class_count: 0
classes: []
context_file: json-ld/dbos-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dbos/refs/heads/main/json-ld/dbos-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dbos from DBOS.
layout: jsonld
name: Dbos Context
namespaces:
- prefix: dbos
  uri: https://docs.dbos.dev/python/reference/
properties:
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: Step
  type: ''
- container: ''
  name: Transaction
  type: ''
- container: ''
  name: Scheduled
  type: ''
- container: ''
  name: KafkaConsumer
  type: ''
- container: ''
  name: Queue
  type: ''
property_count: 6
provider_name: DBOS
provider_slug: dbos
slug: dbos-context
source_filename: dbos-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dbos\": \"https://docs.dbos.dev/python/reference/\",\n    \"Workflow\": {\n      \"@id\": \"dbos:decorators\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"max_recovery_attempts\": \"https://schema.org/maxValue\",\n        \"serialization_type\": \"https://schema.org/encodingFormat\",\n        \"validate_args\": \"https://schema.org/option\"\n      }\n    },\n    \"Step\": {\n      \"@id\": \"dbos:decorators\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"retries_allowed\": \"https://schema.org/option\",\n        \"interval_seconds\": \"https://schema.org/duration\",\n        \"max_attempts\": \"https://schema.org/maxValue\",\n        \"backoff_rate\": \"https://schema.org/value\"\n      }\n    },\n    \"Transaction\": {\n      \"@id\": \"dbos:decorators\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n   \
  \     \"isolation_level\": \"https://schema.org/additionalType\"\n      }\n    },\n    \"Scheduled\": {\n      \"@id\": \"dbos:decorators\",\n      \"@context\": {\n        \"cron\": \"https://schema.org/scheduledTime\"\n      }\n    },\n    \"KafkaConsumer\": {\n      \"@id\": \"dbos:decorators\",\n      \"@context\": {\n        \"topics\": \"https://schema.org/about\",\n        \"config\": \"https://schema.org/additionalProperty\",\n        \"in_order\": \"https://schema.org/option\"\n      }\n    },\n    \"Queue\": {\n      \"@id\": \"dbos:queues\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"concurrency\": \"https://schema.org/maxValue\",\n        \"rate_limit\": \"https://schema.org/value\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dbos/refs/heads/main/json-ld/dbos-context.jsonld
tags:
- API Composition
- Durable Execution
- Postgres
- Queues
- Scheduled Jobs
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
