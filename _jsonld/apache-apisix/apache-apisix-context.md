---
api_specs:
- filename: apache-apisix-admin-api-openapi.yml
  format: yaml
  label: Apache APISIX Admin API
  slug: apache-apisix-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-apisix/refs/heads/main/openapi/apache-apisix-admin-api-openapi.yml
- filename: apache-apisix-control-api-openapi.yml
  format: yaml
  label: Apache APISIX Control API
  slug: apache-apisix-control-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-apisix/refs/heads/main/openapi/apache-apisix-control-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/apache-apisix-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-apisix/refs/heads/main/json-ld/apache-apisix-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Apisix from Apache APISIX.
layout: jsonld
name: Apache Apisix Context
namespaces:
- prefix: apisix
  uri: https://apisix.apache.org/docs/apisix/terminology/
properties:
- container: ''
  name: Route
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: Upstream
  type: ''
- container: ''
  name: Consumer
  type: ''
- container: ''
  name: ConsumerGroup
  type: ''
- container: ''
  name: SSL
  type: ''
- container: ''
  name: GlobalRule
  type: ''
- container: ''
  name: PluginConfig
  type: ''
- container: ''
  name: StreamRoute
  type: ''
- container: ''
  name: Secret
  type: ''
property_count: 10
provider_name: Apache APISIX
provider_slug: apache-apisix
slug: apache-apisix-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"apisix\": \"https://apisix.apache.org/docs/apisix/terminology/\",\n    \"Route\": {\n      \"@id\": \"apisix:route\",\n      \"@context\": {\n        \"uri\": \"https://schema.org/urlTemplate\",\n        \"uris\": \"https://schema.org/urlTemplate\",\n        \"name\": \"https://schema.org/name\",\n        \"desc\": \"https://schema.org/description\",\n        \"host\": \"https://schema.org/hostingOrganization\",\n        \"hosts\": \"https://schema.org/hostingOrganization\",\n        \"methods\": \"https://schema.org/httpMethod\",\n        \"remote_addr\": \"https://schema.org/identifier\",\n        \"remote_addrs\": \"https://schema.org/identifier\",\n        \"priority\": \"https://schema.org/position\",\n        \"plugins\": \"https://schema.org/softwareRequirements\",\n        \"upstream\": {\n          \"@id\": \"apisix:upstream\",\n          \"@type\": \"@id\"\n        },\n        \"upstream_id\": {\n\
  \          \"@id\": \"apisix:upstream\",\n          \"@type\": \"@id\"\n        },\n        \"service_id\": {\n          \"@id\": \"apisix:service\",\n          \"@type\": \"@id\"\n        },\n        \"plugin_config_id\": {\n          \"@id\": \"apisix:plugin-config\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"https://schema.org/keywords\",\n        \"status\": \"https://schema.org/status\",\n        \"enable_websocket\": \"https://schema.org/actionOption\"\n      }\n    },\n    \"Service\": {\n      \"@id\": \"apisix:service\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"desc\": \"https://schema.org/description\",\n        \"plugins\": \"https://schema.org/softwareRequirements\",\n        \"upstream\": {\n          \"@id\": \"apisix:upstream\",\n          \"@type\": \"@id\"\n        },\n        \"upstream_id\": {\n          \"@id\": \"apisix:upstream\",\n          \"@type\": \"@id\"\n        },\n        \"labels\": \"https://schema.org/keywords\"\
  ,\n        \"enable_websocket\": \"https://schema.org/actionOption\",\n        \"hosts\": \"https://schema.org/hostingOrganization\"\n      }\n    },\n    \"Upstream\": {\n      \"@id\": \"apisix:upstream\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"desc\": \"https://schema.org/description\",\n        \"type\": \"https://schema.org/category\",\n        \"nodes\": \"https://schema.org/hasPart\",\n        \"service_name\": \"https://schema.org/name\",\n        \"discovery_type\": \"https://schema.org/category\",\n        \"scheme\": \"https://schema.org/urlTemplate\",\n        \"pass_host\": \"https://schema.org/actionOption\",\n        \"upstream_host\": \"https://schema.org/hostingOrganization\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"retries\": \"https://schema.org/repeatCount\",\n        \"retry_timeout\": \"https://schema.org/duration\"\n      }\n    },\n    \"Consumer\": {\n      \"@id\": \"apisix:consumer\",\n     \
  \ \"@context\": {\n        \"username\": \"https://schema.org/identifier\",\n        \"desc\": \"https://schema.org/description\",\n        \"plugins\": \"https://schema.org/softwareRequirements\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"group_id\": {\n          \"@id\": \"apisix:consumer-group\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"ConsumerGroup\": {\n      \"@id\": \"apisix:consumer-group\",\n      \"@context\": {\n        \"desc\": \"https://schema.org/description\",\n        \"plugins\": \"https://schema.org/softwareRequirements\",\n        \"labels\": \"https://schema.org/keywords\"\n      }\n    },\n    \"SSL\": {\n      \"@id\": \"apisix:ssl\",\n      \"@context\": {\n        \"cert\": \"https://schema.org/text\",\n        \"key\": \"https://schema.org/text\",\n        \"snis\": \"https://schema.org/identifier\",\n        \"labels\": \"https://schema.org/keywords\",\n        \"status\": \"https://schema.org/status\",\n      \
  \  \"type\": \"https://schema.org/category\"\n      }\n    },\n    \"GlobalRule\": {\n      \"@id\": \"apisix:global-rule\",\n      \"@context\": {\n        \"plugins\": \"https://schema.org/softwareRequirements\"\n      }\n    },\n    \"PluginConfig\": {\n      \"@id\": \"apisix:plugin-config\",\n      \"@context\": {\n        \"desc\": \"https://schema.org/description\",\n        \"plugins\": \"https://schema.org/softwareRequirements\",\n        \"labels\": \"https://schema.org/keywords\"\n      }\n    },\n    \"StreamRoute\": {\n      \"@id\": \"apisix:stream-route\",\n      \"@context\": {\n        \"desc\": \"https://schema.org/description\",\n        \"remote_addr\": \"https://schema.org/identifier\",\n        \"server_addr\": \"https://schema.org/identifier\",\n        \"server_port\": \"https://schema.org/identifier\",\n        \"sni\": \"https://schema.org/identifier\",\n        \"plugins\": \"https://schema.org/softwareRequirements\",\n        \"upstream\": {\n          \"@id\"\
  : \"apisix:upstream\",\n          \"@type\": \"@id\"\n        },\n        \"upstream_id\": {\n          \"@id\": \"apisix:upstream\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Secret\": {\n      \"@id\": \"apisix:secret\",\n      \"@context\": {\n        \"uri\": \"https://schema.org/url\",\n        \"prefix\": \"https://schema.org/identifier\",\n        \"token\": \"https://schema.org/accessCode\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-apisix/refs/heads/main/json-ld/apache-apisix-context.jsonld
tags:
- Apache
- API Gateway
- Cloud Native
- Kubernetes
- Lua
- NGINX
- Open Source
- Traffic Management
- JSON-LD
- Linked Data
- Semantic Web
---
