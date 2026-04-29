---
api_specs:
- filename: coredns-health-openapi.yml
  format: yaml
  label: CoreDNS Health API
  slug: coredns-health-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coredns/refs/heads/main/openapi/coredns-health-openapi.yml
- filename: coredns-metrics-openapi.yml
  format: yaml
  label: CoreDNS Metrics API
  slug: coredns-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coredns/refs/heads/main/openapi/coredns-metrics-openapi.yml
class_count: 0
classes: []
context_file: json-ld/coredns-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/coredns/refs/heads/main/json-ld/coredns-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Coredns from CoreDNS.
layout: jsonld
name: Coredns Context
namespaces:
- prefix: coredns
  uri: https://coredns.io/plugins/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: dns
  uri: https://www.iana.org/assignments/dns-parameters/
properties:
- container: ''
  name: ServerBlock
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: DNSRecord
  type: ''
- container: ''
  name: Zone
  type: ''
- container: ''
  name: ForwardConfig
  type: ''
- container: ''
  name: CacheConfig
  type: ''
- container: ''
  name: KubernetesConfig
  type: ''
- container: ''
  name: MetricSample
  type: ''
property_count: 8
provider_name: CoreDNS
provider_slug: coredns
slug: coredns-context
source_filename: coredns-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"coredns\": \"https://coredns.io/plugins/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"dns\": \"https://www.iana.org/assignments/dns-parameters/\",\n\n    \"ServerBlock\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"zones\": {\n          \"@id\": \"schema:serviceArea\",\n          \"@container\": \"@set\"\n        },\n        \"plugins\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Plugin\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"args\": {\n          \"@id\": \"schema:parameter\",\n          \"@container\": \"@set\"\n        },\n        \"options\": \"schema:additionalProperty\"\n      }\n    },\n\n    \"DNSRecord\": {\n      \"@id\": \"dns:resource-record-types\"\
  ,\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"dns:resource-record-types\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ttl\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"rdata\": \"schema:value\",\n        \"zone\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Zone\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"origin\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ttl\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"records\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ForwardConfig\": {\n      \"@id\"\
  : \"coredns:forward\",\n      \"@context\": {\n        \"upstreams\": {\n          \"@id\": \"schema:serviceUrl\",\n          \"@container\": \"@set\"\n        },\n        \"policy\": \"schema:actionOption\",\n        \"health_check\": \"schema:duration\",\n        \"max_fails\": \"schema:numberOfItems\",\n        \"tls_servername\": \"schema:hostName\"\n      }\n    },\n\n    \"CacheConfig\": {\n      \"@id\": \"coredns:cache\",\n      \"@context\": {\n        \"ttl\": \"schema:duration\",\n        \"negative_ttl\": \"schema:duration\",\n        \"capacity\": \"schema:numberOfItems\"\n      }\n    },\n\n    \"KubernetesConfig\": {\n      \"@id\": \"coredns:kubernetes\",\n      \"@context\": {\n        \"cluster_domain\": {\n          \"@id\": \"schema:domainIncludes\",\n          \"@type\": \"xsd:string\"\n        },\n        \"namespaces\": {\n          \"@id\": \"schema:isPartOf\",\n          \"@container\": \"@set\"\n        },\n        \"ttl\": \"schema:duration\",\n        \"pods\"\
  : \"schema:actionOption\"\n      }\n    },\n\n    \"MetricSample\": {\n      \"@id\": \"schema:DataFeedItem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"value\": \"schema:value\",\n        \"labels\": \"schema:additionalProperty\",\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/coredns/refs/heads/main/json-ld/coredns-context.jsonld
tags:
- Apache 2.0
- Cloud Native
- CNCF
- DNS
- Go
- Graduated
- Kubernetes
- Networking
- Open Source
- Plugins
- Prometheus
- Service Discovery
- JSON-LD
- Linked Data
- Semantic Web
---
