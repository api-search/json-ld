---
api_specs:
- filename: thanos-query-api.yml
  format: yaml
  label: Thanos Query API
  slug: thanos-query-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-query-api.yml
- filename: thanos-store-gateway-openapi.yml
  format: yaml
  label: Thanos Store Gateway API
  slug: thanos-store-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-store-gateway-openapi.yml
- filename: thanos-sidecar-openapi.yml
  format: yaml
  label: Thanos Sidecar API
  slug: thanos-sidecar-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-sidecar-openapi.yml
- filename: thanos-ruler-openapi.yml
  format: yaml
  label: Thanos Ruler API
  slug: thanos-ruler-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-ruler-openapi.yml
- filename: thanos-receive-openapi.yml
  format: yaml
  label: Thanos Receive API
  slug: thanos-receive-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-receive-openapi.yml
- filename: thanos-compact-openapi.yml
  format: yaml
  label: Thanos Compact API
  slug: thanos-compact-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/openapi/thanos-compact-openapi.yml
class_count: 0
classes: []
context_file: json-ld/thanos-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/json-ld/thanos-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thanos from Thanos.
layout: jsonld
name: Thanos Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: prov
  uri: http://www.w3.org/ns/prov#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: thanos
  uri: https://thanos.io/vocabulary#
properties:
- container: ''
  name: MonitoringSystem
  type: ''
- container: ''
  name: Store
  type: ''
- container: ''
  name: TimeSeries
  type: ''
- container: ''
  name: Observation
  type: ''
- container: ''
  name: Query
  type: ''
- container: ''
  name: AlertingRule
  type: ''
- container: ''
  name: RecordingRule
  type: ''
- container: ''
  name: Alert
  type: ''
- container: ''
  name: Target
  type: ''
- container: ''
  name: RuleGroup
  type: ''
property_count: 10
provider_name: Thanos
provider_slug: thanos
slug: thanos-context
source_filename: thanos-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"thanos\": \"https://thanos.io/vocabulary#\",\n\n    \"MonitoringSystem\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:softwareVersion\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Store\": {\n      \"@id\": \"thanos:Store\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"storeType\": \"thanos:storeType\",\n        \"minTime\": {\n          \"@id\": \"schema:startDate\"\
  ,\n          \"@type\": \"xsd:long\"\n        },\n        \"maxTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:long\"\n        },\n        \"lastCheck\": {\n          \"@id\": \"thanos:lastHealthCheck\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastError\": \"thanos:lastError\",\n        \"labelSets\": \"thanos:labelSets\",\n        \"endpoint\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TimeSeries\": {\n      \"@id\": \"sosa:ObservationCollection\",\n      \"@context\": {\n        \"metric\": {\n          \"@id\": \"sosa:observedProperty\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"thanos:labels\",\n        \"values\": \"sosa:hasResult\"\n      }\n    },\n\n    \"Observation\": {\n      \"@id\": \"sosa:Observation\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"sosa:resultTime\",\n          \"@type\": \"xsd:dateTime\"\n    \
  \    },\n        \"value\": {\n          \"@id\": \"qudt:numericValue\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"Query\": {\n      \"@id\": \"thanos:Query\",\n      \"@context\": {\n        \"expression\": \"thanos:promqlExpression\",\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"step\": \"thanos:queryStep\",\n        \"dedup\": {\n          \"@id\": \"thanos:deduplication\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"partialResponse\": {\n          \"@id\": \"thanos:partialResponse\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"maxSourceResolution\": \"thanos:maxSourceResolution\"\n      }\n    },\n\n    \"AlertingRule\": {\n      \"@id\": \"thanos:AlertingRule\",\n      \"@context\": {\n        \"name\": \"schema:name\"\
  ,\n        \"query\": \"thanos:promqlExpression\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:duration\"\n        },\n        \"state\": \"thanos:alertState\",\n        \"labels\": \"thanos:labels\",\n        \"annotations\": \"thanos:annotations\",\n        \"lastEvaluation\": {\n          \"@id\": \"prov:generatedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RecordingRule\": {\n      \"@id\": \"thanos:RecordingRule\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"query\": \"thanos:promqlExpression\",\n        \"labels\": \"thanos:labels\",\n        \"lastEvaluation\": {\n          \"@id\": \"prov:generatedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Alert\": {\n      \"@id\": \"thanos:Alert\",\n      \"@context\": {\n        \"labels\": \"thanos:labels\",\n        \"annotations\": \"thanos:annotations\",\n        \"state\": \"thanos:alertState\"\
  ,\n        \"activeAt\": {\n          \"@id\": \"prov:generatedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"value\": {\n          \"@id\": \"qudt:numericValue\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Target\": {\n      \"@id\": \"thanos:ScrapeTarget\",\n      \"@context\": {\n        \"scrapeUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"health\": \"thanos:targetHealth\",\n        \"labels\": \"thanos:labels\",\n        \"lastScrape\": {\n          \"@id\": \"prov:generatedAtTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastScrapeDuration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"RuleGroup\": {\n      \"@id\": \"thanos:RuleGroup\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"file\": \"thanos:ruleFile\",\n        \"interval\": {\n          \"@id\":\
  \ \"schema:repeatFrequency\",\n          \"@type\": \"xsd:double\"\n        },\n        \"rules\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        },\n        \"partialResponseStrategy\": \"thanos:partialResponseStrategy\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thanos/refs/heads/main/json-ld/thanos-context.jsonld
tags:
- Metrics
- Monitoring
- Observability
- Prometheus
- Time Series Database
- JSON-LD
- Linked Data
- Semantic Web
---
