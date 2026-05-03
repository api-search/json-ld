---
api_specs:
- filename: statsig-http-api-openapi.yml
  format: yaml
  label: Statsig HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-http-api-openapi.yml
- filename: statsig-console-api-openapi.yml
  format: yaml
  label: Statsig Console API
  slug: console-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-console-api-openapi.yml
- filename: statsig-client-sdk-api-openapi.yml
  format: yaml
  label: Statsig Client SDK API
  slug: client-sdk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-client-sdk-api-openapi.yml
- filename: statsig-server-sdk-api-openapi.yml
  format: yaml
  label: Statsig Server SDK API
  slug: server-sdk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-server-sdk-api-openapi.yml
- filename: statsig-events-api-openapi.yml
  format: yaml
  label: Statsig Events API
  slug: events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/openapi/statsig-events-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/statsig-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/json-ld/statsig-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Statsig from statsig.
layout: jsonld
name: Statsig Context
namespaces:
- prefix: statsig
  uri: https://schemas.statsig.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: FeatureGate
  type: ''
- container: ''
  name: DynamicConfig
  type: ''
- container: ''
  name: Experiment
  type: ''
- container: ''
  name: ExperimentGroup
  type: ''
- container: ''
  name: Layer
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: Rule
  type: ''
- container: ''
  name: Condition
  type: ''
- container: ''
  name: Metric
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: StatsigUser
  type: ''
- container: ''
  name: Holdout
  type: ''
- container: ''
  name: Autotune
  type: ''
property_count: 13
provider_name: statsig
provider_slug: statsig
slug: statsig-context
source_filename: statsig-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"statsig\": \"https://schemas.statsig.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"FeatureGate\": {\n      \"@id\": \"statsig:FeatureGate\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"isEnabled\": \"statsig:isEnabled\",\n        \"status\": \"statsig:status\",\n        \"rules\": {\n          \"@id\": \"statsig:rules\",\n          \"@container\": \"@set\"\n        },\n        \"overrides\": \"statsig:overrides\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"targetApps\": {\n          \"@id\": \"statsig:targetApps\",\n          \"@container\": \"@set\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"lastModifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DynamicConfig\": {\n      \"@id\": \"statsig:DynamicConfig\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"isEnabled\": \"statsig:isEnabled\",\n        \"defaultValue\": \"statsig:defaultValue\",\n        \"rules\": {\n          \"@id\": \"statsig:rules\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Experiment\": {\n      \"@id\": \"statsig:Experiment\",\n      \"@context\"\
  : {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"hypothesis\": \"statsig:hypothesis\",\n        \"status\": \"statsig:status\",\n        \"groups\": {\n          \"@id\": \"statsig:groups\",\n          \"@container\": \"@set\"\n        },\n        \"allocation\": \"statsig:allocation\",\n        \"layer\": {\n          \"@id\": \"statsig:layer\",\n          \"@type\": \"@id\"\n        },\n        \"targetingGate\": {\n          \"@id\": \"statsig:targetingGate\",\n          \"@type\": \"@id\"\n        },\n        \"primaryMetrics\": {\n          \"@id\": \"statsig:primaryMetrics\",\n          \"@container\": \"@set\"\n        },\n        \"secondaryMetrics\": {\n          \"@id\": \"statsig:secondaryMetrics\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"startedTime\": {\n          \"@id\": \"statsig:startedTime\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ExperimentGroup\": {\n      \"@id\": \"statsig:ExperimentGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"size\": \"statsig:size\",\n        \"parameterValues\": \"statsig:parameterValues\"\n      }\n    },\n\n    \"Layer\": {\n      \"@id\": \"statsig:Layer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"parameters\": \"statsig:parameters\",\n        \"experiments\": {\n          \"@id\": \"statsig:experiments\",\n          \"@container\": \"@set\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\
  \n        }\n      }\n    },\n\n    \"Segment\": {\n      \"@id\": \"statsig:Segment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"statsig:segmentType\",\n        \"rules\": {\n          \"@id\": \"statsig:rules\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Rule\": {\n      \"@id\": \"statsig:Rule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"passPercentage\": \"statsig:passPercentage\",\n        \"conditions\": {\n          \"@id\": \"statsig:conditions\",\n          \"@container\": \"@set\"\n        },\n        \"returnValue\": \"statsig:returnValue\",\n        \"environments\": {\n          \"@id\": \"statsig:environments\"\
  ,\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Condition\": {\n      \"@id\": \"statsig:Condition\",\n      \"@context\": {\n        \"type\": \"statsig:conditionType\",\n        \"targetValue\": \"statsig:targetValue\",\n        \"operator\": \"statsig:operator\",\n        \"field\": \"statsig:field\"\n      }\n    },\n\n    \"Metric\": {\n      \"@id\": \"statsig:Metric\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"statsig:metricType\",\n        \"eventName\": \"statsig:eventName\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"statsig:Event\",\n      \"@context\": {\n        \"eventName\": \"schema:name\",\n        \"user\": {\n          \"@id\": \"statsig:user\",\n          \"@type\": \"@id\"\n        },\n        \"time\": {\n          \"@id\": \"dcterms:date\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"value\": \"schema:value\",\n        \"metadata\": \"statsig:metadata\"\n      }\n    },\n\n    \"StatsigUser\": {\n      \"@id\": \"statsig:StatsigUser\",\n      \"@context\": {\n        \"userID\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"country\": \"schema:addressCountry\",\n        \"locale\": \"schema:inLanguage\",\n        \"appVersion\": \"schema:softwareVersion\"\n      }\n    },\n\n    \"Holdout\": {\n      \"@id\": \"statsig:Holdout\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"passPercentage\": \"statsig:passPercentage\",\n        \"isEnabled\": \"statsig:isEnabled\"\n      }\n    },\n\n    \"Autotune\": {\n      \"@id\": \"statsig:Autotune\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\"\
  : \"statsig:status\",\n        \"variants\": {\n          \"@id\": \"statsig:variants\",\n          \"@container\": \"@set\"\n        },\n        \"successMetric\": \"statsig:successMetric\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/statsig/refs/heads/main/json-ld/statsig-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
