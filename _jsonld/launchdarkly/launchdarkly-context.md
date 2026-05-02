---
api_specs:
- filename: launchdarkly-rest-api-openapi.yml
  format: yaml
  label: LaunchDarkly REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/openapi/launchdarkly-rest-api-openapi.yml
- filename: launchdarkly-webhooks-asyncapi.yml
  format: yaml
  label: LaunchDarkly Webhooks API
  slug: webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/asyncapi/launchdarkly-webhooks-asyncapi.yml
- filename: launchdarkly-relay-proxy-openapi.yml
  format: yaml
  label: LaunchDarkly Relay Proxy
  slug: relay-proxy
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/openapi/launchdarkly-relay-proxy-openapi.yml
class_count: 0
classes: []
context_file: json-ld/launchdarkly-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/json-ld/launchdarkly-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Launchdarkly from launchdarkly.
layout: jsonld
name: Launchdarkly Context
namespaces:
- prefix: ld
  uri: https://launchdarkly.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: FeatureFlag
  type: ''
- container: ''
  name: Variation
  type: ''
- container: ''
  name: Project
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: AuditLogEntry
  type: ''
- container: ''
  name: Member
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Metric
  type: ''
- container: ''
  name: Experiment
  type: ''
- container: ''
  name: CustomRole
  type: ''
- container: ''
  name: AccessToken
  type: ''
- container: ''
  name: RelayProxyConfig
  type: ''
- container: ''
  name: ReleasePipeline
  type: ''
property_count: 15
provider_name: launchdarkly
provider_slug: launchdarkly
slug: launchdarkly-context
source_filename: launchdarkly-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ld\": \"https://launchdarkly.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"FeatureFlag\": {\n      \"@id\": \"ld:FeatureFlag\",\n      \"@context\": {\n        \"key\": \"ld:flagKey\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"kind\": \"ld:flagKind\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"temporary\": \"ld:isTemporary\",\n        \"archived\": \"ld:isArchived\",\n        \"variations\": {\n          \"@id\": \"ld:hasVariations\",\n          \"@container\": \"@set\"\n        },\n        \"environments\": {\n          \"@id\": \"ld:hasEnvironmentConfigs\"\
  ,\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"Variation\": {\n      \"@id\": \"ld:Variation\",\n      \"@context\": {\n        \"value\": \"ld:variationValue\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"Project\": {\n      \"@id\": \"ld:Project\",\n      \"@context\": {\n        \"key\": \"ld:projectKey\",\n        \"name\": \"schema:name\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"environments\": {\n          \"@id\": \"ld:hasEnvironments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"ld:Environment\",\n      \"@context\": {\n        \"key\": \"ld:environmentKey\",\n        \"name\": \"schema:name\",\n        \"color\": \"ld:displayColor\",\n        \"apiKey\": \"ld:sdkKey\",\n        \"mobileKey\": \"ld:mobileKey\",\n        \"defaultTtl\": \"\
  ld:defaultTtl\",\n        \"secureMode\": \"ld:isSecureMode\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Segment\": {\n      \"@id\": \"ld:Segment\",\n      \"@context\": {\n        \"key\": \"ld:segmentKey\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"included\": {\n          \"@id\": \"ld:includedContextKeys\",\n          \"@container\": \"@set\"\n        },\n        \"excluded\": {\n          \"@id\": \"ld:excludedContextKeys\",\n          \"@container\": \"@set\"\n        },\n        \"rules\": {\n          \"@id\": \"ld:hasRules\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Webhook\"\
  : {\n      \"@id\": \"ld:Webhook\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"name\": \"schema:name\",\n        \"on\": \"ld:isEnabled\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"AuditLogEntry\": {\n      \"@id\": \"ld:AuditLogEntry\",\n      \"@context\": {\n        \"date\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"kind\": \"ld:resourceKind\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"shortDescription\": \"ld:shortDescription\",\n        \"member\": {\n          \"@id\": \"ld:performedBy\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Member\": {\n      \"@id\": \"ld:Member\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"firstName\": \"schema:givenName\"\
  ,\n        \"lastName\": \"schema:familyName\",\n        \"role\": \"ld:builtInRole\",\n        \"customRoles\": {\n          \"@id\": \"ld:hasCustomRoles\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"ld:Team\",\n      \"@context\": {\n        \"key\": \"ld:teamKey\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"customRoleKeys\": {\n          \"@id\": \"ld:hasCustomRoleKeys\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Metric\": {\n      \"@id\": \"ld:Metric\",\n      \"@context\": {\n        \"key\": \"ld:metricKey\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"kind\": \"ld:metricKind\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"Experiment\": {\n      \"@id\": \"ld:Experiment\",\n      \"@context\": {\n        \"key\": \"ld:experimentKey\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CustomRole\": {\n      \"@id\": \"ld:CustomRole\",\n      \"@context\": {\n        \"key\": \"ld:roleKey\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"policy\": {\n          \"@id\": \"ld:hasPolicy\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"AccessToken\": {\n      \"@id\": \"ld:AccessToken\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"role\": \"ld:tokenRole\",\n        \"serviceToken\": \"ld:isServiceToken\",\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"lastUsed\": {\n          \"@id\": \"ld:lastUsed\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RelayProxyConfig\": {\n      \"@id\": \"ld:RelayProxyConfig\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"policy\": {\n          \"@id\": \"ld:hasPolicy\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ReleasePipeline\": {\n      \"@id\": \"ld:ReleasePipeline\",\n      \"@context\": {\n        \"key\": \"ld:pipelineKey\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"phases\": {\n          \"@id\": \"ld:hasPipelinePhases\",\n          \"@container\": \"@list\"\n        }\n     \
  \ }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/json-ld/launchdarkly-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
