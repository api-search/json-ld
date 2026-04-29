---
api_specs:
- filename: kong-gateway-admin-api.yml
  format: yaml
  label: Kong Gateway Admin API
  slug: kong-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/openapi/kong-gateway-admin-api.yml
class_count: 2
classes:
- id
- type
context_file: json-ld/kong-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/json-ld/kong-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kong from Kong.
layout: jsonld
name: Kong Context
namespaces:
- prefix: kong
  uri: https://docs.konghq.com/gateway/latest/admin-api/#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Service
  type: ''
- container: ''
  name: Route
  type: ''
- container: ''
  name: Consumer
  type: ''
- container: ''
  name: Plugin
  type: ''
- container: ''
  name: Upstream
  type: ''
- container: ''
  name: Target
  type: ''
- container: ''
  name: Certificate
  type: ''
property_count: 7
provider_name: Kong
provider_slug: kong
slug: kong-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"kong\": \"https://docs.konghq.com/gateway/latest/admin-api/#\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"Service\": {\n      \"@id\": \"kong:service-object\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"protocol\": {\n          \"@id\": \"kong:service-protocol\",\n          \"@type\": \"xsd:string\"\n        },\n        \"host\": {\n          \"@id\": \"kong:service-host\",\n          \"@type\": \"xsd:string\"\n        },\n        \"port\": {\n          \"@id\": \"kong:service-port\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"path\": {\n          \"@id\": \"kong:service-path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"retries\": {\n          \"@id\": \"kong:service-retries\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"connect_timeout\"\
  : {\n          \"@id\": \"kong:service-connect-timeout\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"write_timeout\": {\n          \"@id\": \"kong:service-write-timeout\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"read_timeout\": {\n          \"@id\": \"kong:service-read-timeout\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"enabled\": {\n          \"@id\": \"kong:service-enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"tls_verify\": {\n          \"@id\": \"kong:service-tls-verify\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"tls_verify_depth\": {\n          \"@id\": \"kong:service-tls-verify-depth\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ca_certificates\": {\n    \
  \      \"@id\": \"kong:service-ca-certificates\",\n          \"@container\": \"@set\"\n        },\n        \"client_certificate\": {\n          \"@id\": \"kong:service-client-certificate\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Route\": {\n      \"@id\": \"kong:route-object\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"protocols\": {\n          \"@id\": \"kong:route-protocols\",\n          \"@container\": \"@set\"\n        },\n        \"methods\": {\n          \"@id\": \"kong:route-methods\",\n          \"@container\": \"@set\"\n        },\n        \"hosts\": {\n          \"@id\": \"kong:route-hosts\",\n          \"@container\": \"@set\"\n   \
  \     },\n        \"paths\": {\n          \"@id\": \"kong:route-paths\",\n          \"@container\": \"@set\"\n        },\n        \"headers\": {\n          \"@id\": \"kong:route-headers\"\n        },\n        \"snis\": {\n          \"@id\": \"kong:route-snis\",\n          \"@container\": \"@set\"\n        },\n        \"sources\": {\n          \"@id\": \"kong:route-sources\",\n          \"@container\": \"@set\"\n        },\n        \"destinations\": {\n          \"@id\": \"kong:route-destinations\",\n          \"@container\": \"@set\"\n        },\n        \"strip_path\": {\n          \"@id\": \"kong:route-strip-path\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"preserve_host\": {\n          \"@id\": \"kong:route-preserve-host\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"regex_priority\": {\n          \"@id\": \"kong:route-regex-priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"https_redirect_status_code\": {\n          \"@id\"\
  : \"kong:route-https-redirect-status-code\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"path_handling\": {\n          \"@id\": \"kong:route-path-handling\",\n          \"@type\": \"xsd:string\"\n        },\n        \"request_buffering\": {\n          \"@id\": \"kong:route-request-buffering\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"response_buffering\": {\n          \"@id\": \"kong:route-response-buffering\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"expression\": {\n          \"@id\": \"kong:route-expression\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priority\": {\n          \"@id\": \"kong:route-priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"service\": {\n          \"@id\": \"kong:route-service\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n      \
  \    \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Consumer\": {\n      \"@id\": \"kong:consumer-object\",\n      \"@context\": {\n        \"username\": {\n          \"@id\": \"kong:consumer-username\",\n          \"@type\": \"xsd:string\"\n        },\n        \"custom_id\": {\n          \"@id\": \"kong:consumer-custom-id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Plugin\": {\n      \"@id\": \"kong:plugin-object\",\n      \"\
  @context\": {\n        \"name\": \"schema:name\",\n        \"instance_name\": {\n          \"@id\": \"kong:plugin-instance-name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"config\": {\n          \"@id\": \"kong:plugin-config\"\n        },\n        \"protocols\": {\n          \"@id\": \"kong:plugin-protocols\",\n          \"@container\": \"@set\"\n        },\n        \"enabled\": {\n          \"@id\": \"kong:plugin-enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"ordering\": {\n          \"@id\": \"kong:plugin-ordering\"\n        },\n        \"service\": {\n          \"@id\": \"kong:plugin-service\",\n          \"@type\": \"@id\"\n        },\n        \"route\": {\n          \"@id\": \"kong:plugin-route\",\n          \"@type\": \"@id\"\n        },\n        \"consumer\": {\n          \"@id\": \"kong:plugin-consumer\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"consumer_group\": {\n          \"@id\": \"kong:plugin-consumer-group\",\n          \"@type\": \"@id\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Upstream\": {\n      \"@id\": \"kong:upstream-object\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"algorithm\": {\n          \"@id\": \"kong:upstream-algorithm\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hash_on\": {\n          \"@id\": \"kong:upstream-hash-on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hash_fallback\": {\n          \"@id\": \"kong:upstream-hash-fallback\",\n          \"@type\": \"xsd:string\"\n        },\n        \"slots\": {\n          \"@id\": \"kong:upstream-slots\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"healthchecks\": {\n          \"@id\": \"kong:upstream-healthchecks\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Target\": {\n      \"@id\": \"kong:target-object\",\n      \"@context\": {\n        \"target\": {\n          \"@id\": \"kong:target-address\",\n          \"@type\": \"xsd:string\"\n        },\n        \"weight\": {\n          \"@id\": \"kong:target-weight\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"upstream\": {\n          \"@id\": \"kong:target-upstream\",\n          \"@type\": \"@id\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\
  \n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Certificate\": {\n      \"@id\": \"kong:certificate-object\",\n      \"@context\": {\n        \"cert\": {\n          \"@id\": \"kong:certificate-cert\",\n          \"@type\": \"xsd:string\"\n        },\n        \"key\": {\n          \"@id\": \"kong:certificate-key\",\n          \"@type\": \"xsd:string\"\n        },\n        \"snis\": {\n          \"@id\": \"kong:certificate-snis\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"created_at\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updated_at\": {\n          \"@id\": \"schema:dateModified\"\
  ,\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kong/refs/heads/main/json-ld/kong-context.jsonld
tags:
- API Gateway
- Lua
- NGINX
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
