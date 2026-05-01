---
api_specs:
- filename: dapr-state-management-openapi.yml
  format: yaml
  label: Dapr State Management API
  slug: state-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-state-management-openapi.yml
- filename: dapr-pubsub-openapi.yml
  format: yaml
  label: Dapr Pub/Sub API
  slug: pubsub
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-pubsub-openapi.yml
- filename: dapr-service-invocation-openapi.yml
  format: yaml
  label: Dapr Service Invocation API
  slug: service-invocation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-service-invocation-openapi.yml
- filename: dapr-bindings-openapi.yml
  format: yaml
  label: Dapr Bindings API
  slug: bindings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-bindings-openapi.yml
- filename: dapr-secrets-openapi.yml
  format: yaml
  label: Dapr Secrets API
  slug: secrets
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-secrets-openapi.yml
- filename: dapr-actors-openapi.yml
  format: yaml
  label: Dapr Actors API
  slug: actors
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-actors-openapi.yml
- filename: dapr-workflow-openapi.yml
  format: yaml
  label: Dapr Workflow API
  slug: workflow
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-workflow-openapi.yml
- filename: dapr-configuration-openapi.yml
  format: yaml
  label: Dapr Configuration API
  slug: configuration
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-configuration-openapi.yml
- filename: dapr-distributed-lock-openapi.yml
  format: yaml
  label: Dapr Distributed Lock API
  slug: distributed-lock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-distributed-lock-openapi.yml
- filename: dapr-cryptography-openapi.yml
  format: yaml
  label: Dapr Cryptography API
  slug: cryptography
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-cryptography-openapi.yml
- filename: dapr-jobs-openapi.yml
  format: yaml
  label: Dapr Jobs API
  slug: jobs
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-jobs-openapi.yml
- filename: dapr-health-openapi.yml
  format: yaml
  label: Dapr Health API
  slug: health
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-health-openapi.yml
- filename: dapr-metadata-openapi.yml
  format: yaml
  label: Dapr Metadata API
  slug: metadata
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/openapi/dapr-metadata-openapi.yml
class_count: 0
classes: []
context_file: json-ld/dapr-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/json-ld/dapr-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dapr from Dapr.
layout: jsonld
name: Dapr Context
namespaces:
- prefix: dapr
  uri: https://docs.dapr.io/reference/api/
properties:
- container: ''
  name: StateItem
  type: ''
- container: ''
  name: CloudEvent
  type: ''
- container: ''
  name: Actor
  type: ''
- container: ''
  name: Binding
  type: ''
- container: ''
  name: Secret
  type: ''
- container: ''
  name: ConfigurationItem
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: Metadata
  type: ''
property_count: 9
provider_name: Dapr
provider_slug: dapr
slug: dapr-context
source_filename: dapr-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dapr\": \"https://docs.dapr.io/reference/api/\",\n    \"StateItem\": {\n      \"@id\": \"dapr:state_api\",\n      \"@context\": {\n        \"key\": \"https://schema.org/identifier\",\n        \"value\": \"https://schema.org/value\",\n        \"etag\": \"https://schema.org/version\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"options\": \"https://schema.org/actionOption\"\n      }\n    },\n    \"CloudEvent\": {\n      \"@id\": \"https://cloudevents.io/\",\n      \"@context\": {\n        \"specversion\": \"https://schema.org/schemaVersion\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"source\": \"https://schema.org/sourceOrganization\",\n        \"id\": \"https://schema.org/identifier\",\n        \"subject\": \"https://schema.org/about\",\n        \"time\": \"https://schema.org/dateCreated\",\n        \"datacontenttype\": \"https://schema.org/encodingFormat\"\
  ,\n        \"data\": \"https://schema.org/value\",\n        \"topic\": \"https://schema.org/about\",\n        \"pubsubname\": \"https://schema.org/name\",\n        \"traceid\": \"https://schema.org/identifier\",\n        \"traceparent\": \"https://schema.org/identifier\",\n        \"tracestate\": \"https://schema.org/identifier\"\n      }\n    },\n    \"Actor\": {\n      \"@id\": \"dapr:actors_api\",\n      \"@context\": {\n        \"actorType\": \"https://schema.org/additionalType\",\n        \"actorId\": \"https://schema.org/identifier\",\n        \"timer\": \"https://schema.org/scheduledTime\",\n        \"reminder\": \"https://schema.org/scheduledTime\"\n      }\n    },\n    \"Binding\": {\n      \"@id\": \"dapr:bindings_api\",\n      \"@context\": {\n        \"data\": \"https://schema.org/value\",\n        \"metadata\": \"https://schema.org/additionalProperty\",\n        \"operation\": \"https://schema.org/actionOption\"\n      }\n    },\n    \"Secret\": {\n      \"@id\": \"dapr:secrets_api\"\
  ,\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"store\": \"https://schema.org/provider\",\n        \"values\": \"https://schema.org/value\",\n        \"metadata\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"ConfigurationItem\": {\n      \"@id\": \"dapr:configuration_api\",\n      \"@context\": {\n        \"key\": \"https://schema.org/identifier\",\n        \"value\": \"https://schema.org/value\",\n        \"version\": \"https://schema.org/version\",\n        \"metadata\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"Workflow\": {\n      \"@id\": \"dapr:workflow_api\",\n      \"@context\": {\n        \"instanceID\": \"https://schema.org/identifier\",\n        \"workflowName\": \"https://schema.org/name\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"lastUpdatedAt\": \"https://schema.org/dateModified\",\n        \"runtimeStatus\": \"https://schema.org/status\",\n        \"properties\"\
  : \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"Job\": {\n      \"@id\": \"dapr:jobs_api\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"schedule\": \"https://schema.org/repeatFrequency\",\n        \"dueTime\": \"https://schema.org/scheduledTime\",\n        \"repeats\": \"https://schema.org/repeatCount\",\n        \"ttl\": \"https://schema.org/duration\",\n        \"data\": \"https://schema.org/value\"\n      }\n    },\n    \"Metadata\": {\n      \"@id\": \"dapr:metadata_api\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"runtimeVersion\": \"https://schema.org/softwareVersion\",\n        \"enabledFeatures\": \"https://schema.org/featureList\",\n        \"actors\": \"https://schema.org/hasPart\",\n        \"components\": \"https://schema.org/hasPart\",\n        \"subscriptions\": \"https://schema.org/hasPart\",\n        \"httpEndpoints\": \"https://schema.org/hasPart\",\n        \"appConnectionProperties\"\
  : \"https://schema.org/connectionType\",\n        \"extended\": \"https://schema.org/additionalProperty\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dapr/refs/heads/main/json-ld/dapr-context.jsonld
tags:
- Distributed Systems
- Microservices
- Platform
- Pub/Sub
- State Management
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
