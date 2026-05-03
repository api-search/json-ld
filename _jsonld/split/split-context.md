---
api_specs:
- filename: split-admin-api-openapi.yml
  format: yaml
  label: Split Admin API
  slug: split-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/openapi/split-admin-api-openapi.yml
- filename: split-feature-flag-api-openapi.yml
  format: yaml
  label: Split Feature Flag API
  slug: split-feature-flag-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/openapi/split-feature-flag-api-openapi.yml
- filename: split-evaluator-api-openapi.yml
  format: yaml
  label: Split Evaluator API
  slug: split-evaluator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/openapi/split-evaluator-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/split-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/json-ld/split-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Split from Split.
layout: jsonld
name: Split Context
namespaces:
- prefix: split
  uri: https://api.split.io/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: TrafficType
  type: ''
- container: ''
  name: FeatureFlag
  type: ''
- container: ''
  name: FeatureFlagDefinition
  type: ''
- container: ''
  name: Treatment
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: Attribute
  type: ''
property_count: 11
provider_name: Split
provider_slug: split
slug: split-context
source_filename: split-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"split\": \"https://api.split.io/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Workspace\": {\n      \"@id\": \"split:Workspace\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"requiresTitleAndComments\": \"split:requiresTitleAndComments\"\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"split:Environment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"production\": \"split:production\"\n      }\n    },\n\n    \"TrafficType\": {\n      \"@id\": \"split:TrafficType\",\n      \"@context\": {\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"FeatureFlag\": {\n      \"@id\": \"split:FeatureFlag\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"trafficType\": {\n        \
  \  \"@id\": \"split:trafficType\",\n          \"@type\": \"@id\"\n        },\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"FeatureFlagDefinition\": {\n      \"@id\": \"split:FeatureFlagDefinition\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"environment\": {\n          \"@id\": \"split:environment\",\n          \"@type\": \"@id\"\n        },\n        \"killed\": \"split:killed\",\n        \"treatments\": {\n          \"@id\": \"split:treatments\",\n          \"@container\": \"@set\"\n        },\n        \"defaultTreatment\": \"split:defaultTreatment\",\n        \"baselineTreatment\": \"split:baselineTreatment\",\n        \"trafficAllocation\": \"split:trafficAllocation\",\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n         \
  \ \"@type\": \"xsd:dateTime\"\n        },\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Treatment\": {\n      \"@id\": \"split:Treatment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"configurations\": \"split:configurations\"\n      }\n    },\n\n    \"Segment\": {\n      \"@id\": \"split:Segment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"trafficType\": {\n          \"@id\": \"split:trafficType\",\n          \"@type\": \"@id\"\n        },\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"keys\": {\n          \"@id\": \"split:keys\",\n          \"\
  @container\": \"@set\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"split:User\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"status\": \"split:status\",\n        \"groups\": {\n          \"@id\": \"schema:memberOf\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"split:Group\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"split:ApiKey\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"apiKeyType\": \"split:apiKeyType\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Attribute\": {\n      \"@id\": \"split:Attribute\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\"\
  ,\n        \"dataType\": \"split:dataType\",\n        \"isSearchable\": \"split:isSearchable\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/json-ld/split-context.jsonld
tags:
- Experimentation
- Feature Flags
- Feature Management
- Rollouts
- SDKs
- JSON-LD
- Linked Data
- Semantic Web
---
