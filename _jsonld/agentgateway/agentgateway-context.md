---
class_count: 5
classes:
- LLMBackend
- MCPTarget
- Route
- name
- description
context_file: json-ld/agentgateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agentgateway/refs/heads/main/json-ld/agentgateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agentgateway from AgentGateway.
layout: jsonld
name: Agentgateway Context
namespaces:
- prefix: agw
  uri: https://agentgateway.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: provider
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: alias
  type: string
- container: ''
  name: baseUrl
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: authentication
  type: reference
- container: ''
  name: secretRef
  type: string
- container: ''
  name: tokenRef
  type: string
- container: ''
  name: weight
  type: integer
- container: ''
  name: priority
  type: integer
- container: set
  name: tools
  type: string
- container: set
  name: allowedClients
  type: string
- container: ''
  name: backend
  type: string
- container: set
  name: matches
  type: reference
- container: ''
  name: rateLimit
  type: reference
- container: ''
  name: retries
  type: reference
- container: ''
  name: requestsPerSecond
  type: integer
- container: ''
  name: burstSize
  type: integer
- container: ''
  name: attempts
  type: integer
- container: ''
  name: perTryTimeout
  type: string
property_count: 21
provider_name: AgentGateway
provider_slug: agentgateway
slug: agentgateway-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agw\": \"https://agentgateway.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"LLMBackend\": \"agw:LLMBackend\",\n    \"MCPTarget\": \"agw:MCPTarget\",\n    \"Route\": \"agw:Route\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n\n    \"provider\": {\n      \"@id\": \"agw:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"agw:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alias\": {\n      \"@id\": \"agw:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"agw:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authentication\"\
  : {\n      \"@id\": \"agw:authentication\",\n      \"@type\": \"@id\"\n    },\n    \"secretRef\": {\n      \"@id\": \"agw:secret_ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenRef\": {\n      \"@id\": \"agw:token_ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"agw:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"priority\": {\n      \"@id\": \"agw:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tools\": {\n      \"@id\": \"agw:tools\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowedClients\": {\n      \"@id\": \"agw:allowed_clients\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backend\": {\n      \"@id\": \"agw:backend\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matches\": {\n      \"@id\": \"agw:matches\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"rateLimit\": {\n      \"@id\": \"agw:rate_limit\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"retries\": {\n      \"@id\": \"agw:retries\",\n      \"@type\": \"@id\"\n    },\n    \"requestsPerSecond\": {\n      \"@id\": \"agw:requests_per_second\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"burstSize\": {\n      \"@id\": \"agw:burst_size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attempts\": {\n      \"@id\": \"agw:attempts\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"perTryTimeout\": {\n      \"@id\": \"agw:per_try_timeout\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agentgateway/refs/heads/main/json-ld/agentgateway-context.jsonld
tags:
- AI Gateway
- API Gateway
- MCP
- LLM
- Agent-to-Agent
- Open Source
- CNCF
- Observability
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
