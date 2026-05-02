---
api_specs:
- filename: microsoft-azure-api-management-rest-api-openapi.yaml
  format: yaml
  label: Azure API Management REST API
  slug: azure-api-management-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-rest-api-openapi.yaml
- filename: microsoft-azure-api-management-gateway-openapi.yaml
  format: yaml
  label: Azure API Management Gateway
  slug: azure-api-management-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-gateway-openapi.yaml
- filename: microsoft-azure-api-management-self-hosted-gateway-openapi.yaml
  format: yaml
  label: Azure API Management Self-Hosted Gateway
  slug: azure-api-management-self-hosted-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-self-hosted-gateway-openapi.yaml
- filename: microsoft-azure-api-management-ai-gateway-openapi.yaml
  format: yaml
  label: Azure API Management AI Gateway
  slug: azure-api-management-ai-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-ai-gateway-openapi.yaml
- filename: microsoft-azure-api-management-developer-portal-openapi.yaml
  format: yaml
  label: Azure API Management Developer Portal
  slug: azure-api-management-developer-portal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/openapi/microsoft-azure-api-management-developer-portal-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/microsoft-azure-api-management-ai-gateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/json-ld/microsoft-azure-api-management-ai-gateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Azure Api Management Ai Gateway from Microsoft Azure API Management.
layout: jsonld
name: Microsoft Azure Api Management Ai Gateway Context
namespaces:
- prefix: pan
  uri: https://schemas.providerapis.net/microsoft-azure-api-management/ai-gateway#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ChatCompletionRequest
  type: ''
- container: ''
  name: ChatCompletionResponse
  type: ''
- container: ''
  name: CompletionRequest
  type: ''
- container: ''
  name: CompletionResponse
  type: ''
- container: ''
  name: EmbeddingRequest
  type: ''
- container: ''
  name: EmbeddingResponse
  type: ''
- container: ''
  name: MCPRequest
  type: ''
- container: ''
  name: MCPResponse
  type: ''
property_count: 8
provider_name: Microsoft Azure API Management
provider_slug: microsoft-azure-api-management
slug: microsoft-azure-api-management-ai-gateway-context
source_filename: microsoft-azure-api-management-ai-gateway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"pan\": \"https://schemas.providerapis.net/microsoft-azure-api-management/ai-gateway#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ChatCompletionRequest\": {\n      \"@id\": \"pan:ChatCompletionRequest\",\n      \"@context\": {\n        \"messages\": {\n          \"@id\": \"pan:messages\",\n          \"@container\": \"@list\"\n        },\n        \"role\": {\n          \"@id\": \"pan:role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"pan:content\",\n          \"@type\": \"xsd:string\"\n        },\n        \"max_tokens\": {\n          \"@id\": \"pan:max_tokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"temperature\": {\n          \"@id\": \"pan:temperature\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"ChatCompletionResponse\": {\n     \
  \ \"@id\": \"pan:ChatCompletionResponse\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"pan:object\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"model\": {\n          \"@id\": \"pan:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"choices\": {\n          \"@id\": \"pan:choices\",\n          \"@container\": \"@list\"\n        },\n        \"index\": {\n          \"@id\": \"pan:index\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"pan:message\"\n        },\n        \"finish_reason\": {\n          \"@id\": \"pan:finish_reason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usage\": {\n          \"@id\": \"pan:usage\"\n        },\n        \"prompt_tokens\"\
  : {\n          \"@id\": \"pan:prompt_tokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"completion_tokens\": {\n          \"@id\": \"pan:completion_tokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_tokens\": {\n          \"@id\": \"pan:total_tokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"CompletionRequest\": {\n      \"@id\": \"pan:CompletionRequest\",\n      \"@context\": {\n        \"prompt\": {\n          \"@id\": \"pan:prompt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"max_tokens\": {\n          \"@id\": \"pan:max_tokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"temperature\": {\n          \"@id\": \"pan:temperature\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"CompletionResponse\": {\n      \"@id\": \"pan:CompletionResponse\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"pan:object\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"model\": {\n          \"@id\": \"pan:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"choices\": {\n          \"@id\": \"pan:choices\",\n          \"@container\": \"@list\"\n        },\n        \"index\": {\n          \"@id\": \"pan:index\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"text\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"finish_reason\": {\n          \"@id\": \"pan:finish_reason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usage\": {\n          \"@id\": \"pan:usage\"\n        },\n        \"prompt_tokens\": {\n          \"@id\": \"pan:prompt_tokens\",\n          \"@type\": \"xsd:integer\"\n        },\n   \
  \     \"completion_tokens\": {\n          \"@id\": \"pan:completion_tokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_tokens\": {\n          \"@id\": \"pan:total_tokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"EmbeddingRequest\": {\n      \"@id\": \"pan:EmbeddingRequest\",\n      \"@context\": {\n        \"input\": {\n          \"@id\": \"pan:input\",\n          \"@type\": \"xsd:string\"\n        },\n        \"model\": {\n          \"@id\": \"pan:model\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"EmbeddingResponse\": {\n      \"@id\": \"pan:EmbeddingResponse\",\n      \"@context\": {\n        \"object\": {\n          \"@id\": \"pan:object\",\n          \"@type\": \"xsd:string\"\n        },\n        \"data\": {\n          \"@id\": \"pan:data\",\n          \"@container\": \"@list\"\n        },\n        \"index\": {\n          \"@id\": \"pan:index\",\n          \"@type\": \"xsd:integer\"\n    \
  \    },\n        \"embedding\": {\n          \"@id\": \"pan:embedding\",\n          \"@container\": \"@list\"\n        },\n        \"model\": {\n          \"@id\": \"pan:model\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usage\": {\n          \"@id\": \"pan:usage\"\n        },\n        \"prompt_tokens\": {\n          \"@id\": \"pan:prompt_tokens\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"total_tokens\": {\n          \"@id\": \"pan:total_tokens\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"MCPRequest\": {\n      \"@id\": \"pan:MCPRequest\",\n      \"@context\": {\n        \"jsonrpc\": {\n          \"@id\": \"pan:jsonrpc\",\n          \"@type\": \"xsd:string\"\n        },\n        \"method\": {\n          \"@id\": \"pan:method\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"params\": {\n     \
  \     \"@id\": \"pan:params\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"arguments\": {\n          \"@id\": \"pan:arguments\"\n        }\n      }\n    },\n\n    \"MCPResponse\": {\n      \"@id\": \"pan:MCPResponse\",\n      \"@context\": {\n        \"jsonrpc\": {\n          \"@id\": \"pan:jsonrpc\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"result\": {\n          \"@id\": \"pan:result\"\n        },\n        \"content\": {\n          \"@id\": \"pan:content\",\n          \"@container\": \"@list\"\n        },\n        \"type\": {\n          \"@id\": \"pan:contentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"text\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-api-management/refs/heads/main/json-ld/microsoft-azure-api-management-ai-gateway-context.jsonld
tags:
- AI Gateway
- API Gateway
- API Management
- Enterprise
- Microsoft Azure
- JSON-LD
- Linked Data
- Semantic Web
---
