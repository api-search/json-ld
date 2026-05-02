---
api_specs:
- filename: krakend-service-api-openapi.yml
  format: yaml
  label: KrakenD Service API
  slug: krakend-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/openapi/krakend-service-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/krakend-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/json-ld/krakend-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Krakend from KrakenD.
layout: jsonld
name: Krakend Context
namespaces:
- prefix: krakend
  uri: https://www.krakend.io/docs/
properties:
- container: ''
  name: ServiceConfig
  type: ''
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: Backend
  type: ''
- container: ''
  name: TLS
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: AsyncAgent
  type: ''
property_count: 6
provider_name: KrakenD
provider_slug: krakend
slug: krakend-context
source_filename: krakend-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"krakend\": \"https://www.krakend.io/docs/\",\n    \"ServiceConfig\": {\n      \"@id\": \"krakend:configuration/structure/\",\n      \"@context\": {\n        \"version\": \"https://schema.org/version\",\n        \"name\": \"https://schema.org/name\",\n        \"port\": \"https://schema.org/identifier\",\n        \"host\": \"https://schema.org/hostingOrganization\",\n        \"timeout\": \"https://schema.org/duration\",\n        \"cache_ttl\": \"https://schema.org/duration\",\n        \"output_encoding\": \"https://schema.org/encodingFormat\",\n        \"listen_ip\": \"https://schema.org/identifier\",\n        \"debug_endpoint\": \"https://schema.org/actionOption\",\n        \"echo_endpoint\": \"https://schema.org/actionOption\",\n        \"endpoints\": {\n          \"@id\": \"krakend:endpoints/\",\n          \"@type\": \"@id\"\n        },\n        \"tls\": {\n          \"@id\": \"krakend:service-settings/tls/\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"plugin\": {\n          \"@id\": \"krakend:extending/\",\n          \"@type\": \"@id\"\n        },\n        \"extra_config\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"Endpoint\": {\n      \"@id\": \"krakend:endpoints/\",\n      \"@context\": {\n        \"endpoint\": \"https://schema.org/urlTemplate\",\n        \"method\": \"https://schema.org/httpMethod\",\n        \"output_encoding\": \"https://schema.org/encodingFormat\",\n        \"concurrent_calls\": \"https://schema.org/repeatCount\",\n        \"timeout\": \"https://schema.org/duration\",\n        \"cache_ttl\": \"https://schema.org/duration\",\n        \"querystring_params\": \"https://schema.org/urlTemplate\",\n        \"headers_to_pass\": \"https://schema.org/httpMethod\",\n        \"backend\": {\n          \"@id\": \"krakend:backends/\",\n          \"@type\": \"@id\"\n        },\n        \"extra_config\": \"https://schema.org/additionalProperty\"\n\
  \      }\n    },\n    \"Backend\": {\n      \"@id\": \"krakend:backends/\",\n      \"@context\": {\n        \"host\": \"https://schema.org/hostingOrganization\",\n        \"url_pattern\": \"https://schema.org/urlTemplate\",\n        \"encoding\": \"https://schema.org/encodingFormat\",\n        \"sd\": \"https://schema.org/category\",\n        \"method\": \"https://schema.org/httpMethod\",\n        \"group\": \"https://schema.org/name\",\n        \"target\": \"https://schema.org/identifier\",\n        \"mapping\": \"https://schema.org/propertyID\",\n        \"allow\": \"https://schema.org/includesObject\",\n        \"deny\": \"https://schema.org/excludesObject\",\n        \"is_collection\": \"https://schema.org/actionOption\",\n        \"extra_config\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"TLS\": {\n      \"@id\": \"krakend:service-settings/tls/\",\n      \"@context\": {\n        \"public_key\": \"https://schema.org/text\",\n        \"private_key\": \"https://schema.org/text\"\
  ,\n        \"min_version\": \"https://schema.org/version\",\n        \"max_version\": \"https://schema.org/version\",\n        \"disabled\": \"https://schema.org/actionOption\",\n        \"enable_mtls\": \"https://schema.org/actionOption\",\n        \"ca_certs\": \"https://schema.org/text\"\n      }\n    },\n    \"Plugin\": {\n      \"@id\": \"krakend:extending/\",\n      \"@context\": {\n        \"pattern\": \"https://schema.org/identifier\",\n        \"folder\": \"https://schema.org/contentUrl\"\n      }\n    },\n    \"AsyncAgent\": {\n      \"@id\": \"krakend:async/\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"encoding\": \"https://schema.org/encodingFormat\",\n        \"backend\": {\n          \"@id\": \"krakend:backends/\",\n          \"@type\": \"@id\"\n        },\n        \"consumer\": \"https://schema.org/subscriber\",\n        \"connection\": \"https://schema.org/potentialAction\",\n        \"extra_config\": \"https://schema.org/additionalProperty\"\
  \n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/krakend/refs/heads/main/json-ld/krakend-context.jsonld
tags:
- Aggregation
- API Gateway
- Go
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
