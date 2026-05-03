---
api_specs:
- filename: prometheus-http-api-openapi.yml
  format: yaml
  label: Prometheus HTTP API
  slug: prometheus-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/openapi/prometheus-http-api-openapi.yml
- filename: prometheus-management-api-openapi.yml
  format: yaml
  label: Prometheus Management API
  slug: prometheus-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/openapi/prometheus-management-api-openapi.yml
- filename: prometheus-pushgateway-api-openapi.yml
  format: yaml
  label: Prometheus Pushgateway API
  slug: prometheus-pushgateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/openapi/prometheus-pushgateway-api-openapi.yml
- filename: prometheus-alertmanager-api-openapi.yml
  format: yaml
  label: Prometheus Alertmanager API
  slug: prometheus-alertmanager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/openapi/prometheus-alertmanager-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/prometheus-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/json-ld/prometheus-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Prometheus from Prometheus.
layout: jsonld
name: Prometheus Context
namespaces:
- prefix: prom
  uri: https://prometheus.io/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: prov
  uri: http://www.w3.org/ns/prov#
- prefix: time
  uri: http://www.w3.org/2006/time#
properties:
- container: ''
  name: TimeSeries
  type: ''
- container: ''
  name: MetricFamily
  type: ''
- container: ''
  name: AlertingRule
  type: ''
- container: ''
  name: RecordingRule
  type: ''
- container: ''
  name: RuleGroup
  type: ''
- container: ''
  name: Alert
  type: ''
- container: ''
  name: Silence
  type: ''
- container: ''
  name: ScrapeTarget
  type: ''
- container: ''
  name: AlertGroup
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: startTime
  type: dateTime
property_count: 13
provider_name: Prometheus
provider_slug: prometheus
slug: prometheus-context
source_filename: prometheus-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"prom\": \"https://prometheus.io/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n    \"time\": \"http://www.w3.org/2006/time#\",\n\n    \"TimeSeries\": {\n      \"@id\": \"prom:TimeSeries\",\n      \"@context\": {\n        \"metric\": {\n          \"@id\": \"prom:labels\",\n          \"@container\": \"@index\"\n        },\n        \"values\": {\n          \"@id\": \"prom:values\",\n          \"@container\": \"@list\"\n        },\n        \"value\": {\n          \"@id\": \"prom:value\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"MetricFamily\": {\n      \"@id\": \"prom:MetricFamily\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"help\": {\n          \"@id\": \"rdfs:comment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"prom:metricType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"unit\": {\n          \"@id\": \"schema:unitText\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AlertingRule\": {\n      \"@id\": \"prom:AlertingRule\",\n      \"@context\": {\n        \"alert\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expr\": {\n          \"@id\": \"prom:expression\",\n          \"@type\": \"xsd:string\"\n        },\n        \"for\": {\n          \"@id\": \"prom:pendingDuration\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"prom:ruleLabels\",\n          \"@container\": \"@index\"\n        },\n        \"annotations\": {\n          \"@id\": \"prom:ruleAnnotations\",\n          \"\
  @container\": \"@index\"\n        }\n      }\n    },\n\n    \"RecordingRule\": {\n      \"@id\": \"prom:RecordingRule\",\n      \"@context\": {\n        \"record\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expr\": {\n          \"@id\": \"prom:expression\",\n          \"@type\": \"xsd:string\"\n        },\n        \"labels\": {\n          \"@id\": \"prom:ruleLabels\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"RuleGroup\": {\n      \"@id\": \"prom:RuleGroup\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"interval\": {\n          \"@id\": \"prom:evaluationInterval\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rules\": {\n          \"@id\": \"prom:rules\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Alert\": {\n      \"@id\": \"prom:Alert\",\n      \"@context\"\
  : {\n        \"labels\": {\n          \"@id\": \"prom:alertLabels\",\n          \"@container\": \"@index\"\n        },\n        \"annotations\": {\n          \"@id\": \"prom:alertAnnotations\",\n          \"@container\": \"@index\"\n        },\n        \"state\": {\n          \"@id\": \"prom:alertState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"activeAt\": {\n          \"@id\": \"prom:activeAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"value\": {\n          \"@id\": \"prom:alertValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"generatorURL\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"fingerprint\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startsAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endsAt\": {\n          \"@id\": \"prom:endsAt\",\n          \"\
  @type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Silence\": {\n      \"@id\": \"prom:Silence\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"matchers\": {\n          \"@id\": \"prom:silenceMatchers\",\n          \"@container\": \"@set\"\n        },\n        \"startsAt\": {\n          \"@id\": \"prom:silenceStartsAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endsAt\": {\n          \"@id\": \"prom:silenceEndsAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"comment\": {\n          \"@id\": \"rdfs:comment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ScrapeTarget\": {\n     \
  \ \"@id\": \"prom:ScrapeTarget\",\n      \"@context\": {\n        \"scrapeUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": {\n          \"@id\": \"prom:targetLabels\",\n          \"@container\": \"@index\"\n        },\n        \"health\": {\n          \"@id\": \"schema:healthCondition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastScrape\": {\n          \"@id\": \"prom:lastScrape\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastScrapeDuration\": {\n          \"@id\": \"prom:lastScrapeDuration\",\n          \"@type\": \"xsd:double\"\n        },\n        \"scrapePool\": {\n          \"@id\": \"prom:scrapePool\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AlertGroup\": {\n      \"@id\": \"prom:AlertGroup\",\n      \"@context\": {\n        \"groupLabels\": {\n          \"@id\": \"prom:groupLabels\",\n          \"@container\": \"@index\"\n        },\n        \"commonLabels\"\
  : {\n          \"@id\": \"prom:commonLabels\",\n          \"@container\": \"@index\"\n        },\n        \"commonAnnotations\": {\n          \"@id\": \"prom:commonAnnotations\",\n          \"@container\": \"@index\"\n        },\n        \"receiver\": {\n          \"@id\": \"prom:receiver\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"prom:groupStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"externalURL\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"alerts\": {\n          \"@id\": \"prom:alerts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\"\
  : {\n      \"@id\": \"prov:startedAtTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/prometheus/refs/heads/main/json-ld/prometheus-context.jsonld
tags:
- Alerting
- Metrics
- Monitoring
- Observability
- Time Series
- JSON-LD
- Linked Data
- Semantic Web
---
