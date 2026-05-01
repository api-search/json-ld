---
api_specs:
- filename: fluentd-forward-protocol-asyncapi.yml
  format: yaml
  label: Fluentd Forward Protocol
  slug: fluentd-forward-protocol
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/asyncapi/fluentd-forward-protocol-asyncapi.yml
- filename: fluentd-http-input-openapi.yml
  format: yaml
  label: Fluentd HTTP Input API
  slug: fluentd-http-input
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/openapi/fluentd-http-input-openapi.yml
class_count: 0
classes: []
context_file: json-ld/fluentd-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/json-ld/fluentd-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fluentd from Fluentd.
layout: jsonld
name: Fluentd Context
namespaces:
- prefix: fluentd
  uri: https://docs.fluentd.org/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: LogEvent
  type: ''
- container: ''
  name: Record
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: InputPlugin
  type: ''
- container: ''
  name: OutputPlugin
  type: ''
- container: ''
  name: Buffer
  type: ''
- container: ''
  name: ForwardMessage
  type: ''
property_count: 7
provider_name: Fluentd
provider_slug: fluentd
slug: fluentd-context
source_filename: fluentd-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fluentd\": \"https://docs.fluentd.org/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"LogEvent\": {\n      \"@id\": \"fluentd:plugin-development/api-plugin-base\",\n      \"@context\": {\n        \"tag\": {\n          \"@id\": \"fluentd:routing\",\n          \"@type\": \"xsd:string\"\n        },\n        \"time\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"record\": {\n          \"@id\": \"schema:value\"\n        }\n      }\n    },\n\n    \"Record\": {\n      \"@id\": \"schema:DataFeedItem\",\n      \"@context\": {\n        \"message\": \"schema:description\",\n        \"level\": \"schema:category\",\n        \"host\": \"schema:hostName\",\n        \"service\": \"schema:name\",\n        \"pid\": \"schema:identifier\"\n      }\n    },\n\n    \"Plugin\": {\n\
  \      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"@type\": \"schema:additionalType\",\n        \"@id\": \"schema:identifier\",\n        \"log_level\": \"schema:category\",\n        \"tag\": \"schema:keywords\"\n      }\n    },\n\n    \"InputPlugin\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"bind\": \"schema:url\",\n        \"port\": \"schema:portNumber\",\n        \"format\": \"schema:encodingFormat\"\n      }\n    },\n\n    \"OutputPlugin\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"host\": \"schema:hostName\",\n        \"port\": \"schema:portNumber\",\n        \"buffer\": \"schema:hasPart\"\n      }\n    },\n\n    \"Buffer\": {\n      \"@id\": \"schema:DataCatalog\",\n      \"@context\": {\n        \"path\": \"schema:contentUrl\",\n        \"chunk_limit_size\": \"schema:fileSize\",\n        \"queue_limit_length\": \"schema:numberOfItems\",\n        \"flush_interval\":\
  \ \"schema:duration\",\n        \"retry_max_times\": \"schema:repeatCount\"\n      }\n    },\n\n    \"ForwardMessage\": {\n      \"@id\": \"fluentd:protocol\",\n      \"@context\": {\n        \"tag\": {\n          \"@id\": \"fluentd:routing\",\n          \"@type\": \"xsd:string\"\n        },\n        \"entries\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        },\n        \"chunk\": \"schema:identifier\",\n        \"compressed\": \"schema:encodingFormat\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fluentd/refs/heads/main/json-ld/fluentd-context.jsonld
tags:
- Data Collection
- Logging
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
